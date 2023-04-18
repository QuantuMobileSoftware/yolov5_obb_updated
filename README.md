# Yolov5 for Oriented Object Detection
![图片](./docs/detection.png)
![train_batch0.jpg](./docs/train_batch6.jpg)
![results.png](./docs/results.png)

# Results and Models
The results on **DOTA_subsize1024_gap200_rate1.0** test-dev set are shown in the table below. (**password: yolo**)

 |Model<br><sup>(download link) |Size<br><sup>(pixels) | TTA<br><sup>(multi-scale/<br>rotate testing) | OBB mAP<sup>test<br><sup>0.5<br>DOTAv1.0 | OBB mAP<sup>test<br><sup>0.5<br>DOTAv1.5 | OBB mAP<sup>test<br><sup>0.5<br>DOTAv2.0 | Speed<br><sup>CPU b1<br>(ms)|Speed<br><sup>2080Ti b1<br>(ms) |Speed<br><sup>2080Ti b16<br>(ms) |params<br><sup>(M) |FLOPs<br><sup>@640 (B) 
 | ----                                                                                                                                                           | ---  | ---   | ---      | ---   | ---   | ---   | ---   | --- | --- | ---
 |yolov5m [[baidu](https://pan.baidu.com/s/1UPNaMuQ_gNce9167FZx8-w)/[google](https://drive.google.com/file/d/1NMgxcN98cmBg9_nVK4axxqfiq4pYh-as/view?usp=sharing)]  |1024  | ×     |**77.3** |**73.2** |**58.0**  |**328.2**      |**16.9**     |**11.3**      |**21.6**   |**50.5**   
 |yolov5s [[baidu](https://pan.baidu.com/s/1Lqw42xlSZxZn-2gNniBpmw?pwd=yolo)]    |1024  | ×     |**76.8**   |-      |-      |-      |**15.6**  | -     |**7.5**     |**17.5**    
 |yolov5n [[baidu](https://pan.baidu.com/s/1Lqw42xlSZxZn-2gNniBpmw?pwd=yolo)]    |1024  | ×     |**73.3**   |-      |-      |-      |**15.2**  | -     |**2.0**     |**5.0**

# Getting Started
[The tutorial for setting environment, data preparation, and training Yolov5_obb model](https://i7y.org/en/yolov5-with-oriented-bounding-box/)<br />
[The data annotation tutorial](https://i7y.org/en/oriented-bounding-box-annotation/)<br />
https://github.com/chinakook/labelImg2 - oriented box annotation tool 

