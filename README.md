---
title: "UAVM 2025"
collection: pages
permalink: /ACMMM2025Workshop-UAV
author_profile: false
---



 <div align='center' > 
  <h2> ACM Multimedia </h2>
 </div>

 <div align='center' style = "vertical-align:middle"> 
  <h2> <img src="https://2026.acmmm.org/assets/LOGO-ACM-2026-V2.png?raw=true" margin-right="20px" alt="ACM Multimedia conference 2026" ><a href="https://2026.acmmm.org/"> ACM MM 2026 </a><a href="https://2026.acmmm.org/">(https://2026.acmmm.org/)</a>  </h2>
 </div>
 
 <div align='center' > 
  <h2> Workshop on </h2>
  <h2> UAVs in Multimedia: Capturing the World from a New Perspective (UAVM 2026)
</h2>
 <img src="https://github.com/layumi/ACMMM2023Workshop/blob/main/picture/logo.png?raw=true" alt="workshop logo">
</div>

<meta name="og:image" content="https://github.com/layumi/ACMMM2023Workshop/blob/main/picture/logo.png?raw=true">
<meta name="og:description" content="UAVs in Multimedia: Capturing the World from a New Perspective (UAVM 2026)"> 
<meta name='description' content='ACMMM2026 The 4th Workshop on UAVs in Multimedia: Capturing the World from a New Perspective '>

The accept papers will be published at ACM Multimedia Workshop (top 50%), and go through the same peer review process as the regular papers. Several authors will be invited to do a oral presentation. 

## Important Dates

**Challenge**

* Challenge Start: 11 March 2026
* Challenge End: 30 June 2026

**Submission of papers:**

* Workshop Papers Submission End: 16 July 2026
* Workshop Papers Notification: 06 August 2026
* Student Travel Grants Application Deadline: TBD 
* Camera-ready Submission: 20 August 2026 
* Conference Dates: 10 November 2026 –14 November 2026

Please note: The submission deadline is at 11:59 p.m. of the stated deadline date [Anywhere on Earth](https://time.is/Anywhere_on_Earth)

## Abstract
Uncrewed aerial vehicles (UAVs), also known as drones, have grown in popularity in recent years due to their ability to capture high-quality multimedia data from above. As multimedia applications such as aerial photography, cinematography, and mapping have grown in popularity, UAVs have emerged as powerful tools for gathering rich, diverse multimedia content. This workshop aims to bring together researchers, practitioners, and enthusiasts interested in UAV multimedia to explore the latest advancements, challenges, and opportunities in this exciting field. Topics covered will include aerial image and video processing, machine learning for UAV data analysis, UAV swarm technology, and UAV-based multimedia applications. In the context of the ACM Multimedia Conference, this workshop is highly relevant, as multimedia data from UAVs is becoming an important source of content for many applications. It will provide a platform for researchers to share their work and discuss potential collaborations and an opportunity for practitioners to learn about the latest developments in UAV multimedia technology. Overall, this workshop provides a unique opportunity to explore the exciting, rapidly evolving field of UAV multimedia and its potential impact on the broader multimedia community.


**The list of possible topics includes, but is not limited to:**

*  Video-based UAV Navigation
    + Satellite-guided & Ground-guided Navigation
    + Path Planning and Obstacle Avoidance
    + Visual SLAM (Simultaneous Localization and Mapping)
    + Sensor Fusion and Reinforcement Learning for Navigation
* UAV Swarm Coordination
    + Multiple Platform Collaboration
    + Multi-agent Cooperation and Communication
    + Decentralized Control and Optimization
    + Distributed Perception and Mapping
* UAV-based Object Detection and Tracking
    + Aerial-view Object Detection, Tracking and Re-identification
    + Aerial-view Action Recognition
* UAV-based Sensing and Mapping
    + 3D Mapping and Reconstruction
    + Remote Sensing and Image Analysis
    + Disaster Response and Relief
* UAV-based Delivery and Transportation
    + Package Delivery and Logistics
    + Safety and Regulations for UAV-based Transportation


## Submission Types

Paper can be submitted on [[Open Review]](https://openreview.net/group?id=acmmm.org/ACMMM/2026/Workshop/UAVM).

Submission template can be found at [ACM](https://www.acm.org/publications/proceedings-template) or you may directly follow the [overleaf template](https://www.overleaf.com/read/yfpxtyngmzjn).

**We recommend the single-blind (showing your name and affilliation) for fast processing, but double-blind papers are also acceptable. We will ensure the fairness.**

In this workshop, we welcome four types of submissions, all of which should relate to the topics and themes as listed in Section 3: 

- (1). Challenge papers (**up to 4 pages in length, plus unlimited pages for references**): original solution to the Challenge data, University160k, in terms of effectiveness and efficiency. 

- (2). Original papers (**up to 4 pages in length, plus unlimited pages for references**): original ideas, perspectives, research vision, and open challenges in the area of evaluation approaches for UAVs in Multimedia; Page limits include diagrams and appendices.

Page limits include diagrams and appendices. Submissions should be single-blind, written in English, and formatted according to the current ACM two-column conference format. Suitable LaTeX, Word, and Overleaf templates are available from the ACM Website (use “sigconf” proceedings template for LaTeX and the Interim Template for Word).

**Tips:**
- For privacy protection, please blur faces in the published materials (such as paper, video, poster, etc.) 
- For social good, please do not contain any misleading words, such as ``surveillance`` and  ``secret``.


## Challenge

**Challenge Platform is at [https://codalab.lisn.upsaclay.fr/competitions/22073](https://codalab.lisn.upsaclay.fr/competitions/22073).**

This year, we introduce a new dataset and task targeting fine-grained localization. Specifically, we present PairUAV, which shifts the focus from cross-view retrieval to terminal-range pose alignment. 
Accurate UAV navigation during the final approach phase, often referred to as "last-meter" navigation, is critical for applications such as autonomous landing, delivery, and search-and-rescue, where GNSS may be unreliable and monocular vision suffers from scale ambiguity. To address this challenge, we introduce PairUAV, a fine-grained localization dataset derived from University-1652, providing explicit supervision for relative pose estimation. Unlike existing UAV localization benchmarks, PairUAV formulates navigation as a target-driven task, where a UAV agent must align its pose with a specified target image defining the goal location and orientation. PairUAV is the first dataset to support target-driven UAV navigation at this scale, containing over 4.8 million image pairs across 72 scenes.

An example of the task is shown below. Given a source image and a target image, participants must predict the relative translation and heading required to align the UAV with the target pose.

<img src="https://github.com/spyflying/ACMMM2025Workshop-UAV/blob/main/picture/example.png" width="320">

Check challenge details at Section 5 in [proposal](https://github.com/spyflying/ACMMM2026Workshop-UAV/blob/main/proposal.pdf)

The training dataset can be download by [Request](https://github.com/layumi/University1652-Baseline/blob/master/Request.md). Usually I will reply the download link in 5 minutes. The name-masked test set (query_street & gallery_satellite) can be downloaded from [OneDrive](https://hdueducn-my.sharepoint.com/:f:/g/personal/wongtyu_hdu_edu_cn/Esu6JIlwuBtAnr5VAEFaPzEBM1VjH6WVzWiWJjH0vLW4TQ?e=9JscAg).

The submission example can be found at [Baseline Submission](https://github.com/spyflying/ACMMM2025Workshop-UAV/blob/main/answer.zip). Please zip it as “answer.zip” to submit the result, and it is crucial to name the file exactly as answer.txt within the zip, as otherwise the evaluation will fail.

Please return the top-10 satellite names. For example, the first query is “VdthudbGjJ4aaNkl.jpeg”. Therefore, the first line of returned result in “answer.txt” should be the format as follows from Rank-1 to Rank-10:

```
ptHYAN3piG3YwOft       I9bzP8jnLlz9zpMi	      c3vVTLCzTAVzuapU       gkriPL4PNtcWoHgg       iIL2ASdQ5vrFsJs0       TinwNxUGYAzz0kTO      XilyyHqywhUBxHfT       WLasj720MnF13zPI       Qz4NypYGPhHdiAvn       gO2hUfIHC8N4ZWKz
```

Please return the result following the order of query at [Query TXT](https://github.com/spyflying/ACMMM2025Workshop-UAV/blob/main/query_street_name.txt). It will be 2759 lines.

## FAQ - Frequently Asked Questions

#### Q1: Can we use the original University-1652 test set for training?
**A1:** No, the University-1652 test set must not be used in any form for training. Please only use the official training set and the name-masked test set provided via our links.

#### Q2: Can we use extra training datasets beyond the provided University-1652 training set?
**A2:** Yes, extra training datasets are allowed in this competition. Participants may use additional data sources to improve performance, as long as no information from the name-masked test set is used in any way during training. For reference, [*VehicleNet*](https://www.zdzheng.xyz/files/TMM20.pdf) fuses 4 datasets for a similar retrieval competition. We encourage participants to disclose any external datasets and their usage details in the method description for transparency.


## Related Papers 
- Wang, T., Zheng, Z., Sun, Y., Yan, C., Yang, Y., & Chua, T. S. (2024). [Multiple-environment Self-adaptive Network for Aerial-view Geo-localization](https://zdzheng.xyz/files/PR2024-Wang.pdf). Pattern Recognition, 152, 110363.
- Zheng, Z., Wei, Y., & Yang, Y. (2020, October). [University-1652: A multi-view multi-source benchmark for drone-based geo-localization](https://zdzheng.xyz/files/ACMMM20.pdf). In Proceedings of the 28th ACM international conference on Multimedia (pp. 1395-1403).
- Wang, C., Zheng, Z., Quan, R., Sun, Y., & Yang, Y. (2023). [Context-aware pretraining for efficient blind image decomposition](https://zdzheng.xyz/files/CVPR2023-Wang.pdf). In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 18186-18195).
- Chu, M., Zheng, Z., Ji, W., & Chua, T. S. (2024). [Towards Natural Language-Guided Drones: GeoText-1652 Benchmark with Spatially Relation Matching](https://arxiv.org/abs/2311.12751). ECCV.
- Zheng, Z., Ruan, T., Wei, Y., Yang, Y., & Mei, T. (2020). [VehicleNet: Learning Robust Visual Representation for Vehicle Re-identification](https://www.zdzheng.xyz/files/TMM20.pdf). TMM.

## Organizing Team

| <img src="https://skyy93.github.io/assets/img/avatar.jpeg?raw=true" width="160"> | |<img src="https://github.com/wtyhub/Photo/blob/a713229943f0628ffb82556bc9e396bbfabe8567/1%20inch.jpg?raw=true" width="160"> |
| :-: | :-: | :-: |
| [Fabian Deuser](https://skyy93.github.io/), University of the Bundeswehr Munich, Germany | [Yaxuan Li](https://yaxuanli-cn.github.io), University of Macau, China | [Tingyu Wang](https://scholar.google.com/citations?user=wv3H-F4AAAAJ), Hangzhou Dianzi University, China | 
| <img src="https://yujiaoshi.github.io/images/YujiaoShiCircle.jpg?raw=true" width="160"> | | <img src="https://spyflying.github.io/images/android-chrome-512x512.png" width=160> |
[Yujiao Shi](https://yujiaoshi.github.io/), ShanghaiTech University, China | Anna Bößendörfer, University of the Bundeswehr Munich | [Shaofei Huang](https://spyflying.github.io/), University of Macau, China |
<img src="https://github.com/spyflying/ACMMM2025Workshop-UAV/blob/main/picture/pan.jpeg?raw=true" width="160"> | <img src="https://github.com/layumi/ICME2022SS/raw/main/picture/1.png?raw=true" width="160"> | <img src="https://www.comp.nus.edu.sg/~sochr/www/stfphotos/rogerz.jpg?raw=true" width="160"> |
[Xiao Pan](https://scholar.google.com/citations?user=5Rh3yn4AAAAJ&hl=en/), Shenzhen University, China | [Zhedong Zheng](https://zdzheng.xyz), University of Macau, China | [Roger Zimmermann](https://www.comp.nus.edu.sg/cs/people/rogerz/), National University of Singapore, Singapore |


## Conference and Journal Papers

All papers presented at ACMMM 2026 will be included in ACM proceeding. All papers submitted to this workshop will go through the same review process as the regular papers submitted to the main conference to ensure that the contributions are of high quality. 


## Student Traval Funding

Please check https://acmmm2026.org/

## Workshop Citation
```bibtex
@inproceedings{deuser2026UVA,
  title={The 4th Workshop on UAVs in Multimedia: Capturing the World from a New Perspective},
  author={Deuser, Fabian and Li, Yaxuan and Wang, Tingyu and Shi, Yujiao and  and Bößendörfer, Anna and Huang, Shaofei and Pan, Xiao and Zheng, Zhedong and Zimmermann, Roger},
  booktitle={Proceedings of the 34th ACM International Conference on Multimedia Workshop},
  year={2026}
}  
```