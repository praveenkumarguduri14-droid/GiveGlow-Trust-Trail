# GiveGlow — TrustTrail (HTML / CSS / JavaScript assignment)

A transparent donation tracking and impact verification web app, built with plain HTML, CSS and JavaScript (no build step).

## Run
Extract the ZIP and double-click `index.html`. (Needs internet for fonts and sample photos.)

## Structure
```
index.html        page shell
css/styles.css    all styling (responsive)
js/data.js        sample campaigns, milestones, per-campaign impact units, sample NGO details
js/script.js      rendering, donation flow, receipt, dashboard, badge card, localStorage
```

## Brief coverage
| Requirement | Where |
|---|---|
| Campaign explorer + progress bars + search/filter | Explore Causes page |
| Donation tier presets with impact equivalencies | Donation modal (e.g. ₹1,500 = Science Kits for 3 Girls) |
| Itemized fund ledger 85 / 10 / 5 | Home page ledger: stacked bar, donut, per-campaign table |
| Photographic impact milestone feed | Impact Reports page |
| 80G-style receipt (reference no., PAN, amount in words, clause) | Dashboard > receipt icon > Print / Save as PDF |
| Donor impact portfolio | My Dashboard (totals, causes, units impacted), saved in localStorage |
| Stretch: social badge card | Dashboard > Download social badge card (PNG) |
| Mock checkout: Demo UPI / NetBanking / Credit Card | Donation modal |

## Demo script
Explore Causes > "Rural Girl STEM Education Drive" (74% of ₹5,00,000) > ₹1,500 > enter PAN > confirm > watch the bar update > open the receipt.

## Limitations
All data, NGO registration numbers and photos are samples. No real payment is made and the receipt is **not** a valid tax certificate. Not implemented: Express/SQLite backend, video digest, recurring pledges.

## Theme
Animated classic theme: forest green and antique gold, Playfair Display headings, shimmering gold accents, hero entrance sequence, scroll reveals, count-up statistics, animated progress bars and donut, hover lifts. All motion is disabled automatically for users who prefer reduced motion.
