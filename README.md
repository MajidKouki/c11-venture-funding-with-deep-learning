# Venture Funding with Deep Learning

This project uses deep neural networks to create models that predict whether or not a business will become a success if invested in. 

---

## Technologies

This project leverages python with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For dataframes.

* [Tensorflow](https://github.com/tensorflow/tensorflow) - For Dense and Sequential.

* [Scikit-learn](https://github.com/scikit-learn/scikit-learn) - For train_test_split, StandardScaler, and OneHotEncoder.

---

## Installation Guide

Before first running the application install the following dependencies:

```python
    pip install pandas
    pip install tensorflow
    pip install scikit-learn
```

Jupyter may be required to view the .ipynb file.

```python
    pip install jupyter
```

---

## Usage

This project was done in Google Colab and has alternate version of the csv import code. To switch between colab and non-colab, comment and uncomment the relevant code blocks at the start of the project. Code is labeled for convenience.

This project can be repurposed to modify and further train the models created within to increase evaluation metrics. Alternatively, the models created within this project are saved to the Models folder and can be used in other projects with the load_model function in TensorFlow as follows:

```python
import tensorflow as tf
path = Path("./Resources/<modelname>.h5")
from tf.keras.models.load_model(path)
```

---

## Contributors

Brought to you by Majid Kouki. You can reach me at [majidkpy@gmail.com](mailto:majidkpy@gmail.com).

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
