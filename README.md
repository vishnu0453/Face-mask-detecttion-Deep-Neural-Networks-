# Face-mask-detecttion-Deep-Neural-Networks-

### ABSTRACT:
In the introduction, we mentioned the significance of taking precautionary measures to
prevent the spread of the COVID-19 virus. Wearing masks is one of the most effective ways to
prevent the virus's spread, and the mask detection system aims to ensure that people wear
masks in public places.

### PROBLEM STATEMENT:
 The objective of this project is to develop a face mask detection system using OpenCV
and Keras.
 The system should be able to detect faces in real-time video streams and determine
whether the person is wearing a face mask or not.
 The face mask detection system will be trained using a dataset of images of people
wearing face masks and not wearing face masks.
 The system will use Deep Neural Networks (DNN) to classify the images and
determine whether a face mask is present or not.

### DATASET:
We used a our own dataset that consisted of 7553 images of people wearing and not
wearing masks. The dataset was split into two equal parts, with 3776 images of people
wearing masks and 3777 images of people not wearing masks. The dataset was balanced to
ensure that the model is not biased towards one class.

### METHODODLOGY:
We used a deep Neural Networks approach to train our mask detection model.
We trained our model on a cloud based GPU for 30 epochs, which means that the model
was trained on the dataset 30 times. We used the Adam optimizer with a learning rate of
0.001, which is a commonly used optimizer for training deep learning models. We used
the binary cross-entropy loss function to optimize the model, which is a commonly used
loss function for binary classification problems.

### EVALUATION:
We evaluated our model on a test set that consisted of 1,511 images, which were not used
during the training phase. We used accuracy as our primary metric to evaluate the
model's performance. Our model achieved an accuracy of 98%, which means that the
model predicted the correct class for 98% of the test set images.

### We also calculated the precision and recall values for our model. Precision measures the
proportion of true positives among the total positive predictions, while recall measures
the proportion of true positives among the total actual positive instances. Our model
achieved a precision value of 98%, which means that 98% of the predictions made by the
model were true positives. The recall value was 98%, which means that the model
correctly identified 98% of the actual positive instances in the test set. 

### USE CASE DIAGRAM:
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/c44e24ef-0552-46bb-bf0b-0276eea4fe14)

### Class Diagram:
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/9cb0b357-0180-415b-9a35-fbdad44a9ac6)


### DATA FLOW DIAGRAM:
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/72375b50-cc6a-4a4c-9560-28e52dbafe89)

### CODE:
Building Deep Neural network
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/90f785ba-1616-4e3f-a98b-dd6a92a49224)

### Architecture of DNN:
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/ba8c9163-0dbd-4034-9b94-4052b7b4a5de)


### Training DNN
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/f80977fc-2d2e-4f0e-a5bd-d4d152885599)


### Loss plots
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/08ee91c2-2300-41da-9e4a-9c1aab5dbb73)

### WITH MASK DETECTION
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/ec7f7b2f-7f96-4ec7-852c-7f79a5454f56)


### WITHOUT MASK DETECTION
![image](https://github.com/vishnu0453/Face-mask-detecttion-Deep-Neural-Networks-/assets/73246457/2d96a7b8-dedb-4907-9ac9-0306e59643a4)

### CONCLUSION:
In conclusion, we developed a mask detection system that can detect whether people are wearing masks or not. We used a deep learning-based approach and achieved an accuracy of 98% on the test set. Our model can be an effective tool for enforcing mask-wearing in public places. We also deployed our model on a low- power device like the Raspberry Pi, which makes it easily accessible and affordable. Overall, our mask detection system has the potential to contribute to the ongoing efforts to prevent the spread of the COVID-19 virus.



