---
title: "Manage Access Controls"
slug: manage-access-controls
products: [[Open Path]]
sections: [[Administration/Users & Access]]
tags: [[administration, users, access]]
status: draft
order: 5
toc: true
---

Access controls connect the three pieces that determine a user's access: user group, role, and collection.

The user group defines who the access applies to. The role defines what those users are allowed to do. The collection defines which data they can access.

For example, an access control might say that the **Data Analysts** user group has the **Data Analyst** role for the **All HMIS Projects** collection — meaning users in the Data Analysts group can use the permissions included in the Data Analyst role across all data in that collection. Another access control might say that the **Project Admins** user group has the **Program Manager** role for a smaller collection, such as a few specific projects or one organization — in that case, users may be able to manage enrollments or update project information, but only within that limited set of data.

Access controls are what make the full access setup work. A user does not receive permissions just because a role exists, and they do not receive data access just because a collection exists. The access control combines them so the system knows which users get which permissions for which data.

## Open Access Controls

1. Open **HMIS Admin** in the right sidebar, then click **Access Controls**.

## Create an Access Control

1. Click **Create a New Control**.
2. Select the role. The role defines what users are allowed to do.
3. Select the collection. The collection defines which data users can access.
4. Select the user group. The user group defines who the access applies to.
5. After selecting the role, collection, and user group, click **Create Access Control List**.

## Edit an Access Control

1. Click **Edit** on the row for the access control you want to update.

> [[!NOTE]]
> Clicking the linked user group, role, or collection in the row will take you to that item's settings page instead of editing the access control directly.

2. Make your changes, then click **Update Access Control**.

## Delete an Access Control

1. Find the access control you want to remove, then click **Delete** at the end of the table row.
2. Confirm the deletion in the browser confirmation window.
3. After the access control is deleted, a confirmation message appears at the top of the page.
