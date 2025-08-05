
# Face Emotion Recognition

![Project Banner](https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/assets/banner.png)

## 🚀 Overview

Face Emotion Recognition is a deep learning project that detects and classifies human emotions from facial images. It uses a convolutional neural network (CNN) trained on a diverse dataset to recognize emotions such as Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

---

## 📦 Project Structure

```
├── emotiondetector.h5           # Trained model weights
├── emotiondetector.json         # Model architecture
├── facialemotionmodel.h5        # Alternative model weights
├── facialemotionmodel.json      # Alternative model architecture
├── FaceEmotionRecognition.ipynb # Main Jupyter notebook
├── requirements.txt             # Python dependencies
├── test/                        # Test images by emotion
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
├── train/                       # Training images by emotion
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
└── README.md                    # Project documentation
```

---

## 🖼️ Example Results

| Angry | Happy | Sad | Surprise |
|-------|-------|-----|----------|
| ![](test/angry/PrivateTest_10131363.jpg) | ![](test/happy/PrivateTest_10131363.jpg) | ![](test/sad/PrivateTest_10131363.jpg) | ![](test/surprise/PrivateTest_10131363.jpg) |

---

## 🛠️ Installation

1. Clone the repository:
   ```powershell
   git clone https://github.com/PSKKarthik/Face-Emotion-Recognition.git
   ```
2. Install dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```powershell
   jupyter notebook FaceEmotionRecognition.ipynb
   ```

---

## 🤖 Model Details

- **Architecture:** Convolutional Neural Network (CNN)
- **Framework:** Keras, TensorFlow
- **Classes:** Angry, Disgust, Fear, Happy, Neutral, Sad, Surprise

---

## 📊 Dataset

- Images are organized by emotion in `train/` and `test/` folders.
- Each folder contains real-world facial images for robust training and evaluation.

---

## 💡 Usage

- Load the model and run predictions on new images.
- Visualize results directly in the notebook.

---

## 🌟 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

For questions or feedback, reach out to [PSKKarthik](https://github.com/PSKKarthik).

---

## 🏆 License

This project is licensed under the MIT License.

---

> **Made with ❤️ by PSKKarthik**
