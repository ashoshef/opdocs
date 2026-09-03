---
title: "Use the Form Builder"
slug: form-builder
products: [[Open Path]]
sections: [[Administration/Forms & Assessments]]
tags: [[administration, forms, assessments]]
status: draft
order: 1
toc: true
---

The form builder is used in the HMIS admin to create custom assessments and to create custom services.

## Page Structure

1. The pencil icon next to the form title allows you to edit the form title.
2. The **Preview / Publish** button opens a preview of the form and allows the form to be published.
3. The trash can icon next to the Preview / Publish button deletes the current draft only, not the entire assessment.
4. The vertical sticky toolbar on the right side of the page contains the available form items that can be added to the form.
5. A highlighted row such as **Group: Basic Information** is a grouped form item row, identified by the dropdown arrow on the left side and the gray outline surrounding the grouped items.
6. The vertical three-dot menu on a form row opens options to edit the individual row.
7. The up and down arrow controls move a form row higher or lower in the form. A group row cannot be deleted until all items inside the group have been removed.

## Form Items

**Layout** — organize and structure the form for easier navigation and readability.
- **Group (Section)** — creates a collapsible section that groups related form items together.
- **Display Text** — adds informational text, instructions, or headings that users can read but cannot edit.

**Text Inputs**
- **Short Text** — a single line of text, such as a name, ID number, or brief response.
- **Long Text** — longer responses across multiple lines.

**Numeric**
- **Number** — accepts numeric values only.
- **Currency** — monetary values formatted as currency.

**Date & Time**
- **Date** — select a calendar date.
- **Time** — select or enter a time value.

**Selection**
- **Checkbox** — select one or more options from a list.
- **Multiple Choice** — select a single option from multiple choices.
- **Dropdown** — a collapsible list of options to select from.

**Uploads**
- **Image Upload** — upload image files directly into the form.
- **File Upload** — upload documents or other file types.

## Form Item Editor

Used to configure the behavior, appearance, validation rules, and visibility settings for an individual form item.

**Properties**
- **Assessment Date** — when enabled, the selected date is saved as the official assessment date for the record.
- **Response Validation** — Required prevents submission without a response; Warn If Empty allows blank with a warning; Optional allows skipping without a warning; Read-Only displays the field without allowing edits.
- **Label** — the primary question or field name shown to users.
- **Helper Text** — additional instructions shown beneath the label.
- **Brief Label** — a shortened version of the label for Autofill dialogs or condensed views.
- **Label for Read-Only View** — the label shown in read-only mode (defaults to the standard label if blank).
- **Input Size** — controls the visual width of the field on the form.

**Visibility**
- **Client Applicability** — limits the item to specific clients; shown for all clients if left blank.
- **Always Hide This Item** — prevents the item from being displayed.
- **Conditional Behavior (AND/OR)** — AND requires all conditions to be met; OR displays the item when any condition is met.
- **Dependent Question** / **Operator** / **Add Condition** — define the question, comparison, and additional visibility rules.

**Disabled Display** — Hidden removes the item from view; Protected displays it without allowing interaction; Protected with Value displays the item and its value while preventing edits.

**Min/Max Bounds** — validation rules restricting acceptable values, with a Bound Type (minimum or maximum), Severity (warning or error), and Maximum Date where applicable.

**Advanced Properties**
- **Question ID** — the unique identifier for the form item. Must begin with a letter and contain only letters, numbers, and underscores.
