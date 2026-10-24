# Animations and Interactions

**Last verified:** 2026-10-24 2:54pm

Make your page feel alive when someone scrolls, without writing any code. This guide covers the animations you can add to any block in the Website Builder. Every effect on a block lives in one place: **Motion**, in the Styler.

---

## Entrance Effects

An entrance effect plays once when a block scrolls into view. The block waits out of sight, then fades, slides or zooms in as the visitor reaches it.

### Add an Entrance Effect

1. Open your page in the Website Builder.
2. Click the block you want to animate: a heading, a picture, a card, a section.
3. Click **Styles** in the panel rail on the right, and stay on **Normal**.
4. Open **Motion** and click **Add motion**. The block gets **Fade up**, played **When it scrolls into view**.
5. To use another effect, pick it under **Effect**, such as **Zoom in**.
6. Scroll the page in the builder. The block plays its effect as it enters the screen.
7. Click **Publish** to put it on your live site.

To take the effect away, click the **×** next to it in the list.

A block can have one effect that plays as it scrolls into view. Its other effects can play all the time or on hover.

> **Tip:** The effect follows the size you style at, like any other style. Pick a size in the toolbar first, such as Desktop, to play the effect only on that size.

> **Tip:** Every block has this setting, except blocks that are only wrappers a visitor never sees as one block, such as a Spacer.

### The Effects

| Effect | What visitors see |
|---|---|
| Fade in | The block fades in. |
| Fade up, Fade down | It fades in while moving a short way up or down into place. |
| Fade in from the left, Fade in from the right | It fades in while moving in from the side. |
| Slide up, Slide down, Slide in from the left, Slide in from the right | It slides a full block-height into place, without a fade. |
| Zoom in | It grows from a small size to full size as it fades in. |
| Bounce in | It pops in and settles with a small bounce. |

If you have made your own animation, it appears in the same list, after the built-in effects.

### Fine-Tune the Effect

An effect that plays **When it scrolls into view** shows these settings under it:

- **Delay**: how long the block waits before it starts, in milliseconds. 1000 is one second, and the most you can set is 5000.
- **Start when it is ... of the way up the screen**: how much of the block must be on screen before it plays. **20% (standard)** works for most blocks. Pick **50%** for a tall block that should play when half of it shows.
- **Play only once**: on by default. Turn it off to play the effect again each time a visitor scrolls back to the block.
- **One child after another**: for a block that holds other blocks, such as a section with three cards. The cards start one after the other, this many milliseconds apart, instead of all at once. Leave it at 0 to play them together.

### Animate Word by Word

A heading can enter one word at a time, or one letter at a time.

1. In **Motion**, add an effect that plays **When it scrolls into view**, such as **Fade up**. **Animate word by word** is one of its settings.
2. Choose **Words** or **Letters**. **None** plays the block as one piece.
3. Click **Publish**.

Visitors see each word or letter play after the one before, once, as they scroll to the block. In the builder the text stays plain, so you can edit it. A screen reader still reads the text as one sentence, and visitors who ask for less motion see plain text with no movement. A link inside the text plays as one piece. **Letters** suits a short line, such as a title. A long paragraph reads better with **Words**.

### Blocks at the Top of the Page

A block that is already on the screen when a visitor opens your page shows at once, with no effect. The page then loads without a gap at the top. Effects play for the blocks a visitor scrolls down to. In the builder, a block you pick an effect for plays right away so you can see it.

### Visitors Who Ask for Less Motion

Some visitors turn on **Reduce motion** in their phone or computer. For them, every block shows at once and nothing moves. They still see the whole page. This follows their device setting, so you do not need to turn it on.

### Hover Effects

An effect can play when a visitor points at a block, such as a card that pulses.

1. Click the block, then open **Motion** in **Styles**.
2. Click **Add motion**.
3. Under **When it plays**, pick **On hover**.
4. Under **Effect**, pick an effect, such as **Pulse**.
5. Set how long it takes, its curve and how many times it plays. **More ways it plays** has the direction and the look before and after.
6. Click **Publish**.

The effect also plays when a visitor moves to the block with the **Tab** key, so people who use a keyboard see it too.

To play an effect all the time instead, such as a picture that keeps zooming in, pick **Always** under **When it plays**.

### On Click

An effect can play each time a visitor clicks a block, such as a button that pulses.

1. Click the block, then open **Motion** in **Styles**.
2. Click **Add motion**.
3. Under **When it plays**, pick **On click**.
4. Under **Effect**, pick an effect, such as **Pulse**.
5. To make it wait first, set **Delay**, in milliseconds.
6. Click **Publish**.

The effect also plays when a visitor moves to the block with the **Tab** key and presses **Enter** or **Space**. Your page makes any block with a click effect reachable by the **Tab** key, so you do not need to do anything for keyboard visitors. **Play again on each click** is on at first. Turn it off to play the effect on the first click only. A block can have one click effect.

In the builder, a click selects the block, so the effect does not play there. Open **Preview** to try it.

### Make One Block Act on Another

A rule makes something happen elsewhere on the page. For example: when a visitor clicks a button, a popup opens.

1. Click the block that starts it, such as the button, then open **Motion** in **Styles**.
2. Open **Make it do something else on the page**, under the effects, and click **Add a rule**.
3. Under **When**, pick what starts it, such as **Clicked**.
4. Under **then**, pick what happens, such as **Open a popup**.
5. Next to **on**, click **Pick on page**, then click the block it acts on, such as the popup. Press **Esc** to stop without picking.
6. Click **Publish**.

You can also pick by keyboard: after **Pick on page**, press **Tab** to move through the page and **Enter** to pick. If you pick nothing, the rule acts on the block itself.

| When | What starts it |
|---|---|
| Clicked | A visitor clicks the block, or presses Enter or Space on it. |
| Pointed at | A visitor points at the block. |
| Scrolls into view, Scrolls out of view | The block comes onto the screen, or leaves it. |
| The page opens | The page finishes loading. |
| Scrolled past | A visitor scrolls past the top of the block, plus the distance you set. |
| Its form is sent | The form the block is in is sent. |

| then | What happens |
|---|---|
| Open a popup | The popup you picked opens. |
| Go to a tab, Go to a slide | The tabs or slideshow you picked moves to the number you set. With **Scrolls into view**, **Move on by itself every** moves on by itself while the block is on screen. |
| Play a video, Pause a video | The video you picked plays or pauses. |
| Scroll to it | The page scrolls to the block you picked. |
| Add or remove a class | The class you type is added, or taken off if it is there. |
| Play an effect, Stop an effect | The effect you pick plays on the block, or stops. |

A rule belongs to the block it is on, at every screen size. If you delete the block a rule acts on, the rule shows **Target removed** and does nothing until you pick another one. To take a rule away, click **Remove** next to it.

In the builder, a click selects a block, so rules do not run there. Open **Preview** to try them, or open your published page.

Some things to know:

- **Pointed at** also runs when a visitor moves to the block with the **Tab** key.
- **Add or remove a class** switches each time the rule runs. With **Scrolled past**, the class comes off again when the visitor scrolls back up, which suits a header that changes once the page moves.
- **Move on by itself every** puts a small pause button on the tabs or slideshow. The tabs or slides also wait while a visitor points at them or uses them, and while the block is off the screen.
- In a repeated section, a rule acts on the block in the same copy as the block that starts it.
- A video with sound may not start on its own until the visitor has clicked somewhere on the page. This is a browser rule. A video set to **Play on its own** is muted, so it can start.
- Rules on blocks inside a widget do not run yet.

### Click Effects, Rules and Less Motion

When a visitor asks their device for less motion, click effects show their end look at once, with no delay. **Scroll to it** jumps instead of gliding. Tabs and slideshows do not move on by themselves, and a video does not start by itself. Clicks still open popups, change tabs and play videos.

### Tips

- Use one or two effects across a page. The same effect on every block feels calmer than a different one on each.
- Use a short **Delay** (200 to 400 ms) on the second and third block in a row, so they arrive in turn.

---

## Your Own Animations

You can design an animation of your own and use it anywhere a built-in effect goes. An animation of your own is called a **keyframe**. It belongs to the whole site, so every page can use it.

### Make a Keyframe

1. Click any block, then open the Styler and click **Advanced**.
2. Scroll down to **Keyframes** and click **New keyframe**.
3. Type a name, such as `rise-soft`, and click **Create**. A name starts with a lower-case letter and uses letters, numbers and dashes.
4. The new keyframe starts as a gentle fade up, so it already works. Change it the way you want.

### Change How It Moves

A keyframe has stops along a track. **Start** is how the block looks when the animation begins, and **End** is how it looks when it ends.

1. Click **Add a stop** to put a stop between Start and End. You can also click the track where you want the stop.
2. Under **Add a style at this stop**, pick a style: **Opacity**, **Move**, **Turn**, **Scale**, **Background colour**, **Text colour** or **Letter spacing**.
3. Set the style with the same control you use in **Normal**.
4. To move a stop, drag **Position**, or select the stop and press the Left or Right arrow key. Hold Shift to move it 10% at a time.
5. Click **Play on** and the block's name to see it run on the selected block.

To take a stop away, select it and click **Remove stop**. Start and End always stay.

### Use It

In the Styler, open **Motion** in **Normal**, click **Add motion**, and pick your keyframe under **Effect**. Your keyframes show first, under **Your keyframes**, before the built-in effects. Then choose **When it plays**:

- **When it scrolls into view**, to use it as an entrance effect.
- **Always**, to play it when the page opens.
- **On hover**, to play it when a visitor points at the block or tabs to it.

Click **Publish** to put it on your live site.

### Rename or Delete It

- **Rename:** click the pencil next to the keyframe and type the new name. Every block that uses it changes to the new name, so nothing stops playing.
- **Delete:** click the bin. A warning lists the blocks that use it. If you delete it, those blocks stop animating. **Undo** in the toolbar brings it back.

### Less Motion

If your own device asks for less motion, **Play** shows the End look for two seconds instead of moving. Visitors who ask for less motion see the End look too, with no movement.

### Ask an AI

An AI connected to your site through MCP can read your keyframes, change their stops and rename them, the same way you do in the Styler.

---

## Loops

A loop keeps a block moving gently, with no start or end. Use it for a small touch, such as a picture that floats or a badge that pulses.

### Keep a Block Moving

1. Click the block, then open **Motion** in **Styles**.
2. Under **Keep it moving**, pick **Float**, **Pulse** or **Spin**. Pick **None** to stop it.
3. Click **Publish**.

- **Float** lifts the block up and down a little.
- **Pulse** grows and shrinks the block a little.
- **Spin** turns the block around, slowly.
- **Marquee** scrolls a row of logos or words across the page, in a loop that never ends.

A loop works with any effect you set above it. It is for decoration, so use it on a small block, not on text people need to read.

### Add a Scrolling Logo Strip

1. Click the block that holds the logos or words, such as a **Logo strip**.
2. Open **Motion** in **Styles**.
3. Under **Keep it moving**, pick **Marquee**.
4. Pick a **Speed**: **Slow**, **Normal** or **Fast**.
5. Pick a **Direction**: **Left** or **Right**.
6. Click **Publish**.

The items scroll past one after another and start again with no gap. Each visitor sees a pause button on the strip, so they can stop it at any time. The strip also stops while a visitor points at it or moves through it with the keyboard. To keep it moving when someone points at it, turn off **Pause when a visitor points at it**. The pause button stays.

A screen reader reads each item once, and the Tab key reaches each link once.

### See It in the Builder

The builder keeps loops still while you edit, so your page does not move while you work. To see them move, click **Preview motion** in the top bar, next to the screen size menu. Click it again to hold them still. It starts off each time you open the builder, and it does not change your site.

### Visitors Who Ask for Less Motion

Visitors who turn on **Reduce motion** on their device see a loop standing still. A marquee shows all its items standing still, in as many rows as they need.

---

## Scroll Effects

A scroll effect ties a block's look to the page scroll. The block fades, moves, turns or grows as a visitor scrolls past it, and goes back when they scroll up. You can link four styles: **Opacity**, **Move**, **Turn** and **Scale**.

### Link a Style to the Scroll

1. Click the block, then open **Styles**.
2. Find the style. **Opacity** is in **Visibility**. **Move**, **Turn** and **Scale** are in **Transform**, under **Move, turn and scale on their own**.
3. Click the link button next to the style's name. It turns blue, and the style now shows **From** and **To**.
4. Set **From**, the look when the block comes onto the screen.
5. Set **To**, the look when it leaves the top of the screen.
6. Click **Publish**.

The builder links the style with sensible values to start: **Opacity** from 0 to 1, so the block fades in. Scroll the page in the builder to see the effect.

To unlink it, click the link button again. The block stays at its **From** value. **Undo** takes back a link or an unlink in one step.

### Choose Where It Plays

Under **Plays**, pick where on the screen the style changes:

- **The whole way up the screen**: from the moment the block comes in at the bottom until it leaves the top.
- **As it comes onto the screen**: the first half of the way.
- **Around the middle of the screen**: the middle half.
- **As it leaves the screen**: the last half.
- **Set my own start and end**: pick **Starts at** and **Ends at** yourself. 0% is when the block comes in at the bottom of the screen. 100% is when it leaves the top.

Each linked style has its own **Plays**. To start and stop the whole effect at once, open **Motion**. Under **Scroll effect**, set **Starts at** and **Ends at**.

### A Value Written by Hand

If you typed a style's value by hand in a form the controls cannot read, you cannot click the link button. Clear the value first, then link it.

### Visitors Who Ask for Less Motion

Visitors who turn on **Reduce motion** on their device see each style at its **To** value, standing still. Make **To** the look you want the block to have when it is done.

---

## Stick While Scrolling

A block can stay on screen while visitors scroll. A whole section can hold its content on screen for a few screens of scrolling, so what is inside can move with the scroll. This is the scrolling-story effect.

### Stick a Block at the Top

1. Click the block, then open **Position** in **Styles**.
2. Under **Stick while scrolling**, pick **Stick at the top**.
3. Click **Publish**.

The block scrolls as normal until it reaches the top of the screen. Then it stays there while the block around it scrolls past. A heading above a long article is a good use. To stop it, pick **Off**.

If you set **Position** for one screen size only, such as a computer, the block sticks at that size only.

### Hold a Section for a Few Screens

1. Click the section, then open **Position** in **Styles**.
2. Under **Stick while scrolling**, pick **Hold its content for 1 screen**, **1.5 screens**, **2 screens** or **3 screens**.
3. Click **Publish**.

The first block inside the section stays on screen while visitors scroll that far. Put the headline, picture and text you want to keep in view inside that first block. Only sections can do this, and it holds the section the same way at every screen size. To stop it, pick **Off**.

### Move What Is Inside

While the section holds its content, link the look of a block inside it to the scroll. Follow [Link a Style to the Scroll](#link-a-style-to-the-scroll) for that block. Under **Plays**, the line says "Its section, Our story, holds its content while scrolling, so the section's scroll moves it." The section's scroll moves the block: it starts when the section begins to hold, and it ends when the section lets go.

### Visitors Who Ask for Less Motion

Visitors who turn on **Reduce motion** on their device see the section as normal content. It does not hold its content, and each linked style shows its **To** value. A block you set to **Stick at the top** still sticks.

---

## Smooth Page Changes

When a visitor clicks a link on your site, the next page can fade in over the last one. Without it, the screen can flash for a moment between pages. This setting is for your whole site, so it lives in Site Settings, not in the Website Builder.

### Turn It On

1. In the site menu, open **Settings** and click **Site Settings**.
2. Under **Appearance**, click **Header & Footer**.
3. Scroll to **Between pages**.
4. Turn on **Fade smoothly between pages**.
5. Click **Save Changes**. Your site shows the fade at once. You do not need to publish.

To go back to normal page changes, turn the setting off and click **Save Changes**.

### What Visitors See

- **A short fade** from one page to the next, on browsers that support it, such as Chrome, Edge and Safari.
- **A normal page change** in a browser that does not support it. Nothing breaks.
- **A normal page change** for visitors who ask their device for less motion. They never see the fade.
- **No fade in the Website Builder.** The builder never fades, so editing stays still. Open your live site to see it.

### Ask an AI

An AI connected to your site through MCP can turn smooth page changes on or off, the same way you do in Site Settings.
