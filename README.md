# Neural Network Binary Classifier

This program build a binary classifier to predict a business' future success using deep neural networks.
----

## Technologies
This application is written in Jupyter Lab Notebook in the Python programming language. It was edited in Google Colab. The Python libraries, tools, and modules used in this application are Pandas, TensorFlow, Keras, and scikit-learn(StandardScaler, OneHotEncoder).

[Pandas](https://pandas.pydata.org/docs/index.html), [TensorFlow](https://www.tensorflow.org/api_docs/python/tf/all_symbols), [Keras](https://keras.io/), [scikit-learn](https://scikit-learn.org/stable/index.html)


----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

This program is also reliant on Tensorflow and Keras. Currently, the Apple M1 chip is not compatible with Tensorflow installation, so you will not be installing these tools on your local machine. The program will run using Google Colab, without needing to install TensorFlow and Keras. 

----

## Usage
For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import pandas as pd
    from pathlib import Path
    import tensorflow as tf
    from tensorflow.keras.layers import Dense
    from tensorflow.keras.models import Sequential
    from sklearn.model_selection import train_test_split
    from sklearn.preprocessing import StandardScaler,OneHotEncoder


**The program is comprised of 3 parts:**

1. Preprocess the Data for Use on a Neural Network Model

2. Compile and Evaluate a Binary Classification Model Using a Neural Network

3. Optimize the Neural Networ model

----

## Contributors

Arlie Jones

[E-mail](arliejones98@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/arlie-jones-020092159/)

----

## License

None