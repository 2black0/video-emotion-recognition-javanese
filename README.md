# 🎭 Video Emotion Recognition for Javanese Dataset

This project implements a video-based emotion recognition system specifically for **Javanese speakers**, focusing on facial expression analysis. It uses custom datasets of recorded video samples to detect and classify emotional states.

---

## 📁 Project Structure

```
.
├── code
│   ├── data.csv                        # Metadata and labels
│   ├── emotion-recognition.ipynb       # Main notebook for training/inference
│   └── output
│       ├── *_output.mp4                # Annotated videos with predicted emotions
│       └── images.zip                  # Extracted frames from video (optional)
├── dataset
│   ├── person-01.zip to person-10.zip  # Compressed raw video data per actor
├── LICENSE                             # License file
└── README.md                           # This file
```

---

## 🎯 Objective

The aim of this project is to detect **emotional expressions** from short video clips of Javanese individuals using deep learning-based facial recognition and classification techniques. It helps bridge the gap in **emotion recognition research** for underrepresented languages and cultures.

---

## 🧠 Features

* 🧍 Emotion classification using facial expressions from video
* 🎥 Custom video dataset (Javanese actors)
* 📊 CSV-based label management (`data.csv`)
* 📈 Model evaluation via accuracy and confusion matrix
* 🎬 Video annotation with prediction overlays

---

## 🗃️ Dataset Format

Each video file follows the naming pattern: `aa-bb-cc-dd.mp4`

| Segment | Description           |
| ------- | --------------------- |
| `aa`    | Actor ID (01–10)      |
| `bb`    | Sentence ID (01–04)   |
| `cc`    | Emotion Code (01–06)  |
| `dd`    | Repetition ID (01–07) |

### Emotion Label Codes:

| Code | Emotion   | Description |
| ---- | --------- | ----------- |
| 01   | Neutral   | Biasa       |
| 02   | Sadness   | Susah       |
| 03   | Happiness | Seneng      |
| 04   | Surprise  | Kaget       |
| 05   | Fear      | Wedi        |
| 06   | Anger     | Nesu        |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/javanese-video-emotion-recognition.git
cd javanese-video-emotion-recognition
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open and execute `code/emotion-recognition.ipynb` to:

* Load video data
* Extract facial features
* Predict emotions
* Annotate and save output videos

---

## 🛠 Technologies Used

* Python 3.9+
* OpenCV
* scikit-learn
* NumPy, pandas
* TensorFlow / Keras (for model training, optional)

> 📌 Model training steps may be included or adapted depending on your `emotion-recognition.ipynb`.

---

## 📂 Outputs

Annotated results are saved in:

```
code/output/
├── *_output.mp4    # Videos with predicted emotion labels
└── images.zip      # Optional: extracted frame images
```

---

## 🧑‍💻 Contributors

* [2black0](https://github.com/2black0) – Developer, Dataset creator

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Feedback & Citation

If you use this project or dataset in your research or teaching, please cite or mention it in your work. For questions, feel free to open an issue or contact the author via GitHub.

---