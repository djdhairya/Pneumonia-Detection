# Pneumonia Detection

This project focuses on developing a deep learning model to detect pneumonia from chest X-ray images using the dataset provided by Paul Timothy Mooney on Kaggle. The model leverages the VGG19 architecture and is further fine-tuned for improved performance.

## Dataset

The dataset used for this project is available on Kaggle:

[Chest X-Ray Images (Pneumonia) Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

It comprises chest X-ray images categorized into 'PNEUMONIA' and 'NORMAL' classes, divided into training, validation, and test sets.

## Installation

To set up the project environment:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/djdhairya/Pneumonia-Detection.git
   cd pneumonia-detection
   ```

2. **Install Required Packages**:

   ```bash
   pip install -r requirements.txt
   ```

## Libraries Used 📚

- **TensorFlow / Keras** – For building and training the CNN model.
- **NumPy** – For numerical computations.
- **Pandas** – For data handling and preprocessing.
- **Matplotlib** – For visualizing training history and results.
- **Seaborn** – For creating advanced visualizations.
- **scikit-learn** – For data splitting, evaluation metrics, and confusion matrix.
- **OpenCV** – For image processing (optional based on usage).
- **Flask** – For deploying the model as a web application.
- **Gunicorn** – WSGI server (optional for deployment).
- **Werkzeug** – Used in backend routing (via Flask).
- **Pillow (PIL)** – For image manipulation in Python.

---

## Usage

1. **Train the Model**:

   - Run the Jupyter notebook files provided to preprocess the dataset and train the model.
   - Model weights will be saved in the `model_weights/` directory.

2. **Run the Web Application**:

   - Start the Flask server:

     ```bash
     python app.py
     ```

   - Open the browser and navigate to `http://127.0.0.1:5000/` to upload chest X-ray images and get predictions.

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License.

![Screenshot 2025-03-24 233532](https://github.com/user-attachments/assets/4f866448-cbdd-4438-a50c-3a83b718e180)

