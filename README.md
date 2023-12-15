# Dynamic-Pricing-Strategy

![Demand-analysts-shaking-hands-from-laptops-screens-and-planning-future-demand](https://github.com/SyedsProjectPortfolio45/Dynamic-Pricing-Strategy/assets/147240839/33e08fb9-2512-4c53-a093-b3eead28fb26)

#### Tools used🛠: Python, NumPy, Pandas, Machine Learning, Sci-kit Learn, Plotly
🔗dataset link --> https://statso.io/dynamic-pricing-case-study/

The above dataset contains:
- Historical sales data
- Customer purchase patterns
- Market demand forecasts
- Cost data
- Customer segmentation data, 
- and Real-time market data.

## 🚧You see the detailed code with visualizations by clicking on the Google Colab logo when you open the ipynb file

# Description
Dynamic Pricing is an application of data science that involves adjusting the prices of a product or service based on various factors in real time. It is used by companies to optimize revenue by setting flexible prices that respond to market demand, demographics, customer behaviour and competitor prices.
Using data-driven insights and algorithms, businesses can dynamically modify prices to achieve the most favourable outcomes.

# Objective
The aim is to maximize revenue and profitability of a ride-sharing firm by pricing items at the right level that balances supply and demand dynamics. It allows businesses to adjust prices dynamically based on factors like time of day, day of the week, customer segments, inventory levels, seasonal fluctuations, competitor pricing, and market conditions.

# Step-by-step approach
- Importing necessary Python Libraries
- Performing **EDA**
- Visualizing and Analyzing various factors using Scatter plot, Box plot and Heat map.
- Implemented a Dynamic Pricing Strategy:
  Calculated the demand multiplier by comparing the number of riders to percentiles representing high and low demand levels. If the number of riders exceeds the percentile for high demand, the demand multiplier is set as the number of riders divided by the high-demand percentile. Otherwise, if the number of riders falls below the percentile for low demand, the demand multiplier is set as the number of riders divided by the low-demand percentile.
- Next, we calculated the adjusted ride cost for dynamic pricing. It multiplies the historical cost of the ride by the maximum of the demand multiplier and a lower threshold (demand_threshold_low), and also by the maximum of the supply multiplier and an upper threshold (supply_threshold_high). This multiplication ensures that the adjusted ride cost captures the combined effect of demand and supply multipliers, with the thresholds serving as caps or floors to control the price adjustments.
- Calculated the profit percentage we got after implementing this dynamic pricing strategy
- Checked the relationship between the expected ride duration and the cost of the ride based on the dynamic pricing strategy using Donut plot
- Training a predictive model:
  -implemented a data preprocessing pipeline to preprocess the data
  -split the data and train a Machine Learning model to predict the cost of a ride using RandomForestRegressor
- Compared actual and predicted results using scatter plot

# Output
![Screenshot (2435)](https://github.com/SyedsProjectPortfolio45/Dynamic-Pricing-Strategy/assets/147240839/48197f76-a208-475a-bfb4-17304f99687b)




  
  
