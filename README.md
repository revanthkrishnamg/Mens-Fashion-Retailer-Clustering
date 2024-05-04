# Customer Segmentation for a Men's Fashion Retailer

## Project Phases

### Data Discovery
The initial phase involves evaluating the efficiency of the retailer's marketing channels and understanding its diverse customer base. This phase sets the foundation for targeted analysis focused on optimization and growth.

### Data Preparation
#### Data Import and Cleaning
- **Data Sources**: Two primary datasets were used; `value_info` (30,591 rows, 5 columns) and `demographic_info` (31,441 rows, 7 columns).
- **Cleaning Steps**:
  - Checked and handled missing values.
  - Ensured correct data types for analysis.
  - Removed duplicate rows and outliers in specific stages to maintain data integrity.

#### Data Integrity and Aggregation
- Negative values in order counts and promotional values were addressed, identifying profits and losses.
- Created features for total profit and total orders per customer to gauge individual contributions to the retailer's revenue.

### Model Planning
Focused on analyzing channel performances and customer segmentation based on purchasing behaviors and demographic trends to derive actionable insights for marketing strategies.

### Model Building
#### Customer Segmentation with K-means Clustering
- Developed features such as Age, Gender, and Average Profit Per Order for deeper behavioral insights.
- Utilized the Elbow Method to identify an optimal number of clusters (k=4), indicating four distinct customer segments.
- Applied K-means clustering to categorize customers based on their purchasing behavior.

### Results Communication
Insights from the customer segmentation were visualized using heatmaps to compare mean values of features across clusters, revealing distinct characteristics of each customer segment such as premium, frequent, casual, and promotion-driven customers.

### Operationalize
Recommendations were made to enhance marketing efforts across different channels, targeting specific demographic groups and customer behaviors to maximize profitability and efficiency.

## Results and Insights
Detailed channel performance analysis and demographic analysis were conducted:
- Channels like Direct, Organic Search, and Paid Social showed varying levels of profitability and customer attraction.
- Demographic insights highlighted significant representation of younger and middle-aged individuals, with notable findings regarding the gender distribution in purchasing patterns.

## Strategic Recommendations
### Channel Performance
- **Organic Search**: Increase visibility to attract casual and frequent customers.
- **Affiliates**: Build partnerships focused on the men's fashion industry.
- **Paid Social**: Target premium customers through influencer collaborations.

### Demographic Recommendations
- **Age-Focused Marketing**: Tailor marketing to appeal to younger and middle-aged groups, considering introducing incentives for older age groups.
- **Gender-Inclusive Fashion**: Explore unisex fashion lines given the significant female customer base.

### Customer Behavior Recommendations
- **Engage Premium Customers**: Provide exclusive deals and personalized recommendations.
- **Incentivize Frequent Customers**: Encourage higher order values through bundling and discounts.
- **Promote to Promotion-Driven Customers**: Introduce tiered promotions to leverage their propensity for promotional offers.

## Conclusion
This customer segmentation analysis provides the men's fashion retailer with actionable insights to refine their marketing strategies, target their customer base more effectively, and explore new opportunities for growth.
