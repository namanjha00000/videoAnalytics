run the following commands in terminal to install the libraries:

```
pip install opencv-python
pip install easyocr
```

run the following command to download the yolov3.weights:
```
wget https://pjreddie.com/media/files/yolov3.weights
```

running the yolo.py will help give results of object detection and all objects mentioned in the coco.names list can be detected, with bounding box and object label.

running the ocr.py will help perform optical character recognition on the input video and create a boundig box around detected texts and place the next near the box
