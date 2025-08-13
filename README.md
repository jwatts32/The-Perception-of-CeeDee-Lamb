# 🏈 The Perception of CeeDee Lamb

## 📊 Overview
During the first half of the 2023 NFL season, Dallas Cowboys wide receiver **CeeDee Lamb** faced criticism for not living up to expectations of a first-round draft pick, with some analysts questioning if he could be a true **#1 WR**. 🏈

As I started analyzing Lamb’s stats and trends over the course of the season, I realized this was a case where **perception ≠ reality**. One of my favorite things to do with sports analytics is use data to combat misconceptions—exactly what I did in this project. 📈

---

## 🔑 Key Features
- 🕸 **Web Scraping & Automated Data Extraction** – Pulled CeeDee Lamb’s 2023 game log directly from *Pro Football Reference* using `pandas.read_html`, extracting and cleaning only the relevant statistical table.  
- 🧹 **Data Cleaning & Transformation** – Resolved multi-level index issues, standardized column names, and removed unnecessary fields (e.g., rushing yards) to focus on receiving performance.  
- 📏 **Descriptive Statistics** – Computed and compared average *targets* and *receiving yards* across different segments of the season to highlight performance trends.  
- 📉 **Correlation Analysis** – Created a regression plot to quantify and visualize the relationship between targets and receiving yards, revealing a strong positive correlation.  
- 🎯 **Threshold Identification** – Determined median target values to explore potential performance shifts above or below key workload levels.  

---

## 💡 Insights and Results
- Through statistical analysis, I found that Lamb was indeed performing **up to and beyond expectations**.  
- The perception of underperformance was largely due to people focusing on **big-picture stats** like total receiving yards while ignoring **key contributing variables** such as targets.  
- By creating a regression plot, I visualized that his yardage output **increased significantly** with the number of targets:  
  - 🎯 **Below Median Targets** → ~60 yards/game  
  - 🚀 **Above Median Targets** → ~152 yards/game  

---

## 🛠 Technologies Used
- **Python**: pandas, numpy, matplotlib, seaborn
- **Web Scraping**: pandas.read_html
- **Jupyter Notebook** for exploratory analysis
- **Data Visualization**: Regression plots, trend analysis
