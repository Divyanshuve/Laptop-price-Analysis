Laptop Price Analysis - Data Analytics Report

Project Overview
This project aims to analyze and predict laptop prices based on their specifications. Using Exploratory Data Analysis and data visualization, we uncover key insights into pricing trends and influential factors such as brand, processor, RAM, storage, GPU, screen resolution, and more.

Dataset Overview
The dataset consists of detailed laptop specifications, structured into multiple columns to facilitate efficient data exploration, preprocessing, and modeling. Key features include:

- Company – Laptop manufacturer (Dell, HP, Apple, etc.).
- Product – Model name.
- TypeName – Type of laptop (Notebook, Ultrabook, Gaming, etc.).
- Screen Specifications – Includes screen size, resolution, Retina display, touchscreen, IPSpanel.
- CPU Details – Includes CPU frequency, CPU model, and manufacturer.
- RAM & Storage – Total RAM (GB), Primary and Secondary storage capacity, and storage type(HDD, SSD, Flash Storage, Hybrid).
- GPU Details – Includes GPU manufacturer and model.
- Weight  – Laptop weight in kilograms.
- Operating System – Installed OS such as Windows, macOS, Linux.
- Price (Target Variable) – Laptop price in Euros. 


Data Analytics Process
The analysis is executed through a combination of Python (Jupyter Notebook) for data exploration, DAX for advanced calculations, and Power BI for visualization.

. Data Exploration using Python (Jupyter Notebook)
Step 1: Data Loading & Inspection
- The dataset is loaded using Pandas and inspected for missing values, data types, and formatting.

Step 2: Data Cleaning & Preprocessing
- Duplicate rows removed.
- Handling missing values: Filling missing numeric data using media, categorical data using mode.


Step 3: Exploratory Data Analysis (EDA)
- Feature correlation analysis to determine the most impactful variables.
- Visualizing price distribution based on laptop type, brand, screen resolution, and storage.


3. Advanced Analytics using DAX in Power BI
Power BI is leveraged for interactive dashboards, where advanced calculations provide deep insights.

Key Metrics Created using DAX:
- Average Laptop Price

- Brand-wise Market Share

- Correlation Analysis Between Price & Specifications.

Power BI Dashboards Created:
- Laptop Price Distribution by Brand
- Screen Resolution & Price Influence
- Processor Impact on Laptop Price
- Time Series Analysis of Laptop Pricing Trends
- Interactive Filters for Laptop Comparisons

Laptop Price Analysis Report
Objective
The goal of this analysis is to uncover laptop pricing trends based on hardware specifications, brand influence, and storage configurations. The visualizations provide insights into market positioning, touchscreen adoption, storage types, and operating system preferences.

Key Findings from Visualizations
1. Company-wise Sales Distribution
Major players in the laptop market include:
- Dell, Lenovo, HP, Asus, Acer, MSI, Toshiba, Apple, Samsung, and Razer.
- Dell, Lenovo, and HP dominate the market with the highest sales figures.
- Lesser-known brands like Vero, Chuwi, Mediacom, and Fujitsu have minimal sales impact.

2. Operating System Preferences
- Windows 10 holds the majority share among OS choices.
- Other OS options include Linux, Chrome OS, macOS, and Windows 7.
- Minimal adoption of Android and Windows 10 S, suggesting their limited relevance in the laptop market.

3. Touchscreen Availability
- Only 14.75% of laptops feature touchscreen functionality, with a significant 85.25% non-touchscreen devices.
- Touchscreen models tend to be premium-priced, as reflected in sales volume comparison.

4. RAM Configurations
Common RAM configurations in laptops:
- 8GB RAM is the most prevalent, followed by 4GB and 16GB.
- High-performance devices feature 32GB, 64GB, and even 24GB RAM configurations.
- 2GB RAM laptops remain in circulation, likely in budget and entry-level devices.

5. CPU & GPU Manufacturers
- Intel leads the CPU market (95.22%), followed by AMD (4.71%).
- Nvidia dominates GPU sales (55.22%), while Intel GPUs are widely used for integrated graphics.
- ARM-based laptops show minimal sales impact.

6. Screen Size & Display Types
Laptop screen sizes:
- Most common sizes: 15.6”, 14”, and 13.3” inches.
- Larger screen sizes (17” and above) cater to gaming and professional applications.

Screen resolutions:
- Full HD dominates the market.
- 4K Ultra HD and Quad HD+ are premium features, while Standard HD screens remain relevant in budget models.

7. Storage Preferences
Primary storage types:
- SSD is the most preferred storage option, followed by HDD and hybrid models.
- Flash storage adoption is minimal, indicating preference for traditional SSDs and HDDs.

Secondary storage trends:
- Majority of laptops do not feature secondary storage expansion.
- When available, common secondary storage capacities include 256GB, 500GB, 1TB, and 2TB SSD/HDD options.

8. OS and Touchscreen Sales Trends
- Windows 10 laptops have the highest revenue generation.
- Touchscreen-enabled models contribute significantly to higher-priced devices.
- Non-touchscreen laptops dominate overall sales, reflecting user preferences.

9. OS vs. CPU Frequency Correlation
- Higher CPU frequencies (2.5GHz and above) correlate with premium pricing.
- Lower frequencies (below 1.5GHz) are common in budget-friendly devices.
- Windows laptops span all CPU frequency ranges, indicating diverse product offerings.

10. Company-wise Revenue Generation
- Dell, Lenovo, and HP lead in revenue generation.
- Apple, Razer, and MSI laptops show premium pricing, focusing on high-end users.
- Brands like Chuwi, Mediacom, and Vero contribute minimally to market sales.
