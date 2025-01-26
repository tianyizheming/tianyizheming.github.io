---
title: "Medsegdiff: Medical image segmentation with diffusion probabilistic model"
collection: publications
category: conferences
excerpt: 'Inspired by the success of DPM, we propose MedSegDiff, the first DPM-based model for general medical image segmentation tasks.'
date: 2024-01-23
venue: 'Medical Imaging with Deep Learning'
paperurl: 'https://proceedings.mlr.press/v227/wu24a.html'
citation: 'Wu J, Fu R, Fang H, et al. Medsegdiff: Medical image segmentation with diffusion probabilistic model[C]//Medical Imaging with Deep Learning. PMLR, 2024: 1623-1639.'
---

Diffusion Probabilistic Model (DPM) has recently become one of the hottest topics in computer vision. Its image generation applications, such as Imagen, Latent Diffusion Models, and Stable Diffusion, have demonstrated impressive generation capabilities, which have sparked extensive discussions in the community. Furthermore, many recent studies have found DPM to be useful in a variety of other vision tasks, including image deblurring, super-resolution, and anomaly detection. Inspired by the success of DPM, we propose MedSegDiff, the first DPM-based model for general medical image segmentation tasks. To enhance the step-wise regional attention in DPM for medical image segmentation, we propose Dynamic Conditional Encoding, which establishes state-adaptive conditions for each sampling step. Additionally, we propose the Feature Frequency Parser (FF-Parser) to eliminate the negative effect of high-frequency noise components in this process. We verify the effectiveness of MedSegDiff on three medical segmentation tasks with different image modalities, including optic cup segmentation over fundus images, brain tumor segmentation over MRI images, and thyroid nodule segmentation over ultrasound images. Our experimental results show that MedSegDiff outperforms state-of-the-art (SOTA) methods by a considerable performance gap, demonstrating the generalization and effectiveness of the proposed model.
