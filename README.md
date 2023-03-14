# CNN Melanoma detection
> We built a multiclass classification model using a custom convolutional neural network in TensorFlow


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We built a melanoma detection model using convolitional nueral network.
- The purpose is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 
- We are given a dataset which consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Using the images as it is to build the model doesn't help much with the accuracy. It was underfitting.
- A plain CNN model without dropouts and batch normalization also doesn't provide good result in terms of accuracy.
- When the images were augmented, and dropouts were added, there was unnoticable change in accruacy and it didn't solve underfitting.
- Dropouts improved the performance significantly
- Class rebalancing played a big part in improving the accuracy when coupled with batch normalization and augmentation. The validation accuracy jumped from 50% to 85.5%.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9.12
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2
- tensorflow - version 2.11.0
- Augmentor - version 0.2.10

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of the assignment

## Contact
Created by @Iamvib - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
