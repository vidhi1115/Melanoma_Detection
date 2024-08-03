# Melanoma Detection using a CNN model

CNN based model which can detect melanoma. 

## Table of Contents

- [General Information](#general-information)
- [Data characteristics](#dataset-characteristics)
- [Predicted models](#predicted-models)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

## General Information

This project is to create a CNNbased model to detect Melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Dataset characteristics

Dataset contains a total of ~2.2k images belonging to 9 classes.

Dataset is loaded as a Tensorflow Batch Dataset. The `image_batch` is a tensor of the shape `(32, 180, 180, 3)`. This is a batch of 32 images of shape `180x180x3` (the last dimension refers to color channels RGB). The `label_batch` is a tensor of the shape `(32,)`, these are corresponding labels to the 32 images.


### Predicted models 

1. Create a Basic CNN model, with two sets of convolution layers followed by 2 dense layers, ending with a softmax layer with 9 outcomes. 
2. Adding droput layers
3. testing the change in accuracy with adding more layers and increasing the filter size.
4. Agumenting image data to deal with class imbalance


## Technologies Used

- Python 3.10.9
- Jupyterlab 3.6.3
- numpy 1.23.5
- pandas 1.5.3
- matplotlib 3.7.0
- tensorflow 2.10.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact

Created by [Vidhi Agarwal](https://github.com/vidhi1115)
