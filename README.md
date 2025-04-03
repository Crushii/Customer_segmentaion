
segment customers into distinct clusters based on various features using KMeans clustering.
Summary of the Notebook: Customer Segmentation Using Unsupervised Machine Learning  

Objective: The project aims to segment customers into distinct groups based on various features (such as purchasing behaviour, demographics, and engagement) using K-Means clustering. The goal is to help businesses understand their customer base for personalized marketing and strategic decision-making.


•	Dataset Overview: The dataset contains customer-related attributes, including:
Year_Birth (year of birth)
Education (level of education)
Marital_Status (relationship status)
Income (annual income, with 24 missing values)
Kidhome & Teenhome (number of children and teenagers in the household)
Dt_Customer (date of enrollment in the program)
Recency (days since the last purchase)
Spending-related columns (amount spent on wines, fruits, etc.)
No duplicate values were found in the dataset.



•	Methodology: 

	1.	Data Preprocessing:
		Missing values handled.
		Feature scaling applied using StandardScaler.
		Categorical variables encoded.
  
	2.	Dimensionality Reduction:
		Principal Component Analysis (PCA) applied to reduce feature dimensions.
  
	3.	Clustering Model:
		K-Means Clustering implemented to segment customers into groups.
		Elbow method used to determine the optimal number of clusters
  
	4.	Visualization & Insights:
		Clusters visualized using scatter plots, histograms, and heatmaps.
		Business insights extracted for better customer understanding.



•	Tools & Libraries Used: 

	1.	Python Libraries:
	   NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn
	
	3.	Machine Learning Techniques:
	    K-Means Clustering, PCA
	
	5.	Data Processing:
	   Standardization, Encoding, Missing value treatment

