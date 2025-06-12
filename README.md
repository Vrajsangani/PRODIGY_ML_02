# PRODIGY_ML_02
🛍️ Mall Customer Segmentation
This project performs customer segmentation using clustering algorithms on the Mall Customers dataset. It is a common unsupervised machine learning task that helps businesses understand customer behavior and tailor their marketing strategies accordingly.

📌 Project Objective
Segment mall customers based on their:

Age

Annual Income

Spending Score

...to identify different customer groups and create targeted marketing strategies.

📂 Files
mall_customer.ipynb: Jupyter Notebook with data preprocessing, visualization, and clustering (e.g., K-Means).

Mall_Customers.csv: Dataset containing customer data (not uploaded here, but required to run the notebook).

🔍 Technologies Used
Python 3

Jupyter Notebook

Pandas, NumPy – for data manipulation

Matplotlib, Seaborn – for data visualization

Scikit-learn – for K-Means clustering

📈 Methodology
Load Dataset
Using Pandas to read customer data.

Exploratory Data Analysis (EDA)
Visualizations using Seaborn and Matplotlib to understand data distribution.

Feature Selection
Selecting relevant features like Annual Income and Spending Score.

Clustering (K-Means)

Used Elbow method to find optimal number of clusters.

Applied K-Means algorithm to group customers.

Visualized customer segments in 2D space.

📊 Results
The clustering results helped identify key customer segments like:

High Income, High Spend

Low Income, Low Spend

Average Income, High Spend, etc.

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/VrajSangani/mall-customer-segmentation.git
cd mall-customer-segmentation
Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Open the notebook:

bash
Copy
Edit
jupyter notebook mall_customer.ipynb
✅ Requirements
Python 3.7+

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

📌 Future Improvements
Add other clustering techniques (e.g., DBSCAN, Hierarchical).

Deploy as a web app using Streamlit or Flask.

Perform demographic-based targeting.

📄 License
This project is licensed under the MIT License.
