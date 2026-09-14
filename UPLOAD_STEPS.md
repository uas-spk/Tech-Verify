# TECHVERIFY — upload steps (14 Sep 2026)

Repo: github.com/uas-spk/techverify · Live: https://uas-spk.github.io/techverify/

## Upload (5 minutes)
1. Open **github.com/uas-spk/techverify/upload/main**
2. Drag in **all 11 files** from `techverify_repo/` — they overwrite the existing ones
3. Commit message: `Articles, 20 industries, standards by discipline, 203 linked bodies, scope-based quote, tribunal pitch`
4. Click **Commit changes**
5. Wait ~2 minutes, open the site, press **Ctrl+F5**

## Check six things
- **Articles** appears in the nav and the page loads with three posts
- **Industries** shows twenty cards
- **Sectors & Standards** has "Standards by discipline"; clicking **ASME IX** opens asme.org and **ABS** opens eagle.org
- **Get a Quote** assembles a scope with a live indicative band; unticking a module changes the total
- **About** shows "A test is a test" with the tribunal record
- **Home** shows the short version of the same pitch

## Then
- **search.google.com/search-console** → add the property → submit `https://uas-spk.github.io/techverify/sitemap.xml`
- **business.google.com** → create the profile with the same email and phone

## Files
| File | What it is |
|---|---|
| index.html | Home — plus the short "a test is a test" pitch |
| articles.html | The blog: 3 articles, comment threads, 8 share buttons per post, BlogPosting + FAQ structured data |
| industries.html | 20 industries, every standard tag linked to its body |
| sectors.html | 12 product domains + 10 standards disciplines; 203 bodies, 244 separate links |
| quote.html | 25-question intake → 18 mapped modules → indicative band in 7 currencies |
| services.html · pricing.html · about.html · contact.html | Your originals; nav updated, About carries the pitch |
| robots.txt · sitemap.xml | Indexing and the 9-page sitemap |

## Not for the repo
`monitor_PRIVATE_do_not_upload.html` — your message board with tone reading and reply tracking. Keep it on your machine and in OneDrive. Export its JSON at the end of each day.

## Two values still to paste
1. **Comments** — a Cusdis App ID (no login for visitors) or the giscus ids (instant posting, GitHub login). Block at the bottom of `articles.html`.
2. **Tribunal case numbers** — in `about.html`, at the marked comment inside the "Verify it rather than take my word for it" box, so readers can go straight to the published determinations.

## Still undecided
`pricing.html` publishes the fixed rate card, which lets a visitor skip the quote flow. Reframing it around the pricing drivers is the obvious next step.
