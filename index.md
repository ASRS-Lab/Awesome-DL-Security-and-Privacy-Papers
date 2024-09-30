---
layout: default
---

<p align='center'>
<img src="https://img.shields.io/github/stars/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/forks/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://badges.toozhao.com/badges/01J84J9TP68RXS90T6MYGYY0CH/blue.svg" />
<a href="README.zh-CN.md"><img src="https://img.shields.io/badge/文档-中文版-blue.svg" alt="CN doc"></a>
<a href="README.md"><img src="https://img.shields.io/badge/document-English-blue.svg" alt="EN doc"></a>
<img src="https://img.shields.io/github/repo-size/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/issues/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/issues-pr/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
</p>
## Table of Contents

- [1. Survey](#1-survey)
- [2. Poison & Backdoor](#2-poison-and-backdoor)
  - [2.1. Image Classification](#21-image-classification)
  - [2.2. Object Detection](#22-object-detection)
  - [1.1. Image Segmentation (图像分割)](#11-Image-Segmentation)
  - [1.3. Diffusion Model (扩散模型)](#13-Diffusion-Model)
  - [1.4. Reinforcement Learning (强化学习)](#14-Reinforcement-Learning)
  - [1.5. Recommendation Systems (推荐系统)](#15-Recommendation-Systems)
  - [1.6. Few-shot Learning (小样本学习)](#16-Few-shot-Learning)
  - [1.7. Federated Learning (联邦学习)](#17-Federated-Learning)
  - [1.X. Others](#1X-Others)
- [3. Adversarial Examples](#3-adversarial-examples)

## List of Papers

### 1. Survey

1. **Backdoor Learning: A Survey.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_B-FFC008">
  - Yiming Li, Yong Jiang, Zhifeng Li, Shu-Tao Xia. *TNNLS, 2024.* `backdoor attack`
2. **Physical Adversarial Attack Meets Computer Vision: A Decade Survey.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
  - Hui Wei, Hao Tang, Xuemei Jia, Zhixiang Wang, Hanxun Yu, Zhubo Li, Shin’ichi Satoh, Luc Van Gool, Zheng Wang. *TPAMI, 2024.* `physical adversarial attack`
3. **Physical Adversarial Attacks for Surveillance: A survey.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_B-FFC008">
   - Kien Nguyen , Tharindu Fernando , Clinton Fookes , Sridha Sridharan. *TNNLS, 2023.* `physical adversarial attack`
4. **A Survey on Physical Adversarial Attack in Computer Vision.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
   - Donghua Wang, Wen Yao, Tingsong Jiang, Guijian Tang, Xiaoqian Chen. *Arxiv, 2023.* `Physical adversarial attack`
5. **Visually adversarial attacks and defenses in the physical world: A survey.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
   - Xingxing Wei, Bangzheng Pu, Jiefan Lu, Baoyuan Wu. *Arxiv, 2022.* `adversarial attack`
6. **A survey of practical adversarial example attacks.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_C-28A745">
   - Lu Sun, Mingtian Tan, Zhe Zhou. *Cybersecurity, 2018.* `adversarial attack`

### 2. Poison and Backdoor

#### 2.1. Image Classification

1. **BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D"></span>
   - Tianyu Gu, Brendan Dolan-Gavitt, Siddharth Garg. *Arxiv, 2017.* `BadNets.`
2. **Invisible Backdoor Attack against 3D Point Cloud Classifier in Graph Spectral Domain.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545"></span>
   - Linkun Fan, Fazhi He, Tongzhen Si, Wei Tang, Bing Li. *AAAI, 2024.* `3D Point Cloud.`

#### 2.2. Object Detection

1. **Untargeted backdoor attack against object detection.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_B-FFC008"></span>
   - Chengxiao Luo,Yiming Li, Yong Jiang, Shu-Tao Xia. *ICASSP, 2023.* 
2. **Mask-based Invisible Backdoor Attacks on Object Detection.**
   - Jeongjin Shin. *Arxiv, 2023.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
3. **Attacking by Aligning: Clean-Label Backdoor Attacks on Object Detection.**
   - Yize Cheng, Wenbin Hu, Minhao Cheng. *Arxiv, 2023.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
4. **BadDet: Backdoor Attacks on Object Detection.** 
   - Shih-Han Chan, Yinpeng Dong, Jun Zhu, Xiaolu Zhang, Jun Zhou. *ECCV workshops, 2022.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">



#### 3D Object Detection

1. **BadFusion: 2D-Oriented Backdoor Attacks against 3D Object Detection.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Saket S. Chaturvedi, Lan Zhang, Wenbin Zhang, Pan He, Xiaoyong Yuan. *IJCAI, 2024.*
2. 











---

#### 3.2. Image Segmentation

- **BadSAM: Exploring Security Vulnerabilities of SAM via Backdoor Attacks (Student Abstract).** <span><img src="https://img.shields.io/badge/CCF_A-DC3545"></span>
  - Zihan Guan, Mengxuan Hu, Zhongliang Zhou, Jielu Zhang, Sheng Li, Ninghao Liu. *AAAI, 2024*. 

#### 1.3. Diffusion Model

- **Personalization as a Shortcut for Few-Shot Backdoor Attack against Text-to-Image Diffusion Models.**
  - Yihao Huang, Felix Juefei-Xu, Qing Guo, Jie Zhang, Yutong Wu, Ming Hu, Tianlin Li, Geguang Pu, Yang Liu. *AAAI, 2024.*
- **Elijah: Eliminating Backdoors Injected in Diffusion Models via Distribution Shift.**
  - Shengwei An, Sheng-Yen Chou, Kaiyuan Zhang, Qiuling Xu, Guanhong Tao, Guangyu Shen, Siyuan Cheng, Shiqing Ma, Pin-Yu Chen, Tsung-Yi Ho, Xiangyu Zhang. *AAAI, 2024.*

#### 1.4. Reinforcement Learning

- **BadRL: Sparse Targeted Backdoor Attack against Reinforcement Learning.**
  - Jing Cui, Yufei Han, Yuzhe Ma, Jianbin Jiao, Junge Zhang. *AAAI, 2024.*

#### 1.5. Recommendation Systems

- **Backdoor Adjustment via Group Adaptation for Debiased Coupon Recommendations.**
  - Junpeng Fang, Gongduo Zhang, Qing Cui, Caizhi Tang, Lihong Gu, Longfei Li, Jinjie Gu, Jun Zhou. *AAAI, 2024.*

#### 1.6. Few-shot Learning

- **Does Few-Shot Learning Suffer from Backdoor Attacks?**
  - *AAAI, 2024.*

#### 1.7. Federated Learning

- **Beyond Traditional Threats: A Persistent Backdoor Attack on Federated Learning.**
  - *AAAI, 2024.*
- **Resisting Backdoor Attacks in Federated Learning via Bidirectional Elections and Individual Perspective.**
  - *AAAI, 2024.*
- **Chronic Poisoning: Backdoor Attack against Split Learning.**
  - *AAAI, 2024.*
- **On the Vulnerability of Backdoor Defenses for Federated Learning.**
  - *AAAI, 2023.*
- **Poisoning with Cerberus: Stealthy and Colluded Backdoor Attack against Federated Learning.**
  - *AAAI, 2023.*

- **A Spatiotemporal Backdoor Attack Against Behavior-Oriented Decision Makers in Metaverse: From Perspective of Autonomous Driving.** [[pdf](https://ieeexplore.ieee.org/abstract/document/10368076)] `keywords: Spatiotemporal Backdoor Attack, Reinforcement Learning.`
  - Yinbo Yu, Jiajia Liu, Hongzhi Guo, Bomin Mao, Nei Kato. *IEEE Journal of Selected Areas in Communications (JSAC), 2024. (CCF-A)* 
- **WaTrojan: Wavelet domain trigger injection for backdoor attacks.** [pdf]

#### 1.X. Defense

- **Inspecting Prediction Confidence for Detecting Black-Box Backdoor Attacks.**
  - *AAAI, 2024.*
- **UMA: Facilitating Backdoor Scanning via Unlearning-Based Model Ablation.**
  - *AAAI, 2024.*
- **DataElixir: Purifying Poisoned Dataset to Mitigate Backdoor Attacks via Diffusion Models.**
  - *AAAI, 2024.*
- **SEER: Backdoor Detection for Vision-Language Models through Searching Target Text and Image Trigger Jointly**
  - *AAAI, 2024.*
- **Defending Backdoor Attacks on Vision Transformer via Patch Processing.**
  - *AAAI, 2023.*
- 

#### 1.XX. Others

- **Progressive Poisoned Data Isolation for Training-Time Backdoor Defense.**
  - Yiming Chen, Haiwei Wu, Jiantao Zhou. *AAAI, 2024.*
- **Conditional Backdoor Attack via JPEG Compression.**
  - Qiuyu Duan, Zhongyun Hua, Qing Liao, Yushu Zhang, Leo Yu Zhang. *AAAI, 2024.*
- **A Dual Stealthy Backdoor: From Both Spatial and Frequency Perspectives.**
  - *AAAI, 2024.*
- **COMBAT: Alternated Training for Effective Clean-Label Backdoor Attacks.**
  - *AAAI, 2024.*
- **Temporal-Distributed Backdoor Attack against Video Based Action Recognition.**
  - *AAAI, 2024.*
- **Backdoor Attacks via Machine Unlearning.**
  - *AAAI, 2024.*
- **Poisoning-Based Backdoor Attacks in Computer Vision.**
  - *AAAI, 2023.*

### 3. Adversarial Examples



## Acknowledgement



