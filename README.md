# Customer Segmentation Using K-Means Clustering

## Project Overview
This project applies unsupervised machine learning to segment retail customers based on purchasing behavior using the Online Retail dataset. Recency, Frequency, and Monetary (RFM) features are engineered to identify customer groups and support data-driven business decisions.

## Objectives
- Analyze and clean retail transaction data
- Create customer-level RFM features
- Apply log transformation and feature scaling
- Determine the number of clusters using the Elbow Method
- Perform K-Means clustering
- Evaluate cluster quality using the Silhouette Score
- Visualize customer clusters using PCA
- Analyze customer segment profiles

## Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load and inspect the dataset
2. Clean transaction records and remove invalid data
3. Calculate total transaction revenue
4. Aggregate customer-level RFM features
5. Apply log transformation
6. Standardize features using StandardScaler
7. Analyze inertia using the Elbow Method
8. Apply K-Means clustering
9. Evaluate clustering using the Silhouette Score
10. Visualize clusters using PCA
11. Analyze customer segment characteristics
12. Export the clustering results

## Dataset
The project uses the Online Retail transactional dataset. The notebook expects `Online Retail.xlsx` to be available in the working directory.

## How to Run
1. Clone or download this repository.
2. Install the dependencies:

   `pip install -r requirements.txt`

3. Place the dataset `Online Retail.xlsx` in the notebook working directory.
4. Open `Customer_Segmentation.ipynb` in Jupyter Notebook or Google Colab.
5. Run all cells sequentially.

## Outputs
- Elbow Method visualization
- PCA customer cluster visualization
- Cluster size visualization
- Customer segmentation CSV
- Cluster profile CSV
- PCA coordinates CSV
- Elbow inertia CSV

## Business Applications
Customer segmentation can support:
- Targeted marketing
- Customer retention
- Loyalty program planning
- Identifying high-value customers
- Personalized promotions
- Business strategy and decision-making

## Author
Purva Ghate

## License
For educational and portfolio purposes.
