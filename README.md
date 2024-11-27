# CNN-model
CNN Model: Glasses vs No Glasses (Image Classification)
Objective:
Classify images of people as wearing glasses or not wearing glasses using a Convolutional Neural Network (CNN).

Steps:

Data Collection:
Gather a labeled dataset containing images of people with and without glasses.

Data Preprocessing:
Data Loading: Load image datasets.
Image Resizing: Resize all images to a fixed size.
Image Normalization: Scale pixel values to the range [0, 1] for faster convergence.

Model Building:
Build a CNN architecture with convolutional layers, pooling layers, and fully connected layers.
Use dropout to reduce overfitting and activation functions like ReLU for non-linearity.

Model Compilation:
Compile the model using a loss function (e.g., categorical_crossentropy), an optimizer (e.g., Adam), and evaluation metrics (e.g., Accuracy).

Model Training:
Train the model on the training dataset with validation data to monitor performance.

Model Evaluation:
Evaluate the model on test data and getting accuracy- 65%
