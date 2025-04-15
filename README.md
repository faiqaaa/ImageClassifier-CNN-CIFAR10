# CNN Image Classifier using CIFAR-10 Dataset

This project demonstrates how to build and train a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

---

## 📂 Project Structure

- `load_data.py` – Load CIFAR-10 dataset
- `preprocess.py` – Normalize images and one-hot encode labels
- `model.py` – Build and compile the CNN model
- `train.py` – Train the model and evaluate accuracy
- `predict.py` – Test the model on new data (optional)

---

## 📊 Dataset

**CIFAR-10**: 60,000 32x32 color images in 10 classes, with 6,000 images per class.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib (for visualization)

---

## 🚀 How to Run

```bash
git clone https://github.com/yourusername/cnn-cifar10-image-classifier.git
cd cnn-cifar10-image-classifier
python train.py

