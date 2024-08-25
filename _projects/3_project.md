---
layout: page
title: Securing smart home via traffic classification 
description: abstract, paper and slides 
img: 
redirect: 
importance: 3
category: work
giscus_comments: true
---
# Abstract
> IoT devices have become popular targets for various network attacks due to their lack of industry-wide security standards.
In this work, we focus on the classification of smart home IoT devices and defending them against Distributed Denial of 
Service (DDoS) attacks. The proposed framework protects smart homes by using VLAN-based network isolation. 
This architecture includes two VLANs: one with non-verified devices and the other with verified devices, both of
which are managed by a SDN controller. Lightweight, stateless flow-based features, including ICMP, TCP and UDP 
protocol percentage, packet count and size, and IP diversity ratio, are proposed for efficient feature collection. 
Further analysis is performed to minimize training data to run on resource-constrained edge devices in smart home networks. 
Three popular machine learning models, including K-Nearest-Neighbors, Random Forest, and Support Vector Machines, 
are used to classify IoT devices and detect different DDoS attacks based on TCP-SYN, UDP, and ICMP. The system’s 
effectiveness and efficiency are evaluated by emulating a network consisting of an Open vSwitch, Faucet SDN controller,
and flow traces of several IoT devices from two different testbeds. The proposed framework achieves an average accuracy of 
97% in device classification and 98% in DDoS detection with average latency of 1.18 milliseconds.




# Slides
Download [here](/assets/pdf/sdhomeppt.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/sdhomeppt.pdf" width="100%" height="500" type='application/pdf'></object>

# Paper
Download [here](/assets/pdf/COMPSAC 2021.pdf)
<object data="{{ site.url }}{{ site.baseurl }}/assets/pdf/COMPSAC 2021.pdf" width="100%" height="800" type='application/pdf'></object>


[//]: # (```html)

[//]: # (<div class="row justify-content-sm-center">)

[//]: # (  <div class="col-sm-8 mt-3 mt-md-0">)

[//]: # (    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %})

[//]: # (  </div>)

[//]: # (  <div class="col-sm-4 mt-3 mt-md-0">)

[//]: # (    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %})

[//]: # (  </div>)

[//]: # (</div>)

[//]: # (```)