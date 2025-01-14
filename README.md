# Project Name
> Melanoma Detection Assignment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Project Information: This is an assigment where we aim to build a multiclass classification model using a custom convolutional neural network in TensorFlow.  

- Business Problem: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 

- Dataset: The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion


## Technologies Used
- Numpy Version :  1.26.4
- Pandas Version :  2.2.2
- Matplotlib Version :  3.10.0
- Seaborn Version :  0.13.2
- TensorFlow Version :  2.17.1


## Conclusions
- The final model showcases well-balanced performance, displaying no signs of underfitting or overfitting.

- The implementation of class rebalancing has notably enhanced the model's performance across both training and validation datasets.

- Following 50 epochs, the final model attains an accuracy of 81% on the training set and approximately 82% on the validation set.

- There is a very low difference between training and validation accuracies signifying the robust generalization capability of the final CNN model.

- The addition of batch normalization failed to enhance both training and validation accuracy due to low batch size. We can experiment with larger batch size to get positive effect of batch normalization layer.


## Acknowledgements
- UpGrad tutorials on Convolution Neural Networks (CNNs) on the learning platform
- This project was based on UpGrad IITB Programme as an assignment for the Machine Learning and Artificial Intelligence course.


## Contact
Created by [@mh-utkarsh] - feel free to contact me!
