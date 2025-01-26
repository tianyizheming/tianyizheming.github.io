---
title: "Cache-Driven Spatial Test-Time Adaptation for Cross-Modality Medical Image Segmentation"
collection: publications
category: conferences
excerpt: 'We introduce Spatial Test-Time Adaptation (STTA), for the first time considering the integration of inter-slice spatial information from 3D volumes with TTA.'
date: 2024-10-03
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-72120-5_14'
citation: 'Li X, Fang H, Wang C, et al. Cache-Driven Spatial Test-Time Adaptation for Cross-Modality Medical Image Segmentation[C]//International Conference on Medical Image Computing and Computer-Assisted Intervention. Cham: Springer Nature Switzerland, 2024: 146-156.'
---

Test-Time Adaptation (TTA) shows promise for addressing the domain gap between source and target modalities in medical image segmentation methods. Furthermore, TTA enables the model to quickly fine-tune itself during testing, enabling it to adapt to the continuously evolving data distribution in the medical clinical environment. Consequently, we introduce Spatial Test-Time Adaptation (STTA), for the first time considering the integration of inter-slice spatial information from 3D volumes with TTA. The continuously changing distribution of slice data in the target domain can lead to error accumulate on and catastrophic forgetting. To tackle these challenges, we first propose reducing error accumulation by using an ensemble of multi-head predictions based on data augmentation. Secondly, for pixels with unreliable pseudo-labels, regularization is applied through entropy minimization on the ensemble of predictions from multiple heads. Finally, to prevent catastrophic forgetting, we suggest using a cache mechanism during testing to restore neuron weights from the source pre-trained model, thus effectively preserving source knowledge. The proposed STTA has been bidirectionally validated across modalities in abdominal multi-organ and brain tumor datasets, achieving a relative increase of approximately 13% in the Dice value in the best-case scenario compared to SOTA methods. The code is available at: [STTA](https://github.com/lixiang007666/STTA).

