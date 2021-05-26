# YOLOv5-ShuffleNetV2


## 1. YOLOv5-MobileNetV3

MobileNetV3 Large 

MobileNetV3 Small

## 2. YOLOv5-ShuffleNetV2

ShuffleNetV2

ShuffleNetV2-Focus

ShuffleNetV2-stem（Pelee stem）


```

python train.py  --batch 64 --epochs 300 --data data/coco128.yaml --cfg  models/yolov5-mobilenetv3small.yaml 
```
```
models
├── yolov5-mobilenetv3large.yaml
├── yolov5-mobilenetv3small.yaml
├── yolov5-shufflenetv2-focus.yaml
├── yolov5-shufflenetv2-stem.yaml
├── yolov5-shufflenetv2.yaml
```
