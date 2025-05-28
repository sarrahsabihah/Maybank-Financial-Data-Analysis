Maybank Financial Data Analysis
Project Overview
This project aims to analyze key financial trends of Maybank, specifically focusing on its Dividend Per Share (DPS), Earnings Per Share (EPS), and Payout Ratio. By examining these metrics over time, the analysis seeks to provide insights into Maybank's dividend growth, the consistency between its earnings and dividend distributions, and the evolution of its dividend policy.
Analysis Aims
	1. Dividend Growth or Decline: Assess the historical trend of Maybank's Dividend Per Share to identify periods of growth, decline, or stagnation.
	2. Earnings vs. Dividends Consistency: Evaluate how closely Maybank's dividend payouts align with its earnings performance.
	3. Maybank's Dividend Policy Over Time: Understand Maybank's approach to distributing profits to shareholders by analyzing the Payout Ratio trend.
Dataset
The analysis is based on financial data provided in the dataset_mb.csv file. This dataset contains quarterly financial metrics, including EPS, DPS, and other relevant financial indicators.
Features
	• Data Loading & Cleaning: Reads the CSV dataset and performs essential cleaning, such as stripping whitespace from column names and converting the 'Year' column to datetime objects for proper time-series analysis.
	• Payout Ratio Calculation: Dynamically calculates the Payout Ratio ((DPS / EPS) * 100) for each entry.
	• Annual Data Aggregation: Groups the data by year and calculates the mean of EPS, DPS, and Payout Ratio to provide annual trends.
	• Interactive Visualizations: Generates three interactive line charts using Altair to visualize:
		○ EPS Trend Over Time
		○ DPS Trend Over Time
		○ Payout Ratio Trend Over Time
	• Exportable Charts: Saves the generated charts as .json files, which can be easily shared and viewed in any Vega-Lite compatible viewer or directly in a web browser.
Requirements
To run this project, you will need Python installed, along with the following libraries:
	• pandas
	• altair
You can install these dependencies using pip and the provided requirements.txt file:
pip install -r requirements.txt
Usage
	1. Clone the Repository:
git clone https://github.com/your-username/maybank-financial-analysis.git
cd maybank-financial-analysis

(Replace your-username/maybank-financial-analysis.git with your actual repository URL)
	2. Place the Dataset: Ensure the dataset_mb.csv file is placed in the root directory of the cloned repository.
	3. Install Dependencies: If you haven't already, install the required Python libraries:
pip install -r requirements.txt
	4. Run the Analysis Script: Execute the Python script:
python financial_analysis.py

(Assuming your main analysis script is named financial_analysis.py. If you named it something else, adjust the command accordingly.)
	5. View the Results: After running the script, three .json files will be generated in the same directory:
		○ eps_trend_over_time.json
		○ dps_trend_over_time.json
		○ payout_ratio_trend_over_time.json
You can open these .json files in a web browser or use an online Vega-Lite editor (e.g., Vega Editor) to interact with the charts.
Interpretation Guide
Once you have the visualizations, here's how to interpret them to address your project aims:
	• Dividend Growth or Decline (DPS Trend Chart):
		○ Observe the general direction of the line. An upward slope indicates growth, while a downward slope suggests decline.
		○ Note the steepness of the slope to understand the rate of change.
		○ Identify any significant peaks, troughs, or periods of stagnation.
	• Earnings vs. Dividends Consistency (Comparing EPS and DPS Trend Charts):
		○ Visually compare the movement of the EPS and DPS lines.
		○ If they move in tandem (both rising or falling together), it indicates a strong relationship and consistency.
		○ If DPS remains stable while EPS fluctuates, it suggests a policy aimed at consistent payouts regardless of short-term earnings volatility.
		○ If DPS grows significantly faster than EPS, it might signal an aggressive or potentially unsustainable dividend policy.
	• Maybank's Dividend Policy Over Time (Payout Ratio Trend Chart):
		○ Stable Ratio: Suggests a consistent policy of distributing a fixed percentage of earnings.
		○ Increasing Ratio: May indicate a more generous dividend policy, potentially due to strong cash flow, fewer reinvestment opportunities, or a strategic decision to return more capital to shareholders. Be mindful of ratios exceeding 100%, as this implies paying out more than earned, which is unsustainable.
		○ Decreasing Ratio: Could mean the company is retaining more earnings for reinvestment (e.g., expansion, debt reduction) or adopting a more conservative payout approach.
Contributing
Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to:
	1. Fork the repository.
	2. Create a new branch (git checkout -b feature/your-feature-name).
	3. Make your changes.
	4. Commit your changes (git commit -m 'Add new feature').
	5. Push to the branch (git push origin feature/your-feature-name).
	6. Open a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
![Uploading image.png…]()
