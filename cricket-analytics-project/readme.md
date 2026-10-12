🏏 T20 CRICKET ANALYSIS DASHBOARD 📌 OVERVIEW This project analyzes and visualizes T20 cricket data using Power BI, Python, and Excel. It provides deep insights into player performances, team comparisons, and match trends through interactive dashboards. The dataset includes historical match records, player statistics, and web-scraped data.

📂 PROJECT STRUCTURE 🔹 1. DATA PROCESSING & PREPROCESSING 📜 t20_data_preprocessing.ipynb Jupyter Notebook for data cleaning, transformation, and feature engineering.

Handles missing values, outliers, and exploratory data analysis (EDA).

Uses Pandas, NumPy, Matplotlib, and Seaborn for preprocessing.

📁 t20_csv_files/ Contains raw and processed CSV files related to matches, teams, and players.

Used as an input source for Power BI and Python scripts.

📁 t20_json_files/ Stores structured cricket data in JSON format (fetched from APIs/web scraping).

Used for dynamic data retrieval and integration.

📁 web_scrapping_codes/ Python scripts for extracting real-time cricket data from online sources.

Uses BeautifulSoup, Scrapy, and Selenium for web scraping.

🔹 2. POWER BI DASHBOARD & ANALYTICS 📊 Codebasics Cricket Best 11.pbix Power BI file with a detailed Cricket Analysis Dashboard.

Includes DAX measures, calculated columns, filters, and interactive visuals.

Key Features:

Match Performance Overview (Runs, Wickets, Strike Rate, Economy Rate).

Player Comparison (Batsmen vs. Bowlers, Head-to-Head Analysis).

Team Analysis (Win/Loss Ratio, Powerplay Performance, Death Overs).

Venue & Conditions Impact (Pitch Type, Weather Influence).

Top 11 Player Selection Model based on advanced statistics.

📂 DAX Measures and Calculated Columns.xlsx Contains custom DAX formulas for Power BI reports.

Includes calculated columns, measures, and aggregated metrics.

📂 Dash_Screenshot/ Stores Power BI dashboard screenshots for documentation and reference.

🚀 FEATURES & INSIGHTS ✅ Data Cleaning & Preprocessing – Handling missing values, outliers, and formatting. ✅ Comprehensive Player Analysis – Strike rate, average, wickets, best performances. ✅ Team Performance Comparison – Win/loss ratios, batting vs. bowling trends. ✅ Match Trend Analysis – Impact of venues, weather, and game conditions. ✅ DAX & Power BI Visualizations – Advanced formulas and interactive reports. ✅ Automated Data Extraction – Web scraping for real-time updates.

🛠️ HOW TO USE THE PROJECT 1️⃣ Data Processing 🔹 Run t20_data_preprocessing.ipynb in Jupyter Notebook to clean and format data. 🔹 Ensure CSV/JSON files are correctly placed in respective folders.

2️⃣ Power BI Dashboard 🔹 Open Codebasics Cricket Best 11.pbix in Power BI Desktop. 🔹 Use filters and slicers for customized analysis.

3️⃣ Custom Analysis & Queries 🔹 Use DAX Measures and Calculated Columns.xlsx for Power BI calculations. 🔹 Modify Python scripts in web_scrapping_codes/ for live data extraction.

🔧 TECHNOLOGIES USED 💻 Python (Pandas, NumPy, Matplotlib, Seaborn) – Data preprocessing and analysis. 📊 Power BI – Dashboard creation and visualization. 📈 DAX (Data Analysis Expressions) – Advanced Power BI calculations. 📑 Excel – Storing and calculating additional metrics. 🌍 BeautifulSoup / Selenium – Web scraping cricket data. 🗃️ Git – Version control and collaboration.

📌 REQUIREMENTS ✅ Python 3.12.3 (or later)

✅ Power BI Desktop (Latest version recommended)

✅ Jupyter Notebook (for .ipynb scripts)

✅ Required Python Libraries: pandas, numpy, matplotlib, seaborn, beautifulsoup4, selenium

🔮 FUTURE ENHANCEMENTS 📡 Live Match Data Integration – API connections for real-time analytics. 📊 AI-Powered Player Performance Prediction – Machine Learning models. 📈 More Interactive Power BI Reports – Additional KPIs and visualizations.
