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



## 代码注释

完整讲解《Deep SORT多目标跟踪算法代码解析》在GiantPandaCV公众号首发，欢迎关注。

主要提供了deep_sort文件夹中绝大部分代码的注释，以下是根据代码绘制的类图结构：

![DeepSort](README.assets/DeepSort.jpg)

状态转移：

 ![状态转换图](README.assets/20200415100437671.png) 

整体框架：

 ![图片来自知乎Harlek](README.assets/20200412221106751.png) 

流程图：

 ![知乎@猫弟总结的deep sort流程图](README.assets/2020041418343015.png) 