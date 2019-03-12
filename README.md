# tensorflow2.0-yolo3

# Quick Start
- Download YOLOv3 weights from YOLO website.
- Convert the Darknet YOLO model to a Keras model.

### Run YOLO detection.
```shell
wget https://pjreddie.com/media/files/yolov3.weights
python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
python yolo_video.py [OPTIONS...] --image, for image detection mode, OR
python yolo_video.py [video_path] [output_path (optional)]
```
