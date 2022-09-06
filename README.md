# Fashion AI Video Virtual Try-On
<b>`Individual Research`,`Computer Vision`, `Video Processing`,`OpenCV`, `TorchVision` </b>

#### Related Work: [Smart Mirror Fashion AI](https://github.com/SJSUMS/SMART-MIRROR-FASHION-AI_SMFAI) / [Paper](https://drive.google.com/file/d/1AnocCvgEmQP2fdZu_HuTD_Mg2Pc4YmuU/view) / [Results](https://github.com/SJSUMS/SMART-MIRROR-FASHION-AI_SMFAI/blob/main/SMFAI_Results.pdf)

Autor: [mavisw](https://github.com/mavisw)

## Motivation
<p>The fashion artificial intelligence (FAI) industry is lucrative and competitive. According to
Statista, the global FAI market is projected to be 4.4 billion U.S. dollars by 2027 (Statista, 2020). Many
fashion retail businesses have incorporated FAI technologies into their market strategies for segmentation
and try-before-you-buy service to optimize sales and customer experience. Due to the Covid-19
pandemic, customer shopping behavior has been transformed from the traditional in-store experience to a
digitized space. As a result, the demand for virtual fitting rooms has become immediate.</p>


#### Problem with Smart-Mirror Fitting Room
1. High Cost: High cost of the AI technology investment (ex. Smart Mirror).
2. Data Privacy: Privacy concern over the concept of the virtual fitting room.
4. Shopping behavior: Customer has been changed their shopping pattern from in-store to online.
3. Impractical use case: In addition to #1, #2 and #3, a smart-mirror-based ecommerce online shopping model can be easily replaced by a handy mobile shopping experience, which aligns more with the identified customer behavior and trend.

## Business Goal
- Find opportunity to integrate AI technology to help clothing retailers boost sales.

## Use Cases
1. Online shopping
2. InStore shopping

## Objectives
- Reduce return rates.
- Motivate online sales.
- Incentivise instore shopping.

## Proposed Solutions
1. A Web Application, allowing users to upload their custom posed video to try on any cloth images.
2. In-store Smart-Mirror Kiosk


## Methodology
- [x] 3-stage ML modules Network
1. Real-time Body Pose Detection and Segmentation
2. Garment Segmentation
3. Video Reconstruction
- [x] Transfer learning

### ML Tasks
- [x] Data Collection and Preprocessing (Training and Testing)
- [x] Data Processing (Raw Video and Garment Image Processing)
- [x] Individual module development, testing, and improvement
- [x] Test Video Object Tracking
- [x] Model Integration
- [x] Network pipeline testing, evaluation
- [x] System Design & Testing
    - [x] AI-Powered Functionality
    - [x] Features
- [x] MVP Web Application Demo

## Model Improvement
- Body Parsing (Segmentation): Improved human parsing (fixed-neck)
- Improved body pose estimation <br>

## MVP Features
- [x] Upload a customed video from computer
- [x] Select predefined clothing images
- [x] Preview/Upload New video and body alignment
- [x] Play Result Video and Switch Clothing


# Conclusion / Contribution
1. Market Analysis
2. Recast imaged-based try-on model into video-based transfer learning.
3. Significant model improvement in SSIM for body segmentation, compared to CP-VTON and Shine-On.
4. Successfully integrated and deployed a 3-staged ML system network in Flask.
5. Buit a consumer facing interface MVP AI-Powered Web application to demonstrate product-market opportunity.


### Citation
	@InProceedings{SJSU MSDA Program Project SMFAI,
		title={Smart Mirror-Based Fashion AI Based on Machine Learning},
		author={Mavis Wang, Coco Yu, Xiaocen Xie, Ililta Gebrihiwet},
		month = {May},
		year = {2022}
	}
