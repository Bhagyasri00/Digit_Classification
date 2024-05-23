# MNIST Handwritten Digit Classification

# Introduction

This project aims to build a robust machine learning pipeline for classifying handwritten digits using the famous MNIST dataset. We leverage convolutional neural networks (CNNs) to achieve high accuracy in recognizing digits ranging from 0 to 9.

# Pipeline Overview
1. **Data Loading and Preprocessing**
   - Loaded the MNIST dataset consisting of grayscale images and corresponding labels.
     
   - Preprocessed the data by reshaping images, normalizing pixel values, and one-hot encoding labels.
  
2. **Model Building and Training**
   - Constructed a CNN model using the Sequential API from Keras.
     
   - Compiled the model with Adam optimizer, categorical cross-entropy loss, and accuracy metric.
     
   - Trained the model on the training dataset, validating on a subset for monitoring performance.
     
3. **Model Evaluation**
   - Evaluated the trained model on the test dataset to assess generalization performance.
     
   - Calculated test loss and accuracy metrics to quantify model effectiveness.

4. **Handling NaN Values**
   - Implemented checks for NaN values in the test dataset.
     
5. **Visualization**
   -  Visualized model predictions on a subset of the test dataset, showcasing true and predicted labels.
     
   -  Plotted training and validation accuracies, along with losses, over epochs to visualize training progress.

6. **Saving and Loading Model**
   - Saved the trained model and training history for future use.
     
   - Loaded the saved model and training history for inference, enabling predictions on new data.


# Results

Achieved high accuracy on the test dataset, demonstrating the model's capability to classify handwritten digits effectively.
Through visualization, gained insights into the model's learning dynamics and performance trajectory during training.
Ensured robustness in inference by handling NaN values in the test dataset appropriately.

# Conclusion

This project presents a comprehensive machine learning pipeline for MNIST handwritten digit classification, showcasing the power of CNNs in image recognition tasks.



