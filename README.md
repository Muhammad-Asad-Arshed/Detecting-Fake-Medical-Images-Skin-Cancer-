# Detecting-Fake-Medical-Images-Skin-Cancer-
A deep learning model designed to detect fake medical images, aiming to reduce financial insurance fraud.
# Model Training
Model is based on InceptionV3 and trained with StatifiedKFold=3 approach.

After training with StatifiedKFold=3, model best weights are stored for future prediction. 

In this 'Medical_Fake_Test.ipynb' file, model weights and test images of 600 (300 (real)+300 (fake)) will be downlaoded and extracted.

Test Images are laoded using generator and model evaluted, the results of Test Loss: 0.03022, Test Accuracy: 99.17%. 
