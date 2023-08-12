# face-gaze-estimation-opencv-dnn
使用OpenCV部署L2CS-Net人脸朝向估计，包含C++和Python两个版本的程序，只依赖opencv库就可以运行。
本套程序，先用yolov8face做人脸检测，在检测到人脸之后crop出人脸区域，输入到L2CS-Net库做人脸的朝向估计。
人脸检测器，可以自己的喜好，选择使用，不一定要使用yolov8face。

L2CS-Net的训练源码在 https://github.com/Ahmednull/L2CS-Net

onnx文件在百度云盘，下载链接：https://pan.baidu.com/s/1r3rPRCM8AjNk_eLEOnVDzw?pwd=to14 
提取码：to14
