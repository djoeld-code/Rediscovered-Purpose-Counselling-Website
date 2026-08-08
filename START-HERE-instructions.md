# Priority 1: Mobile Optimization — Upload & Cleanup Guide

This package contains 47 pages with the complete Priority 1 fixes: mobile CSS,
image compression, page speed, and accessibility. Follow these steps in order.

---

## STEP 1 — Upload the 47 HTML files

1. Unzip this package on your phone (or wherever you're uploading from).
2. Go to github.com/djoeld-code/Rediscovered-Purpose-Counselling-Website
3. Upload all 47 `.html` files from this package, overwriting the existing
   files of the same name.
4. Commit directly to `main`.
5. Netlify will auto-redeploy — give it 1–2 minutes.

Do NOT upload this instructions file itself — just the 47 page files.

---

## STEP 2 — Delete the 6 stray/flagged files

These are leftover duplicates (likely from iPhone upload naming) and one
tool page that shouldn't be public. Delete them directly on GitHub:

1. `index (6).html`
2. `index (7).html`
3. `index (9).html`
4. `why-driving-feels-scary-after-car-accident (2).html`
5. `why-driving-feels-scary-after-car-accident.html..html`
6. `internal-linking-tool.html`

**Keep:** `index.html` and `why-driving-feels-scary-after-car-accident.html`
(no parentheses, no double extension) — double-check the filename before
deleting anything.

For each file: open it on GitHub → tap the trash icon → commit to `main`.

---

## STEP 3 — Verify it's live

- Open your homepage in a browser and confirm it loads normally.
- Check that the workbook cover image and logo still look sharp.
- Try the booking form on a phone — the screen should NOT zoom in when you
  tap into a field (this was one of the fixes).

---

## STEP 4 — Re-run PageSpeed Insights

Go to pagespeed.web.dev, enter your homepage URL, run the **Mobile** test.

Compare against the baseline from before this batch:

| Category | Before | Target now |
|---|---|---|
| Performance | 64 | Higher — render-blocking and unused JS should drop |
| Accessibility | 85 | Should be 95–100 |
| Best Practices | 100 | Stays 100 |
| SEO | 100 | Stays 100 |

Send me the new numbers and I'll tell you if anything else needs attention.

---

## STEP 5 — Search Console (optional but recommended)

If `internal-linking-tool.html` shows up in Search Console, submit a removal
request after deleting it so it drops from search results.

---

## What's included in this batch

- **Mobile CSS**: new small-phone breakpoint, no sideways scroll, legible
  text sizes, proper tap targets on nav buttons
- **Images**: 30% lighter (4.02MB → 2.82MB) with no visible quality loss,
  lazy-loading on below-the-fold images
- **Performance**: fonts and Google Analytics no longer block page render,
  images have explicit width/height to prevent layout shift
- **Accessibility**: booking form labels properly linked, Jane App booking
  widget has a screen-reader title, every page has a `<main>` landmark,
  two low-contrast text colors darkened to meet WCAG AA

## What's NOT done yet

- Real-device spot check (worth doing once this is live)
- Priority 2 of the master prompt — the ICBC content cluster (10 new
  articles)
