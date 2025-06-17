# Observing-Effect-of-Union-Budget-on-Stock-Market-Index-in-India
This project investigates the short-term effects of India’s Union Budget announcements on the performance of two major stock indices—Nifty 50 and BSE Sensex—using data visualization and statistical observation.

📊 Project Objective
To analyze and visualize how financial markets react in the immediate days before and after the Union Budget, with a focus on changes in:

1. Volume traded
2. Open and Close prices
3. Volatility patterns

🛠️ Methodology
I. Data Extraction & Cleaning: Index data was obtained and preprocessed using Python for consistency and accuracy.

II. Event Window Analysis:

      1. Simple plotting of 5-day windows before and after the budget announcement for both NSE and BSE indices.
      2. Simple plotting of fortnight(14 days) windows before and after the budget announcement for both NSE and BSE indices.
      3. Ploting of moving average computed with lag of 3 on fortnight(14 days) windows before and after the budget announcement for both NSE and BSE indices  to reduce      short-term market noise.

Visualization:

1. Time-series plots were generated for both price and volume metrics.
2. Separate comparative curves were created for daily vs. fortnight changes to enhance interpretability.

📌 Key Findings
1. Consistent increases in trading volume and notable changes in open and close prices were observed in the post-budget window for both Nifty and Sensex.
2. The fortnight-based difference analysis confirmed these trends while reducing short-term noise, making the patterns clearer and more interpretable.
3. Year 2025 exhibited unusually high volatility, indicating heightened market sensitivity to budget policies or external economic conditions during that period.

📦 Tools & Libraries Used
1. pandas and numpy for data handling
2. matplotlib visualization
3. Basic statistical comparisons and plotting logic for pattern detection

🎯 Takeaways
This project demonstrates how event-based time series analysis can reveal market behavior in response to policy announcements. The step-by-step approach—from raw data to plotted insights—makes it an excellent reference for those exploring financial econometrics, economic policy analysis, or investment strategy research.
