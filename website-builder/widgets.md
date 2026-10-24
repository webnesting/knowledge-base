# Custom Widgets

**Last verified:** 2026-10-24 5:44pm

Widgets are reusable content blocks that you create once and use across multiple pages on your site. Instead of rebuilding the same section over and over, you build it once as a widget, and then place it wherever you need it.

---

## What Is a Widget?

A widget is a saved piece of your website that you can reuse. Think of it like a stamp. You design the stamp once, and then you can stamp it onto any page you want -- as many times as you need.

For example, if every page on your site has the same "Contact Us" block at the bottom, you can turn that block into a widget. Then you just drop the widget onto each page instead of recreating it from scratch every time.

---

## Why Use Widgets?

Widgets save you time and keep your site consistent.

- **Build once, use everywhere.** Create a content block one time, then place it on as many pages as you like.
- **Stay consistent.** Every page that uses the widget looks exactly the same. No more accidentally using the wrong colors or forgetting a detail.
- **Update once, change everywhere.** When you edit a widget, the changes appear on every page that uses it. Update your phone number in one place, and it updates across your entire site.
- **Work faster.** Dragging a ready-made widget onto a page takes seconds. Building the same section from scratch every time takes much longer.

### A widget or a saved section?

Both let you use a part of a page again, but they behave in opposite ways.

- **A widget stays shared.** Every page shows the same widget, so a change to it shows on all of those pages.
- **A saved section is a copy.** Each page gets its own copy, which you change on that page alone. Changing one copy never changes the others, and deleting the saved section leaves every copy in place. See [Save Your Own Section](adding-components.md#save-your-own-section).

Use a widget for a block that must be the same everywhere, such as your opening hours. Use a saved section for a starting point you adapt on each page, such as a banner.

---

## Enabling the Widget Builder

The Widget Builder is an add-on feature. Turn it on before you create widgets. While it is off, the **New Widget** button and the **+** on **My Widgets** do not show.

1. Go to your **Dashboard**.
2. Open **Modules and Features** from the sidebar.
3. Find **Widget Builder** in the list.
4. Enable it.

Once enabled, you will see widget options appear in the Website Builder.

---

## Creating a New Widget

There are two ways to create a widget. Both end up in the same place.

### From the Widgets page

1. Open the site you want to work on.
2. In the site menu on the left, click **Widgets** (it sits at the bottom of the panel, next to **Website Builder**).
3. Click **New Widget**.
4. Give your widget a **name**. Choose something descriptive so you can find it easily later -- for example "Contact Block", "Page Header", or "Sidebar Newsletter Signup".
5. Save. Your widget appears in the list.
6. Click **Edit in Builder** on its row to start designing it.

### From the builder, while you are working

1. In the Website Builder, open the **Add** panel from the rail on the right.
2. Find the **My Widgets** group.
3. Click the **+** on the group header and enter a name.
4. The new widget appears as a tile you can drop onto any page.

---

## Designing Your Widget

The Widget Builder works just like the regular Website Builder -- same canvas, same components, same styling tools.

1. Open your widget with **Edit in Builder**.
2. The builder loads with a blank canvas for your widget.
3. Add components by dragging them from the **Add** panel.
4. Style and arrange your content just like you would on a regular page.
5. **Save** with the Save button or **Ctrl+S** (Windows) / **Cmd+S** (Mac).
6. **Publish** the widget to make it available on your live pages.

> **Tip:** Keep your widgets focused on a single purpose. A widget that does one thing well is more useful than one that tries to do everything.

---

## Using Widgets on Your Pages

Once you have created and saved a widget, it becomes available as a component you can add to any page.

### Finding Your Widgets

1. Open the **Website Builder** for the page you want to edit.
2. Click **Add** in the panel rail on the right.
3. Scroll to the **My Widgets** group. Every widget you have created is listed there by name.

### Adding a Widget to a Page

1. Find the widget you want in the **My Widgets** group.
2. **Click and hold** on the widget tile, then **drag it** onto your page canvas.
3. Drop it where you want it to appear.
4. The widget content will load onto your page automatically.

That is it. The widget and all its content will appear on your page exactly as you designed it.

> **Tip:** You can place the same widget on as many pages as you like, and more than once on one page. It looks the same in each spot, unless you give a spot its own values (see **Widget properties** below).

### Putting a Widget inside another Widget

While you edit a widget, the **My Widgets** group of the **Add** panel lists your other widgets, so a widget can hold another one, such as a pricing card inside a pricing band. A widget can never hold itself. The widget you are editing, and any widget that already holds it, are greyed out with the line "A widget can't contain itself." Pasting or duplicating one of them into the widget is refused with the same message, and nothing is added.

---

## Editing a Widget

When you need to update a widget, you edit it in the Widget Builder -- not on the individual pages where it appears.

1. Open the **Widgets** page from your site menu.
2. Find the widget you want and click **Edit in Builder**.
3. Make your changes.
4. **Save** and **Publish** the widget.

### How Changes Affect Your Pages

When you edit and publish a widget, the updated version will appear on every page that uses it. You do not need to go to each page individually and make the same change -- the update happens automatically.

This is one of the biggest advantages of using widgets. Change it once, and it changes everywhere.

> **Tip:** Before publishing major changes to a widget, remember that the update will affect every page that uses it. Double-check your changes to make sure everything looks right.

---

## Widget properties

A property is a part of your widget that each spot can change, while everything else stays shared. For example, a pricing card can show a different title, photo and button link on each page, and still get every design change you make to the widget.

### Making a property

1. Open your widget with **Edit in Builder**.
2. Select the element each spot should change, such as the title.
3. Open **Settings**. **Widget properties** is at the top.
4. Turn on **Let people change this per spot**.
5. Under **What can people change?**, pick what changes: the text, the picture, the link, or whether it shows.
6. Give the property a name people see, such as "Title", and click **Save property**.
7. **Publish** the widget, so your live pages can use the property.

To see every property of the widget, select nothing and open **Settings**. Each property shows how many spots set their own value. You can rename a property there, and a rename keeps every spot's value. If you delete one, the window first says how many spots lose their own value.

### Giving a spot its own values

1. Open the page in the **Website Builder**.
2. Click the widget on the page to select that spot.
3. Open **Settings**. **Widget properties** is at the top, with a line such as "This only changes this pricing card."
4. Change a property, for example type a new title or click **Choose from my media** for a new photo.
5. **Publish** the page.

A property you have not changed shows the widget's own value in grey. A changed one has a blue dot. Click **Back to the Widget's value** to undo one. To change every spot at once, click **To change every spot, edit the Widget**, which opens the widget in a new tab.

---

## Variants

A variant is a ready-made version of your widget, such as "Quiet" or "Dark". It adds Styles to the widget and can give properties a starting value. Each spot picks the variant it uses.

### Making a variant

1. Open your widget with **Edit in Builder**, select nothing, and open **Settings**.
2. Under **Variants**, click **+ New variant**.
3. Type a name and click **Make variant**.
4. Pick the Styles the variant adds. Each spot that uses the variant gets these Styles.
5. Optionally, give a property a starting value. A value you leave alone follows the widget.
6. **Publish** the widget.

### Picking a variant for a spot

1. Select the widget on your page and open **Settings**.
2. Under **Widget properties**, open **Variant** and pick one. **The Widget's own look** goes back to the plain widget.
3. **Publish** the page.

A value you set on the spot wins over the variant's starting value. When you change a variant in the widget, every spot that uses it changes too. If you delete a variant, the spots that used it show the widget's own look.

---

## Managing Your Widgets

### Viewing All Your Widgets

You can see all your widgets in two places:

- **On the Widgets page:** Click **Widgets** in your site menu for the full list, with **Edit in Builder**, **Rename**, **Share with Your Other Sites** and **Delete** in each row's **⋮** menu.
- **In the Website Builder:** Open the **Add** panel and look under **My Widgets**. Every widget is listed there, ready to drag onto a page.

### Renaming a Widget

1. Open the **Widgets** page from your site menu.
2. Click the **⋮** menu on the widget's row, then **Rename**.
3. Type the new name and click **Save**.

Each widget needs its own name. If another widget already has that name, the window says so.

### Deleting a Widget

If you no longer need a widget, you can delete it from the **Widgets** page.

1. Open the **Widgets** page from your site menu.
2. Click the **⋮** menu on the widget's row, then **Delete**.
3. Click **Delete** to confirm. The button says **Deleting…** while it works, and the list then says "Deleted" with the widget's name.

The window says how many pages use the widget, for example "**Used on 6 pages.** Those spots will be empty." If the widget is your site's header or footer, the window says so first, and names the layout every page shows after you delete it. If the delete fails, the window stays open and says "We couldn't delete the widget. Nothing changed." Check your connection, then press **Delete** again.

Be careful when deleting widgets. If you delete a widget that is still placed on pages, those pages will show a blank space where the widget used to be. You will need to remove or replace the widget on each page.

> **Tip:** Before deleting a widget, check which pages use it. That way you can clean up those pages first and avoid any blank spots on your site.

### Sharing a Widget With Your Other Sites

If your workspace has more than one site, you can build a widget on one site and add it to the others. Each site gets its own separate copy, so changing one copy never changes the other.

**To share a widget:**

1. Open the **Widgets** page of the site that has the widget.
2. Click the **⋮** menu on the widget's row, then **Share with Your Other Sites**.
3. Click **Share Widget**. The list then shows a **Shared** label on that widget.

The shared copy is the **published** version of the widget, together with any widgets inside it. If **Share with Your Other Sites** is greyed out, point at it to read why. A header, footer or sidebar widget cannot be shared, and a widget needs to be published first. Unpublished changes stay on your site.

To send a newer version later, choose **Update the Shared Copy** from the same menu. Sites that already added the widget keep the copy they have.

**To add a shared widget to a site:**

1. Open the **Widgets** page of the site that should get the widget.
2. Click **Browse Shared Widgets**. Every widget shared in your workspace shows as a card, with a picture of how it looks in the theme of the site it came from.
3. Click **Add to This Site** on the card you want. A card that cannot be added says why on the card, for example when the Widget Builder is off on that site.

The widget appears in your **Widgets** list with a **Just added** label, and takes on your site's theme. If the name is taken, the card tells you the new name first, for example "Contact strip (2)". A message lists anything you need to check: an HTML block comes in empty when your role has no Custom Code access, and a form or menu panel is left empty because forms and pages are not shared between sites.

You can also see every shared widget in one place. In the sidebar, open **Sites** and click **Shared widgets**, then click **Add to a Site** on a card and pick the site.

**To stop sharing a widget:**

1. Open the **Widgets** page of the site that shared it.
2. Click the **⋮** menu on the widget's row, then **Stop Sharing**, and confirm.

Other sites can no longer add it. Copies that sites already added stay as they are. Only the person who shared the widget, the workspace owner or someone who manages sites can stop sharing it. If you delete a shared widget from its site, the shared copy stays in **Shared widgets** until you stop sharing it.

---

## Using a Widget as Your Header or Footer

Your site's header and footer usually use one of the layouts in **Site Settings → Appearance → Header & Footer**. You can show one of your own widgets there instead, on every page.

**What visitors see:** only the published version of the widget. Changes you save but do not publish stay in the Website Builder.

### Making your own header from your layout

The quickest way to start is a copy of the header you have now:

1. Open the **Website Builder** and click the header at the top of your page.
2. In the bar that shows on it, click **Make It My Own**.
3. Click **Make My Header** to confirm.

You get a new header widget named after your site (for example "Acme header"), made of **Site logo**, **Site menu** and **Menu button** blocks laid out like your current layout. It opens in the Website Builder, where you can change anything in it. Your site keeps showing your layout until you publish the widget with **Publish & Set as Header**. Click your footer instead to make your own footer. Its copy keeps everything your footer layout shows: your logo and footer text, your social links, your footer details, your footer menus, your copyright line and your extra footer text. The social links, footer details, copyright line and extra footer text are **Site details** blocks, so they still change when you change them in **Site Settings**, and the copyright line always shows this year.

> **Note:** The **Widget Builder** module must be on to make a header or footer widget. If it is off, the bar says so.

### Changing your header right on your page

In the Website Builder, your header and footer have a dashed outline, because they show on every page. Until you first click one, a hint under the top bar says so.

**Pick another layout:**

1. Click your header. **Settings** shows the layout it uses.
2. In **Settings**, pick a **Layout**. The page shows it at once, and **Save Layout** shows under the header's toolbar.
3. Click **Save Layout**. Every page shows the new layout.

**Work on your own header:** after **Make It My Own** (or **Edit Header** on a header of your own), the header opens right on your page:

- A blue ring marks the header, and the rest of the page is dimmed with the note **Locked while you edit the header**. Clicks on the page do nothing until you close the header.
- Click a block in the header to select it and change it in **Settings** and **Styles**. Drag new blocks from **Add** into the header.
- **Layers** lists only the header's blocks.
- The top bar's **Publish** and edit-mode switch are off while the header is open. The header's own toolbar has **Publish & Set as Header** (or **Publish**, once it is your header), and **Close**, which keeps your changes as a draft that visitors do not see.

If a publish fails, a red notice above the page says so, nothing changes on your site, and the header stays open so you can try again.

When your own header is in use, click it to see its toolbar: **Edit Header** opens it on the page again, and **Go Back to a Standard Layout** shows your layout again. The blocks inside your header cannot be selected from the page itself; a click selects the whole header. In **Layers**, your header and footer show as **Header:** and **Footer:** with their name and a lock.

Header and footer widgets have their own group in **Add**, **Header & Footer Widgets**. They never go on a page: click your header or footer to use one.

Footers work the same way.

### Setting your own header

A widget made for your header has a different Publish button in the Website Builder:

1. Open the **Widgets** page and click **Edit in Builder** on your header widget.
2. Add and arrange the blocks you want: your logo, links, a button, a notice.
3. Click **Publish & Set as Header** in the top bar.

Your widget is published and every page shows it at the top, in one step. If something goes wrong, nothing changes on your site. After that, the button says **Publish**, and each publish updates your header on every page. A footer widget works the same way, with **Publish & Set as Footer**.

You can also ask an AI tool you connect to WebNesting to build a header or footer widget and set it for you.

> **Note:** A widget must have something published before it can be your header or footer. An empty widget is refused, so your pages never show an empty header.

### Seeing and changing your own header

Open **Site Settings → Appearance → Header & Footer**. While your own header is in use, the **Header** part shows:

- **Your own header** with an **In use** badge, and the widget's name.
- When it was published. If you saved changes and did not publish them, it says how many, and that visitors still see the published version.
- A picture of your header as visitors see it.
- **Edit on My Home Page**, which opens the Website Builder on your home page with your header selected.

The layout pictures and the layout choices are hidden while your own header is in use.

While your header uses a layout, the **Header** part starts with **Change it on your page** and **Edit on My Home Page**. Under the footer layouts, **Edit on My Home Page** opens your home page with the footer selected, so you can make a footer of your own there.

### Going back to a standard layout

1. Open **Site Settings → Appearance → Header & Footer**.
2. Under **Header**, click **Go Back to a Standard Layout**.
3. Click **Use** and the layout's name to confirm.

Every page shows the layout again at once. Your widget stays on the **Widgets** page, so you can use it again later. The footer works the same way. You can do the same from your header's bar in the Website Builder.

### If you delete your header widget

Every page shows your header layout again. **Header & Footer** shows a notice with the deleted widget's name until you pick a layout, set another header, or make a new header of your own on your page.

---

## Connecting Widgets to Data

Widgets can do more than display static content. You can connect a widget to one of your site's data modules (like Articles, Events, or Products) to display dynamic content that updates automatically.

When creating or editing a widget's settings in the Dashboard:

- **Module** -- Choose which data source the widget should pull from (for example, Articles or Events).
- **Type** -- Choose how the widget retrieves data:
  - **All** -- Shows all items from the module.
  - **Search** -- Filters items based on a search term.
  - **First** -- Shows only the first matching item.
  - **Select** -- Lets you hand-pick specific items to display.
  - **Current** -- Displays the item that matches the current page context (useful on detail pages).
- **Limit** -- Controls how many items are shown.
- **Pagination** -- Choose whether to split results across multiple pages with navigation links.

This is a powerful way to create dynamic content blocks. For example, you could build a "Latest Blog Posts" widget that always shows your three most recent articles without you ever having to update it manually.

> **Tip:** If you are just getting started, you do not need to connect your widgets to data. Simple, static widgets work great for things like headers, footers, and contact blocks.

---

## Widgets vs. Components

Widgets are different from components. Components are the built-in building blocks (text, images, buttons, etc.), while widgets are custom elements you create yourself by combining components. You use components to build your widgets, and then you place those widgets on your pages just like you would place a component.

---

## Tips for Using Widgets Effectively

Widgets work best when you use them for content that appears on many pages or content that needs to stay consistent across your site. Here are some ideas.

### Headers and Footers

You can show your own widget as the header or footer of every page. See **Using a Widget as Your Header or Footer** above. When you need to update your links or footer information, you change the widget once, publish it, and every page updates.

### Call-to-Action Blocks

Create a widget for your main call-to-action, like a "Sign Up Now" or "Get a Free Quote" block. Place it on every page where you want to encourage visitors to take action. If you want to change the wording or the button color, update the widget and it changes everywhere.

### Sidebar Content

If your pages have a sidebar with the same content (like a list of services, a testimonial, or a newsletter signup form), turn that content into a widget. Drop it into the sidebar on each page and keep everything in sync.

### Contact Information Blocks

Your address, phone number, email, and business hours can go in a widget. Place it on your contact page, your about page, your footer -- anywhere visitors might look for it. When your hours change or you move offices, update the widget once and you are done.

### Promotional Banners

Running a sale or promotion? Create a banner widget and place it across your site. When the promotion ends, update or remove the widget and it disappears from every page.

### Latest Content Blocks

Connect a widget to your Articles or Events module to create blocks like "Latest News" or "Upcoming Events." These update automatically as you publish new content, so you never have to manually update them on each page.

> **Tip:** Start simple. Create one or two widgets for content you use on every page, and build from there as you get comfortable with the feature.
