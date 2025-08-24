
# Hand Gesture Recognition Using CNN

## Project Overview

This project implements a hand gesture recognition system based on a Convolutional Neural Network (CNN). The model is trained to classify hand gestures representing numbers from NONE to FIVE by analyzing images of hands.

The core of the system is a CNN trained on a custom dataset for robust and accurate gesture classification.

***

## Dataset

- **Training images:** 300  
- **Validation images:** 60  
- **Classes:** NONE, ONE, TWO, THREE, FOUR, FIVE  
- The dataset consists of labeled images captured for each gesture class.

***

## Training Details

- **Batch size:** 8  
- **Epochs:** 25  
- **Steps per epoch:** 37  
- **Validation steps:** 7  

These parameters were used to train the CNN model to optimize performance on the gesture classification task.

***

## Usage

1. Clone the repository:  
   ```
   git clone <repository-url>
   ```

2. Install the required dependencies:  
   ```
   pip install -r requirements.txt
   ```

3. Run the classification script to predict hand gestures on new images:  
   ```
   python classify_gesture.py
   ```

***

## Project Structure

- `model.h5` — Trained CNN model for gesture classification.  
- `classify_gesture.py` — Script that loads the model and classifies input images.  
- `Dataset/` — Training and validation images used for model training.  
- `README.md` — This documentation.  
- *(Bonus)* `opencv_hand_gesture.py` — Optional OpenCV code demonstrating real-time gesture recognition using computer vision techniques.

***

## Dependencies

- Python 3.x  
- Keras with TensorFlow backend  
- NumPy  
- Other Python packages as listed in `requirements.txt`

***



***

This README clearly highlights the CNN-based gesture recognition as the primary focus while mentioning the OpenCV-based real-time gesture code as an additional bonus feature.
