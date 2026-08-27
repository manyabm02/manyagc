# GooCampus — Landing Pages

This repository holds the GooCampus landing pages. Each page is its own separate file
and its own separate web address. They are not connected to each other.

## 👉 The pages

| Page | Live link |
|---|---|
| **1:1 Career Strategy Session** | **https://manyabm02.github.io/manyagc/** |
| **New Zealand Medical PG Pathway Handbook** | **https://manyabm02.github.io/manyagc/nz-handbook.html** |
| **Gulf (GCC) Medical Licensing Programme** — *draft* | **https://manyabm02.github.io/manyagc/gcc-landing.html** |
| **Samvaya Matrimony** — *draft* | **https://manyabm02.github.io/manyagc/samvaya.html** |

The site is also live on **Netlify** (auto-deploys from this repo):
- Career Strategy Session — https://goocampus-medical-pg.netlify.app/
- NZ Handbook — https://goocampus-medical-pg.netlify.app/nz-handbook.html
- Gulf (GCC) Programme — https://goocampus-medical-pg.netlify.app/gcc-landing.html
- Samvaya Matrimony — https://goocampus-medical-pg.netlify.app/samvaya.html

Anyone with these links can open them, on phone or laptop. They're public.

---

# Page 1 — 1:1 Career Strategy Session

The landing page where doctors book a 60-minute personalised consultation with our
Chief Counsellor about doing their medical PG abroad.

**Live at:** https://manyabm02.github.io/manyagc/

## What's on the page

The page is one long scroll. In order, it covers:

1. **Opening section** — the main headline, and a card showing what you get
2. **Countries** — the 9 countries we map pathways for
3. **Why this session is different** — personalised guidance, country comparisons, and who you'll speak to
4. **Who this session is for** — the types of doctors and students it suits
5. **How it works** — the five steps, shown as a flow
6. **The problem** — the confusion this session clears up
7. **Why doctors trust us** — six reasons
8. **Your post-session report** — a view-only preview of the actual report PDF, plus the checklist of what's included
9. **Inside your report** — a closer look at each part of the report
10. **What this consultation is not** — our honesty section
11. **Pricing** — the price and everything included
12. **Closing section + footer** — final call to action, address and email

## The key details on the page

| | |
|---|---|
| **Price shown** | ₹11,800 (including GST) |
| **Session length** | 60 minutes, one-to-one |
| **Countries covered** | India, Australia, UK, USA, Gulf Countries, Canada, Germany, New Zealand, Ireland |
| **Booking buttons go to** | https://rzp.io/rzp/GH5iPqt (Razorpay payment page) |
| **Email shown** | info@goocampus.in |
| **Address shown** | 138/6, Ground Floor, 10th Main Road, 6th-A Cross, Sadashivanagar, near SBI Bank, Raj Mahal Vilas Extension, Bengaluru, Karnataka 560080 |
| **Report preview** | The actual report PDF, shown **view-only** (no download button, no file link) |

Every "Book" button on the page — in the top bar, the opening section, the pricing
box and the closing section — opens the Razorpay payment page in a new tab.

## The files here

| File | What it's for |
|---|---|
| `index.html` | The **Career Strategy Session** page — shown at the main link. |
| `nz-handbook.html` | The **New Zealand Handbook** page — shown at `/nz-handbook.html`. |
| `gcc-landing.html` | The **Gulf (GCC) Programme** page — shown at `/gcc-landing.html`. Still a draft. |
| `samvaya.html` | The **Samvaya Matrimony** page — shown at `/samvaya.html`. Still a draft. |
| `report-data.js` | Holds the report PDF used for the **view-only preview** on the Career Strategy page. It loads only when a visitor scrolls down to the report section. |
| `README.md` | This file. |
| `CHANGELOG.md` | A plain-English history of what's changed. |

The pages are independent — editing one never affects the others. The logo and
styling are built into each page. The one extra piece is `report-data.js`, which the
Career Strategy page uses for its report preview.

## How to make changes

**The easy way:** just say what you'd like changed and it'll be updated and put live
for you.

**If you want to do it yourself:** the page lives in `index.html`. Once you save a
change and upload it here, the live site updates by itself within about a minute.
There's no build step and no publishing button to press.

## How to view it without the internet

Download `index.html` and double-click it — the whole page opens in any browser. The
one part that needs the internet is the report preview (it uses an online PDF viewer),
so that section may be blank offline; everything else looks exactly the same.

---

# Page 2 — New Zealand Medical PG Pathway Handbook

The landing page that promotes the **New Zealand Medical PG Pathway Handbook for IMGs**
— the digital handbook doctors buy for their complete roadmap to practising medicine in
New Zealand.

**Live at:** https://manyabm02.github.io/manyagc/nz-handbook.html
**File:** `nz-handbook.html`

## What's on the page

1. **Opening section** — the handbook title, star rating, the book cover, and the buy buttons
2. **Why New Zealand?** — the doctor shortage and the opportunity
3. **What's Inside the Handbook** — all 8 chapters; Chapter 1 opens as a free preview, Chapters 2–8 show as locked
4. **What Else You Get** — the CV template, hospital contacts and Master's course information
5. **What Doctors Are Saying** — the review
6. **The Numbers Speak for Themselves** — the key statistics
7. **Who Is This Handbook For?** — the five types of doctor it suits
8. **One Handbook. Everything You Need.** — the offer and the price
9. **Frequently Asked Questions** — the five questions and answers
10. **Footer** — about GooCampus, office address and email

## The key details on the page

| | |
|---|---|
| **Price shown** | ₹699 (was ₹2,999 — 77% OFF) |
| **Format** | Digital PDF · Instant Access |
| **Chapters** | 8 (Chapter 1 free to preview) |
| **Rating shown** | 4.9 · 30+ reviews |
| **Email shown** | info@goocampus.in |

## ⚠️ Two things this page still needs

1. **The buy buttons don't go anywhere yet.** There's no payment link for the handbook,
   so every "Get Instant Access" / "Get Your Copy Now" button currently just scrolls down
   the page. Send the payment link and it takes a minute to wire up.

2. **The price needs confirming.** The original content showed **₹699 (77% OFF)** at the
   top and middle, but **₹999 (67% OFF)** at the very bottom. Those can't both be right,
   so ₹699 is used everywhere for now.

---

# Page 3 — Gulf (GCC) Medical Licensing Programme

**⚠️ This page is a draft.** It is still being reviewed and is not finished — see
"What this page still needs" at the bottom of this section.

The landing page for doctors who want to practise in the Gulf, covering the licensing
pathway for whichever GCC country and authority they are targeting.

**Live at:** https://manyabm02.github.io/manyagc/gcc-landing.html
**File:** `gcc-landing.html`

## What's on the page

1. **Top banner** — offers the free GCC brochure
2. **Opening section** — the headline over a photo, with the brochure button
3. **Who We Are** — what GooCampus does, with a photo
4. **Why Doctors Are Choosing the Gulf** — the six reasons
5. **Where You Can Practice** — all 8 authorities and the country each covers
6. **Your Journey to the Gulf** — the seven steps, from enrolment to relocation
7. **What's Included** — the five service tracks, as cards
8. **What Sets Us Apart** — the five differences
9. **Everything You Need, In One Program** — the six things covered
10. **We Only Work With Serious Professionals** — how candidates are selected, and the three steps
11. **What Our Doctors Say** — five reviews
12. **Closing section + footer** — final call to action, offices, phone and email

## The key details on the page

| | |
|---|---|
| **Authorities covered** | DHA (Dubai), DOH (Abu Dhabi), MOHAP (Northern Emirates), SHA (Sharjah), SCFHS (Saudi Arabia), QCHP (Qatar), NHRA (Bahrain), MOH (Kuwait) |
| **Buttons go to** | Nowhere yet — see below |
| **Phone shown** | 080-41743956 |
| **Email shown** | info@goocampus.in |
| **Offices shown** | United Arab Emirates (head office) and Bengaluru |

## About the look

This page follows a different design from the other two — it was built to match a
business-consulting template the design was based on. Cream and navy sections
alternate, section headings sit on the far left with the content beside them, and the
service cards step left and right down the navy section rather than sitting in a grid.
Text lifts into view as you scroll.

The photos are AI-generated. **They should be looked at before this page is shown
publicly.**

## ⚠️ What this page still needs

1. **The brochure buttons don't go anywhere yet.** Every "Download Free Brochure"
   button just scrolls down the page. Send the brochure file or a form link and it
   takes a minute to wire up.

2. **Three sections say much the same thing.** "What Sets Us Apart", "What's Included"
   and "Everything You Need, In One Program" all cover the same six services.
   "Everything You Need" adds nothing new and could be removed.

3. **There are no numbers on the page.** No doctors placed, pass rate or years running.
   If those figures exist they would strengthen it.

4. **The reviews have no source.** Names only, no photos or verification.

---

# Page 4 — Samvaya Matrimony

**⚠️ This page is a draft.** The photos on it are placeholders — see "What this page
still needs" at the bottom of this section.

The landing page for **Samvaya**, GooCampus's invite-only, hand-curated matchmaking
service for working professionals — verified profiles, curated introductions and
privacy, built on GooCampus's years of guiding professionals through their careers.

**Live at:** https://manyabm02.github.io/manyagc/samvaya.html
**File:** `samvaya.html`

## What's on the page

1. **Opening section** — the couple photo, the Samvaya name ("Made with ❤️ by
   GooCampus"), the headline "Matrimonial Matchmaking", and the "Join Waitlist" button
2. **"Samvaya means coming together"** — the opening line: no swiping, no fake profiles
3. **Why Samvaya is different** — the four points (verified profiles, career alignment,
   curated introductions, privacy-first)
4. **Your field, or beyond it** — you can choose a partner from your own field or beyond
5. **Built for professionals** — the six reasons it's made for people with demanding careers
6. **Samvaya vs generic platforms** — a five-row comparison
7. **How love will find your way** — the five steps, shown as a flow
8. **Private, hosted video introductions** — how the first meeting works
9. **About Samvaya** — the GooCampus story and the numbers
10. **Closing section + footer** — final call to action, email and links

## The key details on the page

| | |
|---|---|
| **Audience** | Working professionals (doctors, engineers, lawyers, CAs — any field) |
| **"Join Waitlist" buttons go to** | https://apply.samvayamatrimony.com (opens in a new tab) |
| **Email shown** | hello@samvayamatrimony.com |
| **Numbers shown** | 50,000+ guided · 4.9/5 rating · 15+ years · 6 continents · 100+ partners |

## About the look

A soft, romantic and elegant design — a warm ivory background, an oxblood-wine accent
with a little antique gold, an elegant serif for the headings, delicate floral
flourishes under each section, and a gentle zoom on the opening photo. It is
deliberately different from the medical pages.

**The photos.** The opening photo runs down the right of the opening section at close to
its own proportions, so the whole picture shows — both faces, the joined hands, the ring
and the bangles. The groom's side carries on underneath the words as a soft dissolve.
The "beyond your field" and "hosted video" photos both run off the very left edge of the
screen and dissolve into the page behind the text beside them; neither sits in a frame.

On all three, the fade is kept **off the faces**, and none of them stops at a visible
edge. On the opening photo the ivory tint is kept where the writing actually is — the
left column and the lower band — and held off the upper part of the picture where the
faces are. On the sunset couple a soft oval window does the same job. In both cases the
tint still backs the words.

The opening section has **no blurred backdrop**. It used to sit a blurred, enlarged copy
of the same photograph behind everything, which put a hazy second groom beside the sharp
one; the photo now softens into flat ivory instead.

**The flowers.** Two hand-drawn botanical marks — a small sprig and a rose spray — sit
quietly in the empty corners of six sections, plus a pair of flowering branches either
side of "Samvaya means coming together". They are faint and deliberately spread out.
The heart in "Made with ❤️ by GooCampus" is drawn in the same wine as the Samvaya
wordmark above it, not the standard emoji.

**On phones** the opening photo becomes a band across the top with the words below it,
and the other two photos become full-width bands that fade into the page. On laptops
the couple sits on the right with the words to the left.

## ⚠️ What this page still needs

1. **The three photos are placeholders.** The hero couple, the "beyond your field"
   sunset couple, and the video-call image are stock/AI images embedded for now. They
   **should be replaced with licensed or brand photos** before this is shown publicly.

   When replacing the opening photo, ask for a **landscape (wide) crop**. The current one
   is portrait, which is why it sits across roughly the right half rather than filling
   the section: stretching a tall photo across a wide screen would enlarge it until the
   hands, the ring and the bangles were cut away. A wide photo could fill the whole
   section and still show all of it.

2. **The waitlist link needs confirming.** Every "Join Waitlist" button points to
   `apply.samvayamatrimony.com` — check that address is live and correct.
