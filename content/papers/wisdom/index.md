---
title: "On-Device Deep Learning for IoT-based Wireless Sensing Applications" 
date: 2024-02-01

tags: ["Wireless Sensing","TinyML","IoT","Embedded Systems"]
author: ["Manoj Kumar Lenka", "Ayon Chakraborty"]
description: "Recent Wi-Fi sensing literature uses deep neural networks to analyze wireless channel dynamics. This being a resource intensive process is usually carried out at the edge, but this isn't always practical due to cost and bandwidth constraints. We propose on-device sensing for IoT platforms, introducing WISDOM to optimize inference models based on hardware and application needs. WISDOM achieves better utility than baseline models in over 85% of cases. It will be published in proceedings of PerCom Workshop 2024, Biarritz, France." 
summary: "Recent Wi-Fi sensing literature uses deep neural networks to analyze wireless channel dynamics. This being a resource intensive process is usually carried out at the edge, but this isn't always practical due to cost and bandwidth constraints. We propose on-device sensing for IoT platforms, introducing WISDOM to optimize inference models based on hardware and application needs. WISDOM achieves better utility than baseline models in over 85% of cases. It will be published in proceedings of PerCom Workshop 2024, Biarritz, France." 
editPost:
    Text: "PerCom Workshops 2024"

---

##### View

+ [Paper - TBA]()
+ [Artifact Paper](artifact_wisdom.pdf)
+ [Code](https://github.com/senselab-iitm/wisdom)
+ [Data](https://drive.google.com/drive/u/2/folders/13Crp-owAzkjZVH85AhisW9Yfi78wsoMf)
+ [Website](http://cse.iitm.ac.in/~sense/wisdom/)

---

##### Abstract

Recent innovations in Wi-Fi sensing capitalizes on a host of powerful deep neural network architectures that make inferences based on minute spatio-temporal dynamics in the wireless channel.
Many of such inference techniques being resource intensive, conventional wisdom recommends offloading them to the network edge for further processing.
In this paper, we argue that edge based sensing is often not a viable option for many applications (cost, bandwidth, latency etc).
Rather, we explore the paradigm of on-device Wi-Fi sensing where inference is carried out locally on resource constrained IoT platforms.
We present extensive benchmark results characterizing the resource consumption (memory, energy) and the performance (accuracy, inference rate) of some typical sensing tasks.
We propose WISDOM, a framework that, depending on capabilities of the hardware platform and application’s requirements, can compress the inference model. Such context aware compression aims to improve the overall utility of the system - maximal inference performance at minimal resource costs.
We demonstrate that models obtained using the Wisdom framework achieve higher utility compared to baseline models in more than 85% of cases.

---

##### Citation

###### Workshop

M. Lenka and A. Chakraborty, “On-Device Deep Learning for IoT-based Wireless Sensing Applications,” in 2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops), Biarritz, France, 2024

```BibTeX
@inproceedings{lenka2024wisdom,
	title={On-Device Deep Learning for IoT-based Wireless Sensing Applications},
	author={Lenka, Manoj and Chakraborty, Ayon},
	booktitle={2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops)},
    location={Biarritz, France},
	year={2024}
}
```
###### Artifact

M. Lenka and A. Chakraborty, “ARTIFACT: On-Device Deep Learning for IoT-based Wireless Sensing Applications,” in 2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops), Biarritz, France, 2024

```BibTeX
@inproceedings{lenka2024wisdomartifact,
	title={ARTIFACT: On-Device Deep Learning for IoT-based Wireless Sensing Applications},
	author={Lenka, Manoj and Chakraborty, Ayon},
	booktitle={2024 IEEE International Conference on Pervasive Computing and Communications Workshops and other Affiliated Events (PerCom Workshops)},
    location={Biarritz, France},
	year={2024}
}
```

