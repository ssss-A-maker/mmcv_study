# mmcv_study
完整使用mmcv库进行代码训练的一个流程
一：数据集加载过程
（1）定义和注册数据集类

这边新建一个watermelon.py

在mmseg/datasets/_init_.py中


（2）pipeline配置文件
pipeline文件主要用于数据集路径以及其他设置的加载，尽量命名为xxxx_pipeline.py
(从这个入口进入)



在pipeline需要变的为（没要求的就默认）


二：开始配置configs文件
（1）创建放自己configs的文件夹，这样放置一个用来写configs，一个保存用于编译。



（2）


（三）开始训练

（输入指令开始运行）
（下面是使用一般情况进行代码运行）

下面两种测试方法选一个就可以


测试fps

（四）：进行数据可视化（用训练得到的模型测试图片）












