---
title: "Domain adaptation method for extracting buildings from remote sensing images using dual contrastive learning"
collection: publications
category: manuscripts
permalink: /publication/2024-09-04-domain-adaptation-for-building-extract
excerpt: 'About deeplearning-based building identification method from satellite images.'
date: 2024-09-04
venue: 'Journal of Applied Remote Sensing'
slidesurl: #'http://academicpages.github.io/files/slides3.pdf'
paperurl: #'http://jingxianwen.github.io/files/Yuan_etal_2024_atmosphere.pdf'
citation: 'He, Chunxiu, Xianwen Jing. <b>2024</b>. "Domain adaptation method for extracting buildings from remote sensing images using dual contrastive learning". <i>J. Appl. Rem. Sens.</i> 18(3), 034517. <a href="https://doi.org/10.1117/1.JRS.18.034517" target="_blank">https://doi.org/10.1117/1.JRS.18.034517</a>'
---
For the land type classification from multi-source remote sensing images with deep learning models, domain adaptation is usually required to improve their generalization ability and work efficiency. We design a dual contrastive learning structure that performs separate contrasts in the encoder and decoder for domain adaptation of the model. Its core utilizes the advantages of contrast learning in classifying unlabeled data. Further optimizations are made toward the loss functions used in the network structure, including a dynamic classification weight adjustment algorithm to treat imbalanced sample numbers and a local dynamic threshold method to filter local noises. With the Potsdam dataset as the source domain and the Vaihingen and LoveDA datasets as the target domains, two sets of experiments are conducted to verify the effectiveness of the model. In addition, corresponding ablation experiments are designed to verify the necessity of the dual contrastive structure. The results show that our method achieved superior performance in building extraction when compared with state-of-the-art methods. Furthermore, it is indicated that the dual contrastive structure is more effective than a single contrastive structure in terms of building extraction.
