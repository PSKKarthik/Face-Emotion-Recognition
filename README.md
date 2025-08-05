# 🎭 Face Emotion Recognition

<div align="center">
    <a href="https://github.com/PSKKarthik/Face-Emotion-Recognition/stargazers"><img src="https://img.shields.io/github/stars/PSKKarthik/Face-Emotion-Recognition?style=for-the-badge&logo=github&color=FFC107" alt="Stars Badge"/></a>
    <a href="https://github.com/PSKKarthik/Face-Emotion-Recognition/network/members"><img src="https://img.shields.io/github/forks/PSKKarthik/Face-Emotion-Recognition?style=for-the-badge&logo=github&color=4CAF50" alt="Forks Badge"/></a>
    <a href="https://github.com/PSKKarthik/Face-Emotion-Recognition/blob/main/LICENSE"><img src="https://img.shields.io/github/license/PSKKarthik/Face-Emotion-Recognition?style=for-the-badge&color=00BCD4" alt="License Badge"/></a>
</div>

<br>

<p align="center">
  <img src="https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/assets/banner.png" alt="Project Banner" width="800"/>
</p>

A deep learning project that detects and classifies human emotions from facial images in real-time. This model uses a powerful Convolutional Neural Network (CNN) to recognize 7 distinct emotions with high accuracy.

---

### ✨ Key Features

* ✅ **Real-Time Detection:** Analyzes webcam feeds or video streams to detect emotions on the fly.
* ✅ **7-Class Emotion Classification:** Accurately identifies **Angry, Disgust, Fear, Happy, Neutral, Sad,** and **Surprise**.
* ✅ **High Accuracy Model:** Built with a deep CNN architecture trained on a diverse facial expression dataset.
* ✅ **Interactive Notebook:** Comes with a Jupyter Notebook for easy experimentation and visualization.

---

### 💻 Tech Stack

The core of this project is built with the following technologies:

| Python | TensorFlow | Keras | OpenCV | Jupyter |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40"/> | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" width="40"/> | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/Keras_logo.svg/1200px-Keras_logo.svg.png" alt="Keras" width="40"/> | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" alt="OpenCV" width="40"/> | <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="Jupyter" width="40"/> |

---

### 🖼️ Example Results

Here are some sample detections from the model.

<div align="center">

| Angry | Happy | Sad | Surprise |
|:---:|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/test/angry/PrivateTest_10131363.jpg" width="150"> | <img src="https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/test/happy/PrivateTest_10131363.jpg" width="150"> | <img src="https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/test/sad/PrivateTest_10131363.jpg" width="150"> | <img src="https://raw.githubusercontent.com/PSKKarthik/Face-Emotion-Recognition/main/test/surprise/PrivateTest_10131363.jpg" width="150"> |

</div>

---

### 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/PSKKarthik/Face-Emotion-Recognition.git](https://github.com/PSKKarthik/Face-Emotion-Recognition.git)
    cd Face-Emotion-Recognition
    ```
2.  **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```
3.  **Run the notebook:**
    ```sh
    jupyter notebook FaceEmotionRecognition.ipynb
    ```

---

### 📁 Project Structure
<details>
<summary>Click to view the project structure</summary>

```
├── emotiondetector.h5          # Trained model weights
├── emotiondetector.json        # Model architecture
├── facialemotionmodel.h5       # Alternative model weights
├── facialemotionmodel.json     # Alternative model architecture
├── FaceEmotionRecognition.ipynb # Main Jupyter notebook for analysis and testing
├── requirements.txt            # Python dependencies
├── test/                         # Test images organized by emotion
│   ├── angry/
│   ├── disgust/
│   ├── fear/
│   ├── happy/
│   ├── neutral/
│   ├── sad/
│   └── surprise/
├── train/                        # Training images organized by emotion
│   ├── ... (similar structure to test/)
└── README.md                     # You are here!
```
</details>

---

### ⭐ Show Your Support

If you find this project useful or interesting, please consider giving it a star ⭐! Your support helps motivate me to continue developing and sharing open-source tools.

### 🙌 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change. Let's make this tool even better together.

---

### 📧 Contact

**Polisetty Sai Krishna Karthik** - [GitHub](https://github.com/PSKKarthik) - [LinkedIn](https://linkedin.com/in/pskk)

<br>
<div align="center">
  Made with ❤️ and a passion for AI.
</div>
