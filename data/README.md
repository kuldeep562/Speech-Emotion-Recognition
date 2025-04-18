# 📁 Data Folder

This folder is intended to store the audio datasets used for the **Speech Emotion Recognition** project.

---

## 🎧 Datasets Used

### 1. **RAVDESS**  
**(Ryerson Audio-Visual Database of Emotional Speech and Song)**

- A high-quality, acted emotional speech dataset.
- Contains recordings of 24 actors speaking with various emotional tones (neutral, calm, happy, sad, angry, fearful, disgust, surprised).

🔗 **Download Link**:  
[RAVDESS on Zenodo](https://zenodo.org/record/1188976)

After downloading and extracting, the folder structure should look like:

```
data/
└── RAVDESS/
    └── Actor_01/
        ├── 03-01-01-01-01-01-01.wav
        └── ...
```

---

### 2. **TESS**  
**(Toronto Emotional Speech Set)**

- Voice recordings of two actresses (aged 26 and 64) speaking 200 target words with 7 emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
- Great for combining with RAVDESS for emotion classification tasks.

🔗 **Download Link**:  
[TESS Dataset - University of Toronto](https://tspace.library.utoronto.ca/handle/1807/24487)

After downloading and extracting, the folder structure should look like:

```
data/
└── TESS/
    ├── OAF_angry/
    ├── OAF_disgust/
    ├── OAF_fear/
    ├── OAF_happy/
    ├── OAF_neutral/
    ├── OAF_ps/
    ├── OAF_sad/
    └── ...
```

---

## 📌 Notes

- Place both `RAVDESS/` and `TESS/` inside this `data/` folder.
- Update your data loading paths in code to match this structure.
- Total combined dataset: ~3,000+ audio files across multiple emotions.

---
