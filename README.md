# Advanced Data Visualization: Treemap (RAWGraphs)

**Email:** 23f2001049@ds.study.iitm.ac.in

This repository contains:
- `chart.png` – Treemap exported from RAWGraphs (300–512 px).
- `market_share_treemap.csv` – Input data used to build the chart.
- `README.md` – These instructions.

## Data
The data was deterministically generated from the SHA-256 hash of the email to keep runs reproducible and consistent with the assignment requirement ("based on your email hash").  
Fields:
- `category` – top-level product group
- `subcategory` – nested group
- `value` – market value (arbitrary units)

## How to Recreate the Treemap in RAWGraphs
1. Open **https://rawgraphs.io/**
2. Click **Use it now** → **Load your data** and paste the contents of `market_share_treemap.csv` (or upload the file).
3. Choose **Treemap** as the chart type.
4. Map the data fields:
   - **Hierarchy**: drag `category` first, then `subcategory`.
   - **Size**: drag `value`.
   - **Color**: drag `category` (for a categorical palette).
   - **Labels**: enable labels and set to show `subcategory` and `value` (optional).
5. Customize:
   - Set dimensions to **512 × 512 px** (or 300–512 px as needed).
   - Enable value formatting (e.g., thousands separator) if available.
   - Tweak padding/inner padding for readability; keep short labels.
6. Export:
   - Click **Export** → **PNG** → **Download** as `chart.png`.

## Suggested Styling (Executive-Ready)
- Keep a neutral background.
- Use category-based color palette; ensure sufficient contrast.
- Show labels for larger rectangles only, or abbreviate small ones.
- Keep font sizes legible for board decks and annual reports.


