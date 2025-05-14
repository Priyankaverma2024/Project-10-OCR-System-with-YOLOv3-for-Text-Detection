# Project-10-OCR-System-with-YOLOv3-for-Text-Detection
# OCR Text Detection Using YOLOv3

## 🔍 Problem Statement
Build an OCR system to detect and localize text in images using a custom-trained YOLOv3 object detection model.

## 🎯 Objectives
- Preprocess and resize images
- Annotate data in YOLO format
- Train YOLOv3 on labeled dataset
- Evaluate the model with mAP and IOU
- Prepare for future deployment

## 📁 Dataset
- Custom dataset with text images
- Resized to 416×416
- YOLO format annotations created using LabelImg

## 🛠️ Steps Performed
1. Mount Google Drive and load dataset
2. Resize all images to target size
3. Generate empty YOLO `.txt` files
4. Annotate using LabelImg
5. Train YOLOv3 model
6. Evaluate and visualize results

## structure 
/content/drive/MyDrive/OCR_Project_dataset/thyrocare_dataset/
 thyrocare_dataset/
├── images/
│   ├── train/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   ├── val/
│       ├── image81.jpg
│       ├── image82.jpg
├── labels/
│   ├── train/
│   │   ├── image1.txt
│   │   ├── image2.txt
│   ├── val/
│       ├── image81.txt
│       ├── image82.txt
├── dataset.yaml  

## 📌 Future Enhancements
- Add OCR text recognition
- Improve dataset size and diversity
- Try YOLOv5 / YOLOv8 for better accuracy
- Build Streamlit dashboard for deployment


