# Fashion AI Video Virtual Try-On
<b>`Individual Research`,`Computer Vision`, `Video Processing`,`OpenCV`, `TorchVision` </b>
<br>
Related Work: 
[Smart Mirror Fashion AI](https://github.com/SJSUMS/SMART-MIRROR-FASHION-AI_SMFAI) | [Paper](https://drive.google.com/file/d/1AnocCvgEmQP2fdZu_HuTD_Mg2Pc4YmuU/view)
<br>
Autor: [mavisw](https://github.com/mavisw)

## Motivation

## Business Goal

## Market Analysis

## Target Audience

## Problem

## Proposed Solution
- Web Application for mobile upload 

## ML Network
- 3-stage ML network
- Segmentation (Body and clothing)
- Object Detaction (Pose estimation)
- Image Reconstruction (Warping and reconstruction)

## Model Improvement
- Body Parsing (Segmentation): Improved human parsing (fixed-neck)
- Improved body pose estimation <br>

## Results
<img src="https://raw.githubusercontent.com/SJSUMS/SMFAI/main/samples/SMFAI_VVT.gif"></img><br>

## Features

## MVP Web App


# Summary

# Contribution
1. Improved body segmentation


### SMFAI Modules
- [x] Video Processing and Tracking @ Mavis Wang
- [x] Garment Mask @ Xiaocen Xie
- [x] Human body Pose Shape Estimation @ Mavis Wang
- [x] CP-VTON GMM @ Ililta Gebrihiwet
- [x] CP-VTON TOM @ Coco Yu

### Tasks
- [x] Roadmap
- [x] Data collection
- [x] Finalize test dataset - ref_person video
- [x] Finalize test dataset - target cloth
- [x] Individual module development, testing, and improvement
- [x] Test Video Object Tracking
- [x] SMFAI network pipeline testing
- [x] Network development
- [x] Network testing
- [x] Network evaluation
- [x] Models integration

### Citation
	@InProceedings{SJSU MSDA Program Project SMFAI,
		title={Smart Mirror-Based Fashion AI Based on Machine Learning},
		author={Mavis Wang, Coco Yu, Xiaocen Xie, Ililta Gebrihiwet},
		month = {May},
		year = {2022}
	}
	@InProceedings{Minar_CPP_2020_CVPR_Workshops,
		title={CP-VTON+: Clothing Shape and Texture Preserving Image-Based Virtual Try-On},
		author={Minar, Matiur Rahman and Thai Thanh Tuan and Ahn, Heejune and Rosin, Paul and Lai, Yu-Kun},
		booktitle = {The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
		month = {June},
		year = {2020}
	}
	
This project is highly influenced by [Toward Characteristic-Preserving Image-based Virtual Try-On Network](https://arxiv.org/abs/1807.07688) 
and reproduced based on the repo [CP-VTON-Plus](https://github.com/minar09/cp-vton-plus) Network.
