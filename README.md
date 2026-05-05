# 🛒 E-Commerce Product Analysis

> Why do customers disappear — and what can we do about it?  
> A product analytics case study on 96,000+ real orders from Olist Brazilian E-Commerce.

---

## 🎯 Business Problem

Most e-commerce teams track revenue. Fewer ask: **are we building a loyal customer base, or just running a one-time purchase machine?**

This analysis digs into order flow, cohort retention, and customer segmentation to answer exactly that — and turns findings into concrete product recommendations.

---

## 🔍 Methodology

| Step | Analysis | Question |
|------|----------|----------|
| 1 | **Funnel Analysis** | Where do we lose customers in the order flow? |
| 2 | **Retention Analysis** | Do customers come back after their first purchase? |
| 3 | **RFM Segmentation** | Who are our best customers — and who's about to churn? |

---

## 📊 Key Findings

- **96,478 delivered orders** out of 99,441 total — ~3% drop-off before delivery, mostly cancellations and unavailable items
- **Retention rate: ~3%** — 10x below the e-commerce industry benchmark of 25–30%
- **Review scores stable at 4.0–4.3/5** across all cohorts — customers aren't leaving because they're angry. They're leaving because no one gave them a reason to stay *(passive churn)*
- **Champions buy 4x more frequently** and spend 11x more than Lost customers (avg. $708 vs $61)
- **~25% of customers are already Lost** (last purchase 377+ days ago), but ~50% are At Risk — still recoverable

---

## 💡 Recommendations

**1. Re-engagement campaign for "At Risk" segment**  
They bought recently enough to remember the brand. A personalised discount or reminder email could recover a significant chunk of revenue.

**2. Build a post-purchase email flow**  
Satisfaction is high — the issue is visibility, not experience. A "you might also like" email 2 weeks after delivery could shift customers from one-time to repeat buyers.

**3. Investigate the delivery drop-off**  
Cancelled and unavailable orders represent real lost revenue. Root cause analysis on which categories or sellers cause this could reduce early churn.

---

## 🗂️ Project Structure

```
ecommerce-product-analysis/
│
├── data/                              # Raw CSV files (not tracked in git)
├── notebooks/
│   ├── 00_eda_and_cleaning.ipynb      # Data exploration & cleaning
│   ├── 01_funnel_analysis.ipynb       # Order conversion funnel
│   ├── 02_retention_analysis.ipynb    # Cohort retention heatmap
│   └── 03_rfm_segmentation.ipynb      # RFM customer segmentation
└── README.md
```

---

## 🛠️ Stack

Python · pandas · plotly · seaborn · matplotlib · Jupyter Notebook

---

## 🚀 How to Run

```bash
git clone https://github.com/KQnok/ecommerce-product-analysis
cd ecommerce-product-analysis
pip install pandas matplotlib seaborn plotly jupyter

# Download dataset → https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
# Place CSV files in /data folder

jupyter notebook
```

---

## 👩‍💻 Author

**Karina Kuralionak** — Aspiring Product Analyst  
<<<<<<< Updated upstream
[GitHub](https://github.com/KQnok) · [LinkedIn](https://linkedin.com/in/karina-kuralionak)
=======
[GitHub](https://github.com/KQnok) · [LinkedIn](https://linkedin.com/in/karina-kuralionak)
>>>>>>> Stashed changes
