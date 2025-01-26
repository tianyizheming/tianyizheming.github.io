---
title: "Calibrate the inter-observer segmentation uncertainty via diagnosis-first principle"
collection: publications
category: manuscripts
excerpt: 'We propose a diagnosis-first principle, which is to take disease diagnosis as the criterion to calibrate the inter-observer segmentation uncertainty.'
date: 2024-04-26
venue: 'IEEE Transactions on Medical Imaging'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10508990'
citation: 'Wu J, Zhang Y, Fang H, et al. Calibrate the inter-observer segmentation uncertainty via diagnosis-first principle[J]. IEEE Transactions on Medical Imaging, 2024.
'
---

Many of the tissues/lesions in the medical images may be ambiguous. Therefore, medical segmentation is typically annotated by a group of clinical experts to mitigate personal bias. A common solution to fuse different annotations is the majority vote, e.g., taking the average of multiple labels. However, such a strategy ignores the difference between the grader expertness. Inspired by the observation that medical image segmentation is usually used to assist the disease diagnosis in clinical practice, we propose the diagnosis-first principle, which is to take disease diagnosis as the criterion to calibrate the inter-observer segmentation uncertainty. Following this idea, a framework named Diagnosis-First segmentation Framework (DiFF) is proposed. Specifically, DiFF will first learn to fuse the multi-rater segmentation labels to a single ground-truth which could maximize the disease diagnosis performance. We dubbed the fused ground-truth as Diagnosis-First Ground-truth (DF-GT). Then, the Take and Give Model (T&G Model) to segment DF-GT from the raw image is proposed. With the T&G Model, DiFF can learn the segmentation with the calibrated uncertainty that facilitate the disease diagnosis. We verify the effectiveness of DiFF on three different medical segmentation tasks: optic-disc/optic-cup (OD/OC) segmentation on fundus images, thyroid nodule segmentation on ultrasound images, and skin lesion segmentation on dermoscopic images. Experimental results show that the proposed DiFF can effectively calibrate the segmentation uncertainty, and thus significantly facilitate the corresponding disease diagnosis, which outperforms previous state-of-the-art multi-rater learning methods.
