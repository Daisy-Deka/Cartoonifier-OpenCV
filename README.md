# 🎨 High Quality Image Cartoonifier using OpenCV

## 📘 Project Overview
This project converts a normal image into a high-quality cartoon style using OpenCV.  
It uses bilateral filtering, adaptive threshold edge detection, and noise reduction techniques to generate smooth and sharp cartoon outputs.  

This beginner-friendly project runs perfectly on Google Colab or any Python environment and does **not** require a webcam.

---

## 🧰 Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab (optional)

---

## ✨ Features
- High-quality cartoon-like output  
- Supports JPG, JPEG, PNG images  
- Fast execution with visually appealing results  
- Uses advanced bilateral filtering and edge detection  

---

## 🧪 Working Principle
| Step | Method Used | Purpose |
|------|-------------|---------|
| 1️⃣ | Bilateral Filtering | Smoothens image colors |
| 2️⃣ | Convert to Gray + Median Blur | Reduces noise |
| 3️⃣ | Adaptive Thresholding | Extracts edges |
| 4️⃣ | Bitwise Combine | Merges edges with smooth colors |

---

## 🚀 How to Run
1. Open `cartoonify.ipynb` in Google Colab or run the Python script locally.  
2. Upload an input image when prompted.  
3. Run all cells sequentially.  
4. The cartoonified image will be displayed and saved as `high_quality_cartoon.jpg`.

---

## 📂 Project Structure
📁 Cartoonifier-Project
├─ 📜 README.md
├─ 📜 cartoonify.ipynb
├─ 🖼️ high_quality_cartoon.jpg (output)

print("✔ Cartoon image saved as: high_quality_cartoon.jpg")
