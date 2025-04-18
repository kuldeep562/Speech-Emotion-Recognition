# 🎙️ Speech Emotion Recognition - Sound Classification

This project focuses on recognizing human emotions from speech audio using machine learning and deep learning techniques. It combines multiple datasets and extracts meaningful features to classify emotions like happy, sad, angry, and more.

---

## 📌 Project Summary

The goal is to build a model that can identify the emotional tone of a speaker based on audio input. This can be useful in applications like virtual assistants, call center analytics, and mental health monitoring.

---

## 🧠 What’s Inside

- 📁 **Jupyter Notebook**: All code is in `SER_model.ipynb`
- 🧪 Feature extraction using **MFCCs** via `librosa`
- 🧠 LSTM-based deep learning model using **Keras**
- 📊 Accuracy tracking and result visualization

---

## 📂 Folder Structure

```
speech-emotion-recognition/
│
├── SER_model.ipynb        # Main notebook
├── requirements.txt       # Python dependencies
├── README.md              # You’re here!
└── data/
    └── README.md          # Dataset download instructions
```

---

## 🎧 Datasets Used

This project uses two popular emotional speech datasets:

1. **RAVDESS** - [Zenodo Link](https://zenodo.org/record/1188976)
2. **TESS** - [University of Toronto](https://tspace.library.utoronto.ca/handle/1807/24487)

Download links and instructions are provided inside `data/README.md`.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/speech-emotion-recognition.git
   cd speech-emotion-recognition
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download datasets as per `data/README.md` and place them in the `data/` folder.

4. Launch the notebook:
   ```bash
   jupyter notebook SER_model.ipynb
   ```

5. Run all cells in order to train the model and view results.

---

## 📈 Sample Output

- Emotion classification accuracy
- Training vs validation plots
- Spectrogram and MFCC visualizations of audio samples

---

## 💡 Future Improvements

- Add real-time emotion prediction from microphone input
- Experiment with CNN architectures
- Hyperparameter tuning for improved accuracy
