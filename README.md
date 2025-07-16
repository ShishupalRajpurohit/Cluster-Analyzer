
# 🌍 Cluster Analyzer: Unveiling Global Development Patterns

Welcome to **Cluster Analyzer**, a data science project focused on extracting meaningful patterns from international development indicators using clustering algorithms. This project demonstrates how unsupervised machine learning can uncover hidden structures in socio-economic data from countries across the globe.

## 🚀 Project Objective

The primary goal is to identify clusters of countries with similar economic and development characteristics. These insights can:

- Support data-driven policymaking.
- Enable businesses to segment markets.
- Reveal regional development disparities.
- Encourage targeted interventions in global issues.

## 📊 Dataset Overview

The dataset includes global indicators such as:

- **Economic**: GDP, business tax rate, lending rate, CO₂ emissions, energy use.
- **Development**: Birth rate, life expectancy (female), infant mortality.
- **Infrastructure**: Internet usage, ease of doing business, days/hours to start a business.
- **Healthcare**: Health expenditure (% GDP), per capita spend.

This multidimensional dataset enables robust, cross-domain clustering analysis.

## 🔍 Techniques Used

The notebook explores and compares several clustering techniques:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **DBSCAN (Density-Based Clustering)**

📌 **Comparative Analysis** is performed to evaluate which algorithm performs best based on visual separation, silhouette score, and data characteristics.

## 📈 Visualizations

Visual exploration includes:

- Cluster plots in 2D and 3D using PCA/t-SNE.
- Dendrograms for hierarchical clustering.
- Heatmaps and pairplots for correlation analysis.
- Interactive maps and feature sliders (if deployed via Streamlit).

## 🧠 Feature Importance

The project identifies the most influential variables in forming clusters, helping explain **why** certain countries are grouped together.

## 🧪 Deployment (Coming Soon)

A Streamlit-based web app is in development to allow:

- Uploading new data
- Real-time clustering and visualization
- Interactive exploration of country clusters

> 🔧 Deployment roadmap includes optional Flask integration for advanced backend logic.

## 🛠️ Installation

Clone the repo:

```bash
git clone https://github.com/ShishupalRajpurohit/Cluster-Analyzer.git
cd Cluster-Analyzer
```

Manually install essentials:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn plotly streamlit
```

Run the notebook:

```bash
jupyter notebook "Cluster Analysis.ipynb"
```

## 📚 Project Structure

```
Cluster-Analyzer/
├── Cluster Analysis.ipynb         # Main analysis notebook
├── requirements.txt               # Required libraries (optional)
├── README.md                      # Project documentation
└── (streamlit_app/)              # Coming soon: Interactive app
```

## ✅ Acceptance Criteria

- Explore and compare at least 3 clustering models
- Analyze global development trends across clusters
- Deploy a working Streamlit app (in progress)
- Provide visual insights and model transparency

## 🧠 Why This Project Matters

- Encourages **evidence-based decision making**
- Provides **actionable insights** for global development professionals
- Offers **interactive tools** for data exploration
- Demonstrates **real-world application** of unsupervised ML

## 🧑‍💻 Author

**Shishupal Rajpurohit**  
Biomedical Engineer | Data Science Enthusiast  
📫 [LinkedIn](https://www.linkedin.com/in/shishupal-rajpurohit-039290190/)

---

> “Clustering the world to understand it better — one country at a time.”
