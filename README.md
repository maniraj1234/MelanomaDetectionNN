# MelanomaDetectionNN
CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## Conclusions
- Adam optimizer performed better than stochastic gradient descent.
- Adding dropout and normalization helped to overcome the problem of overfit.
- Adding more convolution layers / more channels increased the model complexity, run time & accuracy proportinately.
- SeparableConv2D have improved the training time compared to the simple SeparableConv2D
- Increasing the number of epochs is increasing the model accuracy.
- softmax activation performed better over others in final layer.


## Technologies Used
- Google colab
- Azure ML studio (python3 kernel)
- python3
- tensorflow
- keras
- numpy
- augmentor

## Dataset: 
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
## Contact
Created by [@maniraj1234] - feel free to contact me!
