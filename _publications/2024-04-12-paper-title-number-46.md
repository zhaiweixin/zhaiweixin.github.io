---
title: "Reconstruction of missing points in agricultural machinery trajectory based on bidirectional adjacent information"
collection: publications
permalink: /publication/2024-04-12-paper-title-number-46
excerpt: ''
date: 2024-04-12
venue: 'Computers and Electronics in Agriculture'

paperurl: <!--'http://academicpages.github.io/files/paper1.pdf' -->
citation: '<b>Zhai Weixin</b>, Kuang Xinran, Cheng Xiaoyu, Pan Jiawen, Wu Caicong. Reconstruction of missing points in agricultural machinery trajectory based on bidirectional adjacent information. <i>Computers and Electronics in Agriculture<i>, Volume 220, 2024, 108920.'
---



<!--This paper is about the number 1. The number 2 is left for future work.-->
Abstract : Agricultural machinery trajectory data often encounters the phenomenon of missing trajectory points, and reconstructing these missing trajectory points is crucial for subsequent researches that require complete and high-quality agricultural machinery trajectory data. In this paper, we propose a new method called Fast-TRGRU to accurately and quickly reconstruct missing points in the trajectory of agricultural machinery. First, we design a novel data preprocessing process to improve the quality of raw data. Next, we introduce a bidirectional feature extraction module (BFE) to simultaneously utilize the bidirectional adjacent subtrajectory information of missing trajectory points. Then, we use gated recurrent unit (GRU) to extract spatiotemporal correlation features from time series data representing agricultural machinery trajectories to reconstruct trajectories. Finally, we reduce the training time of the model by adjusting the structure of the model in the GRU model. To verify the effectiveness of the model, we conducted experiments using 125 real agricultural machinery trajectory samples including 1,111,813 points provided by the Key Laboratory of Agricultural Machinery Monitoring and Big Data Applications of the Ministry of Agriculture and Rural Affairs. The experimental results show that when the trajectory missing rate is 10 %, the average reconstruction deviations of the model in longitude and latitude are only 1.80 m and 1.95 m, respectively. When the trajectory missing rate is 60 %, the average reconstruction deviation of the model in both longitude and latitude is still less than 4 m, which is higher than the positioning accuracy of the Beidou Navigation Satellite System. The Fast-TRGRU can provide complete and high-quality data for the analysis of agricultural machinery trajectories, effectively assisting in the research of optimizing agricultural machinery operation paths and evaluating agricultural machinery operation efficiency.

<!--[Download paper here](http://academicpages.github.io/files/paper1.pdf)-->

<!--Recommended citation: Zhai W, Cheng C. Vagueness in spatial data: A grid-coding approach[C]. proceedings of the 2014 IEEE Geoscience and Remote Sensing Symposium, 2014. IEEE.-->
