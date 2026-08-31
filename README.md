# Deep Learning Based Fake Video Detection

## 📌 Project Overview

This project detects whether a video is **real or fake (deepfake)** using deep learning techniques.

The system extracts facial features from video frames and uses a deep learning model to classify the video as real or fake.

## 🛠️ Technologies Used

* Python
* Google Colab
* PyTorch
* OpenCV
* NumPy
* Pandas
* MTCNN
* ResNeXt50
* LSTM
* Deep Learning

## 📂 Dataset

The project uses the **Celeb-DF v2** dataset.

A subset of the dataset was used for this project, consisting of real and fake videos. Frames were extracted from the videos and facial regions were detected using MTCNN.

## 🔄 Project Workflow

1. Load real and fake videos
2. Extract frames from videos
3. Detect faces using MTCNN
4. Resize and preprocess face images
5. Extract features using pretrained ResNeXt50
6. Pass extracted features to an LSTM model
7. Train the model
8. Classify videos as real or fake

## 🧠 Model

A pretrained **ResNeXt50** model is used as a feature extractor.

The extracted features are then passed to an **LSTM (Long Short-Term Memory)** network for sequence-based classification.

## 📓 Notebook

The complete implementation is available in the Google Colab notebook:

`Deepfake-Detection.ipynb`

## 🚀 How to Run

1. Open the `.ipynb` notebook in Google Colab.
2. Upload or connect the required dataset.
3. Install the required Python libraries.
4. Run the notebook cells in order.
5. Provide a video according to the notebook's input requirements.
6. The model predicts whether the video is real or fake.

## 👩‍💻 Author

Amrutha Indukuri
