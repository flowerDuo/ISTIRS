[English](https://github.com/flowerDuo/ISTIRS/blob/main/README.md) | 中文 

# 无人机农田热红外遥感图像拼接软件

* 此为用于无人机热红外遥感图像拼接的软件， 软件界面简洁， 功能丰富， 易于操作。
* 软件荣获“华为杯”第二届中国研究生人工智能创新大赛 三等奖。

## 下载

* 软件下载地址： 链接：https://pan.baidu.com/s/1tHy-X8XmXdL3fa7fCF37FA <br/>
  	提取码：msne   <br/>

* 数据集下载地址：链接：https://pan.baidu.com/s/18IPa8ngPdkXrlCSEwhpdAQ <br/>
   提取码：imxv <br/>
  * 注：提供的数据集无人机飞行参数：无人机飞行高度：120 m，相机像元大小：17 µm。图像划分网格大小建议为 40x40。

## 软件使用流程

创建或打开要拼接的遥感图像集 >> 设置拼接相关参数 >> 软件自动进行串行拼接 >> 返回拼接结果图像以及重要的拼接信息 >> 查看拼接结果 

## 软件功能

 - 在软件中可以在无人机飞行路径上对图像进行操作。用户可以宏观把握无人机所采集遥感图像的方位、大小和飞行路线等信息，并且还可以选择感兴趣区域进行拼接。
 - 针对专业人员研究的需求，开发的软件可以单次设置多个图像拼接任务，并为每一个项目设置不同的拼接参数，自动进行串行拼接。
 - 软件会缓存已创建的项目、已设置的参数和历史拼接结果等数据，保证用户使用起来方便、快捷。
 - 软件会缓存重要的拼接过程数据，方便科研人员进行相关工作。
 - 软件提供中、英两个版本。
 - 软件内附有详细使用说明文档。

## 运行结果展示

* 结果对比

  <table>
    <tr>
      <th>Pix4Dmapper</th>
      <th>PTGui</th> 
      <th>AutoStitch</th>
    </tr>
    <tr>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Pix4Dmapper.png"/></td>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/PTGui.png"/></td> 
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/AutoStitch.png"/></td>
    </tr>
  </table>


  <table>
    <tr>
      <th>GSP</th>
      <th>Our</th> 
    </tr>
    <tr>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/GSP.png"/></td>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Ours.png"/></td> 
    </tr>
  </table>

* 调试数据

  <table>
    <tr>
      <th>某对图像特征点对</th>
      <th>某张图像变形结果</th> 
      <th>某张图像线段提取结果</th>
    </tr>
    <tr>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Ransac_pair.jpg"/></td>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Single_wrap.png"/></td> 
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/line-result.jpg"/></td>
    </tr>
  </table>


  <table>
    <tr>
      <th>边框</th>
      <th>网格</th> 
    </tr>
    <tr>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/f01-%5BOP_GSP_Border%5D.png"/></td>
      <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/f01-%5BOP_GSP_Mesh%5D.png"/></td> 
    </tr>
  </table>

## 软件部分截图

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image004.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image008.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image024.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image025.gif"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/CH/image027.gif"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/CH/image029.gif"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/CH/image034.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/CH/image036.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/CH/image042.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image038.png"/></td>
  </tr>
</table>

## 算法支持

软件使用最新提出的图像拼接方法(OP-GSP)  为软件的图像拼接功能提供核心支持。算法在图像畸变以及错位方面均优于 AutoStitch(IJCV 2007)，同时比原始 NISwGSP(ECCV 2016)图像对齐能力和鲁棒性更强。 论文已发表于IEEE Jstars。

* 论文：Jiguang Cui, Man Liu, Zhitao Zhang, Shuqin Yang, Jifeng Ning*. Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap Prior Based Global Similarity Prior Model, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing （IEEE Jstars）. vol. 14, pp. 270-282, 2021.

* 论文链接：https://doi.org/10.1109/JSTARS.2020.3032011

## 引用

 如果您使用我们工作中的任何软件或数据，请引用我们的论文。

* J. Cui, M. Liu, Z. Zhang, S. Yang and J. Ning, "Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap-Prior-Based Global Similarity Prior Model," in *IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing*, vol. 14, pp. 270-282, 2021, doi: 10.1109/JSTARS.2020.3032011.

* ```
  @ARTICLE{9229104,
    author={J. {Cui} and M. {Liu} and Z. {Zhang} and S. {Yang} and J. {Ning}},
    journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
    title={Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap-Prior-Based Global Similarity Prior Model}, 
    year={2021},
    volume={14},
    number={},
    pages={270-282},
    doi={10.1109/JSTARS.2020.3032011}}
  ```

## 开发团队

西北农林科技大学 农业水文遥感研究组

## 联系我们

如果有什么问题，请联系我们吧！

njf@nwsuaf.edu.cn <br/> zhitaozhang@126.com 

## 版权与声明
* 本项目软件与数据集仅用于学术交流，如感兴趣，请联系我们！
* 转载或引用本网站内容以及软件，请注明此网址：https://github.com/flowerDuo/ISTIRS
