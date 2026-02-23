# MenWomanPrediction

👦👧 Gender Classification (Male vs Female)

A deep learning project that classifies whether a person in an image is male or female using a Convolutional Neural Network (CNN).

Developed with TensorFlow and trained on labeled face images.

📌 Project Overview

This project applies a CNN model to a binary image classification task:

0 → Female

1 → Male

The CNN model identifies patterns in facial characteristics and makes predictions on unseen images.

📊 Dataset

The dataset is a collection of JPG face images.

Because of size constraints, the dataset is not included in this repository.

🔗 Dataset Link:
(Paste your dataset link here)

🧠 Model Architecture

Image resizing

Normalization (pixel values scaled to 0-1)

Convolutional layers (CNN)

MaxPooling layers

Dense layers

Final layer:

Dense(1, activation='sigmoid')

⚙️ Train / Test Split
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
X, y,
test_size=0.2,
random_state=42
)
📈 Model Performance

Training Accuracy: 0.6467

Mean absolute error: 0.3533

Loss Function: Binary Crossentropy

(Replace these numbers with your final real results)
