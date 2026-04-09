This Power BI report demonstrates interactive sales analysis using drillthrough pages, slicers, and bookmarks. The focus is on analyzing customer purchases, product categories, and monthly revenue trends.

🧩 Features Implemented
1. Sales Detail Page (Table Visualization)
Added a table visualization displaying:
Customer Location
Order Total
Enabled summary row to display total revenue at the bottom of the table.
2. Drillthrough Setup (Order Month)
Configured Order Month as a drillthrough field.
Created navigation from Sales Summary → Sales Detail based on monthly selection.
Power BI automatically generated a back navigation button for easy return to the summary page.
3. Product Category Filtering (Slicer)
Added a slicer on the Sales Summary page using:
Product Category
Allows dynamic filtering of sales data by product type.
4. Bookmark for Specific Scenario
Created a filtered view for:
Product Category: Mountain Bikes
Month: March
Applied drillthrough from March selection to Sales Detail page.
Saved the filtered state as a bookmark:
“March Mountain Bikes Revenue”
Bookmark captures both filters and report state for quick access.

📌 Key Insights
Drillthrough improves deep-dive analysis from summary to detailed transaction level.
Slicers provide quick segmentation of product performance.
Bookmarks allow saving and presenting specific analytical scenarios (e.g., monthly product performance).

📈 Outcome
This report enables users to:

Navigate from high-level summaries to detailed customer-level data
Analyze revenue by product category and time period
Save and present key business scenarios for reporting or presentations
