# Dog vs Cat Classification Using CNN

![cat_or_dog_1](https://github.com/user-attachments/assets/2f0b0727-2dd6-4d4e-8e3f-8e8d929797b1)

### Overview

This project implements a Convolutional Neural Network (CNN) to classify images of dogs and cats. The model is trained on a dataset containing 4000 images of each class (dogs and cats) and tested on a separate set of 1000 images of each class. The primary goal is to achieve high accuracy in differentiating between the two categories using deep learning techniques.

### Project Structure

├── dataset/<br>
│   ├── training_set/<br>
│   │   ├── cats/<br>
│   │   └── dogs/<br>
│   └── test_set/<br>
│       ├── cats/<br>
│       └── dogs/<br>
│   └── single_prediction/<br>
├── CNN.ipynb<br>
├── requirements.txt

- **dataset/:** Contains the training and test datasets, organized into separate folders for cats and dogs.
- **CNN.ipynb:** Jupyter notebook used for model development and experimentation.
- **requirements.txt:** List of dependencies and libraries required to run the project.

### Model Architecture
The CNN model used in this project has the following architecture:

**Convolutional Layers:** Extract spatial features from the images.<br>
**Pooling Layers:** Reduce the dimensionality of the feature maps.<br>
**Flattening:** To flatten the pooled matrix to a vector.<br>
**Fully Connected Layers:** Combine the features to make predictions.<br>
**Activation Functions:** ReLU for hidden layers and sigmoid for the output layer.

### Installation
To run this project locally, follow these steps:

1. Clone the repository:<br>

   git clone https://github.com/ayushkhandelwal123/Dog-vs-Cat-Classification-Using-CNN.git
   
3. Navigate to the project directory:<br>

     cd Dog-vs-Cat-Classification-Using-CNN
   
5. Install the required dependencies:<br>

     pip install -r requirements.txt
   
7. Download the dataset and place it in the dataset/ directory.<br>

8. Run the training script:<br>

     python convolutional_neural_network.py

### How to Use
- **Training:** The model can be trained by running the main.py script.<br>
- **Evaluation:** After training, the model can be evaluated on the test dataset to measure its performance.<br>
- **Prediction:** You can use the trained model to predict whether a new image is of a dog or a cat.


