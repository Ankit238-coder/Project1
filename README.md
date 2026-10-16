# Electric Vehicle Market Performance & Insights

## Project status
Starter project package for a Tableau Public dashboard. The included dataset is **synthetic demonstration data** generated for practicing analysis and dashboard design. It is **not verified real-world market data** and must not be presented as factual market statistics.

## Objective
Build an interactive dashboard that explores EV sales, manufacturer performance, vehicle categories, battery technologies, driving range, manufacturing countries, and customer ratings.

## Files
- `data/ev_market_sample_dataset.csv` — 180 synthetic EV model records, ready to connect in Tableau.
- `documentation/data_dictionary.md` — column definitions and caveats.
- `documentation/tableau_build_guide.md` — step-by-step workbook and dashboard instructions.
- `documentation/insights_template.md` — template for writing findings after using the dashboard.
- `tableau/dashboard_specification.md` — recommended dashboard layout, filters, and calculated fields.

## Recommended dashboard
1. KPI cards: total annual sales, number of models, average driving range, average customer rating.
2. Bar chart: sales by manufacturer.
3. Bar chart: sales by vehicle category.
4. Pie or stacked bar: battery technology distribution.
5. Scatter plot: battery capacity vs driving range.
6. Map or bar chart: sales by manufacturing country.
7. Filters: Year, Manufacturer, Vehicle Category, Battery Technology, Manufacturing Country.

## How to use
1. Open Tableau Public Desktop.
2. Choose **Connect → To a File → Text File** and select `data/ev_market_sample_dataset.csv`.
3. Build worksheets using the build guide.
4. Combine worksheets into a dashboard and add filters.
5. Publish using **Server → Tableau Public → Save to Tableau Public** (menu wording can vary by version).
6. Create a public GitHub repository and upload this project folder.
7. Add the published Tableau Public URL as Demo Link and the repository URL as GitHub Link on your project portal.

## Important
Do not claim the charts describe actual global EV market share. For a research/market-facing submission, replace the sample data with a documented real dataset and cite its source before publishing.
