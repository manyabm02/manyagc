# What's Changed

A plain-English history of the GooCampus landing pages. Newest updates go at the top.

---

## Version 1.2 — July 2026 · Career Strategy page refinements

A batch of review-feedback updates to the **Career Strategy Session** page
(`index.html`). The New Zealand Handbook page was not affected. All changes are live.

### Mobile fixes
- Fixed the main complaint — text was appearing tiny on phones because the page was
  missing the "viewport" setting mobile browsers need. Added it, so the page now sizes
  correctly on phones and the built-in responsive layout kicks in.
- Stopped the buy buttons and the "Gulf Countries" tile from running off the edge on
  narrow phones.
- Kept the three hero stats (1,100+ · 11 yrs · 9) on a single line on mobile instead of
  wrapping to a second row.

### The points and wording
- Trimmed the session card ("Here's What You'll Get") to 5 points, and its floating
  green tag now reads **"Exclusive Session Benefits"** (was "Free AUS & NZ Handbook").
- Added a **"1:1 mentoring with a practicing specialist"** point.
- Removed the **"Free access to one future webinar…"** point from the session card, the
  post-session report list, and the pricing list.
- Dropped the word **"Free"** from the "Australia & New Zealand Pathway Handbook" point
  everywhere it appears.
- Made the mentoring wording consistent across the session card, pricing box and the
  "how it works" step.

### Layout
- "How it works" is now **five steps**: added a **"1:1 Specialist Mentoring"** step. The
  order ends with the report (step 4) then mentoring (step 5). Fixed the connecting-arrow
  spacing between the step cards.
- Reordered **"Who this session is for"** by career stage — Med School → Internship →
  MBBS graduate → Foreign Medical Graduate → considering specialist → practicing doctor.

### The report preview
- Replaced the placeholder report graphic with an **actual, view-only preview of the
  report PDF**. It displays on the page but is **not downloadable** — there's no download
  button and no PDF file link (the pages are drawn onto the page as images). The pill now
  reads **"View how your report looks like"**.
- Swapped in the latest report PDF (5 pages) and made it load only when a visitor scrolls
  near it, so it doesn't slow the initial page load.
- Balanced the preview height on desktop so the report card lines up neatly with the
  checklist beside it.

---

## Version 1.1 — July 2026 · New page added

Added a **second landing page** to this repository, for the **New Zealand Medical PG
Pathway Handbook**. It is a separate file (`nz-handbook.html`) with its own web address,
and it does not affect the Career Strategy Session page in any way.

**Live at:** https://manyabm02.github.io/manyagc/nz-handbook.html

### The design

- Built to match the reference style that was shared (the "DevBook" eBook landing page
  template) — a template made specifically for selling a book online. This is a
  deliberately different look from the Career Strategy page.
- Followed its look: clean white pages alternating with a pale blue-grey, orange
  buttons, and rounded "pill" button shapes.
- Used its two typefaces — a rounded, friendly one for headings and a clean, plain one
  for body text.
- Followed its running order: book cover and buy buttons first, then what's in the book,
  who it's for, a free preview, reviews, and the offer.
- Added a 3D book cover for the handbook, since the reference leads with a book cover.
- Made the page work properly on phones as well as laptops.

### The words

- Used the supplied handbook content exactly as written — the headings, chapter names,
  statistics, the review, and all five questions and answers.

### The details

- Chapter 1 opens as a free preview; Chapters 2–8 show with a padlock.
- The opening line cycles through the handbook's chapter subjects.
- Added the GooCampus logo, the Bengaluru office address, and info@goocampus.in.
- Price shown as ₹699, reduced from ₹2,999.

### Still to do on this page

- **Payment link:** the buy buttons have nowhere to go yet.
- **Price to confirm:** the content showed ₹699 (77% OFF) at the top but ₹999 (67% OFF)
  at the bottom. ₹699 is used throughout for now.
- **Logo:** the white logo is used on a dark tile in the top bar, because the colour
  version of the logo file was not available at build time.

---

## Version 1.0.1 — July 2026

- Tidy-up: removed the spare duplicate copy of the page, so there is now just one
  file (`index.html`) to look after. Nothing on the live page changed.

---

## Version 1.0 — July 2026 · **Live**

The first version of the Medical PG Abroad 1:1 Career Strategy Session landing page,
now published at **https://manyabm02.github.io/manyagc/**

### The design

- Built the page following the look and feel of the reference site that was shared
  (monodesk.com) — a clean, modern, one-page scroll.
- Used its colour blocks: a bright blue opening section, light grey middle sections,
  dark sections for the report and pricing, and a deep indigo closing section.
- Used its bright lime-green for every button, tick mark and highlight.
- Matched its style of large, light headlines and fully rounded pill buttons.
- Made the whole page work properly on mobile phones, not just laptops.

### The words

- Used the supplied copy exactly as written, section by section, rather than
  rewriting it.
- Changed "Every recommendation is personalised — not generic." to
  "Every recommendation is personalised, not generic." to read more naturally.
- Changed "Final-year MBBS students" to "Students who are in Med School".
- Changed "Personal strategy" to "Personalised strategy" in the opening section.
- Kept the line "Free access to one future webinar on your target country" worded
  identically everywhere it appears, with no special highlighting.
- Removed repeated wording in the closing section, so "take the next step" now
  appears only once.

### The layout

- Gave the 9 countries their own full section with flag tiles, instead of a thin
  strip along the edge, so they stand out.
- Made sure every country name — including "New Zealand" and "Gulf Countries" —
  fits on a single line.
- Turned "How it works" into a proper 1 → 2 → 3 → 4 flow, with arrows connecting the
  four steps (they point downwards on a phone).
- Opened up the spacing around the four steps so they no longer feel cramped, and
  lined up all four descriptions evenly.
- In the opening card: removed the Chief Counsellor block, put "Here's What You'll
  Get" above the list of inclusions, and labelled the card "Your Session".

### The details

- Set the price to **₹11,800**, shown the same way in the opening card, the pricing
  box and the closing section.
- Connected **every** "Book" button to the Razorpay payment page
  (https://rzp.io/rzp/GH5iPqt), opening in a new tab.
- Added the official goocampus logo to the top bar and the footer, using the official
  white version supplied so it reads clearly on the dark backgrounds.
- Added the Bengaluru office address and info@goocampus.in to the footer, with the
  email clickable.

### Going live

- Published the page to this repository.
- Switched on GitHub Pages so the page is live on the internet.
- Confirmed the live page loads correctly, with the logo, payment links, price and
  address all working.

> **Note on the logo:** the artwork itself was not altered. It was only reduced in
> size so the page loads quickly.

---

### How updates work from now on

Any change saved to this repository goes live automatically within about a minute.
Each future update will be added to the top of this file.
