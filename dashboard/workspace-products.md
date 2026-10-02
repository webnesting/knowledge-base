# Workspace Products

**Last verified:** 2026-10-02 6:13pm (home page keeps products that are already active everywhere, marked active). Earlier 2026-09-28 12:12am (scheduled turn-off at month end vs turn off now; removed a turn-off reassurance line; API data transfer priced per GB — usage-billing-correctness Phase 6). Earlier 2026-09-27 9:49pm (Turn back on / trial wording — no turn-off reassurance). Earlier 2026-09-27 8:02pm (turning off warns: data deleted after 30 days, free allowance stops). Earlier 2026-09-27 7:59pm (plain pricing wording — no turn-off reassurance). Earlier 2026-09-27 7:49pm (noted free credits build up hourly while a product is on). Earlier 2026-09-26 6:51pm

WebNesting's workspace includes optional products you can enable to add powerful features to your team's workflow. Six products are available. Most are paid -- you only pay for the ones you use. Two are switched on by default: **Websites**, for building your sites, and **Internal Docs**, which is completely free.

---

## What Are Workspace Products?

Workspace products are add-on features that extend your workspace beyond website management. Each product adds a complete set of tools for a specific purpose. Think of them like apps you install on your phone -- each one adds new abilities to your workspace.

Your workspace starts with the basics: website management, media, and team collaboration. When you need more, you enable a product, and new tools appear in your workspace sidebar right away.

---

## Available Products

### Websites

Build and publish websites. **Websites is always on** -- it has no on/off switch and no monthly base fee of its own; each website you create is billed as it always has been. Use **Create site** on the Websites card to create a website -- including your first one. Once you have a website, the **Sites** section appears in your sidebar, where your websites live.

### Marketing

Email marketing with contacts, campaigns, and automations. When you enable Marketing, you get:

- **Email campaigns** -- Create, design, and send email campaigns to your contacts
- **Contact management** -- Organize your audience with lists and tags
- **Email templates** -- Build beautiful emails with a visual editor
- **Marketing automations** -- Set up automated emails triggered by form submissions, contact tags, and more
- **Campaign analytics** -- Track opens, clicks, and engagement for every campaign

### Helpdesk

Ticket management for customer support. When you enable Helpdesk, you get:

- **Ticket management** -- Create, assign, and track support tickets
- **Team inbox** -- A shared inbox for managing incoming support requests
- **Knowledge base** -- Write self-service articles so customers can find answers on their own
- **SLA policies** -- Set response time targets to keep your team on track
- **Canned responses** -- Save and reuse replies for common questions
- **Site connections** -- Connect to your websites to create customer-facing support portals

### Tasks

Project and task management for your team. When you enable Tasks, you get:

- **Project organization** -- Group related work into projects
- **Multiple views** -- Switch between Board (Kanban), List, Timeline, and Calendar views
- **My Work** -- A personal hub showing all your assigned tasks across projects
- **Time tracking** -- Log time spent on tasks and Helpdesk tickets, by hand or with a start/stop timer
- **Milestones and tags** -- Mark key deadlines and organize tasks with tags
- **Task comments** -- Discuss work and see activity history on every task

### Internal Docs

A private wiki for your team -- how-tos, runbooks, and onboarding notes that only your workspace members can read. **Internal Docs is free and switched on by default**, so it's ready the moment you open your workspace. It has its own section in the sidebar. You can turn it off any time to hide it, and turning it back on brings all your docs back exactly as they were -- nothing is ever deleted.

- **A shared team wiki** -- Write and organize documentation in a familiar folder tree
- **Always free** -- No base fee and no usage charges
- **Optional GitHub sync** -- Keep your docs in a GitHub repository and edit them in either place

### API Access

Programmatic REST API access to your workspace for developers. When you enable API Access, you get:

- **API tokens** -- Create scoped access tokens so external software, scripts, and integrations can read and update your content
- **Usage controls** -- Free monthly allowances for API requests, data transfer, and active tokens, with optional add-ons for higher rate limits and extended audit-log retention

> **Connecting an AI assistant (Claude, Cursor, or another MCP tool) is free and does not require API Access.** That is a separate, no-cost feature -- see [Connecting AI Tools](connecting-ai-tools.md).

---

## Enabling a Product

Turning on a product takes just a few seconds:

1. Go to your workspace dashboard.
2. Click **Products** in the settings area.
3. You will see all available products with their pricing.
4. Click **Turn on** on the product you want to activate.
5. The product will be available immediately in your workspace sidebar.

Once a product is enabled, new menu items will appear in your workspace sidebar. For example, enabling Marketing adds sections for contacts, campaigns, and email templates.

> **Tip:** Each product shows its base monthly cost and any usage-based charges before you enable it. Review the pricing details so there are no surprises.

### Add a product from your home page

Your WebNesting home page also shows every product available to your workspaces, each with its pricing and where it is already active. Click a product to turn it on. If you have more than one workspace, you can choose which workspaces to enable it on — one, several, or all — in a single step, and you will see the estimated added cost before you confirm. Workspaces where you already have the product, or where you do not have permission to manage products, are shown but cannot be changed from here. Once a product is active on every workspace, its card says so (for example, **Active on all 2 workspaces**), and clicking it shows where it is active with a **View products** link for each workspace.

---

## Understanding Product Pricing

Each product has two types of costs:

- **Base monthly fee** -- A fixed monthly charge for having the product enabled.
- **Usage charges** -- Additional costs based on how much you use certain features. These charges include free credits, so you will not be charged until you exceed the free tier.

Free credits build up hour by hour while a product is turned on, rather than being handed out all at once when the month starts, and a product earns none while it's off. The exact free amount for a full month follows how many hours are in it (a 31-day month earns a little more than a 30-day one, February a little less). See [Billing and Usage](billing-and-usage.md) for the exact numbers.

Here is how pricing works for each product:

**Contacts are shared across products.** Marketing, Helpdesk, and your site forms all draw on the same workspace contact database, so contacts are billed once for the whole workspace -- not once per product. Your first 500 contacts are free.

### Marketing Pricing

- Base monthly fee for having Marketing enabled
- Additional charge per email sent (your first emails each month are free)

### Helpdesk Pricing

- Base monthly fee for having Helpdesk enabled
- Additional charge per ticket, counted when the ticket is created (with a free tier)
- Your per-site knowledge base is included -- there is no per-article charge. (Internal Docs is a separate, always-free product -- see above.)

### Tasks Pricing

- Base monthly fee for having Tasks enabled
- Additional charge per active task (with a free tier)
- Projects are free -- their tasks are already covered by the active-task charge

### API Access Pricing

- Base monthly fee for having API Access enabled
- Additional charge per API request (with a free tier)
- Additional charge for data transfer, **priced per GB** (with a free tier)
- Additional charge per active API token (with a free tier)
- Optional add-ons for a higher rate limit and extended audit-log retention

> **Tip:** Usage charges include generous free tiers, so you can get started without paying anything beyond the base fee. You will only see additional charges once you exceed the free allowances.

---

## Disabling a Product

If you no longer need a product:

1. Go to **Products** in your workspace settings.
2. Find the product you want to turn off.
3. Click **Turn off**.
4. A confirmation window states what happens up front: your data for it is **permanently deleted after 30 days** unless you turn it back on before then, and its free allowance stops building up. Below that it lists how many of your tickets, campaigns or projects are kept, and what stops while the product is off.
5. Choose how: **Turn off on {date}** (the end of this billing month) is the default and keeps the product working -- and its free allowance still building up -- until then; **Turn off now** stops it right away instead, giving up whatever free allowance it would have earned for the rest of the month. **Keep it on** cancels and leaves everything as it was.

If you scheduled a turn-off, the product's card shows a banner naming the date, with a **Keep it on** button to cancel it any time before then.

A site module works differently -- it has no free allowance worth keeping, so turning one off always takes effect right away (see [Modules and Features](modules-and-features.md#how-to-disable-a-module)).

Once a product is off, its card shows a banner with:

- **Turn back on** -- turns the product back on with its data, as long as it's before the deletion date.
- **Delete now** -- permanently deletes the product's data right away instead of waiting. You'll be asked to type your workspace name to confirm, because this can't be undone.
- **Download a copy** -- makes a copy of the product's data (a spreadsheet file for each kind of record, plus attached files) and emails you a download link that works for 7 days. Your contacts are not included -- they stay in Contacts. You can download a copy any time the product is off, including right before you delete it.

> **Important:** Disabling a product removes it from your workspace for everyone on your team once it's off. Its data is **permanently deleted after 30 days** after that -- turn it back on before then if you want to keep it; turning it on after that starts it empty. Your contacts are never affected. **Internal Docs** is the exception -- it is free, so its documents are kept for as long as you like.

> **Helpdesk and your sites' knowledge bases:** once Helpdesk is off, the public knowledge base comes off each of your sites, but its articles are kept with the rest of your Helpdesk data. Turn Helpdesk back on and the knowledge base returns to your sites as it was; if the 30 days run out (or you choose **Delete now**), the articles are deleted along with your tickets.

> **Storage:** files the product stored (for example ticket attachments or campaign images) still count toward your workspace storage while they are being kept.

> **Websites** has no **Turn off** button -- it is always on, so the steps above don't apply to it.

### Disabling the same product more than twice in a month

Your first two turn-offs of a product in a billing month work as described above -- immediately if you choose **Turn off now**, or at the date you scheduled. The second time, the confirmation window also warns you about the rule below. If you turn the same product off a **third** time in the same month, there's no choice of timing: it keeps working normally -- and is billed as usual, still earning its free allowance -- until the **1st of next month**, and turns off then. Its card says when, and **Keep it on** cancels it. The count starts over on the 1st of each month.

---

## Who Can Manage Products?

Only workspace members with **Settings** edit permission can enable or disable products. If you do not see the enable or disable buttons, ask your workspace owner or an admin with settings access to make the change for you.

---

## Tips

- **Enable only what you need.** Each enabled product adds to your monthly bill. If you are not actively using a product, disable it to save money.
- **Disabling has real consequences, so it isn't undone lightly.** Its data is **permanently deleted after 30 days** unless you turn it back on, and its free allowance stops building up while it's off. Weigh that before you turn something off, not after.
- **Enabling takes effect immediately;** your first two disables of a product in a month can be immediate too, or scheduled for the end of the billing month (see [Disabling a Product](#disabling-a-product)). A third disable in the same month waits until the 1st either way (see above).
- **30 days is your window to change your mind, not a guarantee.** Turn a disabled product back on within 30 days and nothing is lost; after that, its data is permanently deleted and starting it again means starting empty.
- **All team members benefit.** When you enable a product, all workspace members with appropriate permissions can access it.

---

## Where to Go Next

- **[Modules and Features](modules-and-features.md)** -- Learn about site-level modules like Articles, Events, and E-Commerce.
- **[Billing and Usage](billing-and-usage.md)** -- Understand how billing works and how to manage your costs.
- **[Team and Permissions](team-and-permissions.md)** -- Learn how to manage team access and permissions.
