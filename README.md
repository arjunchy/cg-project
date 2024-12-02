# cg-project
Object Measurement Using YOLOv3
A Flask-based web application for real-time object detection and measurement using the YOLOv3 model. Users can upload images to detect objects and see their real-world dimensions in centimeters. The output includes the input image with bounding boxes, labels, confidence scores, and size annotations.

Features
Object detection using YOLOv3.
Measurement of object dimensions in centimeters.
Simple and interactive web interface for image upload and result visualization.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/object-measurement-yolov3.git
cd object-measurement-yolov3
Install required dependencies:
bash
Copy code
pip install -r requirements.txt
Ensure yolov3.weights, yolov3.cfg, and coco.names are in the project directory.
Usage
Start the Flask application:
bash
Copy code
python app.py
Access the app at http://127.0.0.1:5000/ to upload images and view the results.
