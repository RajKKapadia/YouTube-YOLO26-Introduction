Single File
```bash
uv run yolo predict model=yolo26n.pt source="https://ultralytics.com/images/bus.jpg" project=outputs name=yolo26_demo save=True
```

Webcam
```bash
uv run yolo predict model=yolo26n.pt source=0 show=True project=webcam_out name=yolo26_cam exist_ok=True
```