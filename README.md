# ⚔️ Old School RuneScape (OSRS) Zulrah Loot Analysis

_An end-to-end analysis of in-game boss loot, from web scraping to calculating expected value per kill._

---
## 📊 Table of Contents
<a href="#project-overview">Project Overview</a>
<a href="#tools--technologies">Tools & Technologies</a>
<a href="#project-workflow">Project Workflow</a>
<a href="#key-insights--visualizations">Key Insights & Visualizations</a>
<a href="#how-to-run-this-project">How to Run This Project</a>
<a href="#recruiter-perspective">A Recruiter's Perspective</a>

---
<h2><a class="anchor" id="project-overview"></a>🎯 Project Overview</h2>

This project analyzes the loot dropped by the in-game boss, Zulrah, from Old School RuneScape. The script programmatically scrapes drop data from the official OSRS Wiki, cleans and transforms the raw data into a usable format, and then conducts an analysis to identify the most profitable items.

The primary goal is to move beyond simple drop lists and calculate the expected Gold Piece (GP) value per kill, providing a clear metric of profitability for players.

---
<h2><a class="anchor" id="tools--technologies"></a>🛠️ Tools & Technologies</h2>

**Data Acquisition**: Python, Requests, BeautifulSoup4

**Data Analysis**: Python, Pandas, NumPy

**Data Visualization**: Matplotlib, Seaborn

**Environment**: Jupyter Notebook

---
<h2><a class="anchor" id="project-workflow"></a>⚙️ Project Workflow</h2>

**Web Scraping**: Dynamically fetches the latest drop table information directly from the OSRS Wiki page for Zulrah. This ensures the data is always up-to-date with game changes.

**Data Cleaning**: Includes custom parsing functions to handle non-standard data types found in the wiki table, such as quantity ranges (100–299) and complex rarity strings (2 × 1/1,024).

**Data Transformation**: Cleans and converts price and value columns into numeric types, handling commas and non-saleable items.

**Analysis & Visualization**: Calculates the weighted value of each drop by multiplying its price by its drop probability. The findings are presented through a series of clear and insightful charts.

---
<h2><a class="anchor" id="key-insights--visualizations"></a>💡 Key Insights & Visualizations</h2>

**Most Valuable Drops**: Identifies and charts the top 15 items by individual price, showing which drops are most sought after.

**Value Contribution**: A pie chart illustrates which item categories (e.g., "Unique", "Consumable") contribute the most to the total value.

**Rarity vs. Price**: A scatter plot explores the relationship between an item's rarity and its market price.

**Expected GP per Kill**: The core of the analysis, this calculation provides a clear view of what makes the boss profitable over time.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>🚀 How to Run This Project</h2>

**Prerequisites**: Jupyter Notebook or JupyterLab

**Installation**: pip install requests beautifulsoup4 pandas numpy matplotlib seaborn

**Execution**: Open the .ipynb file and run the cells sequentially.

---
<h2><a class="anchor" id="contact"></a>📞 Contact</h2>

**Harshad Mourya**<br>
Data Analyst<br>
📧 Email: mouryaharshad@gmail.com<br>
🔗 [LinkedIn](https://www.linkedin.com/in/harshad-mourya/)