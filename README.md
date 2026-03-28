# VisionScan: Document AI Pipeline 📄🔍

**Course:** Computer Vision (CSE3010)  
**Slot:** F11+F12  
**Interim Semester:** 2025-26  
**Class Number:** BL2025260500505  

**Name:** Abhi Pandey  
**Register Number:** 23BAI10909  
**Submitted to:** Dr. Amrita Parashar  
**Institution:** VIT Bhopal University  

---

### 📌 Project Overview
VisionScan is a CV pipeline that converts messy physical scans into clean, structured digital data. It solves **perspective distortion**, **noise**, and **manual categorization** issues using advanced image processing.

### 🛠️ The CV Pipeline (Step-by-Step)
1. **Preprocessing:** Grayscale & Bilateral Filtering (removes noise while keeping edges sharp).
2. **Segmentation:** **Canny Edge Detection** + **Contour Analysis** to find the document's boundary.
3. **Rectification:** **4-Point Perspective Transform** to "unwarp" the document into a flat view.
4. **Enhancement:** **Otsu’s Binarization** & Adaptive Thresholding for high-contrast text.
5. **Extraction & Classify:** **OCR** for text retrieval and layout analysis for document typing.

---

### 🚀 Results at a Glance
| 1. Input (Warped) | 2. Processed (Edges) | 3. Final Output (Scan) |
| :---: | :---: | :---: |
| ![Input](input_image.jpeg) | ![Threshold](pre_process_image.png) | ![Output](output_image.png) |

---

### 📂 Quick Links
* 💻 **[Core Logic (.ipynb)](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline/blob/main/VisionScan_An_Integrated_Document_Processing_%26_Classification_Pipeline%20(CODE).ipynb)**
* 📝 **[Project Report (PDF)](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline/blob/main/23BAI10909_ComputerVision_BYOP%20(Report).pdf.pdf)**

---

### ⚙️ Setup & Execution
```bash
# Clone & Install
git clone [https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline.git](https://github.com/Abhi4621/AbhiPandey-23BAI10909-VisionScan-CV-Pipeline.git)
pip install opencv-python numpy pytesseract matplotlib

# Run: Open the .ipynb file in Jupyter/Colab and "Run All"
