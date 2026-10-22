# Paywall Audit — Ling

**Live:** https://bterzic123.github.io/ling-paywall-audit/

Five ranked paywall ideas for Ling, each backed by a number from Adapty's State of Paywalls 2026, plus a clickable rebuild of Ling's paywall and the moment after close, in Ling's own design. Switch **Today / Proposed** above the phone to compare, and tap a numbered pin to see the report finding behind each change.

## The ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Catch the close with a second chance | 4.5: only 4% of apps show a second paywall; it converts at 0.88× the main one and beats it in 45% of apps | ARPU +10–15% (based on Adapty data) |
| 2 | Show the paywall when onboarding ends | 4.4: Education onboarding paywalls convert 0.88% vs 0.27% later ($229 vs $73 per 1,000 views) | Report finding |
| 3 | Put your 4.6 stars and Apple award on the paywall | 5.3 social proof; 3.1: 27% of top paywalls use it | CR +10–30% (observed in winning A/B tests) |
| 4 | Say “no payment now” next to the button | 3.4: 74% of trial paywalls put reassurance near the CTA | Report finding |
| 5 | Hold the X for three seconds | 5.3 close-button delay; 3.7: 3–5 s is the most common delay | CR +8–15% (observed in winning A/B tests) |

**Benchmark slice:** Education apps, US (Ling's largest App Store market), App Store data, Oct 2025–Sep 2026.

**Get the report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=ling)

## Grounding

Prices (EUR 79.99 annual against EUR 129.99, EUR 6.67/mo, EUR 14.99 monthly), the 7-day trial, the Day 5 / Day 7 timeline, the reviews and the headline pattern come from Ling's live paywall (iOS, 22 October 2026). The 4.6 rating from 16K ratings comes from the US App Store listing; the Great Apps for Education 2023 award from Ling's App Store description. The 38% and EUR 1.54 a week on the offer are arithmetic on Ling's own prices. Dark mode is an approximation.

Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and Adapty's own data, not measured results for Ling.

## Run locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype.
