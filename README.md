# 📈 Trader Performance vs. Market Sentiment Analysis
**Data Science & Analytics Intern – Round 0 Assignment**

---

## 📌 Project Overview
This project analyzes the relationship between trader performance (PnL) and market sentiment using the **Fear and Greed Index**. By integrating historical trade data with sentiment classifications, I identified how different trader profiles respond to market extremes.

---

## 🛠️ How to Run
1. **Clone the Repo:** ```bash
   git clone [https://github.com/YOUR_USERNAME/Trader-Performance-Analysis.git](https://github.com/YOUR_USERNAME/Trader-Performance-Analysis.git)
Install Dependencies:Bashpip install pandas numpy matplotlib seaborn
Run Analysis: * Open Mohamed_Saudy_Data_Science_Analytics_Intern_–_Round_0_Assignment_(Trader_Performance_vs_Market_Sentiment).ipynb in Jupyter or Google Colab.Note: Ensure fear_greed_index.csv and historical_data.csv are in the same directory.Select Run All Cells.📊 MethodologyData Integration: Merged a historical trading dataset (211,224 records) with the Fear and Greed Index based on timestamps.Performance Metrics: Calculated total PnL and identified unique account behaviors.Trader Classification: Categorized accounts into groups such as "Inconsistent Winners" to track performance variance across sentiment phases.💡 Strategy RecommendationsBased on the data analysis, the following trading rules are proposed:1. The "Greed" Scaling StrategyRule: High-leverage traders should increase trade size and leverage during "Extreme Greed" periods.Why: Analysis shows that high-leverage traders perform significantly better in these conditions; this strategy amplifies those favorable momentum positions.2. The "Fear" Risk Mitigation StrategyRule: "Inconsistent Winners" (traders with lower win rates) should reduce leverage and limit trade sizes during "Extreme Fear" periods.Why: Data indicates these traders suffer the most significant drawdowns during Extreme Fear. Reducing exposure minimizes the risk of catastrophic loss.📂 Repository StructureFileDescriptionMohamed_Saudy_...ipynbThe complete analysis notebook and visualizations.fear_greed_index.csvSentiment data (Fear, Greed, Neutral).historical_data.csvHistorical trade execution and PnL data.README.mdProject documentation (this file).
### 💡 Pro Tip for GitHub:
Once you paste this, click the **"Preview"** tab at the top of the GitHub editor. You will see the bold text, horizontal lines, and the nice table layout!

**Would you like me to help you write a quick Python snippet to export your charts as images so they show up in your GitHub "Outputs" section?**
