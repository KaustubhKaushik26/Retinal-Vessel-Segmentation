# Retinal Vessel Segmentation using U-Net

This project implements a U-Net-based deep learning model to perform **segmentation of blood vessels** in retinal images. Accurate vessel segmentation is essential for early detection and diagnosis of various retinal diseases such as diabetic retinopathy, glaucoma, and age-related macular degeneration.

## 🧠 Model: U-Net

U-Net is a convolutional neural network architecture designed for biomedical image segmentation. It consists of a contracting path (encoder) and an expansive path (decoder) with skip connections to maintain high-resolution features.

## 📁 Dataset

- **DRIVE Dataset** (Digital Retinal Images for Vessel Extraction)
- Contains high-resolution retinal images along with manually labeled masks for vessel regions.
- [Dataset Link](https://drive.grand-challenge.org/)

## 📌 Features

- Preprocessing steps: grayscale conversion, CLAHE enhancement, resizing.
- Training and validation split of dataset.
- Model trained using binary cross-entropy loss.

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy, OpenCV, Matplotlib
- Google Colab for training

## 🧪 Training and Results

- Epochs: 400
- Optimizer: Adam
- Loss: Binary Cross-Entropy
- Achieved high segmentation accuracy with clear vessel delineation.
- Training Loss : 0.058 & Training Accuracy : 99.02 %

### Sample Output

![U-Net Model Output](output/U-Net%20Model%20Output.png)


## 📝 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/retinal-vessel-segmentation-unet.git
   cd retinal-vessel-segmentation-unet
