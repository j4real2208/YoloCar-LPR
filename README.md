# YoloCar-LPR
 Detecting the Car Plate number using YoloV3
## PreReq 
- Python v3
- Model weight :- `https://drive.google.com/file/d/1kMAjPHsxz-AMdDZWSV-g5R0MpE5c7_9P/view?usp=sharing`
## Description 

- This project is a light wight license plate recognition model build on `YOLOv3 ` and `Tesseract OCR`.
- This model allows us to detect the plates with accuracy upwards of 90%. Post which it runs the OCR engine to produce meaningful numerical value.

## Commands to run the model 
- For an image: python object_detection_yolo.py --image=bird.jpg
-  For a video:  python object_detection_yolo.py --video=cars.mp4

---
## Output

![ ](https://github.com/j4real2208/YoloCar-LPR/blob/main/OutPut-Images/out_proc.png)
