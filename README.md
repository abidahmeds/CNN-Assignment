# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* Problem Statement and Analysis approach
* Overfitting and ways to solve it
* Augmentation to solve class imbalance
* Final results
* Referenecs


## Problem Statement and Analysis Approach
> To Analyze the Lending club data set with all the information on loan given last few years and understand how some variable impacts or not towards loan success to have a loan decision made for new loans . It is important to understand the parameters which should be considered in taking loan approval decision and if some actions can be taken to secure loan customer.
### Analysis approach
- Understand credit funding parameters and factors affecting same through public knowledge and apply same on data set.
- Use EDA principles to analyse the data set 
- Clean , remove, rename and derive parameters ( columns )
- Use Data visualization methods to understand univariate and Bi variate patterns 
- Describe inferences for parameters impacting credit funding decision.


## Overfitting and ways to solve it
- 5 C of Credit – Character , Capacity, Collateral , Capital , Conditions 
- Credit score factors : Payment history-35% , Amounts owned -30%  , Credit history length (15%) , Credit mix(10%), New credits opened (10%).

## Augmentation to solve class imbalance

> The following factors were considered for Analysis and also some derivative metrices were used to arrive at the analysis.
![Lending Decision Factors](https://github.com/abidahmeds/LendingClubCaseStudy/blob/master/charts/factors1.png)
![Lending Decision Factors2](https://github.com/abidahmeds/LendingClubCaseStudy/blob/master/charts/factors2.png)

### Business Driven Derived Metrices and other varaibles.
> For the purpose of Credit risk analysis , Credit Score or FICO score is to be calculated and also some other varaibles were derived out of given data columns.
- Since there is no Credit score given in Dataset , it would probably be a biz driven derived metric. 
> This is how Credit Score was calculated  there could be more parameters used but this is 1st version based on information gathered.
![Credit Score Calculation formula](https://github.com/abidahmeds/LendingClubCaseStudy/blob/master/charts/CreditScoreCalculationFormula.png)

## Final results
- Credit Score and Credit utilization Ration have an important role and decision making factor to grant loans

## References
-  https://www.myfico.com/credit-education/whats-in-your-credit-score
-  https://www.cnbc.com/select/this-is-the-most-important-factor-that-determines-your-credit-score/ 

## Contact
Created by [@abidahmeds] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
