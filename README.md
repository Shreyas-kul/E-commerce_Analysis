E-Commerce Data Analysis and Machine Learning
This repository contains an end-to-end data science project focusing on eCommerce transactions. The project involves performing exploratory data analysis (EDA), building a lookalike model, and performing customer segmentation using clustering techniques. The aim of this analysis is to provide actionable insights to improve business strategy and customer targeting for an eCommerce platform.

Project Overview
The project is divided into three main tasks:

Task 1: Exploratory Data Analysis (EDA)
Objective: Perform EDA on the provided eCommerce datasets to understand customer behavior, product performance, and transaction patterns.
Tools Used: Pandas, Matplotlib, Seaborn
Key Findings:
Analyzed customer distribution by region.
Explored trends in customer signups over time.
Investigated product category distributions and price trends.
Identified key transactional insights, including sales trends, top customers, and product performance.
Task 2: Lookalike Model
Objective: Build a lookalike model to recommend similar customers based on their profile and transaction history.
Techniques: Cosine similarity, Feature engineering
Key Features:
Aggregate customer profiles (total purchases, preferred product categories, region).
Calculate similarity scores between customers and recommend the top 3 lookalikes for each.
Output: A CSV file (Lookalike.csv) containing customer recommendations.
Task 3: Customer Segmentation (Clustering)
Objective: Perform customer segmentation using clustering techniques to identify distinct customer groups.
Techniques: KMeans, DBSCAN, StandardScaler, Elbow Method
Key Steps:
Combined customer profile and transaction data.
Standardized data for clustering.
Performed clustering to categorize customers based on their purchase behavior.
Evaluation Metrics: Davies-Bouldin Index, Visualized clusters using 2D scatter plots.
Installation
To set up the environment for this project, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/Shreyas-kul/E-commerce_Analysis.git
Navigate to the project directory:

bash
Copy
Edit
cd E-commerce_Analysis
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python3 -m venv .venv
Activate the virtual environment:

On Mac/Linux:
bash
Copy
Edit
source .venv/bin/activate
On Windows:
bash
Copy
Edit
.venv\Scripts\activate
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Files in the Repository
Customers.csv: Contains customer information (CustomerID, CustomerName, Region, SignupDate).
Products.csv: Contains product details (ProductID, ProductName, Category, Price).
Transactions.csv: Contains transaction data (TransactionID, CustomerID, ProductID, Date, Quantity, TotalValue, Price).
EDA.ipynb: Jupyter notebook for exploratory data analysis and business insights.
Lookalike.ipynb: Jupyter notebook for building the lookalike model and generating recommendations.
Clustering.ipynb: Jupyter notebook for performing customer segmentation using clustering techniques.
Lookalike.csv: File containing customer lookalike recommendations and their similarity scores.
Clustering_Report.pdf: PDF report summarizing clustering results and insights.
Usage
Task 1 (EDA): Run the EDA.ipynb notebook to explore the data, analyze key business insights, and generate visualizations.
Task 2 (Lookalike Model): Run the Lookalike.ipynb notebook to build the lookalike model and generate customer recommendations based on similarity scores.
Task 3 (Customer Segmentation): Run the Clustering.ipynb notebook to perform customer segmentation and evaluate clustering results.
Results
Business Insights: Derived insights from EDA such as customer distribution, product performance, and sales trends.
Lookalike Model: Generated a list of similar customers for each customer based on profile and transactional data.
Clustering: Performed clustering to segment customers into distinct groups for targeted marketing strategies.
Dependencies
pandas
numpy
scikit-learn
matplotlib
seaborn
You can install all required dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
