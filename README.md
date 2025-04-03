# Awesome-Controllable-Video-Generation
🚀🚀🚀A curated list of papers on controllable video generation. Please join us for more comprehensive summary. If you have any additions to the list, please raise them in the issue section. 欢迎补充👏


# 🤗 Introduction



# 📋 Contents
- [🤗 Introduction](#-introduction)
- [📋 Contents](#-contents)
- [💘 Tips](#-tips)
  - [Video Generation](#video-generation)
    - [Single Control](#single-control)
      - [Character Control/ID/Video Customization/Personalization](#character-controlidvideo-customizationpersonalization)
        - [Spatial Control](#spatial-control)
        - [Pose Control](#pose-control)
        - [BEV-Control](#bev-control)
        - [Style Control](#style-control)
        - [Point Control](#point-control)
        - [Depth Control](#depth-control)
        - [Landmark Control](#landmark-control)
      - [Text Rendering](#text-rendering)
      - [Temporal Control](#temporal-control)
        - [Flow-Guided](#flow-guided)
        - [Camera-Guided](#camera-guided)
        - [Traj-Guided](#traj-guided)
        - [Motion Customization/Motion Mask/Motion Video(traj)](#motion-customizationmotion-maskmotion-videotraj)
      - [Advanced Text-Conditioned](#advanced-text-conditioned)
      - [In-Context](#in-context)
      - [Image-guided](#image-guided)
      - [Sound-Guided](#sound-guided)
      - [Audio/Music-Guided](#audiomusic-guided)
      - [Layout Control](#layout-control)
      - [Sketch Control](#sketch-control)
      - [Language-Gesture Controlled](#language-gesture-controlled)
    - [Multi Control/I2V](#multi-controli2v)
      - [Image + Traj](#image--traj)
      - [Image + Camera](#image--camera)
      - [Traj + Camera](#traj--camera)
      - [Image + Audio](#image--audio)
      - [Video + Camera](#video--camera)
      - [Image + Flow](#image--flow)
      - [Image + Pose](#image--pose)
      - [Text + Sound](#text--sound)
      - [Personalized + Motion](#personalized--motion)
    - [Unified Controllable Generation](#unified-controllable-generation)

- [📍 Related Surveys](#-related-surveys)

- [👨‍💻 Team](#-team)
- [😉 Citation](#-citation)
- [⭐️ Star History](#️-star-history)


# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Paper searching via tag**: You can also search the related papers via the following tags: `customization`, `iteractive`, `human motion generation` `tokenizer`. (More tags are ongoing)


## 🔹 Single Control

### 🌟 Character Control/ID/Video Customization/Personalization

### 📍 Spatial Control

#### 🕺 Pose Control

#### 🚗 BEV-Control
+ **MagicDrive: Street View Generation with Diverse 3D Geometry Control** (04 Oct 2023)<details><summary>Ruiyuan Gao, Kai Chen, Enze Xie, et al.</summary>
Ruiyuan Gao, Kai Chen, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02601)
[![Code](https://img.shields.io/github/stars/cure-lab/MagicDrive.svg?style=social&label=Star)](https://github.com/cure-lab/MagicDrive)
[![Project](https://img.shields.io/badge/Project-111111.svg)](http://gaoruiyuan.com/magicdrive/)

+ **Panacea: Panoramic and Controllable Video Generation for Autonomous   Driving** (28 Nov 2023)<details><summary>Yuqing Wen, Yucheng Zhao, Yingfei Liu, et al.</summary>
Yuqing Wen, Yucheng Zhao, Yingfei Liu, Fan Jia, Yanhui Wang, Chong Luo, Chi Zhang, Tiancai Wang, Xiaoyan Sun, Xiangyu Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16813)
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://panacea-ad.github.io)

+ **DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video   Generation** (11 Mar 2024)<details><summary>Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, et al.</summary>
Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, Xinze Chen, Guan Huang, Xiaoyi Bao, Xingang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06845)
[![Code](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Star)](https://github.com/f1yfisher/DriveDreamer2)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://drivedreamer2.github.io)

+ **Unleashing Generalization of End-to-End Autonomous Driving with   Controllable Long Video Generation** (03 Jun 2024)<details><summary>Enhui Ma, Lijun Zhou, Tao Tang, et al.</summary>
Enhui Ma, Lijun Zhou, Tao Tang, Zhan Zhang, Dong Han, Junpeng Jiang, Kun Zhan, Peng Jia, Xianpeng Lang, Haiyang Sun, Di Lin, Kaicheng Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01349)
[![Code](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Star)](https://github.com/westlake-autolab/Delphi)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://westlake-autolab.github.io/delphi.github.io/)

+ **DiVE: DiT-based Video Generation with Enhanced Control** (03 Sep 2024)<details><summary>Junpeng Jiang, Gangyi Hong, Lijun Zhou, et al.</summary>
Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01595)
[![Code](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Star)](https://github.com/LiAutoAD/DIVE)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://liautoad.github.io/DIVE/)

+ **DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View   Driving Scenes** (06 Sep 2024)<details><summary>Jianbiao Mei, Tao Hu, Xuemeng Yang, et al.</summary>
Jianbiao Mei, Tao Hu, Xuemeng Yang, Licheng Wen, Yu Yang, Tiantian Wei, Yukai Ma, Min Dou, Botian Shi, Yong Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04003)
[![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star)](https://github.com/PJLab-ADG/DriveArena)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://pjlab-adg.github.io/DriveArena/dreamforge/)

+ **MagicDrive-V2: High-Resolution Long Video Generation for Autonomous   Driving with Adaptive Control** (21 Nov 2024)<details><summary>Ruiyuan Gao, Kai Chen, Bo Xiao, et al.</summary>
Ruiyuan Gao, Kai Chen, Bo Xiao, Lanqing Hong, Zhenguo Li, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.13807)
[![Code](https://img.shields.io/github/stars/flymin/MagicDrive-V2.svg?style=social&label=Star)](https://github.com/flymin/MagicDrive-V2)
[![Project](https://img.shields.io/badge/Project-111111.svg)](http://gaoruiyuan.com/magicdrive-v2/)

+ **Seeing Beyond Views: Multi-View Driving Scene Video Generation with   Holistic Attention** (04 Dec 2024)<details><summary>Hannan Lu, Xiaohe Wu, Shudong Wang, et al.</summary>
Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03520)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://luhannan.github.io/CogDrivingPage/)

#### 🎨 Style Control

#### 📌 Point Control

#### 📏 Depth Control

#### 🗺️ Landmark Control

### ✍️ Text Rendering

### ⏳ Temporal Control

#### 🌊 Flow-Guided

#### 📸 Camera-Guided

#### 🛤️ Traj-Guided

#### 🎥 Motion Customization/Motion Mask/Motion Video(traj)

### 📝 Advanced Text-Conditioned

### 🔄 In-Context

### 🖼️ Image-guided

### 🔊 Sound-Guided

+ **（ECCV 22) Sound-Guided Semantic Video Generation** (20 Apr 2022) <details><summary>Seung Hyun Lee, Gyeongrok Oh, Wonmin Byeon, et al.</summary>
Seung Hyun Lee, Gyeongrok Oh, Wonmin Byeon, Chanyoung Kim, Won Jeong Ryoo, Sang Ho Yoon, Hyunjun Cho, Jihyun Bae, Jinkyu Kim, Sangpil Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.09273)
[![Code](https://img.shields.io/github/stars/kuai-lab/sound2video.svg?style=social&label=Star)](https://github.com/kuai-lab/sound2video)
### 🎵 Audio/Music-Guided
+ **(AAAI 24) Diverse and Aligned Audio-to-Video Generation via Text-to-Video Model Adaptation** (28 Sep 2023)<details><summary>Guy Yariv, Itai Gat, Sagie Benaim, et al.</summary>
Guy Yariv, Itai Gat, Sagie Benaim, Lior Wolf, Idan Schwartz, Yossi Adi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
[![Code](https://img.shields.io/github/stars/guyyariv/TempoTokens.svg?style=social&label=Star)](https://github.com/guyyariv/TempoTokens)

+ **(ECCV 24) MOFA-Video: Controllable Image Animation via Generative Motion Field   Adaptions in Frozen Image-to-Video Diffusion Model** (30 May 2024) <details><summary>Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>
Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
[![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)

+ **(ECCV 24) Audio-Synchronized Visual Animation** (08 Mar 2024) <details><summary>Lin Zhang, Shentong Mo, Yijing Zhang, et al.</summary>
Lin Zhang, Shentong Mo, Yijing Zhang, Pedro Morgado </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05659)
[![Code](https://img.shields.io/github/stars/lzhangbj/ASVA.svg?style=social&label=Star)](https://github.com/lzhangbj/ASVA)

+ **(TMM) Ta2v: Text-audio guided video generation** (01 Jan 2024) <details><summary>Minglu Zhao, Wenmin Wang, Tongbao Chen, et al.</summary>
Minglu Zhao, Wenmin Wang, Tongbao Chen, Rui Zhang, Ruochen Li </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1109/TMM.2024.3362149)
[![Code](https://img.shields.io/github/stars/Minglu58/TA2V.svg?style=social&label=Star)](https://github.com/Minglu58/TA2V)

### 🗂️ Layout Control
+ **DrivingDiffusion: Layout-Guided multi-view driving scene video   generation with latent diffusion model** (11 Oct 2023)<details><summary>Xiaofan Li, Yifu Zhang, Xiaoqing Ye</summary>
Xiaofan Li, Yifu Zhang, Xiaoqing Ye</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.07771)
[![Code](https://img.shields.io/github/stars/shalfun/DrivingDiffusion.svg?style=social&label=Star)](https://github.com/shalfun/DrivingDiffusion)

+ **DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View   Driving Scenes** (06 Sep 2024)<details><summary>Jianbiao Mei, Tao Hu, Xuemeng Yang, et al.</summary>
Jianbiao Mei, Tao Hu, Xuemeng Yang, Licheng Wen, Yu Yang, Tiantian Wei, Yukai Ma, Min Dou, Botian Shi, Yong Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04003)
[![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star)](https://github.com/PJLab-ADG/DriveArena)

+ **Multi-object Video Generation from Single Frame Layouts** (06 May 2023)<details><summary>Yang Wu, Zhibin Liu, Hefeng Wu, et al.</summary>
Yang Wu, Zhibin Liu, Hefeng Wu, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03983)

+ **FlowZero: Zero-Shot Text-to-Video Synthesis with LLM-Driven Dynamic   Scene Syntax** (27 Nov 2023)<details><summary>Yu Lu, Linchao Zhu, Hehe Fan, et al.</summary>
Yu Lu, Linchao Zhu, Hehe Fan, Yi Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15813)
[![Code](https://img.shields.io/github/stars/aniki-ly/FlowZero.svg?style=social&label=Star)](https://github.com/aniki-ly/FlowZero)

+ **LLM-grounded Video Diffusion Models** (29 Sep 2023)<details><summary>Long Lian, Baifeng Shi, Adam Yala, et al.</summary>
Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17444)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedVideoDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)

+ **TrackDiffusion: Tracklet-Conditioned Video Generation via Diffusion   Models** (01 Dec 2023)<details><summary>Pengxiang Li, Kai Chen, Zhili Liu, et al.</summary>
Pengxiang Li, Kai Chen, Zhili Liu, Ruiyuan Gao, Lanqing Hong, Guo Zhou, Hua Yao, Dit-Yan Yeung, Huchuan Lu, Xu Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00651)
[![Code](https://img.shields.io/github/stars/pixeli99/TrackDiffusion.svg?style=social&label=Star)](https://github.com/pixeli99/TrackDiffusion)

+ **DiVE: DiT-based Video Generation with Enhanced Control** (03 Sep 2024)<details><summary>Junpeng Jiang, Gangyi Hong, Lijun Zhou, et al.</summary>
Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01595)
[![Code](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Star)](https://github.com/LiAutoAD/DIVE)

+ **Panacea: Panoramic and Controllable Video Generation for Autonomous   Driving** (28 Nov 2023)<details><summary>Yuqing Wen, Yucheng Zhao, Yingfei Liu, et al.</summary>
Yuqing Wen, Yucheng Zhao, Yingfei Liu, Fan Jia, Yanhui Wang, Chong Luo, Chi Zhang, Tiancai Wang, Xiaoyan Sun, Xiangyu Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16813)
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)

+ **DriveDreamer: Towards Real-world-driven World Models for Autonomous   Driving** (18 Sep 2023)<details><summary>Xiaofeng Wang, Zheng Zhu, Guan Huang, et al.</summary>
Xiaofeng Wang, Zheng Zhu, Guan Huang, Xinze Chen, Jiagang Zhu, Jiwen Lu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.09777)
[![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/DriveDreamer)

+ **DriveScape: Towards High-Resolution Controllable Multi-View Driving   Video Generation** (09 Sep 2024)<details><summary>Wei Wu, Xi Guo, Weixuan Tang, et al.</summary>
Wei Wu, Xi Guo, Weixuan Tang, Tingxuan Huang, Chiyu Wang, Dongyue Chen, Chenjing Ding</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05463)

+ **Unleashing Generalization of End-to-End Autonomous Driving with   Controllable Long Video Generation** (03 Jun 2024)<details><summary>Enhui Ma, Lijun Zhou, Tao Tang, et al.</summary>
Enhui Ma, Lijun Zhou, Tao Tang, Zhan Zhang, Dong Han, Junpeng Jiang, Kun Zhan, Peng Jia, Xianpeng Lang, Haiyang Sun, Di Lin, Kaicheng Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01349)
[![Code](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Star)](https://github.com/westlake-autolab/Delphi)

+ **HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for   Autonomous Driving** (02 Dec 2024)<details><summary>Zehuan Wu, Jingcheng Ni, Xiaodong Wang, et al.</summary>
Zehuan Wu, Jingcheng Ni, Xiaodong Wang, Yuxin Guo, Rui Chen, Lewei Lu, Jifeng Dai, Yuwen Xiong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01407)
### ✏️ Sketch Control

### 🤲 Language-Gesture Controlled

## 🔸 Multi Control/I2V

### 🖼️ + 🛤️ Image + Traj

### 🖼️ + 📸 Image + Camera

### 🛤️ + 📸 Traj + Camera

### 🖼️ + 🔊 Image + Audio

### 🎥 + 📸 Video + Camera

### 🖼️ + 🌊 Image + Flow

### 🖼️ + 🕺 Image + Pose

  + **StableAnimator: High-Quality Identity-Preserving Human Image Animation** (26 Nov 2024)<details><summary>Shuyuan Tu, Zhen Xing, Xintong Han, et al.</summary>
  Shuyuan Tu, Zhen Xing, Xintong Han, Zhi-Qi Cheng, Qi Dai, Chong Luo, Zuxuan Wu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17697)
  [![Code](https://img.shields.io/github/stars/Francis-Rings/StableAnimator.svg?style=social&label=Star)](https://github.com/Francis-Rings/StableAnimator)

  + **(MM24) AnimateAnywhere: Context-Controllable Human Video Generation with ID-Consistent One-shot Learning** (28 Oct 2024)<details><summary>Hengyuan Liu, Xiaodong Chen, Xinchen Liu, et al.</summary>
  Hengyuan Liu, Xiaodong Chen, Xinchen Liu, Xiaoyan Gu, Wu Liu</details>
    [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3688865.3689477)

  + **AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation** (26 Nov 2024)<details><summary>Ziyi Xu, Ziyao Huang, Juan Cao, et al.</summary>
  Ziyi Xu, Ziyao Huang, Juan Cao, Yong Zhang, Xiaodong Cun, Qing Shuai, Yuchen Wang, Linchao Bao, Jintao Li, Fan Tang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17383)
  [![Code](https://img.shields.io/github/stars/cangcz/AnchorCrafter.svg?style=social&label=Star)](https://github.com/cangcz/AnchorCrafter)

  + **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models** (3 Feb 2025)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
  Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)
  
  + **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** (28 Nov 2023)<details><summary>Li Hu, Xin Gao, Peng Zhang, et al.</summary>
  Li Hu, Xin Gao, Peng Zhang, Ke Sun, Bang Zhang, Liefeng Bo</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117v3)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone)
  
  + **(ECCV 24)Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (21 Mar 2024)<details><summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>
  Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
  [![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
  
  + **(ECCV 24) TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models** (12 Jul 2024)<details><summary>Jeongho Kim, Min-Jung Kim, Junsoo Lee, et al.</summary>
  Jeongho Kim, Min-Jung Kim, Junsoo Lee, Jaegul Choo</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09012)
  [![Code](https://img.shields.io/github/stars/eccv2024tcan/TCAN.svg?style=social&label=Star)](https://github.com/eccv2024tcan/TCAN)
  
  + **VividPose: Advancing Stable Video Diffusion for Realistic Human Image Animation** (28 May 2024)<details><summary>Qilin Wang, Zhengkai Jiang, Chengming Xu, et al.</summary>
  Qilin Wang, Zhengkai Jiang, Chengming Xu, Jiangning Zhang, Yabiao Wang, Xinyi Zhang, Yun Cao, Weijian Cao, Chengjie Wang, Yanwei Fu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18156)
  [![Code](https://img.shields.io/github/stars/Kelu007/VividPose.svg?style=social&label=Star)](https://github.com/Kelu007/VividPose)
  
  + **(ICCV 23) DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** (12 Apr 2023)<details><summary>Johanna Karras, Aleksander Holynski, Ting-Chun Wang, et al.</summary>
  Johanna Karras, Aleksander Holynski, Ting-Chun Wang, Ira Kemelmacher-Shlizerman</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025)
  [![Code](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose)
  
  + **(CVPR 24) DISCO: Disentangled Control for Realistic Human Dance Generation** (30 Jun 2023)<details><summary>Tan Wang, Linjie Li, Kevin Lin, et al.</summary>
  Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
  [![Code](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
  
  + **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance** (28 Jun 2024)<details><summary>Yuang Zhang, Jiaxi Gu, Li-Wen Wang, et al.</summary>
  Yuang Zhang, Jiaxi Gu, Li-Wen Wang, Han Wang, Junqi Cheng, Yuefeng Zhu, Fangyuan Zou</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)
  [![Code](https://img.shields.io/github/stars/Tencent/MimicMotion.svg?style=social&label=Star)](https://github.com/Tencent/MimicMotion)
  
  + **(ECCV 24) PoseCrafter: One-Shot Personalized Video Synthesis Following Flexible Pose Control** (23 May 2024)<details><summary>Yong Zhong, Min Zhao, Zebin You, et al.</summary>
  Yong Zhong, Min Zhao, Zebin You, Xiaofeng Yu, Changwang Zhang, Chongxuan Li</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14582)
  
  + **Follow-Your-Pose v2: Multiple-Condition Guided Character Image Animation for Stable Pose Control** (05 Jun 2024)<details><summary>Jingyun Xue, Hongfa Wang, Qi Tian, et al.</summary>
  Jingyun Xue, Hongfa Wang, Qi Tian, Yue Ma, Andong Wang, Zhiyuan Zhao, Shaobo Min, Wenzhe Zhao, Kaihao Zhang, Heung-Yeung Shum, Wei Liu, Mengyang Liu, Wenhan Luo</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03035v4)
  
  + **UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation** (3 Jun 2024)<details><summary>Xiang Wang, Shiwei Zhang, Changxin Gao, et al.</summary>
  Xiang Wang, Shiwei Zhang, Changxin Gao, Jiayu Wang, Xiaoqiang Zhou, Yingya Zhang, Luxin Yan, Nong Sang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188)
  [![Code](https://img.shields.io/github/stars/ali-vilab/UniAnimate.svg?style=social&label=Star)](https://github.com/ali-vilab/UniAnimate)
  
  + **Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation** (26 May 2024)<details><summary>Jinlin Liu, Kai Yu, Mengyang Feng, et al.</summary>
  Jinlin Liu, Kai Yu, Mengyang Feng, Xiefan Guo, Miaomiao Cui</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16393v2)
  
  + **Zero-shot High-fidelity and Pose-controllable Character Animation** (25 Jan 2025)<details><summary>Hossein Mirzaei, Mohammad Jafari, Hamid Reza Dehbashi, et al.</summary>
  Hossein Mirzaei, Mohammad Jafari, Hamid Reza Dehbashi, Zeinab Sadat Taghavi, Mohammad Sabokrou, Mohammad Hossein Rohban</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.15271v1)
  
  + **(CVPR 24) MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** (27 Nov 2023)<details><summary>Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, et al.</summary>
  Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
  [![Code](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
  
  + **DreaMoving: A Human Video Generation Framework based on Diffusion Models** (8 Dec 2023)<details><summary>Mengyang Feng, Jinlin Liu, Kai Yu, et al.</summary>
  Mengyang Feng, Jinlin Liu, Kai Yu, Yuan Yao, Zheng Hui, Xiefan Guo, Xianhui Lin, Haolan Xue, Chen Shi, Xiaowen Li, Aojie Li, Xiaoyang Kang, Biwen Lei, Miaomiao Cui, Peiran Ren, Xuansong Xie</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107)
  [![Code](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social&label=Star)](https://github.com/dreamoving/dreamoving-project)          

### ✍️ + 🔊 Text + Sound

### 🌟 + 🎥 Personalized + Motion

## ❓ To be sorted

## 🌐 Unified controllable generation
