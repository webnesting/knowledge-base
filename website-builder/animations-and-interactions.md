# Animations and Interactions

**Last verified:** 2026-10-22 3:05pm

Make your page feel alive when someone scrolls, without writing any code. This guide covers the animations you can add to any block in the Website Builder.

---

## Entrance Effects

An entrance effect plays once when a block scrolls into view. The block waits out of sight, then fades, slides or zooms in as the visitor reaches it.

### Add an Entrance Effect

1. Open your page in the Website Builder.
2. Click the block you want to animate: a heading, a picture, a card, a section.
3. Click **Settings** in the panel rail on the right.
4. Find **Animations**. Under **When this scrolls into view**, pick an effect, such as **Fade up** or **Zoom in**.
5. Scroll the page in the builder. The block plays its effect as it enters the screen.
6. Click **Publish** to put it on your live site.

To take the effect away, set **When this scrolls into view** back to **None**.

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

Click **More options** below **Animations**, then open **Animation options**:

- **Delay**: how long the block waits before it starts, in milliseconds. 1000 is one second, and the most you can set is 5000.
- **Start when it is ... of the way up the screen**: how much of the block must be on screen before it plays. **20% (standard)** works for most blocks. Pick **50%** for a tall block that should play when half of it shows.
- **Play only once**: on by default. Turn it off to play the effect again each time a visitor scrolls back to the block.
- **One child after another**: for a block that holds other blocks, such as a section with three cards. The cards start one after the other, this many milliseconds apart, instead of all at once. Leave it at 0 to play them together.

### Animate Word by Word

A heading can enter one word at a time, or one letter at a time.

1. Pick an effect under **When this scrolls into view**, such as **Fade up**. **Animate word by word** appears below it.
2. Choose **Words** or **Letters**. **None** plays the block as one piece.
3. Click **Publish**.

Visitors see each word or letter play after the one before, once, as they scroll to the block. In the builder the text stays plain, so you can edit it. A screen reader still reads the text as one sentence, and visitors who ask for less motion see plain text with no movement. A link inside the text plays as one piece. **Letters** suits a short line, such as a title. A long paragraph reads better with **Words**.

### Blocks at the Top of the Page

A block that is already on the screen when a visitor opens your page shows at once, with no effect. The page then loads without a gap at the top. Effects play for the blocks a visitor scrolls down to. In the builder, a block you pick an effect for plays right away so you can see it.

### Visitors Who Ask for Less Motion

Some visitors turn on **Reduce motion** in their phone or computer. For them, every block shows at once and nothing moves. They still see the whole page. This follows their device setting, so you do not need to turn it on.

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

- **As an entrance effect:** in **Settings**, under **When this scrolls into view**, pick your keyframe. It shows after the built-in effects.
- **As an animation that plays when the page opens:** in the Styler, open **Animation** in **Normal**, click **Add an animation** and pick your keyframe.

Click **Publish** to put it on your live site.

### Rename or Delete It

- **Rename:** click the pencil next to the keyframe and type the new name. Every block that uses it changes to the new name, so nothing stops playing.
- **Delete:** click the bin. A warning lists the blocks that use it. If you delete it, those blocks stop animating. **Undo** in the toolbar brings it back.

### Less Motion

If your own device asks for less motion, **Play** shows the End look for two seconds instead of moving. Visitors who ask for less motion see the End look too, with no movement.

### Ask an AI

An AI connected to your site through MCP can read your keyframes, change their stops and rename them, the same way you do in the Styler.
