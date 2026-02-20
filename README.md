# Project 1B: Liquidity Crisis Simulation Dashboard

## Overview
This project focuses on building a gamified simulation to understand and analyze liquidity risk during periods of market stress. The objective is to demonstrate how banks can face severe liquidity problems when multiple stress events occur at the same time, such as bank runs, margin calls, asset fire sales, and funding crises.

The project is designed as part of an online internship and uses interactive dashboards to provide real-time insights into liquidity risk management.

---

## Objectives
- To simulate liquidity stress scenarios in a simple and intuitive way  
- To understand the impact of bank runs, margin calls, fire sales, and funding crises  
- To analyze liquidity ratios and cash flow under stress conditions  
- To create an interactive and gamified learning experience  

---

## Dataset
- **Dataset Name:** Bank Marketing Dataset  
- **Source:** Kaggle  
- **File Used:** `bank-additional-full.csv`  

The dataset contains bank customer information. Since real liquidity and cash data is not publicly available, a realistic bank balance sheet is simulated using reasonable financial assumptions.

---

## Methodology
1. Loaded and explored bank customer data  
2. Simulated a simplified bank balance sheet (cash, deposits, assets, funding)  
3. Implemented four stress scenarios:
   - Bank Run  
   - Margin Call  
   - Asset Fire Sale  
   - Funding Crisis  
4. Calculated liquidity ratios such as Cash Ratio and Liquidity Coverage Ratio  
5. Built an interactive dashboard using sliders for real-time scenario analysis  
6. Generated stress test results and survival verdicts  

---

## Key Features
- Interactive sliders for stress scenarios  
- Real-time liquidity ratio updates  
- Cash flow projections during crisis stages  
- Stress test verdicts (Bank Survives / High Risk / Bank Fails)  
- Simple and explainable visualizations  

---

## Results and Insights
- Liquidity can deteriorate very quickly when multiple stress events occur together  
- High withdrawal rates and funding losses significantly reduce cash availability  
- Asset fire sales lead to large losses in asset value  
- Interactive simulations help clearly understand liquidity risk dynamics  

---

## Tools and Technologies Used
- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- ipywidgets  

---

## How to Run the Project
1. Download the dataset from Kaggle  
2. Upload `bank-additional-full.csv` into the Jupyter Notebook directory  
3. Run the notebook cells in order  
4. Use the interactive sliders to test different stress scenarios  

---

## Learning Outcomes
- Practical understanding of liquidity risk management  
- Experience with stress testing and scenario analysis  
- Hands-on exposure to interactive financial dashboards  
- Improved problem-solving and analytical skills  

---

## Acknowledgement
This project was completed as part of an online internship assignment. The work is intended purely for learning and assessment purposes and does not represent real banking operations.

---


