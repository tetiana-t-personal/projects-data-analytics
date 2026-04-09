This exercise demonstrates how to transform flat data into a structured tabular format using the Pivot Column feature in Power Query. The goal is to analyze product distribution by color using aggregated counts.

🧩 Steps Completed
1. Data Import
Imported Product-Color Model.xlsx into Power BI Desktop using Get Data → Excel.
Loaded the dataset into Power Query Editor.
2. Data Cleaning
Reviewed the dataset containing:
Product Name
Color
Model
Removed the Product Name column as it was not required for analysis.
3. Pivot Transformation
Applied Pivot Column on the Color field.
Used Count (All) as the aggregation function.
Converted unique color values into separate columns.
Produced a summarized table showing the count of products per color.
📌 Result

The final table contains:

One row representing aggregated data
Each column represents a color
Values show the number of products per color
📈 Outcome

This transformation allows faster identification of product distribution patterns by color and demonstrates how Power Query can convert flat data into analytical structures for reporting.
