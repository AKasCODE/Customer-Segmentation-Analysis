# Customer Segmentation Analysis using RFM & K-Means Clustering

## Project Overview

This project performs customer segmentation using **RFM (Recency, Frequency, Monetary) Analysis** and **K-Means Clustering**. The objective is to group customers based on their purchasing behavior so businesses can better understand customer value and create targeted marketing strategies.

---

## Dataset

- **Dataset:** Online Retail Dataset
- **Records:** 541,909 transactions
- **Customers after cleaning:** 4,338
- **Features Used:** Invoice Date, Invoice Number, Quantity, Unit Price, Customer ID

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Data Cleaning
   - Removed duplicate records
   - Removed missing Customer IDs
   - Removed returned and cancelled transactions
   - Removed records with invalid prices

2. Feature Engineering
   - Created Total Amount
   - Generated RFM features:
     - Recency
     - Frequency
     - Monetary

3. Feature Scaling
   - Standardized RFM features using StandardScaler

4. K-Means Clustering
   - Used the Elbow Method to determine the optimal number of clusters
   - Applied K-Means clustering with K = 3

5. Customer Segmentation
   - VIP Customers
   - Regular Customers
   - Inactive Customers

---

## Visualizations

- Elbow Method
- Customer Segment Distribution
- Average Recency by Segment
- Average Frequency by Segment
- Average Monetary Value by Segment

---

## Business Insights

- Most customers belong to the **Regular** segment, making them the primary customer base.
- **VIP Customers** represent a very small percentage of customers but contribute significantly through frequent and high-value purchases.
- **Inactive Customers** have not purchased for a long period and can be targeted with re-engagement campaigns.
- Customer segmentation enables businesses to personalize marketing strategies instead of treating every customer the same.

---

## Project Structure

```
Customer-Segmentation-Analysis/
│
├── Customer_Segmentation.ipynb
├── Online Retail.xlsx
├── README.md
```

---

## Future Improvements

- Use Silhouette Score for cluster evaluation.
- Compare K-Means with hierarchical clustering.
- Build an interactive Power BI dashboard for customer segments.
- Deploy the project using Streamlit.

---

## Author

Arpit
