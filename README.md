# ACA Writ Calculator

A single-page, offline calculator for **WoW Forever**. It works out how many Craftsman's Writs you need to reach Friendly (or higher) with the **Azeroth Commerce Authority**.

Open `index.html` in any browser. The page needs no install and no server, and it makes no network requests.

## What it does

- Takes your current standing and works out the reputation left to your target level.
- Counts the one-time Shipping Label quest (+2,000) and any writs already in your bags.
- Shows how many Journeyman, Expert or Artisan writs you need, plus the minimum number of days given the one-of-each-order-a-day rule.
- Optionally takes the price you pay per writ and estimates the gold cost, then picks the cheapest tier.
- For targets above Friendly, it also shows the Forged Delivery Receipt route (15 Merchant's Favor for 50 rep).

## Numbers used

| | Value |
|---|---|
| Journeyman / Expert / Artisan writ | 75 / 125 / 200 rep |
| Distinct orders (once each per day) | ~45 / ~60 / ~45 |
| Neutral → Friendly → Honored → Revered → Exalted | 3,000 / 6,000 / 12,000 / 21,000 |
| Shipping Label (one time) | 2,000 rep |
| Forged Delivery Receipt | 15 Merchant's Favor → 50 rep (Friendly+) |
| Diplomat talent (unconfirmed) | +2% per rank |

These figures come from community guides as of November 2026. WoW Forever is new and hotfixes may change them. Edit the constants at the top of the `<script>` in `index.html` to update them.

---

Fan-made. Not affiliated with Blizzard Entertainment.
