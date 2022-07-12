---
title: Research
permalink: /research/
---
My research is in the area of data management systems, focusing on using approximate query processing in conjunction with high-performance analytical systems on modern hardware to enable workload-agnostic, timely, interactive, energy- and cost-efficient insights offered (and hindered) by the growing amounts of data.
{: .text-justify}

![Data and Hardware Trends](/assets/images/data_hw_trends.jpg)
{: display: block; margin-left: auto; margin-right: auto;}

**Data growth, normalized to PCI-e and memory bandwidth growth rate \[1\] - still no free lunch for interactive and fast analytics**
{: .text-center; font-size: 6pt;}

My goal and vision is to enable truly interactive analytics with zero assumptions about the workload, by co-designing the approximation algorithms to be efficient and utilize fully the underlying hardware, exploring the algorithmic bottlenecks, and developing systems and algorithms that maximize work reuse to further reduce the time-to-insight on high-bandwidth, low-latency analytical systems. Finally, the goal is to develop approximate query processing systems that outperform the best and highly-optimized modern analytical engines. To unlock this potential of modern analytics, I am working and developing my work on approximate analytics on top of a high-performance heterogeneous engine [Proteus](www.proteusdb.com). By harmonizing modern analytics with approximate algorithms, we can enable cost and energy efficient insights, by spending less (computational) time in the fastest layers of increasingly powerful computational hardware. 
{: .text-justify}

Finally, such systems would offer a principled way to overcome the increasing memory bandwidth wall, driven by the data volume outgrowing hardware characteristics. Harmonizing approximate query processing with modern systems needs to result in faster than the state-of-the-art analytical engine performance, especially against the optimized scale-up baselines.
{: .text-justify}

## Peer-Reviewed Publications 

1. Viktor Sanca and Anastasia Ailamaki. 2022. *Sampling-Based AQP in Modern Analytical Engines.* In Data Management on New Hardware (DaMoN'22). Association for Computing Machinery, New York, NY, USA, Article 4, 1–8. [Link](https://doi.org/10.1145/3533737.3535095)

2. Panagiotis Sioulas, Viktor Sanca, Ioannis Mytilinis, and Anastasia Ailamaki. 2021. *Accelerating Complex Analytics using Speculation.* In Conference on Innovative Data Systems Research (CIDR'21). [Link](https://www.cidrdb.org/cidr2021/papers/cidr2021_paper03.pdf)

