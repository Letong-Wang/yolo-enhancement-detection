# YOLO Enhancement Detection

This project focuses on enhancing object detection in low-light conditions using lightweight image enhancement techniques. It utilizes YOLOv8 for object detection and applies image enhancement methods like CLAHE and Gamma correction.

## Features
Image enhancement using CLAHE and Gamma correction
YOLOv8 model for object detection
Trained on the ExDark and BDD100K-Night datasets
Performance comparison using Precision, Recall, and mAP@0.5

## Installation
Clone the repository:
git clone https://github.com/Letong-Wang/yolo-enhancement-detection.git
cd yolo-enhancement-detection

Install required dependencies:
pip install -r requirements.txt

## Usage
To run object detection on an image:
from ultralytics import YOLO
model = YOLO('path_to_trained_model.pt')
results = model.predict('path_to_image.jpg', save=True)

## Results
Trained on the ExDark and BDD100K-Night datasets.
Achieved improved detection performance with lightweight image enhancement techniques.

## License
This project is licensed under the MIT License.
