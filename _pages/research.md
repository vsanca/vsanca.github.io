---
title: Research
permalink: /research/
---
My research is in the area of data management systems and applications. My primary focus is on using approximate query processing in conjunction with high-performance analytical systems on modern hardware to enable workload-agnostic, timely, interactive, energy- and cost-efficient insights offered by the growing amounts of data. Broadly, I am interested in novel hardware architectures, hardware-software co-design, database systems and algorithms for analytics. This also drives my interest in the topic of using machine learning in conjunction with databases, in particular in the context of mixed data format analytics anb data cleaning for online integration. Considerations for different data formats and components of such systems are required, both in logical optimizations of algorithms, as well as hardware mainly driven by the ML community.  
{: .text-justify}

## Approximate query processing on modern hardware

![Data and Hardware Trends](/assets/images/data_hw_trends.jpg)
{: display: block; margin-left: auto; margin-right: auto;}

**Data growth, PCI-e, and memory bandwidth growth rate \[[DAMON'22](https://doi.org/10.1145/3533737.3535095)\] - still no free lunch for interactive and fast analytics**
{: text-align: center; .font-size: 8pt;}

My goal and vision is to enable truly interactive analytics with zero assumptions about the workload, by co-designing the approximation algorithms to be efficient and utilize fully the underlying hardware, exploring the algorithmic bottlenecks, and developing systems and algorithms that maximize work reuse to further reduce the time-to-insight on high-bandwidth, low-latency analytical systems. Finally, the goal is to develop approximate query processing systems that outperform the best and highly-optimized modern analytical engines. To unlock this potential of modern analytics, I am working and developing my work on approximate analytics on top of a high-performance heterogeneous engine [Proteus](https://www.proteusdb.com). By harmonizing modern analytics with approximate algorithms, we can enable cost efficient insights, by spending less (computational) time in the fastest layers of increasingly powerful computational hardware. Beyond analytics, cheaply and efficiently creating and maintaining statistics and summaries is a key driver of components such as query optimizers.
{: .text-justify}

Finally, such systems would offer a principled way to overcome the increasing memory bandwidth wall, driven by the data volume outgrowing hardware characteristics. Harmonizing approximate query processing with modern systems needs to result in faster than the state-of-the-art analytical engine performance, and in line with faster data access and more diverse compute units.
{: .text-justify}

## Peer-Reviewed Publications 

1. Viktor Sanca and Anastasia Ailamaki. 2022. *Sampling-Based AQP in Modern Analytical Engines.* In Data Management on New Hardware (DaMoN'22). Association for Computing Machinery, New York, NY, USA, Article 4, 1–8. [Link](https://doi.org/10.1145/3533737.3535095)

2. Panagiotis Sioulas, Viktor Sanca, Ioannis Mytilinis, and Anastasia Ailamaki. 2021. *Accelerating Complex Analytics using Speculation.* In Conference on Innovative Data Systems Research (CIDR'21). [Link](https://www.cidrdb.org/cidr2021/papers/cidr2021_paper03.pdf)

