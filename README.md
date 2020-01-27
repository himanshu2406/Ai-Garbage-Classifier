# Ai-Garbage-Classifier
Classifies the garbage into 6 classes - {'cardboard': 0, 'glass': 1, 'metal': 2, 'paper': 3, 'plastic': 4, 'trash': 5}

Uses CNN and has an accuracy of 80+ % on New data.*

Takes in input of 256x256 and thus has more features and thus the higher size of .h5 

Trained using colab (With GPU)

Trained on 2527 images 

Data : https://www.kaggle.com/asdasdasasdas/garbage-classification 

80 Mb .h5 file of the trained model :  


Just use the code below from 'IN[0] : 
classifier.save('garbage_classifier.h5')' (Not including it but execute the code below it)

Make sure the .h5 file is in the same directory and replace imageee by our own file path of image.

^Requires a white background
