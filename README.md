📌 Project Overview
This project analyzes the relationship between trader performance (PnL) and market sentiment using the Fear and Greed Index. By integrating historical trade data with sentiment classifications, I identified how different trader profiles respond to market extremes.

🛠️ How to Run
Clone the Repo: git clone https://github.com/YOUR_USERNAME/Trader-Performance-Analysis.git

Install Dependencies:

Bash

pip install pandas numpy matplotlib seaborn
Run Analysis: Open Mohamed_Saudy_Data_Science_Analytics_Intern_–_Round_0_Assignment_(Trader_Performance_vs_Market_Sentiment).ipynb in Jupyter or Google Colab and run all cells.

Note: Ensure fear_greed_index.csv and historical_data.csv are in the same directory.

📊 Methodology
Data Integration: Merged a historical trading dataset (211,224 records) with the Fear and Greed Index based on timestamps.

Performance Metrics: Calculated total PnL and identified unique account behaviors.

Trader Classification: Categorized accounts into groups such as "Inconsistent Winners" to track performance variance across sentiment phases.

💡 Strategy Recommendations
Based on the data analysis, the following trading rules are proposed:

1. The "Greed" Scaling Strategy
Rule: High-leverage traders should increase trade size and leverage during "Extreme Greed" periods.

Why: Analysis shows that high-leverage traders perform significantly better in these conditions, and this strategy amplifies those favorable momentum positions.

2. The "Fear" Risk Mitigation Strategy
Rule: "Inconsistent Winners" (traders with lower win rates) should reduce leverage and limit trade sizes during "Extreme Fear" periods.

Why: Data indicates these traders suffer the most significant drawdowns during Extreme Fear. Reducing exposure during these unfavorable conditions minimizes the risk of catastrophic loss.

📂 Repository Structure
Mohamed_Saudy_...ipynb: The complete analysis notebook.

fear_greed_index.csv: Sentiment data (Fear, Greed, Neutral).

historical_data.csv: Historical trade execution and PnL data.

README.md: Project documentation (this file).
