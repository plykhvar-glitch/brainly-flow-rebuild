# Growth Audit — Brainly

**Live:** https://plykhvar-glitch.github.io/brainly-flow-rebuild/

Five ranked ideas plus a clickable prototype of Brainly's iOS onboarding and paywall, rebuilt in Brainly's own design. One flow for students, one for parents, from the same screens. Prepared by Adapty, October 2026.

## The five ideas

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Ask "student or parent" first, not last | CR +15–20% |
| 02 | Ask for the account after the purchase | CR +8% · ARPU +17% |
| 03 | Ask the goal, subject and grade before the price | CR +15–20% |
| 04 | Put your 4.7 and your guarantee on the paywall | CR +10–15% |
| 05 | One simple offer on "Maybe later" | ARPU +10–15% |

The overview also maps Brainly's US Apple Ads searches to the two flows.

## Grounding

Every price, rating, plan, feature line and week-by-week line comes from Brainly's own App Store listing, brainly.com and in-app screens. Prices are the US store prices. Keyword data is from public observation of Apple Ads in the US storefront, 21 September – 21 October 2026, not from Brainly's account.

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps — not measured lift for Brainly.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/ (add `?open=proto` to land on the prototype).
