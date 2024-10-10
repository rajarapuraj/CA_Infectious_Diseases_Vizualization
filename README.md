# CA_Infectious_Diseases_Vizualization
This project involves analyzing infectious disease data specific to counties in California state and presenting the findings through interactive visualizations in Power BI. The goal is to create a dashboard that can be used by healthcare professionals and policymakers to monitor trends, identify outbreaks, and plan public health interventions. The project steps cover data collection, transformation, and visualization processes.

## Project Setup
1. Ensure that you have Power BI Desktop installed on your machine. If not, download and install the latest version from [Microsoft Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop).
2. I've downloaded the dataset from the [Data.gov](https://catalog.data.gov/dataset/infectious-diseases-by-disease-county-year-and-sex-6e856) The data represents cases reported for California residents with an estimated illness from 2001 through 2022.

## Data Preprocessing
Before loading the dataset into Power BI, inspect and clean the data using tools like Power Query within Power BI or write Python scripts for preprocessing. As I've already done a project on data preprocessing using MS-Excel on the same dataset. Here, I'm skipping the detail steps on data preprocessing. 

- Remove null values or impute missing data.
- Standardize date formats.
- Correct inconsistencies in disease names or location data.
- Data Transformation

## Loading Data
As I've a cleaned dataset, imported the cleaned dataset into Power BI Desktop for further analysis.

## Building Power BI Visualizations
Sketch out your desired dashboard layout, including filters and interactive elements. My visualizations include:

  - Map Visualization: To display infection counts across counties.
  - Line Chart: To show trend in infections over time.
  - Bar Chart: To show total cases reported year-wise.
  - KPIs: To display key metrics such as total cases.
  - Interactivity: Adding interactive filters, allows users to drill down by specific diseases, counties, or years. I've enabled users to filter by disease, or county.

Custom Calculations: I've used DAX (Data Analysis Expressions) in Power BI to create custom metrics, such as year-over-year change in infection rates or comparisons between regions.

## Enhancing Visual Appeal
  - Applied a consistent color scheme across all visuals to improve readability and make the dashboard visually appealing. Consider using color codes to represent severity levels (e.g., red for high infection rates, green for low).
  - Ensure that each chart and visual has appropriate titles and axis labels. Add tooltips to provide users with more context when they hover over a data point.
  - Add annotations or commentary or callouts to highlight significant trends or unusual patterns.

## Testing and Validation
Double-check the data to ensure that all visualizations reflect accurate and meaningful information. Ensure that the dashboard performs efficiently with large datasets. Use Power BI’s performance analyzer to identify any bottlenecks. Share the Power BI report with a few users for feedback. This could be healthcare professionals or other stakeholders. Gather feedback on the usability and insights provided by the dashboard.

## Publishing the Dashboard
Once the dashboard is complete, publish it to Power BI Service (the online version of Power BI) for sharing with other users or embedding in websites. Ensure proper access levels are set for users who need to view the report. Optionally, if you wish to embed the dashboard on a website, you can use the embed link provided by Power BI Service.
