# Project9
This project analyzes the information of 360000 clients about their visits and buys in a web site.

**Objective:** To make the Return On Marketing Investment (ROMI) analysis to determine how much revenue a marketing campaign is generating compared to the cost of running that campaign.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, the Lifetime Value (LTV) and the Client Acquisition Cost (CAC) analysis are made.

The Lifetime Value to Cost of Acquisition (LTV/CAC) Ratio tells if the theoretical lifetime revenue you get from a customer is higher or lower than the sales and marketing costs needed to acquire that customer.

Finally, some conclusions are given.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy.

The Jupyter Notebook is in scripts/project9.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project9.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project9.ipynb.