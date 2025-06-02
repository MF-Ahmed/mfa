---
title: "Efficient Multi-robot Active SLAM"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Autonomous exploration in unknown environments remains a fundamental challenge in robotics, particularly for applications such as search and rescue, industrial inspection, and planetary exploration. Multi-robot active SLAM presents a promising solution by enabling collaborative mapping and exploration while actively reducing uncertainty. However, existing approaches often suffer from high computational costs and inefficient frontier management, making them computationally expensive for real-time applications. In this paper, we introduce an efficient multi-robot active SLAM framework that incorporates a frontier-sharing strategy to enhance robot distribution in unexplored environments. Our approach integrates a utility function that considers both pose graph uncertainty and path entropy, achieving an optimal balance between exploration coverage and computational efficiency. By filtering and prioritizing goal frontiers, our method significantly reduces computational overhead while preserving high mapping accuracy. The proposed framework has been implemented in ROS and validated through simulations and real-world experiments.'
date: 2025-04-28
venue: 'Journal of Intelligent & Robotic Systems (JIRS) '
#slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://mf-ahmed.github.io/mfa/files/2310.06160v1.pdf'
citation: 'M. F. Ahmed, M. Maragliano, V. Frémont, and C. T. Recchiuto. (2024). &quot;Efficient Multi-robot Active SLAM.&quot; <i>JIRS</i>. vol. 111, 2(64).'
---

In this article, we present an efficient multi-robot active SLAM framework that involves a frontier-sharing method
 for maximum exploration of an unknown environment. It encourages the robots to spread into the environment while
 weighting the goal frontiers with the pose graph SLAM uncertainly and path entropy. Our approach works on a limited
 number of frontier points and weights the goal frontiers with a utility function that encapsulates both the SLAM and
 map uncertainties, thus providing an efficient and not computationally expensive solution. Our approach has been
 tested on publicly available simulation environments and on real robots. An accumulative 31% more coverage than
 similar state-of-the-art approaches has been obtained, proving the capability of our approach for efficient environment
 exploration.