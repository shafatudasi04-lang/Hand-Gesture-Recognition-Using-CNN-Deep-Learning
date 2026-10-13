# Hand Gesture Recognition Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify hand gesture images using the LeapGestRecog dataset. It demonstrates image preprocessing, deep learning model training, evaluation, and image-based prediction.

## Technologies Used
- Python
- Google Colab
- TensorFlow and Keras
- NumPy and Pandas
- Matplotlib
- Scikit-learn
- Pillow (PIL)

## Dataset
**LeapGestRecog — Hand Gesture Recognition**

The dataset contains images representing different hand gestures.

Dataset link: https://www.kaggle.com/datasets/gti-upm/leapgestrecog

The dataset is downloaded programmatically using KaggleHub.

## Model Architecture
The CNN includes:
- Convolutional layers
- Batch normalization
- Max pooling
- Global average pooling
- Dense classification layer
- Dropout regularization
- Softmax output for gesture classes

## Project Workflow
1. Download and inspect the dataset.
2. Collect image paths and gesture labels.
3. Split data into training, validation, and test sets.
4. Resize and normalize images.
5. Build and train the CNN model.
6. Evaluate test accuracy and loss.
7. Generate accuracy and loss graphs.
8. Display the confusion matrix and classification report.
9. Predict gestures from individual images.
10. Save the trained model and prediction results.

## Model Evaluation
The project evaluates the model using:
- Test accuracy
- Test loss
- Classification report
- Confusion matrix
- Per-class accuracy

Actual performance metrics should be added after training.

## Files Generated
- `hand_gesture_recognition.keras` — trained CNN model
- `gesture_classes.json` — class label mapping
- `hand_gesture_predictions.csv` — test prediction results

## How to Run
1. Open Google Colab.
2. Create a new Python notebook.
3. Run the dataset download and preprocessing cells.
4. Train the CNN model.
5. Run the evaluation and prediction cells.

## Future Improvements
- Real-time gesture recognition using a webcam.
- Data augmentation and model optimization.
- Deployment as a web application.
- Support for additional gestures.

## Author
**Shafaat Ullah**

## License
Add an appropriate license if you intend to distribute or reuse the project publicly.
