# Wine Quality Analysis 🍷

Welcome to the **Wine Quality Analysis** project! In this repository, we dive into the world of unsupervised learning to uncover patterns and clusters in wine quality data. Whether you're a data enthusiast, a wine lover, or a machine learning practitioner, there's something here for you! 🍇🍷

---

## 📌 Project Overview
This project applies **unsupervised learning techniques** to analyze and cluster wines based on their chemical and physical properties. Using the popular [Red Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009), we aim to:
- Identify hidden patterns in the data.
- Group wines with similar characteristics.
- Gain insights into the features that influence wine quality.

---

## 🛠️ Methodology
Our approach is divided into four key steps, each documented in a dedicated Jupyter notebook:
1. **Data Cleaning & Preprocessing**:
   - Handle missing values and outliers.
   - Scale and normalize features for optimal clustering performance.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize distributions and correlations.
   - Understand feature importance using ANOVA and t-tests.

3. **Unsupervised Learning**:
   - Apply clustering algorithms like **K-Means** and **DBSCAN**.
   - Optimize the number of clusters using **Elbow Method** and **Silhouette Score**.

4. **Dimensionality Reduction**:
   - Use **PCA** to reduce feature dimensions and visualize clusters in 2D.

---

## 💻 Repository Structure
```
wine-quality-analysis/
├── data/                   # Dataset files
├── notebooks/              # Jupyter notebooks for each stage
│   ├── 1_data_cleaning.ipynb
│   ├── 2_exploratory_analysis.ipynb
│   ├── 3_statistical_analysis.ipynb
│   ├── 4_supervised_learning.ipynb
│   ├── 5_unsupervised_learning.ipynb
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
```
---

## 🔬 Results
### Clustering Performance:
- **K-Means**: Optimal number of clusters = 2, **Silhouette Score** = 0.20
- **DBSCAN**: Best parameters (`eps=1.7`, `min_samples=8`), **Silhouette Score** = 0.35

### PCA Visualization:
Clusters are well-separated in 2D using the first two principal components, providing clear insights into the structure of the data.

---

## 🚀 Future Steps
1. Explore **supervised learning** approaches for predicting wine quality.
2. Develop an interactive **Streamlit** dashboard for data exploration.
3. Investigate other clustering algorithms like **Agglomerative Clustering**.

---

## 📚 References
This project was built using the following references and resources:

- [Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009) - UCI Machine Learning Repository.
- "Wine Quality: Machine Learning in Practice" by Cortez et al., 2009.

---

## 📬 Contact

If you have any questions, suggestions, or feedback about this project, feel free to reach out!

- **Author**: Miguel Ángel Chamizo Sánchez
- **Email**: [miguelchamizo10@gmail.com](mailto:miguelchamizo10@gmail.com)
- **LinkedIn**: [https://www.linkedin.com/in/miguelangelchamizosanchez](https://www.linkedin.com/in/miguelangelchamizosanchez)

Feel free to open an issue in this repository for any bugs or feature requests. Contributions are always welcome!

---

## 📦 Requirements
To set up the project environment, install the required dependencies:

```bash
pip install -r requirements.txt
