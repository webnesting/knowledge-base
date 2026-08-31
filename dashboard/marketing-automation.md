# Marketing Automations

**Last verified:** 2026-08-31 12:10pm

Marketing automations let you create set-it-and-forget-it workflows that send emails, update contacts, and perform actions automatically when something happens. Instead of manually sending a welcome email every time someone signs up, or remembering to tag contacts after an event, you build the workflow once and let it run on its own.

---

## What Are Marketing Automations?

An automation is a sequence of steps that runs automatically when a specific event occurs. You define a **trigger** (what starts the automation) and then add **steps** (what happens next). Once you activate the automation, it works in the background without any effort on your part.

For example, you could create a welcome series that sends a thank-you email immediately when someone joins your mailing list, waits three days, and then sends a follow-up email with your best content. Every new subscriber goes through the same experience automatically.

Automations are part of the Marketing product in your workspace. You will find them under **Marketing Automation** in your dashboard sidebar.

---

## How Automations Work

Every automation follows the same pattern:

1. **A trigger fires** -- Something happens that starts the automation, like a form submission or a new contact being added.
2. **The contact enters the automation** -- The person connected to that event is enrolled in the workflow.
3. **Steps run in order** -- Each step in the automation runs one after another. Steps can send emails, wait for a set time, check conditions, or update the contact's information.
4. **The contact reaches the end** -- Once all steps have been completed, the contact exits the automation.

Each contact can only be in an automation once at a time. If the same trigger fires again for a contact who is already enrolled, it will not create a duplicate enrollment.

---

## Creating an Automation

To create a new automation:

1. Click **Marketing** in your workspace sidebar, then **Automations** under **Automation**.
2. Click the **Create** button.
3. Give your automation a name -- something descriptive like "Welcome Series" or "Post-Purchase Follow-Up."
4. Choose a trigger (the event that starts the automation).
5. Add your steps (emails, delays, conditions, and actions).
6. Save the automation.

Your automation starts in a **Paused** state. It will not run until you activate it.

---

## Choosing a Trigger

The trigger is what kicks off the automation. When the trigger event happens, the associated contact enters the workflow. You choose one trigger per automation.

### Available Triggers

- **Form submission** -- Runs when a visitor submits a specific form on your website. Great for sending a thank-you email after someone fills out a contact form, registration form, or survey.

- **Contact created** -- Runs when a new contact is added to your marketing database, regardless of how they were added (form signup, import, manual entry). Use this for universal welcome messages.

- **Added to list** -- Runs when a contact is added to a specific mailing list. Ideal for list-specific welcome sequences -- for example, a different welcome series for your "Newsletter" list versus your "VIP Customers" list.

- **Tag added** -- Runs when a specific tag is applied to a contact. Useful for actions that should happen whenever a contact reaches a certain status, like getting tagged as "VIP" or "Interested in Product X."

- **Date field** -- Runs based on a date stored in a contact's profile, like a birthday or anniversary. Use this for automated birthday wishes, renewal reminders, or anniversary discounts.

- **Manual enrollment** -- No automatic trigger. You manually add specific contacts to the automation whenever you choose. Useful for one-off workflows or situations where you want full control over who enters.

- **Ticket created** -- Runs when a helpdesk ticket is created. This trigger is available when the Helpdesk product is enabled in your workspace. Use it to send a confirmation email to the customer or notify your team.

- **Ticket resolved** -- Runs when a helpdesk ticket is resolved. Available when the Helpdesk product is enabled. Great for sending satisfaction surveys or follow-up messages after a support issue is closed.

- **Task completed** -- Runs when a linked task is completed. Available when the Tasks product is enabled in your workspace. Use it to notify stakeholders or trigger next steps when a piece of work is finished.

> **Tip:** Start with a simple trigger like "Contact created" or "Added to list" for your first automation. You can always create more automations with different triggers later.

---

## Adding Steps

After choosing your trigger, you build out what happens by adding steps. Steps run in the order you add them, one after another.

### Send Email

Sends an email to the contact using one of your saved email templates.

- Choose which email template to send.
- The email goes to the contact who is currently in the automation.
- Make sure you have created the email template before adding this step.

### Wait / Delay

Pauses the automation for a set amount of time before moving to the next step.

- Choose the delay length -- hours, days, or weeks.
- Use delays between emails to avoid overwhelming contacts with too many messages at once.
- For example, wait 3 days between a welcome email and a follow-up.

### Condition

Creates a branch in your automation based on whether something is true or false. Contacts who meet the condition follow one path, and contacts who do not follow a different path.

Conditions can check things like:

- **Opened email** -- Did the contact open a previous email in this automation?
- **Clicked link** -- Did the contact click a link in a previous email?
- **Has tag** -- Does the contact currently have a specific tag?
- **In list** -- Is the contact currently on a specific mailing list?

This lets you create personalized experiences -- for example, sending a reminder only to contacts who did not open the first email, or offering a special deal to contacts who clicked a product link.

### Add Tag

Applies a tag to the contact. Use this to mark contacts who have reached a certain point in the automation, like "Completed Welcome Series" or "Engaged."

### Remove Tag

Removes a tag from the contact. Useful for cleaning up temporary tags or moving contacts between categories as they progress through the workflow.

### Add to List

Adds the contact to a mailing list. For example, after someone completes a welcome series, you could add them to your main "Active Subscribers" list.

### Remove from List

Removes the contact from a mailing list. Useful when you want to move contacts from one list to another as part of the workflow.

### Update Contact Field

Changes a value on the contact's profile. For example, you could update a custom field like "Onboarding Status" to "Complete" when a contact finishes a series of steps.

> **Tip:** A good starting automation might be: **Send Email** (welcome message) then **Wait** (3 days) then **Send Email** (follow-up with your best content). Keep it simple and build from there.

---

## Using Conditions to Branch

Conditions are what make automations truly powerful. Instead of sending every contact down the same path, you can create branches that respond to each contact's behavior and profile.

### How Branching Works

When a contact reaches a condition step, the automation checks whether the condition is true or false:

- **If true** -- The contact follows the "yes" path and runs the steps you have placed there.
- **If false** -- The contact follows the "no" path and runs those steps instead.

### Example: Re-engage Non-Openers

1. **Send Email** -- Send your weekly newsletter.
2. **Wait** -- Wait 2 days.
3. **Condition** -- Did they open the email?
   - **Yes path** -- Add the tag "Engaged."
   - **No path** -- Send a follow-up email with a new subject line.

### Example: Reward Engaged Contacts

1. **Send Email** -- Send a product announcement.
2. **Wait** -- Wait 1 day.
3. **Condition** -- Did they click a link?
   - **Yes path** -- Send a discount code email, then add the tag "Interested."
   - **No path** -- No further action.

> **Tip:** Do not over-complicate your first automations. Start with one or two conditions at most. You can always add more branches later as you learn what works.

---

## Managing Automations

### Activating an Automation

When you are ready for an automation to start running:

1. Open the automation.
2. Switch its status from **Paused** to **Active**.
3. The automation will start processing new trigger events immediately.

Contacts who triggered the event before the automation was activated will not be enrolled retroactively -- only new trigger events are processed.

### Pausing an Automation

If you need to stop an automation temporarily:

1. Open the automation.
2. Switch its status from **Active** to **Paused**.
3. New trigger events will no longer enroll contacts.

Contacts who are already in the automation will remain where they are. They will not continue to the next step until you reactivate the automation.

### Editing an Automation

You can edit an automation at any time -- add steps, remove steps, change the trigger, or update email templates. If the automation is active, consider pausing it first to avoid unexpected behavior while you make changes.

1. Click on the automation you want to edit.
2. Make your changes.
3. Save the automation.

> **Important:** If you change the trigger on an active automation, only new trigger events will use the updated trigger. Contacts already enrolled will continue through their remaining steps.

---

## Viewing Enrollments

You can see which contacts are currently in an automation and where they are in the workflow.

1. Open the automation you want to check.
2. Look for the enrollments section, which shows:
   - **Currently enrolled contacts** -- People who are actively going through the automation.
   - **Current step** -- Which step each contact is on right now.
   - **Completed contacts** -- People who have finished all the steps.

This gives you visibility into how your automation is performing and how many people are moving through each step.

> **Tip:** Check your enrollments regularly when you first launch an automation. This helps you spot any issues early, like contacts getting stuck on a step or not entering the automation as expected.

---

## Cross-Product Automations

If your workspace has the **Helpdesk** or **Tasks** products enabled, you can create automations that respond to events from those products. This lets you connect your marketing, support, and project management workflows.

### Helpdesk Triggers

- **Ticket created** -- Automatically send a confirmation email when a customer submits a support request. You could also tag the contact as "Support Customer" for future reference.
- **Ticket resolved** -- Send a satisfaction survey after a ticket is closed, or add the contact to a "Recent Support" list for follow-up.

### Tasks Triggers

- **Task completed** -- Notify stakeholders when a task is finished, or trigger the next step in a multi-phase project. For example, when a "Design Review" task is completed, the automation could notify the client that their design is ready.

These triggers only appear when the corresponding product is enabled in your workspace. If you disable a product, automations using its triggers will stop processing new enrollments.

> **Tip:** Cross-product automations are a great way to make sure nothing falls through the cracks. For example, you could automatically send a thank-you email every time a support ticket is resolved, without anyone having to remember to do it manually.

---

## Tips

- **Start simple.** Your first automation should be straightforward -- a welcome email with a follow-up delay is a great starting point. Add complexity as you get comfortable.
- **Name automations clearly.** Use descriptive names like "Welcome Series -- Newsletter" or "Post-Purchase Follow-Up" so you can find them easily later.
- **Use delays between emails.** Sending multiple emails in quick succession overwhelms contacts. Space them out by at least a day or two.
- **Test before activating.** Create a test contact and manually enroll them to make sure the automation behaves as expected before turning it on for everyone.
- **Review enrollments regularly.** Check how contacts are moving through your automations, especially in the first few days after activation.
- **One automation per purpose.** It is better to have several focused automations than one giant automation trying to do everything. Keep each workflow focused on a single goal.
- **Pause before editing.** If you need to make significant changes to an active automation, pause it first to avoid unexpected behavior.
- **Combine with tags and lists.** Use tag and list steps within automations to organize contacts as they progress. This makes it easier to segment your audience later.

---

## Where to Go Next

- **[Email Marketing](../content-modules/email-marketing.md)** -- Learn how to manage contacts, mailing lists, tags, and email campaigns.
- **[Workspace Products](workspace-products.md)** -- Enable and manage workspace products like Marketing, Helpdesk, and Tasks.
- **[Modules and Features](modules-and-features.md)** -- Explore other modules you can add to your website.
