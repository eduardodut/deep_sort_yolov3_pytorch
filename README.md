# DEEP SORT YOLOV3 PYTORCH

目标检测：基于U版yolov3（版本比较早） https://github.com/ultralytics/yolov3 

ReID部分(维护中，测试过程还未完善)： https://github.com/pprp/reid_for_deepsort 

Deep SORT参考:  https://github.com/ZQPei/deep_sort_pytorch 

SORT参考： https://github.com/abewley/sort 

## 新特性

目标检测部分添加了常用的注意力模块CBAM, SE

添加了使用OpenCV进行目标跟踪的算法，第一帧使用YOLOv3进行检测。（在miniversion文件夹）

添加了SORT算法

完善ReID部分的训练