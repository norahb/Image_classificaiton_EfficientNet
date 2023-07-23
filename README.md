# Custom Binary Image Classification using EfficientNetV2

This repository contains a notebook for custom binary image classification using the EfficientNetV2 model. The notebook allows users to train a binary image classifier on their own dataset and visualize the training results. Additionally, users can test the trained model on new images for prediction.


## Requirements
- Python 3.6+
- TensorFlow 2.x
- Matplotlib


## Dataset Preparation
Before running the notebook, you need to organize your custom dataset in the following format:
```
Dataset
├───train
│   ├───Class1
│   └───Class2
└───val
    ├───Class1
    └───Class2
```
## Installation

1. Clone this repository to your local machine.
https://github.com/norahb/Image_classificaiton_EfficientNet.git

2. Open the Notebook file `Binary_Image_Classification_EfficientNet.ipynb` in Jupyter Notebook, or Colab.

3. Modify the default values for `img_width`, `img_height`, `effnet_version`, and `epochs` variables as per your requirements. You can also run the Notebook as-is to use the default values.

4. The Notebook will prompt you to enter the desired image width, image height, EfficientNet version, and the number of epochs.

5. The Notebook will preprocess the data, train the custom binary classification model using the specified options, and visualize the training results.
   

## Results

After executing all the cells in the Notebook, you will find the trained model in the `saved_model/` directory. The model can be used for inference on new images or integrated into other applications.


To learn more about EfficientNetV2 and its variants, please visit the [Keras EfficientNetV2 documentation](https://keras.io/api/applications/efficientnet_v2/).

## Note
The EfficientNetV2 model versions available for selection are: EfficientNetV2B0, EfficientNetV2B1, EfficientNetV2B2, EfficientNetV2B3, EfficientNetV2S, EfficientNetV2M, and EfficientNetV2L.

Make sure to adjust the dataset paths, image dimensions, and other hyperparameters as needed for your specific dataset.

Feel free to experiment with different EfficientNetV2 versions and hyperparameters to achieve better classification performance.

