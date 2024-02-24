## MNIST Digit Classification using Convolutional Neural Network (CNN)

1. Introduction:
In the realm of underwater exploration, distinguishing between rocks and metal cylinders is crucial for various applications, from marine research to navigation. The dataset at hand provides a comprehensive description of sonar chirp returns, representing the strength of echoes at different angles. This binary classification problem seeks to develop a robust model capable of accurately identifying whether the sonar signals correspond to rocks or metal cylinders.

2. Objective:
The primary objective of this project is to design and train a deep neural network that can generalize well to new, unseen data, effectively distinguishing between rocks and metal cylinders based on the sonar chirp returns.

3. The DATA: 
The dataset consists of 60 input variables representing the strength of the returns at different angles. The dataset is loaded from a CSV file named "sonar.csv" using the Pandas library. It contains 61 columns, where the first 60 columns are input variables, and the last column (60) is the target variable indicating whether the object is a rock or a metal cylinder.
## 🛠 Skills
1. Neural Network Design
2. Model Compilation and Training
3. Regularization Techniques (L2 and Dropout)
4. Exploratory Data Analysis
5. Visualization using Matplotlib


Workflow:
1. Exploratory Data Analysis:

Imported necessary libraries and suppressed warnings for a cleaner output.
Utilized Keras to import the MNIST dataset, a collection of handwritten digits.
Examined the distribution of labels in both the training and test sets.
Displayed a subset of 25 randomly sampled MNIST digits to gain initial insights.

2. Data Preprocessing:

Calculated the number of unique labels in the dataset.
Transformed class labels into one-hot encoded vectors.
Determined the assumed square dimensions of the images.
Flattened and normalized pixel values to a range between 0 and 1.

3. Neural Network Architecture:

Constructed a Sequential model using Keras.
Incorporated three dense layers with ReLU activation functions.
Displayed a summary of the model architecture, including parameters.

4. Model Training:

Specified the loss function, optimizer, and metrics for model compilation.
Executed training for 20 epochs with a batch size of 128 and a validation split of 30%.
Displayed training and validation accuracy and loss over epochs.

5. Results and Evaluation:

Highlighted the achieved test accuracy of 97.2%.
Plotted training and validation loss over epochs using Matplotlib.
Evaluated the final model on the test set to ensure generalization.
Displayed the test loss achieved by the model.

6. Model Optimization - L2 Regularization:

Modified the model to include L2 regularization in the first dense layer.
Observed changes in training and validation loss with the introduction of L2 regularization.

7. Model Optimization - Dropout:

Enhanced model robustness by adding dropout layers after each dense layer.
Analyzed changes in training and validation loss with the introduction of dropout.

8. Combined L2 and Dropout:

Combined L2 regularization and dropout layers for a more resilient model.
Executed training for 20 epochs with the combined regularization techniques.
Evaluated the model on the test set and highlighted achieved accuracy.

## Authors

- [@siddharthiyervarma](https://github.com/siddharthiyervarma)

