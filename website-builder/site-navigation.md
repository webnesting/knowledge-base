# Setting Up Site Navigation

**Last verified:** 2026-10-27 11:40am

Navigation is how visitors find their way around your website. Good navigation helps people quickly get to the pages they need, whether they are browsing on a desktop or a phone. This guide covers how navigation works in WebNesting, how to control which pages appear in your menus, and tips for creating a clear, easy-to-use navigation structure.

---

## How Navigation Works

Your site's navigation menus are built automatically from your pages. You do not need to create menus by hand or type out lists of links. Instead, WebNesting looks at each page's menu visibility settings and includes it in the appropriate menus.

Every page has checkboxes that control which menus it appears in. When you check a box, that page shows up in that menu. When you uncheck it, the page is hidden from that menu. The order pages appear in your navigation follows the same order they are listed in the **Pages** list in your site menu.

For full details on how to find and change menu visibility settings for a page, see **[Managing Pages in the Builder](page-management.md)** -- specifically the Menu Visibility section.

---

## Setting Up Header Navigation

The header navigation is the main menu at the top of your site. It is usually the first thing visitors look at when they want to find a page, so it is the most important menu to get right.

### How to Add a Page to the Header Menu

1. Open the **Website Builder** and click **Pages** in the panel rail on the right.
2. Point at the page's row and click the **gear icon** (**Page settings for** that page).
3. In the page properties, find the **Menu Visibility** checkboxes.
4. Check the **Header** box.
5. Click **Save**.

That page will now appear in the main navigation at the top of your site.

### Controlling the Order of Pages

The order of items in your header navigation matches the order of pages in your pages list. The first page in the list appears first in the menu, and so on.

To change the navigation order:

1. Close the builder and open your site's dashboard. In the site menu, click **Pages**.
2. Rearrange your pages by dragging them into the order you want.
3. The header navigation will update to match the new order.

> **Tip:** Put your most important pages first in the list. Visitors tend to pay more attention to the first few items in a menu.

---

## Footer Navigation

The footer is the section at the bottom of every page on your site. It is a great place for links that visitors might need but that do not belong in the main header menu.

### Footer Menu Visibility Options

WebNesting gives you three footer-related checkboxes in the menu visibility settings:

- **Footer** -- The main footer navigation area. Use this for general links visitors might look for at the bottom of the page.
- **Footer Secondary** -- A secondary footer navigation area, often used for less prominent links.
- **Footer Important** -- A highlighted footer section, useful for links you want to stand out (like a phone number or a "Get Started" button).

### Adding a Page to the Footer

1. Open the page properties by clicking the **gear icon** on the page's row in the **Pages** panel.
2. Find the **Menu Visibility** checkboxes.
3. Check the footer option you want -- **Footer**, **Footer Secondary**, or **Footer Important**.
4. Save your changes.

### What Belongs in the Footer

Footer navigation is best for pages that visitors may need but that do not deserve top billing in the main menu. Common footer links include:

- Contact information and contact form pages
- Legal pages like privacy policy and terms of service
- About us or company information
- Sitemap or help pages

> **Tip:** You can include the same page in both the header and footer navigation by checking both boxes. This is common for important pages like "Contact Us."

---

## Dropdown Menus via Parent and Child Pages

If your site has pages organized into parent and child relationships, your navigation will automatically create dropdown menus. When a visitor hovers over or clicks a parent page in the header, its child pages appear in a dropdown beneath it.

### How It Works

When you create a child page under a parent, and both the parent and child pages have their **Header** menu visibility checked, the child pages will appear as a dropdown under the parent in the header navigation.

For example, if you have a "Services" page with child pages called "Web Design," "Branding," and "Consulting," visitors will see "Services" in the header menu. When they hover over it, a dropdown will show the three child pages.

To show a parent's child pages as the whole header menu, on the parent and on every page under it, set the parent's **Sub-Menu** to **Children**. See [Giving a Section Its Own Header Menu](../dashboard/managing-pages.md#giving-a-section-its-own-header-menu).

Keyboard visitors press Tab to move through the menu. On a menu item that has a third-level menu, Tab also stops on its arrow: press Space to open or close that menu. A closed menu is skipped by Tab.

### Creating Child Pages

To create a child page:

1. Open the **Pages** panel in the builder.
2. Find the page you want to be the parent.
3. Point at the page's row and click **New sub-page under** that page (the arrow icon at the end of the row).
4. Fill in the page details and click **Save**.

For a full walkthrough, see **[Managing Pages in the Builder](page-management.md)** -- the section on creating child pages.

### Best Practices for Dropdown Menus

- Keep dropdowns to one or two levels deep. A dropdown inside a dropdown inside another dropdown is confusing and hard to use, especially on phones.
- Limit the number of items in each dropdown. Five to seven items is a comfortable maximum.
- Make sure the parent page itself has useful content. Visitors will click on it directly, not just hover over it.

---

## Mega Menus

A mega menu opens a wide panel below your header instead of a short list. It suits a site with many pages: the panel shows an item's pages side by side in columns, with the pages under each one listed below it. You can also fill a panel with your own blocks, such as a picture, a short text and a button.

### Turn On a Mega Menu

A mega menu is a style of the **Site menu** block, the menu in your own header (see [Widgets](widgets.md) for how to make your own header).

1. Open your header in the **Website Builder**.
2. Click your **Site menu**.
3. On the menu's bar, under **Submenu style**, click **Mega menu**.
4. Click **Settings** and set **Levels shown** to **3** to list the pages under each column. With **2**, a panel shows only the columns.
5. Publish your header.

Each top item that has pages under it now opens a panel. An item with no pages under it stays a plain link.

### Choose What a Panel Shows

On the menu's bar, click an item under **Open on the page**. The builder opens that item's panel, and **What opens** shows what the panel holds:

- **Its pages** -- The item's pages, in columns. This is where every item starts.
- **A widget** -- One of your widgets. Pick it in **What opens**, and the panel shows that widget instead of the pages.
- **+ New Panel** -- Makes a new widget named after the item (for example "Services menu panel") with three columns, and picks it for the item, and opens it on your page. In the panel widget's **Settings**, **Columns** picks two, three or four columns.

### Change a Panel on Your Page

Click **Edit Panel** on the menu's bar. The panel opens under its item. The rest of the page is dimmed and locked while you work on it.

1. Drag blocks from the **Add** panel into the panel's columns. Each column is a drop area.
2. Click a block in the panel to change it.
3. Click **Done** to keep your changes as a draft, or **Publish** to show them to visitors.

A panel widget shows on your site once you publish it. Until then, the panel shows the item's pages.

If you are already changing your header on the page, **Edit Panel** opens the panel widget on its own page in the builder instead. To change it on the page, click **Close** on your header's bar first.

### How Visitors Use It

- **With a mouse** -- Point at an item for a moment and its panel opens. Moving the pointer into the panel keeps it open. Move away, click somewhere else on the page or press Escape to close it.
- **With a keyboard** -- Press Tab to reach the arrow beside an item, then press Enter or Space to open its panel. The Down arrow moves into the panel and the Up arrow moves back. The Left and Right arrows move between the top items. Escape closes the panel and puts you back on the arrow.
- **On a phone** -- The panel opens as a section under its item inside the phone menu, one column wide. Tap the arrow beside an item to open or close its section.

Visitors who turn on reduced motion on their device see the panel appear without its slide.

---

## Using Breadcrumbs and Sitemap Components

Beyond your header and footer menus, WebNesting offers two components that help visitors navigate your site.

### Breadcrumbs

Breadcrumbs are a trail of links that show visitors where they are on your site. They look something like this: Home > Services > Web Design. Each part is a clickable link, so visitors can jump back to any level.

Breadcrumbs are especially helpful on sites with many pages or deep page hierarchies. They give visitors a sense of where they are and an easy way to go back.

To add breadcrumbs to a page:

1. Open the page in the Website Builder.
2. Open the **Add** panel and drag a **Breadcrumbs** component from the **Site modules** group onto the page.
3. Place it near the top of the content area, below the header.

The breadcrumbs will automatically generate based on the page's position in your site hierarchy. For details on adding components, see **[Adding Components to Your Page](adding-components.md)**.

### Sitemap Component

The Site Map component displays a complete list of all the pages on your site. It is useful for creating a dedicated sitemap page that helps visitors find what they are looking for and helps search engines discover all your content.

To add a sitemap:

1. Open the page where you want the sitemap to appear.
2. Open the **Add** panel and drag a **Site Map** component from the **Site modules** group onto the page.
3. The component will automatically list all your published pages.

> **Tip:** A dedicated sitemap page is a nice touch for larger websites. Link to it from your footer so visitors always have a way to see everything your site offers.

---

## Tips for Effective Navigation

Good navigation can make or break a visitor's experience. Here are some guidelines to keep your site easy to use.

### Keep It Simple

Aim for seven items or fewer in your main header navigation. When there are too many options, visitors feel overwhelmed and have a harder time finding what they need. If you have more pages, group related ones under parent pages to create tidy dropdowns.

### Use Clear, Descriptive Page Names

Page names like "Services," "About Us," and "Contact" tell visitors exactly what they will find. Avoid clever or vague names that might confuse people. "Our Story" is fine, but "The Journey" might leave visitors guessing.

### Put the Most Important Pages First

Visitors tend to notice and click on the first and last items in a navigation menu more than the ones in the middle. Put your highest-priority pages at the beginning of the list.

### Mobile Navigation

On mobile devices, your navigation menu automatically collapses into a hamburger menu (three horizontal lines). Visitors tap the icon to open the menu. Keyboard visitors press Tab to reach the icon, which shows an outline, and press Space to open the menu. On a phone, a menu item with child pages has a small arrow beside it. Tap it to show the child pages, or reach it with Tab and press Space. Use the responsive preview in the builder to check that your menus are easy to open and read on all screen sizes.

### Active Page Highlighting

The current page is automatically highlighted in the navigation, so visitors always know where they are on your site.

### Do Not Hide Important Pages

If a page is important to your visitors or your business, make sure it is visible in at least one navigation menu. A page that exists but cannot be found from any menu is essentially invisible to most visitors.

### Check the Include on Sitemap Setting

For search engine visibility, make sure your important pages have the **Include on Sitemap** checkbox checked in their menu visibility settings. This helps search engines discover and index your content.

---

## Next Steps

- **[Managing Pages in the Builder](page-management.md)** -- Learn how to create pages, set properties, and control menu visibility
- **[Adding Components to Your Page](adding-components.md)** -- Add breadcrumbs, sitemaps, and other navigation components
- **[Layouts and Structure](layouts-and-structure.md)** -- Understand how layouts define your header and footer areas
- **[Responsive Design](responsive-design.md)** -- Make sure your navigation works well on all screen sizes
