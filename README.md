# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* Problem Statement and Analysis approach
* Overfitting and ways to solve it
* Augmentation to solve class imbalance
* Final results


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
- Clearly the model is overfitting as, we see training loss and accuracy has being increasing with epocs of trainings , reaching a accuracy of around 88% but validation accuracy is up and down and never crosses 38% . This means model does not perform well on unseen validation data and we need to handle same. 
- see this link - https://towardsdatascience.com/simple-image-data-augmentation-technics-to-mitigate-overfitting-in-computer-vision-2a6966f51af4
- Data augmentation methods are one of the ways to mitigate Overfitting.
- Tried rotation , flip , contrast change, zoom etc, but still validation accuracy is poor and also it brings down training accuracy.

## Augmentation to solve class imbalance

> Rectify class imbalances present in the training dataset with Augmentor library- https://augmentor.readthedocs.io/en/master/


## Final results
- After class imbalance handling through Augmentor , which augments few more samples each class , and creates a revised data set with equal nunmber of images for each class. for eg. 500 entries per class. after this when we train using CNN , we get better training auccracy - around 97% training accuracy and 80% validation accuracy. 


## Contact
Created by [@abidahmeds] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
