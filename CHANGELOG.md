# What's Changed

A plain-English history of the GooCampus landing pages. Newest updates go at the top.

---

## Version 1.12 — September 2026 · The sunset photo on phones

On phones the **"Your field, or beyond it"** photo was being sliced — over a third of it
was hidden, cutting the couple at the top and the bouquet at the bottom. The picture is
square, but it was sitting in a wide letterbox band.

The band is now as tall as it is wide, so **the whole photograph shows** — the couple,
the pier and the bouquet complete.

**The photo also starts at the very top of its section now.** There used to be a strip
of empty background above it, which made the picture look as though it began halfway
down. Everything below has moved up to close the gap. The same applies to the
"hosted video" photo further down. Nothing on desktop changed.

⚠️ The **"hosted video"** photo further down has the same problem, and worse — about two
thirds of it is hidden on a phone. It was left alone for now because showing all of it
would need a very tall band (it is a tall, upright picture). Worth deciding separately.

---

## Version 1.11 — September 2026 · The opening photo on phones

On phones the opening photo was cropped too tightly — the couple filled the screen edge
to edge, sat off to one side, and there was a pale glare washing across the bottom of
the picture.

Now:

- **The glare is gone.** It was a fade that blended the photo into the page below; the
  photo simply ends cleanly.
- **The couple are smaller**, taking about four fifths of the screen with clear space
  either side, instead of running off both edges.
- **They sit centred**, to within a pixel, with the joined hands and the ring in view.
- **The slow zoom is switched off on phones.** The picture sits still there. The opening
  photo on desktop still has it.

Because both the band's height and the framing follow the width of the screen, this
holds on every phone size rather than only on one. Nothing on desktop changed.

---

## Version 1.10 — September 2026 · The five steps, side by side

**"How love will find your way" is being trialled as a horizontal row** — the five
icons in a line with dashed curves running between them, and the wording underneath
each, rather than the stacked cards. This is a trial: say the word and it goes back.

Every step is now held to **three lines of text**, with real spacing between the
columns so it is comfortable to read rather than a block of type. The row uses more of
the screen width than the rest of the page to make that possible.

On screens narrower than about 1280px the **original stacked layout still runs** — five
columns simply cannot hold three lines each below that width, so the stacked version is
the better read there.

**The steps now carry a current.** A lit pulse travels along the dotted curve from step
one to step two, then two to three, and on down the line — and the moment it reaches
**Meet Your Match**, the heart beats. Two quick pulses and a rest, the way a real
heartbeat falls, with a soft ring spreading outwards.

The whole sequence takes four and a half seconds and then begins again, so it draws the
eye without ever becoming busy. It stops entirely for anyone whose device is set to
reduce motion.

---

## Version 1.9 — August 2026 · The Samvaya brand fonts

The **Samvaya** page now uses the brand typefaces:

- **Bodoni Moda** for every heading, the Samvaya name and the italic accent lines
- **Satoshi** for body text, buttons and the small labels

Both load from public font services, so nothing needs uploading and the page still works
as a single file.

Bodoni sets noticeably larger and wider than the old face did at the same size, so the
opening headline and its italic line came down a step to keep the intended scale, and
the opening paragraph's column was narrowed a little — otherwise its longest line grew
far enough right to touch the groom's sleeve again.

**Two of the four fonts supplied are not in use.** **Manrope** is an alternative sans
that would duplicate Satoshi's job. **Maharani** is a licensed font, and it is not
available on any public font service — to use it, its two `.woff2` files would need to
be added to this repository. Say the word and it can be wired up, most naturally for the
Samvaya name itself.

---

## Version 1.8 — August 2026 · Kept the soft fades off everyone's faces

On the **Samvaya** page, all three photos fade into the page behind the words. On each
one the fade was starting too early and drifting across a face, which left people
looking veiled — the man in the opening photo most of all, and the bride in the sunset
photo had almost disappeared into the background.

The fades are all still there and still soft. They now simply start further along, in
the gap between where the writing ends and where the people begin:

- **Opening photo (the couple).** This one needed rebuilding rather than adjusting.
  Two separate things were making the groom look blurred while the bride stayed sharp:

  1. **There was a second, out-of-focus copy of him on the page.** A blurred, enlarged
     copy of the same photograph was being used as a backdrop behind the whole opening
     section, and it sat immediately to the left of the real one — so you saw a hazy
     man beside the sharp man. That backdrop is **gone**. The photograph now simply
     softens away into flat ivory.
  2. **The ivory tint was reaching his face.** It now stops well before him.

  **The photograph itself has been widened.** It was a tall, upright picture, and a tall
  picture cannot fill a wide screen without being blown up until the top and bottom fall
  away — which is exactly why **the joined hands, the ring and the bangles kept
  disappearing**, and why the groom's head was running off the top of the screen.

  So the picture was rebuilt as a wide one. The groom's left-hand side — his arm, his
  sherwani and the wall behind him — has been **extended outwards to match**, turning the
  original upright photograph into a wide one (1800 × 997). Nothing of the original was
  cut away; new canvas was added to it.

  What that gives you:

  - The photograph now **fills the whole opening section, edge to edge**, at its natural
    size — it is not being enlarged at all
  - **The couple sit to the right**, in the empty half where there is no writing, so their
    faces are the highlight
  - **The joined hands, the ring and the bangles are all clearly in view**
  - The groom's extended side **runs on to the left, behind the writing**, the way a
    background should
  - Nobody's head runs off the top any more

  The section's height is now tied to its width, so it never becomes taller than the
  picture's own shape — otherwise the sides would be cropped away again on narrow
  windows. On phones the band is framed on the couple rather than the extended wall.
- **"Your field, or beyond it" (the sunset couple).** The fade still sits behind the
  writing, but a soft oval window now lifts it away from the couple's heads. The bride
  is visible again instead of dissolving into the page.
- **"Meet through private, hosted video".** The fade begins further right, so it no
  longer creeps onto the man's cheek and jaw.

**On phones** nothing changes — there the photos fade downwards, which was never over
anyone's face. The other three pages were not touched.

---

## Version 1.7 — August 2026 · Reverted the photo-framing and garland changes

The photo-framing and garland changes have been **undone at your request**. The Samvaya
page is back exactly as it was in version 1.6.

That means these are no longer on the page:

- the oval garland around "Samvaya means coming together" (the two side branches and the
  corner sprays are back instead)
- the shorter video-call section, and the brightened laptop screen
- the photo repositioning that kept the fades off the faces
- the tightened gap above "Samvaya is different"

Nothing else on the page changed, and the other three pages were never affected.

---

## Version 1.6 — August 2026 · Samvaya heart colour and the meaning line

- **The heart in "Made with ❤️ by GooCampus"** (opening section) is now the same deep
  wine as the word **Samvaya** above it. It was a standard emoji before, which always
  renders bright red and couldn't be recoloured, so it's been redrawn as a small shape
  that takes its colour from the page. It will now always match the brand colour.
- **"Samvaya means coming together" is now the romantic centrepiece it should be.**
  "Samvaya means" sits small and quiet above, and **coming together** is much larger in
  italic wine underneath. A pair of matching flowering branches frames the phrase on
  both sides, and the small divider below it has been replaced with a wider, more
  ornate one with a rose at its centre.

---

## Version 1.5 — August 2026 · Samvaya page — photos, layout and florals

Changes to the **Samvaya Matrimony** page (`samvaya.html`). The other three pages
were not touched.

- **Opening section rebuilt.** The couple photo and the text no longer sit in two
  separate halves with a hard line between them. The couple stays on the right, and the
  same photo now fades softly across behind the words. The box around the text — its
  border, rounded corners and panel background — is gone.
- **"Your field, or beyond it" and "Meet through private, hosted video"** — both photos
  now run from the very left edge of the screen instead of sitting inside an arch-shaped
  frame, and each fades into a soft version of itself behind the text beside it.
- **Removed one comparison.** The **Understanding** row ("You, Not Your Job Title" vs
  "Same Old Filters") has gone from the Samvaya vs generic platforms table. The other
  four comparisons are unchanged.
- **Added flowery detailing.** Two new hand-drawn botanical marks — a small sprig and a
  rose spray — now sit quietly in the empty corners of six sections, in the same gold
  and rose as the rest of the page. They're deliberately faint and spread out rather
  than filling the page.
- **On phones**, the opening photo is now a band across the top with the words below it.
  Previously the text sat on top of the photo and was hard to read.

---

## Version 1.4 — August 2026 · New Samvaya Matrimony landing page

- **Added a fourth landing page — Samvaya Matrimony** (`samvaya.html`), live at
  `/samvaya.html` on both GitHub Pages and Netlify. The other three pages were not
  touched — this is a brand-new, separate file.
- Samvaya is GooCampus's invite-only, hand-curated matchmaking service for working
  professionals. The page covers: the hero (couple photo, the Samvaya name, "Join
  Waitlist"), the "coming together" opening line, why Samvaya is different (4 points),
  choosing a partner from your field or beyond it, why it's built for professionals
  (6 points), a Samvaya-vs-generic-platforms comparison, the five-step "how it works"
  flow, the private hosted-video introductions, the About/GooCampus story with the
  numbers, and the closing call to action.
- The "Join Waitlist" buttons open **apply.samvayamatrimony.com** in a new tab; the
  contact email shown is **hello@samvayamatrimony.com**.
- A soft, romantic, elegant look — warm ivory background, an oxblood-wine accent, a
  little antique gold, an elegant serif for the headings, delicate floral flourishes,
  and a gentle zoom on the hero photo. Deliberately different from the medical pages.
- Built mobile-first: on phones the couple photo fills the screen with a compact card
  below it; on laptops the couple sits to the right with the text card on the left.
- **It is a draft.** The three photos on the page (the hero couple, the "beyond your
  field" sunset couple, and the video-call image) are **placeholder stock images and
  should be replaced with licensed/brand photos** before this goes out publicly.

---

## Version 1.3 — August 2026 · New Gulf (GCC) landing page

- **Added a third landing page — the Gulf (GCC) Medical Licensing Programme**
  (`gcc-landing.html`), live at `/gcc-landing.html` on both GitHub Pages and Netlify.
  The other two pages were not touched.
- The page covers all 8 GCC authorities (DHA, DOH, MOHAP, SHA, SCFHS, QCHP, NHRA and
  Kuwait MOH), the seven-step journey, the five service tracks and five reviews.
- **It is a draft.** The "Download Free Brochure" buttons don't go anywhere yet, three
  sections repeat the same six services, and the photos are AI-generated and need a
  look before this goes out publicly. The README lists all of it.
- Built to match a business-consulting template rather than the styling of the other
  two pages, so it looks deliberately different: cream and navy sections, headings on
  the far left, service cards stepping left and right, and text that lifts into view
  as you scroll.
- Included the **viewport setting** from the start, so it sizes correctly on phones —
  the problem that had to be fixed on the Career Strategy page in version 1.2.

---

## Version 1.2.2 — July 2026 · Wording

- Changed the point **"1:1 mentoring with a practicing specialist"** to
  **"Mentoring session by a practicing specialist"** in both places it appears — the hero
  session card and the pricing list.
- Aligned the "How it works" mentoring step to match: title is now **"Mentoring Session by
  a Specialist"** (was "1:1 Specialist Mentoring"), and the "1:1" was dropped from its
  description.

---

## Version 1.2.1 — July 2026 · Netlify deploy + mobile polish

- **Also deployed to Netlify.** The site is now live at
  **https://goocampus-medical-pg.netlify.app** as well as GitHub Pages. It's connected to
  this repo, so pushes auto-deploy to both. (The `goocampusevents.com` domain was left
  untouched — it's a separate site in a different repo.)
- **Mobile tidy-ups on the Career Strategy page:**
  - The opening badge ("Personalised strategy with our Chief Counsellor") now stays on
    one line on phones instead of wrapping.
  - The stats row (1,100+ · 11 yrs · 9) is now centred on phones.
  - The pricing "Book Your Career Strategy Session" button now stays on one line on phones.
  - The hero headline ("Stop Guessing Your Medical PG Abroad.") now shows on two lines on
    phones instead of three.

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

---

