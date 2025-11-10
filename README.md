# Laptop-Price-Analysis-Dashboard

📘 Overview

The Laptop Price Analysis Dashboard aims to explore how different laptop specifications influence their market price.
This project performs exploratory data analysis (EDA) and data visualization to uncover insights about pricing trends, brand value, and hardware impact.

The goal is to help:

Consumers make informed laptop purchase decisions.

Retailers and manufacturers understand which factors most influence pricing to refine their strategies.

📊 Dataset Summary

Dataset Source: Kaggle – Laptop Price Dataset
Total Records: 1303
Columns: 13

Column Name	Description
laptop_ID	Unique identifier for each laptop
Company	Brand or manufacturer
Product	Model name or series
TypeName	Category (Notebook, Ultrabook, Gaming, etc.)
Inches	Screen size in inches
ScreenResolution	Display resolution and type
Cpu	Processor details
Ram	RAM capacity (GB)
Memory	Storage type and size (SSD, HDD, Hybrid)
Gpu	Graphics card details
OpSys	Operating System
Weight	Laptop weight (kg)
Price_euros	Price in Euros (€)
Price	Converted price in Indian Rupees (₹)

🎯 Project Objectives
1. Brand Value and Price Comparison

Compare average prices across brands.

Identify brands offering high specs at affordable prices.

Determine the best value-for-money manufacturers.

2. Impact of RAM and Storage on Price

Analyze if more RAM or higher storage increases price.

Understand the role of SSDs vs HDDs in pricing trends.

3. Brand & Processor Type Analysis

Examine how processor performance impacts laptop cost.

Identify budget, mid-range, and premium processor–brand combinations.

4. Feature Correlation with Price

Quantify which numeric features (RAM, Storage, CPU speed, etc.) most influence price.

5. Premium Feature Impact

Study how GPU, display type, and operating system affect pricing.

Discover which specifications justify higher costs.

🧩 Tools and Technologies

Language: Python

Libraries Used:

pandas – Data handling

numpy – Numerical operations

matplotlib & seaborn – Data visualization

plotly (optional) – Interactive charts

Environment: Jupyter Notebook / Google Colab

⚙️ Workflow
1. Data Loading & Preprocessing

Loaded dataset using pandas from Excel file.

Checked data types, missing values, and duplicates.

Converted relevant columns (RAM, CPU speed, storage) into numeric form.

2. Exploratory Data Analysis (EDA)

Univariate Analysis: Distribution of prices, RAM, and storage.

Bivariate Analysis: Relation between price and brand, RAM, processor, etc.

Multivariate Analysis: Correlation matrix to find strongest predictors of price.

3. Visualization Highlights

📈 Bar Charts: Average prices by brand, RAM, and storage.

🔥 Heatmap: Brand vs Processor pricing patterns.

💡 Correlation Heatmap: Numeric factors influencing laptop price.

🖥️ Boxplots & Histograms: Price distributions and outliers.



🧠 Key Insights
Area	Key Finding
Brand Value	Acer, Asus, Lenovo, and HP offer best value; Apple and Razer dominate premium range.
RAM Impact	Strong positive correlation (0.74) with price — more RAM means higher cost.
Storage Impact	SSDs raise prices significantly compared to HDDs, even with smaller capacities.
Processor Trends	Intel i7 and Apple M2/M3 laptops are the most expensive; i5 and Ryzen 5 give best balance.
Premium Features	Dedicated GPUs (Nvidia GTX/Quadro) and macOS significantly increase price.
Screen Size	Weak correlation with price (0.07) — minimal influence on cost.




🧾 Conclusion

Laptop prices are driven primarily by RAM, CPU, and GPU.

SSD and dedicated graphics add substantial value.

Brand and processor combinations strongly determine affordability.

The insights can help both buyers and retailers optimize decisions.





