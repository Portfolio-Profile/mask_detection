# 😷 Face Mask Detection Using Deep Learning

This project is a deep learning-based solution for detecting whether a person is wearing a mask or not using image data. It uses a Convolutional Neural Network (CNN) model trained with TensorFlow and Keras.

---

## 🧠 Artificial Intelligence Used

- **Supervised Learning**: Classification
- **Deep Learning**: Convolutional Neural Network (CNN)
- **Frameworks**: TensorFlow, Keras

---

## 🛠️ Technologies & Libraries

- **Python 3.10**
- **TensorFlow & Keras** – for building and training the CNN model
- **OpenCV** – for image processing (optional for real-time detection)
- **Matplotlib** – for plotting graphs
- **NumPy** – for numerical operations
- **Pandas** – for data manipulation
- **Jupyter Notebook** – for code development and visualization

---

## 📌 Description of Key Files

- **`Mask_Detection.ipynb`**: Main notebook where the entire workflow is implemented – data loading, preprocessing, model training, and evaluation.
- **`mask_detector_model.keras`**: The saved model file after training, which can be loaded later for inference.
- **`.gitignore`**: Contains rules to ignore files like `kaggle.json`, checkpoints, or virtual environments.
- **`requirements.txt`** *(optional)*: If present, it lists all necessary Python libraries.

---

## 🚀 How to Clone and Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/Portfolio-Profile/mask_detection.git

pip install tensorflow keras matplotlib numpy pandas opencv-python
jupyter notebook Mask_Detection.ipynb
