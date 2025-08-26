# 🛒 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment customers based on their purchasing behavior. Customer segmentation is an essential step for businesses to identify different customer groups, target them effectively, and improve marketing strategies.

## 🚀 Project Overview

- Implemented **K-Means Clustering** algorithm for customer segmentation.
- Used features like **Annual Income** and **Spending Score** to group customers.
- Visualized the clusters to gain business insights.
- Helps businesses design **personalized marketing strategies**.

## 📂 Dataset

- Dataset used: **Mall Customers Dataset** (commonly available on Kaggle).
- Contains customer information such as:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **Libraries Used:**
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## 📊 Steps Performed

1. **Data Preprocessing**
   - Loaded and cleaned dataset.
   - Selected relevant features for clustering.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of income, spending score, and age.
   - Relationship between different features.

3. **Clustering using K-Means**
   - Applied **Elbow Method** to find optimal number of clusters.
   - Implemented K-Means with chosen `k`.

4. **Visualization**
   - Plotted customer clusters in **2D space** using annual income & spending score.
   - Highlighted distinct customer groups.

## 📈 Results

- Customers segmented into **5 clusters** (e.g., low income–low spenders, high income–high spenders, etc.).
- Businesses can target high-value customers more effectively.

## 📷 Sample Output

![Clustering Visualization](https://miro.medium.com/v2/resize:fit:720/format:webp/1*VyRk3t73Cx0d6VHJx0C3wA.png)

## ▶️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/Customer-Segmentation-KMeans.git
   cd Customer-Segmentation-KMeans
   ```

2. Install required libraries  
   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebook  
   ```bash
   jupyter notebook Customer_Segmentation_KMeans.ipynb
   ```

4. Run all cells to reproduce results.

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

## 📜 License

This project is licensed under the **MIT License**.
