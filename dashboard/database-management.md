# Database Tables

**Last verified:** 2026-10-27 11:40am

The **Database Tables** section (in your site menu, under **Settings**) is where you define the structure of your own custom content types. Think of it as creating a spreadsheet -- you choose what columns it has, what kind of information each column holds, and how different tables relate to each other.

This is different from the built-in content modules (like Articles or Events) that come ready to use. Database Tables lets you create something entirely new that is specific to your needs.

---

## When Would You Use This?

Most of the time, the built-in content modules will cover what you need. But sometimes your site requires a type of content that does not exist yet. Here are a few examples:

- A **team directory** with custom fields like department, phone number, and bio
- A **portfolio** with project descriptions, categories, and client names
- A **product catalog** with specifications, pricing tiers, and availability
- A **testimonials** collection with customer names, quotes, and ratings
- A **FAQ list** with questions, answers, and categories

If you can imagine it as a spreadsheet with rows and columns, you can build it as a database table.

---

## Viewing Your Tables

1. Open your WebNesting dashboard.
2. In the site menu, open **Settings** and click **Database Tables**.
3. You will see the **Database Tables** list. It shows the tables you created and the tables that came with your site.

Each table in the list shows its name, a short line about what it holds, and how many columns it has. Click a table, or its **Columns** button, to see its columns.

![The Database Tables page listing available tables with their descriptions](../images/dashboard/database-tables.png)

> **Tip:** If you do not see **Database Tables** in your menu, you may need to ask your site administrator to grant you permission.

---

## Creating a New Table

Setting up a new table is straightforward. You will give it a name and some basic information, then add the columns (fields) that define what kind of data it holds.

### Step 1 -- Name Your Table

1. Go to **Settings → Database Tables** in your site menu.
2. Select **+ Create Table**.
3. Fill in the following:
   - **Display Name** -- A friendly name for your table. This is what you will see in menus and lists. For example, "Team Members" or "Client Testimonials."
   - **Description** -- A short note about what this table is for. This is optional but helpful if you have many tables.
   - **Parent table** -- Use this when entries belong under another table -- for example, "Chapters" under "Books", or "Team Members" under "Departments". For most tables, leave this set to "None." If you pick one and change your mind, click the small **x** on the field to clear it.
   - **Advanced → Internal name** -- You can leave this alone. It is generated from the display name and used behind the scenes (in code and the API). It can only contain letters and numbers, and it can't be changed after the table is created.
4. Click **Create Table**.

After creating the table, you will be taken to the columns page where you can start adding fields.

> **Tip:** Choose a clear and descriptive display name. This name will appear in your dashboard menus, so "Team Members" is much better than "TM Data" or "Table 3."

---

## Adding Columns (Fields)

Columns define what information each entry in your table contains. For example, a "Team Members" table might have columns for Name, Job Title, Email, Photo, and Bio.

### How to Add a Column

1. Open your table from the **Database Tables** list.
2. You see the table's **Columns** page with all existing columns.
3. Click **+ Add Column**. A **New Column** form opens.
4. Fill in the details for your new column (described below).
5. Click **Create Column** when you are done.

### Column Settings

Each column has several settings you can configure:

- **Display Name** -- The label that appears when adding or editing entries. For example, "Job Title" or "Phone Number."
- **Field Name** -- The internal name used by the system. This is generated automatically from the display name using lowercase letters, numbers and underscores.
- **Type** -- The kind of data this column holds (see "Column Types" below).
- **Default Value** -- A value that is filled in automatically when creating a new entry. Leave blank if you do not need a default.
- **Multiple** -- Check this box if the column should accept more than one value. For example, a "Tags" column might allow multiple selections.
- **Required** -- Check this box if every entry must have a value for this column. If checked, you will not be able to save an entry without filling in this field.
- **Unique** -- Check this box if no two entries can have the same value in this column. Useful for things like email addresses or employee IDs. If you mark a column as Unique, the system will prevent you from saving an entry with a duplicate value in that column.
- **Show in List** -- Check this box if you want this column's value to appear when browsing entries in a list view.

### Column Types Explained

When adding a column, you choose the type of data it will hold. Here is what each type means in plain terms:

**Text types:**

- **Text** -- A single line of text. Good for names, titles, short labels, and any brief piece of information.
- **Textarea** -- A larger text area for longer content. Good for descriptions, notes, or summaries.
- **Rich Text (WYSIWYG)** -- A rich text field with formatting options like bold, italic, links, and lists. Best for content that needs formatting, like bios or detailed descriptions.
- **Markdown** -- A text field that uses Markdown formatting. Similar to rich text, but uses a different writing style.
- **Email** -- An email address.

**Image:**

- **Image (Single)** -- Lets you attach one picture from your files. Perfect for profile photos, product images, or logos.
- **Image (Multiple)** -- Lets you attach several pictures, such as a gallery.

**Choice:**

- **Select Dropdown** -- Pick one value from a dropdown list.
- **Radio Buttons** -- Pick one value from a short list shown all at once.
- **Checkbox** -- A yes-or-no box.

**Date and time types:**

- **Date** -- A calendar date, like a birthday or event date.
- **Date & Time** -- A date and time together, like a meeting scheduled for a specific hour.
- **Timestamp** -- A precise moment in time. Useful for tracking when something happened.
- **Time** -- Just a time of day, without a date.
- **Year** -- Just a year, like 2025.

**Number:**

- **Number** -- A numeric value. Good for quantities, prices, ratings, or any countable item.

**Relationship:**

- **Relationship** -- Links this column to another table. See "Setting Up Relationships" below for details.

> **Tip:** If you are unsure which type to choose, "Text" works for most simple fields. You can always adjust your table structure later.

---

## Reordering Columns

Columns appear in the order you add them. To change the order:

- **With the mouse:** drag a column by the grip on its left (the six dots) and drop it on another column.
- **With the keyboard:** press Tab until the grip of the column is selected, then press the up or down arrow. Each press moves the column one place.

The new order is saved at once.

---

## Editing Table Structure

You can change your table's settings or modify its columns at any time.

### Editing Table Settings

1. Go to **Settings → Database Tables** in your site menu.
2. Click on the table you want to change. Its **Columns** page opens.
3. Click **Edit Table**. (You can also open the **⋮** menu on the table's row and choose **Table Settings**.)
4. Update the display name or description.
5. Click **Save Table**.

The parent table is chosen when you create a table and cannot be changed afterwards -- entries already filed under it would be left without a home. If you need a different arrangement, create the table again with the parent you want.

### Editing Columns

1. Go to **Settings → Database Tables** in your site menu.
2. Click on the table you want to change.
3. Click the column you want to change. Its settings open.
4. Change its display name, field name, type, default value, required, unique, or list visibility.
5. Click **Save Changes**.

If you change a column's field name, the values already saved move to the new name.

### Deleting a Column

1. Open the columns page for your table.
2. Click the column you want to remove. Its settings open.
3. Click **Delete Column**, then **Delete** to confirm.
4. The column and the values saved in it no longer show on your entries. You cannot bring a deleted column back from this page.

If you later add a column with the same name, it starts empty: the deleted column's values do not come back. If you need them back, contact support.

---

## Table Options

Each table has additional options that control how its entries are displayed and organized. To access these options:

1. Open your table from the **Database Tables** list.
2. Click **Options** at the top of the **Columns** page. A window titled with your table's name and "Options" opens.

You can set the following:

- **Default Label** -- Which column's value is used as the main label when showing entries in lists and dropdowns.
- **Default Query Field** -- Which column is used by default when searching or filtering entries.
- **Paginate** -- How many entries to show per page when browsing. Leave blank to show all entries at once.
- **Group By** -- Organize entries into groups based on a specific column's value.
- **Group Direction** -- Whether groups are sorted in ascending (A to Z) or descending (Z to A) order.
- **Sort By** -- Which column is used to sort entries within each group.
- **Sort Direction** -- Whether entries are sorted ascending or descending.
- **Children Depth** -- If your table supports nested entries (parent/child), this controls how many levels deep the nesting goes.

Click **Save Options** to apply your changes.

> **Tip:** Setting a good "Default Label" is important. This is the value that shows up in dropdowns and lists throughout your site. For a "Team Members" table, you would want to set this to the "Name" column.

---

## Setting Up Relationships Between Tables

Relationships let you link one table to another. For example, you might want each blog article to be connected to an author from your "Team Members" table, or each product to belong to a category.

### How Relationships Work

When you add a column with the "Related Table" type, you are creating a link between two tables. There are two directions a relationship can go:

- **Has** -- This table contains items that belong to the related table. Think of it as "this table owns entries in the other table." For example, a "Category" table might "have" many products.
- **Belongs to** -- This table's entries are owned by entries in the related table. For example, a "Product" might "belong to" a category.

You can also choose whether the relationship allows one or many connections:

- **Has** + **Single** -- This table has one related entry (for example, a page has one author).
- **Has** + **Multiple** -- This table has many related entries (for example, a category has many products).
- **Belongs to** + **Single** -- This entry belongs to one item in the other table.
- **Belongs to** + **Multiple** -- This entry can belong to many items in the other table.

### Adding a Relationship

1. Open the columns page for your table.
2. Add a new column or edit an existing one.
3. Set the **Type** to "Relationship."
4. Choose **Has (this table owns children)** or **Belongs To (this table references parent)** in **Direction**.
5. Choose the table you want to link to in **Related Table**.
6. Check the **Multiple** box if the relationship should allow many connections.
7. Click **Create Column** (or **Save Changes** on an existing column).

"Has" relationships will show an inline form when editing entries, letting you add related items directly. "Belongs to" relationships will show a dropdown selector where you pick from existing entries in the related table.

---

## Deleting a Table

1. Go to **Settings → Database Tables** in your site menu.
2. Find the table you want to delete.
3. Open the **⋮** menu on the table's row, choose **Delete**, then click **Delete** to confirm.
4. The table, its columns and its entries no longer show anywhere on your site or dashboard.

You cannot bring a deleted table back from this page, so check first that you no longer need it. Some tables cannot be deleted: tables that are part of built-in modules are protected.

---

## How Database Tables Connect to Content Modules

Database tables and content modules work together. When you create a new table, it becomes available as a content type throughout your site. Here is what that means:

- **Your table appears in the dashboard menu** -- Once created, you can manage entries for your table just like you manage pages, articles, or any other content.
- **You can display table data on your pages** -- Use the Website Builder to add components that pull in and display data from your custom tables.
- **Relationships link everything together** -- By connecting tables to each other (and to built-in modules), you create a web of related content that keeps your site organized and flexible.

An AI tool you connect to WebNesting can also create tables, add and change columns, and add entries for you. See [Connecting an AI Tool](connecting-ai-tools.md).

In other words, the Database section is where you design the structure. The content modules are where you fill in the actual content. And the Website Builder is where you display that content to your visitors.
