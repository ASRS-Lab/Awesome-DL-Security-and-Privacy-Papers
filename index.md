---
layout: default
---

<p align='center'>
<img src="https://img.shields.io/github/stars/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/forks/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://badges.toozhao.com/badges/01J84J9TP68RXS90T6MYGYY0CH/blue.svg" />
<!--<a href="README.zh-CN.md"><img src="https://img.shields.io/badge/文档-中文版-blue.svg" alt="CN doc"></a>
<a href="README.md"><img src="https://img.shields.io/badge/document-English-blue.svg" alt="EN doc"></a>-->
<img src="https://img.shields.io/github/repo-size/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/issues/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
<img src="https://img.shields.io/github/issues-pr/ASRS-Lab/Awesome-DL-Security-and-Privacy-Papers.svg">
</p>
# Table of Contents

- [Refine by venue](#Refine-by-venue)
- [Refine by theme](#Refine-by-venue)
  - [1. Survey](#1-survey)
  - [2. Poison & Backdoor](#2-poison-and-backdoor)
    - [2.1. Visual Task](#21-visual-task)
      - [2.1.1. Image Classification](#211-image-classification)
      - [2.1.2. Object Detection](#212-object-detection)
      - [2.1.3. 3D Object Detection](#213-3d-object-detection)
      - [2.1.4. Image Segmentation](#214-image-segmentation)
      - [2.1.5. Person Re-Identification](#215-person-re-identification)
      - [3. Adversarial Examples](#3-adversarial-examples)

# List of Papers
## Refine by venue

> **Venue list:** 
>
> - **Artificial Intelligence:** AAAI(46) > NeurIPS(42) > CVPR(39) > ICLR(38) > ICML(24) > IJCAI(18) > ACL(18) > ICCV(16) > ECCV(10)
> - **Multimedia:** ICASSP(29) > ACM MM(20) > ICME(7)
> - **Information Security:** S&P(30) > Usenix Security(25) > NDSS(11) > CCS(11) > AsiaCCS(7)
> - **Journal:** TIFS(32) > COSE(22) > TDSC(16)
>
> **Update:** 2024.11.21

### CVPR 

#### 2024

1. ⚔️ **Physical Backdoor: Towards Temperature-Based Backdoor Attacks in the Physical World.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.01210)] 
   - Wen Yin, Jian Lou, Pan Zhou, Yulai Xie, Dan Feng, Yuhua Sun, Tailai Zhang, Lichao Sun. *CVPR 2024.*
2. ⚔️ **Adversarial Backdoor Attack by Naturalistic Data Poisoning on Trajectory Prediction in Autonomous Driving.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.01410)]
   - Mozhgan Pourkeshavarz, Mohammad Sabokrou, Amir Rasouli. CVPR 2024.
3. ⚔️ **BadCLIP: Trigger-Aware Prompt Learning for Backdoor Attacks on CLIP.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02288)]
   - Jiawang Bai, Kuofeng Gao, Shaobo Min, Shu-Tao Xia, Zhifeng Li, Wei Liu. *CVPR 2024.*
4. ⚔️ **Data Poisoning Based Backdoor Attacks to Contrastive Learning.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02299)]
   - Jinghuai Zhang, Hongbin Liu, Jinyuan Jia, Neil Zhenqiang Gong. CVPR 2024.
5. 🛡**Not All Prompts Are Secure: A Switchable Backdoor Attack Against Pre-trained Vision Transfomers.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02306)]
   - Sheng Yang, Jiawang Bai, Kuofeng Gao, Yong Yang, Yiming Li, Shu-Tao Xia. CVPR 2024.
6. 🛡**Nearest is Not Dearest: Towards Practical Defense Against Quantization-Conditioned Backdoor Attacks.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02315)]
   - Boheng Li, Yishuo Cai, Haowei Li, Feng Xue, Zhifeng Li, Yiming Li. *CVPR 2024.*
7. 🛡**Backdoor Defense via Test-Time Detecting and Repairing.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02319)] 
   - Jiyang Guan, Jian Liang, Ran He. *CVPR 2024.* 
8. ⚔️ **BadCLIP: Dual-Embedding Guided Backdoor Attack on Multimodal Contrastive Learning.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02327)]
   - Siyuan Liang, Mingli Zhu, Aishan Liu, Baoyuan Wu, Xiaochun Cao, Ee-Chien Chang. *CVPR 2024.*
9. ⚔️ **Lotus: Evasive and Resilient Backdoor Attacks through Sub-Partitioning.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02342)]
   - Siyuan Cheng, Guanhong Tao, Yingqi Liu, Guangyu Shen, Shengwei An, Shiwei Feng, Xiangzhe Xu, Kaiyuan Zhang, Shiqing Ma, Xiangyu Zhang. *CVPR 2024.*
10. 🛡**Semantic Shield: Defending Vision-Language Models Against Backdooring and Poisoning via Fine-Grained Knowledge Alignment.** [[pdf](https://doi.org/10.1109/CVPR52733.2024.02344)]
    - Alvi Md. Ishmam, Christopher Thomas. *CVPR 2024.*

#### 2023
1. 🛡**Backdoor Defense via Adaptively Splitting Poisoned Dataset.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.00390)]
   - Kuofeng Gao, Yang Bai, Jindong Gu, Yong Yang, Shu-Tao Xia. *CVPR 2023.*
2. ⚔️ **How to Backdoor Diffusion Models?** [[pdf](https://doi.org/10.1109/CVPR52729.2023.00391)]
   - Sheng-Yen Chou, Pin-Yu Chen, Tsung-Yi Ho. *CVPR 2023.*
3. ⚔️ **Single Image Backdoor Inversion via Robust Smoothed Classifiers.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.00784)]
   - Mingjie Sun, Zico Kolter. *CVPR 2023.*
4. ⚔️ **Color Backdoor: A Robust Poisoning Attack in Color Space.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.00786)]
   - Wenbo Jiang, Hongwei Li, Guowen Xu, Tianwei Zhang. *CVPR 2023.*
5. 🛡**Backdoor Cleansing with Unlabeled Data.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01176)]
   - Lu Pang, Tao Sun, Haibin Ling, Chao Chen. *CVPR 2023.*
6. 🛡**Backdoor Defense via Deconfounded Representation Learning.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01177)]
   - Zaixi Zhang, Qi Liu, Zhicai Wang, Zepu Lu, Qingyong Hu. *CVPR 2023.*
7. 🛡**Defending Against Patch-based Backdoor Attacks on Self-Supervised Learning.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01178)]
   - Ajinkya Tejankar, Maziar Sanjabi, Qifan Wang, Sinong Wang, Hamed Firooz, Hamed Pirsiavash, Liang Tan. *CVPR 2023.*
8. ⚔️ **Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01179)]
   - Yi Yu, Yufei Wang, Wenhan Yang, Shijian Lu, Yap-Peng Tan, Alex C. Kot. *CVPR 2023.*
9. 🛡**Detecting Backdoors in Pre-trained Encoders.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01569)]
   - Shiwei Feng, Guanhong Tao, Siyuan Cheng, Guangyu Shen, Xiangzhe Xu, Yingqi Liu, Kaiyuan Zhang, Shiqing Ma, Xiangyu Zhang. *CVPR 2023.*
10. 🛡**Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01570)]
    - Xiaogeng Liu, Minghui Li, Haoyu Wang, Shengshan Hu, Dengpan Ye, Hai Jin, Libing Wu, Chaowei Xiao. *CVPR 2023.*
11. 🛡**MEDIC: Remove Model Backdoors via Importance Driven Cloning.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01962)]
    - Qiuling Xu, Guanhong Tao, Jean Honorio, Yingqi Liu, Shengwei An, Guangyu Shen, Siyuan Cheng, Xiangyu Zhang. *CVPR 2023.*
12. 🛡**Progressive Backdoor Erasing via connecting Backdoor and Adversarial Attacks.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.01963)]
    - Bingxu Mu, Zhenxing Niu, Le Wang, Xue Wang, Qiguang Miao, Rong Jin, Gang Hua. *CVPR 2023.*
13. ⚔️ **The Dark Side of Dynamic Routing Neural Networks: Towards Efficiency Backdoor Injection.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.02355)]
    - Simin Chen, Hanlin Chen, Mirazul Haque, Cong Liu, Wei Yang. *CVPR 2023.*
14. ⚔️ **Architectural Backdoors in Neural Networks.** [[pdf](https://doi.org/10.1109/CVPR52729.2023.02356)]
    - Mikel Bober-Irizar, Ilia Shumailov, Yiren Zhao, Robert D. Mullins, Nicolas Papernot. *CVPR 2023.*
15. ⚔️ **You Are Catching My Attention: Are Vision Transformers Bad Learners under Backdoor Attacks?** [[pdf](https://doi.org/10.1109/CVPR52729.2023.02357)]
    - Zenghui Yuan, Pan Zhou, Kai Zou, Yu Cheng. *CVPR 2023.*

#### 2022

1. ⚔️ **Backdoor Attacks on Self-Supervised Learning.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01298)]
   - Aniruddha Saha, Ajinkya Tejankar, Soroush Abbasi Koohpayegani, Hamed Pirsiavash. *CVPR 2022.*
2. ⚔️ **Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01299)]
   - Xiangyu Qi, Tinghao Xie, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu. *CVPR 2022.*
3. 🛡**Few-shot Backdoor Defense Using Shapley Estimation.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01300)]
   - Jiyang Guan, Zhuozhuo Tu, Ran He, Dacheng Tao. *CVPR 2022.*
4. **🛡Better Trigger Inversion Optimization in Backdoor Scanning.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01301)]
   - Guanhong Tao, Guangyu Shen, Yingqi Liu, Shengwei An, Qiuling Xu, Shiqing Ma, Pan Li, Xiangyu Zhang. *CVPR 2022.*
5. 🛡**Complex Backdoor Detection by Symmetric Feature Differencing.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01458)]
   - Yingqi Liu, Guangyu Shen, Guanhong Tao, Zhenting Wang, Shiqing Ma, Xiangyu Zhang. *CVPR 2022.*
6. ⚔️ **DEFEAT: Deep Hidden Feature Backdoor Attacks by Imperceptible Perturbation and Latent Representation Constraints.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01478)]
   - Zhendong Zhao, Xiaojun Chen, Yuexin Xuan, Ye Dong, Dakui Wang, Kaitai Liang. *CVPR 2022.*
7. ⚔️ **Dual-Key Multimodal Backdoors for Visual Question Answering.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.01494)]
   - Matthew Walmer, Karan Sikka, Indranil Sur, Abhinav Shrivastava, Susmit Jha. *CVPR 2022.*
8. ⚔️ **FIBA: Frequency-Injection based Backdoor Attack in Medical Image Analysis.** [[pdf](https://doi.org/10.1109/CVPR52688.2022.02021)]
   - Yu Feng, Benteng Ma, Jing Zhang, Shanshan Zhao, Yong Xia, Dacheng Tao. *CVPR 2022.*

#### 2021

1. ⚔️ **Backdoor Attacks Against Deep Learning Systems in the Physical World.** [[pdf](https://doi.org/10.1109/CVPR46437.2021.00614)]
   - Emily Wenger, Josephine Passananti, Arjun Nitin Bhagoji, Yuanshun Yao, Haitao Zheng, Ben Y. Zhao. *CVPR 2021.*

#### 2020

1. ⚔️ **Universal Litmus Patterns: Revealing Backdoor Attacks in CNNs.** [[pdf](https://openaccess.thecvf.com/content_CVPR_2020/html/Kolouri_Universal_Litmus_Patterns_Revealing_Backdoor_Attacks_in_CNNs_CVPR_2020_paper.html)]
   - Soheil Kolouri, Aniruddha Saha, Hamed Pirsiavash, Heiko Hoffmann. *CVPR 2020.*
2. ⚔️ **Clean-Label Backdoor Attacks on Video Recognition Models.** [[pdf](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.html)]
   - Shihao Zhao, Xingjun Ma, Xiang Zheng, James Bailey, Jingjing Chen, Yu-Gang Jiang. *CVPR 2020.*






## Refine by theme

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

### 2.1. Visual Task

#### 2.1.1. Image Classification

1. **BadNets: Identifying Vulnerabilities in the Machine Learning Model Supply Chain.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D"></span>
   - Tianyu Gu, Brendan Dolan-Gavitt, Siddharth Garg. *Arxiv, 2017.* `BadNets.`
2. **Invisible Backdoor Attack against 3D Point Cloud Classifier in Graph Spectral Domain.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545"></span>
   - Linkun Fan, Fazhi He, Tongzhen Si, Wei Tang, Bing Li. *AAAI, 2024.* `3D Point Cloud.`



#### 2.1.2. Object Detection

1. **Untargeted backdoor attack against object detection.** <span><img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_B-FFC008"></span>
   - Chengxiao Luo,Yiming Li, Yong Jiang, Shu-Tao Xia. *ICASSP, 2023.* 
2. **Mask-based Invisible Backdoor Attacks on Object Detection.**
   - Jeongjin Shin. *Arxiv, 2023.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
3. **Attacking by Aligning: Clean-Label Backdoor Attacks on Object Detection.**
   - Yize Cheng, Wenbin Hu, Minhao Cheng. *Arxiv, 2023.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
4. **BadDet: Backdoor Attacks on Object Detection.** 
   - Shih-Han Chan, Yinpeng Dong, Jun Zhu, Xiaolu Zhang, Jun Zhou. *ECCV workshops, 2022.* <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">



#### 2.1.3. 3D Object Detection

1. **BadFusion: 2D-Oriented Backdoor Attacks against 3D Object Detection.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Saket S. Chaturvedi, Lan Zhang, Wenbin Zhang, Pan He, Xiaoyong Yuan. *IJCAI, 2024.*



#### 2.1.4. Image Segmentation

1. **BadSAM: Exploring Security Vulnerabilities of SAM via Backdoor Attacks (Student Abstract).** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
  - Zihan Guan, Mengxuan Hu, Zhongliang Zhou, Jielu Zhang, Sheng Li, Ninghao Liu. *AAAI, 2024.*



#### 2.1.5. Person Re-Identification

1. **Invisible backdoor attack with dynamic triggers against person re-identification.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   -  Wenli Sun, Xinyang Jiang, Shuguang Dou, Dongsheng Li, Duoqian Miao, Cheng Deng, Cairong Zhao. *TIFS, 2024.*
2. **DiffPhysBA: Diffusion-based Physical Backdoor Attack against Person Re-Identification in Real-World.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
   - Wenli Sun, Xinyang Jiang, Dongsheng Li, Cairong Zhao. *arxiv, 2024.*



#### 2.1.6. Video Recognition

1. **PALETTE : Physically-Realizable Backdoor Attacks Against Video Recognition Models.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Xueluan Gong, Zheng Fang, Bowen Li, Tao Wang, Yanjiao Chen, Qian Wang. *TDSC, 2024.*
2. **Temporal-Distributed Backdoor Attack against Video Based Action Recognition.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Xi Li, Songhe Wang, Ruiquan Huang, Mahanth Gowda, George Kesidis. *AAAI, 2024.*
3. **Clean-Label Backdoor Attacks on Video Recognition Models.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Shihao Zhao, Xingjun Ma, Xiang Zheng, James Bailey, Jingjing Chen, Yu-Gang Jiang. *CVPR, 2020.*





### 2.2. Textual Task

#### 2.2.1. Text-to-Image

1. **Large Language Models are Good Attackers: Efficient and Stealthy Textual Backdoor Attacks.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_None-6C757D">
   - Ziqiang Li, Yueqi Zeng, Pengfei Xia, Lei Liu, Zhangjie Fu, Bin Li. *arxiv, 2024.*
2. **Personalization as a Shortcut for Few-Shot Backdoor Attack against Text-to-Image Diffusion Models.** <img style="vertical-align: middle" src="https://img.shields.io/badge/CCF_A-DC3545">
   - Yihao Huang, Felix Juefei-Xu, Qing Guo, Jie Zhang, Yutong Wu, Ming Hu, Tianlin Li, Geguang Pu, Yang Liu. *AAAI, 2024.*





### 2.3. Federated Learning

1. **Beyond Traditional Threats: A Persistent Backdoor Attack on Federated Learning.**
   - *AAAI, 2024.*
2. **Resisting Backdoor Attacks in Federated Learning via Bidirectional Elections and Individual Perspective.**
   - *AAAI, 2024.*
3. **Chronic Poisoning: Backdoor Attack against Split Learning.**
   - *AAAI, 2024.*
4. **On the Vulnerability of Backdoor Defenses for Federated Learning.**
   - *AAAI, 2023.*
5. **Poisoning with Cerberus: Stealthy and Colluded Backdoor Attack against Federated Learning.**
   - *AAAI, 2023.*



- **A Spatiotemporal Backdoor Attack Against Behavior-Oriented Decision Makers in Metaverse: From Perspective of Autonomous Driving.** [[pdf](https://ieeexplore.ieee.org/abstract/document/10368076)] `keywords: Spatiotemporal Backdoor Attack, Reinforcement Learning.`
  - Yinbo Yu, Jiajia Liu, Hongzhi Guo, Bomin Mao, Nei Kato. *IEEE Journal of Selected Areas in Communications (JSAC), 2024. (CCF-A)* 
- **WaTrojan: Wavelet domain trigger injection for backdoor attacks.** [pdf]







---



#### 1.3. Diffusion Model



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

####  

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
  
  

#### 1.XX. Others

- **Progressive Poisoned Data Isolation for Training-Time Backdoor Defense.**
  - Yiming Chen, Haiwei Wu, Jiantao Zhou. *AAAI, 2024.*
- **Conditional Backdoor Attack via JPEG Compression.**
  - Qiuyu Duan, Zhongyun Hua, Qing Liao, Yushu Zhang, Leo Yu Zhang. *AAAI, 2024.*
- **A Dual Stealthy Backdoor: From Both Spatial and Frequency Perspectives.**
  - *AAAI, 2024.*
- **COMBAT: Alternated Training for Effective Clean-Label Backdoor Attacks.**
  - *AAAI, 2024.*
- **Backdoor Attacks via Machine Unlearning.**
  - *AAAI, 2024.*
- **Poisoning-Based Backdoor Attacks in Computer Vision.**
  - *AAAI, 2023.*

### 3. Adversarial Examples



## Acknowledgement



