

## 🏘️ Informal Settlement Mapping using Object Detection (Synthetic Data)

This project simulates the detection of informal settlements from satellite imagery using a pixel-wise object detection approach with a **Random Forest classifier** trained on synthetic rectangular "building" features.

---

### 📌 Overview

* **Objective**: Detect informal settlements in urban regions using machine learning and synthetic imagery.
* **Approach**: Synthetic satellite-like image with rectangular patches representing informal buildings. ML model is trained to classify pixels as "settlement" or "non-settlement."
* **Technique**: Random Forest classifier on RGB pixel values.

---

### 🧪 Data

* **Input**: Simulated 200×200 RGB image
* **Labels**: Pixels inside synthetic rectangles = 1 (settlement), others = 0
* **Output**: Excel file with RGB values, labels, and predicted classes

---

### 🛠️ How to Run

1. Install dependencies:

```bash
pip install numpy pandas matplotlib opencv-python scikit-learn openpyxl
```

2. Run the script:

```bash
python informal_settlement_mapping.py
```

3. Output file:

```
informal_settlement_detection.xlsx
```

---

### 📊 Output Description

The Excel file contains:

* `Red`, `Green`, `Blue`: RGB values of each pixel
* `Label`: True class (1 = settlement, 0 = background)
* `Predicted`: Model prediction

---

### 📁 Files

* `informal_settlement_mapping.py` – Main script
* `informal_settlement_detection.xlsx` – Output data

---

### 👤 Author

**Ifunanya Blessing**
Remote Sensing | Urban Analytics | AI for Sustainability
🔗 [LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)

