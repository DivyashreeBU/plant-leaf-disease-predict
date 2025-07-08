Plant Leaf Disease Prediction using Deep Learning
About the Project:
This project focuses on the detection of plant leaf diseases using Convolutional Neural Networks (CNNs) implemented in Python with TensorFlow/Keras. By training a deep learning model on labeled images of healthy and diseased leaves, the system learns to accurately classify the type of disease affecting a plant.
The model takes input leaf images, processes them using image augmentation and normalization techniques, and is trained to recognize patterns associated with various plant diseases. It leverages a deep CNN architecture to extract features and make predictions across 10–15 different plant disease categories.

The Dataset consists plant leaf images of:
-Pepper_bell__Bacterial_spot 
-Pepper_bell__healthy
-Potato___Early_blight
-Potato___Late_blight
-Potato___healthy

Key Features:
-Built using TensorFlow and Keras
-Uses ImageDataGenerator for real-time data augmentation
-Trained on structured folder-based image datasets
-Model saved in .h5 format for integration with a Flask web app
-Class labels are saved for use during inference

Objective:
To assist farmers and agricultural experts in identifying plant diseases early by simply uploading a leaf image, which the model analyzes to predict the disease category. 

Requirements:
Python need to be installed
Tensorflow need to be installed
Steps need to be followed in order to execute the file:
step 1:Download and Execute both the files named PlantVillage.zip(dataset folder) and plantleafpredict.zip
step 2:copy and paste the dataset folder in predict folder
step 3:open the terminal of the path where you have the project
step 4:Type the command python app.py in the terminal and press enter
step 5:By default it opens the browser or the path is given.By default the path is http://127.0.0.1:5000
