---
title: "Diffusion-Enhanced Transformation Consistency Learning for Retinal Image Segmentation"
collection: publications
category: conferences
excerpt: 'To improve label utilization efficiency in semantic segmentation models, we propose Diffusion-Enhanced Transformation Consistency Learning (termed as DiffTCL), a semi-supervised segmentation approach.'
date: 2024-10-03
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-72120-5_21'
citation: 'Li X, Fang H, Liu M, et al. Diffusion-Enhanced Transformation Consistency Learning for Retinal Image Segmentation[C]//International Conference on Medical Image Computing and Computer-Assisted Intervention. Cham: Springer Nature Switzerland, 2024: 221-231.'
---

Retinal image segmentation plays a critical role in rapid disease detection and early detection, such as assisting in the observation of abnormal structures and structural quantification. However, acquiring semantic segmentation labels is both expensive and time-consuming. To improve label utilization efficiency in semantic segmentation models, we propose Diffusion-Enhanced Transformation Consistency Learning (termed as DiffTCL), a semi-supervised segmentation approach. Initially, the model undergoes self-supervised diffusion pre-training, establishing a reasonable initial model to improve the accuracy of early pseudo-labels in the subsequent consistency training, thereby preventing error accumulation. Furthermore, we developed a Transformation Consistency Learning (TCL) method for retinal images, effectively utilizing unlabeled data. In TCL, the prediction of image affine transformations acts as supervision for both image elastic transformations and pixel-level transformations. We carry out evaluations on the REFUGE2 and MS datasets, involving the segmentation of two modalities: optic disc/cup segmentation in color fundus photography, and layer segmentation in optical coherence tomography. The results for both tasks demonstrate that DiffTCL achieves relative improvements of 5.0% and 2.3%, respectively, over other state-of-the-art semi-supervised methods. The code is available at: [DiffTCL](https://github.com/lixiang007666/DiffTCL).


