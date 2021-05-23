---
title: "A Low-Altitude Flight Conflict Detection Algorithm Based on a Multilevel Grid Spatiotemporal Index"
collection: publications
permalink: /publication/2019-06-21-paper-title-number-22
excerpt: ''
date: 2019-06-21
venue: 'ISPRS International Journal of Geo-Information'

paperurl: <!--'http://academicpages.github.io/files/paper1.pdf' -->
citation: 'Miao Shuangxi, Cheng Chengqi, <b>Zhai Weixin</b>, Ren Fuhu, Zhang Bo, Li Shuang, Zhang Junxiao, Zhang Huangchuang. A Low-Altitude Flight Conflict Detection Algorithm Based on a Multilevel Grid Spatiotemporal Index [J]. <i>ISPRS International Journal of Geo-Information</i>, 2019, 8(6): 289.'
---



<!--This paper is about the number 1. The number 2 is left for future work.-->
Abstract : Flight conflict detection is fundamental to flight dispatch, trajectory planning, and flight safety control. An ever-increasing aircraft population and higher speeds, particularly the emergence of hypersonic/supersonic aircrafts, are challenging the timeliness and accuracy of flight conflict detection.Traditional trajectory conflict detection algorithms rely on traversing multivariate equations of every two trajectories, in order to yield the conflict result and involve extensive computation and high algorithmic complexity; these algorithms are often unable to provide the flight conflict solutions required quickly enough. In this paper, we present a novel, low-altitude flight conflict detection algorithm, based on the multi-level grid spatiotemporal index, that transforms the traditional trajectory-traversing multivariate conflict computation into a grid conflict state query of distributed grid databases. Essentially, this is a method of exchanging “storage space” for “computational time”.First, we build the spatiotemporal subdivision and encoding model based on the airspace. The model describes the geometries of the trajectories, low-altitude obstacles, or dangerous fields and identifies the grid with grid codes. Next, we design a database table structure of the grid and create a grid database. Finally, we establish a multilevel grid spatiotemporal index, design a query optimization scheme, and examine the flight conflict detection results from the grid database. Experimental verification confirms that the computation efficiency of our algorithm is one order of magnitude higher than those of traditional methods. Our algorithm can perform real-time (dynamic/static)conflict detection on both individual aircraft and aircraft flying in formation with more efficient trajectory planning and airspace utilization.
<!--[Download paper here](http://academicpages.github.io/files/paper1.pdf)-->

<!--Recommended citation: Zhai W, Cheng C. Vagueness in spatial data: A grid-coding approach[C]. proceedings of the 2014 IEEE Geoscience and Remote Sensing Symposium, 2014. IEEE.-->
