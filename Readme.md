
**Kaggle API**

Official API for https://www.kaggle.com, accessible using a command line tool implemented in Python 3.

**Installation**

For start working with Kaggle, you need to have installed Python 3 and Package manager pip. For installing kaggle run following command,

-- pip install -q kaggle

Some other important packages that we need are Numpy, Panda, OpenCV, TensorFlow, Sklearn and Matplotlib. These packages can be installed by using there respective documentation on their official website.

**Dataset**

The dataset we are using is from kaggle/ruchi798/covid19-pulmonary-abnormalities. Which is available publicly. For downloading the dataset, use following command either in command line or terminal.

-- kaggle datasets download -d ruchi798/covid19-pulmonary-abnormalities

**Data Preprocessing**

For Data Preprocessing we are firstly using the slicing technique to rescale our image dataset and defining a same width and height to all images. For training our model we are using 4 Convolutional layers along with ReLU activation function. For Loss we are using "Cross Entropy loss".
