# Food-Recognition-and-Calorie-Estimation-Using-YOLOV5-and-TensorFlow
# 🍽️ Food Recognition and Calorie Estimation using YOLOv5 & TensorFlow



---

## 📌 Table of Contents
- [About](#-about)
- [Key Features](#-key-features)
- [Demo](#-demo)
- [Technologies](#-technologies)
- [Dataset](#-dataset)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Future Work](#-future-work)
- [References](#-references)
- [Contributors](#-contributors)
- [License](#-license)

---

## 🚀 About
Obesity and diet-related diseases are rising globally. This project leverages **YOLOv5** (for real-time food detection) and **TensorFlow** (for calorie estimation) to help users track their dietary intake accurately.  

**Why this project?**  
✅ **High Accuracy**: Precision (0.962) & Recall (0.942) in multi-food detection.  
✅ **User-Friendly**: Web interface for easy uploads and instant results.  
✅ **Scalable**: Handles complex dishes with overlapping ingredients.  

---

## ✨ Key Features
- **Multi-Food Detection**: Identifies multiple items in a single image (e.g., salad components).  
- **Calorie Estimation**: Maps detected foods to calorie values.  
- **Web Interface**: Upload images via Flask-based UI.  
- **Optimized Models**: Uses YOLOv5 (speed) + MobileNet (lightweight classification).  
- **Data Augmentation**: Improved robustness with rotations/flips.  

---

## 📸 Demo
| Web Interface | YOLOv5 Detection |
|--------------|------------------|
| ![Web Demo](media/image8.png) | ![Bounding Boxes](media/image3.png) |

---

## 🛠 Technologies
- **Backend**: Python, TensorFlow, Keras, YOLOv5, OpenCV  
- **Frontend**: Flask, HTML/CSS  
- **Tools**: Roboflow (dataset), MobileNet (lightweight CNN)  

---

## 📂 Dataset
We combined two datasets:  
1. **Roboflow Food Segmentation**  
   - 3,496 images (36 classes like `tomato`, `onion`).  
   - Annotated for YOLOv5 ([Link](https://universe.roboflow.com/college-gg4mu/food-image-segmentation-using-yolov5/dataset/1)).  
2. **Food101 (Kaggle)**  
   - 10,000 images (10 classes).  

---

## ⚙ Installation
```bash
# Clone repo
git clone https://github.com/your-username/food-recognition.git
cd food-recognition

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
