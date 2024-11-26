# Bird Species Classification using Convolutional Neural Networks (CNN)

This project uses a Convolutional Neural Network (CNN) to classify images of birds into six different species: American Goldfinch, Barn Owl, Carmine Bee-Eater, Downy Woodpecker, Emperor Penguin, and Flamingo.

# Dataset

The dataset consists images of birds. The images were preprocessed by resizing them to 224x224 pixels and normalizing the pixel values.

# Model

The CNN model was built using the Keras library in Python. The model consists of several convolutional and max-pooling layers, followed by fully connected layers. The model was trained using the Adam optimizer and categorical cross-entropy loss function.

# Results

The model achieved an accuracy of 89.99% on the test dataset. The confusion matrix and classification report are shown below:
# Usage

To use this project, simply clone the repository and install the required dependencies. You can then use the predict function to classify new images of birds.

# Dependencies

- Python 3.x
- Keras 2.x
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

# License

This project is licensed under the MIT License.


