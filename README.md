# Customer Segmentation on Online Retail Data

## 📌 Project Overview
This project focuses on **customer segmentation** using an online retail dataset. The goal is to analyze customer purchasing behavior, clean and preprocess the data, and segment customers into meaningful groups for better business insights. By understanding customer patterns, businesses can improve marketing strategies, increase customer retention, and personalize offers and recommendations.

---

## 📂 Dataset
- Records: Transactions of a UK-based online retail store (01/12/2010 – 09/12/2011).  
- Key Features:  
  - InvoiceNo – Invoice number  
  - StockCode – Product code  
  - Description – Product description  
  - Quantity – Quantity of product purchased  
  - InvoiceDate – Date of purchase  
  - UnitPrice – Price per unit  
  - CustomerID – Unique ID for customers  
  - Country – Customer’s location  

---

## 🛠️ Steps in Analysis
1. Data Loading & Inspection – Imported dataset from Excel, checked column distributions and unique values.  
2. Data Cleaning – Restricted dataset to UK customers (90% of total), removed missing CustomerID, filtered out negative values.  
3. Exploratory Data Analysis (EDA) – Analyzed customer distribution by country, checked purchasing frequency and order amounts.  
4. Customer Segmentation – Performed RFM Analysis (Recency, Frequency, Monetary), clustered customers into segments (e.g., loyal, at-risk, new).  
5. Insights – Identified high-value customers, suggested strategies for different customer segments.  

---

## 📊 Tools & Libraries
- Python  
- Pandas – Data manipulation  
- NumPy – Numerical operations  
- Matplotlib / Seaborn – Visualization  
- Scikit-learn – Clustering and segmentation  

---

## 🚀 How to Run
1. Clone the repository:  
   git clone https://github.com/yourusername/Customer_Segmentation_Online_Retail.git  

2. Install dependencies:  
   pip install -r requirements.txt  

3. Open Jupyter Notebook:  
   jupyter notebook Customer_Segmentation_Online_Retail.ipynb  

4. Run the cells step by step.  

---

## 📈 Results
- Segmented customers into distinct groups based on purchasing behavior.  
- Derived insights to improve targeted marketing and customer retention strategies.  

---

## 📌 Future Work
- Implement predictive modeling to forecast customer churn.  
- Use advanced clustering (DBSCAN, hierarchical).  
- Deploy the segmentation model as a dashboard using Streamlit.  

---

## 🤝 Contributing
Pull requests and suggestions are welcome!  

---

## 📧 Contact
For questions or collaborations:  
**Saurabh Saini** – saurabh.saini0904@gmail.com  
