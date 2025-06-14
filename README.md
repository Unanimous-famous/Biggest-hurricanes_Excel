# Biggest-hurricanes_Excel

🌪️ Biggest Atlantic Hurricanes – Excel Data Analysis

This project explores the historical data of the most impactful Atlantic hurricanes using Microsoft Excel. It involves structured data cleaning, pivot-based filtering, and visualisation to identify trends across storm categories, wind speeds, and economic damages.

📂 Dataset: Biggest Atlantic Hurricanes starter (Biggest Atlantic Hurricanes).csv
📊 Tool used: Microsoft Excel

📁 Dataset Overview

The dataset provides records of significant Atlantic hurricanes from 1870 to 2017, with the following fields:

![image](https://github.com/user-attachments/assets/f60ecaaf-327a-45c7-b7ef-d48f7b4a09d3)


📈 Visualisation & Interpretation
To explore whether there’s a meaningful progression in hurricane severity and damage costs over time — potentially supporting broader climate change discussions — we aimed to visualise these metrics chronologically.

However, the Start Date column was not recognised as an actual date, and simply changing the cell format via the top ribbon dropdown (you know, the “Format Cells” > Date stuff) didn’t help at all. Excel still treated the column as plain text, and as a result, the visualisations were misleadingly sorted alphabetically by month names, rather than chronologically.

![image](https://github.com/user-attachments/assets/200f59d3-70b1-4e60-ab7f-83c1604bd6aa)

We resolved this by using the Text to Columns method:

Selected the Start Date column.
Clicked Data > Text to Columns.
Chose Delimited, skipped the delimiter setup.
In Step 3, set the column data format to Date (MDY).
Clicked Finish — the column was now truly recognised as a date field.
With this fixed, we were able to build a line and bar chart combo showing how hurricane damage (USD) and severity (category/wind speed) have developed over the years — complete with a trendline to visualise the potential escalation.




