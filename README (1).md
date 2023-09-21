---
<a><font color = '#2471A3' size="6">Elo Customer Loyalty score Prediction</font></a>

---
<a ><font size="4"><b> Problem Statement </b></font></a>

For any payment brand working with Debit and Credit cards payments. These payment methods have partnerships with different merchants in order to offer promotions and discounts to cardholders.They have limitation where the company cannot recommend fully personalize brand recommendation to its customers nor they are able to stop unwanted campaign. So, each customer or cardholder has given a loyalty score which will **tell us whether recommended promotions or discounts works for cardholder or not**. Loyalty score helps to recognize loyal customers for ease of business by offering promotions or discounts without unwanted campaign.

<a ><font size="4"><b> Problem Solution </b></font></a>

This problem is a regression problem where we need to predict the **cardholder’s loyalty score*** in `userscore.csv`.  Loyalty score is numerical score which is **calculated two months after historical** and evaluation period of many factors including cards transactions.
- To solve the problem, we need to perform data quality analysis, statistical analysis, and regression analysis on the provided datasets and use this analysis to build a regression model to predict the loyalty score for each card id.

<a ><font size="4"><b> Machine Learning Problem Formulation </b></font></a>

- **Target** → Loyalty Score
- **Input Features** → all the existing and engineered features
- **Methods** →  
- **Evaluation Metric** → RMSE, R-squared

<a ><font size="4"><b> Data Files Information</b></font></a>

- **`userscore.csv`**: contains information about each card id (5 features) and the loyalty score. 
- **`historical_transactions.csv`**: this file contains up to 3 months' worth of transactions for every card at any of the provided merchant_id's.
- **`new_merchant_transactions.csv`**: contains the transactions at new merchants (merchant_ids that this particular card_id has not yet visited) over a period of two months.
- **`merchants.csv`**: contains aggregate information for each merchant_id represented in the data set.

