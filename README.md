🚗 Lane Detection with YOLOv8 (Custom Model)
Deep learning–based lane detection using a custom‑trained YOLOv8 model.
Real‑time, robust, and scalable for autonomous driving pipelines.

🔍 Highlights
Custom Dataset: Annotated lane images for training YOLOv8.

Real‑Time Inference: ~30 FPS on GPU with high accuracy.

Robust Detection: Handles curves, intersections, and varying weather/lighting.

Easy Integration: Works with video streams, dashcams, or simulation data.

⚙️ Quick Start
bash
# Clone repo
git clone https://github.com/your-username/lane-detection-yolov8.git

cd lane-detection-yolov8

# Install dependencies
pip install -r requirements.txt

# Train model
yolo task=detect mode=train model=yolov8n.pt data=data.yaml epochs=50 imgsz=640

# Run inference
yolo task=detect mode=predict model=models/best.pt source=video.mp4
📊 Results
mAP@50 > 90% on custom dataset

Real‑time lane detection across diverse conditions

Sample outputs available in 
