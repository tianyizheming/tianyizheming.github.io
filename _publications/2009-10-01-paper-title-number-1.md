---
title: "Multi-rater prism: Learning self-calibrated medical image segmentation from multiple raters"
collection: publications
category: manuscripts
excerpt: 'We propose a novel neural network framework called Multi-rater Prism (MrPrism) to learn medical image segmentation from multiple labels.'
date: 2024-09-30
venue: 'Science Bulletin'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2095927324005279'
citation: 'Wu J, Fang H, Zhu J, et al. Multi-rater prism: Learning self-calibrated medical image segmentation from multiple raters[J]. Science Bulletin, 2024, 69(18): 2906-2919.'
---
In medical image segmentation, it is often necessary to collect opinions from multiple experts to make the final decision. This clinical routine helps to mitigate individual bias. However, when data is annotated by multiple experts, standard deep learning models are often not applicable. In this paper, we propose a novel neural network framework called Multi-rater Prism (MrPrism) to learn medical image segmentation from multiple labels. Inspired by iterative half-quadratic optimization, MrPrism combines the task of assigning multi-rater confidences and calibrated segmentation in a recurrent manner. During this process, MrPrism learns inter-observer variability while taking into account the image’s semantic properties and finally converges to a self-calibrated segmentation result reflecting inter-observer agreement. Specifically, we propose Converging Prism (ConP) and Diverging Prism (DivP) to iteratively process the two tasks. ConP learns calibrated segmentation based on multi-rater confidence maps estimated by DivP, and DivP generates multi-rater confidence maps based on segmentation masks estimated by ConP. Experimental results show that the two tasks can mutually improve each other through this recurrent process. The final converged segmentation result of MrPrism outperforms state-of-the-art (SOTA) methods for a wide range of medical image segmentation tasks. The code is available at [MrPrism](https://github.com/WuJunde/MrPrism).
