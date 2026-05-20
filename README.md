# 🚚 Supply Chain & Logistics Performance Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue) ![Scikit--learn](https://img.shields.io/badge/Scikit--learn-1.3-orange) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

## Overview
End-to-end supply chain analysis covering supplier on-time delivery performance, logistics cost optimisation, and supplier segmentation using K-Means clustering. Built from direct experience coordinating procurement, logistics, and warehousing across construction, FMCG, and manufacturing environments in KwaZulu-Natal.

## Business Questions Answered
- Which suppliers have the lowest on-time delivery rates?
- Which routes have the highest logistics cost as a % of order value?
- How can suppliers be segmented by reliability and cost profile?
- Where are the biggest opportunities to reduce supply chain costs?

## Tools & Libraries
| Tool | Purpose |
|------|---------|
| Python / Pandas | Data wrangling & aggregation |
| Matplotlib / Seaborn | Visualisation |
| Scikit-learn (KMeans) | Supplier clustering |
| NumPy | Numerical simulation |
| Jupyter Notebook | Interactive analysis |

## Key Outputs
- On-time delivery rate by supplier (bar chart — red = below threshold)
- Logistics cost % by route (bar chart)
- Supplier segmentation scatter plot (K-Means: 3 clusters)
- Summary findings and actionable recommendations

## How to Run
```bash
git clone https://github.com/aaronleebobby/supply-chain-optimization.git
cd supply-chain-optimization
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook supply_chain_analysis.ipynb
```

## Project Structure
```
supply-chain-optimization/
│
├── supply_chain_analysis.ipynb     # Main analysis notebook
├── otd_by_supplier.png             # Chart output
├── logistics_cost_by_route.png     # Chart output
├── supplier_clustering.png         # Chart output
└── README.md
```

## Author
**Aaron Lee Bobby**  
IBM Data Science Professional Certificate (May 2026)  
📧 aaron.bob@live.co.za | 📍 Durban, KwaZulu-Natal
