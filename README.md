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

#Traing and Testing
For the above created model we got an accuracy of 97% for training
and 92% for testing
#Training accuracy graph

![image](https://user-images.githubusercontent.com/61462986/224817051-cce7cddd-4b00-488a-90e0-6470c36fc999.png)

#Loss per epoch

![image](https://user-images.githubusercontent.com/61462986/224817072-b99df069-c17f-4c7c-9f10-978f9c499cd2.png)



# Result
  Hello
  ![image](https://user-images.githubusercontent.com/61462986/224812464-882f36ea-f475-4d2c-a921-337561687d87.png)

  Yes
  ![image](https://user-images.githubusercontent.com/61462986/224812503-45b69fce-756a-4b8d-8a80-15528453a3af.png)

  No
  ![image](https://user-images.githubusercontent.com/61462986/224812547-b8319bfb-1358-4ea5-be19-be933e9c12a7.png)

  Thanks 
  ![image](https://user-images.githubusercontent.com/61462986/224812590-d7fb529e-eb21-4d42-baeb-7bbc1299dcc5.png)
  
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


