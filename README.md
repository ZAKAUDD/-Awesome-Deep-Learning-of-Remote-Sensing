# Awesome Deep Learning of Remote Sensing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
In this project, we will open source some baseline codes for the remote sensing analysis task, such as semantic segmentation, scene classification, object detection, and image captioning, We will also collect some public datasets that can be used for remote sensing image research and analysis.
- [x] Public Remote Sensing Dataset
- [x] Baseline Codes (Semantic Segmentation/Scene Classification/Object Detection/Image Captioning)
- [x] OpenSoure Codes
- [x] Compitions About Remote Sensing

## Public Remote Sensing Dataset

### 1.Semantic Segmentation
##### [ISPRS Potsdam 2D Semantic Labeling Contest ](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-potsdam.html "ISPRS Potsdam 2D Semantic Labeling Contest")   
6 urban land cover classes, raster mask labels, 4-band RGB-IR aerial imagery (0.05m res.) & DSM, 38 image patches   
##### categories      
 | index | label | color |
 | :-----| ----: | :----: |
 | 1 | Impervious surfaces | 255, 255, 255 |
 | 2 | Building | 0, 0, 255 |
 | 3 | Low vegetation | 0, 255, 255 |
 | 4 | Tree | 0, 255, 0 |
 | 5 | Car | 255, 255, 0 |
 | 6 | Clutter/background | 255, 0, 0 | 
##### Download   
[baiduyun password: 9enz](https://pan.baidu.com/s/1l_s8XsT_wn5TgpNqwMnVMw "ISPRS Potsdam 2D Semantic Labeling Contest")   
#### [DSTL Satellite Imagery Feature Detection Challenge ](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection "DSTL Satellite Imagery Feature Detection Challenge ")   
10 land cover categories from crops to vehicle small, 57 1x1km images, 3/16-band Worldview 3 imagery (0.3m-7.5m res.), Kaggle kernels
#### [Slovenia Land Cover Classification](http://eo-learn.sentinel-hub.com/ "Slovenia Land Cover Classification")   
10 land cover classes, temporal stack of hyperspectral Sentinel-2 imagery (R,G,B,NIR,SWIR1,SWIR2; 10 m res.) for year 2017 with cloud masks, Official Slovenian land use land cover layer as ground truth.
#### [SEN12MS](https://mediatum.ub.tum.de/1474000 "SEN12MS")    
180,748 corresponding image triplets containing Sentinel-1 (VV&VH), Sentinel-2 (all bands, cloud-free), and MODIS-derived land cover maps (IGBP, LCCS, 17 classes, 500m res.). All data upsampled to 10m res., georeferenced, covering all continents and meterological seasons, Paper: Schmitt et al. 2018
#### [IEEE Data Fusion Contest 2018 ](http://www.grss-ieee.org/community/technical-committees/data-fusion/2018-ieee-grss-data-fusion-contest/ "IEEE Data Fusion Contest 2018 ")   
20 land cover categories by fusing three data sources: Multispectral LiDAR, Hyperspectral (1m), RGB imagery (0.05m res.)
#### [Segmentation Data of Sparse Representation and Intelligent Analysis of 2019 Remote Sensing Image competition]( "") (website has been closed)   
16 land cover classes,4-band RGB-IR aerial imagery (4m res.) 8 patches of 7200x6800 for train and 2 patches of 7200x6800 for val and 10 patches of 7200x6800 for test
##### categories  
 | index | label | color |
 | :-----| ----: | :----: |
 | 1 | ?????? | 0,200,0 |
 | 2 | ????????? | 150,250,0 |
 | 3 | ????????? | 150,200,150 |
 | 4 | ?????? | 200,0,200 |
 | 5 | ???????????? | 150,0,250 |
 | 6 | ???????????? | 150,150,250 | 
 | 7 | ???????????? | 250,200,0 | 
 | 8 | ???????????? | 200,200,0 | 
 | 9 | ???????????? | 200,0,0 |
 | 10 | ???????????? | 250,0,150 |
 | 11 | ???????????? | 200,150,150 |
 | 12 | ???????????? | 250,150,150 |
 | 13 | ?????? | 0,0,200 |
 | 14 | ?????? | 0,150,200 |
 | 15 | ?????? | 0,200,250 |
 | 16 | ?????? | 0,0,0 |
 ##### Download 
 [baiduyun password: o2fp](https://pan.baidu.com/s/1Bun1xlFFr49HXJXSjKab3Q "Segmentation Data of Sparse Representation and Intelligent Analysis of 2019 Remote Sensing Image competition")
#### [2019 ?????????????????????AI?????????](https://tianchi.aliyun.com/competition/entrance/231717/information "2019 ?????????????????????AI?????????")   
5 argriculture categories
#### [CCF ???????????????AI????????????????????? BDCI 2017](https://www.datafountain.cn/competitions/270/datasets "BDCI 2017")   
5 land cover classes(greenland, building, waterbody, road and other), 5 rgb images(R,G,B; 1 m res.) for train and val, 3 rgb images for test
##### categories
 | index | label | gary |
 | :-----| ----: | :----: |
 | 1 | ?????? | 1 |
 | 2 | ?????? | 2 |
 | 3 | ?????? | 3 |
 | 4 | ?????? | 4 |
 | 5 | ?????? | 0 | 
 ##### Download 
 [baiduyun password: aaod](https://pan.baidu.com/s/1ld8p2bghiKu_2A6Mg4_-JQ "BDCI 2017")
#### [2020 NAIC ????????????????????????AI+???????????? ](https://naic.pcl.ac.cn/frame/2 "2020NAIC")   
- ?????????10??????????????????????????????????????????????????????8????????????20????????????????????????
- ?????????10??????????????????????????????????????????????????????17????????????30????????????????????????
##### ?????? categories  
 | index | ???????????? | gary(????????????) |
 | :-----| ----: | :----: |
 | 1 | ?????? | 1 |
 | 2 | ???????????? | 2 |
 | 3 | ?????? | 3 |
 | 4 | ?????? | 4 |
 | 5 | ?????? | 5 |
 | 6 | ?????? | 6 | 
 | 7 | ?????? | 7 | 
 | 8 | ?????? | 8 |    
 ##### ?????? categories  
 | index | ???????????? | gary(???????????????????????????) |
 | :-----| ----: | :----: |
 | 1 | ?????? | 01 |
 | 2 | ?????? | 02 |
 | 3 | ????????? | 03 |
 | 4 | ?????? | 04 |
 | 5 | ????????? | 05 |
 | 6 | ?????? | 06 | 
 | 7 | ????????? | 07 | 
 | 8 | ?????? | 08 | 
 | 9 | ???????????? | 09 |
 | 10 | ???????????? | 10 |
 | 11 | ???????????? | 11 |
 | 12 | ???????????? | 12 |
 | 13 | ????????? | 13 |
 | 14 | ????????? | 14 |
 | 15 | ???????????? | 15 |
 | 16 | ???????????? | 16 |
 | 17 | ?????? | 17 |
 ##### Download   
[baiduyun password: pdos](https://pan.baidu.com/s/1Q4YjUAhmTwDCQA7wlKrDxQ "NAIC RS 2020")    
#### [2020 CCF BDCI ???????????????????????? ](https://www.datafountain.cn/competitions/475/datasets "2020BDCI")   
???????????????140,000???????????????2m/pixel????????????256256???JPG???????????????7??????????????????gt 0-6
##### categories
 | index | label | gary |
 | :-----| ----: | :----: |
 | 1 | ?????? | 0 |
 | 2 | ?????? | 1 |
 | 3 | ?????? | 2 |
 | 4 | ?????? | 3 |
 | 5 | ?????? | 4 |
 | 6 | ?????? | 5 | 
 | 7 | ?????? | 6 | 
 | 8 | ??????????????? | 255 | 
 ##### Download 
 [baiduyun password: 7tcn](https://pan.baidu.com/s/1bG9SdvXzmp3oNjkTPkwwfw "BDCI 2020")  
 
 #### [2021???????????????????????????????????????????????????????????????????????? ](https://tianchi.aliyun.com/competition/entrance/531860/introduction "2021TCRS")   
?????????????????????16017???????????????0.8m-2m/pixel????????????256256???TIF???????????????10??????????????????gt 1-10   
?????????????????????15904???????????????0.8m-2m/pixel????????????256256???TIF???????????????10??????????????????gt 1-10
##### categories
 | index | label | gary |
 | :-----| ----: | :----: |
 | 1 | ?????? | 1 |
 | 2 | ?????? | 2 |
 | 3 | ?????? | 3 |
 | 4 | ?????? | 4 |
 | 5 | ?????????????????? | 5 |
 | 6 | ?????????????????? | 6 | 
 | 7 | ???????????? | 7 | 
 | 8 | ????????? | 8 | 
 | 9 | ?????? | 9 | 
 | 10 | ?????? | 10 | 
 ##### Download 
 [baiduyun password: td5k](https://pan.baidu.com/s/1QQJPTKB8zqEflYmHaTXtJg "2021TCRS") 
 

### 2.Scene Classification
### 3.Object Detection
### 4.Image Captioning
## Baseline Codes
### Scene Classification
[image_classification](https://github.com/whut2962575697/image_classification "hexin") [pytorch]
### Semantic Segmentation
[image_seg](https://github.com/whut2962575697/image_seg "hexin") [pytorch]   
It is based on the codes of our Tianchi competition in 2021 (https://tianchi.aliyun.com/competition/entrance/531860/introduction).   
In the competition, our team won the third place (please see [Tianchi_README.md](https://github.com/whut2962575697/image_seg/blob/main/Tianchi_README.md "hexin")).
## OpenSoure Codes
### 1.Semantic Segmentation
- [cuilunan/Unet-of-remote-sensing-image](https://github.com/cuilunan/Unet-of-remote-sensing-image "cuilunan") [tensorflow]
- [Epsilon123/Semantic-Segmentation-of-Remote-Sensing-Images](https://github.com/Epsilon123/Semantic-Segmentation-of-Remote-Sensing-Images "Epsilon123") [keras]
- [YudeWang/UNet-Satellite-Image-Segmentation](https://github.com/YudeWang/UNet-Satellite-Image-Segmentation "YudeWang") [tensorflow]
- [rmkemker/EarthMapper](https://github.com/rmkemker/EarthMapper "rmkemker/EarthMapper") [tensorflow]
- [TachibanaYoshino/Remote-sensing-image-semantic-segmentation](https://github.com/TachibanaYoshino/Remote-sensing-image-semantic-segmentation "TachibanaYoshino/Remote-sensing-image-semantic-segmentation") [Keras]
- [lcylmhlcy/Semantic-segmentation](https://github.com/lcylmhlcy/Semantic-segmentation "lcylmhlcy/Semantic-segmentation") [pytorch]
- [liushuo2018/ERN](https://github.com/liushuo2018/ERN "liushuo2018/ERN") [caffe]
- [Walkerlikesfish/HSNRS](https://github.com/Walkerlikesfish/HSNRS "Walkerlikesfish/HSNRS") [caffe]
- [1044197988/Semantic-segmentation-of-remote-sensing-images](https://github.com/1044197988/Semantic-segmentation-of-remote-sensing-images "1044197988/Semantic-segmentation-of-remote-sensing-images") [keras]
- [fuweifu-vtoo/Semantic-segmentation](https://github.com/fuweifu-vtoo/Semantic-segmentation "fuweifu-vtoo/Semantic-segmentation") [pytorch]
- [reachsumit/deep-unet-for-satellite-image-segmentation](https://github.com/reachsumit/deep-unet-for-satellite-image-segmentation "reachsumit/deep-unet-for-satellite-image-segmentation") [keras]
- [lehaifeng/SCAttNet](https://github.com/lehaifeng/SCAttNet "lehaifeng/SCAttNet") [tensorflow]
- [NexGenMap/dl-semantic-segmentation](https://github.com/NexGenMap/dl-semantic-segmentation "NexGenMap/dl-semantic-segmentation") [tensorflow ]
- [yiskw713/boundary_loss_for_remote_sensing](https://github.com/yiskw713/boundary_loss_for_remote_sensing "yiskw713/boundary_loss_for_remote_sensing") [pytorch]
- [zetrun-liu/FCNs-for-road-extraction-keras](https://github.com/zetrun-liu/FCNs-for-road-extraction-keras "zetrun-liu/FCNs-for-road-extraction-keras") [keras]
- [susurrant/rs-img-classification](https://github.com/susurrant/rs-img-classification "susurrant/rs-img-classification") [tensorflow]
- [AI-Chen/Deeplab-v3-Plus-pytorch-](https://github.com/AI-Chen/Deeplab-v3-Plus-pytorch- "AI-Chen/Deeplab-v3-Plus-pytorch-") [pytorch]
- [mohuazheliu/ResUnet-a](https://github.com/mohuazheliu/ResUnet-a "mohuazheliu/ResUnet-a") [tensorflow]
- [zlkanata/DeepGlobe-Road-Extraction-Challenge](https://github.com/zlkanata/DeepGlobe-Road-Extraction-Challenge "zlkanata/DeepGlobe-Road-Extraction-Challenge") [pytorch]
- [DeepVoltaire/Dstl-Satellite-Imagery-Feature-Detection](https://github.com/DeepVoltaire/Dstl-Satellite-Imagery-Feature-Detection "DeepVoltaire/Dstl-Satellite-Imagery-Feature-Detection") [keras]
### 2.Scene Classification
- [weihancug/SENet_ResNeXt_Remote_Sensing_Scene_Classification](https://github.com/weihancug/SENet_ResNeXt_Remote_Sensing_Scene_Classification "weihancug/SENet_ResNeXt_Remote_Sensing_Scene_Classification") [pytorch]
- [BiQiWHU/DenseNet40-for-HRRSISC](https://github.com/BiQiWHU/DenseNet40-for-HRRSISC "BiQiWHU/DenseNet40-for-HRRSISC") [tensorflow]
- [weihancug/SSGF-for-HRRS-scene-classification](https://github.com/weihancug/SSGF-for-HRRS-scene-classification "weihancug/SSGF-for-HRRS-scene-classification") [caffe]
- [Arafat123-iit/A-System-for-Effecient-Remote-Sensing-Image-Scene-Classification-](https://github.com/Arafat123-iit/A-System-for-Effecient-Remote-Sensing-Image-Scene-Classification- "Arafat123-iit/A-System-for-Effecient-Remote-Sensing-Image-Scene-Classification-") [keras]
- [Aaromxj/SF-CNN](https://github.com/Aaromxj/SF-CNN "Aaromxj/SF-CNN") [Caffe]
- [Aaron-Lst/ARCNet](https://github.com/Aaron-Lst/ARCNet "Aaron-Lst/ARCNet") [pytorch]
- [Wanke15/Feature_extraction-SVM-classification-Remote-sensing](https://github.com/Wanke15/Feature_extraction-SVM-classification-Remote-sensing "Wanke15/Feature_extraction-SVM-classification-Remote-sensing") [caffe]
- [williamzhao95/Pay-More-Attention](https://github.com/williamzhao95/Pay-More-Attention "williamzhao95/Pay-More-Attention") [Mxnet]
- [henanjun/SccovNet](https://github.com/henanjun/SccovNet "henanjun/SccovNet") [matlab]
### 3.Object Detection
- [clw5180/remote_sensing_object_detection_2019](https://github.com/clw5180/remote_sensing_object_detection_2019 "clw5180/remote_sensing_object_detection_2019") [pytorch]
- [jiangruoqiao/RICNN_GongCheng_CVPR2015](https://github.com/jiangruoqiao/RICNN_GongCheng_CVPR2015 "jiangruoqiao/RICNN_GongCheng_CVPR2015") [tensorflow]
- [R-Stefano/Remote-Sensing-Analysis](https://github.com/R-Stefano/Remote-Sensing-Analysis "R-Stefano/Remote-Sensing-Analysis") [tensorflow]
- [WenchaoliuMUC/Detection-of-Multiclass-Objects-in-Optical-Remote-Sensing-Images](https://github.com/WenchaoliuMUC/Detection-of-Multiclass-Objects-in-Optical-Remote-Sensing-Images "WenchaoliuMUC/Detection-of-Multiclass-Objects-in-Optical-Remote-Sensing-Images") [pytorch]
- [weihancug/Remote-Sensing-Object-Detection-with-Oriented-Bouding-Box](https://github.com/weihancug/Remote-Sensing-Object-Detection-with-Oriented-Bouding-Box "weihancug/Remote-Sensing-Object-Detection-with-Oriented-Bouding-Box") [pytorch]
- [Pilot-Zhang/ssd.pytorch](https://github.com/Pilot-Zhang/ssd.pytorch "Pilot-Zhang/ssd.pytorch") [pytorch]
### 4.Image Captioning
## Compitions About Remote Sensing
### 2020
### 2019
### 2018
### 2017
