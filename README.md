# Dynamic Pricing Optimization System

## About the Project

I developed this project to explore how data analysis and regression can help businesses make better pricing decisions in retail.

The project uses historical retail sales data to study the relationship between product prices and demand. I built a demand prediction model for individual products and used it to calculate prices that could potentially maximize revenue.

## Why I Chose This Project

Pricing plays an important role in retail businesses. Setting a price too high may reduce demand, while setting it too low can affect revenue.

I wanted to understand how data analysis and statistical modeling could help identify a suitable price for different products.

## What I Worked On

- Explored and analyzed retail sales data.
- Cleaned and prepared the dataset using Python.
- Simulated product prices because the original dataset did not contain actual selling prices.
- Built separate linear regression models for 50 products.
- Studied how estimated demand changes with price.
- Calculated revenue at different price levels.
- Identified potential revenue-maximizing prices.
- Created visualizations to understand the results.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses a retail sales dataset containing:

- 913,000+ records
- 5 years of sales data
- 10 stores
- 50 product items

Since actual selling prices were not available in the original dataset, I generated simulated prices using base prices and random variations.

## How the Project Works

1. **Data Preparation:** Loaded and explored the retail dataset.
2. **Price Simulation:** Generated product prices for the analysis.
3. **Demand Modeling:** Built individual linear regression models for each product.
4. **Revenue Calculation:** Calculated estimated revenue at different price levels.
5. **Price Optimization:** Identified the price corresponding to the highest estimated revenue within the selected price range.
6. **Visualization:** Created charts to understand demand patterns and pricing recommendations.

The demand model follows:

`Q(P) = β₀ + β₁P`

Estimated revenue is calculated as:

`R(P) = P × Q(P)`

The optimal price is calculated using:

`P* = -β₀ / (2β₁)`

The recommended prices are restricted to a range of ±30% around the average price.

## Project Visualizations

The project includes:

- Demand Curve with Regression Fit
- Optimal Price Distribution
- Item-wise Price Recommendations
- Revenue Maximization Curve

## Results

- Analyzed more than 913,000 retail records.
- Built regression models for 50 individual products.
- Generated approximately 45,000 price recommendations for test records.
- Compared estimated demand and revenue across different price levels.
- Created visualizations to communicate the pricing analysis.

These results are based on simulated prices and estimated demand, so they should be treated as exploratory findings rather than verified real-world revenue improvements.

## Project Workflow

`Data Collection → Data Cleaning → Price Simulation → Demand Modeling → Revenue Optimization → Visualization`

## Project Files

- `dynamic-pricing.ipynb` – Jupyter Notebook containing the analysis and implementation.
- `DynamicPricing_ProjectReport.docx` – Project documentation.
- `Dynamic_Pricing_Final_Project.pptx` – Project presentation.

## How to Run

1. Clone this repository:

   `git clone https://github.com/SionRani/dynamic-pricing-optimization-system.git`

2. Open the project folder.

3. Install the required libraries:

   `pip install pandas numpy statsmodels matplotlib seaborn jupyter`

4. Open the notebook:

   `jupyter notebook`

5. Run the cells in sequence.

## Limitations and Future Scope

This project uses simulated prices, so the results do not establish actual customer price sensitivity.

In the future, I would like to improve the project by:

- Using real product pricing data.
- Including competitor pricing.
- Considering inventory levels and seasonal demand.
- Exploring more advanced demand forecasting techniques.
- Testing the recommendations against real sales outcomes.

## About Me

**Kondepudi Sion Rani**

- Email: [kondepudisionrani@gmail.com](mailto:kondepudisionrani@gmail.com)
- LinkedIn: [linkedin.com/in/sionrani](https://linkedin.com/in/sionrani)
- GitHub: [github.com/SionRani](https://github.com/SionRani)
- Portfolio: [sionrani.github.io](https://sionrani.github.io)
