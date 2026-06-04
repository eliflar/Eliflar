# 📖 Eliflar — Complete Manual

> **Interactive drawing on images · All features and modes**
> Version: Drawing Engine (Screen 2 & Screen 3)

---
## Create narrated tutorial videos without video editing!
## Table of Contents

1. [What is this?](#1-what-is-this)
2. [Screen layout](#2-screen-layout)
3. [Indicator gestures](#3-indicator-gestures)
4. [Left strip — Drawing modes](#4-left-strip--drawing-modes)
5. [Drawing modes in detail](#5-drawing-modes-in-detail)
6. [Changing images](#6-changing-images)
7. [Tips for best results](#7-tips-for-best-results)

---

## 1. What is this?

Eliflar lets you **draw on images in real time** while you present, explain, or record.

Marks automatically fade away — creating a **light-trail effect** — or you can freeze them to stay permanently on screen. When you switch images, any marks you have drawn fade away smoothly along with the old image, and the new one appears underneath.

This feature is active in:
- **Screen 2** — Landscape orientation
- **Screen 3** — Portrait orientation

---

## 2. Screen layout

The screen has three invisible layers stacked on top of each other:

| Layer | What it does |
|---|---|
| **Background** | Displays the current image |
| **Overlay** | Your drawings — fades automatically |
| **Indicator** *(top-left)* | Control badge — all gestures go here |

On the **left edge** of the screen there is an invisible strip for switching drawing modes.

---

## 3. Indicator gestures

All controls are performed by tapping the **indicator badge** (top-left corner).

The indicator always shows:
`[image number]  🎨  [mode icon]  [thickness in px]`

| Gesture | Action | Details |
|---|---|---|
| 👆 **Single tap** | Change color | Cycles through your available colors |
| 👆👆 **Double tap** *(fast)* | Next image | Smooth crossfade transition |
| ✋ **Long press** *(0.6 s)* | Change thickness | Cycles: `10 → 30 → 10 → 50 px` |

> **Note:** Changing color or thickness always resets the drawing mode back to 🖊️ Flare Line.

---

## 4. Left strip — Drawing modes

The **left edge** of the screen is an invisible control strip, divided into **5 vertical zones**.
Tap any zone to activate that mode. The indicator updates immediately to confirm.

| Zone | Icon | Mode name | Description |
|---|---|---|---|
| Zone 1 — Top | ✨ | **Dust / Spray** | Tiny dots scatter randomly around your finger |
| Zone 2 | ⬛ | **Rectangle** | Drag from corner to corner to draw |
| Zone 3 — Middle | ⭕ | **Ellipse** | Drag to set width and height |
| Zone 4 | 📏 | **Straight Line** | Drag from start to end; a dot is added at the endpoint |
| Zone 5 — Bottom | 🔒 | **Freeze** | Marks stop fading — stay permanently on screen |

The strip width adapts to screen orientation:
- **Landscape** → narrower strip (1/18 of screen width)
- **Portrait** → wider strip (1/12 of screen width)

---

## 5. Drawing modes in detail

### 🖊️ Flare Line *(default)*

- Touch and drag freely across the image
- Marks **auto-fade** after a few seconds — the signature Eliflar light-trail effect
- Line thickness and color are set via the indicator
- This is the default mode on every new image and after every color/thickness change

---

### ✨ Dust / Spray

- Touch and drag — tiny dots scatter randomly in a radius around your finger
- **Larger thickness** = wider spray radius and denser coverage
- Great for creating glow, fog, or highlight effects

---

### ⬛ Rectangle

- Touch where you want the **first corner**
- Drag to the **opposite corner**
- The rectangle is drawn when you **lift your finger**
- Line thickness applies at 50% scale for clean outlines

---

### ⭕ Ellipse

- Touch and drag to define the **bounding box** of the ellipse
- The ellipse is drawn when you lift your finger
- Works the same way as Rectangle — drag defines width and height
- Line thickness applies at 50% scale

---

### 📏 Straight Line

- Touch the **start point**, drag to the **end point**, release
- A filled circle is automatically drawn at the endpoint
- Circle size scales with line thickness (0.7× factor)
- Great for pointing at or highlighting specific areas in the image

---

### 🔒 Freeze

- Tap **Zone 5** (bottom of left strip) to activate
- All marks **stop fading** and remain permanently visible
- Tap Zone 5 again to **deactivate** — all marks are immediately cleared
- Freeze is **automatically turned off** when you switch images
- The indicator shows 🔒 while Freeze is active

---

## 6. Changing images

**Double-tap the indicator** to move to the next image.

What happens during the transition:

1. The current image + all visible marks are **captured as a snapshot**
2. The **overlay is cleared** immediately (marks are now inside the snapshot)
3. The **new image loads** in the background
4. Once loaded, the snapshot **fades out smoothly** over the new image — crossfade
5. Mode resets to 🖊️ Flare Line, Freeze turns off

> The crossfade duration is approximately **0.75 seconds**.
> Images are preloaded in advance so the transition is near-instant.

---

## 7. Tips for best results

### Light-trail effect
Draw **fast, circular or sweeping strokes** — the auto-fade creates a glowing trail that follows your movement. Slower strokes leave longer-lasting marks.

### Multi-color drawing
Change color mid-session (single tap on indicator) without stopping. Each stroke keeps the color it was drawn with as it fades independently.

### Freeze + shapes
Activate 🔒 Freeze, then draw a Rectangle or Ellipse to highlight an area of the image. The shape stays visible for as long as you need it.

### Spray for atmosphere
Switch to ✨ Dust mode with a large thickness setting. Hold your finger still or move slowly over an area — creates a soft glow or fog effect around objects in the image.

### Straight lines for annotation
Use 📏 Straight Line mode to draw precise pointer lines toward specific details. The endpoint dot acts as a visual anchor.

### Combining modes
You can switch modes freely at any time using the left strip — without losing marks already on screen.

---

## Reference card

| What you want | How to do it |
|---|---|
| Change color | Single tap indicator |
| Next image | Double tap indicator |
| Change thickness | Long press indicator (0.6 s) |
| Freehand drawing | Draw anywhere on screen *(default)* |
| Spray / dust effect | Tap Zone 1 (top of left strip) |
| Draw rectangle | Tap Zone 2, then drag on screen |
| Draw ellipse | Tap Zone 3, then drag on screen |
| Draw straight line | Tap Zone 4, then drag on screen |
| Freeze marks | Tap Zone 5 (bottom of left strip) |
| Unfreeze + clear | Tap Zone 5 again |

---

*Quick reference → [QUICK_GUIDE.md](./QUICK_GUIDE.md)*
*Official app → [eliflar.app](http://eliflar.app)*

---

<sub>Eliflar · Developed by Boris Sekirarski · North Macedonia</sub>

