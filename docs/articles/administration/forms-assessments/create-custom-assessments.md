---
title: "Create Custom Assessments"
slug: create-custom-assessments
products: [[Open Path]]
sections: [[Administration/Forms & Assessments]]
tags: [[administration, forms, assessments]]
status: draft
order: 2
toc: true
---

Create custom assessments for use in HMIS projects, publish them, and configure the rules that control where they appear.

> [[!NOTE]]
> HUD-required forms cannot be customized by end users due to HUD compliance requirements. If a HUD form requires customization, submit a support request so the changes can be created in the backend.

## Create a Custom Assessment

1. Navigate to **Forms** in the Admin menu. Admin permissions are required.
2. Click **+ New Form**.
3. Review the available form types. Forms can be created as either services or custom assessments.
4. Select **Custom Assessment** as the form type, complete the required fields, and click **Save**.

## Build the Assessment Form

1. Use the form builder to create your custom assessment fields and layout. See [Use the Form Builder](form-builder.md) for details.

## Publish the Assessment

1. Once the form is complete, click **Preview / Publish**. To discard the current draft, click the delete icon next to the Preview / Publish button.
2. Click **Publish** to make the assessment available for use.

## Configure Form Applicability

1. Under **Form Applicability**, click **+ New Rule**.
2. Configure the condition type and rules, then click **Create Rule**.
3. Once the form is published and rules are applied, the custom assessment can be added to clients in applicable projects.

## Deactivate a Custom Assessment

> [[!NOTE]]
> Custom assessments cannot be permanently deleted. To stop an assessment from appearing in HMIS projects, remove all applicability rules.

1. Delete the applicability rules you no longer want associated with the assessment.
2. After all rules are removed, the assessment will no longer appear in projects.
