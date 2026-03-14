# Trader Sentiment Analysis

## Project Overview
This project analyzes cryptocurrency trader behavior under different market sentiment conditions using the Fear & Greed Index.

The objective is to understand how trader performance and behavior change during Fear and Greed market phases.

---

## Methodology

1. Loaded two datasets:
   - Fear & Greed Index dataset
   - Historical trader transaction dataset

2. Cleaned and prepared the data.

3. Converted timestamp columns to datetime format.

4. Created a common **date column** to align both datasets.

5. Merged datasets using the date column.

6. Created key metrics:
   - Daily PnL per trader
   - Win Rate
   - Average Trade Size
   - Trading Activity
   - Long vs Short ratio

7. Analyzed trader performance across different sentiment classifications.

---

## Key Insights

• Traders achieve the **highest average PnL during Extreme Greed periods**.

• **Trading activity increases during Fear periods**, suggesting traders become more active during market uncertainty.

• Traders take **larger trade sizes during Fear**, indicating stronger conviction or risk-taking behavior.

---

## Strategy Recommendations

1. During **Fear markets**, traders increase activity and position size.  
   → Strategy: Increase position size moderately as markets may offer buying opportunities.

2. During **Extreme Greed**, traders reduce trade sizes and performance stabilizes.  
   → Strategy: Reduce exposure as markets may become overextended and reversal risk increases.

---

## Setup

Install required libraries:

---

## How to Run

1. Clone the repository
2. Open the Jupyter notebook
3. Run all cells to reproduce the analysis and charts.

---

## Tools Used

Python  
Pandas  
Matplotlib  
Jupyter Notebook
