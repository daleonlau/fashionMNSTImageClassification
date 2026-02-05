# fashionMNISTImageClassification

google collab link: https://colab.research.google.com/drive/1zSfN432tLszkExzSlp-v_E1fOTS520XH?usp=sharing

Questions: (February 8, 2026)
## 1. What is the Fashion MNIST dataset?
- Fashion MNIST is a dataset of 70,000 grayscal images of clothing items, each sized 28x28 pixels, classified into 10 categories. It is used for training and testing image classification models.

## 2. Why do we normalize image pixel values before training?
- Normalization scales pixel values from 0-255 to 0-1, which helps the model train faster, more accurately, and more stably. 

## 3. List the layers used in the neural network and their functions.
- Flatten Layer - Converts 2D images into 1D data
- Dense Layers(ReLU) - Learn important image features
- Output Dense Layer - Produces scores for 10 classes
- Softmax Layer - Converts scores into probabilities 

## 4. What does an epoch mean in model training?
- An epoch is one full pass of the training data through the neural network.


## 5. Compare the predicted label and actual label for the first test image.
- The predicted label matches the actual label if the model classifies the image correctly; otherwise, it is incorrect.

## 6. What could be done to improve the model’s accuracy?
- Add more layers or neurons
- Train for more epochs
- Use regularization techniques
- Tune model parameters



