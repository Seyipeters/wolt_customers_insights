# Customer Insights Analysis

This project analyzes customer data to extract insights about purchasing behavior, preferred restaurant types, and other key metrics. The analysis is performed using Python and Jupyter Notebook.

## Dataset
The dataset used for this analysis is dataset_for_datascience_assignment.csv. It contains customer-related information such as:
- Registration details
- Purchase counts
- Preferred restaurant types
- Total purchases in EUR
- Delivery and takeaway preferences
- Purchase times and frequencies

## Key Insights

### 1. Total Purchases Over Time
A line chart was created to visualize the trend of total purchases over time. This helps identify patterns in customer spending behavior.

### 2. Preferred Restaurant Types
A bar chart was used to analyze the total purchases (in EUR) by preferred restaurant types. This provides insights into customer preferences.

### 3. Most Engaged Users by Country
A bar chart was plotted to show the number of users by country. Finland was identified as having the most engaged users.

### 4. Purchase Frequency Segmentation
Customers were segmented based on their average days between purchases:
- Frequent: 0–7 days
- Moderate: 8–30 days
- Infrequent: 31+ days

The average and total spending for each segment were calculated and visualized.

### 5. Spending by Device
The average spending by preferred device (e.g., Android, iOS, Web) was analyzed and visualized using a bar chart.

### 6. Delivery vs Takeaway Preferences
A pie chart was created to compare the proportion of purchases made via delivery versus takeaway.

### 7. Purchases by Meal Type
The total purchases for different meal types (e.g., breakfast, lunch, dinner) were visualized using a bar chart.

### 8. Purchases by Hour of the Day
A bar chart was plotted to show the number of purchases made during different hours of the day.

## Tools and Libraries
The following Python libraries were used:
- pandas for EDA
- matplotlib and seaborn for data visualization


### Results and Recommendations

Based on the insights from the analysis and charts, here are some actionable recommendations:

#### 1. Total Purchases Over Time
- **Insight**: The trend of total purchases over time shows patterns in customer spending behavior.
- **Recommendation**:
    - Identify peak periods and align marketing campaigns or promotions with these times to maximize revenue.
    - Investigate dips in purchases to understand potential causes and address them.

#### 2. Preferred Restaurant Types
- **Insight**: Certain restaurant types generate higher total purchases.
- **Recommendation**:
    - Focus on promoting the most preferred restaurant types to attract more customers.
    - Collaborate with restaurants in the most popular categories to offer exclusive deals.

#### 3. Most Engaged Users by Country
- **Insight**: Finland has the most engaged users.
- **Recommendation**:
    - Invest in targeted marketing campaigns in Finland to further engage this audience.
    - Explore opportunities to replicate successful strategies in other countries with lower engagement.

#### 4. Purchase Frequency Segmentation
- **Insight**: Customers are segmented into frequent, moderate, and infrequent purchasers.
- **Recommendation**:
    - Offer loyalty programs or discounts to frequent purchasers to retain them.
    - Create targeted campaigns to convert moderate and infrequent purchasers into frequent buyers.

#### 5. Spending by Device
- **Insight**: Spending varies by preferred device but the IOS users has more spending.
- **Recommendation**:
    - Optimize the user experience on the most popular devices to encourage higher spending.
    - Develop device-specific promotions to engage users across all platforms.

#### 6. Delivery vs Takeaway Preferences
- **Insight**: Delivery purchases are more common than takeaways.
- **Recommendation**:
    - Enhance delivery services by improving speed, reliability, and customer satisfaction.
    - Offer incentives for takeaway orders to balance preferences and reduce delivery costs.

#### 7. Purchases by Meal Type
- **Insight**: Certain meal types (e.g., lunch, dinner) generate more purchases.
- **Recommendation**:
    - Focus marketing efforts on the most popular meal times to maximize sales.
    - Introduce meal-specific promotions (e.g., discounts on breakfast orders) to boost less popular categories.

#### 8. Purchases by Hour of the Day
- **Insight**: Purchases are concentrated during specific hours of the day.
- **Recommendation**:
    - Schedule promotions or discounts during off-peak hours to encourage more purchases.
    - Ensure adequate staffing and resources during peak hours to handle demand efficiently.

#### General Recommendations
- **Data-Driven Decisions**: We can use the above insights and recommendations to guide business strategies, such as pricing, promotions, and partnerships.
- **Customer Retention**: Implement loyalty programs and personalized offers to retain high-value customers.
- **Expand Market Reach**: Focus on underperforming segments or regions to grow the customer base.

These recommendations can help improve customer engagement, optimize operations, and increase revenue.
