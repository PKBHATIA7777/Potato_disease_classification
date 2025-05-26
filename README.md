Potato Disease Classifier
This is a deep learning model I built to classify potato leaf images into one of three categories:

Early Blight
Late Blight
Healthy
I trained this using TensorFlow on the Plant Village dataset — it’s a great collection of real-world plant disease images.

What It Does
I made this as part of a project to explore how AI can help with crop health.
The model looks at an image of a potato leaf and tries to tell if it's healthy or affected by one of the two common blights.

It’s not perfect, but it works pretty well — and I had a lot of fun building it!

How I Built It
Used TensorFlow/Keras for training
Created a CNN (Convolutional Neural Network) from scratch
Trained on resized 224x224 images
Added data augmentation to improve generalization
Reached over 98% test accuracy
