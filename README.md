# Sign Language Classification
Software Used - Windows 10/11 64 bit OS 
                        Google Colab/Jupyter Notebook
Programming Language Used - Python 3.8.0
Dataset - Kaggle MNIST Dataset for Sign Language Classification using CNN
API required- Keras version 2.13.0
Framework - Tensorflow version 2.13.0
Libraries used - string , Pandas , Numpy , Matplotlib , ImageDataGenerator

Step-1 - Download the Kaggle MNIST Dataset from here https://www.kaggle.com/datasets/hojjatk/mnist-dataset and Unzip the file.
Step 2 - Import the required libraries
Step 3 - Import the training Dataset and perform read operation on it.
Step 5 - Data Preprocessing - Load the training data in the training module and testing data in the testing module.
Step 6 - Data Visualization - Plot the images from the training data images in the form of a grid 
Step 7 - Model Development - Import the tensorflow framework and Keras API along with Keras Layers namely Convo2D , Dense , MaxPooling2D , Flatten , BatchNormalization and Dropout. Train the model using each layer to refine the data cleaning.
Compile the model.
Step 8 - Model Training - Train the model using the cleaned training dataset and extract the text and label columns from the DataFrame to create a text Dataset.
Step 9 - Model Evalutaion - Generate a Correlation Matrix for the dataframe generated in the previous step and evaluate the model using the different Keras Layers. 
Compute the model Accuracy and predict the loss.
                 

