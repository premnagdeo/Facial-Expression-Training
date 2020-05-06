# Facial-Expression-Training

Facial Expression Recognition using a Convolutional Neural Network.

Model Accuracy - 64.26%

This Model is based on the FER2013 Dataset:
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data


## Getting Started

### Requirements
> Python (3.x)

> Tensorflow (2.2.0)

> Keras (2.3.1)

> Numpy (1.18.3)

> OpenCV (4.2.0)

> Flask (1.1.2)


### Clone
Clone this repo to your local machine using 

> git clone https://github.com/premnagdeo/Facial-Expression-Training.git


### Usage

* Run the pretrained model (model.json) with parameters (model_weights.h5):

> python main.py

This will start flask and you can view the out at http://127.0.0.1:5000/


* To switch to live camera feed Facial Expression Detection:

In `camera.py`, use:
> self.video = cv2.VideoCapture(0)


* To retrain the model, extract the dataset from `dataset.zip` and run `Facial_Expression_Training.ipynb`

## Model

### Model Architecture
![Model Architecture](https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/model_architecture.png)


### Model Summary
![Model Summary 1](https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/model_summary_1.png)

![Model Summary 2](https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/model_summary_2.png)


### Model Accuracy
![Model Accuracy](https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/plot.png)


### Images in the Dataset

<img alt="Dataset Images" src="https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/sample_dataset_images.png" height=60% width=80%> 


## Sample Output

<img alt="Happy Example" src="https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/happy.png" height=40% width=40%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img alt="Sad Example" src="https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/sad.png" height=40% width=40%>

<img alt="Disgust Example" src="https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/disgust.png" height=40% width=40%> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img alt="Surprise Example" src="https://github.com/premnagdeo/Facial-Expression-Training/blob/master/Images/surprise.png" height=40% width=40%>

