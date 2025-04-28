# Handwritten Digit Recognition Project

This project focuses on recognizing handwritten digits (0–9) using a K-Nearest Neighbors (KNN) classifier trained on a custom dataset.  
It allows users to draw a digit on a canvas and predicts the drawn digit using the trained model.

## 📂 Project Structure

- **Dataset**:
  - 28x28 pixel grayscale images.
  - Organized in folders named `0`, `1`, ..., `9`.
  - Approximately 999 images per digit.

- **Model**:
  - K-Nearest Neighbors (KNN) classifier.
  - Trained on the flattened pixel data.
  - Model is saved locally for future predictions.

- **User Interface**:
  - A simple canvas in Google Colab for users to draw digits.
  - Captures and preprocesses the drawing to match model input format.

## 🚀 How to Run
1. **Prepare the Dataset**:
   - (Provided in the repo)
   - Ensure images are in the correct folder structure (0–9).
   - Each image should be 28x28 pixels.

3. **Train the Model**:
   - Run the training code to fit the KNN model.
   - The model will be saved after training.

4. **Test the Model**:
   - Draw a digit on the canvas provided in the notebook.
   - The model will predict and display the drawn digit.

## 🛠 Technologies Used

- Python 3
- OpenCV
- NumPy
- Scikit-learn (KNeighborsClassifier)
- Google Colab

## 📋 Requirements

Install the following packages if running locally:

```bash
pip install opencv-python scikit-learn numpy matplotlib
