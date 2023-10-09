## Melanoma Detection Assignment

 Table of Contents
* General Info
* Dataset
* Technologies Used
* Conclusion
* Acknowledgements


## General Info
Build a CNN based model which can accurately detect melanoma. 
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential 
to reduce a lot of manual effort needed in diagnosis.

## Dataset
Google Drive link to the data: https://drive.google.com/drive/folders/1KAIRrQdnN-EafIl7oOptvdVoUB2Cw2RH

The dataset consists of 2357 images of malignant and benign oncological diseases, 
which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, 
and all subsets were divided into the same number of images, with the exception of melanomas and moles, 
whose images are slightly dominant. The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Conclusions

- When CNN was created without Dropout, Augmentor and Class rebalance, we could observe model was clearly Overfitting

- Augmentation and Class rebalance has helped us to get rid of Overfitting and Underfitting and we could Training accuracy of ~99 % and Validation Accuracy more than 75%



## Technologies Used
Python
Libraries numpy, pandas, matplotlib.pyplot, tensorflow, keras

## Acknowledgements
- This project was inspired by Upgrad Assignment and solved using Learnings from Upgrad course


