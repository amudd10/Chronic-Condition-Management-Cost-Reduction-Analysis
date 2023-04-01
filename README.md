# Chronic Condition (Diabetes & Hypertension) Management Cost Reduction Analysis

**Healthcare Insurance Data Analysis**

This repository contains a data analysis project focusing on healthcare insurance data, specifically exploring average submitted charges and Medicare payment amounts for various providers and diagnosis-related groups (DRGs) related to diabetes and hypertension.

### Project Overview
The project aims to:

- Investigate the relationship between average submitted charges and Medicare payment amounts
- Identify top and bottom performers in terms of charges and payments
- Perform a geographical analysis of the data by state
- Conduct domain-specific analysis by exploring DRGs related to diabetes and hypertension

### Dataset
The dataset used in this project is the "Medicare Inpatient Hospitals - by Provider and Service" dataset, which contains information on hospital discharges from Original Medicare (fee-for-service) Part A (Hospital Insurance) beneficiaries by Inpatient Prospective Payment System (IPPS) hospitals, aggregated by provider and service.

The dataset includes the following columns:

- Rndrng_Prvdr_CCN
- Rndrng_Prvdr_Org_Name
- Rndrng_Prvdr_St
- Rndrng_Prvdr_City
- Rndrng_Prvdr_State_Abrvtn
- Rndrng_Prvdr_State_FIPS
- Rndrng_Prvdr_Zip5
- Rndrng_Prvdr_RUCA
- Rndrng_Prvdr_RUCA_Desc
- DRG_Cd
- DRG_Desc
- Tot_Dschrgs
- Avg_Submtd_Cvrd_Chrg
- Avg_Tot_Pymt_Amt
- Avg_Mdcr_Pymt_Amt

### Getting Started

#### Prerequisites
To run the Jupyter Notebook and Python scripts in this repository, you need to have the following packages installed:

- pandas
- numpy
- matplotlib
- seaborn
- geopandas
- scikit-learn (optional)

#### Installation
1. Clone the repo
git clone amudd10/Chronic-Condition-Management-Cost-Reduction-Analysis.git

2. Install the required packages (if not already installed)
pip install pandas numpy matplotlib seaborn geopandas 

#### Usage
Open the Jupyter Notebook file (diabetes-hypertension_cost-reduce.ipynbb) in the repository and follow the steps to perform the data analysis. You can also refer to the Python scripts provided for specific parts of the analysis.

### Results
The analysis provides insights into the relationship between average submitted charges and Medicare payment amounts, geographical variations in charges and payments, and domain-specific trends related to diabetes and hypertension. Visualizations, such as histograms, choropleth maps, and box plots, are included to help communicate the findings effectively.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### Acknowledgments
- Medicare Inpatient Hospitals - by Provider and Service dataset
- Geopandas documentation