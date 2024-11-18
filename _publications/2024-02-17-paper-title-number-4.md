---
title: " Efficient Frontier Management for Collaborative Active SLAM"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This article tackles the challenge of Active Collaborative SLAM, where multiple robots work together to explore and map unknown environments. It presents a centralized frontier-sharing approach that maximizes exploration by considering information gain, distance, and reward computation among frontier candidates, promoting efficient robot distribution. The method includes synchronous and asynchronous coordination strategies to prioritize robot goal assignments via a central server. Implemented in ROS, it is validated through simulations and experiments on public datasets, achieving promising results.'
date: 2024-10-17
venue: 'IEEE MFI 2024, Pilsen'
paperurl: 'https://mf-ahmed.github.io/mfa/files/2310.01967v5.pdf'
citation: 'M. F. Ahmed, M. Maragliano, V. Frémont, C. T. Recchiuto and A. Sgorbissa. (2024). &quot;Efficient Frontier Management for Collaborative Active SLAM.&quot; <i>IEEE MFI 2024</i>. pp. 1-7, doi: 10.1109/MFI62651.2024.10705778.'
---


In autonomous robotics, a critical challenge lies in developing robust solutions for Active Collaborative SLAM, wherein multiple robots collaboratively explore and map an unknown environment while intelligently coordinating their movements and sensor data acquisitions. In this article, we present an efficient centralized frontier sharing approach that maximizes exploration by taking into account information gain in the merged map, distance, and reward computation among frontier candidates and encourages the spread of agents into the environment. Eventually, our method efficiently spreads the robots for maximum exploration while keeping SLAM uncertainty low. Additionally, we also present two coordination approaches, synchronous and asynchronous to prioritize robot goal assignments by the central server. The proposed method is implemented in ROS and evaluated through simulation and experiments on publicly available datasets and similar methods, rendering promising results.

<iframe width="560" height="315" 
    src="https://www.youtube.com/embed/MsZqoaEA0gY?autoplay=1" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
    allowfullscreen>
</iframe>