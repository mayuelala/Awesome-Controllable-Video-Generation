# Awesome-Controllable-Video-Generation
🚀🚀🚀A curated list of papers on controllable video generation. Please join us for more comprehensive summary. If you have any additions to the list, please raise them in the issue section. 欢迎补充👏


# 🤗 Introduction



# 📋 Contents
- [Awesome-Controllable-Video-Generation](#awesome-controllable-video-generation)
- [🤗 Introduction](#-introduction)
- [📋 Contents](#-contents)
- [💘 Tips](#-tips)
  - [🔹 Single Control](#-single-control)
    - [🌟 Character Control/ID/Video Customization/Personalization](#-character-controlidvideo-customizationpersonalization)
    - [📍 Spatial Control](#-spatial-control)
      - [🕺 Pose Control](#-pose-control)
      - [🚗 BEV-Control](#-bev-control)
      - [🎨 Style Control](#-style-control)
      - [📌 Point Control](#-point-control)
      - [📏 Depth Control](#-depth-control)
      - [🗺️ Landmark Control](#️-landmark-control)
    - [✍️ Text Rendering](#️-text-rendering)
    - [⏳ Temporal Control](#-temporal-control)
      - [🌊 Flow-Guided](#-flow-guided)
      - [📸 Camera-Guided](#-camera-guided)
      - [🛤️ Traj-Guided](#️-traj-guided)
      - [🎥 Motion Customization/Motion Mask/Motion Video(traj)](#-motion-customizationmotion-maskmotion-videotraj)
    - [📝 Advanced Text-Conditioned](#-advanced-text-conditioned)
    - [🔄 In-Context](#-in-context)
    - [🖼️ Image-guided](#️-image-guided)
    - [🔊 Sound-Guided](#-sound-guided)
    - [🎵 Audio/Music-Guided](#-audiomusic-guided)
    - [🗂️ Layout Control](#️-layout-control)
    - [✏️ Sketch Control](#️-sketch-control)
    - [🤲 Language-Gesture Controlled](#-language-gesture-controlled)
  - [🔸 Multi Control/I2V](#-multi-controli2v)
    - [🖼️ + 🛤️ Image + Traj](#️--️-image--traj)
    - [🖼️ + 📸 Image + Camera](#️---image--camera)
    - [🛤️ + 📸 Traj + Camera](#️---traj--camera)
    - [🖼️ + 🔊 Image + Audio](#️---image--audio)
    - [🎥 + 📸 Video + Camera](#---video--camera)
    - [🖼️ + 🌊 Image + Flow](#️---image--flow)
    - [🖼️ + 🕺 Image + Pose](#️---image--pose)
    - [✍️ + 🔊 Text + Sound](#️---text--sound)
    - [🌟 + 🎥 Personalized + Motion](#---personalized--motion)
  - [❓ To be sorted](#-to-be-sorted)
  - [🌐 Unified controllable generation](#-unified-controllable-generation)


# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Paper searching via tag**: You can also search the related papers via the following tags: `customization`, `iteractive`, `human motion generation` `tokenizer`. (More tags are ongoing)


## 🔹 Single Control

### 🌟 Character Control/ID/Video Customization/Personalization

+ **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** (13 Jul 2023)<details><summary>Yingqing He, Menghan Xia, Haoxin Chen, et al.</summary>
        Yingqing He, Menghan Xia, Haoxin Chen, Xiaodong Cun, Yuan Gong, Jinbo Xing, Yong Zhang, Xintao Wang, Chao Weng, Ying Shan, Qifeng Chen</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
        [![Code](https://img.shields.io/github/stars/VideoCrafter/Animate-A-Story.svg?style=social&label=Star)](https://github.com/VideoCrafter/Animate-A-Story)
+ **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Fuchen Long, Zhaofan Qiu, Ting Yao, et al.</summary>
        Fuchen Long, Zhaofan Qiu, Ting Yao, Tao Mei</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
        [![Project](https://img.shields.io/badge/Project-111111.svg)](https://videodrafter.github.io/)
+ **Vlogger: Make Your Dream A Vlog** (17 Jan 2024)<details><summary>Shaobin Zhuang, Kunchang Li, Xinyuan Chen, et al.</summary>
        Shaobin Zhuang, Kunchang Li, Xinyuan Chen, Yaohui Wang, Ziwei Liu, Yu Qiao, Yali Wang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09414)
        [![Code](https://img.shields.io/github/stars/zhuangshaobin/Vlogger.svg?style=social&label=Star)](https://github.com/zhuangshaobin/Vlogger)
+ **VideoBooth: Diffusion-based Video Generation with Image Prompts** (1 Dec 2023)<details><summary>Yuming Jiang, Tianxing Wu, Shuai Yang, et al.</summary>
        Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)
        [![Code](https://img.shields.io/github/stars/Vchitect/VideoBooth.svg?style=social&label=Star)](https://github.com/Vchitect/VideoBooth)
+ **Magic-Me: Identity-Specific Video Customized Diffusion** (14 Feb 2024)<details><summary>Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, et al.</summary>
        Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, Xue-She Wang, Xiuyu Li, Huanrui Yang, Zhen Dong, Kurt Keutzer, Jiashi Feng</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368)
        [![Code](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social&label=Star)](https://github.com/Zhen-Dong/Magic-Me)
+ **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production** (12 Mar 2024)<details><summary>Jiuniu Wang, Zehua Du, Yuyuan Zhao, et al.</summary>
        Jiuniu Wang, Zehua Du, Yuyuan Zhao, Bo Yuan, Kexiang Wang, Jian Liang, Yaxi Zhao, Yihen Lu, Gengliang Li, Junlong Gao, Xin Tu, Zhenyu Guo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07952)
+ **Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation** (19 Aug 2024)<details><summary>Yunxin Li, Haoyuan Shi, Baotian Hu, et al.</summary>
        Yunxin Li, Haoyuan Shi, Baotian Hu, Longyue Wang, Jiashun Zhu, Jinyi Xu, Zhen Zhao, Min Zhang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)
        [![Code](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)](https://github.com/HITsz-TMG/Anim-Director)
+ **DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control** (21 May 2024)<details><summary>Hong Chen, Xin Wang, Yipeng Zhang, et al.</summary>
        Hong Chen, Xin Wang, Yipeng Zhang, Yuwei Zhou, Zeyang Zhang, Siao Tang, Wenwu Zhu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.12796)
+ **StoryAgent: Customized Storytelling Video Generation via Multi-Agent Collaboration** (7 Nov 2024)<details><summary>Panwen Hu, Jin Jiang, Jianqi Chen, et al.</summary>
        Panwen Hu, Jin Jiang, Jianqi Chen, Mingfei Han, Shengcai Liao, Xiaojun Chang, Xiaodan Liang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04925)
+ **MIMO: Controllable Character Video Synthesis with Spatial Decomposed Modeling** (24 Sep 2024)<details><summary>Yifang Men, Yuan Yao, Miaomiao Cui, et al.</summary>
        Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16160)
        [![Code](https://img.shields.io/github/stars/menyifang/MIMO.svg?style=social&label=Star)](https://github.com/menyifang/MIMO)
+ **MovieCharacter: A Tuning-Free Framework for Controllable Character Video Synthesis** (28 Oct 2024)<details><summary>Di Qiu, Zheng Chen, Rui Wang, et al.</summary>
        Di Qiu, Zheng Chen, Rui Wang, Mingyuan Fan, Changqian Yu, Junshi Huang, Xiang Wen</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20974)
+ **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** (12 Feb 2025)<details><summary>Zhao Wang, Hao Wen, Lingting Zhu, et al.</summary>
        Zhao Wang, Hao Wen, Lingting Zhu, Chenming Shang, Yujiu Yang, Qi Dou</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189)
        [![Code](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social&label=Star)](https://github.com/AnyCharV/AnyCharV) 
+ **DreamRunner: Fine-Grained Compositional Story-to-Video Generation with Retrieval-Augmented Motion Adaptation** (25 Nov 2024)<details><summary>Zun Wang, Jialu Li, Han Lin, et al.</summary>
        Zun Wang, Jialu Li, Han Lin, Jaehong Yoon, Mohit Bansal</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16657)
        [![Code](https://img.shields.io/github/stars/wz0919/DreamRunner.svg?style=social&label=Star)](https://github.com/wz0919/DreamRunner)
+ **Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers** (9 May 2024)<details><summary>Peng Gao, Le Zhuo, Dongyang Liu, et al.</summary>
        Peng Gao, Le Zhuo, Dongyang Liu, Ruoyi Du, Xu Luo, Longtian Qiu, Yuhang Zhang, Chen Lin, Rongjie Huang, Shijie Geng, Renrui Zhang, Junlin Xi, Wenqi Shao, Zhengkai Jiang, Tianshuo Yang, Weicai Ye, He Tong, Jingwen He, Yu Qiao, Hongsheng Li</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05945)
        [![Code](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-T2X.svg?style=social&label=Star)](https://github.com/Alpha-VLLM/Lumina-T2X)
+ **VIMI: Grounding Video Generation through Multi-modal Instruction** (8 Jul 2024)<details><summary>Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, et al.</summary>
        Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, Tsai-Shien Chen, Kuan-Chien Wang, Ivan Skorokhodov, Graham Neubig, Sergey Tulyakov</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06304)
+ **SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control** (28 Mar 2024)<details><summary>Zheng Chen, Di Qiu, Rui Wang, et al.</summary>
        Binyuan Huang, Yuqing Wen, Yucheng Zhao, Yaosi Hu, Yingfei Liu, Fan Jia, Weixin Mao, Tiancai Wang, Chi Zhang, Chang Wen Chen, Zhenzhong Chen, Xiangyu Zhang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.19438)
        [![Project](https://img.shields.io/badge/Project-111111.svg)](https://subjectdrive.github.io/)
+ **VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models** (27 Dec 2024)<details><summary>Tao Wu, Yong Zhang, Xiaodong Cun, et al.</summary>
        Tao Wu, Yong Zhang, Xiaodong Cun, Zhongang Qi, Junfu Pu, Huanzhang Dou, Guangcong Zheng, Ying Shan, Xi Li</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19645)
        [![Code](https://img.shields.io/github/stars/WuTao-CS/VideoMaker.svg?style=social&label=Star)](https://github.com/WuTao-CS/VideoMaker)
+ **EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion** (23 Jan 2025)<details><summary>Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, et al.</summary>
        Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, Boyuan Liu, Renjie Chen, Mingyu Guo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.13452)
+ **SUGAR: Subject-Driven Video Customization in a Zero-Shot Manner** (13 Dec 2024)<details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary>
        Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Nanxuan Zhao, Jing Shi, Tong Sun</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10533)
+ **Multi-subject Open-set Personalization in Video Generation** (10 Jan 2025)<details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, et al.</summary>
        Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Kwot Sin Lee, Ivan Skorokhodov, Kfir Aberman, Jun-Yan Zhu, Ming-Hsuan Yang, Sergey Tulyakov</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06187)
        [![Code](https://img.shields.io/github/stars/snap-research/MSRVTT-Personalization.svg?style=social&label=Star)](https://github.com/snap-research/MSRVTT-Personalization)
+ **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** (4 Feb 2025)<details><summary>Feng Liang, Haoyu Ma, Zecheng He, et al.</summary>
        Feng Liang, Haoyu Ma, Zecheng He, Tingbo Hou, Ji Hou, Kunpeng Li, Xiaoliang Dai, Felix Juefei-Xu, Samaneh Azadi, Animesh Sinha, Peizhao Zhang, Peter Vajda, Diana Marculescu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07802)
+ **CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training** (20 Dec 2024)<details><summary>Xiuli Bi, Jian Lu, Bo Liu, et al.</summary>
        Xiuli Bi, Jian Lu, Bo Liu, Xiaodong Cun, Yong Zhang, Weisheng Li, Bin Xiao</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15646)
        [![Code](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/RongPiKing/CustomTTT)
+ **DreamRelation: Relation-Centric Video Customization** (10 Mar 2025)<details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, et al.</summary>
        Yujie Wei, Shiwei Zhang, Hangjie Yuan, Biao Gong, Longxiang Tang, Xiang Wang, Haonan Qiu, Hengjia Li, Shuai Tan, Yingya Zhang, Hongming Shan</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06033)
+ **Get In Video: Add Anything You Want to the Video** (8 Mar 2025)<details><summary>Shaobin Zhuang, Zhipeng Huang, Binxin Yang, et al.</summary>
        Shaobin Zhuang, Zhipeng Huang, Binxin Yang, Ying Zhang, Fangyikang Wang, Canmiao Fu, Chong Sun, Zheng-Jun Zha, Chen Li, Yali Wang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06268)
+ **Phantom: Subject-consistent video generation via cross-modal alignment** (16 Feb 2025)<details><summary>Lijie Liu, Tianxiang Ma, Bingchuan Li, et al.</summary>
        Lijie Liu, Tianxiang Ma, Bingchuan Li, Zhuowei Chen, Jiawei Liu, Qian He, Xinglong Wu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11079)
        [![Code](https://img.shields.io/github/stars/Phantom-video/Phantom.svg?style=social&label=Star)](https://github.com/Phantom-video/Phantom)


### 📍 Spatial Control

#### 🕺 Pose Control

#### 🚗 BEV-Control

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

### 🎵 Audio/Music-Guided

### 🗂️ Layout Control

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
