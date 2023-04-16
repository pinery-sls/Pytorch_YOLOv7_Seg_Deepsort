# Pytorch_YOLOv7_seg_Deepsort
 YOLOv7_seg and Deepsort



![demo](demo_yolov7_seg_deepsort.gif)

## Download
### Deepsort
Download [ckpt.t7](https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6) and copy to deep_sort_pytorch/deep_sort/deep/checkpoint/

### YOLOv7_Seg
Downlod Yolov7_seg model and copy to yolov7/weights/

|Model |
| ------ |
|[YOLOv7-seg](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-seg.pt))|
|[YOLOv7x-seg](https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7x-seg.pt)|

## Tracking sources

Tracking can be run on most video formats

```bash
python3 track_seg.py --source ... --show-vid  # show live inference results as well
```

- Video:  `--source file.mp4`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa`
- HTTP stream:  `--source http://wmccpinetop.axiscam.net/mjpg/video.mjpg`
