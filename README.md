# Trader Performance vs. Market Sentiment Analysis

## Project Overview
This project explores the correlation between market sentiment—measured by the **Fear & Greed Index**—and the performance of individual traders. By analyzing historical trade data alongside sentiment levels, the notebook identifies behavioral patterns and performance trends across different market conditions (from "Extreme Fear" to "Extreme Greed").

The ultimate goal of this analysis is to derive data-driven trading strategies that optimize leverage and trade size based on prevailing market sentiment.

## Datasets
The analysis utilizes two primary datasets:
1.  **`fear_greed_index.csv`**: Contains daily sentiment scores (0-100), classifications (e.g., Extreme Fear, Greed), and timestamps.
2.  **`historical_data.csv`**: A comprehensive log of over 200,000 trades, including account IDs, coin types, execution prices, trade sizes (USD/Tokens), closed P&L, fees, and timestamps.

## Key Analysis Workflow
-   **Data Preparation**: Cleaning and merging historical trade logs with daily sentiment data using timestamps.
-   **Performance Metrics**: Calculating metrics such as Win Rate, Average P&L, and Total Volume for traders under different sentiment categories.
-   **Behavioral Profiling**: Analyzing how leverage and trade frequency change as market sentiment shifts.
-   **Strategy Derivation**: Identifying specific conditions where certain trader profiles (e.g., high-leverage vs. inconsistent winners) succeed or fail.

## Trading Strategy Insights
Based on the analysis, the following strategies were developed to optimize performance:

### 1. High-Sentiment Scaling (Extreme Greed)
* **Rule**: Traders using high leverage should increase their trade size and leverage during periods of **"Extreme Greed."**
* **Rational**: Data suggests that high-leverage traders tend to perform significantly better during these periods, as favorable market conditions amplify their positions effectively.

### 2. Risk Mitigation (Extreme Fear)
* **Rule**: "Inconsistent Winners" (traders with lower win rates) should reduce leverage and limit trade size during periods of **"Extreme Fear."**
* **Rational**: During extreme fear, these traders are more susceptible to significant drawdowns. Reducing exposure helps minimize risk and prevents large losses during unfavorable market volatility.

## Installation & Requirements
To run this notebook, ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1.  Ensure `fear_greed_index.csv` and `historical_data.csv` are in the same directory as the notebook.
2.  Open the notebook:
    ```bash
    jupyter notebook Mohamed_Saudy_Data_Science_Analytics_Intern_–_Round_0_Assignment_(Trader_Performance_vs_Market_Sentiment).ipynb
    ```
3.  Execute the cells sequentially to reproduce the analysis and visualizations.

---
**Author:** Mohamed Saudy  
