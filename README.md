# Persian Alphabet Recognition 📚✨

Welcome to the **Persian Alphabet Recognition** project! This repository
implements a robust system for classifying 43 Persian alphabet
characters using two neural network models: a fully connected network
and a convolutional neural network (CNN). 🚀

## 📖 Overview

This project processes image datasets, trains two neural network models,
evaluates their performance, and visualizes results. It includes data
preprocessing, model training, ROC/AUC analysis, and real-world image
classification. 🖼️🔍

## 🌟 Features

-   **Data Preprocessing** 🛠️: Loads and preprocesses images (64x64,
    normalized, inverted) using a custom `DataLoader` class.
-   **Model 1** 🧠: Fully connected neural network with dense layers
    (2048 to 64 units, ReLU, softmax).
-   **Model 2** 🌐: CNN with Conv2D, BatchNormalization, MaxPooling, and
    Dropout layers.
-   **Training** 📈: Both models trained for 20 epochs using Adam
    optimizer and sparse categorical crossentropy loss.
-   **Evaluation** 📊: ROC curves, AUC scores, and accuracy/loss plots
    for performance analysis.
-   **Visualization** 🎨: Displays sample images, predictions, and
    real-world test results using Matplotlib.
-   **Real-World Testing** 🌍: Classifies preprocessed real-world images
    with both models.

## 🛠️ Requirements

-   Python 3.x 🐍
-   Keras
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn
-   OpenCV

## ⚙️ Installation

1.  Clone the repository:

    ``` bash
    git clone https://github.com/yourusername/persian-alphabet-recognition.git
    ```

2.  Install dependencies:

    ``` bash
    pip install -r requirements.txt
    ```

## 🚀 Usage

1.  Update dataset paths (`DATASET1`, `DATASET2`, `DATASET3`,
    `REAL_DATA`) in `alphabet_recognition.py`.

2.  Run the script:

    ``` bash
    python alphabet_recognition.py
    ```

## 📊 Results

-   **Model 1 Test Accuracy** ✅: Displayed in console output.
-   **Model 2 Test Accuracy** ✅: Displayed in console output.
-   Visualizations include:
    -   Training/validation accuracy and loss plots 📈
    -   ROC curves for each class 📉
    -   Sample test images with true/predicted labels 🖼️
    -   Real-world image predictions 🌍

## 📌 GitHub Topics

-   `machine-learning`
-   `deep-learning`
-   `neural-network`
-   `cnn`
-   `image-classification`
-   `persian-alphabet`
-   `keras`
-   `python`
-   `computer-vision`
-   `data-science`

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for
details. 📝

## 🙌 Contributing

Contributions are welcome! Feel free to open issues or submit pull
requests to improve the project. 🤝

## 📧 Contact

For questions or feedback, reach out via GitHub Issues or email at
your.email@example.com. 📬
