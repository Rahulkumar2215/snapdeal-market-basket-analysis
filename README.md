# Market Basket Analysis with Python – Snapdeal

## Project overview

This project analyzes customer behavior using the Snapdeal dataset. The analysis covers purchasing behavior, customer satisfaction, customer segmentation, personalized recommendations, reviews, and transaction values.

The project was completed in Python using pandas, matplotlib, and scikit-learn.

## Project contents

- `Market_Basket_Analysis.ipynb` – complete analysis notebook
- `SnapDeal.csv` – dataset used for the analysis
- `report/Snapdeal_Market_Basket_Analysis_Simple_Report.pdf` – project summary report
- `visualizations/` – selected charts generated during the analysis
- `requirements.txt` – Python packages required to run the notebook

## Analysis covered

1. Data cleaning and preparation
2. Descriptive customer behavior analysis
3. Customer segmentation using purchase frequency and shopping satisfaction
4. K-Means behavioral clustering
5. Recommendation and review analysis
6. Transaction-value analysis
7. Visualizations and summary findings

## Key findings

- The cleaned dataset contains **800 records** with no missing values or duplicate rows.
- **Clothing and Fashion** was the most selected purchase category, with **476 selections**.
- Shopping Satisfaction averaged **2.99**, Personalized Recommendation Rating **2.91**, and Rating Accuracy **2.96**.
- Customers were grouped into six behavior-based segments using purchase frequency and satisfaction.
- K-Means clustering was tested across different values of *k*; **8 clusters** produced the highest tested silhouette score of **0.244**. The project report notes that the clusters have considerable overlap and should therefore be viewed as broad behavioral patterns.
- Customers reporting that recommendations were not helpful had average shopping satisfaction of **2.89**, compared with **3.08** for customers selecting “sometimes” and **3.02** for “yes”.
- The average transaction value was approximately **547,442**, with a median of approximately **541,613**.
- Customers with a satisfaction rating of 5 had an average transaction value of approximately **584,307**, compared with approximately **518,181** for satisfaction rating 3.

These findings describe associations in this dataset and should not be interpreted as proof of causation.

## How to run

1. Install Python 3.
2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook Market_Basket_Analysis.ipynb
```

4. Keep `SnapDeal.csv` in the same folder as the notebook.

## Video

Project presentation:

https://drive.google.com/file/d/1QIsPNAIT3fdYNkY1Sbzcnv_XWXjoLIao/view?usp=sharing
