# Customer_segmentaion
segment customers into distinct clusters based on various featuresusing KMeans clustering.


 Objective:  The main goal of the project is to segment customers into distinct clusters based on various features (e.g., purchasing behavior, demographics, engagement) using KMeans clustering. This helps businesses understand their customer base and allows for more personalized marketing and business strategies.


Summary of the Notebook: Customer Segmentation Using Unsupervised Machine Learning
Objective:
The project aims to segment customers into distinct groups based on various features (such as purchasing behavior, demographics, and engagement) using K-Means clustering. The goal is to help businesses understand their customer base for personalized marketing and strategic decision-making.

Dataset Overview:
The dataset contains customer-related attributes, including:

Year_Birth (year of birth)

Education (level of education)

Marital_Status (relationship status)

Income (annual income, with 24 missing values)

Kidhome & Teenhome (number of children and teenagers in the household)

Dt_Customer (date of enrollment in the program)

Recency (days since the last purchase)

Spending-related columns (amount spent on wines, fruits, etc.)

No duplicate values were found in the dataset.

Methodology:
Data Preprocessing:

Missing values handled.

Feature scaling applied using StandardScaler.

Categorical variables encoded.

Dimensionality Reduction:

Principal Component Analysis (PCA) applied to reduce feature dimensions.

Clustering Model:

K-Means Clustering implemented to segment customers into groups.

Elbow method used to determine the optimal number of clusters.

Visualization & Insights:

Clusters visualized using scatter plots, histograms, and heatmaps.

Business insights extracted for better customer understanding.

Tools & Libraries Used:
Python Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

Machine Learning Techniques: K-Means Clustering, PCA

Data Processing: Standardization, Encoding, Missing value treatment

