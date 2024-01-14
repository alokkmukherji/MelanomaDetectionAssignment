# Melanoma Skin Cancer Detection

Melanoma, also redundantly known as malignant melanoma, is a type of cancer that develops from the pigment-producing cells known as melanocytes. Melanomas typically occur in the skin, but may rarely occur in the mouth, intestines, or eye (uveal melanoma).In women, they most commonly occur on the legs, while in men, they most commonly occur on the back. About 25% of melanomas develop from moles.

The primary cause of melanoma is ultraviolet light (UV) exposure in those with low levels of the skin pigment melanin.

Early signs of melanoma are changes to the shape or color of existing moles or, in the case of nodular melanoma, the appearance of a new lump anywhere on the skin.

[Source - Wikipedia]
## Problem Statement
Build a CNN based model which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Goal
To create a multiclass classification model using a custom convolutional neural network in tensorflow

## Dataset
The dataset consists of 2357 images (including train and test set) of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
-  Actinic keratosis
-  Basal cell carcinoma
-  Dermatofibroma
-  Melanoma
-  Nevus
-  Pigmented benign keratosis
-  Seborrheic keratosis
-  Squamous cell carcinoma
-  Vascular lesion

## Steps
-  Loading required libraries 
-  Data ( train and test images ) loading 
-  Dataset Creation based on a batch size of 32 and resize images to 180*180.
-  Dataset visualisation 
-  Initial Model Building & training<br>
   a. Rescale images to normalize pixel values between (0,1)<br>
   b. Selection of an appropriate optimiser and loss function for model training<br>
   c. Train the model for ~20 epochs<br>
   d. Summary of findings<br>
-  Data augmentation to resolve underfitting/overfitting Model Building & training on the augmented data<br>
   a. Rescale images to normalize pixel values between (0,1)<br>
   b. Selection of an appropriate optimiser and loss function for model training<br>
   c. Train the model for ~20 epochs<br>
   d. Summary of findings<br>
- Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the augmented data<br>
   a. Rescale images to normalize pixel values between (0,1)<br>
   b. Selection of an appropriate optimiser and loss function for model training<br>
   c. Train the model for ~30 epochs<br>
   d. Summary of findings<br>
-  Final Summary

