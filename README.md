# Melanoma Detection Assignment
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- The dataset comprises 2,357 images representing various oncological diseases, both malignant and benign. These images were sourced from the International Skin Imaging Collaboration (ISIC) dataset.

- The dataset's images were categorized based on the classifications provided by ISIC. Each category contains a similar number of images, except for melanomas and moles, which have a slight predominance.

- The dataset encompasses a diverse range of skin diseases, including actinic keratosis, basal cell carcinoma, dermatofibroma, melanoma, nevus, pigmented benign keratosis, seborrheic keratosis, squamous cell carcinoma, and vascular lesions.

- This dataset is valuable for training and evaluating machine learning models designed for dermatological image analysis and disease classification tasks.

- The inclusion of malignant and benign conditions, along with the diversity of diseases represented, makes this dataset a valuable resource for research and medical applications related to skin cancer and dermatology.


## Technologies Used
- TensorFlow	2.13.0-rc2
- Matplotlib	3.5.1
- NumPy	1.22.2
- Pandas	1.4.2
- PIL	8.3.2
- Seaborn	0.11.2
- Keras	2.9.0



## Conclusions
- As the training accuracy increases linearly over time, where as the validation accuracy increases in training process.
- As the training loss decreases with epochs the validation loss also decreases.
- The plots show that gap between training accuracy and validation accuracy have decreased significantly from previous model, and it has achieved around 74% accuracy on the validation set.
- The difference in accuracy between training and validation accuracy is very less