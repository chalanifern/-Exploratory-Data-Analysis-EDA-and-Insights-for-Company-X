Company X — Event Data Analytics

Project Overview

This project focuses on analyzing customer behavior, audience demographics, event attendance, ticket pricing, customer satisfaction, and spending patterns for Company X.

Using Python and data analytics techniques, the project explores audience and event datasets to identify trends, understand customer preferences, and generate actionable business insights that can support data-driven decision-making.

The analysis covers Exploratory Data Analysis (EDA), descriptive statistics, data quality checks, data visualization, and business insight generation.

Objectives
- Analyze audience demographics and customer purchasing behavior.
- Identify the countries contributing the highest audience numbers.
- Examine attendance patterns across different seating regions.
- Investigate the relationship between ticket prices and customer satisfaction.
- Compare merchandise and drink spending between repeat and non-repeat visitors.
- Identify spending outliers and potential high-value customers.
- Analyze event attendance and ticket sales patterns over time.
- Explore customer engagement, recommendation likelihood, and retention opportunities.
- Provide business recommendations based on analytical findings.

Datasets
The project uses two datasets:
1. Company_X_Audience
Contains customer-level information about audience demographics, event visits, and purchasing behavior.

Key features include:
- `Customer_ID`
- `Age`
- `Gender`
- `Country`
- `Seating_Region`
- `Ticket_Price`
- `Merchandise_Spend`
- `Drink_Spend`
- `Satisfaction_Score`
- `Recommendation_Likelihood`
- `Repeat_Visit`
- `Visit_Date`

**Dataset size:** 800 rows and 13 columns.
2. Company_X_ShowData
Contains event-level information about attendance, revenue, ticket prices, and event conditions.

Key features include:
- `Show_Date`
- `Attendance`
- `Avg_Ticket_Price`
- `Avg_Merch_Sales`
- `Revenue`
- `Weather_Score`
- `Guest_Performance`
- `Date_Type`
- `Region`

**Dataset size:** 200 rows and 10 columns.

Technologies and Libraries
The project uses the following technologies:

- **Python** — Data analysis and processing
- **Pandas** — Data manipulation, aggregation, and analysis
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Excel and Google Colab** — Development and analysis environment

🔍 Project Workflow
1. Data Understanding
- Inspected the structure and dimensions of both datasets.
- Examined column names and data types.
- Identified categorical, numerical, and date features.

2. Data Cleaning and Validation
- Checked for missing values.
- Checked for duplicate records.
- Validated feature data types.
- Identified an invalid non-numerical value (`y`) in the `Attendance` column of the event dataset and replaced it with a blank value to preserve the remaining information in the record.

3. Exploratory Data Analysis
- Analyzed audience distribution by country.
- Examined attendance across seating regions.
- Investigated ticket prices and satisfaction scores.
- Compared merchandise and drink spending by repeat-visit status.
- Identified unusual spending patterns and potential outliers.
- Explored correlations among ticket price, additional spending, and customer satisfaction.

4. Descriptive Statistics
- Generated summary statistics for numerical features.
- Examined categorical feature distributions.
- Compared satisfaction levels between VIP and Economy seating regions.
- Interpreted customer engagement value.

5. Time-Based Analysis
- Examined ticket revenue over time.
- Analyzed average attendance by day of the week.
- Investigated monthly attendance patterns and potential seasonality.

6. Business Insights and Recommendations
- Identified customer segments with potential for increased revenue.
- Evaluated whether higher ticket prices correspond to higher satisfaction.
- Investigated differences between repeat and non-repeat visitors.
- Developed recommendations for customer retention, pricing, and targeted promotions.

Key Findings

Audience Distribution
Sweden, France, the USA, Australia, and Japan were identified as the five leading countries by audience contribution in the analysis.

Seating Region Preferences
Economy seating accounted for approximately 31% of the audience, followed by High Economy at 29%, Premium at 24%, and VIP at 17%.

This suggests that lower-priced seating options attracted a larger proportion of attendees.

Ticket Price vs. Customer Satisfaction
Customer satisfaction was relatively consistent across ticket price categories. The analysis did not indicate a strong relationship between higher ticket prices and higher satisfaction.

**Business implication:** Company X could review its premium ticket benefits and pricing strategy to improve perceived value.

Customer Spending Behavior
Repeat visitors spent an average of approximately $60.40 on merchandise and $20.00 on drinks. Non-repeat visitors spent approximately $59.40 on merchandise and $19.60 on drinks.

The differences were small, suggesting that repeat-visit status was not associated with a substantial difference in average spending in this dataset.

Attendance Trends
The analysis identified variations in attendance across days of the week and months of the year.

March had the highest reported average monthly attendance, at approximately 5,077 visitors, while November had the lowest, at approximately 3,347 visitors.

These patterns could help inform event scheduling and marketing campaigns.

Customer Satisfaction and Retention
Repeat and non-repeat visitors showed similar recommendation likelihood in the analysis.

This suggests an opportunity for Company X to investigate why positive customer experiences do not necessarily translate into repeat visits and to evaluate loyalty programs and targeted retention incentives.

High-Value Customers
Spending distributions revealed potential high-spending customers in merchandise and drinks.

Understanding these customer segments could help Company X develop targeted offers and improve additional revenue opportunities.

Business Recommendations
Based on the analysis, the following actions could be considered:

1. **Improve customer retention:** Explore loyalty programs and targeted incentives to encourage repeat visits.
2. **Review premium ticket offerings:** Consider additional benefits to strengthen the perceived value of VIP and Premium tickets.
3. **Optimize event scheduling:** Use attendance patterns to inform event planning and promotional activities.
4. **Target high-value customers:** Develop personalized promotions for customers with higher spending potential.
5. **Improve additional sales:** Explore merchandise bundles, promotions, and beverage offers to increase spending during events.
6. **Investigate customer dissatisfaction:** Examine factors affecting lower satisfaction scores across ticket price categories.

 Skills Demonstrated

- Data cleaning and validation
- Exploratory Data Analysis (EDA)
- Descriptive statistics
- Data aggregation and grouping
- Statistical visualization
- Correlation analysis
- Outlier detection
- Time-series and seasonal pattern exploration
- Business insight generation
- Data-driven decision-making

Author
Chalani Fernando
BSc (Hons) Computer Science
Interested in Data Analytics, Artificial Intelligence, Machine Learning, Cloud and DevOps.

---

⭐ If you find this project interesting, feel free to explore the repository and its analysis.
