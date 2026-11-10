基于深度学习YOLOV11渣土车篷布覆盖检测系统  渣土车盖顶覆盖情况检测数据集，2112张，提供yolo，voc，coco三种标注方式![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8664eb5bf6304ac1bb8364ecf4c2aefe.png)

图像尺寸:640*640
类别数量:3类![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/52830ab214fa411ba32b85acd502c237.png)

训练集图像数量:875; 验证集图像数量:622； 测试集图像数量:615
类别名称: 每一类图像数 ，每一类标注数![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/63fd8bf5f2484b3a80b75f68a4a074c3.png)

In-progress 未覆盖 180,252
Half covered 半覆盖 250,250
Completed 已完工 |1602,1610
image num: 2112


模型代码
采用 YOLOv11n 网络训练
训练轮次：80 个 epoch
提供全部训练 + 测试源代码
训练精度 mAP 效果如图所示![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/7656520e1aba4d44971493e9ec96917a.png)

PyQt5 界面功能![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b08957d3c49b4718ab8fd037b7059bde.png)

界面使用 PyQt5 开发，提供全部源码（.ui、.qrc、.py 及图标文件）
支持图片检测、视频检测、摄像头实时检测
界面实时显示：目标位置、目标总数、置信度等信息
支持检测结果保存导出![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/2415745ddac349b39415b2d7e6364ab9.png)

操作简单直观，无需命令行
4、
运行环境：Python=3.8、opencv-python、PyQt5、torch
支持 Windows、Linux 系统
