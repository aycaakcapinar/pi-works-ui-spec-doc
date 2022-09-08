---
layout: post
title: "UI specification document"
date: 2022-09-08 11:18:39 +0300
categories: jekyll update
---

This document is written for user management screen.

**Requirements:**

- When users open the page, they will see the interface containing the user information table.
- This interface also includes different actions which are adding a new user, saving a user, and hiding or showing disabled users.

> Top of the page, there will be three actions as below.

- When a user clicks the `+New User` button, the add **new user** form will open.
- With the help of the `Hide disabled User` checkbox, users will be able not to see disabled users in the table.
- When a user clicks the `Save User` button, user information in the form will be saved in the database and according to the **enabled** status, it will be shown in the table.
  Also, if saving is successful, the form will be reset.

{% include button.html %}

<br>

> Make sure that your new user form will look like that:

{% include form.html %}

<br>

> Make sure that your table will look like that:

| ID  | User Name | Email                | Enabled |
| --- | --------- | -------------------- | ------- |
| 1   | AdminUser | admin@piworks.net    | true    |
| 2   | Test User | testuser@piworks.net | true    |
