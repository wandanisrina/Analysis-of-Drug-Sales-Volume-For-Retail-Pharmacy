# Analysis of Drug Sales Volume For Retail Pharmacy in 2019-2020

## Repository Outline
```
1. README.md - Explanation of the project overview
2. Dataset_Analysis_By_Wanda_Nisrina.ipynb - Notebook that contains data loading, data processing, visualization, and statistical analysis with python
3. pharma-data.csv - Raw data from Kaggle
4. filtered-data.csv - Filtered data for analysis
```

## Problem Background
```
The pharmaceutical sector is one of the  vital industries in the global healthcare system, with continus growing in response to the increasing demand for healthcare products. Amidst the competitiveness in the pharmaceutical sales, the healthcare sector must analyze sales trends before making whole-sales purchases from pharmaceutical distributors. The dataset "Pharmaceutical Company Wholesale-Retail Data" provides a comprehensive overview of the sales activities of drug products and transactions between distributors, buyers (in this case, the healthcare sector), pharmaceutical products, pricing, and sales periods.

This analysis plays a crucial role in supporting data-driven decision-making when selecting distributors for upcoming pharmaceutical purchases for next period. As prospective buyers from pharmaceutical distributors; hospitals and pharmacies need to consider reviewing the sales trends of pharmaceutical products from each distributor. By analyzing this sales data, stakeholders including pharmacy owners, sales and marketing team, the PPIC (Production Planning and Inventory Control) team are expected to gain insights that will help enhance business efficiency.
```

## Project Output
```
The output of this project is an interactive Tableau dashboard featuring five visualizations: "Sales Volume of Drug Class by Distributor," "Sales Volume Based on Drug Class," "Price of Drug Class by Distributor," "Return Product by Distributor," and "Drug Sales Trend Based on Months." Additionally, the dashboard includes a descriptive analysis section presenting "Analysis of Central Tendency of Drug Prices Based on Product Class" for descriptive statistics analysis, and "Analysis of the Correlation Between Product Class Prices and Sales Time (Month)" for inferential statistics analysis. This analysis can further support decision-making for products purchase planning for the upcoming inventory.
```

## Data

```
This analysis use data from pharma-data.csv. Furthermore, only some colomns are sorted for project analysis. 
1. Distributor  :   Name of Wholesaler. There are total 11 distributors after the data was filtered.
2. Customer Name:   Name of customer
3. City         :   Customer's city
4. Country      :   Customer's country. Only show German after the data was filtered.
5. Channel      :   Pharmacy. This column is filtered because want to see the sales of Pharmacy only
6. Sub-channel  :   Retail. This column is filtered because want to see the sales of Retail Pharmacy 
7. Product Name :   Name of Drug
8. Product Class:   Class of Drug. Total 6 classes that are being used for analysis which is 'Antibiotics', 'Analgesics', 'Antipiretics', 'Antimalarial', 'Antiseptics', and 'Mood Stabilisizers'
9. Quantity     :   Quantity purchased
10. Price       :   Price of product was sold for
11. Sales       :   Amount made from sale (Quantity * Price)
13. Month       :   Month sale was made
14. Year        :   Year sale was made
```

## Method
```

This analysis used statistics and visualization method to produce project outcome.
1. Statistic methods that being used are Descriptive and Inferential Statistics. Descriptive analysis method is used to describe the main features of a dataset such as central main tendency. Inferential analysis method is used to predict and see correlation of some parameters.
2. Visualization methods that being used are Tableau and Matplotlib. For Tableau will produce dashboard that shows charts from analysis.
```

## Stacks
```
Tools used for this analysis are `VS Code` and `Tableau`. Libraries from Python that being used are `pandas`, `numpy`, `scipy`, and `matlplotlib` for supporting tools in analysis

```

## Reference
```
- [Tableau Dashboard Visualization](https://public.tableau.com/app/profile/wanda.nisrina/viz/AnalysisofDrugSalesVolume/AnalysisofDrugSalesVolumeForRetailPharmacyin2019-2020?publish=yes) (**Must read**)
- [Project Repository](https://github.com/wandanisrina/Analysis-of-Drug-Sales-Volume-For-Retail-Pharmacy.git) (**Must read**)
- [Raw dataset link](https://www.kaggle.com/datasets/krishangupta33/pharmaceutical-company-wholesale-retail-data?resource=download)

```