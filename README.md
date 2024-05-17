# Time series analysis of Covid 19 date wise dataset  

[Here is the dataset](https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-india?select=covid_19_india.csv)  

## Models Used:
- Arima
- Sarima
- Prophet

First we made the data stationary and then used SARIMA, ARIMA and Prophet models to determine `Cured`, `Deaths`, `Confirmed` cases for the next 30 days
And used **matplotlib** to visualisation of the data  
Also calculated Mean, SE Mean, Standard Deviation, Minimum, Maximum, Skewness and Kurtosis



This is an implementation of this research paper
[Wang Y, Yan Z, Wang D, Yang M, Li Z, Gong X, Wu D, Zhai L, Zhang W, Wang Y. Prediction and analysis of COVID-19 daily new cases and cumulative cases: times series forecasting and machine learning models. BMC Infect Dis. 2022 May 25;22(1):495. doi: 10.1186/s12879-022-07472-6. PMID: 35614387; PMCID: PMC9131989.](https://pubmed.ncbi.nlm.nih.gov/35614387/)
