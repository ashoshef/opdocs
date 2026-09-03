---
title: "Manage Data Access Collections"
slug: manage-data-access-collections
products: [[Open Path]]
sections: [[Administration/Users & Access]]
tags: [[administration, users, access]]
status: draft
order: 4
toc: true
---

Collections define which data a group of users can access. If roles and permissions control what users can do, collections control where they can do it.

For example, a role might allow someone to view reports or manage enrollments, but the collection determines whether they can do that for all projects, one organization, a specific project, or a smaller project group.

A collection could be broad, such as **All HMIS Projects**, which gives assigned users access to data across every HMIS project included in that collection. A collection could also be more limited, such as **Downtown Outreach Projects**, for users who should only access data related to a specific group of outreach programs. A third example could be **Shelter Programs Only**, for users who need access to emergency shelter project data but should not be able to view data from permanent housing, outreach, or prevention programs.

Collections help administrators keep access scoped to the right data. A user may have the right permissions to view or manage information, but they should only be able to use those permissions within the collections assigned through access controls.

## Open Collections

1. Open **HMIS Admin** in the right sidebar, then click **Collections**.

## Create a Collection

1. Click **Add a Collection**.
2. Enter a collection name and description, then click **Create Collection**.

## Manage Data in a Collection

When you manage a collection, you are deciding which data should be included in that collection. You can add data in a few different ways:

- **Data Sources** — add a full data source if users should access a broad set of data from that source.
- **Organizations** — add one or more organizations if users should access data connected to those organizations.
- **Projects** — add specific projects if users should only access data from certain programs.
- **Project Groups** — add a project group if users should access a predefined set of related projects.

The collection does not decide what the user can do with the data — it only decides which data is available to them. Their role and permissions decide whether they can view, edit, report on, or manage that data.

1. Select **Add/Remove** on the Data Sources, Organizations, Projects, or Project Groups card you want to update.
2. In the modal, select the items you want to include in the collection and clear any items you want to remove.
3. Click **Save** to save your changes.
4. Review the number of projects included in the collection based on your selections.

> [[!NOTE]]
> If a project is already included through another selection, an alert will show that the project has been duplicated. This does not change the level of access in the collection.

## View Data Access Audit History

1. Click **History** in the upper-right corner of the page to review changes made to the collection.
2. Review changes in the audit history table, or click **Export CSV** to download the history.

## Delete a Collection

1. If your account has permission to delete collections, click **Delete** next to the collection you want to remove.
2. Confirm the deletion in the browser confirmation window.

Once a collection exists, see [Manage Access Controls](manage-access-controls.md) to combine it with a user group and a role.
