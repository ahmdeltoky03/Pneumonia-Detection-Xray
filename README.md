# Pneumonia-Detection-Xray

### Project Details

This project is designed to assist in detecting pneumonia from chest X-ray images using deep learning. The model is trained on a dataset of labeled X-ray images and can classify whether an image is normal or shows signs of pneumonia. It is deployed using Flask, providing a user-friendly web interface for image uploads and predictions.

## Dataset

The dataset used for training the model can be found on Kaggle:
 [Chest X-Ray Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data)
This project is designed to assist in detecting pneumonia from chest X-ray images using deep learning. The model is trained on a dataset of labeled X-ray images and can classify whether an image is normal or shows signs of pneumonia. It is deployed using Flask, providing a user-friendly web interface for image uploads and predictions.

## Installation

### Prerequisites
Make sure you have the following installed:
- Python (>=3.7)
- Flask
- TensorFlow/Keras (for model inference)
- OpenCV, PIL (for image processing)
- NumPy, Pandas

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmdeltoky03/Pneumonia-Detection-Xray
   cd Pneumonia-Detection-Xray
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the trained model in the project directory (ensure the filename matches the one used in your Flask app).

## Running the Application

1. Start the Flask server:
   ```bash
   python app.py
   ```

2. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## Project Structure
```
.
├── static/
│   ├── styles.css
│   └── uploaded_images/
├── templates/
│   ├── index.html
├── model/
│   ├── vgg19_model_03.h5
├── app.py
├── requirements.txt
├── README.md
```

## Usage
1. Upload a chest X-ray image.
2. Click "Predict" to process the image.
3. The application will classify the image and display the result (Normal/Pneumonia).

## License
This project is open-source and available for educational and research purposes.

## Contact
For any queries, contact [Your Name] at [your email].

