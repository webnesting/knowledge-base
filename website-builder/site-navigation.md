# Setting Up Site Navigation

**Last verified:** 2026-05-11 9:00am

Navigation is how visitors find their way around your website. Good navigation helps people quickly get to the pages they need, whether they are browsing on a desktop or a phone. This guide covers how navigation works in WebNesting, how to control which pages appear in your menus, and tips for creating a clear, easy-to-use navigation structure.

---

## How Navigation Works

Your site's navigation menus are built automatically from your pages. You do not need to create menus by hand or type out lists of links. Instead, WebNesting looks at each page's menu visibility settings and includes it in the appropriate menus.

Every page has checkboxes that control which menus it appears in. When you check a box, that page shows up in that menu. When you uncheck it, the page is hidden from that menu. The order pages appear in your navigation follows the same order they are listed in your pages panel.

For full details on how to find and change menu visibility settings for a page, see **[Managing Pages in the Builder](page-management.md)** -- specifically the Menu Visibility section.

---

## Setting Up Header Navigation

The header navigation is the main menu at the top of your site. It is usually the first thing visitors look at when they want to find a page, so it is the most important menu to get right.

### How to Add a Page to the Header Menu

1. Open the **Website Builder** and go to the **Pages** panel in the left sidebar.
2. Click the **document icon** next to the page you want to include in the header.
3. In the page properties, find the **Menu Visibility** checkboxes.
4. Check the **Header** box.
5. Save your changes.

That page will now appear in the main navigation at the top of your site.

### Controlling the Order of Pages

The order of items in your header navigation matches the order of pages in your pages list. The first page in the list appears first in the menu, and so on.

To change the navigation order:

1. Open the **Pages** panel in the left sidebar.
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

1. Open the page properties by clicking the **document icon** next to the page in the **Pages** panel.
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

### Creating Child Pages

To create a child page:

1. Open the **Pages** panel in the builder.
2. Find the page you want to be the parent.
3. Click the **plus icon** next to that page's name.
4. Fill in the page details and save.

For a full walkthrough, see **[Managing Pages in the Builder](page-management.md)** -- the section on creating child pages.

### Best Practices for Dropdown Menus

- Keep dropdowns to one or two levels deep. A dropdown inside a dropdown inside another dropdown is confusing and hard to use, especially on phones.
- Limit the number of items in each dropdown. Five to seven items is a comfortable maximum.
- Make sure the parent page itself has useful content. Visitors will click on it directly, not just hover over it.

---

## Using Breadcrumbs and Sitemap Components

Beyond your header and footer menus, WebNesting offers two components that help visitors navigate your site.

### Breadcrumbs

Breadcrumbs are a trail of links that show visitors where they are on your site. They look something like this: Home > Services > Web Design. Each part is a clickable link, so visitors can jump back to any level.

Breadcrumbs are especially helpful on sites with many pages or deep page hierarchies. They give visitors a sense of where they are and an easy way to go back.

To add breadcrumbs to a page:

1. Open the page in the Website Builder.
2. Drag a **Breadcrumbs** component from the **Navigation** category in the left sidebar onto the page.
3. Place it near the top of the content area, below the header.

The breadcrumbs will automatically generate based on the page's position in your site hierarchy. For details on adding components, see **[Adding Components to Your Page](adding-components.md)**.

### Sitemap Component

The Sitemap component displays a complete list of all the pages on your site. It is useful for creating a dedicated sitemap page that helps visitors find what they are looking for and helps search engines discover all your content.

To add a sitemap:

1. Open the page where you want the sitemap to appear.
2. Drag a **Sitemap** component from the **Text** category in the left sidebar onto the page.
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

On mobile devices, your navigation menu automatically collapses into a hamburger menu (three horizontal lines). Visitors tap the icon to open the menu. Use the responsive preview in the builder to check that your menus are easy to open and read on all screen sizes.

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
