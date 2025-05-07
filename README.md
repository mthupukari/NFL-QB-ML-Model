# 🏈 NFL Quarterback Performance Analysis with Machine Learning

This project investigates the performance of NFL quarterbacks using machine learning techniques. By leveraging historical NFL stats and clustering algorithms, the notebook identifies patterns, evaluates quarterback performance, and groups QBs into meaningful tiers based on their statistical profiles.

## 📊 Project Overview

**Goal:**  
To explore and cluster NFL quarterbacks using advanced analytics and machine learning to uncover performance trends and similarities.

**Approach:**
- Collected and cleaned NFL quarterback performance data.
- Performed exploratory data analysis (EDA) on key metrics.
- Standardized features for clustering analysis.
- Applied **KMeans Clustering** to group quarterbacks into performance tiers.
- Visualized clusters and interpreted model insights.

## 📁 Project Structure

```
NFL-QB-ML-Model/
├── Investigation_of_NFL_Quarterbacks.ipynb  # Main notebook with EDA and ML modeling
├── README.md                                # Project overview and setup instructions
└── data/                                    # (Optional) Directory to store dataset files
```

## 🧠 Techniques Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (StandardScaler, KMeans)
- Data Cleaning and Preprocessing
- Clustering (Unsupervised Learning)
- Visualization and Interpretation of Clusters

## 📈 Key Insights
- Clustering revealed distinct tiers of quarterback performance based on passing and rushing statistics.
- Visualizations helped identify standout QBs and outliers in the data.
- KMeans model provided a framework to group players with similar profiles, aiding scouting or historical comparisons.

## 🔧 Requirements

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Make sure you are using **Python 3.7+**.

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/mthupukari/NFL-QB-ML-Model.git
   cd NFL-QB-ML-Model
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Investigation_of_NFL_Quarterbacks.ipynb
   ```

3. Run the notebook cells sequentially to explore the analysis and clustering.

## 📌 Future Work
- Integrate additional features like win/loss records, salary, or playoff performance.
- Try other clustering algorithms like DBSCAN or hierarchical clustering.
- Build a prediction model for QB performance using regression.

## 🧑‍💻 Author

**Mahit Thupukari**  
[GitHub](https://github.com/mthupukari)
