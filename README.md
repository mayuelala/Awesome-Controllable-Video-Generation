# 


<div align="center">
<!-- <h2><font color="red"> Awesome-Controllable-Video-Generation </h2> -->

 ![visitors](https://visitor-badge.laobi.icu/badge?page_id=mayuelala.Awesome-Controllable-Video-Generation&left_color=green&right_color=red)  [![GitHub](https://img.shields.io/github/stars/mayuelala/Awesome-Controllable-Video-Generation?style=social)](https://github.com/mayuelala/Awesome-Controllable-Video-Generation) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

🚀🚀🚀A curated list of papers on controllable video generation. Please join us for more comprehensive summary. If you have any additions to the list, please raise them in the issue section. 欢迎补充👏

</div>

# 🤗 Introduction



# 📋 Contents
- [](#)
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
      - [🎥 Motion Customization/Motion Mask/Motion Video](#-motion-customizationmotion-maskmotion-video)
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
    - [🖼️ + 💡 Image + Lighting](#️---image--lighting)
    - [✍️ + 🔊 Text + Sound](#️---text--sound)
    - [🌟 + 🎥 Personalized + Motion](#---personalized--motion)
  - [❓ To be sorted](#-to-be-sorted)
  - [🌐 Unified controllable generation](#-unified-controllable-generation)


# 💘 Tips
- **✅ Paper searching via catatogue**: directly clicking the content of the catatogue to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Free feel to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.


## 🔹 Single Control

### 🌟 Character Control/ID/Video Customization/Personalization
+ **OpenS2V-Nexus: A Detailed Benchmark and Million-Scale Dataset for Subject-to-Video Generation** (26 May 2025)
  <details><summary> Shenghai Yuan, Xianyi He, et al.</summary>
        Shenghai Yuan, Xianyi He, Yufan Deng, Yang Ye, Jinfa Huang, Bin Lin, Jiebo Luo, Li Yuan</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.20292)
   [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/OpenS2V-Nexus.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/OpenS2V-Nexus)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/OpenS2V-Nexus/)

+ **SkyReels-A2: Compose Anything in Video Diffusion Transformers** (3 Apr 2025)<details><summary>Zhengcong Fei, Debang Li, Di Qiu, et al.</summary>
        Zhengcong Fei, Debang Li, Di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2504.02436)
        [![Code](https://img.shields.io/github/stars/SkyworkAI/SkyReels-A2.svg?style=social&label=Star)](https://github.com/SkyworkAI/SkyReels-A2)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://skyworkai.github.io/skyreels-a2.github.io/)

+ **PERSONALVIDEO: High ID-Fidelity Video Customization with Static Images** (16 Mar 2025) 
   <details><summary>Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, et al.</summary>  
         Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, Yujie Wei, Zekun Li, Yingya Zhang, Boxi Wu, Deng Cai</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17048)

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
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://phantom-video.github.io/Phantom/)

+ **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** (12 Feb 2025)<details><summary>Zhao Wang, Hao Wen, Lingting Zhu, et al.</summary>
        Zhao Wang, Hao Wen, Lingting Zhu, Chenming Shang, Yujiu Yang, Qi Dou</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189)
        [![Code](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social&label=Star)](https://github.com/AnyCharV/AnyCharV)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://anycharv.github.io/)
 

+ **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** (4 Feb 2025)<details><summary>Feng Liang, Haoyu Ma, Zecheng He, et al.</summary>
        Feng Liang, Haoyu Ma, Zecheng He, Tingbo Hou, Ji Hou, Kunpeng Li, Xiaoliang Dai, Felix Juefei-Xu, Samaneh Azadi, Animesh Sinha, Peizhao Zhang, Peter Vajda, Diana Marculescu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07802)

+ **EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion** (23 Jan 2025)<details><summary>Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, et al.</summary>
        Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, Boyuan Liu, Renjie Chen, Mingyu Guo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.13452)
        [![Code](https://img.shields.io/github/stars/bytedance/EchoVideo.svg?style=social&label=Star)](https://github.com/bytedance/EchoVideo) 

+ **Multi-subject Open-set Personalization in Video Generation** (10 Jan 2025)<details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, et al.</summary>
        Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Kwot Sin Lee, Ivan Skorokhodov, Kfir Aberman, Jun-Yan Zhu, Ming-Hsuan Yang, Sergey Tulyakov</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06187)
        [![Code](https://img.shields.io/github/stars/snap-research/MSRVTT-Personalization.svg?style=social&label=Star)](https://github.com/snap-research/MSRVTT-Personalization)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/open-set-video-personalization/)

+ **ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning** (8 Jan 2025) 
   <details><summary>Yuzhou Huang, Ziyang Yuan, Quande Liu, et al.</summary>  
         Yuzhou Huang, Ziyang Yuan, Quande Liu, Qiulin Wang, Xintao Wang, Ruimao Zhang, Pengfei Wan, Di Zhang, Kun Gai</details>  
         
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04698)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://yuzhou914.github.io/ConceptMaster/)
+ **VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models** (27 Dec 2024)<details><summary>Tao Wu, Yong Zhang, Xiaodong Cun, et al.</summary>
        Tao Wu, Yong Zhang, Xiaodong Cun, Zhongang Qi, Junfu Pu, Huanzhang Dou, Guangcong Zheng, Ying Shan, Xi Li</details>
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19645)
   [![Code](https://img.shields.io/github/stars/WuTao-CS/VideoMaker.svg?style=social&label=Star)](https://github.com/WuTao-CS/VideoMaker)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://wutao-cs.github.io/VideoMaker/)

+ **Customcrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities** (27 Dec 2024)
   <details><summary>Tao Wu, Yong Zhang, Xintao Wang, et al.</summary>  
         Tao Wu, Yong Zhang, Xintao Wang, Xianpan Zhou, Guangcong Zheng, Zhongang Qi, Ying Shan, Xi Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13239)
   [![Code](https://img.shields.io/github/stars/WuTao-CS/CustomCrafter.svg?style=social&label=Star)](https://github.com/WuTao-CS/CustomCrafter)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://customcrafter.github.io/)
 
+ **CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training** (20 Dec 2024)<details><summary>Xiuli Bi, Jian Lu, Bo Liu, et al.</summary>
        Xiuli Bi, Jian Lu, Bo Liu, Xiaodong Cun, Yong Zhang, Weisheng Li, Bin Xiao</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15646)
        [![Code](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/RongPiKing/CustomTTT)

+ **SUGAR: Subject-Driven Video Customization in a Zero-Shot Manner** (13 Dec 2024)<details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary>
        Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Nanxuan Zhao, Jing Shi, Tong Sun</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10533)

+ **Identity-Preserving Text-to-Video Generation by Frequency Decomposition** (25 Nov 2024)
  <details><summary> Shenghai Yuan, Jinfa Huang, et al.</summary>
        Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
   [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ConsisID)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/ConsisID/)

+ **DreamRunner: Fine-Grained Compositional Story-to-Video Generation with Retrieval-Augmented Motion Adaptation** (25 Nov 2024)<details><summary>Zun Wang, Jialu Li, Han Lin, et al.</summary>
        Zun Wang, Jialu Li, Han Lin, Jaehong Yoon, Mohit Bansal</details>
      [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16657)
      [![Code](https://img.shields.io/github/stars/wz0919/DreamRunner.svg?style=social&label=Star)](https://github.com/wz0919/DreamRunner)
      [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://zunwang1.github.io/DreamRunner)

+ **VideoAlchemy: Open-set Personalization in Video Generation** (15 Nov 2024)
   <details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, et al.</summary>  
        Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Ivan Skorokhodov, Jun-Yan Zhu, Kfir Aberman, Ming-Hsuan Yang, Sergey Tulyakov </details>  

   [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=popKM1zAYa)   

+ **StoryAgent: Customized Storytelling Video Generation via Multi-Agent Collaboration** (7 Nov 2024)<details><summary>Panwen Hu, Jin Jiang, Jianqi Chen, et al.</summary>
        Panwen Hu, Jin Jiang, Jianqi Chen, Mingfei Han, Shengcai Liao, Xiaojun Chang, Xiaodan Liang</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04925)

+ **MotionBooth: Motion-Aware Customized Text-to-Video Generation** (29 Oct 2024)
   <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>  
         Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
   [![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/motionbooth/)

+ **MovieCharacter: A Tuning-Free Framework for Controllable Character Video Synthesis** (28 Oct 2024)<details><summary>Di Qiu, Zheng Chen, Rui Wang, et al.</summary>
        Di Qiu, Zheng Chen, Rui Wang, Mingyuan Fan, Changqian Yu, Junshi Huang, Xiang Wen</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20974)

+ **MIMO: Controllable Character Video Synthesis with Spatial Decomposed Modeling** (24 Sep 2024)<details><summary>Yifang Men, Yuan Yao, Miaomiao Cui, et al.</summary>
        Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16160)
        [![Code](https://img.shields.io/github/stars/menyifang/MIMO.svg?style=social&label=Star)](https://github.com/menyifang/MIMO)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://menyifang.github.io/projects/MIMO/index.html)

+ **Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation** (19 Aug 2024)<details><summary>Yunxin Li, Haoyuan Shi, Baotian Hu, et al.</summary>
        Yunxin Li, Haoyuan Shi, Baotian Hu, Longyue Wang, Jiashun Zhu, Jinyi Xu, Zhen Zhao, Min Zhang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)
        [![Code](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)](https://github.com/HITsz-TMG/Anim-Director)

+ **Still-Moving: Customized Video Generation Without Customized Video Data** (11 Jul 2024)  
   <details><summary>Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, et al.</summary>  
         Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, Omer Tov, Michael Rubinstein, Lior Wolf, Tali Dekel, Tomer Michaeli, Inbar Mosseri</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08674)
   [![Code](https://img.shields.io/github/stars/harshbhatt7585/StillMoving.svg?style=social&label=Star)](https://github.com/harshbhatt7585/StillMoving)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://still-moving.github.io/)

+ **VIMI: Grounding Video Generation through Multi-modal Instruction** (8 Jul 2024)<details><summary>Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, et al.</summary>
        Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, Tsai-Shien Chen, Kuan-Chien Wang, Ivan Skorokhodov, Graham Neubig, Sergey Tulyakov</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06304)

+ **ID-Animator: Zero-Shot Identity-Preserving Human Video Generation** (25 Jun 2024)  
   <details><summary>Xuanhua He, Quande Liu, et al.</summary>  
         Xuanhua He, Quande Liu, Shengju Qian, Xin Wang, Tao Hu, Ke Cao, Keyu Yan, Jie Zhang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275) 
   [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/ID-Animator/ID-Animator)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://id-animator.github.io)

+ **Customvideo: Customizing Text-to-Video Generation with Multiple Subjects** (22 May 2024)
   <details><summary>Zhao Wang, Aoxue Li, et al.</summary>  
         Zhao Wang, Aoxue Li, Lingting Zhu, Yong Guo, Qi Dou, Zhenguo Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09962)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://kyfafyd.wang/projects/customvideo/)

+ **DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control** (21 May 2024)<details><summary>Hong Chen, Xin Wang, Yipeng Zhang, et al.</summary>
        Hong Chen, Xin Wang, Yipeng Zhang, Yuwei Zhou, Zeyang Zhang, Siao Tang, Wenwu Zhu</details>
      [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.12796)
      [![GitHub](https://img.shields.io/github/stars/forchchch/disenstudio.github.io.svg?style=social&label=Star)](https://github.com/forchchch/disenstudio.github.io)

+ **Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers** (9 May 2024)<details><summary>Peng Gao, Le Zhuo, Dongyang Liu, et al.</summary>
        Peng Gao, Le Zhuo, Dongyang Liu, Ruoyi Du, Xu Luo, Longtian Qiu, Yuhang Zhang, Chen Lin, Rongjie Huang, Shijie Geng, Renrui Zhang, Junlin Xi, Wenqi Shao, Zhengkai Jiang, Tianshuo Yang, Weicai Ye, He Tong, Jingwen He, Yu Qiao, Hongsheng Li</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05945)
        [![Code](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-T2X.svg?style=social&label=Star)](https://github.com/Alpha-VLLM/Lumina-T2X)

+ **SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control** (28 Mar 2024)<details><summary>Zheng Chen, Di Qiu, Rui Wang, et al.</summary>
        Zheng Chen, Di Qiu, Rui Wang, Binyuan Huang, Yuqing Wen, Yucheng Zhao, Yaosi Hu, Yingfei Liu, Fan Jia, Weixin Mao, Tiancai Wang, Chi Zhang, Chang Wen Chen, Zhenzhong Chen, Xiangyu Zhang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.19438)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://subjectdrive.github.io/)

+ **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production** (12 Mar 2024)<details><summary>Jiuniu Wang, Zehua Du, Yuyuan Zhao, et al.</summary>
        Jiuniu Wang, Zehua Du, Yuyuan Zhao, Bo Yuan, Kexiang Wang, Jian Liang, Yaxi Zhao, Yihen Lu, Gengliang Li, Junlong Gao, Xin Tu, Zhenyu Guo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07952)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://aesopai.github.io/)
        

+ **Magic-Me: Identity-Specific Video Customized Diffusion** (14 Feb 2024)<details><summary>Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, et al.</summary>
        Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, Xue-She Wang, Xiuyu Li, Huanrui Yang, Zhen Dong, Kurt Keutzer, Jiashi Feng</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368)
        [![Code](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social&label=Star)](https://github.com/Zhen-Dong/Magic-Me)

+ **Vlogger: Make Your Dream A Vlog** (17 Jan 2024)<details><summary>Shaobin Zhuang, Kunchang Li, Xinyuan Chen, et al.</summary>
        Shaobin Zhuang, Kunchang Li, Xinyuan Chen, Yaohui Wang, Ziwei Liu, Yu Qiao, Yali Wang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09414)
        [![Code](https://img.shields.io/github/stars/zhuangshaobin/Vlogger.svg?style=social&label=Star)](https://github.com/zhuangshaobin/Vlogger)

+ **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)<details><summary>Fuchen Long, Zhaofan Qiu, Ting Yao, et al.</summary>
        Fuchen Long, Zhaofan Qiu, Ting Yao, Tao Mei</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://videodrafter.github.io/)

+ **Dreamvideo: Composing Your Dream Videos with Customized Subject and Motion** (7 Dec 2023)
   <details><summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing, et al.</summary>  
         Yujie Wei, Shiwei Zhang, Zhiwu Qing, Hangjie Yuan, Zhiheng Liu, Yu Liu, Yingya Zhang, Jingren Zhou, Hongming Shan</details> 
          
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
   [![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamvideo-t2v.github.io/)

+ **VideoBooth: Diffusion-based Video Generation with Image Prompts** (1 Dec 2023)<details><summary>Yuming Jiang, Tianxing Wu, Shuai Yang, et al.</summary>
        Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)
        [![Code](https://img.shields.io/github/stars/Vchitect/VideoBooth.svg?style=social&label=Star)](https://github.com/Vchitect/VideoBooth)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/VideoBooth-project/)

+ **Videodreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning** (2 Nov 2023)
   <details><summary>Hong Chen, Xin Wang, Guanning Zeng, et al.</summary>  
         Hong Chen, Xin Wang, Guanning Zeng, Yipeng Zhang, Yuwei Zhou, Feilin Han, Wenwu Zhu</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00990)

   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://videodreamer23.github.io/)

+ **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** (13 Jul 2023)<details><summary>Yingqing He, Menghan Xia, Haoxin Chen, et al.</summary>
        Yingqing He, Menghan Xia, Haoxin Chen, Xiaodong Cun, Yuan Gong, Jinbo Xing, Yong Zhang, Xintao Wang, Chao Weng, Ying Shan, Qifeng Chen</details>
      [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)
      [![Code](https://img.shields.io/github/stars/VideoCrafter/Animate-A-Story.svg?style=social&label=Star)](https://github.com/VideoCrafter/Animate-A-Story)
      [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/Animate-A-Story/)

+ **TaleCrafter: Interactive Story Visualization with Multiple Characters** (30 May 2023)
   <details><summary>Yuan Gong, Youxin Pang, et al.</summary>  
         Yuan Gong, Youxin Pang, Xiaodong Cun, Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247) 
   [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/VideoCrafter/TaleCrafter)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/TaleCrafter/)

+ **Dreamix: Video Diffusion Models are General Video Editors** (2 Feb 2023)
   <details><summary>Eyal Molad, Eliahu Horwitz, et al.</summary>  
         Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)  


### 📍 Spatial Control

#### 🕺 Pose Control
+ **TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation** (14 Mar 2025)
   <details><summary>Hongxiang Zhao, Xingchen Liu, et al.</summary>  
        Hongxiang Zhao, Xingchen Liu, Mutian Xu, Yiming Hao, Weikai Chen, Xiaoguang Han </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11423)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://taste-rob.github.io/)

+ **SkyReels-A1: Expressive Portrait Animation in Video Diffusion Transformers** (15 Feb 2025)
   <details><summary>Di Qiu, Zhengcong Fei, et al.</summary>
    Di Qiu, Zhengcong Fei, Rui Wang, Jialin Bai, Changqian Yu, Mingyuan Fan, Guibin Chen, Xiang Wen</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.10841)
   [![Code](https://img.shields.io/github/stars/SkyworkAI/SkyReels-A1.svg?style=social&label=Star)](https://github.com/SkyworkAI/SkyReels-A1)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)]([https://anycharv.github.io/](https://skyworkai.github.io/skyreels-a1.github.io/))

+ **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** (12 Feb 2025)
   <details><summary>Zhao Wang, Hao Wen, et al.</summary>  
        Zhao Wang, Hao Wen, Lingting Zhu, Chenming Shang, Yujiu Yang, Qi Dou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189)
   [![Code](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social&label=Star)](https://github.com/AnyCharV/AnyCharV)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anycharv.github.io/)
        
+ **Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance** (10 Feb 2025)
   <details><summary>Li Hu, Guangyuan Wang, et al.</summary>  
        Li Hu, Guangyuan Wang, Zhen Shen, Xin Gao, Dechao Meng, Lian Zhuo, Peng Zhang, Bang Zhang, Liefeng Bo </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06145)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone-2/)

+ **Consistent Human Image and Video Generation with Spatially Conditioned Diffusion** (19 Dec 2024)
   <details><summary>Mingdeng Cao, Chong Mou, et al.</summary>  
        Mingdeng Cao, Chong Mou, Ziyang Yuan, Xintao Wang, Zhaoyang Zhang, Ying Shan, Yinqiang Zheng </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14531)
   [![Code](https://img.shields.io/github/stars/ljzycmd/SCD.svg?style=social&label=Star)](https://github.com/ljzycmd/SCD)

+ **DirectorLLM for Human-Centric Video Generation** (19 Dec 2024)
   <details><summary>Kunpeng Song, Tingbo Hou, et al.</summary>  
        Kunpeng Song, Tingbo Hou, Zecheng He, Haoyu Ma, Jialiang Wang, Animesh Sinha, Sam Tsai, Yaqiao Luo, Xiaoliang Dai, Li Chen, Xide Xia, Peizhao Zhang, Peter Vajda, Ahmed Elgammal, Felix Juefei-Xu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14484)

+ **Generative Inbetweening through Frame-wise Conditions-Driven Video Generation** (16 Dec 2024)
   <details><summary>[CVPR 2025] Tianyi Zhu, Dongwei Ren, et al.</summary>  
        Tianyi Zhu, Dongwei Ren, Qilong Wang, Xiaohe Wu, Wangmeng Zuo </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11755)
   [![Code](https://img.shields.io/github/stars/Tian-one/FCVG.svg?style=social&label=Star)](https://github.com/Tian-one/FCVG)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fcvg-inbetween.github.io/)

+ **DisPose: Disentangling Pose Guidance for Controllable Human Image Animation** (12 Dec 2024)
   <details><summary>[ICLR2025] Hongxiang Li, Yaowei Li, et al.</summary>  
        Hongxiang Li, Yaowei Li, Yuhang Yang, Junjie Cao, Zhihong Zhu, Xuxin Cheng, Long Chen </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09349)
   [![Code](https://img.shields.io/github/stars/lihxxx/DisPose.svg?style=social&label=Star)](https://github.com/lihxxx/DisPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lihxxx.github.io/DisPose/)

+ **ControlNeXt: Powerful and Efficient Control for Image and Video Generation** (12 Aug 2024)
   <details><summary>Bohao Peng, Jian Wang, et al.</summary>  
        Bohao Peng, Jian Wang, Yuechen Zhang, Wenbo Li, Ming-Chang Yang, Jiaya Jia </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06070)
   [![Code](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star)](https://github.com/dvlab-research/ControlNeXt)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pbihao.github.io/projects/controlnext/index.html)

+ **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance** (28 Jun 2024)
   <details><summary>Yuang Zhang, Jiaxi Gu, et al.</summary>  
        Yuang Zhang, Jiaxi Gu, Li-Wen Wang, Han Wang, Junqi Cheng, Yuefeng Zhu, Fangyuan Zou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)
   [![Code](https://img.shields.io/github/stars/tencent/MimicMotion.svg?style=social&label=Star)](https://github.com/tencent/MimicMotion)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tencent.github.io/MimicMotion/)

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (21 Mar 2024)
   <details><summary>[ECCV 2024] Shenhao Zhu, Junming Leo Chen, et al.</summary>  
        Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
   [![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **Do You Guys Want to Dance: Zero-Shot Compositional Human Dance Generation with Multiple Persons** (24 Jan 2024)
   <details><summary>Zhe Xu, Kun Wei, et al.</summary>  
        Zhe Xu, Kun Wei, Xu Yang, Cheng Deng </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13363)

+ **Generative Rendering: Controllable 4D-Guided Video Generation with 2D Diffusion Models** (3 Dec 2023)
   <details><summary>[CVPR 2024] Shengqu Cai, Duygu Ceylan, et al.</summary>  
        Shengqu Cai, Duygu Ceylan, Matheus Gadelha, Chun-Hao Paul Huang, Tuanfeng Yang Wang, Gordon Wetzstein </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://primecai.github.io/generative_rendering/)


+ **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** (28 Nov 2023)
   <details><summary>[CVPR 2024] Li Hu, Xin Gao, et al.</summary>  
        Li Hu, Xin Gao, Peng Zhang, Ke Sun, Bang Zhang, Liefeng Bo </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117)
   [![Code](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone/)

+ **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** (27 Nov 2023)
   <details><summary>[CVPR 2024] Zhongcong Xu, Jianfeng Zhang, et al.</summary>  
        Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
   [![Code](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/magicanimate/)

+ **MagicPose: Realistic Human Poses and Facial Expressions Retargeting with Identity-aware Diffusion** (18 Nov 2023)
   <details><summary>[ICML 2024] Di Chang, Yichun Shi, Quankai Gao, et al.</summary>  
        Di Chang, Yichun Shi, Quankai Gao, Jessica Fu, Hongyi Xu, Guoxian Song, Qing Yan, Yizhe Zhu, Xiao Yang, Mohammad Soleymani </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12052)
   [![Code](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social&label=Star)](https://github.com/Boese0601/MagicDance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boese0601.github.io/magicdance/)

+ **Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model** (15 Aug 2023)
   <details><summary>Bosheng Qin, Wentao Ye, et al.</summary>  
        Bosheng Qin, Wentao Ye, Qifan Yu, Siliang Tang, Yueting Zhuang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07749)

+ **DisCo: Disentangled Control for Realistic Human Dance Generation** (30 Jun 2023)
   <details><summary>[CVPR2024] Tan Wang, Linjie Li, et al.</summary>  
        Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
   [![Code](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://disco-dance.github.io/)

+ **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** (12 Apr 2023)
   <details><summary>[ICCV 2023] Johanna Karras, Aleksander Holynski, et al.</summary>  
        Johanna Karras, Aleksander Holynski, Ting-Chun Wang, Ira Kemelmacher-Shlizerman </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025)
   [![Code](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://grail.cs.washington.edu/projects/dreampose/)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023)
   <details><summary>[AAAI 2024] Yue Ma, Yingqing He, et al.</summary>  
        Yue Ma, Yingqing He, Xiaodong Cun, Xintao Wang, Siran Chen, Ying Shan, Xiu Li, Qifeng Chen </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
   [![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)


#### 🚗 BEV-Control
+ **Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention** (04 Dec 2024)<details><summary>Hannan Lu, Xiaohe Wu, Shudong Wang, et al.</summary>
Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03520)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://luhannan.github.io/CogDrivingPage/)

+ **MagicDrive-V2: High-Resolution Long Video Generation for Autonomous Driving with Adaptive Control** (21 Nov 2024)<details><summary>Ruiyuan Gao, Kai Chen, Bo Xiao, et al.</summary>
Ruiyuan Gao, Kai Chen, Bo Xiao, Lanqing Hong, Zhenguo Li, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.13807)
[![Code](https://img.shields.io/github/stars/flymin/MagicDrive-V2.svg?style=social&label=Star)](https://github.com/flymin/MagicDrive-V2)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](http://gaoruiyuan.com/magicdrive-v2/)

+ **DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View Driving Scenes** (06 Sep 2024)<details><summary>Jianbiao Mei, Tao Hu, Xuemeng Yang, et al.</summary>
Jianbiao Mei, Tao Hu, Xuemeng Yang, Licheng Wen, Yu Yang, Tiantian Wei, Yukai Ma, Min Dou, Botian Shi, Yong Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04003)
[![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star)](https://github.com/PJLab-ADG/DriveArena)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pjlab-adg.github.io/DriveArena/dreamforge/)

+ **DiVE: DiT-based Video Generation with Enhanced Control** (03 Sep 2024)<details><summary>Junpeng Jiang, Gangyi Hong, Lijun Zhou, et al.</summary>
Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01595)
[![Code](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Star)](https://github.com/LiAutoAD/DIVE)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://liautoad.github.io/DIVE/)

+ **Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation** (03 Jun 2024)<details><summary>Enhui Ma, Lijun Zhou, Tao Tang, et al.</summary>
Enhui Ma, Lijun Zhou, Tao Tang, Zhan Zhang, Dong Han, Junpeng Jiang, Kun Zhan, Peng Jia, Xianpeng Lang, Haiyang Sun, Di Lin, Kaicheng Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01349)
[![Code](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Star)](https://github.com/westlake-autolab/Delphi)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://westlake-autolab.github.io/delphi.github.io/)

+ **DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation** (11 Mar 2024)<details><summary>Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, et al.</summary>
Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, Xinze Chen, Guan Huang, Xiaoyi Bao, Xingang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06845)
[![Code](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Star)](https://github.com/f1yfisher/DriveDreamer2)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://drivedreamer2.github.io)

+ **Panacea: Panoramic and Controllable Video Generation for Autonomous Driving** (28 Nov 2023)<details><summary>Yuqing Wen, Yucheng Zhao, Yingfei Liu, et al.</summary>
Yuqing Wen, Yucheng Zhao, Yingfei Liu, Fan Jia, Yanhui Wang, Chong Luo, Chi Zhang, Tiancai Wang, Xiaoyan Sun, Xiangyu Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16813)
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://panacea-ad.github.io)

+ **MagicDrive: Street View Generation with Diverse 3D Geometry Control** (04 Oct 2023)<details><summary>Ruiyuan Gao, Kai Chen, Enze Xie, et al.</summary>
Ruiyuan Gao, Kai Chen, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02601)
[![Code](https://img.shields.io/github/stars/cure-lab/MagicDrive.svg?style=social&label=Star)](https://github.com/cure-lab/MagicDrive)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](http://gaoruiyuan.com/magicdrive/)

#### 🎨 Style Control

+ **StyleMaster: Stylize Your Video with Artistic Generation and Translation** (10 Dec 2024)<details><summary>Zixuan Ye, Huijuan Huang, Xintao Wang, et al.</summary>
Pengfei Wan, Di Zhang, Wenhan Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07744)
[![Code](https://img.shields.io/github/stars/KwaiVGI/StyleMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/StyleMaster.git)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=0b0847aeb0eca4a26f838b0969b35c26ff8d8cc2)](https://www.semanticscholar.org/paper/0b0847aeb0eca4a26f838b0969b35c26ff8d8cc2)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laulampaul.github.io/text-animator)

+ **FRESCO: Spatial-Temporal Correspondence for Zero-Shot Video Translation** (19 Mar 2024)<details><summary>[CVPR 2024] Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12962)
[![Code](https://img.shields.io/github/stars/williamyang1991/FRESCO.svg?style=social&label=Star)](https://github.com/williamyang1991/FRESCO.git)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=2900738d1d9a51726b6baae203d100e379f74418)](https://www.semanticscholar.org/paper/2900738d1d9a51726b6baae203d100e379f74418)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/fresco/)

+ **StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter** (1 Dec 2023)<details><summary>[TOG 2024] Gongye Liu, Menghan Xia, Yong Zhang, et al.</summary>
Haoxin Chen, Jinbo Xing, Yibo Wang, Xintao Wang, Yujiu Yang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00330)
[![Code](https://img.shields.io/github/stars/GongyeLiu/StyleCrafter.svg?style=social&label=Star)](https://github.com/GongyeLiu/StyleCrafter.git)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=b013c9eb1284554ae696fba02bd4d7fc599890b6)](https://www.semanticscholar.org/paper/b013c9eb1284554ae696fba02bd4d7fc599890b6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gongyeliu.github.io/StyleCrafter.github.io/)

+ **UniVST: A Unified Framework for Training-free Localized Video Style Transfer** (26 Oct 2024)<details><summary>Quanjian Song, Mingbao Lin, Wengyi Zhan, et al.</summary>
Shuicheng Yan, Liujuan Cao, Rongrong Ji</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20084)
[![Code](https://img.shields.io/github/stars/QuanjianSong/UniVST.svg?style=social&label=Star)](https://github.com/QuanjianSong/UniVST)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=fcc87eec6543d4e33a2cd679b705292af9020cb4)](https://www.semanticscholar.org/paper/fcc87eec6543d4e33a2cd679b705292af9020cb4)

+ **StyleGANEX: StyleGAN-Based Manipulation Beyond Cropped Aligned Faces** (21 Jul 2023)<details><summary>[ICCV 2023] Shua Yang, Liming Jiang, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.06146)
[![Code](https://img.shields.io/github/stars/williamyang1991/StyleGANEX.svg?style=social&label=Star)](https://github.com/williamyang1991/StyleGANEX.git)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=06aa2aa2a29f25437545478e7361744aa35a0419)](https://www.semanticscholar.org/paper/06aa2aa2a29f25437545478e7361744aa35a0419)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/styleganex/)

+ **Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation** (13 Jun 2023)<details><summary>[Siggraph Asia 2023] Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
[![Code](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social&label=Star)](https://github.com/williamyang1991/Rerender_A_Video.git)
[![citation](https://img.shields.io/badge/citation-184-blue.svg?paper=1e09b83fe064826a9a1ac61a7bdc00f26be41aee)](https://www.semanticscholar.org/paper/1e09b83fe064826a9a1ac61a7bdc00f26be41aee)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/rerender/)

+ **VToonify: Controllable High-Resolution Portrait Video Style Transfer** (22 Sep 2022)<details><summary>[Siggraph Asia 2022] Shuai Yang, Liming Jiang, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.11224)
[![Code](https://img.shields.io/github/stars/williamyang1991/VToonify.svg?style=social&label=Star)](https://github.com/williamyang1991/VToonify.git)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=866e09b1b9fcca7371346fd225479485a2bae20b)](https://www.semanticscholar.org/paper/866e09b1b9fcca7371346fd225479485a2bae20b) 
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/vtoonify/)

+ **Arbitrary video style transfer via multi-channel correlation** (17 Sep 2020)<details><summary>[AAAI 2020] Yingying Deng, Fan Tang, Weiming Dong, et al.</summary>
Yingying Deng, Fan Tang, Weiming Dong, Haibin Huang, Chongyang Ma, Changsheng Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2009.08003)
[![Code](https://img.shields.io/github/stars/diyiiyiii/MCCNet.svg?style=social&label=Star)](https://github.com/diyiiyiii/MCCNet)
[![citation](https://img.shields.io/badge/citation-170-blue.svg?paper=6c6aa5974edccd33117bdd1f6d2a8b6b3d0b44da)](https://www.semanticscholar.org/paper/6c6aa5974edccd33117bdd1f6d2a8b6b3d0b44da)

+ **Fast video multi-style transfer** (2020)<details><summary>[WACV 2020] Wei Gao, Yijun Li, et al.</summary>
Yihang Yin, Ming-Hsuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_WACV_2020/papers/Gao_Fast_Video_Multi-Style_Transfer_WACV_2020_paper.pdf)
[![Code](https://img.shields.io/github/stars/gaow0007/Fast-Multi-Video-Style-Transfer.svg?style=social&label=Star)](https://github.com/gaow0007/Fast-Multi-Video-Style-Transfer.git)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=0da4bd286cac8a8aa8577867ff87cab279ca964f)](https://www.semanticscholar.org/paper/0da4bd286cac8a8aa8577867ff87cab279ca964f)

+ **Coherent online video style transfer** (27 Mar 2017)<details><summary>[CVPR 2017] Dongdong Chen, Jing Liao, Lu Yuan, et al.</summary>
Nenghai Yu, Gang Hua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1703.09211)
[![citation](https://img.shields.io/badge/citation-335-blue.svg?paper=2d5b4144124f47a6357e6390dc6c0f8806ac54f5)](https://www.semanticscholar.org/paper/2d5b4144124f47a6357e6390dc6c0f8806ac54f5)

+ **Real-time neural style transfer for videos** (2017)<details><summary>[CVPR 2017] Haozhi Huang, Hao Wang, Wenhan Luo, et al.</summary>
Lin Ma, Wenhao Jiang, Xiaolong Zhu, Zhifeng Li, Wei Liu </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2017/papers/Huang_Real-Time_Neural_Style_CVPR_2017_paper.pdf)
[![citation](https://img.shields.io/badge/citation-286-blue.svg?paper=6d05778f51fb0138a4ba46a6f007702a9a93654c)](https://www.semanticscholar.org/paper/6d05778f51fb0138a4ba46a6f007702a9a93654c)


#### 📌 Point Control
+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** (7 Jan 2025)<details><summary>Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, et al.</summary>
Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03847)
[![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader.git)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=db6df95b051f02c28926f448faf0046f18ebc454)](https://www.semanticscholar.org/paper/db6df95b051f02c28926f448faf0046f18ebc454)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://igl-hkust.github.io/das/)

+ **GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking** (5 Jan 2025)<details><summary>Weikang Bian, Zhaoyang Huang, Xiaoyu Shi, et al.</summary>
Yijin Li, Fu-Yun Wang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.02690)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=00166f6852bc348570bf65e27a23407bd789ab37)](https://www.semanticscholar.org/paper/00166f6852bc348570bf65e27a23407bd789ab37)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wkbian.github.io/Projects/GS-DiT/)

+ **Track4Gen: Teaching Video Diffusion Models to Track Points Improves Video Generation** (8 Dec 2024)<details><summary>[CVPR 2025] Hyeonho Jeong, Chun-Hao Paul Huang, et al.</summary>
Jong Chul Ye, Niloy Mitra, Duygu Ceylan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06016)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=e1fabe62210b24456b558f0864faa4b35b056f98)](https://www.semanticscholar.org/paper/e1fabe62210b24456b558f0864faa4b35b056f98)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyeonho99.github.io/track4gen/)

+ **Drag-A-Video: Non-rigid Video Editing with Point-based Interaction** (5 Dec 2023)<details><summary>Yao Teng, Enze Xie, Yue Wu, Haoyu Han, et al.</summary>
Zhenguo Li, Xihui Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02936)
[![Code](https://img.shields.io/github/stars/tyshiwo1/drag-a-video.svg?style=social&label=Star)](https://github.com/tyshiwo1/drag-a-video.git)
[![citation](https://img.shields.io/badge/citation-14-blue.svg?paper=58dfc9cfc39787322a74cc93c22c9d3028aa9ad7)](https://www.semanticscholar.org/paper/58dfc9cfc39787322a74cc93c22c9d3028aa9ad7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drag-a-video.github.io/)

+ **Point-to-Point Video Generation** (5 Apr 2019)<details><summary>[ICCV 2019] Tsun-Hsuan Wang, Yen-Chi Cheng, Chieh Hubert Lin, et al.</summary> Hwann-Tzong Chen, Min Sun </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1904.02912)
[![Code](https://img.shields.io/github/stars/yccyenchicheng/p2pvg.svg?style=social&label=Star)](https://github.com/yccyenchicheng/p2pvg.git)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=cb0a151cf8740c66b461ff809e086b91f14bd23b)](https://www.semanticscholar.org/paper/cb0a151cf8740c66b461ff809e086b91f14bd23b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zswang666.github.io/P2PVG-Project-Page/)


#### 📏 Depth Control
+ **DreamDance: Animating Human Images by Enriching 3D Geometry Cues from 2D Poses** (30 Nov 2024)<details><summary>Yatian Pang, Bin Zhu, Bin Lin, et al.</summary>
        Mingzhe Zheng, Francis E. H. Tay, Ser-Nam Lim, Harry Yang, Li Yuan </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00397)
[![Code](https://img.shields.io/github/stars/YongjinLiu/DreamDance.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/DreamDance.git)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=00166f6852bc348570bf65e27a23407bd789ab37)](https://www.semanticscholar.org/paper/0be2accfc866bbe4aa1d507b0d2b53cd5fc4a62a#citing-papers)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pang-yatian.github.io/Dreamdance-webpage/)

+ **ControlNeXt: Powerful and Efficient Control for Image and Video Generation** (12 Aug 2024)<details><summary>Bohao Peng, Jian Wang, Yuechen Zhang, et al.</summary>
        Wenbo Li, Ming-Chang Yang, Jiaya Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06070)
[![Code](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star)](https://github.com/dvlab-research/ControlNeXt.git)
[![citation](https://img.shields.io/badge/citation-45-blue.svg?paper=e4ec4dea3e6f26e69f39a96d00d228070f4bde60)](https://www.semanticscholar.org/paper/e4ec4dea3e6f26e69f39a96d00d228070f4bde60)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pbihao.github.io/projects/controlnext/index.html)

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (21 Mar 2024)<details><summary>[ECCV 2024] Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>
      Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ.git)
[![citation](https://img.shields.io/badge/citation-89-blue.svg?paper=ec41ad3a2a538da7eda1a7b0979d6904ade17d82)](https://www.semanticscholar.org/paper/ec41ad3a2a538da7eda1a7b0979d6904ade17d82)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **MoonShot: Towards Controllable Video Generation and Editing with Multimodal Conditions** (3 Jan 2024)<details><summary>David Junhao Zhang, Dongxu Li, Hung Le, et al.</summary>
      Mike Zheng Shou, Caiming Xiong, Doyen Sahoo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)
[![Code](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star)](https://github.com/salesforce/LAVIS.git)
[![citation](https://img.shields.io/badge/citation-37-blue.svg?paper=9be8950710e375cf47a002e9b4094b04814bde62)](https://www.semanticscholar.org/paper/9be8950710e375cf47a002e9b4094b04814bde62)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/Moonshot/)

+ **SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models** (28 Nov 2023)<details><summary>[ECCV 2024] Yuwei Guo, Ceyuan Yang, Anyi Rao, et al.</summary>
        Maneesh Agrawala, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff.svg?style=social&label=Star)](https://github.com/guoyww/AnimateDiff.git)
[![citation](https://img.shields.io/badge/citation-97-blue.svg?paper=40626a059bcd8d3e7f364b410f831b9baf997b0c)](https://www.semanticscholar.org/paper/40626a059bcd8d3e7f364b410f831b9baf997b0c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoyww.github.io/projects/SparseCtrl/)

+ **GD-VDM: Generated Depth for better Diffusion-based Video Generation** (19 Jun 2023)<details><summary>Ariel Lapid, Idan Achituve, Lior Bracha, et al.</summary>
        Ethan Fetaya</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.11173)
[![Code](https://img.shields.io/github/stars/lapid92/GD-VDM.svg?style=social&label=Star)](https://github.com/lapid92/GD-VDM.git)
[![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=da771b92882d87f97dead9c5705d67ae0c717916)](https://www.semanticscholar.org/paper/da771b92882d87f97dead9c5705d67ae0c717916)

+ **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** (1 Jun 2023)<details><summary>[IEEE TVCG 2024] Jinbo Xing, Menghan Xia, Yuxin Liu, et al.</summary>
        Yuechen Zhang, Yong Zhang, Yingqing He, Hanyuan Liu, Haoxin Chen, Xiaodong Cun, Xintao Wang, Ying Shan, Tien-Tsin Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Make-Your-Video.svg?style=social&label=Star)](https://github.com/AILab-CVC/Make-Your-Video.git)
[![citation](https://img.shields.io/badge/citation-69-blue.svg?paper=52b10ae66d025e99fbb602935e155f97f4f0696f)](https://www.semanticscholar.org/paper/52b10ae66d025e99fbb602935e155f97f4f0696f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/Make-Your-Video/)

+ **Control-A-Video: Controllable Text-to-Video Diffusion Models with Motion Prior and Reward Feedback Learning** (23 May 2023)<details><summary>Weifeng Chen, Yatai Ji, Jie Wu, et al.</summary>
        Hefeng Wu, Pan Xie, Jiashi Li, Xin Xia, Xuefeng Xiao, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
[![Code](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Star)](https://github.com/Weifeng-Chen/control-a-video.git)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=7f37a93af316e16245498337bb160ee08e82346f)](https://www.semanticscholar.org/paper/7f37a93af316e16245498337bb160ee08e82346f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlavideo.github.io/)

+ **ControlVideo: Training-free Controllable Text-to-Video Generation** (22 May 2023)<details><summary>[ICLR 2024] Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, et al.</summary>
      Xiaopeng Zhang, Wangmeng Zuo, Qi Tian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13077)
[![Code](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Star)](https://github.com/YBYBZhang/ControlVideo.git)
[![citation](https://img.shields.io/badge/citation-249-blue.svg?paper=529191401a8a5f0a8bdb2a1c01301d76af585a3a)](https://www.semanticscholar.org/paper/529191401a8a5f0a8bdb2a1c01301d76af585a3a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlvideov1.github.io/)

#### 🗺️ Landmark Control

+ **HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation** (24 Mar 2024)
   <details><summary>[CVPR 2025] Zunnan Xu, Zhentao Yu, et al.</summary>  
        Zunnan Xu, Zhentao Yu, Zixiang Zhou, Jun Zhou, Xiaoyu Jin, Fa-Ting Hong, Xiaozhong Ji, Junwei Zhu, Chengfei Cai, Shiyu Tang, Qin Lin, Xiu Li, Qinglin Lu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18860)
   [![Code](https://img.shields.io/github/stars/kkakkkka/HunyuanPortrait.svg?style=social&label=Star)](https://github.com/kkakkkka/HunyuanPortrait)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kkakkkka.github.io/HunyuanPortrait)

+ **TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation** (14 Mar 2025)
   <details><summary>Hongxiang Zhao, Xingchen Liu, et al.</summary>  
        Hongxiang Zhao, Xingchen Liu, Mutian Xu, Yiming Hao, Weikai Chen, Xiaoguang Han </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11423)
   [![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=f8ce125cb422e8bc8459b25f3ce64b2cea1f0718)](https://www.semanticscholar.org/paper/f8ce125cb422e8bc8459b25f3ce64b2cea1f0718)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://taste-rob.github.io/)

+ **Identity-Preserving Text-to-Video Generation by Frequency Decomposition** (26 Nov 2024)
   <details><summary>[CVPR 2025] Shenghai Yuan, Jinfa Huang, et al.</summary>  
        Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
   [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ConsisID)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/ConsisID/)

+ **EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation** (15 Nov 2024)<details><summary>[CVPR 2025] Rang Meng, Xingyu Zhang, Yuming Li, et al.</summary>
Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://antgroup.github.io/ai/echomimic_v2/)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic_v2.svg?style=social&label=Star)](https://github.com/antgroup/echomimic_v2)

+ **Takin-ADA: Emotion Controllable Audio-Driven Animation with Canonical and Landmark Loss Optimization** (18 Oct 2024)
   <details><summary>Bin Lin, Yanzhen Yu, et al.</summary>  
        Bin Lin, Yanzhen Yu, Jianhao Ye, Ruitao Lv, Yuguang Yang, Ruoye Xie, Pan Yu, Hongbin Zhou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14283)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://everest-ai.github.io/takinada/)

+ **EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions** (12 Jul 2024)<details><summary>[AAAI 2025] Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, et al.</summary>
Yuming Li, Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)
[![citation](https://img.shields.io/badge/citation-34-blue.svg?paper=d92c15b21777bd81b95622506e406e24a4de4bdb)](https://www.semanticscholar.org/paper/d92c15b21777bd81b95622506e406e24a4de4bdb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic.svg?style=social&label=Star)](https://github.com/antgroup/echomimic)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BadToBest/EchoMimic)

+ **LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control** (3 Jul 2024)
   <details><summary>Jianzhu Guo, Dingyun Zhang, et al.</summary>  
        Jianzhu Guo, Dingyun Zhang, Xiaoqiang Liu, Zhizhou Zhong, Yuan Zhang, Pengfei Wan, Di Zhang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03168)
   [![Code](https://img.shields.io/github/stars/KwaiVGI/LivePortrait.svg?style=social&label=Star)](https://github.com/KwaiVGI/LivePortrait)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://liveportrait.github.io/)

+ **Follow-Your-Emoji: Fine-Controllable and Expressive Freestyle Portrait Animation** (4 Jun 2024)
   <details><summary>[Siggraph Asia 2024] Yue Ma, Hongyu Liu, et al.</summary>  
        Yue Ma, Hongyu Liu, Hongfa Wang, Heng Pan, Yingqing He, Junkun Yuan, Ailing Zeng, Chengfei Cai, Heung-Yeung Shum, Wei Liu, Qifeng Chen </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01900)
   [![Code](https://img.shields.io/github/stars/mayuelala/FollowYourEmoji.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourEmoji)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-emoji.github.io/)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023)
   <details><summary>[AAAI 2024] Yue Ma, Yingqing He, et al.</summary>  
        Yue Ma, Yingqing He, Xiaodong Cun, Xintao Wang, Siran Chen, Ying Shan, Xiu Li, Qifeng Chen </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
   [![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)



### ✍️ Text Rendering
+ **Wan: Open and Advanced Large-Scale Video Generative Models** (2025)<details><summary>WanTeam, Ang Wang, Baole Ai, et al.</summary>Bin Wen,Chaojie Mao,Chen-Wei Xie,Di Chen,Feiwu Yu,Haiming Zhao,Jianxiao Yang,Jianyuan Zeng,Jiayu Wang,Jingfeng Zhang,Jingren Zhou,Jinkai Wang,Jixuan Chen,Kai Zhu,Kang Zhao,Keyu Yan,Lianghua Huang,Mengyang Feng,Ningyi Zhang,Pandeng Li,Pingyu Wu,Ruihang Chu,Ruili Feng,Shiwei Zhang,Siyang Sun,Tao Fang,Tianxing Wang,Tianyi Gui,Tingyu Weng,Tong Shen,Wei Lin,Wei Wang~1,Wei Wang~2,Wenmeng Zhou,Wente Wang,Wenting Shen,Wenyuan Yu,Xianzhong Shi,Xiaoming Huang,Xin Xu,Yan Kou,Yangyu Lv,Yifei Li,Yijing Liu,Yiming Wang,Yingya Zhang,Yitong Huang,Yong Li,You Wu,Yu Liu,Yulin Pan,Yun Zheng,Yuntao Hong,Yupeng Shi,Yutong Feng,Zeyinzi Jiang,Zhen Han,Zhi-Fan Wu,Ziyu Liu</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://files.alicdn.com/tpsservice/5c9de1c74de03972b7aa657e5a54756b.pdf)
[![Code](https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social&label=Star)](https://github.com/Wan-Video/Wan2.1)


+ **Text-Animator: Controllable Visual Text Video Generation** (25 Jun 2024)<details><summary>Lin Liu, Quande Liu, Shengju Qian, et al.</summary>Yuan Zhou, Wengang Zhou, Houqiang Li, Lingxi Xie, Qi Tian</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17777)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=fcc87eec6543d4e33a2cd679b705292af9020cb4)](https://www.semanticscholar.org/paper/fcc87eec6543d4e33a2cd679b705292af9020cb4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laulampaul.github.io/text-animator)

### ⏳ Temporal Control

#### 🌊 Flow-Guided

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (30 May 2024)
   <details><summary>[ECCV 2024] Muyao Niu, Xiaodong Cun, et al.</summary>  
        Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
   [![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://myniuuu.github.io/MOFA_Video/)

+ **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (29 Jan 2024)
   <details><summary>[SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, et al.</summary>  
        Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)
   [![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)

+ **Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023)
   <details><summary>Tsai-Shien Chen, Chieh Hubert Lin, et al.</summary>  
        Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, Tsung-Yi Lin, Ming-Hsuan Yang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tsaishien-chen.github.io/MCDiff/)

#### 📸 Camera-Guided
+ **ReCamMaster: Camera-Controlled Generative Rendering from A Single Video** (14 Mar 2025)<details><summary>Jianhong Bai, Menghan Xia, Xiao Fu, et al.</summary>Xintao Wang, Lianrui Mu, Jinwen Cao, Zuozhu Liu, Haoji Hu, Xiang Bai, Pengfei Wan, Di Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11647)
[![code](https://img.shields.io/github/stars/KwaiVGI/ReCamMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/ReCamMaster)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianhongbai.github.io/ReCamMaster/)

+ **CPA: Camera-pose-awareness Diffusion Transformer for Video Generation** (14 Mar 2025)<details><summary>Yuelei Wang, Jian Zhang, Pengtao Jiang, et al.</summary>Hao Zhang, Jinwei Chen, Bo Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01429)
[![code](https://img.shields.io/github/stars/Yangzhangcst/Transformer-in-Computer-Vision.svg?style=social&label=Star)](https://github.com/Yangzhangcst/Transformer-in-Computer-Vision/blob/main/main/diffusion.md)


+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models** (13 Mar 2025) <details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary>Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592)
[![code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/Projects-CameraCtrl-II/)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** (13 Mar 2025) <details><summary>Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
[![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/)

+ **EgoSim: Egocentric Exploration in Virtual Worlds with Multi-modal Conditioning** (16 Mar 2025)<details><summary>Wei Yu, Songheng Yin, Steve Easterbrook, Animesh Garg, et al.</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=zAyS5aRKV8)
[![code](https://img.shields.io/github/stars/opendilab/awesome-exploration-rl.svg?style=social&label=Star)](https://github.com/opendilab/awesome-exploration-rl)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://iplab.dmi.unict.it/egoism-hoi/)

+ **AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers** (22 Mar 2025) <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, et al.</summary>Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18673)
  [![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)
  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sherwinbahmani.github.io/)

+ **CineMaster: A 3D-Aware and Controllable Framework for Cinematic Text-to-Video Generation** (12 Feb 2025)<details><summary>Qinghe Wang, Yawen Luo, Xiaoyu Shi, et al.</summary>Xu Jia, Huchuan Lu, Tianfan Xue, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08639)
[![code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deeplearn.org/arxiv/575817/cinemaster:-a-3d-aware-and-controllable-framework-for-cinematic-text-to-video-generation)

+ **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion** (12 Feb 2025) <details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, et al.</summary>Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
[![Code](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://direct-a-video.github.io/)

+ **3DTrajMaster: Mastering 3D Trajectory for Multi-Entity Motion in Video Generation** (7 Feb 2025)  <details><summary>Xiao Fu, Xian Liu, Xintao Wang, et al.</summary>Sida Peng, Menghan Xia, Xiaoyu Shi, Ziyang Yuan, Pengfei Wan, Di Zhang, Dahua Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07759)
[![code](https://img.shields.io/github/stars/KwaiVGI/3DTrajMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/3DTrajMaster)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.aimodels.fyi/papers/arxiv/3dtrajmaster-mastering-3d-trajectory-multi-entity-motion)

+ **Boosting Camera Motion Control for Video Diffusion Transformers** (14 Oct 2024)<details><summary>Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, et al.</summary>Andrew Gilbert, Chun-Hao Paul Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10802)
[![code](https://img.shields.io/github/stars/soon-yau/CameraMotionGuidance.svg?style=social&label=Star)](https://github.com/soon-yau/CameraMotionGuidance)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://soon-yau.github.io/CameraMotionGuidance/)

+ **Cavia: Camera-controllable Multi-view Video Diffusion with View-Integrated Attention** (14 Oct 2024)<details><summary>Dejia Xu, Yifan Jiang, Chen Huang, et al.</summary>Liangchen Song, Thorsten Gernoth, Liangliang Cao, Zhangyang Wang, Hao Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10774)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ir1d.github.io/Cavia/)

+ **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** (3 Sep 2024)<details><summary>Wangbo Yu, Jinbo Xing, Li Yuan, et al.</summary>Wenbo Hu, Xiaoyu Li, Zhipeng Huang, Xiangjun Gao, Tien-Tsin Wong, Ying Shan, Yonghong Tian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048)
[![Code](https://img.shields.io/github/stars/Drexubery/ViewCrafter.svg?style=social&label=Star)](https://github.com/Drexubery/ViewCrafter)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drexubery.github.io/ViewCrafter/)

+ **MotionMaster: Training-free Camera Motion Transfer For Video Generation** (1 May 2024)<details><summary>Teng Hu, Jiangning Zhang, Ran Yi, et al.</summary>Yating Wang, Hongrui Huang, Jieyu Weng, Yabiao Wang, Lizhuang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15789)
[![Code](https://img.shields.io/github/stars/sjtuplayer/MotionMaster.svg?style=social&label=Star)](https://github.com/sjtuplayer/MotionMaster)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dsin.ai/news/article/cBZRAtg/motionmaster_training_free_camera_motion_transfer_for_video_generation)

+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** (17 Jul 2024)<details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
[![code](https://img.shields.io/github/stars/Yangzhangcst/Transformer-in-Computer-Vision.svg?style=social&label=Star)](https://github.com/Yangzhangcst/Transformer-in-Computer-Vision/blob/main/main/diffusion.md)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/vd3d/gallery.html)

+ **Latent-Reframe: Enabling Camera Control for Video Diffusion Model without Training** (8 Dec 2024) <details><summary>Zhenghong Zhou, Jie An, Jiebo Luo, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06029)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://img.shields.io/badge/Project_Pa)

+ **MOTIONFLOW:Learning Implicit Motion Flow for Complex Camera Trajectory Control in Video Generation**<details><summary>Author list not fully provided</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=OBTmkKBmQW)
[![code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://motion-prompting.github.io/)
#### 🛤️ Traj-Guided
+ **MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation** (6 Feb 2025) <details><summary>Jinbo Xing, Long Mai, Cusuh Ham, et al.</summary>Jinbo Xing, Long Mai, Cusuh Ham, Jiahui Huang, Aniruddha Mahapatra, Chi-Wing Fu, Tien-Tsin Wong, Feng Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2502.04299v1) 
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-canvas25.github.io/)

+ **MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance** (20 Mar 2025)  <details><summary>Quanhao Li, Zhen Xing, Rui Wang, et al.</summary>Quanhao Li, Zhen Xing, Rui Wang, Hui Zhang, Qi Dai, Zuxuan Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.16421v1)
 [![code](https://img.shields.io/github/stars/quanhaol/MagicMotion.svg?style=social&label=Star)](https://github.com/quanhaol/MagicMotion)
  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.radneurons.com/magicmotion/)

+ **Tora: Trajectory-oriented Diffusion Transformer for Video Generation** (14 Mar 2025) <details><summary>Zhenghao Zhang, Junchao Liao, Menghao Li, et al.</summary>Zhenghao Zhang, Junchao Liao, Menghao Li, ZuoZhuo Dai, Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
[![code](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social&label=Star)](https://github.com/alibaba/Tora/blob/main/README.md)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-videoai.github.io/tora_video/)

+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** (22 Mar 2025)<details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)
[![code](https://img.shields.io/github/stars/snap-research/vd3d.svg?style=social&label=Star)](https://github.com/snap-research/vd3d/blob/main/index.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/vd3d/)

+ **Motion-Zero: A Zero-Shot Trajectory Control Framework of Moving Object** (08 Jan 2025)<details><summary>Changgu Chen, Junwei Shu, Gaoqi He, et al.</summary>Changgu Chen, Junwei Shu, Gaoqi He, Changbo Wang, Yang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2401.10150v4)
[![code](https://img.shields.io/github/stars/vpx-ecnu/MotionZero-website.svg?style=social&label=Star)](https://github.com/vpx-ecnu/MotionZero-website/blob/main/index.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://litaoguo.github.io/MotionZero.github.io/)

+ **MotionBooth: Motion-Aware Customized Text-to-Video Generation** (29 Oct 2024)  <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
[![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/motionbooth/?ref=aiartweekly)

+ **Freetraj: Tuning-free trajectory control in video diffusion models(T2V)** (24 Jun 2024) <details><summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, et al.</summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, Yingqing He, Menghan Xia, Ziwei Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)
[![code](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](http://github.com/arthur-qiu/FreeTraj)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](freetraj.github.io)

+ **Collaborative video diffusion: Consistent multi-video generation with camera control** (27 May 2024)  <details><summary>Zhengfei Kuang, Shengqu Cai, Hao He, et al.</summary>Zhengfei Kuang, Shengqu Cai, Hao He, Yinghao Xu, Hongsheng Li, Leonidas Guibas, Gordon Wetzstein</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)
[![code](https://img.shields.io/github/stars/CollaborativeVideoDiffusion/collaborativevideodiffusion.github.io.svg?style=social&label=Star)](https://github.com/CollaborativeVideoDiffusion/collaborativevideodiffusion.github.io/blob/main/index.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://collaborativevideodiffusion.github.io/)

+ **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion** (6 May 2024) <details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, et al.</summary>Shiyuan Yang, Liang Hou, Haibin Huang, Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)
  [![Code](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)
  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://direct-a-video.github.io/?ref=aiartweekly)

+ **Peekaboo: Interactive video generation via masked-diffusion(T2V)** (19 Apr 2024)
  <details><summary>Yash Jain, Anshul Nasery, Vibhav Vineet, et al.</summary>Yash Jain, Anshul Nasery, Vibhav Vineet, Harkirat Behl</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2312.07509)
   [![code](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Star)](https://github.com/microsoft/Peekaboo)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yash-jain.com/projects/Peekaboo/)

+ **TrailBlazer: Trajectory Control for Diffusion-Based Video Generation(Both are based on T2V, not I2V.)** (8 Apr 2024)  <details><summary>Wan-Duo Kurt Ma, J.P. Lewis, W. Bastiaan Kleijn, et al.</summary>Wan-Duo Kurt Ma, J.P. Lewis, W. Bastiaan Kleijn</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00896)
[![Code](https://img.shields.io/github/stars/hohonu-vicml/TrailBlazer.svg?style=social&label=Star)](https://github.com/hohonu-vicml/TrailBlazer)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hohonu-vicml.github.io/Trailblazer.Page/)

+ **Controllable Video Generation With Sparse Trajectories** (16 Dec 2018) <details><summary>Zekun Hao, Xun Huang, Serge Belongie, et al.</summary>Zekun Hao, Xun Huang, Serge Belongie</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2018/html/Hao_Controllable_Video_Generation_CVPR_2018_paper.html)
[![code](https://img.shields.io/github/stars/zekunhao1995/ControllableVideoGen.svg?style=social&label=Star)](https://github.com/zekunhao1995/ControllableVideoGen)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)


#### 🎥 Motion Customization/Motion Mask/Motion Video

+ **UniAnimate-DiT: Human Image Animation with Large-Scale Video Diffusion Transformer** (15 Apr 2025) <details><summary>Xiang Wang, Shiwei Zhang, Longxiang Tang, et al.</summary>Xiang Wang, Shiwei Zhang, Longxiang Tang, Yingya Zhang, Changxin Gao, Yuehuan Wang, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.11289)

+ **InterDyn: Controllable Interactive Dynamics with Video Diffusion Models(hand mask sequence as control signal)** (4 Apr 2025) <details><summary>Rick Akkerman, Haiwen Feng, Michael J. Black, et al.</summary>Rick Akkerman, Haiwen Feng, Michael J. Black, Dimitrios Tzionas, Victoria Fern´andez Abrevaya</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11785)
[![code](https://img.shields.io/github/stars/jiuntian/interactdiffusion.svg?style=social&label=Star)](https://github.com/jiuntian/interactdiffusion)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://interdyn.is.tue.mpg.de/)
+ **DreamActor-M1: Holistic, Expressive and Robust Human Image Animation with Hybrid Guidance** (3 Apr 2025) <details><summary>Yuxuan Luo, Zhengkun Rong, Lizhen Wang, et al.</summary>Yuxuan Luo, Zhengkun Rong, Lizhen Wang, Longhao Zhang, Tianshu Hu, Yongming Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.01724)[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://grisoon.github.io/DreamActor-M1/)

+ **Video Motion Transfer with Diffusion Transformers** (27 Mar 2025)<details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, et al.</summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07776)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://ditflow.github.io/)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories** (27 Mar 2025) <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Daniel Geng, Charles Herrmann, Junhwa Hur, Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02700)
+ **EfficientMT: Efficient Temporal Adaptation for Motion Transfer in Text-to-Video Diffusion Models** (25 Mar 2025)  
   <details><summary>Yufei Cai, et al.</summary>  
         Yufei Cai, Hu Han, Yuxiang Wei, Shiguang Shan, Xilin Chen</details>  
         
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19369)
+ **MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance** (20 Mar 2025) <details><summary>Quanhao Li, Zhen Xing, Rui Wang, et al.</summary>Quanhao Li, Zhen Xing, Rui Wang, Hui Zhang, Qi Dai, Zuxuan Wu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.16421v1)
[![Code](https://img.shields.io/github/stars/quanhaol/MagicMotion.svg?style=social&label=Star)](https://github.com/quanhaol/MagicMotion)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://quanhaol.github.io/magicmotion-site/)

+ **LHM: Large Animatable Human Reconstruction Model for Single Image to 3D in Seconds** (13 Mar 2025)  <details><summary>Lingteng Qiu, Xiaodong Gu, Peihao Li, et al.</summary>Lingteng Qiu, Xiaodong Gu, Peihao Li, Qi Zuo, Weichao Shen, Junfei Zhang, Kejie Qiu, Weihao Yuan, Guanying Chen, Zilong Dong, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.10625)
[![Code](https://img.shields.io/github/stars/aigc3d/LHM.svg?style=social&label=Star)](https://github.com/aigc3d/LHM)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lingtengqiu.github.io/LHM/)

+ **DreamRelation: Relation-Centric Video Customization** (10 Mar 2025) <details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, et al.</summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, Biao Gong, Longxiang Tang, Xiang Wang, Haonan Qiu, Hengjia Li, Shuai Tan, Yingya Zhang, Hongming Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07602)
[![code](https://img.shields.io/github/stars/mayuelala/Awesome-Controllable-Video-Generation.svg?style=social&label=Star)](https://github.com/mayuelala/Awesome-Controllable-Video-Generation)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamrelation.github.io/#)

+ **MotionMatcher: Motion Customization of Text-to-Video Diffusion Models via Motion Feature Matching** (18 Feb 2025) <details><summary>Yen-Siang Wu, Chi-Pin Huang, Fu-En Yang, et al.</summary>Yen-Siang Wu, Chi-Pin Huang, Fu-En Yang, Yu-Chiang Frank Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.13234)
[![Code](https://img.shields.io/github/stars/b09902097/motionmatcher.svg?style=social&label=Star)](https://github.com/b09902097/motionmatcher)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aiartweekly.com/tools/motionmatcher-motion-customization-of-text-to-video-diffusion-models-via-motion-feature-matching)

+ **MotionAgent: Fine-grained Controllable Video Generation via Motion Field Agent** (5 Feb 2025)  <details><summary>Xinyao Liao, Xianfang Zeng, Liao Wang</summary>Xinyao Liao, Xianfang Zeng, Liao Wang, Gang Yu, Guosheng Lin, Chi Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.03207)
[![code](https://img.shields.io/github/stars/modelscope/motionagent.svg?style=social&label=Star)](github.com/modelscope/motionagent/blob/main/README_ZH.md)


+ **Training-Free Motion-Guided Video Generation with Enhanced Temporal Consistency Using Motion Consistency Loss** (13 Jan 2025) <details><summary>Xinyu Zhang, Zicheng Duan, Dong Gong, et al.</summary>Xinyu Zhang, Zicheng Duan, Dong Gong, Lingqiao Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.07563)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhangxinyu-xyz.github.io/SimulateMotion.github.io/)

+ **SST-EM: Advanced Metrics for Evaluating Semantic, Spatial and Temporal Aspects in Video Editing** (13 Jan 2025) <details><summary>Varun Biyyala, Bharat Chanderprakash Kathuria, Jialu Li, et al.</summary>Varun Biyyala, Bharat Chanderprakash Kathuria, Jialu Li, and Youshan Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.07554)
[![code](https://img.shields.io/github/stars/tangwen-qian/DailyArXiv.svg?style=social&label=Star)](https://github.com/tangwen-qian/DailyArXiv/issues/199)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sinoxiv.napstic.cn/article/14698631)

+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** (9 Jan 2025) <details><summary>Zekai Gu, Rui Yan, Jiahao Lu, et al.</summary>Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03847)
[![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://igl-hkust.github.io/das/)

+ **Spectral Motion Alignment for Video Motion Transfer using Diffusion Models** (19 Dec 2024)<details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, et al.</summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.15249)
[![Code](https://img.shields.io/github/stars/iffusion-motion-transfer/diffusion-motion-transfer.svg?style=social&label=Star)](https://github.com/diffusion-motion-transfer/diffusion-motion-transfer)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://geonyeong-park.github.io/spectral-motion-alignment/)

+ **MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models** (2 Dec 2024)<details><summary>Xiaomin Li, Xu Jia, Qinghe Wang, et al.</summary>Xiaomin Li, Xu Jia, Qinghe Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01343)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sinoxiv.napstic.cn/article/14430132)

+ **OnlyFlow: Optical Flow based Motion Conditioning for Video Diffusion ModelsOnlyFlow: Optical Flow based Motion Conditioning for Video Diffusion Models** (15 Nov 2024) <details><summary>Mathis Koroglu, Hugo Caselles-Dupré, Guillaume Jeanneret Sanmiguel, et al.</summary>Mathis Koroglu, Hugo Caselles-Dupré, Guillaume Jeanneret Sanmiguel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10501)
[![code](https://img.shields.io/github/stars/obvious-research/onlyflow.svg?style=social&label=Star)](https://github.com/obvious-research/onlyflow)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://obvious-research.github.io/onlyflow/)

+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (12 Nov 2024) <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, et al.</summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)
[![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/?ref=aiartweekly)

+ **AnimateAnything: Consistent and Controllable Animation for Video Generation** (16 Nov 2024) <details><summary>Guojun Lei, Chi Wang, Hong Li, et al.</summary>Guojun Lei, Chi Wang, Hong Li, Rong Zhang, Yikai Wang, Weiwei Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://animationai.github.io/AnimateAnything/)
[![Code](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yu-shaonian.github.io/Animate_Anything/)


+ **Motionbooth: Motion-aware customized text-to-video generation** (29 Oct 2024) <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
[![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://jianzongwu.github.io/projects/motionbooth/)

+ **MotionClone: Training-Free Motion Cloning for Controllable Video Generation** (22 Oct 2024) <details><summary>Pengyang Ling, Jiazi Bu, Pan Zhang, et al.</summary>Pengyang Ling, Jiazi Bu, Pan Zhang, Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian Chen, Jiaqi Wang, Yi Jin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
[![Code](https://img.shields.io/github/stars/LPengYang/MotionClone.svg?style=social&label=Star)](https://github.com/LPengYang/MotionClone)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bujiazi.github.io/motionclone.github.io/)

+ **Motion Inversion for Video Customization** (16 Oct 2024)  <details><summary>Luozhou Wang, Ziyang Mai, Guibao Shen, et al.</summary>Luozhou Wang, Ziyang Mai, Guibao Shen, Yixuan Liang, Xin Tao, Pengfei Wan, Di Zhang, Yijun Li, Yingcong Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.20193)
[![Code](https://img.shields.io/github/stars/EnVision-Research/MotionInversion.svg?style=social&label=Star)](https://github.com/EnVision-Research/MotionInversion)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wileewang.github.io/MotionInversion/)
+ **Zero-Shot Controllable Image-to-Video Animation via Motion Decomposition** (21 Jul 2024)<details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, et al.</summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=vngElHOj2N&referrer=%5Bthe%20profile%20of%20Mohit%20Bansal%5D(%2Fprofile%3Fid%3D~Mohit_Bansal2))
[![Code](https://img.shields.io/github/stars/baaivision/NOVA.svg?style=social&label=Star)](https://github.com/Yui010206/IVA-0) 
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yui010206.github.io/)


+ **DreamMotion: Space-Time Self-Similar Score Distillation for Zero-Shot Video Editing** (15 Jul 2024) <details><summary>Hyeonho Jeong, Jinho Chang, Geon Yeong Park, et al.</summary>Hyeonho Jeong, Jinho Chang, Geon Yeong Park, and Jong Chul Ye</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2403.12002)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyeonho99.github.io/dreammotion/)

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (1 Jun 2024) <details><summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** (28 Aug 2024)  <details><summary>Yixuan Ren, Yang Zhou, Jimei Yang, et al.</summary>Yixuan Ren, Yang Zhou, Jimei Yang, Jing Shi, Difan Liu, Feng Liu, Mingi Kwon, Abhinav Shrivastava</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
[![Code](https://img.shields.io/github/stars/customize-a-video/customize-a-video.svg?style=social&label=Star)](https://github.com/customize-a-video/customize-a-video)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.aimodels.fyi/papers/arxiv/customize-video-one-shot-motion-customization-text)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (7 Dec 2023) <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2501.05020)
[![Code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/)

+ **DreamVideo: Composing Your Dream Videos with Customized Subject and Motion** (7 Dec 2023) <details><summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing</summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing, Hangjie Yuan, Zhiheng Liu, Yu Liu, Yingya Zhang, Jingren Zhou, Hongming Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
[![code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamvideo-t2v.github.io/)

+ **VMC: Video Motion Customization with Pre-trained Diffusion Models** (1 Dec 2023)<details><summary>Hyeonho Jeong, Geon Yeong Park, Jong Chul Ye, et al.</summary>Hyeonho Jeong, Geon Yeong Park, Jong Chul Ye</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00845)
[![Code](https://img.shields.io/github/stars/HyeonHo99/Video-Motion-Customization.svg?style=social&label=Star)](https://github.com/HyeonHo99/Video-Motion-Customization)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-motion-customization.github.io/?ref=aiartweekly)

+ **Space-Time Diffusion Features for Zero-Shot Text-Driven Motion Transfer** (3 Dec 2023) <details><summary>Danah Yatim, Rafail Fridman, Omer Bar-Tal, et al.</summary>Danah Yatim, Rafail Fridman, Omer Bar-Tal, Yoni Kasten, Tali Dekel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17009)
[![Code](https://img.shields.io/github/stars/EnVision-Research/MotionInversion.svg?style=social&label=Star)](https://github.com/EnVision-Research/MotionInversion)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://diffusion-motion-transfer.github.io/)

+ **MotionDirector: Motion Customization for Text-to-Video Diffusion Models** (12 Oct 2023)<details><summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, et al.</summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, David Junhao Zhang, Jia-Wei Liu, Weijia Wu, Jussi Keppo, and Mike Zheng Shou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
[![Code](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ruizhaocv.github.io/)




### 📝 Advanced Text-Conditioned

### 🔄 In-Context

### 🖼️ Image-guided

+ **HunyuanVideo: A Systematic Framework For Large Video Generative Models** (11 Mar 2025)<details><summary>Weijie Kong, Qi Tian, Zijian Zhang, et al.</summary>Rox Min, Zuozhuo Dai, Jin Zhou, Jiangfeng Xiong, Xin Li, Bo Wu, Jianwei Zhang, Kathrina Wu, Qin Lin, Junkun Yuan, Yanxin Long, Aladdin Wang, Andong Wang, Changlin Li, Duojun Huang, Fang Yang, Hao Tan, Hongmei Wang, Jacob Song, Jiawang Bai, Jianbing Wu, Jinbao Xue, Joey Wang, Kai Wang, Mengyang Liu, Pengyu Li, Shuai Li, Weiyan Wang, Wenqing Yu, Xinchi Deng, Yang Li, Yi Chen, Yutao Cui, Yuanbo Peng, Zhentao Yu, Zhiyu He, Zhiyong Xu, Zixiang Zhou, Zunnan Xu, Yangyu Tao, Qinglin Lu, Songtao Liu, Dax Zhou, Hongfa Wang, Yong Yang, Di Wang, Yuhong Liu, Jie Jiang, Caesar Zhong</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://arxiv.org/abs/2412.03603)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=1fa298e3f745099d39ca5bd088fcb62f87e8cc2f)](https://www.semanticscholar.org/paper/1fa298e3f745099d39ca5bd088fcb62f87e8cc2f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aivideo.hunyuan.tencent.com/)
[![Code](https://img.shields.io/github/stars/Tencent/HunyuanVideo-I2V.svg?style=social&label=Star)](https://github.com/Tencent/HunyuanVideo-I2V)

+ **Extrapolating and Decoupling Image-to-Video Generation Models: Motion Modeling is Easier Than You Think** (2 Mar 2025)<details><summary>[CVPR 2025] Jie Tian, Xiaoye Qu, Zhenyi Lu, et al.</summary>Wei Wei, Sichen Liu, Yu Cheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00948)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=7ab6ed3edb7d781a34f2c8a67aa974903b1f9f4f)](https://www.semanticscholar.org/paper/7ab6ed3edb7d781a34f2c8a67aa974903b1f9f4f)
[![Code](https://img.shields.io/github/stars/Chuge0335/EDG.svg?style=social&label=Star)](https://github.com/Chuge0335/EDG)

+ **Adapting Image-to-Video Diffusion Models for Large-Motion Frame Interpolation** (17 Feb 2025)<details><summary>Luoxu Jin, Hiroshi Watanabe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17042)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=25fc7b5cdfaf5ecca730115671788dbde95c96c4)](https://www.semanticscholar.org/paper/25fc7b5cdfaf5ecca730115671788dbde95c96c4)

+ **Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation** (12 Feb 2025)<details><summary>[ICLR 2025] Xiaojuan Wang, Boyang Zhou, Brian Curless, et al.</summary>Ira Kemelmacher-Shlizerman, Aleksander Holynski, Steven M. Seitz</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15239)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=d6837b60f100b40c5ee2284fbee3134a904c0603)](https://www.semanticscholar.org/paper/d6837b60f100b40c5ee2284fbee3134a904c0603)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://svd-keyframe-interpolation.github.io/)
[![Code](https://img.shields.io/github/stars/jeanne-wang/svd_keyframe_interpolation.svg?style=social&label=Star)](https://github.com/jeanne-wang/svd_keyframe_interpolation)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/svd_keyframe_interpolation)


+ **Autoregressive Video Generation without Vector Quantization** (9 Jan 2025)<details><summary>[ICLR 2025] Haoge Deng, Ting Pan, Haiwen Diao, et al.</summary>Zhengxiong Luo, Yufeng Cui, Huchuan Lu, Shiguang Shan, Yonggang Qi, Xinlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14169)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=735b7f4f91bcc5e9712df7f419eade672b1d3968)](https://www.semanticscholar.org/paper/735b7f4f91bcc5e9712df7f419eade672b1d3968)
[![Code](https://img.shields.io/github/stars/baaivision/NOVA.svg?style=social&label=Star)](https://github.com/baaivision/NOVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BAAI/nova-d48w1024-osp480)


+ **Through-The-Mask: Mask-based Motion Trajectories for Image-to-Video Generation** (6 Jan 2025)<details><summary>[CVPR 2025] Guy Yariv, Yuval Kirstain, Amit Zohar, et al.</summary>Shelly Sheynin, Yaniv Taigman, Yossi Adi, Sagie Benaim, Adam Polyak</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03059)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=44eac98880108aef441ee8ca0c0edac9a8d53b67)](https://www.semanticscholar.org/paper/44eac98880108aef441ee8ca0c0edac9a8d53b67)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guyyariv.github.io/TTM/)





+ **STIV: Scalable Text and Image Conditioned Video Generation** (10 Dec 2024)<details><summary>Zongyu Lin, Wei Liu, Chen Chen, et al.</summary>Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07730)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=20ae850e781fc07eb08311df7772010da3123f98)](https://www.semanticscholar.org/paper/20ae850e781fc07eb08311df7772010da3123f98)

+ **MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation** (8 Dec 2024)<details><summary>Shuwei Shi, Biao Gong, Xi Chen, et al.</summary>Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05848)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=d66fa35283319bacc82cbbde80b7cc710bd4cb38)](https://www.semanticscholar.org/paper/d66fa35283319bacc82cbbde80b7cc710bd4cb38)

+ **Lumiere: A Space-Time Diffusion Model for Video Generation** (3 Dec 2024)<details><summary>[SIGGRAPH Asia 2024] Omer Bar-Tal, Hila Chefer, Omer Tov, et al.</summary>Charles Herrmann, Roni Paiss, Shiran Zada, Ariel Ephrat, Junhwa Hur, Guanghui Liu, Amit Raj, Yuanzhen Li, Michael Rubinstein, Tomer Michaeli, Oliver Wang, Deqing Sun, Tali Dekel, Inbar Mosseri</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/full/10.1145/3680528.3687614)
[![citation](https://img.shields.io/badge/citation-189-blue.svg?paper=94f7d8bce3bb848d127c8f113afc5bb0243579df)](https://www.semanticscholar.org/paper/94f7d8bce3bb848d127c8f113afc5bb0243579df)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lumiere-video.github.io/)

+ **Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model** (6 Nov 2024)<details><summary>[NeurIPS 2024] Min Zhao, Hongzhou Zhu, Chendong Xiang, et al.</summary>Kaiwen Zheng, Chongxuan Li, Jun Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=ebf4f746d24d79d61c070f8c354b3371f461aafb)](https://www.semanticscholar.org/paper/ebf4f746d24d79d61c070f8c354b3371f461aafb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cond-image-leak.github.io/)
[![Code](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social&label=Star)](https://github.com/thu-ml/cond-image-leakage)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Xiang-cd/DynamiCrafter-CIL)


+ **FrameBridge: Improving Image-to-Video Generation with Bridge Models** (20 Oct 2024)<details><summary>Yuji Wang, Zehua Chen, Xiaoyu Chen, et al.</summary>Jun Zhu, Jianfei Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15371)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=355544f41ff0f28234c3f5190a7ce75d74dd8f61)](https://www.semanticscholar.org/paper/355544f41ff0f28234c3f5190a7ce75d74dd8f61)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://framebridge-demo.github.io/)



+ **I4VGen: Image as Free Stepping Stone for Text-to-Video Generation** (3 Oct 2024)<details><summary>Xiefan Guo, Jinlin Liu, Miaomiao Cui, et al.</summary>Liefeng Bo, Di Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02230)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=74b41f1723263a8a2f2999a0cdffb57b79b1e97e)](https://www.semanticscholar.org/paper/74b41f1723263a8a2f2999a0cdffb57b79b1e97e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiefan-guo.github.io/i4vgen/)
[![Code](https://img.shields.io/github/stars/xiefan-guo/i4vgen.svg?style=social&label=Star)](https://github.com/xiefan-guo/i4vgen)


+ **DynamiCrafter: Animating Open-Domain Images with Video Diffusion Priors** (1 Oct 2024)<details><summary>[ECCV 2024] Jinbo Xing, Menghan Xia, Yong Zhang,  et al.</summary>Haoxin Chen, Wangbo Yu, Hanyuan Liu, Gongye Liu, Xintao Wang, Ying Shan, Tien-Tsin Wong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-72952-2_23)
[![citation](https://img.shields.io/badge/citation-152-blue.svg?paper=083bab4a967c2221d9f4da9110fe37d8ca679078)](https://www.semanticscholar.org/paper/083bab4a967c2221d9f4da9110fe37d8ca679078)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/DynamiCrafter/)
[![Code](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/DynamiCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Doubiiu/DynamiCrafter)



+ **PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation** (27 Sep 2024)<details><summary>[ECCV 2024] Shaowei Liu, Zhongzheng Ren, Saurabh Gupta, et al.</summary>Shenlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18964)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=3c314149c36871bace898f3dcff03fb21de0ba64)](https://www.semanticscholar.org/paper/3c314149c36871bace898f3dcff03fb21de0ba64)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://stevenlsw.github.io/physgen/)
[![Code](https://img.shields.io/github/stars/stevenlsw/physgen.svg?style=social&label=Star)](https://github.com/stevenlsw/physgen)


+ **Structure and Content-Guided Video Synthesis with Diffusion Models** (27 Sep 2024)<details><summary>[ICCV 2023] Patrick Esser, Johnathan Chiu, Parmida Atighehchian, et al.</summary>Jonathan Granskog, Anastasis Germanidis</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.html)
[![citation](https://img.shields.io/badge/citation-459-blue.svg?paper=07be0ec1f45e21a1032616535d0290ee6bfe0f6b)](https://www.semanticscholar.org/paper/07be0ec1f45e21a1032616535d0290ee6bfe0f6b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://runwayml.com/research/gen-1)

+ **DreamVideo: High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance** (16 Sep 2024)<details><summary>[ICASSP 2025] Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary>Songcen Xu, Hang Xu, Xiaodan Liang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/abstract/document/10887583)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=a30883a9408914732f816933f0a5f1f3980fd5c8)](https://www.semanticscholar.org/paper/a30883a9408914732f816933f0a5f1f3980fd5c8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anonymous0769.github.io/DreamVideo/)
[![Code](https://img.shields.io/github/stars/anonymous0769/DreamVideo.svg?style=social&label=Star)](https://github.com/anonymous0769/DreamVideo)



+ **Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning** (2 Aug 2024)<details><summary>[ECCV 2024] Rohit Girdhar, Mannat Singh, Andrew Brown, et al.</summary>Quentin Duval, Samaneh Azadi, Sai Saketh Rambhatla, Akbar Shah, Xi Yin, Devi Parikh, Ishan Misra</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10709)
[![citation](https://img.shields.io/badge/citation-179-blue.svg?paper=85b10400864187230714506412c85610c786b5c3)](https://www.semanticscholar.org/paper/85b10400864187230714506412c85610c786b5c3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://emu-video.metademolab.com/)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://emu-video.metademolab.com/#/demo)


+ **MoVideo: Motion-Aware Video Generation with Diffusion Model** (29 Jul 2024)<details><summary>[ECCV 2024] Jingyun Liang, Yuchen Fan, Kai Zhang, et al.</summary>Radu Timofte, Luc Van Gool, Rakesh Ranjan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=b57a0f46b4b5148b8bdd3cc2969d4ed43333bda0)](https://www.semanticscholar.org/paper/b57a0f46b4b5148b8bdd3cc2969d4ed43333bda0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyunliang.github.io/MoVideo/)


+ **I2V-Adapter: A General Image-to-Video Adapter for Diffusion Models** (13 Jul 2024)<details><summary>[ACM SIGGRAPH 2024] Xun Guo1, Mingwu Zheng, Liang Hou, et al.</summary>Yuan Gao, Yufan Deng, Pengfei Wan,
Di Zhang, Yufan Liu, Weiming Hu, Zhengjun Zha, Haibin Huang, Chongyang Ma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657407)
[![citation](https://img.shields.io/badge/citation-21-blue.svg?paper=9512a9bbef95560c719a746676611bfcded428a1)](https://www.semanticscholar.org/paper/9512a9bbef95560c719a746676611bfcded428a1)



+ **EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture** (5 Jul 2024)<details><summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, et al.</summary>Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18991)
[![citation](https://img.shields.io/badge/citation-26-blue.svg?paper=40122a222374504fda4997ef6204dcdcee1678da)](https://www.semanticscholar.org/paper/40122a222374504fda4997ef6204dcdcee1678da)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://easyanimate.github.io/)
[![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star)](https://github.com/aigc-apps/EasyAnimate)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/alibaba-pai/EasyAnimate)


+ **ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation** (1 Jul 2024)<details><summary>[TMLR 2024] Weiming Ren, Huan Yang, Ge Zhang, et al.</summary>Cong Wei, Xinrun Du, Wenhao Huang, Wenhu Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.04324)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=d599dc40c9cb8d6d76554ee7d21d20c22cc7cdb5)](https://www.semanticscholar.org/paper/d599dc40c9cb8d6d76554ee7d21d20c22cc7cdb5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tiger-ai-lab.github.io/ConsistI2V/)
[![Code](https://img.shields.io/github/stars/TIGER-AI-Lab/ConsistI2V.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/ConsistI2V)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/TIGER-Lab/ConsistI2V)



+ **OmniTokenizer: A Joint Image-Video Tokenizer for Visual Generation** (13 Jun 2024)<details><summary>[NeurIPS 2024] Junke Wang, Yi Jiang, Zehuan Yuan, et al.</summary>Binyue Peng, Zuxuan Wu, Yu-Gang Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09399)
[![citation](https://img.shields.io/badge/citation-27-blue.svg?paper=8613c1081a6ab34e2f980e35c06a1af461d7314e)](https://www.semanticscholar.org/paper/8613c1081a6ab34e2f980e35c06a1af461d7314e)
[![Code](https://img.shields.io/github/stars/FoundationVision/OmniTokenizer.svg?style=social&label=Star)](https://github.com/FoundationVision/OmniTokenizer)



+ **AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction** (10 Jun 2024)<details><summary>Zhen Xing, Qi Dai, Zejia Weng, et al.</summary>Zuxuan Wu, Yu-Gang Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06465)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=d657de11802239a58a77f486a0c6861e89d4da50)](https://www.semanticscholar.org/paper/d657de11802239a58a77f486a0c6861e89d4da50)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenhsing.github.io/AID/)
[![Code](https://img.shields.io/github/stars/ChenHsing/AID.svg?style=social&label=Star)](https://github.com/ChenHsing/AID)


+ **TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models** (25 Apr 2024)<details><summary>[CVPR 2024] Haomiao Ni, Bernhard Egger, Suhas Lohit, et al.</summary>Anoop Cherian, Ye Wang, Toshiaki Koike-Akino, Sharon X. Huang, Tim K. Marks</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=5cbe42a201e2d1a90ac83dadc78afec6a3d20fec)](https://www.semanticscholar.org/paper/5cbe42a201e2d1a90ac83dadc78afec6a3d20fec)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.merl.com/demos/TI2V-Zero)
[![Code](https://img.shields.io/github/stars/merlresearch/TI2V-Zero.svg?style=social&label=Star)](https://github.com/merlresearch/TI2V-Zero)



+ **TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models** (25 Mar 2024)<details><summary>[CVPR 2024] Zhongwei Zhang, Fuchen Long, Yingwei Pan, et al.</summary>Zhaofan Qiu, Ting Yao, Yang Cao, Tao Mei</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_TRIP_Temporal_Residual_Learning_with_Image_Noise_Prior_for_Image-to-Video_CVPR_2024_paper.html)
[![citation](https://img.shields.io/badge/citation-17-blue.svg?paper=c87c910063dfaba7b5abcf49989a6e9ae1d9d7ce)](https://www.semanticscholar.org/paper/c87c910063dfaba7b5abcf49989a6e9ae1d9d7ce)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://trip-i2v.github.io/TRIP/)
+ **Follow-Your-Click: Open-domain Regional Image Animation via Short Prompts** (13 Mar 2024)<details><summary>Yue Ma, Yingqing He, Hongfa Wang, et al.</summary>Andong Wang, Chenyang Qi, Chengfei Cai, Xiu Li, Zhifeng Li, Heung-Yeung Shum, Wei Liu, Qifeng Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08268)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=d9c20c449a51910ef2d107668d962b4a2e182f52)](https://www.semanticscholar.org/paper/d9c20c449a51910ef2d107668d962b4a2e182f52)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-click.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourClick.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourClick)

+ **AtomoVideo: High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Litong Gong, Yiran Zhu, Weijie Li, et al.</summary>Xiaoyang Kang, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01800)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=1f2dfc535180bf6806b13086fe4f25d622483ada)](https://www.semanticscholar.org/paper/1f2dfc535180bf6806b13086fe4f25d622483ada)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://atomo-video.github.io/)


+ **Tuning-Free Noise Rectification for High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Weijie Li, Litong Gong, Yiran Zhu, et al.</summary>Fanda Fan, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02827)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=cf0a5c9eeaf52d02661c8a52c2ccc12d7fb58b15)](https://www.semanticscholar.org/paper/cf0a5c9eeaf52d02661c8a52c2ccc12d7fb58b15)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://noise-rectification.github.io/)
[![Code](https://img.shields.io/github/stars/alimama-creative/Noise-Rectification.svg?style=social&label=Star)](https://github.com/alimama-creative/Noise-Rectification)

+ **Motion-i2v: Consistent and controllable image-to-video generation with explicit motion modeling** (31 Jan 2024)<details><summary>[ACM SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657497)
[![citation](https://img.shields.io/badge/citation-61-blue.svg?paper=450011c7e089675b25dad11cd7611c310a7a8e9b)](https://www.semanticscholar.org/paper/450011c7e089675b25dad11cd7611c310a7a8e9b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)


+ **UniVG: Towards UNIfied-modal Video Generation** (17 Jan 2024)<details><summary>Ludan Ruan, Lei Tian, Chuanwei Huang, et al.</summary>Xu Zhang, Xinyan Xiao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=147ceee32c1e33f332ac7b2dcabf397788a01d1a)](https://www.semanticscholar.org/paper/147ceee32c1e33f332ac7b2dcabf397788a01d1a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://univg-baidu.github.io/)


+ **Decouple Content and Motion for Conditional Image-to-Video Generation** (14 Dec 2023)<details><summary>[AAAI 2024] Cuifeng Shen, Yulu Gan, Chen Chen, et al.</summary>Xiongwei Zhu, Lele Cheng, Tingting Gao, Jinzhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=8e37c6d2442ece49a80e63b65bcc4e9c0b49d580)](https://www.semanticscholar.org/paper/8e37c6d2442ece49a80e63b65bcc4e9c0b49d580)


+ **AnimateAnything: Fine-Grained Open Domain Image Animation with Motion Guidance** (4 Dec 2023)<details><summary>[TMLR 2024] Zuozhuo Dai, Zhenghao Zhang, Yao Yao, et al.</summary>Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12886)
[![citation](https://img.shields.io/badge/citation-40-blue.svg?paper=ff1715c4a33a58cc8069b86be8b99e760134eb78)](https://www.semanticscholar.org/paper/ff1715c4a33a58cc8069b86be8b99e760134eb78)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://animationai.github.io/AnimateAnything/)
[![Code](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)



+ **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** (25 Nov 2023)<details><summary>Andreas Blattmann, Tim Dockhorn, Sumith Kulal, et al.</summary>Daniel Mendelevitch, Maciej Kilian, Dominik Lorenz, Yam Levi, Zion English, Vikram Voleti, Adam Letts, Varun Jampani, Robin Rombach</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
[![citation](https://img.shields.io/badge/citation-878-blue.svg?paper=1206b05eae5a06ba662ae79fb291b50e359c4f42)](https://www.semanticscholar.org/paper/1206b05eae5a06ba662ae79fb291b50e359c4f42)
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)

+ **I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models** (7 Nov 2023)<details><summary>Shiwei Zhang, Jiayu Wang, Yingya Zhang, et al.</summary>Kang Zhao, Hangjie Yuan, Zhiwu Qin, Xiang Wang, Deli Zhao, Jingren Zhou</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04145)
[![citation](https://img.shields.io/badge/citation-168-blue.svg?paper=9b86ce1bde87b304141641b49299f4d0f1f7ba1d)](https://www.semanticscholar.org/paper/9b86ce1bde87b304141641b49299f4d0f1f7ba1d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://i2vgen-xl.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)







+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** (30 Oct 2023)<details><summary>Haoxin Chen, Menghan Xia, Yingqing He, et al.</summary>Yong Zhang, Xiaodong Cun, Shaoshu Yang, Jinbo Xing, Yaofang Liu, Qifeng Chen, Xintao Wang, Chao Weng, Ying Shan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![citation](https://img.shields.io/badge/citation-244-blue.svg?paper=1891c3756f870d902a0b793a1dcd5cc34c778612)](https://www.semanticscholar.org/paper/1891c3756f870d902a0b793a1dcd5cc34c778612)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter2/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/VideoCrafter/VideoCrafter)



+ **Synthesizing Videos from Images for Image-to-Video Adaptation** (27 Oct 2023)<details><summary>[ACM MM 2023] Junbao Zhuo, Xingyu Zhao, Shuhui Wang, et al.</summary>Huimin Ma, Qingming Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3581783.3611897)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=b26d4c0b127e4a3e81b94cad4b2c8ecb0dda1bd9)](https://www.semanticscholar.org/paper/b26d4c0b127e4a3e81b94cad4b2c8ecb0dda1bd9)
[![Code](https://img.shields.io/github/stars/junbaoZHUO/ST-I2V.svg?style=social&label=Star)](https://github.com/junbaoZHUO/ST-I2V)


+ **VideoDoodles: Hand-Drawn Animations on Videos with Scene-Aware Canvases** (26 Jul 2023)<details><summary>[ACM Transactions on Graphics] Emilie Yu, Kevin Blackburn-Matzen, Cuong Nguyen, et al.</summary>Oliver Wang, Rubaiat Habib Kazi, Adrien Bousseau</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3592413)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=ffd1f7b6bc38579b5e4a02d1cde64bdda030dce5)](https://www.semanticscholar.org/paper/ffd1f7b6bc38579b5e4a02d1cde64bdda030dce5)

+ **LaMD: Latent Motion Diffusion for Video Generation** (23 Apr 2023)<details><summary>Yaosi Hu, Zhenzhong Chen, Chong Luo</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603)
[![citation](https://img.shields.io/badge/citation-16-blue.svg?paper=e1d5c8ee59031f19ea9979d05f6e92295a540f88)](https://www.semanticscholar.org/paper/e1d5c8ee59031f19ea9979d05f6e92295a540f88)




+ **Prompt Image to Life: Training-Free Text-Driven Image-to-Video Generation** (2023)<details><summary>Jinxiu Liu, Yuan Yao, Bingwen Zhu, et al.</summary>Fanyi Wang, Weijian Luo, Jingwen Su,
Yanhao Zhang, Yuxiao Wang, Liyuan Ma, Qi Liu, Jiebo Luo, Guo-Jun Qi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.cs.rochester.edu/u/yyao39/files/PiLife.pdf)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=ed1dfe38b52c0c1cdd8b20f860520858f28ed9a6)](https://www.semanticscholar.org/paper/ed1dfe38b52c0c1cdd8b20f860520858f28ed9a6)




+ **Make It Move: Controllable Image-to-Video Generation With Text Descriptions** (31 Mar 2022)<details><summary>[CVPR 2022] Yaosi Hu, Chong Luo, Zhenzhong Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Make_It_Move_Controllable_Image-to-Video_Generation_With_Text_Descriptions_CVPR_2022_paper.html)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=e829046a7f9a65e3bbe937ce4ce4649a0f78f0e7)](https://www.semanticscholar.org/paper/e829046a7f9a65e3bbe937ce4ce4649a0f78f0e7)
[![Code](https://img.shields.io/github/stars/Youncy-Hu/MAGE.svg?style=social&label=Star)](https://github.com/Youncy-Hu/MAGE)


### 🔊 Sound-Guided

+ **Sound-Guided Semantic Video Generation** (20 Apr 2022) <details><summary>[ECCV 2022] Seung Hyun Lee, Gyeongrok Oh, Wonmin Byeon, et al.</summary>
Seung Hyun Lee, Gyeongrok Oh, Wonmin Byeon, Chanyoung Kim, Won Jeong Ryoo, Sang Ho Yoon, Hyunjun Cho, Jihyun Bae, Jinkyu Kim, Sangpil Kim</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.09273)
[![Code](https://img.shields.io/github/stars/kuai-lab/sound2video.svg?style=social&label=Star)](https://github.com/kuai-lab/sound2video)


### 🎵 Audio/Music-Guided

+ **AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation** (19 Dec 2024)<details><summary>Moayed Haji-Ali, Willi Menapace, Aliaksandr Siarohin, et al.</summary>
Moayed Haji-Ali, Willi Menapace, Aliaksandr Siarohin, Ivan Skorokhodov, Alper Canberk, Kwot Sin Lee, Vicente Ordonez, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
[![Code](https://img.shields.io/github/stars/snap-research/AVLink.svg?style=social&label=Star)](https://github.com/snap-research/AVLink)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/AVLink/)

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (30 May 2024) <details><summary>[ECCV 2024] Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>
Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
[![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)

+ **Audio-Synchronized Visual Animation** (08 Mar 2024) <details><summary>[ECCV 2024] Lin Zhang, Shentong Mo, Yijing Zhang, et al.</summary>
Lin Zhang, Shentong Mo, Yijing Zhang, Pedro Morgado </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.05659)
[![Code](https://img.shields.io/github/stars/lzhangbj/ASVA.svg?style=social&label=Star)](https://github.com/lzhangbj/ASVA)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://lzhangbj.github.io/projects/asva/asva.html)

+ **Ta2v: Text-audio guided video generation** (01 Jan 2024) <details><summary>[TMM] Minglu Zhao, Wenmin Wang, Tongbao Chen, et al.</summary>
Minglu Zhao, Wenmin Wang, Tongbao Chen, Rui Zhang, Ruochen Li </details>
[![Paper](https://img.shields.io/badge/paper-b31b1b.svg)](https://dl.acm.org/doi/10.1109/TMM.2024.3362149)
[![Code](https://img.shields.io/github/stars/Minglu58/TA2V.svg?style=social&label=Star)](https://github.com/Minglu58/TA2V)

+ **Diverse and Aligned Audio-to-Video Generation via Text-to-Video Model Adaptation** (28 Sep 2023)<details><summary>[AAAI 2024] Guy Yariv, Itai Gat, Sagie Benaim, et al.</summary>
Guy Yariv, Itai Gat, Sagie Benaim, Lior Wolf, Idan Schwartz, Yossi Adi</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
[![Code](https://img.shields.io/github/stars/guyyariv/TempoTokens.svg?style=social&label=Star)](https://github.com/guyyariv/TempoTokens)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pages.cs.huji.ac.il/adiyoss-lab/TempoTokens/)


### 🗂️ Layout Control

+ **HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for   Autonomous Driving** (02 Dec 2024)<details><summary>Zehuan Wu, Jingcheng Ni, Xiaodong Wang, et al.</summary>
Zehuan Wu, Jingcheng Ni, Xiaodong Wang, Yuxin Guo, Rui Chen, Lewei Lu, Jifeng Dai, Yuwen Xiong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01407)

+ **DriveScape: Towards High-Resolution Controllable Multi-View Driving   Video Generation** (09 Sep 2024)<details><summary>Wei Wu, Xi Guo, Weixuan Tang, et al.</summary>
Wei Wu, Xi Guo, Weixuan Tang, Tingxuan Huang, Chiyu Wang, Dongyue Chen, Chenjing Ding</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05463)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://metadrivescape.github.io/papers_project/drivescapev1/index.html)

+ **DriveScape: Towards High-Resolution Controllable Multi-View Driving   Video Generation** (09 Sep 2024)<details><summary>Wei Wu, Xi Guo, Weixuan Tang, et al.</summary>
Wei Wu, Xi Guo, Weixuan Tang, Tingxuan Huang, Chiyu Wang, Dongyue Chen, Chenjing Ding</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05463)

+ **DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View   Driving Scenes** (06 Sep 2024)<details><summary>Jianbiao Mei, Tao Hu, Xuemeng Yang, et al.</summary>
Jianbiao Mei, Tao Hu, Xuemeng Yang, Licheng Wen, Yu Yang, Tiantian Wei, Yukai Ma, Min Dou, Botian Shi, Yong Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04003)
[![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star)](https://github.com/PJLab-ADG/DriveArena)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pjlab-adg.github.io/DriveArena/dreamforge/)

+ **DiVE: DiT-based Video Generation with Enhanced Control** (03 Sep 2024)<details><summary>Junpeng Jiang, Gangyi Hong, Lijun Zhou, et al.</summary>
Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01595)
[![Code](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Star)](https://github.com/LiAutoAD/DIVE)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://liautoad.github.io/DIVE/)

+ **Unleashing Generalization of End-to-End Autonomous Driving with   Controllable Long Video Generation** (3 Jun 2024)<details><summary>Enhui Ma, Lijun Zhou, Tao Tang, et al.</summary>
Enhui Ma, Lijun Zhou, Tao Tang, Zhan Zhang, Dong Han, Junpeng Jiang, Kun Zhan, Peng Jia, Xianpeng Lang, Haiyang Sun, Di Lin, Kaicheng Yu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01349)
[![Code](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Star)](https://github.com/westlake-autolab/Delphi)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://westlake-autolab.github.io/delphi.github.io/)

+ **LLM-grounded Video Diffusion Models** (29 Sep 2023)<details><summary>Long Lian, Baifeng Shi, Adam Yala, et al.</summary>
Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17444)
[![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedVideoDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-video-diffusion.github.io)

+ **DriveDreamer: Towards Real-world-driven World Models for Autonomous   Driving** (18 Sep 2023)<details><summary>Xiaofeng Wang, Zheng Zhu, Guan Huang, et al.</summary>
Xiaofeng Wang, Zheng Zhu, Guan Huang, Xinze Chen, Jiagang Zhu, Jiwen Lu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.09777)
[![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/DriveDreamer)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://drivedreamer.github.io)

+ **Multi-object Video Generation from Single Frame Layouts** (06 May 2023)<details><summary>Yang Wu, Zhibin Liu, Hefeng Wu, et al.</summary>
Yang Wu, Zhibin Liu, Hefeng Wu, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03983)


### ✏️ Sketch Control

+ **LayerAnimate: Layer-level Control for Animation** (22 Mar 2025)<details><summary>Yuxue Yang, Lue Fan, Zuzeng Lin, et al.</summary>
Feng Wang, Zhaoxiang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08295)
[![citation](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2F4f8e95b78dab0cf5021667beef90eb80849b77a3%3Ffields%3DcitationCount&query=citationCount&label=citation&color=blue)](https://www.semanticscholar.org/paper/4f8e95b78dab0cf5021667beef90eb80849b77a3)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layeranimate.github.io/)
[![Code](https://img.shields.io/github/stars/IamCreateAI/LayerAnimate.svg?style=social&label=Star)](https://github.com/IamCreateAI/LayerAnimate)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/IamCreateAI/LayerAnimate)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** (13 Mar 2025)<details><summary>[ICLR 2025] Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>
Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
[![citation](https://img.shields.io/badge/citation-82-blue.svg?paper=3fc6184c72fd55b67409ef87493c333f15a33180)](https://www.semanticscholar.org/paper/3fc6184c72fd55b67409ef87493c333f15a33180)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/)
[![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/hehao13/CameraCtrl-svd)


+ **VidSketch: Hand-drawn Sketch-Driven Video Generation with Diffusion Control** (17 Feb 2025)<details><summary>Lifan Jiang, Shuang Chen, Boxi Wu, et al.</summary>
Xiaotong Guan, Jiahui Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01101)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=760f115fb3cb45de0ee8353c44c934b50af4c146)](https://www.semanticscholar.org/paper/760f115fb3cb45de0ee8353c44c934b50af4c146)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://csfufu.github.io/vid_sketch/)
[![Code](https://img.shields.io/github/stars/CSfufu/VidSketch.svg?style=social&label=Star)](https://github.com/CSfufu/VidSketch)

+ **AniDoc: Animation Creation Made Easier** (30 Jan 2025)<details><summary>[CVPR 2025] Yihao Meng, Hao Ouyang, Hanlin Wang, et al.</summary>
Qiuyu Wang, Wen Wang, Ka Leong Cheng, Zhiheng Liu, Yujun Shen, Huamin Qu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14173)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=95c7b164bc149215b62adb974762e20eb637d46f)](https://www.semanticscholar.org/paper/95c7b164bc149215b62adb974762e20eb637d46f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yihao-meng.github.io/AniDoc_demo/)
[![Code](https://img.shields.io/github/stars/ant-research/AniDoc.svg?style=social&label=Star)](https://github.com/ant-research/AniDoc)

+ **Open-Sora Plan: Open-Source Large Video Generation Model** (28 Nov 2024)<details><summary>Bin Lin, Yunyang Ge, Xinhua Cheng, et al.</summary>
Zongjian Li, Bin Zhu, Shaodong Wang, Xianyi He, Yang Ye, Shenghai Yuan, Liuhan Chen, Tanghui Jia, Junwu Zhang, Zhenyu Tang, Yatian Pang, Bin She, Cen Yan, Zhiheng Hu, Xiaoyi Dong, Lin Chen, Zhang Pan, Xing Zhou, Shaoling Dong, Yonghong Tian, Li Yuan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00131)
[![citation](https://img.shields.io/badge/citation-37-blue.svg?paper=ae588b682150047b5f8adc3d73fa09a9fdf17edb)](https://www.semanticscholar.org/paper/ae588b682150047b5f8adc3d73fa09a9fdf17edb)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)

+ **ToonCrafter: Generative Cartoon Interpolation** (19 Nov 2024)<details><summary>[ACM TOG] Jinbo Xing, Hanyuan Liu, Menghan Xia, et al.</summary>
Yong Zhang, Xintao Wang, Ying Shan, Tien-Tsin Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3687761)
[![citation](https://img.shields.io/badge/citation-23-blue.svg?paper=bf906c89602669a7d5bff06e3363b50c258b1d38)](https://www.semanticscholar.org/paper/bf906c89602669a7d5bff06e3363b50c258b1d38)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/ToonCrafter/)
[![Code](https://img.shields.io/github/stars/Doubiiu/ToonCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/ToonCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Doubiiu/tooncrafter)

+ **MagicStick: Controllable Video Editing via Control Handle Transformations** (18 Nov 2024)<details><summary>[WACV 2025] Yue Ma, Xiaodong Cun, Sen Liang, et al.</summary>
Jinbo Xing, Yingqing He, Chenyang Qi, Siran Chen, Qifeng Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=0b05282a316c56ac6e247d8bc78ac4dfa91c1d20)](https://www.semanticscholar.org/paper/0b05282a316c56ac6e247d8bc78ac4dfa91c1d20)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-stick-edit.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourHandle.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourHandle)


+ **MotionClone: Training-Free Motion Cloning for Controllable Video Generation** (22 Oct 2024)<details><summary>Pengyang Ling, Jiazi Bu, Pan Zhang, et al.</summary>
Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian Chen, Jiaqi Wang, Yi Jin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=e872ad446a3c6986feea7bd5cbd5b5754c068ab6)](https://www.semanticscholar.org/paper/e872ad446a3c6986feea7bd5cbd5b5754c068ab6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bujiazi.github.io/motionclone.github.io/)
[![Code](https://img.shields.io/github/stars/LPengYang/MotionClone.svg?style=social&label=Star)](https://github.com/LPengYang/MotionClone)

+ **LVCD: Reference-based Lineart Video Colorization with Diffusion Models** (19 Sep 2024)<details><summary>[ACM TOG and SIGGRAPH Asia 2024] Zhitong Huang, Mohan Zhang, Jing Liao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12960)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=97705d8c14345882683edefc367e830f94b3415e)](https://www.semanticscholar.org/paper/97705d8c14345882683edefc367e830f94b3415e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://luckyhzt.github.io/lvcd)
[![Code](https://img.shields.io/github/stars/luckyhzt/LVCD.svg?style=social&label=Star)](https://github.com/luckyhzt/LVCD)

+ **EasyControl: Transfer ControlNet to Video Diffusion for Controllable Generation and Interpolation** (16 Sep 2024)<details><summary>Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary>
Haoyu Zhao, Yuanfan Guo, Jianhua Han, Hang Xu, Xiaodan Liang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13005)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=a0a6a4ac75dcb5aa25e662a91361490836b0fd1c)](https://www.semanticscholar.org/paper/a0a6a4ac75dcb5aa25e662a91361490836b0fd1c)



+ **Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model** (24 May 2024)<details><summary>[ICLR 2025] Han Lin, Jaemin Cho, Abhay Zala, et al.</summary>
Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.09967)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=bcbef7546696cd2d102b8b440702614876dda5aa)](https://www.semanticscholar.org/paper/bcbef7546696cd2d102b8b440702614876dda5aa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ctrl-adapter.github.io/)
[![Code](https://img.shields.io/github/stars/HL-hanlin/Ctrl-Adapter.svg?style=social&label=Star)](https://github.com/HL-hanlin/Ctrl-Adapter)



+ **A Recipe for Scaling up Text-to-Video Generation with Text-free Videos** (25 Dec 2023)<details><summary>[CVPR 2024] Xiang Wang, Shiwei Zhang, Hangjie Yuan, et al.</summary>
Zhiwu Qing, Biao Gong, Yingya Zhang, Yujun Shen, Changxin Gao, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05845)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=a40e68121e7887fc49e3e9b35f8acc7ce7dc9c89)](https://www.semanticscholar.org/paper/a40e68121e7887fc49e3e9b35f8acc7ce7dc9c89)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tf-t2v.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)




+ **VideoLCM: Video Latent Consistency Model** (14 Dec 2023)<details><summary>Xiang Wang, Shiwei Zhang, Han Zhang,  et al.</summary>
Yu Liu, Yingya Zhang, Changxin Gao, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09109)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=e97b37c3d4c73912e19c5d2fc664ee2fb7a55c46)](https://www.semanticscholar.org/paper/e97b37c3d4c73912e19c5d2fc664ee2fb7a55c46)



+ **SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models** (28 Nov 2023)<details><summary>Yuwei Guo, Ceyuan Yang, Anyi Rao, et al.</summary>
Maneesh Agrawala, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
[![citation](https://img.shields.io/badge/citation-89-blue.svg?paper=40626a059bcd8d3e7f364b410f831b9baf997b0c)](https://www.semanticscholar.org/paper/40626a059bcd8d3e7f364b410f831b9baf997b0c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoyww.github.io/projects/SparseCtrl/)
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl.svg?style=social&label=Star)](https://github.com/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl)

+ **Make Pixels Dance: High-Dynamic Video Generation** (18 Nov 2023)<details><summary>[CVPR 2024] Yan Zeng, Guoqiang Wei, Jiani Zheng, et al.</summary>
Jiaxin Zou, Yang Wei, Yuchen Zhang, Hang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10982)
[![citation](https://img.shields.io/badge/citation-80-blue.svg?paper=8467c119251ea48204586d1c3c67aa8fb781f7c4)](https://www.semanticscholar.org/paper/8467c119251ea48204586d1c3c67aa8fb781f7c4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://arxiv.org/abs/2311.10982)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://makepixelsdance.github.io/demo.html)

+ **TaleCrafter: Interactive Story Visualization with Multiple Characters** (30 May 2023)<details><summary>[SIGGRAPH Asia 2023] Yuan Gong, Youxin Pang, Xiaodong Cun, et al.</summary>
Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247)
[![citation](https://img.shields.io/badge/citation-39-blue.svg?paper=32fad3ebb40bc9e827ad8ebb250dfabc5006a17a)](https://www.semanticscholar.org/paper/32fad3ebb40bc9e827ad8ebb250dfabc5006a17a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/TaleCrafter/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/TaleCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/TaleCrafter)

+ **Sketching the Future(STF): Applying Conditional Control Techniques to Text-to-Video Models** (10 May 2023)<details><summary>Rohan Dhesikan, Vignesh Rajmohan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05845)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=1d66f30782a13c1d775c690e0bc329324f188ced)](https://www.semanticscholar.org/paper/1d66f30782a13c1d775c690e0bc329324f188ced)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sketchingthefuture.github.io/)
[![Code](https://img.shields.io/github/stars/rohandkn/skribble2vid.svg?style=social&label=Star)](https://github.com/rohandkn/skribble2vid)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://docs.google.com/forms/d/e/1FAIpQLSd9EGien53IkxOlbPkUx9n9ANu2N_FG6ySJaZASr_A1VCdxUQ/viewform?usp=sf_link)
### 🤲 Language-Gesture Controlled

## 🔸 Multi Control/I2V

### 🖼️ + 🛤️ Image + Traj 
+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025) <details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531)
[![Code](https://img.shields.io/github/stars/tandaily/Awesome-Relighting.svg?style=social&label=Star)](https://github.com/tandaily/Awesome-Relighting)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VidCRAFT3/)

+ **LeviTor: 3D Trajectory Oriented Image-to-Video Synthesis** (28 Mar 2025)<details><summary>Hanlin Wang, Hao Ouyang, Qiuyu Wang, et al.</summary>Wen Wang, Ka Leong Cheng, Qifeng Chen, Yujun Shen, Limin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15214)
[![Code](https://img.shields.io/github/stars/ant-research/LeviTor.svg?style=social&label=Star)](https://github.com/ant-research/LeviTor)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ppetrichor.github.io/levitor.github.io/)

+ **LayerAnimate: Layer-level Control for Animation** (22 Mar 2025)<details><summary>Yuxue Yang, Lue Fan, Zuzeng Lin, et al.</summary>
Feng Wang, Zhaoxiang Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08295)
[![Code](https://img.shields.io/github/stars/IamCreateAI/LayerAnimate.svg?style=social&label=Star)](https://github.com/IamCreateAI/LayerAnimate)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layeranimate.github.io/)

+ **Tora: Trajectory-oriented Diffusion Transformer for Video Generation** (14 Mar 2025)<details><summary>Zhenghao Zhang, Junchao Liao, Menghao Li, et al.</summary>ZuoZhuo Dai, Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)
[![Code](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social&label=Star)](https://github.com/alibaba/Tora)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-videoai.github.io/tora_video/)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (10 Mar 2025)  <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05020)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/index.html)

+ **C-Drag: Chain-of-Thought Driven Motion Controller for Video Generation** (27 Feb 2025)<details><summary>Yuhao Li, Mirana Claire Angel, Salman Khan, et al.</summary>Yu Zhu, Jinqiu Sun, Yanning Zhang, Fahad Shahbaz Khan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.19868)
[![Code](https://img.shields.io/github/stars/WesLee88524/C-Drag-Official-Repo.svg?style=social&label=Star)](https://github.com/WesLee88524/C-Drag-Official-Repo)


+ **SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation** (25 Feb 2025)<details><summary>Koichi Namekata, Sherwin Bahmani, Ziyi Wu, et al.</summary>Yash Kant, Igor Gilitschenski, David B. Lindell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2411.04989)
[![Code](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social&label=Star)](https://github.com/Kmcode1/SG-I2V)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kmcode1.github.io/Projects/SG-I2V/)

+ **MotionBridge: Dynamic Video Inbetweening with Flexible Controls** (7 Jan 2025)<details><summary>Maham Tanveer, Yang Zhou, Simon Niklaus, et al.</summary>Ali Mahdavi Amiri, Hao Zhang, Krishna Kumar Singh, Nanxuan Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.13190v1)
[![Code](https://img.shields.io/github/stars/lwq20020127/OmniDrag.svg?style=social&label=Star)](https://github.com/lwq20020127/OmniDrag)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motionbridge.github.io/)

+ **TrackGo: A Flexible and Efficient Method for Controllable Video Generation** (5 Jan 2025)<details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11475)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhtjtcz.github.io/TrackGo-Page/)

+ **OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation** (12 Dec 2024)<details><summary>Weiqi Li, Shijie Zhao, Chong Mou, et al.</summary>Xuhan Sheng, Zhenyu Zhang, Qian Wang, Junlin Li, Li Zhang, Jian Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09623)
[![Code](https://img.shields.io/github/stars/lwq20020127/OmniDrag.svg?style=social&label=Star)](https://github.com/lwq20020127/OmniDrag)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lwq20020127.github.io/OmniDrag/)

+ **ObjCtrl-2.5D: Training-free Object Control with Camera Poses** (10 Dec 2024)<details><summary>Zhouxia Wang, Yushi Lan, Shangchen Zhou, Chen Change Loy, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07721)
[![Code](https://img.shields.io/github/stars/wzhouxiff/ObjCtrl-2.5D.svg?style=social&label=Star)](https://github.com/wzhouxiff/ObjCtrl-2.5D)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wzhouxiff.github.io/projects/ObjCtrl-2.5D/)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories** (03 Dec 2024)<details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1)
[![Code](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** (30 Nov 2024)<details><summary>Wanquan Feng, Tianhao Qi, Jiawei Liu, et al.</summary>Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)
+ **InTraGen: Trajectory-controlled Video Generation for Object Interactions** (25 Nov 2024)<details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16804)
[![Code](https://img.shields.io/github/stars/insait-institute/InTraGen.svg?style=social&label=Star)](https://github.com/insait-institute/InTraGen)

+ **DragEntity: Trajectory Guided Video Generation using Entity and Positional Relationships** (14 Oct 2024) <details><summary>Zhang Wan, Sheng Tang, Jiawei Wei</summary></details>
[![Paper](https://img.shields.io/badge/ACM-b31b1b.svg)](https://arxiv.org/abs/2410.10751)
[![code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md)


+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (11 Jul 2024) <details><summary>Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>Yong Zhang, Ying Shan, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
[![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://myniuuu.github.io/MOFA_Video/)

+ **Image Conductor: Precision Control for Interactive Video Synthesis** (21 Jun 2024)<details><summary>Yaowei Li, Xintao Wang, Zhaoyang Zhang, et al.</summary>Zhouxia Wang, Ziyang Yuan, Liangbin Xie, Yuexian Zou, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15339)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/liyaowei-stu/ImageConductor)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://liyaowei-stu.github.io/project/ImageConductor/)

+ **ReVideo: Remake a Video with Motion and Content** (22 May 2024)<details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>
[![Paper](https://img.shields.io/badge/NeurIPS-b31b1b.svg)](https://proceedings.neurips.cc)
[![Code](https://img.shields.io/github/stars/MC-E/ReVideo.svg?style=social&label=Star)](https://github.com/MC-E/ReVideo)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mc-e.github.io/project/ReVideo/)

+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (19 Apr 2024) <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2312.07509)
[![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

+ **Draganything: Motion control for anything using entity representation** (15 Mar 2024)<details><summary>Weijia Wu, Zhuang Li, Yuchao Gu, et al.</summary>Rui Zhao, Yefei He, David Junhao Zhang, Mike Zheng Shou, Yan Li, Tingting Gao, Di Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
[![Code](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://weijiawu.github.io/draganything_page/)

+ **Boximator: Generating Rich and Controllable Motions for Video Synthesis** (2 Feb 2024) <details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01566)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boximator.github.io/)

+ **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (31 Jan 2024)<details><summary>Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)
[![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cpii.hk/inventions/motion-i2v-consistent-and-controllable-image-to-video-generation-with-explicit-motion-modeling/)

+ **DragNuwa(Image+text_Traj)** (16 Aug 2023) <details><summary>Shengming Yin, Chenfei Wu, Jian Liang, et al.</summary>Jie Shi, Houqiang Li, Gong Ming, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08089)
[![Code](https://img.shields.io/github/stars/ProjectNUWA/DragNUWA.svg?style=social&label=Star)](https://github.com/ProjectNUWA/DragNUWA)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aiartweekly.com/tools/dragnuwa-fine-grained-control-in-video-generation-by-integrating-text-image-and-trajectory)

+ **MCDiff Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023) <details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tsaishien-chen.github.io/MCDiff/)


### 🖼️ + 📸 Image + Camera
+ **Aether: Geometric-Aware Unified World Modeling** (18 Mar 2025)
   <details><summary>Aether Team, et al.</summary>  
        Haoyi Zhu, Yifan Wang, Jianjun Zhou, Wenzheng Chang, Yang Zhou, Zizun Li, Junyi Chen, Chunhua Shen, Jiangmiao Pang, Tong He </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18945)
   [![GitHub](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Star)](https://github.com/OpenRobotLab/Aether)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aether-world.github.io/)
  
+ **GenDoP: Auto-regressive Camera Trajectory Generation as a Director of Photography** (10 Apr 2025) <details><summary>Mengchen Zhang, Tong Wu, Jing Tan, et al.</summary>Mengchen Zhang, Tong Wu, Jing Tan, Ziwei Liu, Gordon Wetzstein, Dahua Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.07083)
[![code](https://img.shields.io/github/stars/3DTopia/GenDoP.svg?style=social&label=Star)](https://github.com/3DTopia/GenDoP)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kszpxxzmc.github.io/GenDoP/)

+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025) <details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531)
[![code](https://img.shields.io/github/stars/tandaily/Awesome-Relighting.svg?style=social&label=Star)](https://github.com/tandaily/Awesome-Relighting)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deep-diver.github.io/ai-paper-reviewer/paper-reviews/2411.19324/)

+ **Optical Flow Meets Video Diffusion Model for Enhanced Camera-Controlled Video Synthesis** (25 Mar 2025) <details><summary>Wonjoon Jin, Qi Dai, Chong Luo, et al.</summary>Seung-Hwan Baek, Sunghyun Cho, POSTECH, Microsoft Research Asia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08244)
[![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cvpr.thecvf.com/virtual/2025/poster/33323)

+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models** (13 Mar 2025) <details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary>Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592)
[![code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/Projects-CameraCtrl-II/)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** (13 Mar 2025) <details><summary>Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
[![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/)

+ **I2V3D: Controllable Image-to-Video Generation with 3D Guidance** (12 Mar 2025)<details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.09733)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://arxiv.org/html/2503.09733v1)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (10 Mar 2025) <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05020)
[![Code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control/blob/main/README.md)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/)

+ **GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control** (5 Mar 2025) <details><summary>Xuanchi Ren, Tianchang Shen, Jiahui Huang, et al.</summary>Huan Ling, Yifan Lu, Merlin Nimier-David, Thomas Müller, Alexander Keller, Sanja Fidler, Jun Gao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.03751)
[![Code](https://img.shields.io/github/stars/nv-tlabs/GEN3C.svg?style=social&label=Star)](https://github.com/nv-tlabs/GEN3C)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aiartweekly.com/tools/gen3c-3d-informed-world-consistent-video-generation-with-precise-camera-control)

+ **I2VCONTROL-CAMERA: Precise Video Camera Control with Adjustable Motion Strength** (28 Feb 2025)<details><summary>Wanquan Feng, Jiawei Liu, Pengqi Tu, et al.</summary>Tianhao Qi, Mingzhen Sun, Tianxiang Ma, Songtao Zhao, Siyu Zhou, Qian He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.06525)
[![code](https://img.shields.io/github/stars/WanquanF/I2VControl-Camera.svg?style=social&label=Star)](https://github.com/WanquanF/I2VControl-Camera)


+ **Training-free Camera Control for Video Generation** (25 Feb 2025) <details><summary>Chen Hou, Zhibo Chen, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.10126)
[![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://qcy22.github.io/2024/08/02/paper-reading/paper-reading5/)

+ **RealCam-I2V: Real-World Image-to-Video Generation with Interactive Complex Camera Control** (14 Feb 2025) <details><summary>Teng Li, Guangcong Zheng, Rui Jiang, et al.</summary>Shuigenzhan, Tao Wu, Yehao Lu, Yining Lin, Xi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10059)
[![Code](https://img.shields.io/github/stars/ZGCTroy/RealCam-I2V.svg?style=social&label=Star)](https://github.com/ZGCTroy/RealCam-I2V)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zgctroy.github.io/RealCam-I2V/)


+ **EgoSim: Egocentric Exploration in Virtual Worlds with Multi-modal Conditioning** (23 Jan 2025) <details><summary>Wei Yu, Songheng Yin, Steve Easterbrook, Animesh Garg, et al.</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=zAyS5aRKV8)
[![code](https://img.shields.io/github/stars/EgocentricVision/EgocentricVision.svg?style=social&label=Star)](https://github.com/EgocentricVision/EgocentricVision)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://egosim.github.io/EgoSim/)

+ **CamI2V: Camera-Controlled Image-to-Video Diffusion Model** (4 Dec 2024)<details><summary>Guangcong Zheng, Teng Li, Rui Jiang, et al.</summary>Yehao Lu, Tao Wu, Xi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15957)
[![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zgctroy.github.io/CamI2V/?ref=aiartweekly)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories(frame+track+text)** (03 Dec 2024)<details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1)
[![code](https://img.shields.io/github/stars/HyelinNAM/MotionPrompt.svg?style=social&label=Star)](https://github.com/HyelinNAM/MotionPrompt)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** (30 Nov 2024)<details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)

+ **Trajectory Attention: Enhancing Video Generation with Fine-Grained Motion Control** (28 Nov 2024)<details><summary>Zeqi Xiao, Wenqi Ouyang, Yifan Zhou, et al.</summary>Shuai Yang, Lei Yang, Jianlou Si, Xingang Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19324)
[![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deep-diver.github.io/ai-paper-reviewer/paper-reviews/2411.19324/)



+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (12 Nov 2024) <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)
[![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

+ **DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion** (7 Nov 2024)<details><summary>Wenqiang Sun, Shuo Chen, Fangfu Liu, et al.</summary>Zilong Chen, Yueqi Duan, Jun Zhang, Yikai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04928)
[![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Star)](https://github.com/wenqsun/DimensionX)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenshuo20.github.io/DimensionX/)

+ **CamCo: Camera-Controllable 3D-Consistent Image-to-Video Generation** (4 Jun 2024)<details><summary>Dejia Xu, Weili Nie, Chao Liu, et al.</summary>Sifei Liu, Jan Kautz, Zhangyang Wang, Arash Vahdat</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ir1d.github.io/CamCo/)
[![code](https://img.shields.io/github/stars/wangqiang9/Awesome-Controllable-Video-Diffusion.svg?style=social&label=Star)](https://github.com/wangqiang9/Awesome-Controllable-Video-Diffusion)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ir1d.github.io/CamCo/)



### 🛤️ + 📸 Traj + Camera
+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025)<details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531) 
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VidCRAFT3/)
+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (10 Mar 2025)<details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05020)
[![Project Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/)
[![code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)
+ **MotionCtrl: A Unified and Flexible Motion Controller for Video Generation** (16 Jul 2024)<details><summary>Zhouxia Wang, Ziyang Yuan, Xintao Wang, et al.</summary>Zhouxia Wang, Ziyang Yuan, Xintao Wang, Tianshui Chen, Menghan Xia, Ping Luo, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)[![Project Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wzhouxiff.github.io/projects/MotionCtrl/)[![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/TencentARC/MotionCtrl)




### 🖼️ + 🔊 Image + Audio

+ **Audio-visual Controlled Video Diffusion with Masked Selective State Spaces Modeling for Natural Talking Head Generation** (4 Apr 2025)<details><summary>Fa-Ting Hong, Zunnan Xu, Zixiang Zhou, et al.</summary>
Jun Zhou, Xiu Li, Qin Lin, Qinglin Lu, Dan Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02542)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=5152b487416195caa6493efba96cbdbb5b91fbf7)](https://www.semanticscholar.org/paper/5152b487416195caa6493efba96cbdbb5b91fbf7)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://harlanhong.github.io/publications/actalker/index.html)
[![Code](https://img.shields.io/github/stars/harlanhong/ACTalker.svg?style=social&label=Star)](https://github.com/harlanhong/ACTalker)



+ **ChatAnyone: Stylized Real-time Portrait Video Generation with Hierarchical Motion Diffusion Model** (27 Mar 2025)<details><summary>Jinwei Qi, Chaonan Ji, Sheng Xu, et al.</summary>
Peng Zhang, Bang Zhang, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21144)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=9045629ae00382f73ffd3a8c4772aa4858260c27)](https://www.semanticscholar.org/paper/9045629ae00382f73ffd3a8c4772aa4858260c27)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/chat-anyone/)

+ **MuseTalk: Real-Time High-Fidelity Video Dubbing via Spatio-Temporal Sampling** (26 Mar 2025)<details><summary>Yue Zhang, Zhizhou Zhong, Minhao Liu, et al.</summary>Zhaokang Chen, Bin Wu, Yubin Zeng, Chao Zhan, Junxin Huang, Yingjie He, Wenjiang Zhou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10122)
  [![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=31f1293316741d43903e4b8580ba5356f3ba262b)](https://www.semanticscholar.org/paper/31f1293316741d43903e4b8580ba5356f3ba262b)
  [![Code](https://img.shields.io/github/stars/TMElyralab/MuseTalk.svg?style=social&label=Star)](https://github.com/TMElyralab/MuseTalk)

+ **Cafe-Talk: Generating 3D Talking Face Animation with Multimodal Coarse- and Fine-grained Control** (14 Mar 2025)<details><summary>[ICLR 2025] Hejia Chen, Haoxian Zhang, Shoulong Zhang, et al.</summary>
Xiaoqiang Liu, Sisi Zhuang, Yuan Zhang, Pengfei Wan, Di Zhang, Shuai Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14517)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=6f7f74bb2d4ab7decbeec23b13ac814de41c86fb)](https://www.semanticscholar.org/paper/6f7f74bb2d4ab7decbeec23b13ac814de41c86fb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://harryxd2018.github.io/cafe-talk/)


+ **Towards High-fidelity 3D Talking Avatar with Personalized Dynamic Texture** (1 Mar 2025)<details><summary>[CVPR 2025] Xuanchen Li, Jianyu Wang, Yuhao Cheng, et al.</summary>
Yikun Zeng, Xingyu Ren, Wenhan Zhu, Weiming Zhao, Yichao Yan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00495)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=0b76dff851ca7196ca68f05f246332f16a74cf30)](https://www.semanticscholar.org/paper/0b76dff851ca7196ca68f05f246332f16a74cf30)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xuanchenli.github.io/TexTalk/)
[![Code](https://img.shields.io/github/stars/XuanchenLi/TexTalk.svg?style=social&label=Star)](https://github.com/XuanchenLi/TexTalk)


+ **SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion** (17 Feb 2025)<details><summary>Junxian Ma, Shiwen Wang, Jian Yang, et al.</summary>
Junyi Hu, Jian Liang, Guosheng Lin, Jingbo chen, Kai Li, Yu Meng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11515)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=601d15cdf802fb45d83e8c88ef0ae8acd261dc35)](https://www.semanticscholar.org/paper/601d15cdf802fb45d83e8c88ef0ae8acd261dc35)

+ **Long-Term TalkingFace Generation via Motion-Prior Conditional Diffusion Model** (13 Feb 2025)<details><summary>Fei Shen, Cong Wang, Junyao Gao, et al.</summary>
Qin Guo, Jisheng Dang, Jinhui Tang, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.09533)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=ddddfcaf88c6b0ea24316cfce2d6838d8d19e563)](https://www.semanticscholar.org/paper/ddddfcaf88c6b0ea24316cfce2d6838d8d19e563)



+ **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models** (13 Feb 2025)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
Zerong Zheng, Chao Liang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)
     [![citation](https://img.shields.io/badge/citation-8-blue.svg?paper=e8fd310e67c537fd2fcab36a823827e41c579ab4)](https://www.semanticscholar.org/paper/e8fd310e67c537fd2fcab36a823827e41c579ab4)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://omnihuman-lab.github.io/)


+ **CyberHost: A One-stage Diffusion Framework for Audio-driven Talking Body Generation** (23 Jan 2025)<details><summary>[ICLR 2025] Gaojie Lin, Jianwen Jiang, Chao Liang, et al.</summary>
Tianyun Zhong, Jiaqi Yang, Yanbo Zheng</details>

  [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=vaEPihQsAA)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cyberhost.github.io/)


+ **Float: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait** (4 Dec 2024)<details><summary>Taekyung Ki, Dongchan Min, Gyeongsu Chae</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01064)
  [![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=bdf3375410d55056521b64b190eddfbcbf45c9d7)](https://www.semanticscholar.org/paper/bdf3375410d55056521b64b190eddfbcbf45c9d7)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deepbrainai-research.github.io/float/)
  [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/deepbrainai-research/float)


+ **SVP: Style-Enhanced Vivid Portrait Talking Head Diffusion Model** (28 Nov 2024)<details><summary>Weipeng Tan, Chuming Lin, Chengming Xu, et al.</summary>
Xiaozhong Ji, Junwei Zhu, Chengjie Wang, Yunsheng Wu, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03270)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=813fe44fb99294cf87174678302cde891af9098b)](https://www.semanticscholar.org/paper/813fe44fb99294cf87174678302cde891af9098b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://svportrait.github.io/)

+ **EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation** (15 Nov 2024)<details><summary>[CVPR 2025] Rang Meng, Xingyu Zhang, Yuming Li, et al.</summary>
Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=5f2c046a4da302e3225afb378411aabd7d89c1cc)](https://www.semanticscholar.org/paper/5f2c046a4da302e3225afb378411aabd7d89c1cc)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://antgroup.github.io/ai/echomimic_v2/)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic_v2.svg?style=social&label=Star)](https://github.com/antgroup/echomimic_v2)


+ **VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time** (31 Oct 2024)<details><summary>[NeurIPS 2024] Sicheng Xu, Guojun Chen, Yu-Xiao Guo, et al.</summary>
Jiaolong Yang, Chong Li, Zhenyu Zang, Yizhong Zhang, Xin Tong, Baining Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10667)
   [![citation](https://img.shields.io/badge/citation-70-blue.svg?paper=292bcd3e8d580413a74510bfacf1bb88c4fb9f61)](https://www.semanticscholar.org/paper/292bcd3e8d580413a74510bfacf1bb88c4fb9f61)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.microsoft.com/en-us/research/project/vasa-1/)



+ **MegActor-Σ: Unlocking Flexible Mixed-Modal Control in Portrait Animation with Diffusion Transformer** (27 Aug 2024)<details><summary>[AAAI 2025] Shurong Yang, Huadong Li, Juhao Wu, et al.</summary>
Minhao Jing, Linze Li, Renhe Ji, Jiajun Liang, Haoqiang Fan, Jin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14975)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=55139479ae7f68e7e3febda844331dd907990faa)](https://www.semanticscholar.org/paper/55139479ae7f68e7e3febda844331dd907990faa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/megvii-research/MegActor.svg?style=social&label=Star)](https://github.com/megvii-research/MegActor)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://f4c5-58-240-80-18.ngrok-free.app/)


+ **MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls** (25 Aug 2024)<details><summary>Yuxuan Bian, Ailing Zeng, Xuan Ju, et al.</summary>Xian Liu, Zhaoyang Zhang, Wei Liu, Qiang Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21136)
  [![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=a74e0cd895bd43f7d9e4d548c76712d0dc1b5e9d)](https://www.semanticscholar.org/paper/a74e0cd895bd43f7d9e4d548c76712d0dc1b5e9d)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cure-lab.github.io/MotionCraft/)
  [![Code](https://img.shields.io/github/stars/cure-lab/MotionCraft.svg?style=social&label=Star)](https://github.com/cure-lab/MotionCraft)

+ **Dreamtalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models** (10 Aug 2024)<details><summary>Yifeng Ma, Shiwei Zhang, Jiayu Wang, et al.</summary>Xiang Wang, Yingya Zhang, Zhidong Deng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09767)
  [![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=64d79ce32ec667f54bcbf7e761a75dd42c6240b2)](https://www.semanticscholar.org/paper/64d79ce32ec667f54bcbf7e761a75dd42c6240b2)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamtalk-project.github.io/)
  [![Code](https://img.shields.io/github/stars/ali-vilab/dreamtalk.svg?style=social&label=Star)](https://github.com/ali-vilab/dreamtalk)
+ **EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions** (12 Jul 2024)<details><summary>[AAAI 2025] Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, et al.</summary>
Yuming Li, Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)
[![citation](https://img.shields.io/badge/citation-34-blue.svg?paper=d92c15b21777bd81b95622506e406e24a4de4bdb)](https://www.semanticscholar.org/paper/d92c15b21777bd81b95622506e406e24a4de4bdb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic.svg?style=social&label=Star)](https://github.com/antgroup/echomimic)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BadToBest/EchoMimic)


+ **Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation** (16 Jun 2024)<details><summary>Mingwang Xu, Hui Li, Qingkun Su, et al.</summary>Hanlin Shang, Liwei Zhang, Ce Liu, Jingdong Wang, Yao Yao, Siyu Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08801)
[![citation](https://img.shields.io/badge/citation-49-blue.svg?paper=17556ab7cd1bf0f6d385de30bb71f421625519ef)](https://www.semanticscholar.org/paper/17556ab7cd1bf0f6d385de30bb71f421625519ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/hallo/#/)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/hallo.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/hallo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/tts-hallo-talking-portrait)

+ **V-Express: Conditional Dropout for Progressive Training of Portrait Video Generation** (4 Jun 2024)<details><summary>Cong Wang, Kuan Tian, Jun Zhang, et al.</summary>
Yonghang Guan, Feng Luo, Fei Shen, Zhiwei Jiang, Qing Gu, Xiao Han, Wei Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02511)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=2c710db17e7c651b4653d9872668cd6ff7baf69f)](https://www.semanticscholar.org/paper/2c710db17e7c651b4653d9872668cd6ff7baf69f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tenvence.github.io/p/v-express/)
[![Code](https://img.shields.io/github/stars/tencent-ailab/V-Express.svg?style=social&label=Star)](https://github.com/tencent-ailab/V-Express)
+ **InstructAvatar: Text-Guided Emotion and Motion Control for Avatar Generation** (24 May 2024)<details><summary>Yuchi Wang, Junliang Guo, Jianhong Bai, et al.</summary>
Runyi Yu, Tianyu He, Xu Tan, Xu Sun, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15758)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=bfed480ef00c8ed659283a111e5322f03b664520)](https://www.semanticscholar.org/paper/bfed480ef00c8ed659283a111e5322f03b664520)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wangyuchi369.github.io/InstructAvatar/)
+ **SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis** (28 Apr 2024)<details><summary>[CVPR 2024] Ziqiao Peng, Wentao Hu, Yue Shi, et al.</summary>Xiangyu Zhu, Xiaomei Zhang, Hao Zhao, Jun He, Hongyan Liu, Zhaoxin Fan</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17590)
   [![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=90bc388771469da88997b197bd010a5bba8ca960)](https://www.semanticscholar.org/paper/90bc388771469da88997b197bd010a5bba8ca960)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ziqiaopeng.github.io/synctalk/)
  [![Code](https://img.shields.io/github/stars/ZiqiaoPeng/SyncTalk.svg?style=social&label=Star)](https://github.com/ZiqiaoPeng/SyncTalk)
+ **EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis** (2 Apr 2024)<details><summary>Shuai Tan, Bin Ji, Mengxiao Bi, et al.</summary>
Ye Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01647)
[![citation](https://img.shields.io/badge/citation-21-blue.svg?paper=f9511d7409f72ecaa2634af02f4be3a8643c4037)](https://www.semanticscholar.org/paper/f9511d7409f72ecaa2634af02f4be3a8643c4037)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tanshuai0219.github.io/EDTalk/)
[![Code](https://img.shields.io/github/stars/tanshuai0219/EDTalk.svg?style=social&label=Star)](https://github.com/tanshuai0219/EDTalk)

+ **AniPortrait: Audio-Driven Synthesis of Photorealistic Portrait Animation** (26 Mar 2024)<details><summary>Huawei Wei, Zejun Yang, Zhisheng Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17694)
[![citation](https://img.shields.io/badge/citation-54-blue.svg?paper=f81cb2475408ebf7b39268aff1cffd8c791ac5b2)](https://www.semanticscholar.org/paper/f81cb2475408ebf7b39268aff1cffd8c791ac5b2)
[![Code](https://img.shields.io/github/stars/Zejun-Yang/AniPortrait.svg?style=social&label=Star)](https://github.com/Zejun-Yang/AniPortrait)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/ZJYang/AniPortrait_official)


+ **EMO: Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions** (27 Feb 2024)<details><summary>[ECCV 2024] Linrui Tian, Qi Wang, Bang Zhang, et al.</summary>
Liefeng Bo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17485)
  [![citation](https://img.shields.io/badge/citation-92-blue.svg?paper=aac7c6a33dc0f71bd4853e41e205ad908d3b3d09)](https://www.semanticscholar.org/paper/aac7c6a33dc0f71bd4853e41e205ad908d3b3d09)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/EMO.svg?style=social&label=Star)](https://github.com/HumanAIGC/EMO)

+ **VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior** (7 Dec 2023)<details><summary>Xusen Sun, Longhao Zhang, Hao Zhu, et al.</summary>Peng Zhang, Bang Zhang, Xinya Ji, Kangneng Zhou, Daiheng Gao, Liefeng Bo, Xun Cao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.01841)
    [![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=e6983128cdba6a46c4e6efe834e76e6fc9fc75ee)](https://www.semanticscholar.org/paper/e6983128cdba6a46c4e6efe834e76e6fc9fc75ee)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/vivid-talk/)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/VividTalk.svg?style=social&label=Star)](https://github.com/HumanAIGC/VividTalk)



+ **Sadtalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation** (22 Nov 2022)<details><summary>[CVPR 2023] Wenxuan Zhang, Xiaodong Cun, Xuan Wang, et al.</summary>
Yong Zhang, Xi Shen, Yu Guo, Ying Shan, Fei Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12194)
    [![citation](https://img.shields.io/badge/citation-213-blue.svg?paper=a7019f9a2ecb9983b66456ae32978e2574625980)](https://www.semanticscholar.org/paper/a7019f9a2ecb9983b66456ae32978e2574625980)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sadtalker.github.io/)
  [![Code](https://img.shields.io/github/stars/OpenTalker/SadTalker.svg?style=social&label=Star)](https://github.com/OpenTalker/SadTalker)
   [![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/vinthony/SadTalker)


+ **MakeItTalk: Speaker-Aware Talking-Head Animation** (25 Feb 2021)<details><summary>[SIGGRAPH Asia 2020] Yang Zhou, Xintong Han, Eli Shechtman, et al.</summary>
Jose Echevarria, Evangelos Kalogerakis, Dingzeyu Li</details>
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2004.12992)
  [![citation](https://img.shields.io/badge/citation-401-blue.svg?paper=7a7c4e666e5dd8a489770643b72fd99cf708f7c1)](https://www.semanticscholar.org/paper/7a7c4e666e5dd8a489770643b72fd99cf708f7c1)
  [![Code](https://img.shields.io/github/stars/yzhou359/MakeItTalk.svg?style=social&label=Star)](https://github.com/yzhou359/MakeItTalk)





+ **A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild** (23 Aug 2020)<details><summary>[ACM MM 2020] K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, et al.</summary>
C V Jawahar</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2008.10010)
  [![citation](https://img.shields.io/badge/citation-726-blue.svg?paper=9c160a71d3265eedaf7645c39be073c966f10433)](https://www.semanticscholar.org/paper/9c160a71d3265eedaf7645c39be073c966f10433)
  [![Code](https://img.shields.io/github/stars/Rudrabha/Wav2Lip.svg?style=social&label=Star)](https://github.com/Rudrabha/Wav2Lip)



### 🎥 + 📸 Video + Camera
+ **ReCapture: Generative Video Camera Controls for User-Provided Videos using Masked Video Fine-Tuning** (11 Nov 2024)<details><summary>David Junhao Zhang, Roni Paiss, Shiran Zada, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.05003)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://generative-video-camera-controls.github.io/)
+ **Reangle-A-Video: 4D Video Generation as Video-to-Video Translation**<details><summary>Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://hyeonho99.github.io/reangle-a-video/)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyeonho99.github.io/reangle-a-video/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/HyeonHo99/Reangle-Video)
+ **Redirecting Camera Trajectory for Monocular Videos via Diffusion Models** (25 Mar 2025)<details><summary>Mark YU, Wenbo Hu, Jinbo Xing, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05638)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://trajectorycrafter.github.io/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/TrajectoryCrafter/TrajectoryCrafter)
+ **AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers**<details><summary>Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, et al.</summary></details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/ac3d/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)
+ **MotionDirector: Motion Customization of Text-to-Video Diffusion Models**<details><summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, et al.</summary></details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/MotionDirector/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)

### 🖼️ + 🌊 Image + Flow

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** (26 Nov 2024)
   <details><summary>Wanquan Feng, Tianhao Qi, et al.</summary>  
        Wanquan Feng, Tianhao Qi, Jiawei Liu, Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)

+ **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (29 Jan 2024)
   <details><summary>[SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, et al.</summary>  
        Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)
   [![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)



### 🖼️ + 🕺 Image + Pose
+ **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models** (3 Feb 2025)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
  Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://omnihuman-lab.github.io)

 + **AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation** (26 Nov 2024)<details><summary>Ziyi Xu, Ziyao Huang, Juan Cao, et al.</summary>
 Ziyi Xu, Ziyao Huang, Juan Cao, Yong Zhang, Xiaodong Cun, Qing Shuai, Yuchen Wang, Linchao Bao, Jintao Li, Fan Tang</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17383)
 [![Code](https://img.shields.io/github/stars/cangcz/AnchorCrafter.svg?style=social&label=Star)](https://github.com/cangcz/AnchorCrafter)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://cangcz.github.io/Anchor-Crafter/)

 + **StableAnimator: High-Quality Identity-Preserving Human Image Animation** (26 Nov 2024)<details><summary>[CVPR 2025] Shuyuan Tu, Zhen Xing, Xintong Han, et al.</summary>
 Shuyuan Tu, Zhen Xing, Xintong Han, Zhi-Qi Cheng, Qi Dai, Chong Luo, Zuxuan Wu</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17697)
 [![Code](https://img.shields.io/github/stars/Francis-Rings/StableAnimator.svg?style=social&label=Star)](https://github.com/Francis-Rings/StableAnimator)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://francis-rings.github.io/StableAnimator)

 + **AnimateAnywhere: Context-Controllable Human Video Generation with ID-Consistent One-shot Learning** (28 Oct 2024)<details><summary>[ACMMM 2024] Hengyuan Liu, Xiaodong Chen, Xinchen Liu, et al.</summary>
 Hengyuan Liu, Xiaodong Chen, Xinchen Liu, Xiaoyan Gu, Wu Liu</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3688865.3689477)

 + **TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models** (12 Jul 2024)<details><summary>Jeongho Kim, Min-Jung Kim, Junsoo Lee, et al.</summary>
 Jeongho Kim, Min-Jung Kim, Junsoo Lee, Jaegul Choo</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09012)
 [![Code](https://img.shields.io/github/stars/eccv2024tcan/TCAN.svg?style=social&label=Star)](https://github.com/eccv2024tcan/TCAN)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://eccv2024tcan.github.io)

 + **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance** (28 Jun 2024)<details><summary>Yuang Zhang, Jiaxi Gu, Li-Wen Wang, et al.</summary>
 Yuang Zhang, Jiaxi Gu, Li-Wen Wang, Han Wang, Junqi Cheng, Yuefeng Zhu, Fangyuan Zou</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680)
 [![Code](https://img.shields.io/github/stars/Tencent/MimicMotion.svg?style=social&label=Star)](https://github.com/Tencent/MimicMotion)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://tencent.github.io/MimicMotion/)

 + **Follow-Your-Pose v2: Multiple-Condition Guided Character Image Animation for Stable Pose Control** (05 Jun 2024)<details><summary>Jingyun Xue, Hongfa Wang, Qi Tian, et al.</summary>
 Jingyun Xue, Hongfa Wang, Qi Tian, Yue Ma, Andong Wang, Zhiyuan Zhao, Shaobo Min, Wenzhe Zhao, Kaihao Zhang, Heung-Yeung Shum, Wei Liu, Mengyang Liu, Wenhan Luo</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03035v3)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose-v2.github.io)

 + **UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation** (3 Jun 2024)<details><summary>Xiang Wang, Shiwei Zhang, Changxin Gao, et al.</summary>
 Xiang Wang, Shiwei Zhang, Changxin Gao, Jiayu Wang, Xiaoqiang Zhou, Yingya Zhang, Luxin Yan, Nong Sang</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188)
 [![Code](https://img.shields.io/github/stars/ali-vilab/UniAnimate.svg?style=social&label=Star)](https://github.com/ali-vilab/UniAnimate)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://unianimate.github.io)

 + **VividPose: Advancing Stable Video Diffusion for Realistic Human Image Animation** (28 May 2024)<details><summary>Qilin Wang, Zhengkai Jiang, Chengming Xu, et al.</summary>
 Qilin Wang, Zhengkai Jiang, Chengming Xu, Jiangning Zhang, Yabiao Wang, Xinyi Zhang, Yun Cao, Weijian Cao, Chengjie Wang, Yanwei Fu</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18156)
 [![Code](https://img.shields.io/github/stars/Kelu007/VividPose.svg?style=social&label=Star)](https://github.com/Kelu007/VividPose)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://kelu007.github.io/vivid-pose/)

 + **Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation** (26 May 2024)<details><summary>Jinlin Liu, Kai Yu, Mengyang Feng, et al.</summary>
 Jinlin Liu, Kai Yu, Mengyang Feng, Xiefan Guo, Miaomiao Cui</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16393v2)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://liujl09.github.io/humanvideo_movingbackground/)

 + **PoseCrafter: One-Shot Personalized Video Synthesis Following Flexible Pose Control** (23 May 2024)<details><summary>[ECCV 2024] Yong Zhong, Min Zhao, Zebin You, et al.</summary>
 Yong Zhong, Min Zhao, Zebin You, Xiaofeng Yu, Changwang Zhang, Chongxuan Li</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14582)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://ml-gsai.github.io/PoseCrafter-demo/)

 + **Zero-shot High-fidelity and Pose-controllable Character Animation** (21 Apr 2024)<details><summary>[IJCAI 2024] Bingwen Zhu, Fanyi Wang, Tianyi Lu, et al.</summary>
 Bingwen Zhu, Fanyi Wang, Tianyi Lu, Peng Liu, Jingwen Su, Jinxiu Liu, Yanhao Zhang, Zuxuan Wu, Guo-Jun Qi, Yu-Gang Jiang</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13680)

 + **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (21 Mar 2024)<details><summary>[ECCV 2024] Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>
 Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
 [![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/)

 + **DreaMoving: A Human Video Generation Framework based on Diffusion Models** (8 Dec 2023)<details><summary>Mengyang Feng, Jinlin Liu, Kai Yu, et al.</summary>
 Mengyang Feng, Jinlin Liu, Kai Yu, Yuan Yao, Zheng Hui, Xiefan Guo, Xianhui Lin, Haolan Xue, Chen Shi, Xiaowen Li, Aojie Li, Xiaoyang Kang, Biwen Lei, Miaomiao Cui, Peiran Ren, Xuansong Xie</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107)
 [![Code](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social&label=Star)](https://github.com/dreamoving/dreamoving-project)
[![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamoving.github.io/dreamoving/)

 + **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** (28 Nov 2023)<details><summary>[CVPR 2024] Li Hu, Xin Gao, Peng Zhang, et al.</summary>
 Li Hu, Xin Gao, Peng Zhang, Ke Sun, Bang Zhang, Liefeng Bo</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117v3)
 [![Code](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone/)

 + **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** (27 Nov 2023)<details><summary>[CVPR 2024] Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, et al.</summary>
 Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
 [![Code](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/magicanimate/)

 + **DISCO: Disentangled Control for Realistic Human Dance Generation** (30 Jun 2023)<details><summary>[CVPR 2024] Tan Wang, Linjie Li, Kevin Lin, et al.</summary>
 Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
 [![Code](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://disco-dance.github.io)

 + **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** (12 Apr 2023)<details><summary>[ICCV 2023] Johanna Karras, Aleksander Holynski, Ting-Chun Wang, et al.</summary>
 Johanna Karras, Aleksander Holynski, Ting-Chun Wang, Ira Kemelmacher-Shlizerman</details>
 [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025)
 [![Code](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose)
 [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://grail.cs.washington.edu/projects/dreampose/)


### 🖼️ + 💡 Image + Lighting

+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025) <details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531)
[![Code](https://img.shields.io/github/stars/tandaily/Awesome-Relighting.svg?style=social&label=Star)](https://github.com/tandaily/Awesome-Relighting)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VidCRAFT3/)

### ✍️ + 🔊 Text + Sound

### 🌟 + 🎥 Personalized + Motion
+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** (7 Jan 2025)<details><summary>Zekai Gu, Rui Yan, Jiahao Lu, et al.</summary>
  Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03847)
  [![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://igl-hkust.github.io/das/)

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (30 May 2024)<details><summary>[ECCV 2024] Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>
  Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
  [![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://myniuuu.github.io/MOFA_Video/)

+ **MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation** (27 Nov 2024)<details><summary>Haopeng Fang, Di Qiu, Binjie Mao, et al.</summary>
  Haopeng Fang, Di Qiu, Binjie Mao, Pengfei Yan, He Tang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18281)

+ **DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control** (17 Oct 2024)<details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, et al.</summary>
  Yujie Wei, Shiwei Zhang, Hangjie Yuan, Xiang Wang, Haonan Qiu, Rui Zhao, Yutong Feng, Feng Liu, Zhizhong Huang, Jiaxin Ye, Yingya Zhang, Hongming Shan</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13830)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamvideo2.github.io/)

+ **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** (22 Feb 2024)<details><summary>[ECCV 2024] Yixuan Ren, Yang Zhou, Jimei Yang, et al.</summary>
  Yixuan Ren, Yang Zhou, Jimei Yang, Jing Shi, Difan Liu, Feng Liu, Mingi Kwon, Abhinav Shrivastava</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
  [![Code](https://img.shields.io/github/stars/customize-a-video/customize-a-video.svg?style=social&label=Star)](https://github.com/customize-a-video/customize-a-video)

+ **Boximator: Generating Rich and Controllable Motions for Video Synthesis** (2 Feb 2024)<details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>
  Jiawei Wang, Yuchen Zhang, Jiaxin Zou, Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.00015)

+ **Moonshot: Towards Controllable Video Generation and Editing with Multimodal Conditions** (3 Jan 2024)<details><summary>David Junhao Zhang, Dongxu Li, Hung Le, et al.</summary>
  David Junhao Zhang, Dongxu Li, Hung Le, Mike Zheng Shou, Caiming Xiong, Doyen Sahoo</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/Moonshot/)

+ **VideoComposer: Compositional Video Synthesis with Motion Controllability** (3 Jun 2023)<details><summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, et al.</summary>
  Xiang Wang, Hangjie Yuan, Shiwei Zhang, Dayou Chen, Jiuniu Wang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
  [![Code](https://img.shields.io/github/stars/damo-vilab/videocomposer.svg?style=social&label=Star)](https://github.com/damo-vilab/videocomposer)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://videocomposer.github.io/)

+ **ControlVideo: Conditional Control for One-shot Text-driven Video Editing and Beyond** (26 May 2023)<details><summary>Min Zhao, Rongzhen Wang, Fan Bao, et al.</summary>
  Min Zhao, Rongzhen Wang, Fan Bao, Chongxuan Li, Jun Zhu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098)
  [![Code](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social&label=Star)](https://github.com/thu-ml/controlvideo)

+ **Control-A-Video: Controllable Text-to-Video Diffusion Models with Motion Prior and Reward Feedback Learning** (23 May 2023)<details><summary>Weifeng Chen, Yatai Ji, Jie Wu, et al.</summary>
  Weifeng Chen, Yatai Ji, Jie Wu, Hefeng Wu, Pan Xie, Jiashi Li, Xin Xia, Xuefeng Xiao, Liang Lin</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Code](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Star)](https://github.com/Weifeng-Chen/control-a-video)

+ **ControlVideo: Training-free Controllable Text-to-Video Generation** (22 May 2023)<details><summary>[ICLR 2024] Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, et al.</summary>
  Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, Xiaopeng Zhang, Wangmeng Zuo, Qi Tian</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Code](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Star)](https://github.com/YBYBZhang/ControlVideo)

+ **Video ControlNet: Towards Temporally Consistent Synthetic-to-Real Video Translation Using Conditional Image Diffusion Models** (30 May 2023)<details><summary>Ernie Chu, Shuo-Yen Lin, Jun-Cheng Chen</summary>
  Ernie Chu, Shuo-Yen Lin, Jun-Cheng Chen</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.19193)

+ **Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023)<details><summary>Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, et al.</summary>
  Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, Tsung-Yi Lin, Ming-Hsuan Yang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14797)

+ **Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators** (23 Mar 2023)<details><summary>[ICCV 2023 Oral] Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, et al.</summary>
  Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, Roberto Henschel, Zhangyang Wang, Shant Navasardyan, Humphrey Shi</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13439)
  [![Code](https://img.shields.io/github/stars/Picsart-AI-Research/Text2Video-Zero.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/Text2Video-Zero)
  [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://github.com/Picsart-AI-Research/Text2Video-Zero)

+ **Show Me What and Tell Me How: Video Synthesis via Multimodal Conditioning** (4 Mar 2022)<details><summary>[CVPR 2022] Ligong Han, Jian Ren, Hsin-Ying Lee, et al.</summary>
  Ligong Han, Jian Ren, Hsin-Ying Lee, Francesco Barbieri, Kyle Olszewski, Shervin Minaee, Dimitris Metaxas, Sergey Tulyakov</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.02573)
  [![Code](https://img.shields.io/github/stars/snap-research/MMVID.svg?style=social&label=Star)](https://github.com/snap-research/MMVID)
## ❓ To be sorted

## 🌐 Unified controllable generation
+ **Aether: Geometric-Aware Unified World Modeling** (18 Mar 2025)
   <details><summary>Aether Team, et al.</summary>  
        Haoyi Zhu, Yifan Wang, Jianjun Zhou, Wenzheng Chang, Yang Zhou, Zizun Li, Junyi Chen, Chunhua Shen, Jiangmiao Pang, Tong He </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18945)
   [![GitHub](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Star)](https://github.com/OpenRobotLab/Aether)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aether-world.github.io/)
+ **VACE: All-in-One Video Creation and Editing** (11 Mar 2025)<details><summary>Zeyinzi Jiang, Zhen Han, Chaojie Mao, et al.</summary>Zeyinzi Jiang, Zhen Han, Chaojie Mao, Jingfeng Zhang, Yulin Pan, Yu Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07598)
[![Code](https://img.shields.io/github/stars/ali-vilab/VACE.svg?style=social&label=Star)](https://github.com/ali-vilab/VACE)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-vilab.github.io/VACE-Page/)

+ **FullDiT: Multi-Task Video Generative Foundation Model with Full Attention** (25 Mar 2025)<details><summary>Xuan Ju, Weicai Ye, Quande Liu, et al.</summary>Xuan Ju, Weicai Ye, Quande Liu, Qiulin Wang, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.19907v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fulldit.github.io/)
+ **Any2Caption:Interpreting Any Condition to Caption for Controllable Video Generation** (31 Mar 2025)<details><summary>Shengqiong Wu, Weicai Ye, Jiahao Wang, et al.</summary>Shengqiong Wu, Weicai Ye, Jiahao Wang, Quande Liu, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Shuicheng Yan, Hao Fei, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.24379) 
[![Code](https://img.shields.io/github/stars/ChocoWu/Any2Caption.svg?style=social&label=Star)](https://github.com/ChocoWu/Any2Caption)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sqwu.top/Any2Cap/)




+ **VideoComposer: Compositional Video Synthesis with Motion Controllability** (6 Jun 2023)<details><summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, et al.</summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, Dayou Chen, Jiuniu Wang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
[![Code](https://img.shields.io/github/stars/ali-vilab/videocomposer.svg?style=social&label=Star)](https://github.com/ali-vilab/videocomposer)

