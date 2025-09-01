# Loan-Default-Prediction
## Problem Statement
Given customer and loan-related features, predict whether a customer will default on their loan.

## Dataset Information
The dataset contains customer-related information such as:
- Demographic details
- Loan details
- Employment history
- Credit behavior


**Dataset:** [`Loan_Default.csv`](https://drive.google.com/file/d/1T0fYXXkviYYrut20qu1Djs141RhLPjIB/view?usp=sharing)

You can directly load the dataset using this code:
```python
import pandas as pd
file_id = '1ibeEvuGTnWyMx6grwa6pe2P2Q1O2gJAU'
download_url = f'https://drive.google.com/uc?export=download&id={file_id}'

df = pd.read_csv(download_url)
