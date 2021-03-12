[中文](https://github.com/flowerDuo/ISTIRS/blob/main/README.md)  | English

# Image Stitching for UAV Thermal Infrared Remote Sensing

This software is used for UAV thermal infrared remote sensing image stitching. The software is simple in UI, rich in functions and easy to operate.<br/>
The software won the third prize in the second "Huawei Cup" China Postgraduate Artificial Intelligence Innovation Competition.

Software Download： URL：https://pan.baidu.com/s/1tHy-X8XmXdL3fa7fCF37FA <br/>
										Password：msne

## Guide

Creates or opens a set of remote sensing images to be stitched  >> Setting parameters >> Working >> Return the result and important information >> Viewing the result

## Software function

 - The software allows you to manipulate images on the flight path. Users can macroscopically grasp the orientation, size and flight path of the remote sensing images collected by the UAV, and users can also select the area of interest for stitching.
 - According to the research needs of professionals, the software developed can set multiple image stitching tasks at a single time, and set different stitching parameters for each project, and automatically carry out stitching serially .
 - The software will cache the data，such as the created project, the set parameters and the historical stitching results. So as to ensure the user to use it conveniently and quickly。
 - The software will cache the important data of the splicing process, which is convenient for researchers to carry out related work.
 - The software is available in both Chinese and English versions.
 - Detailed instructions are attached to the software.

## Part of the software screenshot

<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image004.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image008.png" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image024.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image025.gif" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image027.gif" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image029.gif" width="250" /> <br/>
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image036.png" width="250" /> &nbsp;
<img src="https://github.com/flowerDuo/ISTIRS/blob/main/imgs/image038.png" width="250" /> &nbsp;

## Algorithm 

The newly proposed image stitching method (OP-GSP) is used to provide the core support for the image stitching function of the software. The algorithm is superior to AutoStitch in image distortion and misalignment, and has better alignment and robustness than the original GSP. The paper has been published in IEEE JSTARS.

Paper：Jiguang Cui, Man Liu, Zhitao Zhang, Shuqin Yang, Jifeng Ning*. Robust UAV Thermal Infrared Remote Sensing Images Stitching Via Overlap Prior Based Global Similarity Prior Model, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing （IEEE Jstars）. vol. 14, pp. 270-282, 2021.

URL：https://doi.org/10.1109/JSTARS.2020.3032011

## Data set

We provide a large number of farmland thermal infrared remote sensing image data for users to experience and test.<br/>

Data set：URL：https://pan.baidu.com/s/18IPa8ngPdkXrlCSEwhpdAQ <br/>
				  Password：imxv <br/>
Note: The UAV flight parameters of this data set : UAV altitude: 120 m, Camera pixel size: 17 µm. The recommended image grid size: 40x40 .

## Team

Northwest A&F University - Agricultural Hydrological Remote Sensing Research Group

## Contact us

njf@nwsuaf.edu.cn <br/> zhitaozhang@126.com 

