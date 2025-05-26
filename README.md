# customer-personality-analysis

This project explores a real-world marketing dataset to understand customer behavior, segment customers, and predict marketing campaign response.

It involves:
- Visual EDA
- KMeans Clustering (Customer Segmentation)
- Classification (Response Prediction)

---


## Dataset Info

- Source: [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- Type: Tab-separated CSV
- Size: ~2,200 customer records
- Features include: demographics, product spending, marketing response

---

### EDA Insights
- Younger customers tend to spend more on wines and sweets.
- Customers with higher income don’t always spend more — behavior varies by segment.
- Marital status affects response rates: Singles and Together groups showed better engagement.

### KMeans Clustering
- Segmented customers into 4 groups based on age, income, tenure, and total spend.
- Found high-value segments ("VIP shoppers") and low-engagement segments ("Dormant group").

### Classification Model
- Built a Random Forest to predict if a customer would respond to a marketing campaign.
- Addressed class imbalance using class weighting.
- Achieved ~85% overall accuracy, with room for improving recall on responders.

---

