# Architectural Enhancements to YOLOv12 for Thoracic Pathology Detection

[![DOI:10.1109/ICCP68926.2025.11427119](https://img.shields.io/badge/DOI-10.1109%2FICCP68926.2025.11427119-blue.svg)](https://doi.org/10.1109/ICCP68926.2025.11427119)
[![Conference: IEEE ICCP 2025](https://img.shields.io/badge/Conference-IEEE%20ICCP%202025-orange.svg)](https://iccp.ro/iccp2025/technical-program)

## Abstract
In recent years, artificial intelligence has played a pivotal role in advancing medical imaging, particularly in the early detection of thoracic diseases through chest X-rays. We propose an original deep learning model for affected area detection based on the **YOLOv12** object detection architecture, enhanced specifically for medical use cases. 

The improvements include attention mechanisms, deformable convolutions, and feature aggregation modules (FPN and PANet). Experimental results demonstrate that the proposed model achieves a **mAP@0.5 of 0.374** and a **Recall of 0.519**, outperforming existing models while maintaining a competitive inference time of **6.3 ms** per image.

##  Key Technical Contributions
This repository contains the implementation of the architectural modifications described in the paper:
* **High-Resolution Branch (P2):** Optimized for detecting small-scale pathologies like pulmonary nodules.
* **Attention Mechanisms (CBAM):** Integrated to enhance feature extraction focus.
* **Deformable Convolutions:** Implementation of adaptive receptive fields for irregular pathology shapes.
* **Hybrid Aggregation:** Custom Neck design using FPN and PANet for better multi-scale feature flow.

> [!IMPORTANT]  
> **Full Paper:** For detailed architectural diagrams, training hyperparameters, and ablation studies, please refer to the official publication on [IEEE Xplore](https://doi.org/10.1109/ICCP68926.2025.11427119).

## Citation
If you use this work in your research, please cite:
```latex
@INPROCEEDINGS{11427119,
  author={Andro, Ruxandra and Vancea, Cristian-Cosmin},
  booktitle={Proceedings of IEEE 21st International Conference on Intelligent Computer Communication and Processing (ICCP 2025)}, 
  title={Architectural Enhancements to YOLOv12 for Improving Detection of Thoracic Pathologies in Chest X-rays}, 
  year={2025},
  pages={1-8},
  doi={10.1109/ICCP68926.2025.11427119}}
