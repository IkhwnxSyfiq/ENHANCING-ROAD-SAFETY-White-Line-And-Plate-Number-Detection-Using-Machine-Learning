# Enhancing Road Safety: White Line and Plate Number Detection powered by YOLOv8

This project focuses on ** Enhancing Road Safety** by detecting vehicles that stop beyond white lines and identifying offenders’ plate numbers using **YOLOv8** and **Pytesseract OCR**. It aims to support law enforcement (JPJ Malaysia) in monitoring traffic violations more effectively.

---

## 📌 Project Overview
- **Technology Used:** YOLOv8, Pytesseract OCR, Python, Roboflow  
- **Hardware:** Logitech C920 Pro HD Webcam, Acer Predator Gaming Laptop  
- **Dataset:** 1025 annotated Malaysian plate number images (split into Training 80%, Validation 10%, Testing 10%)  
- **Objective:**  
  - Detect vehicles crossing white lines.  
  - Recognise and extract plate numbers.  
  - Save violation records in `.txt` or `.csv` format for monitoring.  

---

## 🛠️ System Workflow
1. **Input:** Webcam captures vehicle crossing the stop line.  
2. **Processing:**  
   - YOLOv8 detects the plate number region.  
   - Image cropped and converted to grayscale.  
   - Pytesseract extracts text from the plate.  
3. **Output:** Plate number saved into a text file as evidence.  


**Flowchart**
- Collect & annotate dataset  
- Train YOLOv8 (150 epochs)  
- Validate & evaluate model  
- Real-time detection with webcam  

---

## 📊 Results
- **YOLOv8 Training:**  
  - Precision: ~99%  
  - Recall: ~94%  
  - mAP50: ~94.6%  
- **System Accuracy:** ~90% in real-time environment  
- **Limitations:**  
  - Requires a larger dataset for improved accuracy.  
  - Performance drops in adverse weather or low resolution.  

---

## 📷 Hardware Setup

Logitech C920 Pro HD Webcam – captures real-time traffic violations.

Acer Predator Laptop – model training & execution.

## 📌 Recommendations

Increase the dataset size for plate numbers across regions.

Implement faster algorithms for real-time detection in dense traffic.

Explore weather-adaptive detection models.

## 📖 References

YOLOv8 Documentation: Ultralytics

Pytesseract OCR: Tesseract Wiki

Dataset Annotation: Roboflow

## 👨‍💻 Author

Muhammad Ikhwan Syafiq Bin Norsham
Bachelor of Electronic Technology Engineering (Hons)
Universiti Kuala Lumpur, British Malaysian Institute

## 📧 Email: ikhwan.norsham@s.unikl.edu.my / ikhwansyafiq00@gmail.com

## 🙏 Acknowledgment

This project was conducted at Universiti Kuala Lumpur (UniKL BMI) with the guidance and supervision of Ts. Dr. Izanoordina Binti Ahmad and supported by UniKL BMI. 

