# Face-mask-detecttion-Deep-Neural-Networks-

ABSTRACT:
In the introduction, we mentioned the significance of taking precautionary measures to
prevent the spread of the COVID-19 virus. Wearing masks is one of the most effective ways to
prevent the virus's spread, and the mask detection system aims to ensure that people wear
masks in public places.
PROBLEM STATEMENT:
 The objective of this project is to develop a face mask detection system using OpenCV
and Keras.
 The system should be able to detect faces in real-time video streams and determine
whether the person is wearing a face mask or not.
 The face mask detection system will be trained using a dataset of images of people
wearing face masks and not wearing face masks.
 The system will use Deep Neural Networks (DNN) to classify the images and
determine whether a face mask is present or not.
DATASET:
We used a our own dataset that consisted of 7553 images of people wearing and not
wearing masks. The dataset was split into two equal parts, with 3776 images of people
wearing masks and 3777 images of people not wearing masks. The dataset was balanced to
ensure that the model is not biased towards one class.
METHODODLOGY:
We used a deep Neural Networks approach to train our mask detection model.
We trained our model on a cloud based GPU for 30 epochs, which means that the model
was trained on the dataset 30 times. We used the Adam optimizer with a learning rate of
0.001, which is a commonly used optimizer for training deep learning models. We used
the binary cross-entropy loss function to optimize the model, which is a commonly used
loss function for binary classification problems.
EVALUATION:
We evaluated our model on a test set that consisted of 1,511 images, which were not used
during the training phase. We used accuracy as our primary metric to evaluate the
model's performance. Our model achieved an accuracy of 98%, which means that the
model predicted the correct class for 98% of the test set images.

We also calculated the precision and recall values for our model. Precision measures the
proportion of true positives among the total positive predictions, while recall measures
the proportion of true positives among the total actual positive instances. Our model
achieved a precision value of 98%, which means that 98% of the predictions made by the
model were true positives. The recall value was 98%, which means that the model
correctly identified 98% of the actual positive instances in the test set. 

USE CASE DIAGRAM:
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/c44e24ef-0552-46bb-bf0b-0276eea4fe14)

