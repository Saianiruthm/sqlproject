# SQL Task: Credit Cards Dataset

## Dataset Information

**Name:** `sql_task_credit_cards.sqlite`

**Structure:** 
- Columns: `[index], City, Date, CardType, ExpType, Gender, Amount`

This SQLite dataset contains credit card transaction details including city, date, card type, expenditure type, gender, and amount.

## SQL Insights

### Total Amount Spent
- **Query:** `1.txt`
- **Description:** Calculates the total amount spent by everyone.

### City-wise Expenditure Analysis
- **Queries:** `2.txt`
- **Insights:**
  - City with the highest and lowest total expenditure.
  - City with the highest and lowest average expenditure.

### Platinum Card Expenditure
- **Query:** `3.txt`
- **Insight:** Determines the expenditure type most used with the "Platinum" card.

### Additional Insights (4.txt)
Several insights have been generated including:
- Comparison of spending among different card types.
- Gender-based spending analysis.
- Top expenditure categories.
- Customer segmentation by city and card type.
- Customer loyalty assessment.
- Refunds and chargebacks analysis.
- Detection of outliers in spending.
- Demographic trends in spending.
- Geographical trends in spending.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/sql_credit_card_insights.git
   cd sql_credit_card_insights
2. **Access the Database and Run Queries:**
 - Load the SQLite database:
   ```bash
   sqlite3 sql_task_credit_cards.sqlite
 - Execute queries:
   ```bash
   sqlite3 sql_task_credit_cards.sqlite < queries/1.txt
3. **Review Insights:**
 - Examine the results generated by each query to gain insights into the credit card dataset.

## Contribution

If you'd like to contribute additional SQL queries, improve the dataset, or enhance the insights, feel free to fork this repository and submit a pull request.

## Note

 - The dataset is for educational purposes and contains fictional data.
 - Respect data privacy and legal considerations when working with real datasets.
