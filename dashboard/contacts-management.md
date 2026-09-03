# Contacts Management

**Last verified:** 2026-09-02 8:05pm

Contacts are your audience database in WebNesting. Every person who submits a form on your website, signs up for your newsletter, or is imported from a spreadsheet becomes a contact. Use the Contacts system to keep track of who your audience is, organize them into lists, and connect them to your marketing, forms, and support tools.

---

## What Are Contacts?

Think of Contacts as your digital address book for everyone who interacts with your business. Each contact record stores a person's name, email address, phone number, and any other details you want to track. Contacts are the foundation that ties together your forms, email marketing, and helpdesk features.

Contacts live at the workspace level, which means they are shared across all the websites in your workspace. A customer who fills out a form on one of your sites and submits a support ticket on another is still one contact -- not two separate records.

---

## Adding Contacts

You can create contacts one at a time directly from your workspace dashboard.

1. Go to the **Contacts** section in your workspace sidebar.
2. Click the **Create** button.
3. Fill in the contact details:
   - **Email** (required) -- The contact's email address. This is the primary identifier for every contact, so each email address can only appear once.
   - **First Name** -- The contact's first name.
   - **Last Name** -- The contact's last name.
   - **Phone** -- A phone number.
   - **Company** -- The company this contact is associated with (if any).
4. Set the contact's status:
   - **Active** -- The contact is current and engaged.
   - **Inactive** -- The contact is no longer active but you want to keep their record.
5. Save the contact.

> **Tip:** You do not need to fill in every field. Only the email address is required. You can always come back and add more details later.

---

## Importing Contacts

If you have an existing list of contacts in a spreadsheet, you can import them all at once using a CSV file.

### How to Import

1. Go to the **Contacts** section in your workspace sidebar.
2. Click the **Import** button.
3. Upload your CSV file.
4. Map your CSV columns to contact fields -- the system will show you the columns from your file and let you match each one to a contact field (email, first name, last name, phone, company, or any custom field you have created).
5. Choose how to handle duplicates (contacts whose email address already exists in your database):
   - **Skip** -- Leave the existing contact unchanged and do not import the duplicate row.
   - **Update** -- Merge the new information into the existing contact record. Existing data is kept for any fields not included in the import.
   - **Overwrite** -- Replace the existing contact's data entirely with the imported data.
6. Click **Import** to start the process.

After the import finishes, you will see a summary showing how many contacts were created, updated, and skipped.

### Preparing Your CSV File

For the smoothest import experience:

- Make sure your file has a header row with column names (like "Email," "First Name," "Last Name").
- The email column is required -- rows without a valid email address will be skipped.
- Save your file in CSV format. Most spreadsheet applications (Excel, Google Sheets, Numbers) can export to CSV.

> **Tip:** Start with a small test import of five to ten contacts to make sure your column mapping is correct before importing your full list.

---

## Contact Details

Every contact record stores a set of standard information, plus any custom fields you define.

### Standard Fields

- **Email** -- The contact's email address. This is the unique identifier for each contact.
- **First Name** -- The contact's first name.
- **Last Name** -- The contact's last name.
- **Phone** -- A phone number.
- **Company** -- The company the contact is associated with.
- **Status** -- Whether the contact is Active or Inactive.
- **Source** -- How the contact was added to your database (form submission, CSV import, or manual creation). This is tracked automatically so you always know where a contact came from.

### Subscription Information

If you use the Marketing product, each contact also has an email subscription status:

- **Subscribed** -- The contact is receiving your workspace-wide marketing emails.
- **Unsubscribed** -- The contact has opted out of marketing emails.
- **Bounced** -- The contact's email address is not deliverable.
- **Pending** -- The contact has not opted in to workspace-wide email (this is the starting status).

You can change it with the **Email Status** control in the Marketing panel of the contact's page. Setting someone to **Subscribed** is what makes them reachable by workspace-wide campaigns, so only do it for people who have genuinely agreed to hear from you.

### Sites This Person Belongs To

When someone creates an account on one of your websites, they appear in your Contacts, and their page shows a **Sites** panel: which sites they belong to, when they joined, when they last signed in, and whether they opted in to marketing email on each site. Site opt-ins are separate from the workspace-wide Email Status above -- a campaign sent to one site's audience reaches the people who opted in on that site.

- **Remove from this site** takes away their account on that one site and leaves the rest alone.
- Removing them from their **last** site deletes the whole contact -- their login, marketing history, and record. The confirmation message tells you when that is about to happen.
- **Download their data** (at the top of the page) gives you everything the workspace holds about one person, for when they ask for a copy of it.

You can also filter your contact list by site, and **Export CSV** always exports exactly what the current filters show.

### Editing a Contact

1. Click on any contact in your list to open their details.
2. Update any field -- name, phone, company, status, or custom fields.
3. Save your changes.

### Deleting a Contact

1. Find the contact you want to remove.
2. Click the **Delete** option.
3. Confirm the deletion.

Deleted contacts are moved to the trash and can be restored if needed.

---

## Contact Lists

Lists help you organize your contacts into groups. You can use lists to keep track of different audiences, target specific people with email campaigns, or simply stay organized.

There are two types of lists:

### Manual Lists

A manual list is a straightforward group of contacts. You explicitly add and remove contacts from the list. A contact stays on a manual list until you remove them.

Use manual lists when you want full control over who is in the group. For example:
- "VIP Customers"
- "Event Attendees 2026"
- "Newsletter Subscribers"

### Segments

A segment is a smart list that automatically includes contacts matching rules you define. Instead of adding contacts one by one, you set the criteria and the segment updates itself.

Use segments when you want the list to stay current without manual work. For example:
- "All contacts added in the last 30 days"
- "Contacts with a company in the Technology industry"
- "Active contacts tagged as VIP"

### Creating a List

1. Go to the **Lists** area within your Contacts section.
2. Click the **Create** button.
3. Fill in the list details:
   - **Name** (required) -- A descriptive name for the list, like "Monthly Newsletter" or "Product Launch Invites."
   - **Description** -- An internal note to help you remember what this list is for.
   - **Type** -- Choose "Manual" for a standard list you manage yourself, or "Segment" for a dynamic list that auto-populates based on rules.
4. If you chose Segment, define the rules that determine which contacts are included.
5. Save the list.

> **Tip:** Lists and tags serve different purposes. Use **lists** to group contacts for a specific purpose, like sending an email campaign. Use **tags** for flexible labels that describe a characteristic, like "VIP" or "Attended Workshop." A contact can be on multiple lists and have multiple tags at the same time.

---

## Tags

Tags are color-coded labels you attach to contacts to categorize them in flexible ways. Unlike lists (which group contacts for a purpose), tags describe characteristics or qualities. A contact can have as many tags as you want.

Common tag examples: "VIP," "New Lead," "Attended Workshop," "Purchased," "Follow Up Needed."

### Creating a Tag

1. Go to the **Tags** area within your Contacts section.
2. Click the **Create** button.
3. Fill in the tag details:
   - **Name** (required) -- A short, descriptive label like "VIP" or "Hot Lead."
   - **Color** -- Choose a color to make this tag easy to spot visually when viewing your contact list.
4. Save the tag.

### Applying Tags to Contacts

Tags are applied from the contact detail view. Open a contact, add or remove tags, and save. Each tag shows how many contacts currently have it applied, so you can see at a glance how your audience breaks down.

> **Tip:** Use tag colors strategically. For example, use red for urgent follow-ups, green for completed actions, and blue for informational labels. This makes scanning your contact list much faster.

---

## Companies

Companies let you associate contacts with the organizations they belong to. This is especially useful for B2B businesses where you work with multiple people at the same company.

### Company Information

Each company record can store:

- **Name** -- The company name.
- **Domain** -- The company's website domain (like "example.com").
- **Industry** -- The industry the company operates in.
- **Size** -- The approximate number of employees.
- **Phone** -- A company phone number.
- **Website** -- The company's full website URL.
- **Address** -- The company's physical address.

### Creating a Company

1. Go to the **Companies** area within your Contacts section.
2. Click the **Create** button.
3. Fill in the company details.
4. Save the company.

### Linking Contacts to Companies

When you create or edit a contact, you can select a company from the **Company** field. Multiple contacts can be linked to the same company, which makes it easy to see all the people you work with at a given organization.

> **Tip:** If you work primarily with individual consumers rather than businesses, you may not need to use the Companies feature at all. It is entirely optional.

---

## Custom Fields

Every contact has standard fields like name, email, and phone. Custom fields let you track additional information that is specific to your business.

For example, a real estate agent might add a "Property Interest" field. A fitness studio might add a "Membership Level" field. A nonprofit might add a "Donation Tier" field.

### Creating a Custom Field

1. Go to the **Custom Fields** area within your Contacts section.
2. Click the **Create** button.
3. Fill in the field details:
   - **Label** (required) -- The display name for the field, like "Membership Level" or "Preferred Language."
   - **Type** -- The kind of data this field stores:
     - **Text** -- Any text (names, descriptions, notes).
     - **Number** -- Numeric values (scores, quantities, amounts).
     - **Date** -- A date value.
     - **Boolean** -- A yes or no checkbox.
     - **Dropdown** -- A menu with predefined options you define.
4. Save the custom field.

### How Custom Fields Work

Once created, custom fields appear whenever you create or edit a contact. The data is stored on each contact record and can be used for filtering and organizing your contact list.

Custom fields also work with form integrations -- you can map a form field to a custom field so that the information flows directly into your contact records when visitors submit forms.

---

## How Contacts Connect to Other Features

Contacts are not just a standalone address book. They connect to several other features in your workspace, creating a unified view of every person who interacts with your business.

### Forms

When a visitor submits a form on your website, a contact record is automatically created or updated with the information they provided. You do not need to set this up manually -- if a form collects an email address, the contact is created automatically.

Form fields can be mapped to contact fields so that names, phone numbers, and custom information flow directly into the right places on the contact record. The contact's source is recorded as "Form Submission" so you can see exactly how they found you.

### Email Marketing

If you have the Marketing product enabled, your contacts become the audience for email campaigns. You can:

- Send campaigns to specific lists or segments of contacts.
- Track who opened your emails, clicked links, and engaged with your content.
- Manage subscription preferences -- subscribed, unsubscribed, bounced, and pending statuses.
- Set up automated emails triggered by contact actions.

Every interaction is recorded on the contact record, giving you a complete history of each person's engagement with your marketing.

### Helpdesk

If you have the Helpdesk product enabled, contacts are automatically linked to their support tickets. When a customer submits a ticket, you can see their full history -- previous tickets, form submissions, and marketing engagement -- all in one place.

---

## Searching and Filtering

When your contact database grows, finding the right people is simple.

### Searching

1. Go to the **Contacts** section.
2. Use the search bar at the top of the list.
3. Type a name or email address.
4. The list will update to show matching contacts.

### Filtering

Filters let you narrow down your contact list by specific criteria:

- **Status** -- Show only Active or Inactive contacts.
- **List** -- Show only contacts on a specific list or segment.
- **Tag** -- Show only contacts with a specific tag applied.
- **Company** -- Show only contacts associated with a specific company.
- **Date** -- Filter by when the contact was created or last updated.

You can combine multiple filters to get exactly the view you need. For example, you might filter for "Active contacts tagged as VIP who are on the Newsletter list."

> **Tip:** If you find yourself applying the same filters regularly, consider creating a segment that captures those criteria. Segments save your filtering rules and update automatically.

---

## Tips

- **Keep email addresses clean.** Since the email address is the unique identifier for each contact, make sure email addresses are correct before importing. Typos create duplicate records that are hard to clean up later.

- **Use tags generously.** Tags are lightweight and flexible. Create tags for any characteristic that helps you understand your audience -- interests, lead quality, event attendance, purchase history, or anything else relevant to your business.

- **Start with manual lists, add segments later.** If you are new to contact management, start by creating a few manual lists for your most important groups. Once you understand your audience better, create segments to automate the grouping.

- **Let forms do the work.** Instead of adding contacts manually, set up forms on your website that collect the information you need. Contacts are created automatically from form submissions, saving you time and reducing data entry errors.

- **Review your contacts regularly.** Periodically check for bounced emails, inactive contacts, and outdated information. A clean, up-to-date contact database leads to better email deliverability and more accurate reporting.

- **Use companies for B2B relationships.** If you work with businesses, linking contacts to companies helps you see the full picture -- all the people you interact with at each organization.

- **Define custom fields early.** Think about what information is important to your business and set up custom fields before you start collecting contacts. It is easier to collect the right data from the start than to go back and fill in missing information later.

> **Tip:** Quality matters more than quantity. A database of 200 engaged, well-organized contacts is more valuable than 5,000 outdated records with missing information.

---

## Where to Go Next

- **[Email Marketing](../content-modules/email-marketing.md)** -- Learn how to send email campaigns to your contacts.
- **[Workspace Products](workspace-products.md)** -- Learn about enabling the Marketing, Helpdesk, and Tasks products.
- **[Team and Permissions](team-and-permissions.md)** -- Control who on your team can view and manage contacts.
