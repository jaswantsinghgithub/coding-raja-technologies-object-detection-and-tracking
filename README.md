# Object-Detection-YOLOv5-Python

## Watch the Video
![Alt text](https://github.com/atakhan27/Object-Detection-YOLOv5-Python/blob/main/yolov5-california.png)
https://drive.google.com/file/d/1KdvGyUdGHZbxNSEMxa0HOcB7ZpZn6rjv/view?usp=share_link

## Installation

### Step 1: Clone the YOLOv5 Repository
First, you need to clone the YOLOv5 repository from GitHub:
```console
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
```

### Step 2: Install Dependencies
Next, install the required dependencies by running:
```console
pip install -r requirements.txt
```

### Step 3: Run Object Detection on a Video Stream
To run object detection on a video stream (e.g., your webcam), execute the following command:
```console
python detect.py --source 0
```
Replace "0" with the index of your camera if you have multiple cameras connected to your system.

### Step 4: Run Object Detection on a Video File
To run object detection on a video file, provide the path to your video file as the source parameter:
```console
python detect.py --source /path/to/your/video/file.mp4
```
Replace "/path/to/your/video/file.mp4" with the actual path to your video file and ensure the file extension is correct (e.g., `.mp4`, `.avi`, `.mov`).

YOLOv5 will process the video stream or file and perform object detection on each frame. The output will be saved in the `runs/detect` directory by default.

That's it! You now have a working setup for YOLOv5 object detection on video streams and files. 🎉
