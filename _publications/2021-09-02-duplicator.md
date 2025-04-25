---
title: "Data Augmentation for Writer Identification Using a Cognitive Inspired Model"
collection: publications
category: conferences
permalink: /publication/2021-09-02-duplicator
excerpt: 'Investigate the impact of the increase in the number of manuscript samples on the writer identification task, using Duplicator. Experiments were performed at block, line and word-level.'
date: 2021-09-02
venue: '16th International Conference on Document Analysis and Recognition  (ICDAR)'
bibtexurl: 'http://fpignelli.github.io/files/citation_duplicator.bib'
citation: 'Pignelli, F., Costa, Y.M.G., Oliveira, L.S., Bertolini, D. (2021). Data Augmentation for Writer Identification Using a Cognitive Inspired Model. In: Lladós, J., Lopresti, D., Uchida, S. (eds) Document Analysis and Recognition – ICDAR 2021. ICDAR 2021. Lecture Notes in Computer Science(), vol 12824. Springer, Cham. https://doi.org/10.1007/978-3-030-86337-1_17'
---

Abstract

Assuming that two people do not have the same handwriting and do not write twice identically, handwriting can be considered a biometric characteristic of a person, frequently used in forensic document analysis. In the writer identification and verification scenario, the number of samples available for training is not always sufficient. Thus, in this work, we investigate the impact of the increase in the number of manuscript samples on the writer identification task, using synthetic samples generation inspired on a cognitive model. To better compare the proposed approach, we also performed experiments using a Gaussian Filter to generate new samples. Experiments were accomplished on the IAM and CVL databases, containing samples collected from 301 and 310 volunteer writers, respectively. From genuine samples of these databases, we generate new samples of images using the Duplicator approach. Feature vectors obtained using some well-known texture operators were used to feed an SVM classifier. Experiments showed that increasing the number of synthetic samples in the training set can be beneficial for the writer identification task, particularly when there are very few manuscript samples available for some writers. In the best scenario, the gain increased 31.7% in the identification rate using three genuine and fifteen duplicated samples at line-level.
