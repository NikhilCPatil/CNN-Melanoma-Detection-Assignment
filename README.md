# CNN Melanoma Detection Assignment

> Outline :- Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model that we build with the given data was over fitting initially
- Later we observed that the data distribution was un even so we h
- We had to argument the data using argumentor and add 500 more samples to each class
- Then with 3 layers and 45 epocs we were able to get training accurasy of 87% and validation accurasy of 81%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python - version 3.11.4
Matplotlib - version 3.10.0
Numpy - version 1.26.4
Pandas - version 2.2.2
Seaborn - version 0.13.2
Tensorflow - version 2.18.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@NikhilCPatil] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->