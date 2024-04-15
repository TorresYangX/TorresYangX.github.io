---
title: "Reconstructing Trajectories with Transformer Variational AutoEncoder"
collection: publications
permalink: /publication/2024-02-08-Reconstructing Trajectories with Transformer Variational AutoEncoder
excerpt: 'This paper is about the reconstrcution of low-quality trajectory dataset'
date: 2024-02-08
venue: 'SIGKDD'
paperurl: #'http://academicpages.github.io/files/paper1.pdf'
citation: 'Xuan Yang, Dou Huang, Haoran Zhang, Jianan Xie & Yebei Gou, “Reconstructing Trajectories with Transformer Variational AutoEncoder”'
---

Reconstructing trajectory sets with a low sampling rate or incompleteness while ensuring high accuracy and low bias is of great importance. Although many recent studies have solved this by trajectory complements, these methods primarily focus on the similarity and reconstruction of individual trajectories, overlooking the overall spatio-temporal structure of the trajectory dataset, which is still affected by the bias of individual trajectories. In this paper, we take into account the spatio-temporal characteristics of the trajectory dataset to address the drawbacks. Specifically, we utilize the Transformer Variational AutoEncoder (NVAE) model to regularize and extract features of the low-quality trajectories. To reconstruct, we retrieve these trajectories from a pre-established trajectory database and recover a set of trajectories with a high sampling rate, high accuracy, and low bias. Our experiments with two real-life datasets demonstrate that the NVAE method outperforms existing approaches consistently and significantly.
