# Open Path WordPress Knowledge Base

This package is prepared for WebberZone Knowledge Base Pro GitHub ingestion.

## WebberZone mapping

- Map the repository folder `docs/articles`.
- Enable recursive scanning.
- Enable **Import external media** so repository images are copied into the WordPress Media Library.
- Keep the mapping's article-status override unset so each file's `status: draft` value is respected.
- Run the initial import and review the articles in WordPress before changing their status to `publish`.

Only article Markdown lives below `docs/articles`, so section metadata and project documentation will not be imported as knowledge-base articles.

## Package structure

- `docs/articles/` — 35 knowledge-base articles imported by WebberZone.
- `docs/assets/images/` — repository-owned screenshots referenced by the articles.
- `taxonomy/sections.yml` — proposed navigation hierarchy and section descriptions for WordPress setup; it is intentionally outside the mapped folder.
- `news/release-notes.md` — release notes kept outside the procedural knowledge-base import. Map or publish this separately if release notes should appear in WordPress.

## Publishing workflow

1. Edit Markdown and images in this repository.
2. Review the changes in a pull request.
3. Merge to the branch connected to WebberZone.
4. Let the GitHub webhook update WordPress.
5. Treat GitHub as the source of truth; avoid editing synchronized article content directly in WordPress.

:) 
