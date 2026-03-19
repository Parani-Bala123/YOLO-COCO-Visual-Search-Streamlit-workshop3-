#  YOLO COCO Visual Search Web App

##  1. Project Title
**Real-Time Object Detection & Visual Search using YOLO (COCO) with Streamlit**

---

##  2. Abstract / Introduction
This project implements a **real-time object detection and visual search system** using the YOLO (You Only Look Once) deep learning model trained on the COCO dataset.

The application allows users to:
- Upload images
- Detect objects in real time
- Perform visual search based on detected objects
- View results in an interactive Streamlit web interface

The system is designed to be **fast, accurate, and user-friendly**, suitable for applications like surveillance, e-commerce, and AI-based search systems.

---

##  3. Dataset & YOLO Model Details (COCO)

- **Dataset:** COCO (Common Objects in Context)
- **Total Classes:** 80
- **Examples:** Person, Car, Dog, Cat, Bottle, Chair

- **Model Used:** YOLOv8 / YOLOv11  
- **Framework:** PyTorch (Ultralytics)  
- **Weights:** Pretrained on COCO dataset  

---

##  4. Environment Setup

### Step 1: Install Anaconda / Miniconda  
https://www.anaconda.com/

### Step 2: Create Environment
```bash
conda create -n yolov11_Image_search python=3.10 -y
conda activate yolov11_Image_search
```
## GPU Installation Steps or CPU Installation Steps:
```
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
python -c "import torch; print(torch.cuda.is_available())"
```

## How to Run in VS Code using Conda:
  - open new terminal in vs code
```
conda activate yolov11_Image_Search
streamlit run app.py
```
<img width="1112" height="343" alt="image" src="https://github.com/user-attachments/assets/9936d714-ff48-4ca4-b11e-1f0dd93deb66" />

## 	How to Deploy using Streamlit:
```
streamlit run app.py
```
Or you can deploy in other platforms like netlify, vercel by uploading your project folder.

## OUTPUT:
<img width="1112" height="343" alt="image" src="https://github.com/user-attachments/assets/0818342f-852e-4a58-b48f-42b0b6d0b65b" />
<img width="1919" height="1047" alt="image" src="https://github.com/user-attachments/assets/21303038-58d0-4c5b-bfe9-27449cf5fa05" />
<img width="1890" height="1077" alt="image" src="https://github.com/user-attachments/assets/a40d7cdd-2e17-416c-bebf-ed224a2b22f1" />

## 	Enhancements / innovations added:
  - visual Search Feature
  - Real-time detection
  - Interactive UI with Streamlit
  - Object count display
  - Faster inference
  - Multi-image support
  - Efficient processing pipeline

## Results & Conclusion:
Thus, the YOLO image search using streamlit is executed successfully. This project successfully integrates YOLO deep learning model with a Streamlit web interface to build a real-time object detection and visual search system.
