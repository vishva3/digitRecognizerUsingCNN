# digitRecognizerUsingCNN

About Dataset:
The dataset that I used for this project is the very famous MNIST dataset. It consists of 60,000 images of 28x28 pixel grayscale images of handwritten single digit numbers ranging from 0 to 9 in different fonts. 
You can find the dataset here: https://www.kaggle.com/competitions/digit-recognizer/data?select=test.csv

Packages used:
For completing this task, I have used numpy and pandas for doing the basic operations in python. I used matplotlib for data visualization. Further, to train and split the dataset, I have used keras and sklearn.

Model Trained:
For training the model, I tried various convolutional neural networks. You can go through my final network on the above repository. To give a gist, I have applied a sequence of convolutional layers with batchnormalization and maxpooling wherever required. ReLU activation function is been used throughout the training except for the final layer, where I have used a sigmoid function. I have further applied dropout layers to avoid overfitting on my training data. For more understanding, you can refer to the code.

Feel free to give suggestions if you see any scope of improvement.

