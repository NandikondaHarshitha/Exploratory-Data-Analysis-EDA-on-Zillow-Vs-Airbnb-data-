# Exploratory-Data-Analysis-EDA-on-Zillow-Vs-Airbnb-data
** AIRBNB and ZILLOW Capital One Data Challenge

Harshitha Reddy Nandikonda

07/09/2022

* Files included in the submission
* Airbnb_Zillow_Data_Challenge.ipynb
* Airbnb_Zillow_Data_Challenge.html
* Read-Me.html
* visual plots folder

* Follow the below steps before executing the code
* Install Anaconda Prompt/ Jupyter Notebook
* Make sure to install the packages numpy, pandas, pylab, plotly_express, pandas_profiling, scipy.stats, geopy, plotly, re, matplotlib, seaborn
* Make sure to install nbextensions to view table of contents in the ipynb file.
* Do change the directory of the data sets in the "cell no. 2".

* Additional Notes - What I learnt from the data challenge
* Reference - Investopedia

* ROI: Return on investment (ROI) is a financial metric that is widely used to measure the probability of gaining a return from an investment. It is a ratio that compares the gain or loss from an investment relative to its cost. It is as useful in evaluating the potential return from a stand-alone investment as it is in comparing returns from several investments.

*** ROI= Cost of Investment/Net Return on Investment ×100%

* Profitability Index: The profitability index (PI), alternatively referred to as value investment ratio (VIR) or profit investment ratio (PIR), describes an index that represents the relationship between the costs and benefits of a proposed project.

* The profitability index (PI) is a measure of a project's or investment's attractiveness.
* A PI greater than 1.0 is deemed as a good investment, with higher values corresponding to more attractive projects.
*  PI = Present Value of Cash Flows/ Initial Investment

* * Normality for analysis: Normality is an important step for deciding the measures of central tendency and statistical methods for data analysis.

* In a normal distribution the mean is zero and the standard deviation is 1. It has zero skew and a kurtosis of 3.
Treating Outliers: Three standard deviations from the mean is a common cut-off in practice for identifying outliers in a Gaussian or Gaussian-like distribution.

* For smaller samples, 2 standard deviations (95%) can be used and for larger samples 4 standard deviations (99.9%) is used.
* What I've performed and how it works
* Initially I've read all the csv files, combined all the airbnb listings into one. Performed Data exploration including data cleaning, Imputing missing values, removing outliers and dropped unwanted columns. I've repeated the same steps for zillow dataset as well. Both the inputs are merged into one and used to derive conclusions. I've calculated derived metrics 'annual_income', 'Invest_Rec', 'ten_year_PI' based on my study. Performed visual data analysis to find out the best type of room to invest, few best zipcodes and areas to invest in based on 10 year profitability index and return of investment.
