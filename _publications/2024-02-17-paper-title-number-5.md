---
title: "Active Collaborative Visual SLAM exploiting ORB Features"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-5
excerpt: 'This article addresses the challenge of Active Collaborative SLAM (AC-SLAM) in autonomous robotics, where multiple robots cooperatively explore and map unknown environments. It introduces an efficient visual AC-SLAM method using aerial and ground robots. The approach features a novel frontier filtering technique based on IoU map frontiers to optimize exploration and a strategy for guiding robots to revisited goal positions, enhancing loop closure and reducing SLAM uncertainty. Implemented in ROS, the method is validated through simulations on public datasets, achieving an average 59% improvement in area coverage compared to similar approaches.'
date: 2024-02-17
venue: 'IEEE ICARCV 2024, Dubai'
paperurl: 'https://mf-ahmed.github.io/mfa/files/2407.05453v2.pdf'
slidesurl: 'https://mf-ahmed.github.io/mfa/files/ICARCV2024.pdf'
citation: 'M. F. Ahmed, V. Frémont and I. Fantoni (2024). &quot;Active Collaborative Visual SLAM exploiting ORB Features.&quot; <i>ICARCV2024</i>. pp. 966-971, doi: 10.1109/ICARCV63323.2024.10821699.'
---


In autonomous robotics, a significant challenge involves devising robust solutions for Active Collaborative
 SLAM (AC-SLAM). This process requires multiple robots to cooperatively explore and map an unknown environment by
 intelligently coordinating their movements and sensor data acquisition. In this article, we present an efficient visual AC
SLAM method using aerial and ground robots for environment exploration and mapping. We propose an efficient frontiers filtering method that takes into account the common IoU map frontiers and reduces the frontiers for each robot. Additionally,
 we also present an approach to guide robots to previously visited goal positions to promote loop closure to reduce SLAM
 uncertainty. The proposed method is implemented in ROS and evaluated through simulations on publicly available datasets
 and similar methods, achieving an accumulative average of 59% of increase in area coverage.

<iframe width="560" height="315" 
    src="https://www.youtube.com/embed/6j3VBdnVcO8?autoplay=1" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>