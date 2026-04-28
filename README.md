# 🚗 Automatic Number Plate Detection System

## 📌 Overview
This project is a **Computer Vision and Image Processing-based Automatic Number Plate Detection (ANPD) system** built using Python. It detects vehicle license plates from images and extracts the plate number using Optical Character Recognition (OCR).

The system also identifies the **state/region** of the vehicle based on the registration code, making it useful for applications like traffic monitoring, surveillance, and smart city solutions.

---

## ⚙️ Features
- Detects number plates using Haar Cascade Classifier  
- Performs image preprocessing for better OCR accuracy  
- Extracts text using Tesseract OCR  
- Identifies Indian state from registration number  
- Displays detected plate and annotated image  
- Saves processed output image  

---

## 🛠️ Tech Stack
- **Python**
- **OpenCV (cv2)** – Image processing & detection  
- **NumPy** – Array operations  
- **Tesseract OCR** – Text extraction  
- **Google Colab (cv2_imshow)** – Visualization  

---

## 🧩 How It Works
1. Load the input image  
2. Convert image to grayscale  
3. Detect number plate using Haar Cascade  
4. Crop the detected plate region  
5. Apply preprocessing:
   - Dilation & Erosion  
   - Thresholding  
6. Extract text using OCR  
7. Clean and format detected text  
8. Map state code to region  
9. Display and save results  

---

## 📂 Project Structure
