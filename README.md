<h1 align="center">Hi 👋, I'm Sahil Parmar</h1>
<h3 align="center">A passionate Electronic Engineer from India, VLSI Enthusiast & AI Developer</h3>


## 📡 Connect with Me:
<p align="left">
<a href="https://dev.to/sahil_parmar_31" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="sahil_parmar_31" height="30" width="40" /></a>
<a href="https://instagram.com/s_a_h_i_l_31" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="s_a_h_i_l_31" height="30" width="40" /></a>
<a href="https://www.leetcode.com/sahilparmar31" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/leet-code.svg" alt="sahilparmar31" height="30" width="40" /></a>
</p>
<a href="https://www.linkedin.com/in/sahil-parmar-a16377237/" target="blank">
  <img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="sahil-parmar" height="30" width="40" />
</a>


# YOLO12 with Gemini 2.0 – Vehicle Detection  

This repository contains an advanced vehicle detection system combining **YOLOv12** with **Gemini 2.0** to enhance accuracy and efficiency in real-time object detection. The model is optimized for identifying vehicles in various environments, including urban streets, highways, and parking areas.

## 🚀 Features  
- **YOLOv12 Integration**: Utilizes the latest YOLO architecture for fast and precise vehicle detection.  
- **Gemini 2.0 AI Enhancement**: Leverages Google’s Gemini 2.0 for improved contextual understanding and post-processing.  
- **Real-Time Detection**: Processes live video streams and images efficiently.  
- **Multi-Class Detection**: Recognizes cars, trucks, buses, motorcycles, and more.  
- **Optimized Performance**: Supports edge computing and cloud deployment.  
- **Dataset Support**: Trained on large-scale vehicle datasets for high accuracy.  

## 📌 Installation  
```bash
git clone https://github.com/your-username/YOLO12-with-Gemini2.0-Vehicle-Detection.git  
cd YOLO12-with-Gemini2.0-Vehicle-Detection  
pip install -r requirements.txt  
```

## 📷 Usage  
```python
python test2.py --source my.mp4 --weights yolo12n.pt --device 0
```

## 🏗️ Model Training  
1. Prepare the dataset (COCO format recommended).  
2. Train the model using `train.py` with appropriate hyperparameters.  

## 📊 Results  
- Achieves **high mAP scores** on benchmark datasets.  
- Efficiently detects vehicles in **low-light** and **occluded** conditions.  
- **Reduced false positives** due to Gemini 2.0 post-processing.  

## 📂 Repository Structure  
- **test2/** – Detects cars on wide roads.  
- **check/** – Detects vehicles on one side of the road.  
- **vehicle_data.txt** – Stores detected vehicle details (type, count, time, location).  
- **JPG/** – Contains cropped images of detected cars.  

## 📜 License  
This project is open-source under the **MIT License**.  
