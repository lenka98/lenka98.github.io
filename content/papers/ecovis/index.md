---
title: "EcoVis: Towards Energy and Connectivity Optimized Visual Surveillance" 
date: 2025-03-17

tags: ["mmWave Radar","Wireless Sensing","Video Compression","TinyML","IoT","Embedded Systems"]
author: ["Manoj Kumar Lenka", "Ayon Chakraborty"]
description: "EcoVis leverages mmWave sensing to identify regions of interest (ROIs) for compressing surveillance video frames, reducing static background transmission and optimizing resource usage. Unlike traditional video-based methods, our approach lowers energy consumption by ~40% and enhances efficiency by ~25% through dynamic camera sleep cycles. For tasks like vehicle detection, EcoVis minimizes camera reliance, enabling on-device processing and improving network efficiency by ~20%. We also introduce uniform and non-uniform tiling algorithms that use mmWave-derived ROIs for tile-specific Quantization Parameter (QP) encoding, optimizing video compression. It will be published in proceedings of PerCom 2025, Washington D.C, USA." 
summary: "EcoVis leverages mmWave sensing to identify regions of interest (ROIs) for compressing surveillance video frames, reducing static background transmission and optimizing resource usage. Unlike traditional video-based methods, our approach lowers energy consumption by ~40% and enhances efficiency by ~25% through dynamic camera sleep cycles. For tasks like vehicle detection, EcoVis minimizes camera reliance, enabling on-device processing and improving network efficiency by ~20%. We also introduce uniform and non-uniform tiling algorithms that use mmWave-derived ROIs for tile-specific Quantization Parameter (QP) encoding, optimizing video compression. It will be published in proceedings of PerCom 2025, Washington D.C, USA." 
editPost:
    Text: "PerCom 2025"

---

##### View

+ [Paper](ecovis.pdf)

---

##### Abstract

Visual Analytics Pipelines (VAPs) for real-time surveillance are resource-intensive, consuming high energy and bandwidth. We propose EcoVis, a novel approach that uses mmWave sensing to identify regions of interest (ROIs) for compressing surveillance video frames. This reduces the transmission of static background, optimizing resource usage while maintaining high fidelity of content relevant in traffic surveillance. Unlike conventional methods that rely solely on video frames to detect ROIs, our use of mmWave range-azimuth maps achieves a comparable reduction in network bandwidth while lowering energy consumption by approximately 40%. Moreover, our approach enhances energy efficiency by nearly another 25%, by dynamically controlling the sleep cycle of the camera. For simpler tasks such as vehicle detection or counting, EcoVis works with minimal reliance of the camera. Due to its lower dimensionality compared to video, it allows on-device processing, improving operational speed and network efficiency by roughly 20%. Finally, we introduce both uniform and non-uniform tiling algorithms, utilizing RoIs derived from mmWave analysis. These algorithms enable video encoding with tile-specific Quantization Parameters (QPs), optimizing the overall compression process.

---

##### Citation

M. Lenka and A. Chakraborty, “EcoVis: Towards Energy and Connectivity Optimized Visual Surveillance,” in IEEE International Conference on Pervasive Computing and Communications (PerCom), Washington D.C, USA, 2025

```BibTeX
@inproceedings{lenka2024wisdom,
    title={EcoVis: Towards Energy and Connectivity Optimized Visual Surveillance},
    author={Lenka, Manoj and Chakraborty, Ayon},
    booktitle={IEEE International Conference on Pervasive Computing and Communications (PerCom)},
    location={Washington D.C, USA},
    year={2025}
}
```