# Web Log Analysis with PySpark: Big Data Processing & Visualization

## 📌 Overview
This project demonstrates how to process and analyze large-scale **web server log data** using **Apache Spark (PySpark)**. It covers the complete workflow from raw log ingestion to structured transformations, Spark SQL queries, and visualizations. The project highlights how distributed data processing can uncover insights such as request distributions, error trends, and traffic behavior in a scalable way.

---

## 🚀 Features
- Parse raw web server logs into structured **RDDs & DataFrames**
- Perform **ETL (Extract, Transform, Load)** operations for data cleaning
- Use **Spark SQL** to analyze request methods, URLs, and error patterns
- Aggregate and classify logs into categories (documents, images, etc.)
- Convert Spark DataFrames to **Pandas** for visualization
- Scalable workflow suitable for large datasets

---

## 🛠️ Tech Stack
- **Apache Spark (PySpark)**
- **Python**
- **Pandas** (for visualization)
- **Google Colab / Jupyter Notebook**

---

## 📂 Project Structure
```
├── weblogs.ipynb   # Main notebook with PySpark log analysis
├── data/            # (Optional) Folder for log files
└── README.md        # Project documentation
```

---

## ⚡ Installation & Setup
1. Clone the repository:
   ```bash
   git clone  https://github.com/sarfarazsher/Web-Log-Analysis-with-PySpark
   cd your repository 
   ```

2. Install dependencies:
   ```bash
   pip install pyspark pandas
   ```

3. Run the notebook in **Jupyter** or **Google Colab**.

---

## 📊 Example Insights
- Count of requests per HTTP method (GET, POST, etc.)
- URL hit distributions and traffic trends
- Error requests (404s, failed requests) analysis
- Document vs. image vs. other resource requests

---

## 🎯 Learning Outcomes
- Hands-on experience with **PySpark DataFrames & SQL**
- Building a **scalable log analytics pipeline**
- Visualizing big data results for better interpretation

---

## 👨‍💻 Author
- Mohammad Sarfaraz Gundluru
