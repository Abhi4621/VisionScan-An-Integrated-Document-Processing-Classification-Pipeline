# VisionScan: Document AI Pipeline 📄🔍

**Course:** Computer Vision (CSE3010)  
**Slot:** F11+F12  
**Interim Semester:** 2025-26  
**Class Number:** BL2025260500505  

**Author:** Abhi Pandey  
**Register Number:** 23BAI10909  
**Submitted to:** Dr. Amrita Parashar  
**Institution:** VIT Bhopal University  

---
### 📌 Project Overview
VisionScan automates document digitization by solving **perspective distortion**, **noise**, and **manual categorization** through advanced image processing.

### 🛠️ CV Pipeline Flow
* **Step 1: Preprocessing** – Grayscale & Bilateral Filtering for noise reduction.
* **Step 2: Segmentation** – **Canny Edge Detection** + **Contour Analysis** for boundary mapping.
* **Step 3: Rectification** – **4-Point Perspective Transform** to straighten warped images.
* **Step 4: Enhancement** – **Otsu’s Binarization** & Adaptive Thresholding for text clarity.
* **Step 5: Extraction** – **OCR** for text retrieval and automated layout classification.

---

### 🚀 Visual Results
| 1. Input (Warped) | 2. Processed (Edges) | 3. Final Output (Scan) |
| :---: | :---: | :---: |
| ![Input](input_image.jpeg) | ![Threshold](pre_process_image.png) | ![Output](output_image.png) |

---

### 📂 Quick Access
* 💻 **[Core Implementation (.ipynb)](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline/blob/main/VisionScan_An_Integrated_Document_Processing_%26_Classification_Pipeline%20(CODE).ipynb)**
* 📝 **[Project Report (PDF)](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline/blob/main/23BAI10909_ComputerVision_BYOP%20(Report).pdf.pdf)**

---

### ⚙️ Setup & Execution
```bash
# Clone Repository
git clone [https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline.git](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline.git)

# Install Dependencies
pip install opencv-python numpy pytesseract matplotlib

# Execution: Open .ipynb in Jupyter/Colab and "Run All"
