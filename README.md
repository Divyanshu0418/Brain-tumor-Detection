#  Brain Tumor Detection using CNN and Data Augmentation

This repository contains code and models for detecting brain tumors from MRI images using Convolutional Neural Networks (CNN). The project also demonstrates the importance of data augmentation to improve model generalization and performance.

## Project Structure
 Brain-Tumor-Detection
├── Brain_tumour_detection.ipynb # CNN model for classification
├── Augmentation.ipynb # Image augmentation techniques
├── dataset/ #  Directory for MRI images
├── saved_model/ # Trained model weights
└── README.md # Project documentation

##  Project Description

### Brain Tumor Detection
- Utilizes a custom CNN model to classify MRI scans as **tumor** or **no tumor**.
- Trained on labeled MRI image datasets (e.g., from Kaggle or other open sources).
- Includes preprocessing, model architecture, training, and evaluation steps.

### Data Augmentation
- Demonstrates techniques like rotation, flipping, zooming, brightness changes, etc.
- Helps in increasing dataset diversity to reduce overfitting.
- Uses libraries such as `TensorFlow`, `Keras`, and `imgaug`.

---

##  Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy / OpenCV
- Matplotlib / Seaborn
- Jupyter Notebook
