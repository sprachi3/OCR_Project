# 📄 Smart Document Scanner using OCR

## 📌 Overview

This project implements a **Printed Text Optical Character Recognition (OCR) system** that extracts text from images of documents using computer vision techniques. The system enhances image quality through preprocessing and evaluates OCR performance using a dataset.

---

## 🎯 Problem Statement

Extracting text manually from printed documents such as notes, invoices, and forms is time-consuming and inefficient. This project aims to automate text extraction using OCR while improving accuracy through image preprocessing techniques.

---

## 🚀 Features

* 📷 Image to text conversion
* 🧠 OCR using Tesseract
* 🖼️ Image preprocessing (grayscale, thresholding)
* 📊 Accuracy evaluation using dataset
* 📈 Comparison of preprocessing techniques
* 🔍 Bounding box visualization of detected text

---

## 🛠️ Tech Stack

* Python
* OpenCV
* Tesseract OCR
* Pytesseract
* Matplotlib
* Google Colab

---

## 📂 Project Structure

```
OCR_Project/
│
├── dataset/               # Dataset folder (images)
├── OCRproject_CV.ipynb    # Main implementation (Colab notebook)
├── sample_output/         # Output images/screenshots
├── report.pdf             # Project report
└── README.md              # Documentation
```

---

## ⚙️ How to Run

1. Open the notebook in Google Colab
2. Install dependencies:

```
!sudo apt install tesseract-ocr
!pip install pytesseract opencv-python matplotlib
```

3. Mount Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

4. Set dataset path:

```python
folder_path = "/content/drive/MyDrive/OCR_Project/dataset"
```

5. Run all cells to:

   * Process images
   * Extract text
   * Calculate accuracy
   * Generate graphs

---

## 🧠 Methodology

```
Input Image → Preprocessing → OCR → Text Output → Accuracy Evaluation
```

### 🔹 Preprocessing Techniques:

* Grayscale conversion
* Thresholding

### 🔹 OCR Engine:

* Tesseract OCR with custom configuration

---

## 📊 Results

* Improved OCR accuracy after preprocessing
* Thresholding performed better than raw images
* Visual confirmation using bounding boxes

---

## ⚠️ Challenges Faced

* Low-quality or noisy images reduced accuracy
* Dataset ground truth alignment issues
* OCR errors for complex fonts

---

## 🔮 Future Scope

* Handwritten text recognition
* Deep learning-based OCR models (CNN + RNN)
* Real-time document scanning application

---

## 👩‍💻 Author

Prachi Singh

---

## 📌 Conclusion

This project demonstrates how computer vision techniques can significantly improve OCR performance. By applying preprocessing and evaluating results on a dataset, we achieved a practical and effective document text extraction system.

---
