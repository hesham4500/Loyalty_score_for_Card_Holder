---
<a><font color = '#2471A3' size="6">Elo-custome Segmentation</font></a>

---
<a ><font size="4"><b> Problem Statement </b></font></a>

For any payment brand working with Debit and Credit cards payments. These payment methods have partnerships with different merchants in order to offer promotions and discounts to cardholders.They have limitation where the company cannot recommend fully personalize brand recommendation to its customers nor they are able to stop unwanted campaign. The goal is to gain insights into the structure of the data and discover any underlying patterns or relationships that may exist within it, without the use of any labeled data or prior knowledge.


<a ><font size="4"><b> Problem Solution </b></font></a>



<a ><font size="4"><b> Machine Learning Problem Formulation </b></font></a>

- **Target** → Loyalty Score
- **Input Features** → all the existing and engineered features
- **Methods** →  Kmeans, PCA, t-SNE, Apriori
- **Evaluation Metric** → Elbow Method, silhouette Score, Support, and Confidance.

<a ><font size="4"><b> Data Files Information</b></font></a>

- **`userscore.csv`**: contains information about each card id (5 features) and the loyalty score.
- **`historical_transactions.csv`**: this file contains up to 3 months' worth of transactions for every card at any of the provided merchant_id's.
- **`new_merchant_transactions.csv`**: contains the transactions at new merchants (merchant_ids that this particular card_id has not yet visited) over a period of two months.
- **`merchants.csv`**: contains aggregate information for each merchant_id represented in the data set.

<a ><font size="4"><b> Project Pipleline (Workflow)</b></font></a>
