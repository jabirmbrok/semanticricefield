# Semantic Segmentation of Sentinel-2 Satellite Image for Rice Growth Phase Classification Using Deep Learning
This repository contains the code and configuration files to reproduce the semantic segmentation results using U-Net and Classification CNN models, focusing on satellite imagery analysis of rice fields. Included are pre-trained models for semantic segmentation of satellite images into rice field areas and classification of rice growth stages (land preparation, early vegetative, late vegetative, generative, and harvested).

For a comprehensive explanation of the methodology, experimental setup, and results, please refer to our IEEE conference paper:
[Semantic Segmentation of Sentinel-2 Satellite Image for Rice Growth Phase Classification Using Deep Learning](https://ieeexplore.ieee.org/document/10759168.)

## Dataset Sources

To train and test the models, we used data provided by the European Space Agency (ESA) from the ESA NOR project, consisting of Sentinel-2 satellite images. For the classification of rice growth stages, we utilized the rice growth dataset from the ASF survey conducted by BPS.

Initially, the dataset contained many classes. We reduced the number of classes to six, focusing on those relevant to rice growth phases and non-rice areas, which are:

1. Land preparation  
2. Early vegetative  
3. Late vegetative  
4. Generative  
5. Harvested  
6. Non-paddy (non-rice area)


