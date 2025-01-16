# PCDM-UDA
Pseudo-class distribution guided multi-view unsupervised domain adaptation for hyperspectral image classification
===
Abstract
---
Unsupervised domain adaptation (UDA) has made great progress in cross-scene hyperspectral image (HSI) classification. Existing methods focus on aligning the distribution of source domain (SD) and target domain (TD). However, they all ignore the implicit class distribution information of TD data, which can help the model predict the class with a higher posterior probability. To solve the above issue, we propose pseudo-class distribution guided multi-view unsupervised domain adaptation for hyperspectral image classification (PCDM-UDA). We transform the label correction into a zero–one programming problem and optimize it with the estimated pseudo-class distribution as a constraint. The corrected labels are used to fine-tune the network, which can integrate class distribution information into the network. The frequency domain phase view is introduced as an additional branch to extract domain stable feature. To credibly fuse the information from the prediction of the two branches, we introduce the Subjective logic and Dempster’s rule into our method. In addition, we design an adaptive style learning module to enhance the inter-class separability of the model. Extensive experimental results on three public datasets demonstrate that the proposed method outperforms the state-of-the-art methods.

Requirements
---
Python = 3.8
torch = 1.11.0
gurobipy = 9.5.0

Cite
---
Jingpeng Gao, Xiangyu Ji, Geng Chen, Yuhang Huang, Fang Ye, Pseudo-class distribution guided multi-view unsupervised domain adaptation for hyperspectral image classification, International Journal of Applied Earth Observation and Geoinformation, Volume 136, 2025, 104356, ISSN 1569-8432, https://doi.org/10.1016/j.jag.2025.104356.
