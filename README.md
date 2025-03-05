# YOLOv10n Object Detection Project

## 📚 Introduction
This project focuses on real-time object detection using YOLOv10n, a lightweight variant of YOLOv10. The goal was to detect cars and license plates efficiently, prioritizing model speed and size over extreme accuracy. Despite its smaller size, YOLOv10n performed well in identifying objects, making it ideal for edge devices or real-time applications.

## 🏎️ Project Overview
- **Model:** YOLOv10n
- **Dataset:** Custom dataset with car and license plate images/videos
- **Tools:** Python, Ultralytics YOLO library, Kaggle Notebooks
- **Purpose:** Explore real-time object detection for autonomous driving and smart surveillance

## 🚀 Results
Below are examples of the detection results:

### 📸 Image Results
![Car Detection](https://github.com/HanaNabhan/Car-Plate-Detection/blob/main/result_image.png)

### 🎥 Video Results
![License Plate Detection](https://github.com/HanaNabhan/Car-Plate-Detection/blob/main/result_video.gif)


## 📈 Model Performance
- **Precision:** 0.903
- **Recall:** 0.735
- **mAP@0.5:** 0.851
- **mAP@0.5:0.95:** 0.496
- **Epochs** 90/90

The YOLOv10n model was selected for its speed and efficiency, trading off some accuracy for reduced computational cost.

## 🔧 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/YOLOv10n-Object-Detection.git
   cd YOLOv10n-Object-Detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run predictions:
   ```bash
   yolo task=detect mode=predict conf=0.25 save=True model='runs/detect/train2/weights/best.pt' source='path/to/your_image_or_video'
   ```

## 🏁 Conclusion
Through this project, YOLOv10n demonstrated its effectiveness in real-time object detection, accurately identifying cars and license plates. While the model's accuracy was not as high as larger variants, its lightweight nature made it suitable for real-time applications, such as autonomous driving and smart surveillance. Future work may include fine-tuning the model, expanding the dataset, or deploying the detection system in a live environment.

## 📬 Contact
- **Name:** Hana Nabhan  
- **GitHub:** [Hana Nabhan](https://github.com/HanaNabhan)  
- **LinkedIn:** [Hana Nabhan](https://www.linkedin.com/in/hana-nabhan/)

---
Feel free to contribute or raise any issues!

