# Data Analysis: Laptop Market and Medical Insurance Costs

Two exploratory data analysis case studies in Python, built for a Data Analytics module of my BSc Computer Science with Artificial Intelligence at Nottingham Trent University. Each case study follows the same workflow: clean the data, explore it with statistics and charts, and explain what the results mean.

## Case study 1: Laptop market

Dataset of 205 laptop listings (193 after cleaning), covering brand, processor, graphics, storage, prices and ratings.

- Cleaning: removed a record with a missing name and 11 duplicates, and checked for impossible values
- Brand analysis: number of manufacturers and products per brand
- Price analysis: cheapest and most expensive laptops, spread of prices, average price per brand
- Brand vs rating, and how many laptops are discounted
- Relationships between storage, screen size and price

## Case study 2: Medical insurance costs

- Cleaning and checks on the insurance dataset
- Distribution of age groups and the spread of healthcare charges
- BMI grouped into categories, and which region has the most obese individuals
- How age, number of dependents, BMI, smoking status and region relate to medical charges

## Technologies

Python, pandas, NumPy, matplotlib, seaborn, Jupyter

## Data

The datasets (`laptops(in).csv` and `insurance(in).csv`) are not included. The notebook loads them from Kaggle input paths, so to run it elsewhere, change the two `read_csv` paths at the top.

## Run it

```bash
git clone https://github.com/linabelaa-eng/laptop-insurance-data-analysis.git
cd laptop-insurance-data-analysis
pip install numpy pandas matplotlib seaborn jupyter
jupyter notebook laptop-insurance-data-analysis.ipynb
```

## What I learned

- A repeatable data cleaning routine: missing values, duplicates and anomalies
- Choosing the right chart for each question (histograms, box and violin plots, scatter plots, grouped bars)
- Explaining findings clearly in plain English next to the code

## Author

Lina Belaa, Computer Science with AI student at Nottingham Trent University
