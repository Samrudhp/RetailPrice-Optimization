# Sales Price Elasticity Analysis

## Project Overview
This project analyzes the relationship between coffee prices and sales quantity to determine price elasticity of demand for different coffee products. Using linear regression, we can understand how price changes affect sales volume, helping optimize pricing strategies for maximum revenue.

## Key Features
- Price elasticity calculation using linear regression
- Data visualization of price-quantity relationships
- Automated analysis for multiple coffee products
- Clean data processing and handling

## Why Linear Regression?
Linear regression was chosen for this analysis because:
1. It helps establish the linear relationship between price (independent variable) and quantity sold (dependent variable)
2. The coefficient (slope) represents the price elasticity of demand, showing how quantity changes with price
3. It provides a simple, interpretable model for business decisions
4. The visualization capabilities help in understanding trends

## Understanding the Coefficient (Slope)
In this project, the coefficient (-3.5714 for Espresso) represents the price elasticity of demand:
- The negative value indicates an inverse relationship between price and quantity
- For every $1 increase in price, the quantity demanded decreases by approximately 3.57 units
- This high elasticity suggests that Espresso sales are quite sensitive to price changes

## Technical Features
### Data Processing
- Date conversion to datetime format
- Numeric conversion for price and quantity
- Grouped analysis by product type
- Null value checking

### Visualization
- Scatter plots of actual price-quantity relationships
- Regression line showing the trend
- Separate plots for each product category
- Custom-sized figures for better readability

## Dependencies
```
numpy
pandas
matplotlib
scikit-learn
```

## Dataset Structure
The analysis uses a CSV file with the following columns:
- date: Sale date
- product: Coffee type (Espresso, Cappuccino)
- price: Unit price
- quantity: Units sold

## Results and Interpretation
- The negative coefficient confirms that demand follows the law of demand
- The magnitude helps in understanding demand sensitivity
- Visualization shows the clear downward trend in quantity as price increases
- Results can be used for strategic pricing decisions

## Business Applications
1. Optimize pricing strategy
2. Forecast sales at different price points
3. Compare price sensitivity across products
4. Make data-driven pricing decisions

## Future Enhancements
- Add seasonal analysis
- Include more product categories
- Implement non-linear regression for complex relationships
- Add confidence intervals for predictions

## Usage
1. Ensure all dependencies are installed
2. Place your sales data in 'sales_data.csv'
3. Run the script to generate analysis and visualizations
4. Interpret results using the provided plots and elasticity values
