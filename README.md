# Blood Cell Image Classifier

---

Task: Build an image classifier to identify blood cell types.

### Prerequisites:
* Python 3
* Keras with TensorFlow backend
* numpy, scipy, seaborn, sklearn
* cv2
* data source: [Kaggle](https://www.kaggle.com/paultimothymooney/blood-cells)

### Description
There are important applications in medicine to help identify blood cell images correctly.
In this exercise, an image classifier is built using a convolutional neural network.
Data preprocessing in this work relies on the
ImageDataGenerator class in Keras as it is not efficient to load all the images onto memory. 
The model is assessed by use of a confusion matrix and computing performance scores (i.e., precision, recall, f-score).
