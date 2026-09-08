# Workspace Data Tables

**Last verified:** 2026-09-08 6:43pm

Your workspace keeps its own set of tables, separate from the ones inside each website. They hold the information your products share -- your contacts, your support tickets, your tasks and projects, your marketing campaigns. You will find them under **Settings → Database**.

Two things happen on this page:

- **Add your own fields** to the tables that came with your workspace, so they hold the information *your* business needs.
- **Create your own tables**, for information that does not fit anywhere else, and put related ones into groups.

This is different from the [Database Tables](database-management.md) page inside a website. That one belongs to a single site and holds that site's content. This one belongs to your whole workspace and is shared by Marketing, Helpdesk and Tasks.

---

## What You Will See

The list shows every table in your workspace:

| Column | What it means |
|--------|---------------|
| **Table** | The table's name, with a short line about what it holds |
| **Group** | Which group the table belongs to, or a dash if it is not in one |
| **Columns** | How many of your own fields you have added to it |

Tables like **Contacts**, **Helpdesk Tickets** and **Tasks** came with your workspace. You can add your own fields to them, but you cannot rename or delete them -- other parts of the product depend on them existing.

---

## Adding Your Own Fields to a Table

Say you want to record which trade show a contact came from, or how urgent a ticket is on your own scale. You do that by adding a field.

1. Go to **Settings → Database**.
2. Find the table you want to add to and click **Columns**.
3. Click **Add Column**.
4. Give it a **display name** -- what you and your team will see on screen, like "Trade show".
5. Choose the **type** -- text, number, date, a dropdown of choices, a checkbox, and so on.
6. Click **Save**.

The new field appears wherever that record is edited. A field added to Contacts shows up on every contact; one added to Helpdesk Tickets shows up on every ticket.

To remove a field, open the same **Columns** screen and delete it there. Deleting a field also deletes the information stored in it, so check first that nobody is relying on it.

---

## Creating Your Own Table

When the information you want to keep does not belong on a contact, a ticket or a task, make a table for it -- a supplier list, a stock list, a register of equipment.

1. Go to **Settings → Database**.
2. Click **Create Table**.
3. Enter a **display name** -- what you will see in menus and lists, like "Suppliers".
4. Add a **description** if it helps your team know what belongs in it.
5. Optionally pick a **Group** to keep it with related tables (see below).
6. Click **Create Table**.

You are taken straight to its Columns screen so you can add fields.

To change a table's name, description or group later, open the table and click **Edit Table** (or use the cog button on its row in the list). To remove it, use the delete button on its row. Tables that came with your workspace offer neither -- only the ones you created.

---

## Table Groups

Once you have a few tables of your own, groups keep the related ones together. A group is just a label -- it does not change what a table holds or who can see it.

**To make a group:**

1. Go to **Settings → Database** and scroll to **Table groups**.
2. Click **New group**.
3. Give it a name, and a description if you want one.
4. Click **Create group**.

**To put a table in a group**, open the table's settings and choose the group from the **Group** list. To take it out again, click the small **x** on that field and save.

Each group you create also appears in the left-hand menu under **Table groups**, and clicking it shows just that group's tables.

**To delete a group**, use the delete button on its row. You will be asked to move or delete the tables inside it first -- deleting a group never deletes the tables in it.

---

## Where Products Fit In

Marketing, Helpdesk, Tasks and Internal Docs are **products**, not groups. They are switched on and off under **Settings → Products**, and each brings its own tables with it. You will see those tables in the list here, with the product's name in the **Group** column, but you manage the products themselves on the Products page.

---

## Common Questions

**Will adding a field slow anything down?**
No. Fields you add are stored alongside the information already there.

**Can I add a field to only some contacts?**
A field belongs to the whole table, so it appears on every record in it. Leave it blank where it does not apply.

**I deleted a group by mistake -- can I get it back?**
Make a new group with the same name and it comes back, description and all.

**Why can I not delete Contacts or Tickets?**
Those tables came with your workspace and other parts of the product read from them. You can add your own fields to them, but not remove the tables themselves.

**Is this the same as the Database Tables inside my website?**
No. Those belong to one website and hold that site's content -- see [Database Tables](database-management.md). The tables here belong to your workspace and are shared across your products.
