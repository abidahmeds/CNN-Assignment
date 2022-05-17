# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* Problem Statement and Analysis approach
* Overfitting and ways to solve it
* Augmentation to solve class imbalance
* Final results
* Referenecs


## Problem Statement and Analysis Approach
> Data Reading/Data Understanding → Defining the path for train and test images 
- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, resize your images to 180*180.
- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
> Model Building & training : 
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Analyse findings after the model fit. Check if there is any evidence of model overfit or underfit.
Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
> Model Building & training on the augmented data :
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~20 epochs
- Write your findings after the model fit, see if the earlier issue is resolved or not?
- Class distribution: Examine the current class distribution in the training dataset 
- Which class has the least number of samples?
- Which classes dominate the data in terms of the proportionate number of samples?
- Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
> Model Building & training on the rectified class imbalance data :
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
- Train the model for ~30 epochs
- Write your findings after the model fit, see if the issues are resolved or not?


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
