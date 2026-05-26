A deep learning project that classifies smartphone images into Samsung or Apple categories using a Convolutional Neural Network (CNN).
Built using Python with TensorFlow, Keras, Matplotlib, and Google Colab with Drive integration
Dataset contains 150 images split into 2 classes — Samsung and Apple — stored in Google Drive
Loaded and preprocessed images using image_dataset_from_directory with 200x200 resolution
Applied 90/10 training and validation split with a batch size of 32 for model training
Visualized all training images from both Samsung and Apple folders using Matplotlib
Built a Sequential CNN model with Conv2D, MaxPooling2D, Flatten, and Dense layers
Used ReLU activation for hidden layers and Sigmoid activation for binary classification output
Dense layer with 512 neurons used for feature learning before the final prediction layer
Model designed to distinguish between two major smartphone brands from image data
Useful for brand recognition and image-based product classification using deep learning.
