# 🪨📄✂️ Rock Paper Scissors Classifier  

A real-time **Rock-Paper-Scissors** classifier built using **TensorFlow.js** and **MobileNet** for **transfer learning**. It uses a webcam to collect hand gesture samples, trains a custom model, and classifies gestures live.

## 📌 Features
- Uses **MobileNet** as the base model for transfer learning.
- Train the classifier in the browser using **TensorFlow.js**.
- Classify hand gestures into **Rock, Paper, or Scissors**.
- Live predictions with webcam input.
- Simple UI with styled buttons and live feedback.

---

## 📁 Project Structure
```
📂 rock-paper-scissors-classifier
│── 📜 index.html          # Main HTML file with UI and script links
│── 📜 index.js            # JavaScript logic for classification
│── 📜 rps-dataset.js      # Data handling and preprocessing
│── 📜 webcam.js           # Webcam integration
│── 📜 README.md           # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/ashpakshaikh26732/rock-paper-scissor.git
cd rock-paper-scissor
```

### 2️⃣ Open the Project  
Simply open `index.html` in your browser. Since it's a client-side **TensorFlow.js** app, no server setup is needed.

---

## 🛠 How It Works  
1. **MobileNet as Base Model**  
   - The model **loads MobileNet**, a lightweight deep learning model trained on ImageNet.  
   - The top layers of MobileNet are **removed**, and new layers are added to classify **Rock, Paper, or Scissors**.  

2. **Training with Your Webcam**  
   - Click **Rock, Paper, or Scissors** multiple times to collect training samples.  
   - Click **Train Network** to train the classifier using **transfer learning**.  

3. **Real-time Predictions**  
   - Click **Start Predicting** to see real-time classifications.  
   - Click **Stop Predicting** to stop the model.  

---

## 📌 Dependencies
- [TensorFlow.js](https://www.tensorflow.org/js) (for ML in the browser)
- [MobileNet](https://arxiv.org/abs/1704.04861) (pre-trained model)
- A webcam for real-time predictions.

---

## 💡 Future Improvements
- Save and load trained models.
- Improve accuracy with **data augmentation**.
- Deploy as a web app for easy access.

---

## 🤝 Contributing
Feel free to **fork this repo**, open a pull request, or submit issues for improvements!

---

## 📜 License
This project is **open-source** under the MIT License.

---

### 🌟 Show Some Love!
If you found this project useful, **star the repo** ⭐ and share it! 🚀
