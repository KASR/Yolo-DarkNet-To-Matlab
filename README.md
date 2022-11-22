![RUNOOB icon](https://github.com/cuixing158/yolov3-yolov4-matlab/blob/master/images/importerExporter.png)<br>
![RUNOOB icon](https://github.com/cuixing158/yolov3-yolov4-matlab/blob/master/images/yolov4Detect.jpg)<br>
![RUNOOB icon](https://github.com/cuixing158/yolov3-yolov4-matlab/blob/master/images/dogYolov4Detect.jpg)<br>

# yoloV3/yolov4 to matlab
This respository uses simplified and minimal code to reproduce the yolov3 / yolov4 detection networks and darknet classification networks. The highlights are as follows:<br>
- Support original version of darknet model<br>
- Support training, inference, import and export of "* .cfg", "* .weights" models<br>
- Support the latest [yolov3, yolov4](https://github.com/AlexeyAB/darknet) models<br>
- Support darknet classification model<br>
- Support all kinds of indicators such as feature map size calculation, flops calculation and so on.<br>

---

These code is highly readable and more brief than other frameworks such as pytorch and tensorflow!<br>
But it does not contain various training data augmentation tricks!<br>

# Requirements
Matlab R2020a or higher,the newer the better,no other dependencies!!!

# How to use
Use train.m for training, detect.m and demo.mlx for inference testing<br>
