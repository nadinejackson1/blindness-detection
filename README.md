# Blindness Detection

This repository provides a solution for detecting blindness using Convolutional Neural Networks (CNNs) based on the APTOS 2019 Blindness Detection competition on Kaggle. The data set includes a large set of retina images taken using fundus photography under a variety of imaging conditions.

### Installation

1. Clone the repository
2. Download the dataset from [Kaggle APTOS 2019 Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection/data)
3. Unzip the dataset in your current working directory.

### Dependencies

This project is built using Python and requires the following libraries:

* Keras
* Pandas
* Numpy
* Matplotlib
* Scikit-learn

You can install the dependencies using pip:

    pip install keras pandas numpy matplotlib scikit-learn

### Usage

To train and evaluate the model, run the following:

    python blindness_detection.py

You can modify the model and preprocessing steps according to your needs.

### Model

We use transfer learning using the pre-trained ResNet50 model. We made the base model untrainable and added a dense layer on top for the classification task.

### Results

The model's performance is evaluated in terms of accuracy and loss on the validation set. The model's performance over epochs can be visualized using matplotlib.

### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### License

This project is licensed under the terms of the MIT license.

### Acknowledgements

This project uses data from the APTOS 2019 Blindness Detection competition on Kaggle.
