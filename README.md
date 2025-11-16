# Bright-Motors-Car-Sales-Analysis
Purpose: Business Insights for a New Head of Sales using Historical Car Sales Data from Bright Motors

Project Overview

This repository contains a complete data analytics project focused on historical car sales data from Bright Motors. The goal is to provide actionable insights for a new Head of Sales, guiding strategies to improve sales performance, optimize inventory, and increase dealership profitability.

Objectives:

Identify top-performing car makes and models

Analyze relationships between price, mileage, and year

Highlight regional sales performance

Track emerging customer purchasing trends

Recommend strategies to optimize inventory and profitability

Repository Structure
01_Data/
   ├── raw/          # Original datasets
   └── processed/    # Cleaned datasets

02_SQL/
   └── car_sales_queries.sql  # SQL scripts

03_Visualizations/
   ├── PowerBI/     # Power BI files
   ├── Excel/       # Excel dashboards
   └── Images/      # Screenshots / GIFs

04_Presentation/
   └── BrightMotors_Presentation.pdf

05_Planning/
   └── Miro_Architecture.png

README.md

Tools & Technologies

Database / SQL: Snowflake

Data Visualization: Power BI, Excel

Planning / Architecture: Miro / Figma

Presentation: PowerPoint, Canva

Key Calculations

Total Revenue: selling_price * units_sold

Profit Margin (%): ((selling_price - cost_price) / selling_price) * 100

How to Run

Clone the repository:

git clone https://github.com/yourusername/bright-motors-car-sales.git


Load dataset into Snowflake and run 02_SQL/car_sales_queries.sql.

Visualize using 03_Visualizations/ files (Power BI / Excel).

Review findings in 04_Presentation/BrightMotors_Presentation.pdf.

Key Insights

High-margin cars drive most profit → focus on inventory and marketing

Certain regions outperform → prioritize dealership expansion

Seasonal and fuel-type trends → guide promotions and sales strategy

Contributing

Fork the repo

Create a branch: git checkout -b feature/your-feature

Commit changes: git commit -m "Add feature"

Push branch: git push origin feature/your-feature

Open a Pull Request
