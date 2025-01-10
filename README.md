# YoloV9

detect.py modification,

# Screen
python detect.py --source screen --img 640 --device 0 --weights './yolov9-m-converted.pt' --name yolov9_c_c_640_detect

# Camera 
python detect.py --source 0 --img 640 --device 0 --weights './yolov9-m-converted.pt' --name yolov9_c_c_640_detect

# Image 
python detect.py --source something.mp4 --img 640 --device 0 --weights './yolov9-m-converted.pt' --name yolov9_c_c_640_detect
