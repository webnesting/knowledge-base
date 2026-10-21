# Styling Your Page Elements

**Last verified:** 2026-10-21 11:54am

Every element on your page -- text, images, buttons, sections -- can be customized to look exactly the way you want. This guide walks you through the styling tools in WebNesting's Website Builder.

---

## What Is the Styler?

The Styler is the **Styles** panel, opened from the icon rail on the right side of the builder. It controls how things look -- colors, spacing, size, shadows, and more.

Think of the Styler as a set of dials and switches for each element on your page. Select something, and the Styler shows you all the ways you can customize it.

![The Styler panel showing Layout, Position, and Spacing controls for a selected element](../images/website-builder/styler-panel.png)

---

## How to Open the Styler

1. Open your page in the Website Builder.
2. Click on any element on your page (a heading, image, section, button, etc.).
3. Click **Styles** in the panel rail on the right.
4. You will see different sections you can expand, like Spacing, Layout, Position, and more. The Styler remembers which sections you keep open or closed, on every page and every element, until you change them.

> **Tip:** If Styles shows your own CSS instead of the element controls, nothing is selected. Click directly on an element -- clicking empty space deselects everything. See [Your Own CSS](#your-own-css) for that view.

---

## Fine-Tuning Values with Your Keyboard

Every number and text box in the Styler works like a design tool.

- **Type a value.** The page shows it after a short pause, so you see the result without it flickering on every key.
- **Press Enter** to apply the value. If the box is inside a small editor (like a spacing value), the editor stays open.
- **Press Esc** to go back to the value you started with. In a small editor, press Esc once to undo your typing and a second time to close the editor.
- **Press the up or down arrow** to nudge a number by one step (for example 1px, or 0.1 for rem).
- **Hold Shift** with the arrows for bigger steps (ten times as big), or **hold Alt** (Option on a Mac) for smaller steps (a tenth of a step).
- **Scroll with the mouse wheel** over a box you are typing in to nudge it the same way. Hold Shift for bigger steps.
- **Drag** a spacing value in the Spacing diagram, or a margin or padding handle on the page, to change it with your mouse. Hold Shift or Alt while you drag for bigger or finer steps. Press Esc while you drag to cancel.

Each change is one step in your undo history. Press **Cmd+Z** (Ctrl+Z on Windows) once to undo the whole change, however you made it.

> **Tip:** Hover over the **?** next to a length or number setting to see these keys as a reminder.

> **Working with a teammate?** Esc only takes back your own change. If a teammate changes something while you type, their change stays.

---

## Colors

You can change the background color and text color of most elements.

### Changing a Background Color

1. Select the element you want to change.
2. In the Styler, find the **Background** section.
3. Click the color swatch (the small colored square).
4. A color picker will appear. Choose your color by clicking in the color area, or type in a specific color code.
5. The change appears instantly on your page.

### Changing Text Color

1. Select the text element.
2. In the Styler, find the **Typography** section.
3. Click the color swatch next to **Color**.
4. Pick your color from the color picker.

### Using Your Theme's Colors

Next to each color swatch is a **Theme token** menu. It lists the colors your theme already has, each with a plain name such as **Main color**, **Page background** or **Text on main-color buttons**. The names sit in groups: **Main colors**, **Made from your main colors**, **Messages** and **Grays and neutrals**. Type in the search box to find one.

Pick a theme color instead of a color code. When you change the theme's colors later, every element that uses a theme color changes with it. A color a theme adds later shows up in the menu on its own.

### Color Contrast

When choosing text colors, make sure your text is easy to read against its background. Dark text on a light background or light text on a dark background works best. Avoid putting light gray text on a white background, for example -- your visitors will struggle to read it.

> **Tip:** If your text seems hard to read, try increasing the contrast. Use very dark colors (close to black) on light backgrounds, or very light colors (close to white) on dark backgrounds.

---

## Spacing

Spacing controls how much room an element has around and inside it. Think of it like the breathing room around your furniture in a room.

### Two Types of Spacing

- **Padding** is the space *inside* an element, between its edge and its content. Imagine the cushioning inside a picture frame -- it pushes the content away from the border.
- **Margin** is the space *outside* an element, between it and the things around it. Imagine the gap between two picture frames hanging on a wall.

### How to Adjust Spacing

1. Select the element you want to adjust.
2. In the Styler, find the **Spacing** section.
3. You will see a visual box diagram. The outer box represents the margin, and the inner box represents the padding.
4. Click on any value in the diagram (top, right, bottom, or left).
5. A small editor will appear where you can type a number, drag a slider, or choose a preset value.

### Quick Preset Values

When you click a spacing value, you will see preset buttons like 0, 4, 8, 16, 24, and 32. These let you quickly set common spacing amounts without typing.

> **Tip:** Start with even, consistent spacing. Using the same spacing values throughout your page (like 16 for small gaps and 32 for large gaps) creates a clean, professional look.

---

## Size

Size controls how wide and tall an element is.

### Width and Height

1. Select the element.
2. In the Styler, look for the **Width** and **Height** controls. These may appear in the Spacing or Size section.
3. Type a number or drag the slider to set the size.
4. Choose your unit from the dropdown next to the number.

### Understanding Units

- **Pixels (px)** -- An exact, fixed size. Use pixels when you want something to be a specific size no matter what. For example, "200px" will always be 200 pixels wide.
- **Percent (%)** -- A size relative to the parent container. If you set something to "50%", it will take up half of its parent's width. Great for flexible, responsive layouts.
- **Auto** -- Lets the browser decide the best size based on the content. This is often the default and works well in most cases.

### When to Use Each Unit

| Unit | Best For | Example |
|------|----------|---------|
| Pixels (px) | Icons, specific image sizes, exact spacing | A logo that should always be 150px wide |
| Percent (%) | Flexible layouts, columns, responsive elements | A sidebar that should always be 30% of the page width |
| Auto | Letting content determine the size naturally | A text block that grows with the amount of text |

> **Tip:** When in doubt, leave width and height on "auto." Elements usually size themselves correctly based on their content.

---

## Borders

You can also add borders to elements. In the Styler, look for the Border section where you can set the border width, style (solid, dashed, dotted), color, and corner radius for rounded corners.

---

## Opacity

The Opacity control lets you make elements partially transparent. A value of 1 is fully visible, and 0 is completely invisible.

---

## Shadows

Shadows add depth to your elements, making them look like they are lifted off the page. This is great for cards, buttons, and images.

### Adding a Shadow

1. Select the element.
2. In the Styler, find the **Box Shadow** section (or **Text Shadow** for the shadow behind text).
3. Click **Add Box Shadow**. The new shadow appears as a row in the list, and its settings open below the list.
4. Adjust the shadow settings:
   - **The square pad** -- Drag the dot to move the shadow. You can also click the pad and use the arrow keys; hold Shift to move 10 at a time.
   - **X** and **Y** -- How far the shadow moves left or right, and up or down.
   - **Blur** -- How soft or sharp the shadow edges are. Higher blur makes a softer shadow.
   - **Spread** -- How large the shadow is overall.
   - **Side** -- **Outset** puts the shadow outside the element; **Inset** puts it inside.
   - **Color** -- The color of the shadow (usually a semi-transparent black or gray).

### Working With Several Shadows

An element can have several shadows. Each one is a row in the list, with a small picture of the shadow and a short description.

- **Edit a shadow:** click its row. Its settings open below the list.
- **Change the order:** drag a row by its handle (the dots on the left). Or open the row's **⋮** menu and choose **Move up** or **Move down**. The first shadow in the list is drawn on top.
- **Hide a shadow:** click the eye icon. The shadow stays in the list but is not drawn. Click the eye again to show it. A hidden shadow is kept when you save and publish.
- **Copy a shadow:** open the row's **⋮** menu and choose **Duplicate**. The copy appears below the original.
- **Remove a shadow:** open the row's **⋮** menu and choose **Remove**.

Each of these changes is one step, so one **Undo** puts it back.

If a shadow was written by hand in a form the settings cannot show (for example, sizes in `rem`), its row says **Custom**. Click the row to edit its text directly. It is kept exactly as written.

### Shadow Tips

- A subtle shadow (small offset, moderate blur, light color) looks professional. Try something like X: 0, Y: 2, Blur: 8 for a gentle lift effect.
- Avoid very dark or very large shadows unless you want a dramatic effect.
- Two soft shadows often look more natural than one: a small, tight shadow under a larger, softer one.

---

## Display and Layout

The Display and Layout controls determine how an element arranges the items inside it. This is how you put things side by side, stack them vertically, or create grids.

### Display Options

In the Styler, the **Layout** section shows display buttons:

- **Block** -- The element takes up the full width available and stacks on top of the next element. This is the default behavior for most elements.
- **Flex** -- Items inside the element can be arranged side by side or with flexible spacing. Great for navigation bars, card rows, and any horizontal layout.
- **Grid** -- Items inside the element are arranged in a structured grid of rows and columns. Perfect for image galleries, feature grids, and evenly spaced layouts.
- **None** -- Hides the element completely.

### Using Flex Layout

When you choose Flex, a gear icon appears. Click it to open additional layout options:

1. **Direction** -- Choose whether items flow left-to-right (row) or top-to-bottom (column).
2. **Wrap** -- Choose whether items wrap to the next line when they run out of space, or if they squeeze together.
3. **Justify** -- Controls how items are spread out along the main direction (start, center, end, space between, etc.).
4. **Align** -- Controls how items line up in the other direction (top, center, bottom, stretch).

### Using Grid Layout

When you choose Grid, a gear icon appears with grid-specific options:

1. Set the number of columns.
2. Set the number of rows (optional).
3. The items inside will automatically fill the grid cells.

### Gap (Spacing Between Items)

When using Flex or Grid, you can set the **Gap** -- the space between each item. This is different from margin because it only adds space between items, not around the outside.

1. Find the **Gap** control in the Layout section.
2. Drag the slider or type a number.
3. Click the link icon to set different gaps for horizontal and vertical spacing, or keep them the same.

On a phone, the space between side-by-side items in a grid row shrinks if it would make the row wider than the screen. The space above and below each item stays as you set it.

> **Tip:** Using Flex with "center" alignment and "space between" justification is a great way to create a navigation bar where the logo is on the left and the menu is on the right.

---

## Position

The Position controls determine where an element sits on the page.

### Position Types

Most of the time, you will not need to change an element's position. But when you do, here are the options:

- **Static** -- The default. The element flows naturally with the rest of the page content.
- **Relative** -- The element stays in its normal place but can be nudged up, down, left, or right from where it would normally be.
- **Absolute** -- The element is removed from the normal flow and placed at a specific spot within its parent container. Useful for overlays and badges.
- **Fixed** -- The element stays in the same spot on the screen even when the visitor scrolls. Useful for sticky headers or floating buttons.
- **Sticky** -- The element scrolls normally until it reaches a certain point, then sticks in place. Great for section headers that should remain visible.

### Anchor Presets

When you choose Absolute, Fixed, or Sticky, a set of nine anchor points appears in the Styler. These let you quickly position the element:

- Top-left, top-center, top-right
- Middle-left, center, middle-right
- Bottom-left, bottom-center, bottom-right

Click any anchor point to snap the element to that position.

---

## Clearing and Resetting Styles

If you have made changes and want to start fresh, you can clear individual style properties.

### Clearing a Single Property

1. Find the property you want to reset in the Styler.
2. Look for a clear button (an "x" icon) next to the property value.
3. Click it to remove your custom value and return to the default.

### Clearing Values from the Spacing Box

1. Click on the value you want to clear in the visual spacing diagram.
2. In the popover that appears, look for preset buttons.
3. Click the "0" preset to remove spacing, or use the clear button to reset the value entirely.

> **Tip:** Clearing a style does not delete the element -- it just removes your customization, letting the default or theme style show through.

---

## Your Own CSS

The Styler can do most things with its controls. For anything it cannot do yet, write your own CSS. In a website's builder, the top of the **Styles** panel has a **Stylesheet** button beside **Normal** and **Advanced**. With nothing selected, Styles opens on it.

![The Styles panel in Stylesheet mode, with the Whole site, This layout and This page switch above the CSS editor](../images/website-builder/styler-stylesheet.png)

### Where Your CSS Applies

Pick where the CSS applies with the switch at the top:

- **Whole site** -- every page of your site.
- **This layout** -- every page that uses the same layout as the page you are editing. The line under the switch names the layout and counts its pages. If you delete a layout, its CSS and that CSS's history are deleted with it.
- **This page** -- only the page you are editing.

Your CSS comes after the Styler's own styles: first the whole site's, then the layout's, then the page's. So when two rules match the same element equally, the later one wins.

### Writing and Publishing CSS

1. Open your page in the Website Builder.
2. Click on empty space so that nothing is selected, then click **Styles**. Or click **Stylesheet** at the top of Styles.
3. Choose **Whole site**, **This layout** or **This page**.
4. Type your CSS. The page in the builder shows it as you type.
5. Click **Publish** in the builder. Your CSS goes live on your site with the page.

What you type saves as a draft by itself. Visitors do not see it until you publish. The line under the editor says "Draft. Publish puts it on your live site." until you do.

> **Tip:** Publishing a page puts the drafts of all three places live: the whole site's, the layout's and the page's. A draft you saved on another page goes live with it too.

### What Is Removed

CSS that can load or run code is removed when it saves. This keeps your site safe. Under the editor, a yellow box lists each part removed and why. For example:

- `@import` -- it loads another style sheet from outside this field.
- `</style>` -- it would end the style sheet early and let what follows run as page code.
- `expression(`, `behavior:` and `-moz-binding:` -- they run script in old browsers.
- A `url(` that points somewhere other than a web address or an image.

Everything else stays exactly as you typed it.

### Version History

Click **History** under the editor to see earlier versions of that place's CSS, newest first. Click **Load into Editor** to put a version back in the editor. It saves as your draft, and it goes live when you publish.

### Who Can Change It

Only people with the **Custom Code** permission can change your CSS or publish it. Site owners and Admins have it. People who may only view it see the CSS read-only, with the line "Only people with the Custom Code permission can change this CSS. Ask your site owner." When they publish a page, their page changes go live, and your CSS drafts stay as they are. People without the permission see "Only people with the Custom Code permission can see your site's CSS." See [Team and Permissions](../dashboard/team-and-permissions.md#builder-access).

### Code That Also Runs on the Page

When your site or the page also loads code from other services, a line under the editor says so, for example "This page also loads code from www.googletagmanager.com." Its links open **Code from Other Services** or the page's **Custom Code**, where that code is changed.

---

## Breakpoint Indicators

Some properties in the Styler show small colored dots or badges. These tell you that the property has different values set for different screen sizes (desktop, tablet, mobile). You will learn more about this in the Responsive Design guide.

---

## Tips for Professional-Looking Design

1. **Be consistent.** Use the same colors, spacing, and fonts throughout your site. Consistency is the single biggest factor in making a site look professional.

2. **Use whitespace generously.** Do not crowd elements together. Give your content room to breathe by adding padding and margin.

3. **Limit your color palette.** Pick 2-3 main colors and stick with them. Too many colors looks cluttered.

4. **Use subtle shadows.** A gentle shadow can make cards and buttons feel more interactive without being distracting.

5. **Align everything.** Elements that line up with each other look intentional and polished. Use consistent margins and the same column widths to keep things aligned.

6. **Less is more.** When in doubt, simplify. Remove decorations, reduce the number of different font sizes, and keep your layouts clean.
