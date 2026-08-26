# FMCG_Sales_And_Supply_Chain_Analytics
FMCG sales and supply chain analytics using Python, Pandas, NumPy, Matplotlib and Seaborn with business-focused EDA and insights.

##  Business Objective

The objective of this project is to analyze sales and supply chain data and answer important business questions related to:
- Revenue and profit performance
- Customer segment performance
- Product profitability
- Category performance
- Sales trends
- Discount impact on profit
- Loss-making products and categories
- Inventory movement and potential overstock risk

##  Dataset

The analysis is based on four interconnected datasets:

| Dataset | Description |
|---|---|
| Customers | Customer information and customer segments |
| Products | Product details, categories and pricing |
| Orders | Transaction-level sales, quantity, revenue and profit |
| Inventory | Product inventory and movement information |

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub

##  Data Cleaning

The datasets were cleaned and prepared for analysis by performing:

- Missing value checks
- Duplicate record checks
- Data type validation and conversion
- Date formatting
- Text standardization
- City/value standardization
- Negative and inconsistent value investigation
- Inventory consistency checks
- Creation of calculated fields where required

##  Exploratory Data Analysis

The cleaned datasets were analyzed using Python to investigate:

- Customer distribution across segments and cities
- Product category distribution
- Product price distribution
- Order quantity patterns
- Revenue and profit trends
- Monthly sales performance
- Top revenue-generating products
- Category-level revenue and profitability
- Customer segment revenue and profit
- Profit margin across products and categories
- Discount versus profit relationship
- Loss-making products and categories
- Fast-moving and slow-moving products
- Potential inventory risks

##  Key Business Insights

### Customer & Segment Performance

- Retailers and Supermarkets represent the largest customer segments, indicating strong dependence on offline channels.
- The Online segment has the highest profit margin despite generating the lowest revenue, indicating potential for profitable growth.
- Supermarket is the largest customer segment by both revenue and absolute profit.

### Product Performance

- Household and Beverages have the largest product assortment, with 11 products each.
- Most products are concentrated in the ₹100–₹300 price range.
- 50% of products are classified as high-margin, while only 6% are classified as low-margin.
- No products were classified as loss-making based on the defined margin classification.

### Sales & Category Performance

- Beverages generate the highest category revenue.
- Snacks generate the highest total category profit.
- Snacks and Packaged Food have the highest profit margins at approximately 27%.
- Personal Care has the lowest profit margin among the analyzed categories.

### Discount & Profitability

- Discount percentage has a weak negative correlation with profit (-0.28).
- Higher discount levels are generally associated with lower average profit.

### Inventory & Product Movement

- Fast-moving products require higher replenishment priority.
- Slow-moving products with relatively high stock levels should be monitored for potential overstock risk.

##  Business Recommendations

1. **Expand the Online Segment**
   
   Explore strategies to increase Online sales while maintaining its relatively high profit margin.

2. **Optimize Product Profitability**
   
   Review pricing, discounts and cost structures for low-margin and loss-making categories.

3. **Improve Discount Management**
   
   Evaluate discount levels using both profitability and sales volume before establishing discount thresholds.

4. **Prioritize High-Performing Products**
   
   Maintain strong inventory availability for leading revenue-generating products.

5. **Improve Inventory Planning**
   
   Prioritize fast-moving products while monitoring slow-moving products to reduce potential overstock.

##  Future Scope

- Build an interactive Power BI dashboard for business reporting.
- Develop demand forecasting models using historical sales data.
- Build inventory risk prediction models.
- Explore product-level demand prediction.
- Extend the analysis with machine learning techniques.














