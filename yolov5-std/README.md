#The deep learning model (YOLOv5-STD) is designed for small targets detection in remote sensing images..  
#Compared with YOLOv5 anchor frames, YOLOv5-STD has an extra set of small selection boxes, which is sensitive to small objects in fish processing factories images.The improved models can be found in "yolov5-std/models" folder.  
#The code of the YOLOv5-STD algorithm has been trained and tested using Windows 64-bit professional edition with a NVIDIA GeForce RTX 2080Ti (12G) GPU and an Intel Xeon 5218R CPU.The images object detection program was developed in pytorch1.7.  
#Structure of YOLOv5-STD is as follows:  
   
![Fig. 1](https://github.com/houmx666666/YOLOv5-STD/blob/main/Structure%20of%20YOLOv5-STD.jpg)

#Install  
cd YOLOv5-STD  
pip install -r requirements.txt

#Inference with detect.py  
python detect.py
