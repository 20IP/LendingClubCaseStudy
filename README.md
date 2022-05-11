# Lending Club Case Study
> Research and apply techniques learned in EDA to analyze risks in banking and financial services and understand how data is used to minimize the risk of losing money when lending to customers.


## Table of Contents
1. [General Info](#general-information)
2. [Technologies Used](#technologies-used)
3. [Approach Method](#approach-method)
4. [Conclusions](#conclusions)
5. [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The application of financial analysis technology in lending activities is a growing trend in the financial sector - lending institutions in the world. To support and help customers access capital in the maximum way. However, there are always lending risks, these risks come from many different reasons, from customers or regulations of the lending institution. To limit that, we will analyze what factors cause losses for lending institutions.
- This project uses typical EDA techniques to analyze the lending sector, to understand how consumer attributes and loan attributes influence the tendency of default. Analysis results can be applied to make recommendations to limit risks for lending institutions

- Based on information about customers whose loan results are "Good loan" or "Bad loan"  in loan status,  the provided dataset. Then we analyze what factors affect the above results, whether it is due to location, occupation, purpose of borrowing, loan interest rate or a combination of many attributes that affect "Good loan" and "Bad loan" results  of cutomer.
- We have a dataset (provided by Upgrade downloaded and included in this repo). It contains the entire loan data for all loans issued between 2007 and 2011.

## Technologies Used
* In this project we use some of the following libraries, you can install it according to the version noted in the requirement.txt file.
> Pandas version 	 1.4.2
Numpy version 	 1.22.3
Ploly version 	 5.6.0
Matplotlib version 	 3.5.1
Seaborn version 	 0.11.2

## Approach method
- Our approach is as follows:
>1. Load data and get an overview of its size
>2. Which specialty is the data about: lending
>3. Check how many columns are in lending data and size of the lending data
>4. Apply filters on Current Loan type
>5. Handle blank, missing, (NaN value), inappropriate data (% in percentage value), drop column if all columns are blank and drop columns if they contains 1 unique value
>6. Handle daytime data type if available
>7. Find the main objective of data analysis (in this case: risk analysis in banking and financial services and risk reduction)
>8. Find attributes that have a great influence on the primary target.
>9. Analysis of the obtained properties
>10. Observation & Conclusions during analysis

## Conclusions
- Debt Consolidation Purpose Tops across all default loans
- Small Business / Renewable energy / Educational / Other / Moving Purpose are top defaults loans
- On an average risky loans are charged 2 % higher interest rates
- 42 % Default loan are from 60 months term compared to all default loans
- Grade A is most reliable group
- Grade F & G are more riskier group
- Close to 3% increase in loan default with applicant experience more than 9
- Mortgage Home Ownership loan are least riskier than all others home ownership loans
- Risk Order for home Ownership is Mortgage < OWN < Rent < Others

## Acknowledgements
- This project was inspired by our group exercise on loan market analysis.
- References on [this tutorial](https://www.kaggle.com/datasets/urstrulyvikas/lending-club-loan-data-analysis).


## Contact

Created by : </br>Mr.Sanjay  Singh: singh.iitr2004@gmail.com </br>[And]</br>Pham Van Thai: phamthai.ats@gmail.com</br>Feel free to contact us!
- We do not have any constraints about License on the use of our results. You can use it for free.
