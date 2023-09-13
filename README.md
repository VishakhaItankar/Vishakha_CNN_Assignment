# Project Name
> Melanoma Detection Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Problem Statement:

Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sortedaccording to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

<li> Actinic keratosis
<li> Basal cell carcinoma
<li> Dermatofibroma
<li> Melanoma
<li> Nevus
<li> Pigmented benign keratosis
<li> Seborrheic keratosis
<li> Squamous cell carcinoma
<li> Vascular lesion 


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

  
<li> Firstly we have tackled overfitting issue using data augmentation and dropout
<li> We then tried to improve the accuracy using batch normalization
<li> Class rebalance also helped to get the model at par and tackled the problem of data sparcity
<li> All this techniques and tweaks has proven helpful in improvising the model
<li> Finally model has scored a good accuracy on training and validation data 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - tensorflow
- library - numpy
- library - seaborn
- library - matplotlib.pyplot
- library - pandas
- library - os
- library - PIL 
- library - glob 
- library - Augmentor  

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@VishakhaItankar] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->