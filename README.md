中文 | [English](https://github.com/alibaba/kiwi/blob/master/README-en.md)

# 无人机农田热红外遥感图像拼接软件

此为用于无人机热红外遥感图像拼接的软件， 软件界面简洁， 功能丰富， 易于操作。<br/>
软件荣获“华为杯”第二届中国研究生人工智能创新大赛 三等奖。

软件下载地址： 链接：https://pan.baidu.com/s/1tHy-X8XmXdL3fa7fCF37FA <br/>
							提取码：msne

## 软件使用流程

创建或打开要拼接的遥感图像集 >> 设置拼接相关参数 >> 软件自动进行串行拼接 >> 返回拼接结果图像以及重要的拼接信息 >> 查看拼接结果 

## 软件功能

 - 在软件中可以在无人机飞行路径上对图像进行操作。用户可以宏观把握无人机所采集遥感图像的方位、大小和飞行路线等信息，并且还可以选择感兴趣区域进行拼接。
 - 针对专业人员研究的需求，开发的软件可以单次设置多个图像拼接任务，并为每一个项目设置不同的拼接参数，自动进行串行拼接。
 - 软件会缓存已创建的项目、已设置的参数和历史拼接结果等数据，保证用户使用起来方便、快捷。
 - 软件会缓存重要的拼接过程数据，方便科研人员进行相关工作。
 - 软件提供中、英两个版本。
 - 软件内附有详细使用说明文档。

## 软件部分截图

<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image004.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image008.png" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image024.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image025.gif" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image027.gif" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image029.gif" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image036.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image038.png" width="250" /> &nbsp;

## 算法支持

软件使用最新提出的图像拼接方法(OP-GSP)  为软件的图像拼接功能提供核心支持。算法在图像畸变以及错位方面均优于 AutoStitch，同时比原始 GSP 图像对齐能力和鲁棒性更强。 论文已发表于IEEE Jstars。

论文：Jiguang Cui, Man Liu, Zhitao Zhang, Shuqin Yang, Jifeng Ning*. Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap Prior Based Global Similarity Prior Model, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing （IEEE Jstars）. vol. 14, pp. 270-282, 2021.

论文链接：https://doi.org/10.1109/JSTARS.2020.3032011

## 数据集

我们提供大量的农田热红外遥感图像数据供用户体验、测试。

数据集下载地址：链接：https://pan.baidu.com/s/18IPa8ngPdkXrlCSEwhpdAQ <br/>
							  提取码：imxv <br/>
注：提供的数据集无人机飞行参数：无人机飞行高度：120 m，相机像元大小：17 µm。图像划分网格大小建议为 40x40。

## 开发团队

西北农林科技大学 农业水文遥感研究组

## 联系我们

njf@nwsuaf.edu.cn <br/> zhitaozhang@126.com 

