# Melonoma Detection Assignment
> Mlticlass classification model using a custom convolutional neural network in TensorFlow & Keras.  


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- The model is performing better overall. While the accuracies might still seem low for a classification task.
- Overfitting has been significantly reduced. The model is generalizing better to unseen data.
- There's still room for improvement. The model isn't underfitting (as both training and validation accuracies are well above random guessing for a 9-class problem), but it might benefit from further optimization.

## Technologies Used
- TensorFlow - latest
- Numpy - Latest
- matplotlib - latest
- Augmentor
- google colab for GPU & TPU

## Contact
Created by [@Ashu7] - feel free to contact me!
