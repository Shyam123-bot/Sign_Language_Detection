# Sign_Language_Detection
This repository contains a variety of tools to build up a experimental ecosystem for recognizing signs language. Our claim is an experimental attempt at live subtitling of gestures. For this we train a deep learning model (RNN) for predicting the actual signs made by a person filmed. Therefore we use MediaPipe, a framework for building ML pipelines, to extract face and hand positions, including multiple coordinates for each finger.

# Software requirement specifications
● Python

● IDE (Jupyter)

● Numpy

● CV2 (OpenCV)

● Keras

● Tensorflow

● Matplotlib

● Mediapipe

# Model : LSTM Neural Network
An artificial neural network called Long Short-Term Memory
(LSTM) is employed in deep learning and artificial intelligence.
LSTM features feedback connections as opposed to typical
feedforward neural networks. Such a recurrent neural network
(RNN) may analyze whole data sequences in addition to single
data points (such as photos). For instance, LSTM can be used for
applications like speech recognition, robot control, machine
translation, networked, unsegmented handwriting recognition,
video games, and healthcare.

![image](https://user-images.githubusercontent.com/61462986/224814545-6c175dbb-ea9b-4a95-ab92-a5885d6f56f8.png)

Since there may be lags of uncertain length between significant
occurrences in a time series, LSTM networks are well-suited to
categorizing, processing, and making predictions based on time
series data. To solve the vanishing gradient issue that can arise
when training conventional RNNs, LSTMs were created. In many
cases, LSTM has an advantage over RNNs, hidden Markov
models, and other sequence learning techniques due to its relative
insensitivity to gap length.

# Traningg and Testing
For the above created model we got an accuracy of 97% for training
and 92% for testing

### Training accuracy graph

![image](https://user-images.githubusercontent.com/61462986/224817747-7352137b-2603-45ae-b533-5e1b66ae1018.png)


### Loss per epoch

![image](https://user-images.githubusercontent.com/61462986/224817796-833c1346-51ff-4c1f-8203-44e55dadfa0c.png)






# Result
 
 ### Hello
  
  ![image](https://user-images.githubusercontent.com/61462986/224817856-b5f9a664-fc6f-455b-a85c-2698c24b442e.png)

 ### Yes
  
  ![image](https://user-images.githubusercontent.com/61462986/224817886-7c7b802c-d80a-4855-b26b-4e207641942c.png)

 ### No
  
  ![image](https://user-images.githubusercontent.com/61462986/224817951-f917fd42-4927-4b31-b8a5-fd68e705a5dc.png)

 ### Thanks 
 
  ![image](https://user-images.githubusercontent.com/61462986/224817995-b513275d-1664-4dac-8e3b-5b3af88b8804.png)

  
# Conclusion
  A sign language recognition model can be created using Python
modules like OpenCV and Keras to help the disabled community.
Here, a set of inputs, like photos, are used to train the created
model before it is used to generate a series of messages after
recognizing a particular hand motion.
This model has the unique ability to be trained to create a variety
of messages using custom hand gestures, thereby bridging the
communication gap between people who require special assistance
and the general public.


