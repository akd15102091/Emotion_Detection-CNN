# Emotion_Detection-CNN

In this project

       We **predict the Emotion** using **CNN deep learning technique** and **Opencv** .

images/train => there are 7 folders containing around total 28000 images

images/test => there are 7 folders containing around total 7000 images

["angry","disgust", "fear", "happy", "neutral", "sad", "surprise"] - 7 types of emotions (7 folders)

The model has been trained over these images.

Used **Transfer Learning (InceptionV3) technique** also along with normal CNN model.

Also tried to optimize the CNN model.

Libraries used in this project :

    1) OS, Numpy, Random, Matplotlib

    2) Tensorflow (keras)
    
    3) Opencv-python


Approach to solve task :

    1) Import the required python libraries
    
    2) Create a function that takes directory name as a argument and return the dataset. This function reads the images from directory, convert them into array and assigned a label.

    3) Create train dataset and test dataset using function which is made for this task.

    4) Convert those dataset in X_train, X_test, y_train, y_test

    5) Convert list(X_train,X_test, y_train, y_test) into numpy-arrays , normalise them.

    6) Apply the CNN model, Transfer learning technique ......, and Optimize the model.

    7) Save the model into h5 file .

    8) Using Opencv, implement model at run time. When camera captures the frame, our model will predict the emotions and if there is no faces in front of camera then "NO FACES" detected.
    
    
    ................................................END........................................................................
