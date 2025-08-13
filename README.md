# Tracee – Track Groceries, Reduce Waste

A concept app developed for the **ASPIRE Challenge** to help households cut food waste by tracking groceries from receipts and nudging timely use.  
*“What’s measured is managed” – Tracee makes food waste visible, actionable, and preventable.*

[![Pitch Deck Thumbnail](pitch/slide_1_title.png)]([https://drive.google.com/your-deck-link-here](https://github.com/jasminejoy01/tracee-food-waste-tracker/blob/main/pitch/Organic%20Waste%20Management.pdf))

---

## 1. Elevator Pitch
Meet Stacey, a 29-year-old working professional in Toronto. She finds a jar of pasta sauce in her fridge—ten days past its best-before date—and tosses it, unopened.  
Stacey’s mistake? She thought best-before meant expiry, and she forgot the item was there in the first place.

**Tracee** fixes this by:
1. Snapping a photo of your grocery receipt.
2. Logging your items and storage locations.
3. Estimating best-before dates based on storage.
4. Sending timely nudges before food goes bad.
5. Tracking what’s used vs. wasted to inform future shopping.

---

## 2. The Problem
- About **half of household food waste happens at home**.
- Many consumers misunderstand *best-before* vs *expiry* dates.
- Once groceries leave the store, there’s **no tracking** of what’s bought, stored, or wasted.
- Food waste costs money, wastes resources, and strains waste management systems:contentReference[oaicite:0]{index=0}.

---

## 3. The Solution – Tracee
Tracee bridges the gap between purchase and consumption by providing:
- **Receipt scanning** – Upload a receipt photo, auto-parse items & prices.
- **Storage mapping** – Assign fridge, freezer, or pantry to estimate shelf life.
- **Alerts & nudges** – Notifications for items nearing best-before dates.
- **Waste tracking** – Log what’s discarded vs used.
- **Insights & budgeting** – See $ lost to waste and adjust buying habits.
- **Optional integrations** – Recipes, donation locations, grocery swaps:contentReference[oaicite:1]{index=1}.

---

## 4. Feature Summary

| Feature         | Description |
|-----------------|-------------|
| Receipt Scanning | OCR extracts items from receipts. |
| Storage Mapping | Map storage location → shelf-life estimate. |
| Alerts          | Notifications for items nearing expiry. |
| Waste Tracking  | Record outcomes (used, donated, repurposed, discarded). |
| Insights        | Track $ wasted, most-frequently wasted items. |

---

## 5. User Flow

```plaintext
Receipt Photo → OCR → Item List → Storage Mapping → Best-Before Dates → Alerts → Waste Tracking → Insights
