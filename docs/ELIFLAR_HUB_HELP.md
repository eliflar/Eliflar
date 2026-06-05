# Eliflar Hub — Help Guide

**Version:** 1.0  
**App:** eliflar-docs.netlify.app  
**Related:** eliflar.app

---
## ELIFLAR - Create narrated tutorial videos without video editing!

## What is Eliflar Hub?

Eliflar Hub is a mobile-first PWA (Progressive Web App) that works as your personal recording assistant. Before you start recording in Eliflar, open your script, notes, and resources here — everything stays on your device, always one tap away.

It has two main functions:
- **My Docs** — save links to your Google Docs notebooks for quick access
- **Book** — a full recording log where you fill in details for every video you make

---

## Installation

Eliflar Hub works in any mobile browser, but installing it gives you a home screen icon and a faster experience.

**Android (Chrome):**
1. Open the app in Chrome
2. Tap the banner at the top that says *"Install Eliflar Hub"*, or tap the three-dot menu → *Add to Home screen*
3. Tap **Install** — done

**iPhone (Safari):**
1. Open the app in Safari
2. Tap the Share button (box with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

---

## My Docs Tab

This is where you save links to your Google Docs — scripts, label lists, intro timing notes, anything you want open while recording.

**To add a document:**
1. Paste your Google Docs link into the first field
2. Give it a name (optional — a default name is used if left empty)
3. Tap **Save notebook**

**To open a document:**
- Tap the **arrow icon** on any saved document — it opens in the built-in viewer
- Tap the **copy icon** to copy the link to clipboard

**To delete a document:**
- Tap the **trash icon**
- The two default help documents (Manual, Quick Guide) cannot be deleted

> **Note:** All your documents are saved on this device only. They will not appear on another phone or browser.

---

## Book Tab

The Book is your recording log. Every video you make gets one entry with all the details filled in — before, during, and after recording.

### Adding a new recording

Tap **New** in the top right corner. A form slides up from the bottom with all the fields.

Fill in what you know and tap **Save Recording**. You do not need to fill in everything — you can always edit later.

New recordings always appear **at the top** of the list (newest first).

### The two numbers

Every recording has two numbers, both visible on the card:

| Number | Label | What it means |
|--------|-------|---------------|
| **#3** | order | Position in the list. Changes when you add or delete recordings. |
| **ID 7** | permanent ID | Assigned once when saved. Never changes, even if you delete other recordings. Use this when referring to a specific recording. |

Example: *"Check ID 12 for the intro settings we used"* — this will always point to the same recording.

### Form fields explained

**Basic Information**

| Field | What to fill in |
|-------|----------------|
| Date | Recording date, e.g. `2025-06-04` |
| User | Who is recording (useful for shared devices) |
| Project / Theme | The series or topic name |
| Video Title | The title of this specific video |
| Language | Language spoken in the video |
| Duration | Planned or actual length, e.g. `5 min` |

**Links**

Up to 10 numbered fields for reference links — sources, images, scripts, Google Docs, YouTube videos you are referencing, etc.

If you have more than 10 links, use the **Extra Links / Notes on Links** textarea below — paste as many as you need, one per line.

**Intro Configuration**

| Field | What to fill in |
|-------|----------------|
| Intro Name | The name or filename of the intro clip |
| Intro Active | YES if you are using the intro in this video, NO if not |

**Webtro Configuration**

Webtro is a web-based intro/overlay feature in Eliflar.

| Field | What to fill in |
|-------|----------------|
| Webtro Slot | Which slot (1–4) the webtro is loaded in |
| Webtro Active | YES or NO |
| Webtro URL | The URL of the webtro |

**Recording Plan**

| Field | What to fill in |
|-------|----------------|
| Opening | How the video starts — what you say or show first |
| Main Content | Key points to cover. Write one point per line. |
| Closing | How the video ends — call to action, outro, etc. |
| Notes | Anything else — reminders, corrections, ideas for next time |

**Publication**

Fill these in after the video is published.

| Field | What to fill in |
|-------|----------------|
| Video File | Filename or storage path of the exported video |
| Published | YES once it is live, NO while still in progress |
| Publication Date | When it was published |
| Platforms | Tap to select: YouTube, Facebook, Website, Other |

**Results**

Fill these in after a few days when stats are available.

| Field | What to fill in |
|-------|----------------|
| Views | Total view count |
| Likes | Total likes |
| Comments | Total comment count |
| Personal Evaluation | Your own notes on how the recording went |

**Recording Type**

Select **Landscape** or **Portrait** depending on how the video was recorded.

---

### Editing a recording

Open any recording by tapping on it, then tap **Edit**. All fields will be pre-filled with the saved data. Make your changes and tap **Save Recording**.

The permanent ID does not change when you edit.

### Deleting a recording

Open a recording and tap **Delete**. You will be asked to confirm. Deletion is permanent.

---

## Exporting your Book

Tap the **Export** button at the top of the Book tab. This downloads a `.txt` file to your device with all your recordings, newest first.

The export file is a plain text backup. Keep it somewhere safe — in Google Drive, on your computer, or sent to yourself by email. If you ever clear your browser data, the export is the only copy.

**Recommended:** export regularly, at least once a month.

---

## Data & Privacy

All data is stored in your browser's `localStorage` — only on this device, only in this browser. Nothing is sent to any server.

**This means:**
- Clearing browser data or cache will delete all recordings
- Using a different browser on the same phone will show an empty Book
- Two people using the same phone and same browser share the same Book — which is useful for small teams recording together

**To protect your data:** use the Export function regularly.

---

## Multiple users on one device

If several people use the same phone to record videos, they all share one Book. This is by design — it works like a shared physical logbook.

Each person should fill in the **User** field when creating a recording so you can see who recorded what.

---

## Tabs overview

| Tab | What it does |
|-----|-------------|
| **My Docs** | Save and open Google Docs links |
| **Book** | Recording log — add, view, edit, export |
| **Viewer** | Built-in viewer for Google Docs |
| **Eliflar** | Info and download links for the Eliflar app |

---

## Tips

- Fill in the form **before** recording, not after — it helps you stay focused
- Use the **Notes** field for anything that does not fit elsewhere
- The **Main Content** field is not a script — use it for bullet points only
- If a recording is cancelled, save it anyway with a note explaining why — it is useful context later
- Use **ID numbers** when talking about recordings with others: *"I updated ID 23 with the final view count"*

---

*Eliflar Hub is part of the Eliflar ecosystem. For the recording app, visit eliflar.app*
