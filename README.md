
# README.md

# Handwritten Digit Recognition with CNN on MNIST Dataset
This project focuses on building and training a Convolutional Neural Network (CNN) to classify handwritten digits from the renowned MNIST dataset. Using state-of-the-art deep learning tools, the model demonstrates high accuracy in recognizing digits and evaluates its performance using various metrics and visualizations.

# Project Highlights
Objective: Create an accurate model for handwritten digit classification using the MNIST dataset.

Output:
• Test accuracy of the trained CNN.
• Visualization of true vs. predicted labels.
• Classification report with precision, recall, and F1-score for each digit.

# Project Components
1. Libraries Used
Pandas: Data manipulation and loading MNIST dataset from CSV files.

NumPy: Numerical operations and array handling.

Matplotlib: Visualization of images and results.

Scikit-learn: Train-test split and performance evaluation (accuracy, classification report).

TensorFlow & Keras: Building, compiling, and training the CNN model.

2. Dataset Loading and Preprocessing
The MNIST dataset is loaded from CSV files (mnist_train.csv and mnist_test.csv) using Pandas.
Pixel values are normalized to the range 0 to 1 for better convergence during training.

3. Data Splitting
The dataset is divided into training and validation sets using train_test_split from Scikit-learn.

4. Convolutional Neural Network (CNN)

Model Architecture:
• Convolutional layers with ReLU activation for feature extraction.
• Max-pooling layers for downsampling.
• Dense layers for classification with:
• ReLU activation for intermediate layers.
• Softmax activation for final classification into digit classes (0–9).

5. Model Compilation and Training
The model is compiled using:

• Optimizer: Adam.

• Loss Function: Categorical cross-entropy.

• Trained on the MNIST training data for 10 epochs, with validation data for monitoring performance.

6. Model Evaluation

• Accuracy: The trained model is evaluated on the test dataset.

7. Visualization:

• A subset of test images is displayed with their true and predicted labels.

8. Classification Report: Includes metrics like precision, recall, and F1-score for detailed performance analysis.

Expected Output
• Test Accuracy: Quantifies the model's performance on unseen data.

• Visualization: Shows the test images along with their actual and predicted labels.

• Classification Report: Detailed metrics for each digit class (0–9), providing insights into the model’s strengths and areas for improvement.
