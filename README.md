this is shrimp counter made with yolov4 and tensorflow with dataset taken from factories on the conveyor belt.
to run the file please download the variables folder and all the files before running
to run the video in the data folder:

shrimp-counter:
python detectvideo_counter.py --weights ./checkpoints/yolov4-416 --framework tf --size 416 --video ./data/video/shrimps.mp4
please use this code.
