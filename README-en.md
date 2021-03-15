[中文](https://github.com/flowerDuo/ISTIRS/blob/main/README.md)  | English

# Image Stitching for UAV Thermal Infrared Remote Sensing

* This software is used for UAV thermal infrared remote sensing image stitching. The software is simple in UI, rich in functions and easy to operate.
* The software won the third prize in the second "Huawei Cup" China Postgraduate Artificial Intelligence Innovation Competition.

## Download

* Software Download： URL：https://pan.baidu.com/s/1tHy-X8XmXdL3fa7fCF37FA <br/>
  										Password：msne

* Data set：URL：https://pan.baidu.com/s/18IPa8ngPdkXrlCSEwhpdAQ <br/>
            Password：imxv 
  * Note: The UAV flight parameters of this data set : UAV altitude: 120 m, Camera pixel size: 17 µm. The recommended image grid size: 40x40 .

## Guide

Creates or opens a set of remote sensing images to be stitched  >> Setting parameters >> Working >> Return the result and important information >> Viewing the result

## Software function

 - The software allows you to manipulate images on the flight path. Users can macroscopically grasp the orientation, size and flight path of the remote sensing images collected by the UAV, and users can also select the area of interest for stitching.
 - According to the research needs of professionals, the software developed can set multiple image stitching tasks at a single time, and set different stitching parameters for each project, and automatically carry out stitching serially .
 - The software will cache the data，such as the created project, the set parameters and the historical stitching results. So as to ensure the user to use it conveniently and quickly。
 - The software will cache the important data of the splicing process, which is convenient for researchers to carry out related work.
 - The software is available in both Chinese and English versions.
 - Detailed instructions are attached to the software.

## Result

* Compare

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

* Debug

  <table>
      <tr>
        <th>Features</th>
        <th>Deformation of a single image</th> 
        <th>Line Data</th>
      </tr>
      <tr>
        <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Ransac_pair.jpg"/></td>
        <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/Single_wrap.png"/></td> 
        <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/line-result.jpg"/></td>
      </tr>
    </table>

    <table>
      <tr>
        <th>Border</th>
        <th>Mesh</th> 
      </tr>
      <tr>
        <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/f01-%5BOP_GSP_Border%5D.png"/></td>
        <td width="33%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/datas/f01-%5BOP_GSP_Mesh%5D.png"/></td> 
      </tr>
    </table>

## Part of the software screenshot

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image007.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image019.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image023.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image026.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image027.gif"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image029.gif"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image034.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image036.png"/></td>
  </tr>
</table>

<table>
  <tr>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image036.png"/></td>
    <td width="45%"><img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image038.png"/></td>
  </tr>
</table>

## Algorithm 

The newly proposed image stitching method (OP-GSP) is used to provide the core support for the image stitching function of the software. The algorithm is superior to AutoStitch(IJCV 2007) in image distortion and misalignment, and has better alignment and robustness than the original NISwGSP(ECCV 2016). The paper has been published in IEEE JSTARS.

* Paper：Jiguang Cui, Man Liu, Zhitao Zhang, Shuqin Yang, Jifeng Ning*. Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap Prior Based Global Similarity Prior Model, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing （IEEE Jstars）. vol. 14, pp. 270-282, 2021.

* URL：https://doi.org/10.1109/JSTARS.2020.3032011

## Citation

If you use any software or data from our work, please cite our paper.

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

## Team

Northwest A&F University - Agricultural Hydrological Remote Sensing Research Group

## Contact us

Feel free to contact us if there is any question!

njf@nwsuaf.edu.cn <br/> zhitaozhang@126.com 

## Statement
* The software and data set of this project are only used for academic research, do not use for commercial purposes!
* To reprint or quote the content of this website and software , please indicate this website address:https://github.com/flowerDuo/ISTIRS
* This software and the core algorithm has applied for software copyright, please use legally!
