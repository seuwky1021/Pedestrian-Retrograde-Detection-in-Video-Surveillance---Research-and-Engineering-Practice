2022东南大学自动化学院19级-科研与工程实践
===========================

《视频监控中的逆行检测》
===========================

############小组成员

#SEU Automation#

08019118吴康宇

08119131许子轩

08119108周润林

指导教师：钱堃

特别鸣谢：孔维一

###########环境依赖
Python 3.7

Opencv3.4.3

Tensorflow2.0

###########目录结构描述
├── Readme.md                   // help
├── src                     // 源代码
│   ├── Optical Flow Method       //传统方法（光流法）
│   ├── YOLO Method                // Yolo方法（精检测方案二）
│   ├── Deep Learning Method         // 深度学习自编码器方法
├── dataset                 //数据集和采集原视频

│   ├── SCUT_HEAD_Part_A       //YOLO方法用数据集
│   ├── mydataset                // 深度学习方法用数据集

├── model.hdf5                 //深度学习方法神经网络模型

├── lib                         // 转换格式与视频测试用工具

├── results                         // 存放结果

│   ├── Optical Flow Method       //传统方法（光流法）结果
│   ├── YOLO Method                // Yolo方法（精检测方案二）结果
│   ├── Deep Learning Method         // 深度学习自编码器方法结果

├── image                       // 存放原理图





@Copyright 吴康宇# Pedestrian-Retrograde-Detection-in-Video-Surveillance---Research-and-Engineering-Practice
# Pedestrian-Retrograde-Detection-in-Video-Surveillance---Research-and-Engineering-Practice
# Pedestrian-Retrograde-Detection-in-Video-Surveillance---Research-and-Engineering-Practice
