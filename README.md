# Melanoma Detection Assignment
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

 - Actinic keratosis
 - Basal cell carcinoma
 - Dermatofibroma
 - Melanoma
 - Nevus
 - Pigmented benign keratosis
 - Seborrheic keratosis
 - Squamous cell carcinoma
 - Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Implement Regularization: Techniques like dropout or weight regularization may help stabilize validation performance.
- Early Stopping: Use early stopping to prevent overfitting by halting training once validation loss consistently increases.
- Data Augmentation: Further augmenting the dataset may improve generalization and reduce the variability seen in validation accuracy and loss.
- Layers: Adding more dense layers and Batchnormalization layers.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow==2.17.0
- numpy==1.26.4
- pandas==2.2.2
- PIL==10.4.0
- tensorflow.keras==3.5.0
- keras==3.5.0
- Augmentor==0.2.12

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@siddhant1605] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->