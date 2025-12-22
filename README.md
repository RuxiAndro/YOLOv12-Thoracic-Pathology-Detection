# Architectural Enhancements to YOLOv12 for Thoracic Pathology Detection

##  Abstract
This research introduces a customized deep learning model based on **YOLOv12**, optimized for high-sensitivity detection of thoracic pathologies in chest X-rays. The model balances real-time inference performance with the precision required for medical diagnostics.

> **Publication:** Presented at the **IEEE 21st International Conference on Intelligent Computer Communication and Processing (ICCP 2025)**.

##  Proposed Solution & Enhancements
Unlike standard detectors, this version of YOLOv12 incorporates specific architectural changes to handle the complexity of medical images:

* **High-Resolution Detection Branch (P2):** Added specifically to improve the localization of small and subtle lesions that are often missed by standard scales.
* **Convolutional Block Attention Module (CBAM):** Enhances the model's focus on diagnostically relevant spatial and channel features, filtering out noise in X-ray scans.
* **Deformable Convolutions (DCN):** Increased architectural flexibility for detecting irregularly shaped pathologies, adapting the receptive field to the actual lesion form.
* **Optimized for Medical Use:** Fine-tuned to balance higher sensitivity (recall) with fast inference, crucial for clinical decision support systems.

##  Targeted Pathologies
The model is trained to identify:
* **Aortic enlargement** | **Cardiomegaly** | **Pleural effusion** | **Pulmonary nodules/masses** 

##  Repository Structure
* `/src`: Core implementation of the P2 branch, CBAM integration, and DCN layers.
* `/paper`: Research paper presented at IEEE ICCP 2025.


---
**Author:** Ruxandra Andro  
**Research Partners:** Cristian-Cosmin Vancea  
**Institution:** Technical University of Cluj-Napoca (UTCN)
