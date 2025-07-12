# UK Housing Forecast & Clustering Analysis (2011–2030)

Analysis of UK Census data to uncover housing and socio-economic patterns using data cleaning, PCA, t-SNE, and Bayesian Ridge forecasting. Visualized with Tableau to explore historical trends and predict 2030 outcomes.



## 📁 Project Contents

•⁠  ⁠⁠ Python_Script.ipynb ⁠ — Jupyter notebook with full preprocessing, modeling, and projection workflow
•⁠  ⁠⁠ data/ ⁠ — Cleaned and merged datasets (2011, 2021, and forecasted 2030)
•⁠  ⁠⁠ dashboard.twbx ⁠ (optional) — Tableau workbook for visual analysis
•⁠  ⁠⁠ README.md ⁠ — Project overview and usage guide

## 🧠 Techniques Used

•⁠  ⁠*Bayesian Ridge Regression* — For forecasting 2030 housing data
•⁠  ⁠*Principal Component Analysis (PCA)* — To reduce dimensionality
•⁠  ⁠*t-SNE (t-Distributed Stochastic Neighbor Embedding)* — For visualizing complex patterns
•⁠  ⁠*Bayesian Gaussian Mixture Models (BGMM)* — To identify clusters of local authorities
•⁠  ⁠*Trustworthiness Metric* — To evaluate t-SNE output quality

## 📊 Dashboard Capabilities

•⁠  ⁠Time-based comparison of housing metrics: *2011 → 2021 → 2030*
•⁠  ⁠Clustering of local authorities by housing characteristics
•⁠  ⁠Visualizations of deprivation and housing inequality
•⁠  ⁠Interactive Tableau views for region, tenure type, and occupancy

## ⚙️ Technologies

•⁠  ⁠*Python*: pandas, NumPy, seaborn, scikit-learn
•⁠  ⁠*Machine Learning*: BayesianRidge, PCA, t-SNE, BGMM
•⁠  ⁠*Visualization*: Tableau (for final dashboard)
•⁠  ⁠*Notebook*: Jupyter for reproducibility

## ▶️ How to Run

1.⁠ ⁠Clone this repository:

git clone 

2 . Install required Python libraries:

pip install -r requirements.txt

3. Run the notebook:
   
jupyter notebook Python_Script.ipynb
Open dashboard.twbx in Tableau Desktop (2021.4 or later)

🧩 Data Sources
UK Census 2011 & 2021 datasets (ONS):

Tenure Type

Occupancy Ratings (Bedrooms and Rooms)

Heating Type

Deprivation Indices
