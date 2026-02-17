 Handwritten Digit Recognition using Deep Learning (MNIST)

Python
Keras
Tensor Flow
Numpy

 📌 What It Does

A deep learning model that recognizes handwritten digits (0–9) from images using a Neural Network trained on the MNIST dataset — one of the most widely used benchmarks in computer vision and machine learning.

This project demonstrates a complete ML pipeline: data loading, preprocessing, model building, training, and evaluation.



📊 Dataset — MNIST

| Property | Value |
|----------|-------|
| Training samples | 60,000 images |
| Test samples | 10,000 images |
| Image size | 28 × 28 pixels (grayscale) |
| Classes | 10 (digits 0–9) |
| Source | `keras.datasets.mnist` |



🧠 How It Works


Input Image (28×28 pixels)
        │
        ▼
  Flatten Layer (784 neurons)
        │
        ▼
  Dense Hidden Layer (ReLU activation)
        │
        ▼
  Output Layer (10 neurons — Softmax)
        │
        ▼
  Predicted Digit (0–9)


🛠️ Tech Stack

- Python — core implementation
- TensorFlow / Keras  — model building and training
- NumPy — data manipulation
- Matplotlib  — visualizing images and training results



 ▶️ How to Run

bash
git clone https://github.com/sandhyashreer23/mnist-digit-recognition
cd mnist-digit-recognition
pip install -r requirements.txt
jupyter notebook mnist_classification.ipynb


📁 Project Structure


mnist-digit-recognition/
├── mnist_classification.ipynb   # Main Jupyter notebook
├── requirements.txt             # Dependencies
├── results/                     # Accuracy plots, sample predictions
└── README.md


 📈 Results

- Model trained on 60,000 images
- Evaluated on 10,000 unseen test images
- Training and validation accuracy plotted across epochs
- Sample predictions visualized with true vs predicted labels



 💡 Key Concepts Demonstrated

- Loading and exploring datasets with Keras
- Image data preprocessing and normalization
- Building and compiling neural networks
- Model training with validation
- Evaluating classification performance
- Visualizing predictions with Matplotlib


## 🔗 Related Projects

- [Iris Recognition System — IEEE Published](https://github.com/sandhyashreer23/iris-recognition-fnn)
- [Visual-Inertial Odometry](https://github.com/sandhyashreer23/visual-inertial-odometry)
