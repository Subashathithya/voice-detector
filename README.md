# 🎙️ Voice Emotion Detector

This project detects **human emotions** (like happy, sad, angry, etc.) from **voice input** using machine learning. It uses audio feature extraction with `librosa`, a classifier model (e.g., Random Forest), and a simple UI with Streamlit or Gradio.

---

##  Features

- Input voice recordings (RAVDESS dataset or microphone)
-  Extract MFCC features using `librosa`
-  Predict emotions using trained ML model
-  Display waveform and prediction in UI

---

##  Tech Stack

| Tool       | Use                               |
|------------|------------------------------------|
| Python     | Programming language               |
| Librosa    | Audio feature extraction (MFCC)    |
| Scikit-learn | Machine learning model (Random Forest / SVM) |
| Streamlit / Gradio | User Interface (optional)  |
| RAVDESS     | Dataset for training/testing      |

---

## 🗃 Dataset

- RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
- Download: [RAVDESS on Kaggle](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

---

##  How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/voice-emotion-detector.git
cd voice-emotion-detector
