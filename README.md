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
```
python train.py --data coco.yaml --cfg mobilenetv3small-stem.yaml --weights  '' --batch-size 16 --img-size 640  --epoch 300
result:
Model: YOLOv5 (mobilenetv3small-stem.yaml) version
Dataset: COCO
parameters: 1.4M
FLOPS: 0.8G
mAP@.5: 0.301 
P: 0.521       
R: 0.288 
```
