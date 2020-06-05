# CNN-Emotion-Regnition
  
    Import essential modules and helper functions from NumPy, Matplotlib, and Keras.
    
    The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown     
    in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).I 
    used OpenCV to automatically detect faces in images and draw bounding boxes around them. Once have trained, saved, and exported
    the CNN, then this can be directly serve the trained model to a web interface and perform real-time facial expression 
    recognition on video and image data. 

#Data-set Used
    Display some images from every expression type in the Emotion FER dataset.
    Check for class imbalance problems in the training data.


#Create a Convolutional Neural Network (CNN) Model
  1. Designed a convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial            
     expressions.
  2. Used Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.

#Batch_Size used is 4
#epoch = 50

    Run the main.py script to create the Flask app and serve the model's predictions to a web interface.
    Apply the model to saved videos on disk.
