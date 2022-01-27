# YoloCar-LPR
 Detecting the Car Plate number using YoloV3

## Description 

- This project is a light wight license plate recognition model build on `YOLOv3 ` and `Tesseract OCR`.
- This model allows us to detect the plates with accuracy upwards of 90%. Post which it runs the OCR engine to produce meaningful numerical value.

## Commands to run the model 
- For an image: python object_detection_yolo.py --image=bird.jpg
-  For a video:  python object_detection_yolo.py --video=cars.mp4