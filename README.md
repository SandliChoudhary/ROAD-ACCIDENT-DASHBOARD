📘 Project Overview
The Road Accident Dashboard is an interactive data analytics solution built in Microsoft Excel to visualize and analyze road accident trends. It aims to provide meaningful insights into accident frequency, casualty severity, vehicle involvement, environmental conditions, and location-based distributions. The dashboard can be used by analysts, policymakers, or traffic safety researchers to identify risk patterns and make informed decisions.

This project leverages Excel’s advanced data visualization capabilities — such as PivotTables, PivotCharts, slicers, and calculated fields — to convert raw traffic accident data into an easy-to-navigate reporting tool.

🚀 Features
🧹 Data Cleaning
Standardized inconsistent entries (e.g., surface types, light conditions).

Removed duplicates and blanks to ensure data quality.

Added helper columns like Year, Month, and DayOfWeek using Excel formulas.

📊 Data Analysis
Analyzed accident data across multiple dimensions:

By Year and Month – Trend tracking across time.

By Severity – Fatal, Serious, Slight breakdowns.

By Vehicle Type – Cars, Bicycles, Motorcycles, HGVs, etc.

By Environmental Conditions – Light, road surface, area type.

📈 Dashboard Interactivity
Created dynamic visuals using:

Slicers for year, severity, vehicle type, and more.

Timelines for month-by-month filtering.

KPIs with Year-over-Year (YoY) comparisons.

Interactive charts such as:

Line charts for monthly trends.

Donut charts for proportion-based insights.

Stacked bar charts for distribution by category.


| Column Name         | Description                                            |
| ------------------- | ------------------------------------------------------ |
| `Accident_Index`    | Unique identifier for each accident                    |
| `Date`              | Date of accident (DD/MM/YYYY)                          |
| `Year`              | Extracted using `=YEAR(Date)`                          |
| `Month`             | Extracted using `=TEXT(Date, "MMM")`                   |
| `Day_of_Week`       | Extracted using `=TEXT(Date, "dddd")`                  |
| `Casualties`        | Total number of casualties in that accident            |
| `Accident_Severity` | Level of severity: Fatal / Serious / Slight            |
| `Vehicle_Type`      | Vehicle involved (Car, Bike, Truck, etc.)              |
| `Road_Type`         | Single carriageway, Dual carriageway, Roundabout, etc. |
| `Surface_Condition` | Dry, Wet, Icy, etc.                                    |
| `Light_Condition`   | Daylight, Darkness with/without lights                 |
| `Area_Type`         | Urban or Rural                                         |



.

🛠️ How to Use
Open the Excel workbook and go to the Data sheet.

Paste or import your raw accident data into the designated area.

Refresh all pivot tables (Data > Refresh All).

Navigate to the Dashboard sheet.

Use slicers and timelines to interact with the dashboard and filter by year, severity, area type, etc.

Observe the charts and KPIs update dynamically based on your filters.

💡 Enhancements (Ideas for Future Versions)
Time-of-Day Analysis: Add Hour field to study accidents by time segments (e.g., peak hours).

Map Integration: If geographic coordinates are available, integrate with Power Map (3D Maps).

YoY Trend Sparklines: Use sparklines to show month-over-month or year-over-year changes visually.

Severity Ratios: Use 100% stacked charts to compare severity distribution across filters.

Automated Data Loading: Integrate Power Query for automated data import and preprocessing.

🧰 Tech & Tools Used
Microsoft Excel 2016 or later

PivotTables and PivotCharts

Slicers and Timelines for interactivity

Conditional formatting for KPIs

Excel formulas: YEAR(), TEXT(), IF(), VLOOKUP(), COUNTIFS(), etc.

📊 Key Insights from the Dashboard
Seasonality: Casualties tend to peak in October and November.

Vehicle Type: Cars are involved in ~80% of total accidents.

Road Conditions: Most accidents occur on single carriageways and dry road surfaces.

Lighting: The majority of accidents occur in daylight.

Location: Urban areas account for ~60–70% of reported accidents.

