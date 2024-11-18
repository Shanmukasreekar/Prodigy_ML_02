Customer Segmentation Using K-Means Clustering
Project Description
This project applies K-Means clustering on customer data to perform segmentation based on annual income. The objective is to determine the optimal number of clusters using inertia scores and visualize the results.

Requirements
Python 3.8 or above
Libraries:
pandas
scikit-learn
plotly
Install dependencies using:

Copy code
pip install pandas scikit-learn plotly
Dataset
The dataset used is Mall_Customers.csv, containing the following columns:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
Ensure the dataset is in the correct path:

bash
Copy code
/kaggle/input/customer-segmentation-tutorial-in-python/Mall_Customers.csv
Code Description
Load the dataset using pandas.
Preprocess the data by selecting the Annual Income (k$) column.
Use the KMeans algorithm to calculate inertia scores for cluster counts ranging from 1 to 10.
Visualize the inertia scores using a line plot created with Plotly.
Output
The script generates an interactive plot displaying the inertia scores vs. the number of clusters. This helps identify the optimal number of clusters using the "elbow method."

How to Run
Place the dataset in the specified directory.
Run the Python script in an IDE or a Jupyter Notebook.
View the interactive plot to determine the optimal cluster count.
