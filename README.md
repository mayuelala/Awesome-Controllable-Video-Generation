# 


<div align="center">
<h2><font color="red"> Awesome-Controllable-Video-Generation </h2>

 ![visitors](https://visitor-badge.laobi.icu/badge?page_id=mayuelala.Awesome-Controllable-Video-Generation&left_color=green&right_color=red)  [![GitHub](https://img.shields.io/github/stars/mayuelala/Awesome-Controllable-Video-Generation?style=social)](https://github.com/mayuelala/Awesome-Controllable-Video-Generation ) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

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
+ **Identity-Preserving Text-to-Video Generation by Frequency Decomposition** (25 Mar 2024)
  <details><summary> Shenghai Yuan, Jinfa Huang, et al.</summary>
        Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)


+ **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation**  
   <details><summary>Yingqing He, Menghan Xia, et al.</summary>  
         Yingqing He, Menghan Xia, Haoxin Chen, Xiaodong Cun, Yuan Gong, Jinbo Xing, Yong Zhang, Xintao Wang, Chao Weng, Ying Shan, Qifeng Chen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)  [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/VideoCrafter/Animate-A-Story)

+ **ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning**  
   <details><summary>Yuzhou Huang, Ziyang Yuan, Quande Liu, et al.</summary>  
         Yuzhou Huang, Ziyang Yuan, Quande Liu, Qiulin Wang, Xintao Wang, Ruimao Zhang, Pengfei Wan, Di Zhang, Kun Gai</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04698)

+ **Videodreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning**  
   <details><summary>Hong Chen, Xin Wang, Guanning Zeng, et al.</summary>  
         Hong Chen, Xin Wang, Guanning Zeng, Yipeng Zhang, Yuwei Zhou, Feilin Han, Wenwu Zhu</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00990)

+ **VideoBooth: Diffusion-based Video Generation with Image Prompts**  
   <details><summary>Yuming Jiang, Tianxing Wu, et al.</summary>  
         Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)  [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/Vchitect/VideoBooth)

+ **Customcrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities**  
   <details><summary>Tao Wu, Yong Zhang, Xintao Wang, et al.</summary>  
         Tao Wu, Yong Zhang, Xintao Wang, Xianpan Zhou, Guangcong Zheng, Zhongang Qi, Ying Shan, Xi Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13239)

+ **Still-Moving: Customized Video Generation Without Customized Video Data**  
   <details><summary>Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, et al.</summary>  
         Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, Omer Tov, Michael Rubinstein, Lior Wolf, Tali Dekel, Tomer Michaeli, Inbar Mosseri</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08674)

+ **Customvideo: Customizing Text-to-Video Generation with Multiple Subjects**  
   <details><summary>Zhao Wang, Aoxue Li, et al.</summary>  
         Zhao Wang, Aoxue Li, Lingting Zhu, Yong Guo, Qi Dou, Zhenguo Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09962)

+ **Dreamvideo: Composing Your Dream Videos with Customized Subject and Motion**  
   <details><summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing, et al.</summary>  
         Yujie Wei, Shiwei Zhang, Zhiwu Qing, Hangjie Yuan, Zhiheng Liu, Yu Liu, Yingya Zhang, Jingren Zhou, Hongming Shan</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)[![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://dreamvideo-t2v.github.io/)

+ **MotionBooth: Motion-Aware Customized Text-to-Video Generation**  
   <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>  
         Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)

+ **ID-Animator: Zero-Shot Identity-Preserving Human Video Generation** (25 Jun 2024)  
   <details><summary>Xuanhua He, Quande Liu, et al.</summary>  
         Xuanhua He, Quande Liu, Shengju Qian, Xin Wang, Tao Hu, Ke Cao, Keyu Yan, Jie Zhang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275) [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/ID-Animator/ID-Animator)

+ **PERSONALVIDEO: High ID-Fidelity Video Customization with Static Images**  
   <details><summary>Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, et al.</summary>  
         Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, Yujie Wei, Zekun Li, Yingya Zhang, Boxi Wu, Deng Cai</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17048)

+ **TaleCrafter: Interactive Story Visualization with Multiple Characters**  
   <details><summary>Yuan Gong, Youxin Pang, et al.</summary>  
         Yuan Gong, Youxin Pang, Xiaodong Cun, Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247) [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/VideoCrafter/TaleCrafter)

+ **Dreamix: Video Diffusion Models are General Video Editors**  
   <details><summary>Eyal Molad, Eliahu Horwitz, et al.</summary>  
         Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)  


+ **VideoAlchemy: Open-set Personalization in Video Generation**  
   <details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, et al.</summary>  
        Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Ivan Skorokhodov, Jun-Yan Zhu, Kfir Aberman, Ming-Hsuan Yang, Sergey Tulyakov </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/pdf?id=popKM1zAYa)   



### 📍 Spatial Control

#### 🕺 Pose Control
+ **TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation** (14 Mar 2025)
   <details><summary>Hongxiang Zhao, Xingchen Liu, et al.</summary>  
        Hongxiang Zhao, Xingchen Liu, Mutian Xu, Yiming Hao, Weikai Chen, Xiaoguang Han </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11423)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://taste-rob.github.io/)

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

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14484)
   [![Code](https://img.shields.io/github/stars/ljzycmd/SCD.svg?style=social&label=Star)](https://github.com/ljzycmd/SCD)

+ **DirectorLLM for Human-Centric Video Generation** (19 Dec 2024)
   <details><summary>Kunpeng Song, Tingbo Hou, et al.</summary>  
        Kunpeng Song, Tingbo Hou, Zecheng He, Haoyu Ma, Jialiang Wang, Animesh Sinha, Sam Tsai, Yaqiao Luo, Xiaoliang Dai, Li Chen, Xide Xia, Peizhao Zhang, Peter Vajda, Ahmed Elgammal, Felix Juefei-Xu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14484)

+ **Generative Inbetweening through Frame-wise Conditions-Driven Video Generation** (16 Dec 2024)
   <details><summary>Tianyi Zhu, Dongwei Ren, et al.</summary>  
        Tianyi Zhu, Dongwei Ren, Qilong Wang, Xiaohe Wu, Wangmeng Zuo </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11755)
   [![Code](https://img.shields.io/github/stars/Tian-one/FCVGe.svg?style=social&label=Star)](https://github.com/Tian-one/FCVG)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fcvg-inbetween.github.io/)

+ **DisPose: Disentangling Pose Guidance for Controllable Human Image Animation** (12 Dec 2024)
   <details><summary>Hongxiang Li, Yaowei Li, et al.</summary>  
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
   <details><summary>Shenhao Zhu, Junming Leo Chen, et al.</summary>  
        Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
   [![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **Do You Guys Want to Dance: Zero-Shot Compositional Human Dance Generation with Multiple Persons** (24 Jan 2024)
   <details><summary>Zhe Xu, Kun Wei, et al.</summary>  
        Zhe Xu, Kun Wei, Xu Yang, Cheng Deng </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13363)

+ **Generative Rendering: Controllable 4D-Guided Video Generation with 2D Diffusion Models** (3 Dec 2023)
   <details><summary>Shengqu Cai, Duygu Ceylan, et al.</summary>  
        Shengqu Cai, Duygu Ceylan, Matheus Gadelha, Chun-Hao Paul Huang, Tuanfeng Yang Wang, Gordon Wetzstein </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://primecai.github.io/generative_rendering/)


+ **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** (28 Nov 2023)
   <details><summary>Li Hu, Xin Gao, et al.</summary>  
        Li Hu, Xin Gao, Peng Zhang, Ke Sun, Bang Zhang, Liefeng Bo </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117)
   [![Code](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone/)

+ **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** (27 Nov 2023)
   <details><summary>Zhongcong Xu, Jianfeng Zhang, et al.</summary>  
        Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
   [![Code](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/magicanimate/)

+ **MagicPose: Realistic Human Poses and Facial Expressions Retargeting with Identity-aware Diffusion** (18 Nov 2023)
   <details><summary>Zhongcong Xu, Jianfeng Zhang, et al.</summary>  
        Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498)
   [![Code](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social&label=Star)](https://github.com/Boese0601/MagicDance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boese0601.github.io/magicdance/)

+ **Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model** (15 Aug 2023)
   <details><summary>Bosheng Qin, Wentao Ye, et al.</summary>  
        Bosheng Qin, Wentao Ye, Qifan Yu, Siliang Tang, Yueting Zhuang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07749)

+ **DisCo: Disentangled Control for Realistic Human Dance Generation** (30 Jun 2023)
   <details><summary>Tan Wang, Linjie Li, et al.</summary>  
        Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040)
   [![Code](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://disco-dance.github.io/)

+ **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** (12 Apr 2023)
   <details><summary>Johanna Karras, Aleksander Holynski, et al.</summary>  
        Johanna Karras, Aleksander Holynski, Ting-Chun Wang, Ira Kemelmacher-Shlizerman </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025)
   [![Code](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://grail.cs.washington.edu/projects/dreampose/)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023)
   <details><summary>Yue Ma, Yingqing He, et al.</summary>  
        Yue Ma, Yingqing He, Xiaodong Cun, Xintao Wang, Siran Chen, Ying Shan, Xiu Li, Qifeng Chen </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)
   [![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)

+ **Point-to-Point Video Generation** (5 Apr 2019)
   <details><summary>Tsun-Hsuan Wang, Yen-Chi Cheng, et al.</summary>  
        Tsun-Hsuan Wang, Yen-Chi Cheng, Chieh Hubert Lin, Hwann-Tzong Chen, Min Sun </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1904.02912)
   [![Code](https://img.shields.io/github/stars/yccyenchicheng/p2pvg.svg?style=social&label=Star)](https://github.com/yccyenchicheng/p2pvg)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zswang666.github.io/P2PVG-Project-Page/)

+ **Pose Guided Human Video Generation** (3 Apr 2023)
   <details><summary>Ceyuan Yang, Zhe Wang, et al.</summary>  
        Ceyuan Yang, Zhe Wang, Xinge Zhu, Chen Huang, Jianping Shi, Dahua Lin </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186)

#### 🚗 BEV-Control
+ **MagicDrive: Street View Generation with Diverse 3D Geometry Control** (04 Oct 2023)<details><summary>Ruiyuan Gao, Kai Chen, Enze Xie, et al.</summary>
Ruiyuan Gao, Kai Chen, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02601)
[![Code](https://img.shields.io/github/stars/cure-lab/MagicDrive.svg?style=social&label=Star)](https://github.com/cure-lab/MagicDrive)
[![Project](https://img.shields.io/badge/Project-111111.svg)](http://gaoruiyuan.com/magicdrive/)

+ **Seeing Beyond Views: Multi-View Driving Scene Video Generation with   Holistic Attention** (04 Dec 2024)<details><summary>Hannan Lu, Xiaohe Wu, Shudong Wang, et al.</summary>
Hannan Lu, Xiaohe Wu, Shudong Wang, Xiameng Qin, Xinyu Zhang, Junyu Han, Wangmeng Zuo, Ji Tao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.03520)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://luhannan.github.io/CogDrivingPage/)

+ **DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video   Generation** (11 Mar 2024)<details><summary>Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, et al.</summary>
Guosheng Zhao, Xiaofeng Wang, Zheng Zhu, Xinze Chen, Guan Huang, Xiaoyi Bao, Xingang Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.06845)
[![Code](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Star)](https://github.com/f1yfisher/DriveDreamer2)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://drivedreamer2.github.io)

+ **MagicDrive-V2: High-Resolution Long Video Generation for Autonomous   Driving with Adaptive Control** (21 Nov 2024)<details><summary>Ruiyuan Gao, Kai Chen, Bo Xiao, et al.</summary>
Ruiyuan Gao, Kai Chen, Bo Xiao, Lanqing Hong, Zhenguo Li, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.13807)
[![Code](https://img.shields.io/github/stars/flymin/MagicDrive-V2.svg?style=social&label=Star)](https://github.com/flymin/MagicDrive-V2)
[![Project](https://img.shields.io/badge/Project-111111.svg)](http://gaoruiyuan.com/magicdrive-v2/)

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

+ **Panacea: Panoramic and Controllable Video Generation for Autonomous   Driving** (28 Nov 2023)<details><summary>Yuqing Wen, Yucheng Zhao, Yingfei Liu, et al.</summary>
Yuqing Wen, Yucheng Zhao, Yingfei Liu, Fan Jia, Yanhui Wang, Chong Luo, Chi Zhang, Tiancai Wang, Xiaoyan Sun, Xiangyu Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16813)
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)
[![Project](https://img.shields.io/badge/Project-111111.svg)](https://panacea-ad.github.io)

#### 🎨 Style Control

#### 📌 Point Control

#### 📏 Depth Control

#### 🗺️ Landmark Control

### ✍️ Text Rendering
+ **Text-Animator: Controllable Visual Text Video Generation** (25 Jun 2024)<details><summary>Lin Liu, Quande Liu, Shengju Qian, et al.</summary>Yuan Zhou, Wengang Zhou, Houqiang Li, Lingxi Xie, Qi Tian</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17777)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=fcc87eec6543d4e33a2cd679b705292af9020cb4)](https://www.semanticscholar.org/paper/fcc87eec6543d4e33a2cd679b705292af9020cb4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laulampaul.github.io/text-animator)

+ **Wan: Open and Advanced Large-Scale Video Generative Models** (2025)<details><summary>WanTeam, Ang Wang, Baole Ai, et al.</summary>Bin Wen,Chaojie Mao,Chen-Wei Xie,Di Chen,Feiwu Yu,Haiming Zhao,Jianxiao Yang,Jianyuan Zeng,Jiayu Wang,Jingfeng Zhang,Jingren Zhou,Jinkai Wang,Jixuan Chen,Kai Zhu,Kang Zhao,Keyu Yan,Lianghua Huang,Mengyang Feng,Ningyi Zhang,Pandeng Li,Pingyu Wu,Ruihang Chu,Ruili Feng,Shiwei Zhang,Siyang Sun,Tao Fang,Tianxing Wang,Tianyi Gui,Tingyu Weng,Tong Shen,Wei Lin,Wei Wang~1,Wei Wang~2,Wenmeng Zhou,Wente Wang,Wenting Shen,Wenyuan Yu,Xianzhong Shi,Xiaoming Huang,Xin Xu,Yan Kou,Yangyu Lv,Yifei Li,Yijing Liu,Yiming Wang,Yingya Zhang,Yitong Huang,Yong Li,You Wu,Yu Liu,Yulin Pan,Yun Zheng,Yuntao Hong,Yupeng Shi,Yutong Feng,Zeyinzi Jiang,Zhen Han,Zhi-Fan Wu,Ziyu Liu</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://files.alicdn.com/tpsservice/5c9de1c74de03972b7aa657e5a54756b.pdf)
[![Code](https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social&label=Star)](https://github.com/Wan-Video/Wan2.1)


### ⏳ Temporal Control

#### 🌊 Flow-Guided

#### 📸 Camera-Guided
+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** (30 Mar 2025)<details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary>Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)

+ **CineMaster: A 3D-Aware and Controllable Framework for Cinematic Text-to-Video Generation** (30 Mar 2025)<details><summary>Qinghe Wang, Yawen Luo, Xiaoyu Shi, et al.</summary>Xu Jia, Huchuan Lu, Tianfan Xue, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08639)

+ **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion** (30 Mar 2025)<details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, et al.</summary>Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2402.03162)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)

+ **3DTRAJMASTER: MASTERING 3D TRAJECTORY FOR MULTI-ENTITY MOTION IN VIDEO GENERATION** (30 Mar 2025)<details><summary>Xiao Fu, Xian Liu, Xintao Wang, et al.</summary>Sida Peng, Menghan Xia, Xiaoyu Shi, Ziyang Yuan, Pengfei Wan, Di Zhang, Dahua Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07759)

+ **AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers** (30 Mar 2025)<details><summary>Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, et al.</summary>Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.18673)
  [![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** (30 Mar 2025)<details><summary>Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.02101)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)

+ **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** (30 Mar 2025)<details><summary>Wangbo Yu, Jinbo Xing, Li Yuan, et al.</summary>Wenbo Hu, Xiaoyu Li, Zhipeng Huang, Xiangjun Gao, Tien-Tsin Wong, Ying Shan, Yonghong Tian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/Drexubery/ViewCrafter)

+ **EgoSim: Egocentric Exploration in Virtual Worlds with Multi-modal Conditioning** (30 Mar 2025)<details><summary>Wei Yu, Songheng Yin, Steve Easterbrook, Animesh Garg</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/pdf?id=hN5h0hrQ6a)

+ **MOTIONFLOW: LEARNING IMPLICIT MOTION FLOW FOR COMPLEX CAMERA TRAJECTORY CONTROL IN VIDEO GENERATION** (30 Mar 2025)<details><summary>Author list not fully provided</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/pdf?id=OBTmkKBmQW)

+ **MotionMaster: Training-free Camera Motion Transfer For Video Generation** (30 Mar 2025)<details><summary>Teng Hu, Jiangning Zhang, Ran Yi, et al.</summary>Yating Wang, Hongrui Huang, Jieyu Weng, Yabiao Wang, Lizhuang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15789)
[![Code](https://img.shields.io/github/stars/sjtuplayer/MotionMaster.svg?style=social&label=Star)](https://github.com/sjtuplayer/MotionMaster)

+ **ReCamMaster: Camera-Controlled Generative Rendering from A Single Video** (30 Mar 2025)<details><summary>Jianhong Bai, Menghan Xia, Xiao Fu, et al.</summary>Xintao Wang, Lianrui Mu, Jinwen Cao, Zuozhu Liu, Haoji Hu, Xiang Bai, Pengfei Wan, Di Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11647)

+ **CPA: Camera-pose-awareness Diffusion Transformer for Video Generation** (30 Mar 2025)<details><summary>Yuelei Wang, Jian Zhang, Pengtao Jiang, et al.</summary>Hao Zhang, Jinwei Chen, Bo Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01429)

+ **BOOSTING CAMERA MOTION CONTROL FOR VIDEO DIFFUSION TRANSFORMERS** (30 Mar 2025)<details><summary>Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, et al.</summary>Andrew Gilbert, Chun-Hao Paul Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10802)

+ **CAVIA: CAMERA-CONTROLLABLE MULTI-VIEW VIDEO DIFFUSION WITH VIEW-INTEGRATED ATTENTION** (30 Mar 2025)<details><summary>Dejia Xu, Yifan Jiang, Chen Huang, et al.</summary>Liangchen Song, Thorsten Gernoth, Liangliang Cao, Zhangyang Wang, Hao Tang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10774)

+ **Latent-Reframe: Enabling Camera Control for Video Diffusion Model without Training** (30 Mar 2025)<details><summary>Zhenghong Zhou, Jie An, Jiebo Luo</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06029)

+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models** (30 Mar 2025)<details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary>Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592)
#### 🛤️ Traj-Guided
+ **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion** <details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2402.03162)
+ **TrailBlazer: Trajectory Control for Diffusion-Based Video Generation(Both are based on T2V, not I2V.)** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00896)
+ **Freetraj: Tuning-free trajectory control in video diffusion models(T2V)** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.16863)
+ **Peekaboo: Interactive video generation via masked-diffusion(T2V)** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.07509)
+ **MotionBooth: Motion-Aware Customized Text-to-Video Generation** <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.17758)
+ **Collaborative video diffusion: Consistent multi-video generation with camera control** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.17414)
+ **Tora: Trajectory-oriented Diffusion Transformer for Video Generation** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21705)
+ **Motion-Zero: A Zero-Shot Trajectory Control Framework of Moving Object** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2401.10150)
+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)
+ **Controllable Video Generation With Sparse Trajectories** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2018/papers/Hao_Controllable_Video_Generation_CVPR_2018_paper.pdf)
+ **MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance** <details><summary>Quanhao Li, Zhen Xing, Rui Wang, Hui Zhang, Qi Dai, Zuxuan Wu</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.16421v1)
+ **MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation** <details><summary>Authors not provided</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2502.04299v1) 

#### 🎥 Motion Customization/Motion Mask/Motion Video(traj)
+ **MotionAgent: Fine-grained Controllable Video Generation via Motion Field Agent** <details><summary>Xinyao Liao, Xianfang Zeng, Liao Wang, Gang Yu, Guosheng Lin, Chi Zhang</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.03207)

+ **Motionbooth: Motion-aware customized text-to-video generation** <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories** <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02700)

+ **Video Motion Transfer with Diffusion Transformers** <details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07776)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/ditflow/ditflow)

+ **MOTION INVERSION FOR VIDEO CUSTOMIZATION** <details><summary>Luozhou Wang, Ziyang Mai, Guibao Shen, Yixun Liang, Xin Tao, Pengfei Wan, Di Zhang, Yijun Li, Yingcong Chen</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2403.20193)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/EnVision-Research/MotionInversion)

+ **Space-Time Diffusion Features for Zero-Shot Text-Driven Motion Transfer** <details><summary>Danah Yatim, Rafail Fridman, Omer Bar-Tal, Yoni Kasten, Tali Dekel</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2311.17009)

+ **Spectral Motion Alignment for Video Motion Transfer using Diffusion Models** <details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2403.15249)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/diffusion-motion-transfer/diffusion-motion-transfer)

+ **MoTrans: Customized Motion Transfer with Text-driven Video Diffusion Models** <details><summary>Xiaomin Li, Xu Jia, Qinghe Wang</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.01343)

+ **DreamMotion: Space-Time Self-Similar Score Distillation for Zero-Shot Video Editing** <details><summary>Hyeonho Jeong, Jinho Chang, Geon Yeong Park, and Jong Chul Ye</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2403.12002)

+ **DreamRelation: Relation-Centric Video Customization** <details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, Biao Gong, Longxiang Tang, Xiang Wang, Haonan Qiu, Hengjia Li, Shuai Tan, Yingya Zhang, Hongming Shan</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.07602)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamrelation.github.io/#)

+ **Training-Free Motion-Guided Video Generation with Enhanced Temporal Consistency Using Motion Consistency Loss** <details><summary>Xinyu Zhang, Zicheng Duan, Dong Gong, Lingqiao Liu</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.07563)
+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance**<details><summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ)
+ **DreamVideo: Composing Your Dream Videos with Customized Subject and Motion(可以single motion vedios和multiple vedios)** <details><summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing, Hangjie Yuan, Zhiheng Liu, Yu Liu, Yingya Zhang, Jingren Zhou, Hongming Shan</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)
+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05020)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)
+ **InterDyn: Controllable Interactive Dynamics with Video Diffusion Models (hand mask sequence as control signal)** <details><summary>Rick Akkerman, Haiwen Feng, Michael J. Black, Dimitrios Tzionas, Victoria Fern´andez Abrevaya</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.11785)
+ **LHM: Large Animatable Human Reconstruction Model for Single Image to 3D in Seconds** <details><summary>Lingteng Qiu, Xiaodong Gu, Peihao Li, Qi Zuo, Weichao Shen, Junfei Zhang, Kejie Qiu, Weihao Yuan, Guanying Chen, Zilong Dong, Liefeng Bo</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://lingtengqiu.github.io/LHM/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/aigc3d/LHM)
+ **MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance** <details><summary>Quanhao Li, Zhen Xing, Rui Wang, Hui Zhang, Qi Dai, Zuxuan Wu</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.16421v1)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/quanhaol/MagicMotion)
+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** <details><summary>Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://igl-hkust.github.io/das/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader)
+ **Zero-Shot Controllable Image-to-Video Animation via Motion Decomposition** <details><summary>Alexander Pondaven, Aliaksandr Siarohin, Sergey Tulyakov, Philip Torr, Fabio Pizzati</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07776)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/Yui010206/IVA-0) 

### 📝 Advanced Text-Conditioned

### 🔄 In-Context

### 🖼️ Image-guided
+ **Autoregressive Video Generation without Vector Quantization** (9 Jan 2025)<details><summary>[ICLR 2025] Haoge Deng, Ting Pan, Haiwen Diao, et al.</summary>Zhengxiong Luo, Yufeng Cui, Huchuan Lu, Shiguang Shan, Yonggang Qi, Xinlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14169)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=735b7f4f91bcc5e9712df7f419eade672b1d3968)](https://www.semanticscholar.org/paper/735b7f4f91bcc5e9712df7f419eade672b1d3968)
[![Code](https://img.shields.io/github/stars/baaivision/NOVA.svg?style=social&label=Star)](https://github.com/baaivision/NOVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BAAI/nova-d48w1024-osp480)

+ **I4VGen: Image as Free Stepping Stone for Text-to-Video Generation** (3 Oct 2024)<details><summary>Xiefan Guo, Jinlin Liu, Miaomiao Cui, et al.</summary>Liefeng Bo, Di Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02230)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=74b41f1723263a8a2f2999a0cdffb57b79b1e97e)](https://www.semanticscholar.org/paper/74b41f1723263a8a2f2999a0cdffb57b79b1e97e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiefan-guo.github.io/i4vgen/)
[![Code](https://img.shields.io/github/stars/xiefan-guo/i4vgen.svg?style=social&label=Star)](https://github.com/xiefan-guo/i4vgen)

+ **DreamVideo: High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance** (16 Sep 2024)<details><summary>[ICASSP 2025] Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary>Songcen Xu, Hang Xu, Xiaodan Liang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/abstract/document/10887583)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=a30883a9408914732f816933f0a5f1f3980fd5c8)](https://www.semanticscholar.org/paper/a30883a9408914732f816933f0a5f1f3980fd5c8)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anonymous0769.github.io/DreamVideo/)
[![Code](https://img.shields.io/github/stars/anonymous0769/DreamVideo.svg?style=social&label=Star)](https://github.com/anonymous0769/DreamVideo)

+ **HunyuanVideo: A Systematic Framework For Large Video Generative Models** (11 Mar 2025)<details><summary>Weijie Kong, Qi Tian, Zijian Zhang, et al.</summary>Rox Min, Zuozhuo Dai, Jin Zhou, Jiangfeng Xiong, Xin Li, Bo Wu, Jianwei Zhang, Kathrina Wu, Qin Lin, Junkun Yuan, Yanxin Long, Aladdin Wang, Andong Wang, Changlin Li, Duojun Huang, Fang Yang, Hao Tan, Hongmei Wang, Jacob Song, Jiawang Bai, Jianbing Wu, Jinbao Xue, Joey Wang, Kai Wang, Mengyang Liu, Pengyu Li, Shuai Li, Weiyan Wang, Wenqing Yu, Xinchi Deng, Yang Li, Yi Chen, Yutao Cui, Yuanbo Peng, Zhentao Yu, Zhiyu He, Zhiyong Xu, Zixiang Zhou, Zunnan Xu, Yangyu Tao, Qinglin Lu, Songtao Liu, Dax Zhou, Hongfa Wang, Yong Yang, Di Wang, Yuhong Liu, Jie Jiang, Caesar Zhong</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://arxiv.org/abs/2412.03603)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=1fa298e3f745099d39ca5bd088fcb62f87e8cc2f)](https://www.semanticscholar.org/paper/1fa298e3f745099d39ca5bd088fcb62f87e8cc2f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aivideo.hunyuan.tencent.com/)
[![Code](https://img.shields.io/github/stars/Tencent/HunyuanVideo-I2V.svg?style=social&label=Star)](https://github.com/Tencent/HunyuanVideo-I2V)

+ **ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation** (1 Jul 2024)<details><summary>[TMLR 2024] Weiming Ren, Huan Yang, Ge Zhang, et al.</summary>Cong Wei, Xinrun Du, Wenhao Huang, Wenhu Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.04324)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=d599dc40c9cb8d6d76554ee7d21d20c22cc7cdb5)](https://www.semanticscholar.org/paper/d599dc40c9cb8d6d76554ee7d21d20c22cc7cdb5)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tiger-ai-lab.github.io/ConsistI2V/)
[![Code](https://img.shields.io/github/stars/TIGER-AI-Lab/ConsistI2V.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/ConsistI2V)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/TIGER-Lab/ConsistI2V)

+ **AnimateAnything: Fine-Grained Open Domain Image Animation with Motion Guidance** (4 Dec 2023)<details><summary>[TMLR 2024] Zuozhuo Dai, Zhenghao Zhang, Yao Yao, et al.</summary>Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12886)
[![citation](https://img.shields.io/badge/citation-40-blue.svg?paper=ff1715c4a33a58cc8069b86be8b99e760134eb78)](https://www.semanticscholar.org/paper/ff1715c4a33a58cc8069b86be8b99e760134eb78)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://animationai.github.io/AnimateAnything/)
[![Code](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)

+ **Make It Move: Controllable Image-to-Video Generation With Text Descriptions** (31 Mar 2022)<details><summary>[CVPR 2022] Yaosi Hu, Chong Luo, Zhenzhong Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Make_It_Move_Controllable_Image-to-Video_Generation_With_Text_Descriptions_CVPR_2022_paper.html)
[![citation](https://img.shields.io/badge/citation-73-blue.svg?paper=e829046a7f9a65e3bbe937ce4ce4649a0f78f0e7)](https://www.semanticscholar.org/paper/e829046a7f9a65e3bbe937ce4ce4649a0f78f0e7)
[![Code](https://img.shields.io/github/stars/Youncy-Hu/MAGE.svg?style=social&label=Star)](https://github.com/Youncy-Hu/MAGE)

+ **PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation** (27 Sep 2024)<details><summary>[ECCV 2024] Shaowei Liu, Zhongzheng Ren, Saurabh Gupta, et al.</summary>Shenlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18964)
[![citation](https://img.shields.io/badge/citation-19-blue.svg?paper=3c314149c36871bace898f3dcff03fb21de0ba64)](https://www.semanticscholar.org/paper/3c314149c36871bace898f3dcff03fb21de0ba64)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://stevenlsw.github.io/physgen/)
[![Code](https://img.shields.io/github/stars/stevenlsw/physgen.svg?style=social&label=Star)](https://github.com/stevenlsw/physgen)

+ **Motion-i2v: Consistent and controllable image-to-video generation with explicit motion modeling** (31 Jan 2024)<details><summary>[ACM SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657497)
[![citation](https://img.shields.io/badge/citation-61-blue.svg?paper=450011c7e089675b25dad11cd7611c310a7a8e9b)](https://www.semanticscholar.org/paper/450011c7e089675b25dad11cd7611c310a7a8e9b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)

+ **I2V-Adapter: A General Image-to-Video Adapter for Diffusion Models** (13 July 2024)<details><summary>[ACM SIGGRAPH 2024] Xun Guo1, Mingwu Zheng, Liang Hou, et al.</summary>Yuan Gao, Yufan Deng, Pengfei Wan,
Di Zhang, Yufan Liu, Weiming Hu, Zhengjun Zha, Haibin Huang, Chongyang Ma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657407)
[![citation](https://img.shields.io/badge/citation-21-blue.svg?paper=9512a9bbef95560c719a746676611bfcded428a1)](https://www.semanticscholar.org/paper/9512a9bbef95560c719a746676611bfcded428a1)

+ **DynamiCrafter: Animating Open-Domain Images with Video Diffusion Priors** (1 Oct 2024)<details><summary>[ECCV 2024] Jinbo Xing, Menghan Xia, Yong Zhang,  et al.</summary>Haoxin Chen, Wangbo Yu, Hanyuan Liu, Gongye Liu, Xintao Wang, Ying Shan, Tien-Tsin Wong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-72952-2_23)
[![citation](https://img.shields.io/badge/citation-152-blue.svg?paper=083bab4a967c2221d9f4da9110fe37d8ca679078)](https://www.semanticscholar.org/paper/083bab4a967c2221d9f4da9110fe37d8ca679078)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/DynamiCrafter/)
[![Code](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/DynamiCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Doubiiu/DynamiCrafter)

+ **VideoDoodles: Hand-Drawn Animations on Videos with Scene-Aware Canvases** (26 July 2023)<details><summary>[ACM Transactions on Graphics] Emilie Yu, Kevin Blackburn-Matzen, Cuong Nguyen, et al.</summary>Oliver Wang, Rubaiat Habib Kazi, Adrien Bousseau</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3592413)
[![citation](https://img.shields.io/badge/citation-12-blue.svg?paper=ffd1f7b6bc38579b5e4a02d1cde64bdda030dce5)](https://www.semanticscholar.org/paper/ffd1f7b6bc38579b5e4a02d1cde64bdda030dce5)

+ **Structure and Content-Guided Video Synthesis with Diffusion Models** (27 Sep 2024)<details><summary>[ICCV 2023] Patrick Esser, Johnathan Chiu, Parmida Atighehchian, et al.</summary>Jonathan Granskog, Anastasis Germanidis</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.html)
[![citation](https://img.shields.io/badge/citation-459-blue.svg?paper=07be0ec1f45e21a1032616535d0290ee6bfe0f6b)](https://www.semanticscholar.org/paper/07be0ec1f45e21a1032616535d0290ee6bfe0f6b)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://runwayml.com/research/gen-1)

+ **Follow-Your-Click: Open-domain Regional Image Animation via Short Prompts** (13 Mar 2024)<details><summary>Yue Ma, Yingqing He, Hongfa Wang, et al.</summary>Andong Wang, Chenyang Qi, Chengfei Cai, Xiu Li, Zhifeng Li, Heung-Yeung Shum, Wei Liu, Qifeng Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08268)
[![citation](https://img.shields.io/badge/citation-31-blue.svg?paper=d9c20c449a51910ef2d107668d962b4a2e182f52)](https://www.semanticscholar.org/paper/d9c20c449a51910ef2d107668d962b4a2e182f52)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-click.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourClick.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourClick)


+ **FrameBridge: Improving Image-to-Video Generation with Bridge Models** (20 Oct 2024)<details><summary>Yuji Wang, Zehua Chen, Xiaoyu Chen, et al.</summary>Jun Zhu, Jianfei Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15371)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=355544f41ff0f28234c3f5190a7ce75d74dd8f61)](https://www.semanticscholar.org/paper/355544f41ff0f28234c3f5190a7ce75d74dd8f61)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://framebridge-demo.github.io/)

+ **I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models** (7 Nov 2023)<details><summary>Shiwei Zhang, Jiayu Wang, Yingya Zhang, et al.</summary>Kang Zhao, Hangjie Yuan, Zhiwu Qin, Xiang Wang, Deli Zhao, Jingren Zhou</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04145)
[![citation](https://img.shields.io/badge/citation-168-blue.svg?paper=9b86ce1bde87b304141641b49299f4d0f1f7ba1d)](https://www.semanticscholar.org/paper/9b86ce1bde87b304141641b49299f4d0f1f7ba1d)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://i2vgen-xl.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)

+ **Extrapolating and Decoupling Image-to-Video Generation Models: Motion Modeling is Easier Than You Think** (2 Mar 2025)<details><summary>[CVPR 2025] Jie Tian, Xiaoye Qu, Zhenyi Lu, et al.</summary>Wei Wei, Sichen Liu, Yu Cheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00948)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=7ab6ed3edb7d781a34f2c8a67aa974903b1f9f4f)](https://www.semanticscholar.org/paper/7ab6ed3edb7d781a34f2c8a67aa974903b1f9f4f)
[![Code](https://img.shields.io/github/stars/Chuge0335/EDG.svg?style=social&label=Star)](https://github.com/Chuge0335/EDG)

+ **STIV: Scalable Text and Image Conditioned Video Generation** (10 Dec 2024)<details><summary>Zongyu Lin, Wei Liu, Chen Chen, et al.</summary>Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07730)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=20ae850e781fc07eb08311df7772010da3123f98)](https://www.semanticscholar.org/paper/20ae850e781fc07eb08311df7772010da3123f98)

+ **Through-The-Mask: Mask-based Motion Trajectories for Image-to-Video Generation** (6 Jan 2025)<details><summary>[CVPR 2025] Guy Yariv, Yuval Kirstain, Amit Zohar, et al.</summary>Shelly Sheynin, Yaniv Taigman, Yossi Adi, Sagie Benaim, Adam Polyak</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03059)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=44eac98880108aef441ee8ca0c0edac9a8d53b67)](https://www.semanticscholar.org/paper/44eac98880108aef441ee8ca0c0edac9a8d53b67)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guyyariv.github.io/TTM/)

+ **Tuning-Free Noise Rectification for High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Weijie Li, Litong Gong, Yiran Zhu, et al.</summary>Fanda Fan, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02827)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=cf0a5c9eeaf52d02661c8a52c2ccc12d7fb58b15)](https://www.semanticscholar.org/paper/cf0a5c9eeaf52d02661c8a52c2ccc12d7fb58b15)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://noise-rectification.github.io/)
[![Code](https://img.shields.io/github/stars/alimama-creative/Noise-Rectification.svg?style=social&label=Star)](https://github.com/alimama-creative/Noise-Rectification)

+ **Decouple Content and Motion for Conditional Image-to-Video Generation** (14 Dec 2023)<details><summary>[AAAI 2024] Cuifeng Shen, Yulu Gan, Chen Chen, et al.</summary>Xiongwei Zhu, Lele Cheng, Tingting Gao, Jinzhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=8e37c6d2442ece49a80e63b65bcc4e9c0b49d580)](https://www.semanticscholar.org/paper/8e37c6d2442ece49a80e63b65bcc4e9c0b49d580)

+ **MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation** (8 Dec 2024)<details><summary>Shuwei Shi, Biao Gong, Xi Chen, et al.</summary>Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05848)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=d66fa35283319bacc82cbbde80b7cc710bd4cb38)](https://www.semanticscholar.org/paper/d66fa35283319bacc82cbbde80b7cc710bd4cb38)


+ **AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction** (10 Jun 2024)<details><summary>Zhen Xing, Qi Dai, Zejia Weng, et al.</summary>Zuxuan Wu, Yu-Gang Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06465)
[![citation](https://img.shields.io/badge/citation-10-blue.svg?paper=d657de11802239a58a77f486a0c6861e89d4da50)](https://www.semanticscholar.org/paper/d657de11802239a58a77f486a0c6861e89d4da50)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenhsing.github.io/AID/)
[![Code](https://img.shields.io/github/stars/ChenHsing/AID.svg?style=social&label=Star)](https://github.com/ChenHsing/AID)

+ **LaMD: Latent Motion Diffusion for Video Generation** (23 Apr 2023)<details><summary>Yaosi Hu, Zhenzhong Chen, Chong Luo</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603)
[![citation](https://img.shields.io/badge/citation-16-blue.svg?paper=e1d5c8ee59031f19ea9979d05f6e92295a540f88)](https://www.semanticscholar.org/paper/e1d5c8ee59031f19ea9979d05f6e92295a540f88)

+ **EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture** (5 Jul 2024)<details><summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, et al.</summary>Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18991)
[![citation](https://img.shields.io/badge/citation-26-blue.svg?paper=40122a222374504fda4997ef6204dcdcee1678da)](https://www.semanticscholar.org/paper/40122a222374504fda4997ef6204dcdcee1678da)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://easyanimate.github.io/)
[![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star)](https://github.com/aigc-apps/EasyAnimate)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/alibaba-pai/EasyAnimate)

+ **AtomoVideo: High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Litong Gong, Yiran Zhu, Weijie Li, et al.</summary>Xiaoyang Kang, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01800)
[![citation](https://img.shields.io/badge/citation-11-blue.svg?paper=1f2dfc535180bf6806b13086fe4f25d622483ada)](https://www.semanticscholar.org/paper/1f2dfc535180bf6806b13086fe4f25d622483ada)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://atomo-video.github.io/)

+ **TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models** (25 Mar 2024)<details><summary>[CVPR 2024] Zhongwei Zhang, Fuchen Long, Yingwei Pan, et al.</summary>Zhaofan Qiu, Ting Yao, Yang Cao, Tao Mei</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_TRIP_Temporal_Residual_Learning_with_Image_Noise_Prior_for_Image-to-Video_CVPR_2024_paper.html)
[![citation](https://img.shields.io/badge/citation-17-blue.svg?paper=c87c910063dfaba7b5abcf49989a6e9ae1d9d7ce)](https://www.semanticscholar.org/paper/c87c910063dfaba7b5abcf49989a6e9ae1d9d7ce)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://trip-i2v.github.io/TRIP/)


+ **Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation** (12 Feb 2025)<details><summary>[ICLR 2025] Xiaojuan Wang, Boyang Zhou, Brian Curless, et al.</summary>Ira Kemelmacher-Shlizerman, Aleksander Holynski, Steven M. Seitz</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15239)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=d6837b60f100b40c5ee2284fbee3134a904c0603)](https://www.semanticscholar.org/paper/d6837b60f100b40c5ee2284fbee3134a904c0603)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://svd-keyframe-interpolation.github.io/)
[![Code](https://img.shields.io/github/stars/jeanne-wang/svd_keyframe_interpolation.svg?style=social&label=Star)](https://github.com/jeanne-wang/svd_keyframe_interpolation)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/svd_keyframe_interpolation)

+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** (30 Oct 2023)<details><summary>Haoxin Chen, Menghan Xia, Yingqing He, et al.</summary>Yong Zhang, Xiaodong Cun, Shaoshu Yang, Jinbo Xing, Yaofang Liu, Qifeng Chen, Xintao Wang, Chao Weng, Ying Shan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![citation](https://img.shields.io/badge/citation-244-blue.svg?paper=1891c3756f870d902a0b793a1dcd5cc34c778612)](https://www.semanticscholar.org/paper/1891c3756f870d902a0b793a1dcd5cc34c778612)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter2/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/VideoCrafter/VideoCrafter)

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

+ **MoVideo: Motion-Aware Video Generation with Diffusion Model** (29 Jul 2024)<details><summary>[ECCV 2024] Jingyun Liang, Yuchen Fan, Kai Zhang, et al.</summary>Radu Timofte, Luc Van Gool, Rakesh Ranjan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)
[![citation](https://img.shields.io/badge/citation-3-blue.svg?paper=b57a0f46b4b5148b8bdd3cc2969d4ed43333bda0)](https://www.semanticscholar.org/paper/b57a0f46b4b5148b8bdd3cc2969d4ed43333bda0)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyunliang.github.io/MoVideo/)

+ **Synthesizing Videos from Images for Image-to-Video Adaptation** (27 Oct 2023)<details><summary>[ACM MM 2023] Junbao Zhuo, Xingyu Zhao, Shuhui Wang, et al.</summary>Huimin Ma, Qingming Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3581783.3611897)
[![citation](https://img.shields.io/badge/citation-4-blue.svg?paper=b26d4c0b127e4a3e81b94cad4b2c8ecb0dda1bd9)](https://www.semanticscholar.org/paper/b26d4c0b127e4a3e81b94cad4b2c8ecb0dda1bd9)
[![Code](https://img.shields.io/github/stars/junbaoZHUO/ST-I2V.svg?style=social&label=Star)](https://github.com/junbaoZHUO/ST-I2V)

+ **Prompt Image to Life: Training-Free Text-Driven Image-to-Video Generation** (2023)<details><summary>Jinxiu Liu, Yuan Yao, Bingwen Zhu, et al.</summary>Fanyi Wang, Weijian Luo, Jingwen Su,
Yanhao Zhang, Yuxiao Wang, Liyuan Ma, Qi Liu, Jiebo Luo, Guo-Jun Qi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.cs.rochester.edu/u/yyao39/files/PiLife.pdf)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=ed1dfe38b52c0c1cdd8b20f860520858f28ed9a6)](https://www.semanticscholar.org/paper/ed1dfe38b52c0c1cdd8b20f860520858f28ed9a6)

+ **TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models** (25 Apr 2024)<details><summary>[CVPR 2024] Haomiao Ni, Bernhard Egger, Suhas Lohit, et al.</summary>Anoop Cherian, Ye Wang, Toshiaki Koike-Akino, Sharon X. Huang, Tim K. Marks</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)
[![citation](https://img.shields.io/badge/citation-9-blue.svg?paper=5cbe42a201e2d1a90ac83dadc78afec6a3d20fec)](https://www.semanticscholar.org/paper/5cbe42a201e2d1a90ac83dadc78afec6a3d20fec)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.merl.com/demos/TI2V-Zero)
[![Code](https://img.shields.io/github/stars/merlresearch/TI2V-Zero.svg?style=social&label=Star)](https://github.com/merlresearch/TI2V-Zero)


+ **UniVG: Towards UNIfied-modal Video Generation** (17 Jan 2024)<details><summary>Ludan Ruan, Lei Tian, Chuanwei Huang, et al.</summary>Xu Zhang, Xinyan Xiao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=147ceee32c1e33f332ac7b2dcabf397788a01d1a)](https://www.semanticscholar.org/paper/147ceee32c1e33f332ac7b2dcabf397788a01d1a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://univg-baidu.github.io/)

+ **Adapting Image-to-Video Diffusion Models for Large-Motion Frame Interpolation** (17 Feb 2025)<details><summary>Luoxu Jin, Hiroshi Watanabe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17042)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=25fc7b5cdfaf5ecca730115671788dbde95c96c4)](https://www.semanticscholar.org/paper/25fc7b5cdfaf5ecca730115671788dbde95c96c4)


+ **STIV: Scalable Text and Image Conditioned Video Generation** (10 Dec 2024) <details><summary>Zongyu Lin, Wei Liu, Chen Chen, et al.</summary>
Zongyu Lin, Wei Liu, Chen Chen, Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07730)

+ **Through-The-Mask: Mask-based Motion Trajectories for Image-to-Video Generation** (6 Jan 2025) <details><summary>Guy Yariv, Yuval Kirstain, Amit Zohar, et al.</summary>
Guy Yariv, Yuval Kirstain, Amit Zohar, Shelly Sheynin, Yaniv Taigman, Yossi Adi, Sagie Benaim, Adam Polyak</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03059)

+ **Tuning-Free Noise Rectification for High Fidelity Image-to-Video Generation** (5 Mar 2024) <details><summary>Weijie Li, Litong Gong, Yiran Zhu, et al.</summary>
Weijie Li, Litong Gong, Yiran Zhu, Fanda Fan, Biao Wang, Tiezheng Ge, Bo Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02827)

+ **Decouple Content and Motion for Conditional Image-to-Video Generation** (24 Nov 2023) <details><summary>Cuifeng Shen, Yulu Gan, Chen Chen, et al.</summary>
Cuifeng Shen, Yulu Gan, Chen Chen, Xiongwei Zhu, Lele Cheng, Tingting Gao, Jinzhi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)

+ **MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation** (8 Dec 2024) <details><summary>Shuwei Shi, Biao Gong, Xi Chen, et al.</summary>
Shuwei Shi, Biao Gong, Xi Chen, Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05848)

+ **MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation** (6 Feb 2025) <details><summary>Jinbo Xing, Long Mai, Cusuh Ham, et al.</summary>
Jinbo Xing, Long Mai, Cusuh Ham, Jiahui Huang, Aniruddha Mahapatra, Chi-Wing Fu, Tien-Tsin Wong, Feng Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.04299)

+ **AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction** (10 Jun 2024) <details><summary>Zhen Xing, Qi Dai, Zejia Weng, et al.</summary>
Zhen Xing, Qi Dai, Zejia Weng, Zuxuan Wu, Yu-Gang Jiang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06465)

+ **LaMD: Latent Motion Diffusion for Video Generation** (23 Apr 2023) <details><summary>Yaosi Hu, Zhenzhong Chen, Chong Luo</summary>
Yaosi Hu, Zhenzhong Chen, Chong Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603)

+ **SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation** (7 Nov 2024) <details><summary>Koichi Namekata, Sherwin Bahmani, Ziyi Wu, et al.</summary>
Koichi Namekata, Sherwin Bahmani, Ziyi Wu, Yash Kant, Igor Gilitschenski, David B. Lindell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04033)
[![Code](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social&label=Star)](https://github.com/Kmcode1/SG-I2V)

+ **EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture** (29 May 2024) <details><summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, et al.</summary>
Jiaqi Xu, Xinyi Zou, Kunzhe Huang, Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18991)
[![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star)](https://github.com/aigc-apps/EasyAnimate)

+ **AtomoVideo: High Fidelity Image-to-Video Generation** (4 Mar 2024) <details><summary>Litong Gong, Yiran Zhu, Weijie Li, et al.</summary>
Litong Gong, Yiran Zhu, Weijie Li, Xiaoyang Kang, Biao Wang, Tiezheng Ge, Bo Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01800)

+ **TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models** (25 Mar 2024) <details><summary>Zhongwei Zhang, Fuchen Long, Yingwei Pan, et al.</summary>
Zhongwei Zhang, Fuchen Long, Yingwei Pan, Zhaofan Qiu, Ting Yao, Yang Cao, Tao Mei</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17005)

+ **CamViG: Camera Aware Image-to-Video Generation with Multimodal Transformers** (21 May 2024) <details><summary>Andrew Marmon, Grant Schindler, José Lezama, et al.</summary>
Andrew Marmon, Grant Schindler, José Lezama, Dan Kondratyuk, Bryan Seybold, Irfan Essa</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.13195)

+ **Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation** (27 Aug 2024) <details><summary>Xiaojuan Wang, Boyang Zhou, Brian Curless, et al.</summary>
Xiaojuan Wang, Boyang Zhou, Brian Curless, Ira Kemelmacher-Shlizerman, Aleksander Holynski, Steven M. Seitz</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15239)
[![Code](https://img.shields.io/github/stars/jeanne-wang/svd_keyframe_interpolation.svg?style=social&label=Star)](https://github.com/jeanne-wang/svd_keyframe_interpolation)

+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** (30 Oct 2023) <details><summary>Haoxin Chen, Menghan Xia, Yingqing He, et al.</summary>
Haoxin Chen, Menghan Xia, Yingqing He, Yong Zhang, Xiaodong Cun, Shaoshu Yang, Jinbo Xing, Yaofang Liu, Qifeng Chen, Xintao Wang, Chao Weng, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)

+ **Lumiere: A Space-Time Diffusion Model for Video Generation** (23 Jan 2024) <details><summary>Omer Bar-Tal, Hila Chefer, Omer Tov, et al.</summary>
Omer Bar-Tal, Hila Chefer, Omer Tov, Charles Herrmann, Roni Paiss, Shiran Zada, Ariel Ephrat, Junhwa Hur, Guanghui Liu, Amit Raj, Yuanzhen Li, Michael Rubinstein, Tomer Michaeli, Oliver Wang, Deqing Sun, Tali Dekel, Inbar Mosseri</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.12945)

+ **Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model** (22 Jun 2024) <details><summary>Min Zhao, Hongzhou Zhu, Chendong Xiang, et al.</summary>
Min Zhao, Hongzhou Zhu, Chendong Xiang, et al.</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.12533)
[![Code](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social&label=Star)](https://github.com/thu-ml/cond-image-leakage)

+ **MoVideo: Motion-Aware Video Generation with Diffusion Models** (19 Nov 2023) <details><summary>Jingyun Liang, Yuchen Fan, Kai Zhang, et al.</summary>
Jingyun Liang, Yuchen Fan, Kai Zhang, Radu Timofte, Luc Van Gool, Rakesh Ranjan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)

+ **Synthesizing Videos from Images for Image-to-Video Adaptation** (27 Oct 2023) <details><summary>Junbao Zhuo, Xingyu Zhao, Shuhui Wang, et al.</summary>
Junbao Zhuo, Xingyu Zhao, Shuhui Wang, Huimin Ma, Qingming Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3581783.3611897)

+ **TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models** (25 Apr 2024) <details><summary>Haomiao Ni, Bernhard Egger, Suhas Lohit, et al.</summary>
Haomiao Ni, Bernhard Egger, Suhas Lohit, Anoop Cherian, Ye Wang, Toshiaki Koike-Akino, Sharon X. Huang, Tim K. Marks</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)

+ **Ultrasound Image-to-Video Synthesis via Latent Dynamic Diffusion Models** (19 Mar 2025) <details><summary>Tingxiu Chen, Yilei Shi, Zixuan Zheng, et al.</summary>
Tingxiu Chen, Yilei Shi, Zixuan Zheng, Bingcong Yan, Jingliang Hu, Xiao Xiang Zhu, Lichao Mou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14966)

+ **UniVG: Towards UNIfied-modal Video Generation** (17 Jan 2024) <details><summary>Ludan Ruan, Lei Tian, Chuanwei Huang, et al.</summary>
Ludan Ruan, Lei Tian, Chuanwei Huang, Xu Zhang, Xinyan Xiao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)

+ **Adapting Image-to-Video Diffusion Models for Large-Motion Frame Interpolation** (22 Dec 2024) <details><summary>Luoxu Jin, Hiroshi Watanabe</summary>
Luoxu Jin, Hiroshi Watanabe</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17042)



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

+ **Sketching the Future (STF): Applying Conditional Control Techniques to Text-to-Video Models** (10 May 2023)<details><summary>Rohan Dhesikan, Vignesh Rajmohan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05845)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=1d66f30782a13c1d775c690e0bc329324f188ced)](https://www.semanticscholar.org/paper/1d66f30782a13c1d775c690e0bc329324f188ced)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sketchingthefuture.github.io/)
[![Code](https://img.shields.io/github/stars/rohandkn/skribble2vid.svg?style=social&label=Star)](https://github.com/rohandkn/skribble2vid)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://docs.google.com/forms/d/e/1FAIpQLSd9EGien53IkxOlbPkUx9n9ANu2N_FG6ySJaZASr_A1VCdxUQ/viewform?usp=sf_link)

+ **SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models** (28 Nov 2023)<details><summary>Yuwei Guo, Ceyuan Yang, Anyi Rao, et al.</summary>
Maneesh Agrawala, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
[![citation](https://img.shields.io/badge/citation-89-blue.svg?paper=40626a059bcd8d3e7f364b410f831b9baf997b0c)](https://www.semanticscholar.org/paper/40626a059bcd8d3e7f364b410f831b9baf997b0c)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoyww.github.io/projects/SparseCtrl/)
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl.svg?style=social&label=Star)](https://github.com/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl)


+ **EasyControl: Transfer ControlNet to Video Diffusion for Controllable Generation and Interpolation** (16 Sep 2024)<details><summary>Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary>
Haoyu Zhao, Yuanfan Guo, Jianhua Han, Hang Xu, Xiaodan Liang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13005)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=a0a6a4ac75dcb5aa25e662a91361490836b0fd1c)](https://www.semanticscholar.org/paper/a0a6a4ac75dcb5aa25e662a91361490836b0fd1c)


+ **VidSketch: Hand-drawn Sketch-Driven Video Generation with Diffusion Control** (17 Feb 2025)<details><summary>Lifan Jiang, Shuang Chen, Boxi Wu, et al.</summary>
Xiaotong Guan, Jiahui Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01101)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=760f115fb3cb45de0ee8353c44c934b50af4c146)](https://www.semanticscholar.org/paper/760f115fb3cb45de0ee8353c44c934b50af4c146)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://csfufu.github.io/vid_sketch/)
[![Code](https://img.shields.io/github/stars/CSfufu/VidSketch.svg?style=social&label=Star)](https://github.com/CSfufu/VidSketch)


+ **A Recipe for Scaling up Text-to-Video Generation with Text-free Videos** (25 Dec 2023)<details><summary>[CVPR 2024] Xiang Wang, Shiwei Zhang, Hangjie Yuan, et al.</summary>
Zhiwu Qing, Biao Gong, Yingya Zhang, Yujun Shen, Changxin Gao, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05845)
[![citation](https://img.shields.io/badge/citation-22-blue.svg?paper=a40e68121e7887fc49e3e9b35f8acc7ce7dc9c89)](https://www.semanticscholar.org/paper/a40e68121e7887fc49e3e9b35f8acc7ce7dc9c89)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tf-t2v.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)


+ **Make Pixels Dance: High-Dynamic Video Generation** (18 Nov 2023)<details><summary>[CVPR 2024] Yan Zeng, Guoqiang Wei, Jiani Zheng, et al.</summary>
Jiaxin Zou, Yang Wei, Yuchen Zhang, Hang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10982)
[![citation](https://img.shields.io/badge/citation-80-blue.svg?paper=8467c119251ea48204586d1c3c67aa8fb781f7c4)](https://www.semanticscholar.org/paper/8467c119251ea48204586d1c3c67aa8fb781f7c4)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://arxiv.org/abs/2311.10982)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://makepixelsdance.github.io/demo.html)

+ **LVCD: Reference-based Lineart Video Colorization with Diffusion Models** (19 Sep 2024)<details><summary>[ACM TOG and SIGGRAPH Asia 2024] Zhitong Huang, Mohan Zhang, Jing Liao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12960)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=97705d8c14345882683edefc367e830f94b3415e)](https://www.semanticscholar.org/paper/97705d8c14345882683edefc367e830f94b3415e)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://luckyhzt.github.io/lvcd)
[![Code](https://img.shields.io/github/stars/luckyhzt/LVCD.svg?style=social&label=Star)](https://github.com/luckyhzt/LVCD)


+ **MotionClone: Training-Free Motion Cloning for Controllable Video Generation** (22 Oct 2024)<details><summary>Pengyang Ling, Jiazi Bu, Pan Zhang, et al.</summary>
Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian Chen, Jiaqi Wang, Yi Jin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338)
[![citation](https://img.shields.io/badge/citation-30-blue.svg?paper=e872ad446a3c6986feea7bd5cbd5b5754c068ab6)](https://www.semanticscholar.org/paper/e872ad446a3c6986feea7bd5cbd5b5754c068ab6)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bujiazi.github.io/motionclone.github.io/)
[![Code](https://img.shields.io/github/stars/LPengYang/MotionClone.svg?style=social&label=Star)](https://github.com/LPengYang/MotionClone)

+ **VideoLCM: Video Latent Consistency Model** (14 Dec 2023)<details><summary>Xiang Wang, Shiwei Zhang, Han Zhang,  et al.</summary>
Yu Liu, Yingya Zhang, Changxin Gao, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09109)
[![citation](https://img.shields.io/badge/citation-44-blue.svg?paper=e97b37c3d4c73912e19c5d2fc664ee2fb7a55c46)](https://www.semanticscholar.org/paper/e97b37c3d4c73912e19c5d2fc664ee2fb7a55c46)

+ **Open-Sora Plan: Open-Source Large Video Generation Model** (28 Nov 2024)<details><summary>Bin Lin, Yunyang Ge, Xinhua Cheng, et al.</summary>
Zongjian Li, Bin Zhu, Shaodong Wang, Xianyi He, Yang Ye, Shenghai Yuan, Liuhan Chen, Tanghui Jia, Junwu Zhang, Zhenyu Tang, Yatian Pang, Bin She, Cen Yan, Zhiheng Hu, Xiaoyi Dong, Lin Chen, Zhang Pan, Xing Zhou, Shaoling Dong, Yonghong Tian, Li Yuan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00131)
[![citation](https://img.shields.io/badge/citation-37-blue.svg?paper=ae588b682150047b5f8adc3d73fa09a9fdf17edb)](https://www.semanticscholar.org/paper/ae588b682150047b5f8adc3d73fa09a9fdf17edb)
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** (13 Mar 2025)<details><summary>[ICLR 2025] Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>
Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)
[![citation](https://img.shields.io/badge/citation-82-blue.svg?paper=3fc6184c72fd55b67409ef87493c333f15a33180)](https://www.semanticscholar.org/paper/3fc6184c72fd55b67409ef87493c333f15a33180)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/)
[![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/hehao13/CameraCtrl-svd)

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

+ **AniDoc: Animation Creation Made Easier** (30 Jan 2025)<details><summary>[CVPR 2025] Yihao Meng, Hao Ouyang, Hanlin Wang, et al.</summary>
Qiuyu Wang, Wen Wang, Ka Leong Cheng, Zhiheng Liu, Yujun Shen, Huamin Qu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14173)
[![citation](https://img.shields.io/badge/citation-5-blue.svg?paper=95c7b164bc149215b62adb974762e20eb637d46f)](https://www.semanticscholar.org/paper/95c7b164bc149215b62adb974762e20eb637d46f)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yihao-meng.github.io/AniDoc_demo/)
[![Code](https://img.shields.io/github/stars/ant-research/AniDoc.svg?style=social&label=Star)](https://github.com/ant-research/AniDoc)

+ **TaleCrafter: Interactive Story Visualization with Multiple Characters** (30 May 2023)<details><summary>[SIGGRAPH Asia 2023] Yuan Gong, Youxin Pang, Xiaodong Cun, et al.</summary>
Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247)
[![citation](https://img.shields.io/badge/citation-39-blue.svg?paper=32fad3ebb40bc9e827ad8ebb250dfabc5006a17a)](https://www.semanticscholar.org/paper/32fad3ebb40bc9e827ad8ebb250dfabc5006a17a)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/TaleCrafter/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/TaleCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/TaleCrafter)


+ **Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model** (24 May 2024)<details><summary>[ICLR 2025] Han Lin, Jaemin Cho, Abhay Zala, et al.</summary>
Mohit Bansal</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.09967)
[![citation](https://img.shields.io/badge/citation-15-blue.svg?paper=bcbef7546696cd2d102b8b440702614876dda5aa)](https://www.semanticscholar.org/paper/bcbef7546696cd2d102b8b440702614876dda5aa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ctrl-adapter.github.io/)
[![Code](https://img.shields.io/github/stars/HL-hanlin/Ctrl-Adapter.svg?style=social&label=Star)](https://github.com/HL-hanlin/Ctrl-Adapter)



### 🤲 Language-Gesture Controlled

## 🔸 Multi Control/I2V

### 🖼️ + 🛤️ Image + Traj
+ **Boximator: Generating Rich and Controllable Motions for Video Synthesis** (30 Mar 2025)<details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2402.01566)

+ **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (30 Mar 2025)<details><summary>Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)
[![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)

+ **DragNuwa (Image+text_Traj)** (30 Mar 2025)<details><summary>Shengming Yin, Chenfei Wu, Jian Liang, et al.</summary>Jie Shi, Houqiang Li, Gong Ming, Nan Duan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2308.08089)
[![Code](https://img.shields.io/github/stars/ProjectNUWA/DragNUWA.svg?style=social&label=Star)](https://github.com/ProjectNUWA/DragNUWA)

+ **MCDiff Motion-Conditioned Diffusion Model for Controllable Video Synthesis (Start Frame+Input Strokes)** (30 Mar 2025)<details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.11475)

+ **SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation** (30 Mar 2025)<details><summary>Koichi Namekata, Sherwin Bahmani, Ziyi Wu, et al.</summary>Yash Kant, Igor Gilitschenski, David B. Lindell</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2411.04989)
[![Code](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social&label=Star)](https://github.com/Kmcode1/SG-I2V)

+ **Draganything: Motion control for anything using entity representation** (30 Mar 2025)<details><summary>Weijia Wu, Zhuang Li, Yuchao Gu, et al.</summary>Rui Zhao, Yefei He, David Junhao Zhang, Mike Zheng Shou, Yan Li, Tingting Gao, Di Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)
[![Code](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)

+ **TrackGo: A Flexible and Efficient Method for Controllable Video Generation** (30 Mar 2025)<details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2408.11475)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories (frame+track+text)** (30 Mar 2025)<details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1)

+ **InTraGen: Trajectory-controlled Video Generation for Object Interactions (frame+track)** (30 Mar 2025)<details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.16804)
[![Code](https://img.shields.io/github/stars/insait-institute/InTraGen.svg?style=social&label=Star)](https://github.com/insait-institute/InTraGen)

+ **ReVideo: Remake a Video with Motion and Content** (30 Mar 2025)<details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>
[![Paper](https://img.shields.io/badge/NeurIPS-b31b1b.svg)](https://proceedings.neurips.cc)
[![Code](https://img.shields.io/github/stars/MC-E/ReVideo.svg?style=social&label=Star)](https://github.com/MC-E/ReVideo)

+ **LeviTor: 3D Trajectory Oriented Image-to-Video Synthesis** (30 Mar 2025)<details><summary>Hanlin Wang, Hao Ouyang, Qiuyu Wang, et al.</summary>Wen Wang, Ka Leong Cheng, Qifeng Chen, Yujun Shen, Limin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.15214)
[![Code](https://img.shields.io/github/stars/ant-research/LeviTor.svg?style=social&label=Star)](https://github.com/ant-research/LeviTor)

+ **ObjCtrl-2.5D: Training-free Object Control with Camera Poses** (30 Mar 2025)<details><summary>Zhouxia Wang, Yushi Lan, Shangchen Zhou, Chen Change Loy</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.07721)
[![Code](https://img.shields.io/github/stars/wzhouxiff/ObjCtrl-2.5D.svg?style=social&label=Star)](https://github.com/wzhouxiff/ObjCtrl-2.5D)

+ **C-Drag: Chain-of-Thought Driven Motion Controller for Video Generation** (30 Mar 2025)<details><summary>Yuhao Li, Mirana Claire Angel, Salman Khan, et al.</summary>Yu Zhu, Jinqiu Sun, Yanning Zhang, Fahad Shahbaz Khan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.19868)
[![Code](https://img.shields.io/github/stars/WesLee88524/C-Drag-Official-Repo.svg?style=social&label=Star)](https://github.com/WesLee88524/C-Drag-Official-Repo)

+ **DragEntity: Trajectory Guided Video Generation using Entity and Positional Relationships** (30 Mar 2025)<details><summary>Zhang Wan, Sheng Tang, Jiawei Wei</summary></details>
[![Paper](https://img.shields.io/badge/ACM-b31b1b.svg)](https://dl.acm.org/doi/pdf/10.1145/3664647.3681567)

+ **OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation** (30 Mar 2025)<details><summary>Weiqi Li, Shijie Zhao, Chong Mou, et al.</summary>Xuhan Sheng, Zhenyu Zhang, Qian Wang, Junlin Li, Li Zhang, Jian Zhang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2412.09623)
[![Code](https://img.shields.io/github/stars/lwq20020127/OmniDrag.svg?style=social&label=Star)](https://github.com/lwq20020127/OmniDrag)

+ **MotionBridge: Dynamic Video Inbetweening with Flexible Controls** (30 Mar 2025)<details><summary>Maham Tanveer, Yang Zhou, Simon Niklaus, et al.</summary>Ali Mahdavi Amiri, Hao Zhang, Krishna Kumar Singh, Nanxuan Zhao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.13190v1)

+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (30 Mar 2025)<details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.14864)
[![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)

+ **Tora: Trajectory-oriented Diffusion Transformer for Video Generation** (30 Mar 2025)<details><summary>Zhenghao Zhang, Junchao Liao, Menghao Li, et al.</summary>ZuoZhuo Dai, Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21705)
[![Code](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social&label=Star)](https://github.com/alibaba/Tora)

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (30 Mar 2025)<details><summary>Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>Yong Zhang, Ying Shan, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.20222)
[![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)

+ **IMAGE CONDUCTOR: PRECISION CONTROL FOR INTERACTIVE VIDEO SYNTHESIS** (30 Mar 2025)<details><summary>Yaowei Li, Xintao Wang, Zhaoyang Zhang, et al.</summary>Zhouxia Wang, Ziyang Yuan, Liangbin Xie, Yuexian Zou, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.15339)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/liyaowei-stu/ImageConductor)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (30 Mar 2025)<details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05020)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** (30 Mar 2025)<details><summary>Wanquan Feng, Tianhao Qi, Jiawei Liu, et al.</summary>Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17765)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://wanquanf.github.io/I2VControl)

+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (30 Mar 2025)<details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07531)
### 🖼️ + 📸 Image + Camera
+ **RealCam-I2V: Real-World Image-to-Video Generation with Interactive Complex Camera Control** (30 Mar 2025)<details><summary>Teng Li, Guangcong Zheng, Rui Jiang, et al.</summary>Shuigenzhan, Tao Wu, Yehao Lu, Yining Lin, Xi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10059)
[![Code](https://img.shields.io/github/stars/ZGCTroy/RealCam-I2V.svg?style=social&label=Star)](https://github.com/ZGCTroy/RealCam-I2V)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories (frame+track+text)** (30 Mar 2025)<details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1)

+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (30 Mar 2025)<details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2405.14864)
[![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)

+ **CamCo: Camera-Controllable 3D-Consistent Image-to-Video Generation** (30 Mar 2025)<details><summary>Dejia Xu, Weili Nie, Chao Liu, et al.</summary>Sifei Liu, Jan Kautz, Zhangyang Wang, Arash Vahdat</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.02509)

+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models** (30 Mar 2025)<details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary>Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2503.10592)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation (包含天t2v,i2v)** (30 Mar 2025)<details><summary>Hao He, Yinghao Xu, Yuwei Guo, et al.</summary>Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2404.02101)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)

+ **Optical Flow Meets Video Diffusion Model for Enhanced Camera-Controlled Video Synthesis** (30 Mar 2025)<details><summary>Wonjoon Jin, Qi Dai, Chong Luo, et al.</summary>Seung-Hwan Baek, Sunghyun Cho, POSTECH, Microsoft Research Asia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.08244)
[![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)

+ **CamI2V: Camera-Controlled Image-to-Video Diffusion Model** (30 Mar 2025)<details><summary>Guangcong Zheng, Teng Li, Rui Jiang, et al.</summary>Yehao Lu, Tao Wu, Xi Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2410.15957)

+ **Training-free Camera Control for Video Generation** (30 Mar 2025)<details><summary>Chen Hou, Zhibo Chen</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2406.10126)

+ **Trajectory Attention: Enhancing Video Generation with Fine-Grained Motion Control** (30 Mar 2025)<details><summary>Zeqi Xiao, Wenqi Ouyang, Yifan Zhou, et al.</summary>Shuai Yang, Lei Yang, Jianlou Si, Xingang Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19324)

+ **DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion** (30 Mar 2025)<details><summary>Wenqiang Sun, Shuo Chen, Fangfu Liu, et al.</summary>Zilong Chen, Yueqi Duan, Jun Zhang, Yikai Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04928)
[![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Star)](https://github.com/wenqsun/DimensionX)

+ **I2V3D: Controllable Image-to-Video Generation with 3D Guidance** (30 Mar 2025)<details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.09733)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (30 Mar 2025)<details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Miaomiao Cui, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2501.05020)
[![Code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** (30 Mar 2025)<details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.17765)

+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (30 Mar 2025)<details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.07531)

+ **I2VCONTROL-CAMERA: Precise Video Camera Control with Adjustable Motion Strength** (30 Mar 2025)<details><summary>Wanquan Feng, Jiawei Liu, Pengqi Tu, et al.</summary>Tianhao Qi, Mingzhen Sun, Tianxiang Ma, Songtao Zhao, Siyu Zhou, Qian He</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.06525)

+ **EgoSim: Egocentric Exploration in Virtual Worlds with Multi-modal Conditioning** (30 Mar 2025)<details><summary>Wei Yu, Songheng Yin, Steve Easterbrook, Animesh Garg</summary></details>
[![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/pdf?id=hN5h0hrQ6a)

+ **GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control** (30 Mar 2025)<details><summary>Xuanchi Ren, Tianchang Shen, Jiahui Huang, et al.</summary>Huan Ling, Yifan Lu, Merlin Nimier-David, Thomas Müller, Alexander Keller, Sanja Fidler, Jun Gao</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.03751)
[![Code](https://img.shields.io/github/stars/nv-tlabs/GEN3C.svg?style=social&label=Star)](https://github.com/nv-tlabs/GEN3C)

### 🛤️ + 📸 Traj + Camera

### 🖼️ + 🔊 Image + Audio

+ **EMO: Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions** (27 Feb 2024)<details><summary>Linrui Tian, Qi Wang, Bang Zhang, et al.</summary>
Linrui Tian, Qi Wang, Bang Zhang, Liefeng Bo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17485)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/EMO.svg?style=social&label=Star)](https://github.com/HumanAIGC/EMO)

+ **Sadtalker: Learning Realistic 3D Motion Coefficients for Stylized Audio-Driven Single Image Talking Face Animation** (22 Nov 2022)<details><summary>Wenxuan Zhang, Xiaodong Cun, Xuan Wang, et al.</summary>
Wenxuan Zhang, Xiaodong Cun, Xuan Wang, Yong Zhang, Xi Shen, Yu Guo, Ying Shan, Fei Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.12194)
  [![Code](https://img.shields.io/github/stars/OpenTalker/SadTalker.svg?style=social&label=Star)](https://github.com/OpenTalker/SadTalker)

+ **Float: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait**<details><summary>Taekyung Ki, Dongchan Min, Gyeongsu Chae</summary>
Taekyung Ki, Dongchan Min, Gyeongsu Chae</details>

  [![Paper](https://img.shields.io/badge/Website-0073b7.svg)](https://deepbrainai-research.github.io/float/)
  [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/deepbrainai-research/float)

+ **Float: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait**<details><summary>Taekyung Ki, Dongchan Min, Gyeongsu Chae</summary>
Taekyung Ki, Dongchan Min, Gyeongsu Chae</details>

  [![Paper](https://img.shields.io/badge/Website-0073b7.svg)](https://deepbrainai-research.github.io/float/)
  [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/deepbrainai-research/float)

+ **Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation**<details><summary>Mingwang Xu, Hui Li, Qingkun Su, et al.</summary>
Mingwang Xu, Hui Li, Qingkun Su, Hanlin Shang, Liwei Zhang, Ce Liu, Jingdong Wang, Yao Yao, Siyu Zhu</details>

  [![Code](https://img.shields.io/github/stars/fudan-generative-vision/hallo.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/hallo)

+ **VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior** (4 Dec 2023)<details><summary>Xusen Sun, Longhao Zhang, Hao Zhu, et al.</summary>
Xusen Sun, Longhao Zhang, Hao Zhu, Peng Zhang, Bang Zhang, Xinya Ji, Kangneng Zhou, Daiheng Gao, Liefeng Bo, Xun Cao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.01841)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/VividTalk.svg?style=social&label=Star)](https://github.com/HumanAIGC/VividTalk)

+ **VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time** (16 Apr 2024)<details><summary>Sicheng Xu, Guojun Chen, Yu-Xiao Guo, et al.</summary>
Sicheng Xu, Guojun Chen, Yu-Xiao Guo, Jiaolong Yang, Chong Li, Zhenyu Zang, Yizhong Zhang, Xin Tong, Baining Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10667)

+ **CyberHost: A One-stage Diffusion Framework for Audio-driven Talking Body Generation**<details><summary>Gaojie Lin, Jianwen Jiang, Chao Liang, et al.</summary>
Gaojie Lin, Jianwen Jiang, Chao Liang, Tianyun Zhong, Jiaqi Yang, Yanbo Zheng</details>

  [![Paper](https://img.shields.io/badge/Website-0073b7.svg)](https://cyberhost.github.io/)

+ **MuseTalk: Real-Time High-Fidelity Video Dubbing via Spatio-Temporal Sampling** (14 Oct 2024)<details><summary>Yue Zhang, Zhizhou Zhong, Minhao Liu, et al.</summary>
Yue Zhang, Zhizhou Zhong, Minhao Liu, Zhaokang Chen, Bin Wu, Yubin Zeng, Chao Zhan, Junxin Huang, Yingjie He, Wenjiang Zhou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10122)
  [![Code](https://img.shields.io/github/stars/TMElyralab/MuseTalk.svg?style=social&label=Star)](https://github.com/TMElyralab/MuseTalk)

+ **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models** (2 Feb 2025)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)

+ **A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild** (23 Aug 2020)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
Gaojie Lin, Jianwen Jiang, Jiaqi Yang, Zerong Zheng, Chao Liang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2008.10010)
  [![Code](https://img.shields.io/github/stars/Rudrabha/Wav2Lip.svg?style=social&label=Star)](https://github.com/Rudrabha/Wav2Lip)

+ **MakeItTalk: Speaker-Aware Talking-Head Animation**<details><summary>Yang Zhou, Xintong Han, Eli Shechtman, et al.</summary>
Yang Zhou, Xintong Han, Eli Shechtman, Jose Echevarria, Evangelos Kalogerakis, Dingzeyu Li</details>

  [![Code](https://img.shields.io/github/stars/yzhou359/MakeItTalk.svg?style=social&label=Star)](https://github.com/yzhou359/MakeItTalk)

+ **(CVPR 24) SyncTalk: The Devil😈 is in the Synchronization for Talking Head Synthesis** (29 Nov 2023)<details><summary>Ziqiao Peng, Wentao Hu, Yue Shi, et al.</summary>
Ziqiao Peng, Wentao Hu, Yue Shi, Xiangyu Zhu, Xiaomei Zhang, Hao Zhao, Jun He, Hongyan Liu, Zhaoxin Fan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17590)
  [![Code](https://img.shields.io/github/stars/ZiqiaoPeng/SyncTalk.svg?style=social&label=Star)](https://github.com/ZiqiaoPeng/SyncTalk)

+ **MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls** (30 Jul 2024)<details><summary>Yuxuan Bian, Ailing Zeng, Xuan Ju, et al.</summary>
Yuxuan Bian, Ailing Zeng, Xuan Ju, Xian Liu, Zhaoyang Zhang, Wei Liu, Qiang Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21136)
  [![Code](https://img.shields.io/github/stars/cure-lab/MotionCraft.svg?style=social&label=Star)](https://github.com/cure-lab/MotionCraft)

+ **Dreamtalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models** (15 Dec 2023)<details><summary>Yifeng Ma, Shiwei Zhang, Jiayu Wang, et al.</summary>
Yifeng Ma, Shiwei Zhang, Jiayu Wang, Xiang Wang, Yingya Zhang, Zhidong Deng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09767)
  [![Code](https://img.shields.io/github/stars/ali-vilab/dreamtalk.svg?style=social&label=Star)](https://github.com/ali-vilab/dreamtalk)

+ **Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation** (16 Jun 2024)<details><summary>Mingwang Xu, Hui Li, Qingkun Su, et al.</summary>Hanlin Shang, Liwei Zhang, Ce Liu, Jingdong Wang, Yao Yao, Siyu Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08801)
[![citation](https://img.shields.io/badge/citation-49-blue.svg?paper=17556ab7cd1bf0f6d385de30bb71f421625519ef)](https://www.semanticscholar.org/paper/17556ab7cd1bf0f6d385de30bb71f421625519ef)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/hallo/#/)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/hallo.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/hallo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/tts-hallo-talking-portrait)

+ **EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis** (2 Apr 2024)<details><summary>Shuai Tan, Bin Ji, Mengxiao Bi, et al.</summary>
Ye Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01647)
[![citation](https://img.shields.io/badge/citation-21-blue.svg?paper=f9511d7409f72ecaa2634af02f4be3a8643c4037)](https://www.semanticscholar.org/paper/f9511d7409f72ecaa2634af02f4be3a8643c4037)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tanshuai0219.github.io/EDTalk/)
[![Code](https://img.shields.io/github/stars/tanshuai0219/EDTalk.svg?style=social&label=Star)](https://github.com/tanshuai0219/EDTalk)

+ **EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions** (12 Jul 2024)<details><summary>[AAAI 2025] Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, et al.</summary>
Yuming Li, Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)
[![citation](https://img.shields.io/badge/citation-34-blue.svg?paper=d92c15b21777bd81b95622506e406e24a4de4bdb)](https://www.semanticscholar.org/paper/d92c15b21777bd81b95622506e406e24a4de4bdb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic.svg?style=social&label=Star)](https://github.com/antgroup/echomimic)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BadToBest/EchoMimic)

+ **AniPortrait: Audio-Driven Synthesis of Photorealistic Portrait Animation** (26 Mar 2024)<details><summary>Huawei Wei, Zejun Yang, Zhisheng Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17694)
[![citation](https://img.shields.io/badge/citation-54-blue.svg?paper=f81cb2475408ebf7b39268aff1cffd8c791ac5b2)](https://www.semanticscholar.org/paper/f81cb2475408ebf7b39268aff1cffd8c791ac5b2)
[![Code](https://img.shields.io/github/stars/Zejun-Yang/AniPortrait.svg?style=social&label=Star)](https://github.com/Zejun-Yang/AniPortrait)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/ZJYang/AniPortrait_official)

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

+ **MegActor-Σ: Unlocking Flexible Mixed-Modal Control in Portrait Animation with Diffusion Transformer** (27 Aug 2024)<details><summary>[AAAI 2025] Shurong Yang, Huadong Li, Juhao Wu, et al.</summary>
Minhao Jing, Linze Li, Renhe Ji, Jiajun Liang, Haoqiang Fan, Jin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14975)
[![citation](https://img.shields.io/badge/citation-7-blue.svg?paper=55139479ae7f68e7e3febda844331dd907990faa)](https://www.semanticscholar.org/paper/55139479ae7f68e7e3febda844331dd907990faa)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/megvii-research/MegActor.svg?style=social&label=Star)](https://github.com/megvii-research/MegActor)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://f4c5-58-240-80-18.ngrok-free.app/)

+ **Long-Term TalkingFace Generation via Motion-Prior Conditional Diffusion Model** (13 Feb 2025)<details><summary>Fei Shen, Cong Wang, Junyao Gao, et al.</summary>
Qin Guo, Jisheng Dang, Jinhui Tang, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.09533)
[![citation](https://img.shields.io/badge/citation-6-blue.svg?paper=ddddfcaf88c6b0ea24316cfce2d6838d8d19e563)](https://www.semanticscholar.org/paper/ddddfcaf88c6b0ea24316cfce2d6838d8d19e563)

+ **SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion** (17 Feb 2025)<details><summary>Junxian Ma, Shiwen Wang, Jian Yang, et al.</summary>
Junyi Hu, Jian Liang, Guosheng Lin, Jingbo chen, Kai Li, Yu Meng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11515)
[![citation](https://img.shields.io/badge/citation-2-blue.svg?paper=601d15cdf802fb45d83e8c88ef0ae8acd261dc35)](https://www.semanticscholar.org/paper/601d15cdf802fb45d83e8c88ef0ae8acd261dc35)

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


+ **Cafe-Talk: Generating 3D Talking Face Animation with Multimodal Coarse- and Fine-grained Control** (14 Mar 2025)<details><summary>[ICLR 2025] Hejia Chen, Haoxian Zhang, Shoulong Zhang, et al.</summary>
Xiaoqiang Liu, Sisi Zhuang, Yuan Zhang, Pengfei Wan, Di Zhang, Shuai Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14517)
[![citation](https://img.shields.io/badge/citation-1-blue.svg?paper=6f7f74bb2d4ab7decbeec23b13ac814de41c86fb)](https://www.semanticscholar.org/paper/6f7f74bb2d4ab7decbeec23b13ac814de41c86fb)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://harryxd2018.github.io/cafe-talk/)

+ **ChatAnyone: Stylized Real-time Portrait Video Generation with Hierarchical Motion Diffusion Model** (27 Mar 2025)<details><summary>Jinwei Qi, Chaonan Ji, Sheng Xu, et al.</summary>
Peng Zhang, Bang Zhang, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21144)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=9045629ae00382f73ffd3a8c4772aa4858260c27)](https://www.semanticscholar.org/paper/9045629ae00382f73ffd3a8c4772aa4858260c27)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/chat-anyone/)

+ **Towards High-fidelity 3D Talking Avatar with Personalized Dynamic Texture** (1 Mar 2025)<details><summary>[CVPR 2025] Xuanchen Li, Jianyu Wang, Yuhao Cheng, et al.</summary>
Yikun Zeng, Xingyu Ren, Wenhan Zhu, Weiming Zhao, Yichao Yan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00495)
[![citation](https://img.shields.io/badge/citation-0-blue.svg?paper=0b76dff851ca7196ca68f05f246332f16a74cf30)](https://www.semanticscholar.org/paper/0b76dff851ca7196ca68f05f246332f16a74cf30)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xuanchenli.github.io/TexTalk/)
[![Code](https://img.shields.io/github/stars/XuanchenLi/TexTalk.svg?style=social&label=Star)](https://github.com/XuanchenLi/TexTalk)

### 🎥 + 📸 Video + Camera
+ **ReCapture: Generative Video Camera Controls for User-Provided Videos using Masked Video Fine-Tuning** (11 Nov 2024)<details><summary>David Junhao Zhang, Roni Paiss, Shiran Zada, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.05003)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://generative-video-camera-controls.github.io/)
+ **Reangle-A-Video: 4D Video Generation as Video-to-Video Translation** <details><summary>Hyeonho Jeong, Suhyeon Lee, Jong Chul Ye</summary></details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyeonho99.github.io/reangle-a-video/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/HyeonHo99/Reangle-Video)
+ **Redirecting Camera Trajectory for Monocular Videos via Diffusion Models** (25 Mar 2025)<details><summary>Mark YU, Wenbo Hu, Jinbo Xing, et al.</summary></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.05638)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://trajectorycrafter.github.io/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/TrajectoryCrafter/TrajectoryCrafter)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://huggingface.co/spaces/Doubiiu/TrajectoryCrafter)
+ **AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers** <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, et al.</summary></details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/ac3d/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)
+ **MotionDirector: Motion Customization of Text-to-Video Diffusion Models** <details><summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, et al.</summary></details>
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/MotionDirector/)
[![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)

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
+ **DreamVideo-2: Zero-Shot Subject-Driven Video Customization with Precise Motion Control** (17 Oct 2024)<details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, et al.</summary>
  Yujie Wei, Shiwei Zhang, Hangjie Yuan, Xiang Wang, Haonan Qiu, Rui Zhao, Yutong Feng, Feng Liu, Zhizhong Huang, Jiaxin Ye, Yingya Zhang, Hongming Shan</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13830)

+ **Moonshot: Towards Controllable Video Generation and Editing with Multimodal Conditions** (3 Jan 2024)<details><summary>David Junhao Zhang, Dongxu Li, Hung Le, et al.</summary>
  David Junhao Zhang, Dongxu Li, Hung Le, Mike Zheng Shou, Caiming Xiong, Doyen Sahoo</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)

+ **MotionCharacter: Identity-Preserving and Motion Controllable Human Video Generation** (27 Nov 2024)<details><summary>Haopeng Fang, Di Qiu, Binjie Mao, et al.</summary>
  Haopeng Fang, Di Qiu, Binjie Mao, Pengfei Yan, He Tang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18281)

+ **Video ControlNet: Towards Temporally Consistent Synthetic-to-Real Video Translation Using Conditional Image Diffusion Models** (30 May 2023)<details><summary>Ernie Chu, Shuo-Yen Lin, Jun-Cheng Chen</summary>
  Ernie Chu, Shuo-Yen Lin, Jun-Cheng Chen</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.19193)

+ **VideoComposer: Compositional Video Synthesis with Motion Controllability** (3 Jun 2023)<details><summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, et al.</summary>
  Xiang Wang, Hangjie Yuan, Shiwei Zhang, Dayou Chen, Jiuniu Wang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
  [![Code](https://img.shields.io/github/stars/damo-vilab/videocomposer.svg?style=social&label=Star)](https://github.com/damo-vilab/videocomposer)

+ **ControlVideo: Conditional Control for One-shot Text-driven Video Editing and Beyond** (26 May 2023)<details><summary>Min Zhao, Rongzhen Wang, Fan Bao, et al.</summary>
  Min Zhao, Rongzhen Wang, Fan Bao, Chongxuan Li, Jun Zhu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.17098)
  [![Code](https://img.shields.io/github/stars/thu-ml/controlvideo.svg?style=social&label=Star)](https://github.com/thu-ml/controlvideo)

+ **Control-A-Video: Controllable Text-to-Video Diffusion Models with Motion Prior and Reward Feedback Learning** (23 May 2023)<details><summary>Weifeng Chen, Yatai Ji, Jie Wu, et al.</summary>
  Weifeng Chen, Yatai Ji, Jie Wu, Hefeng Wu, Pan Xie, Jiashi Li, Xin Xia, Xuefeng Xiao, Liang Lin</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Code](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Star)](https://github.com/Weifeng-Chen/control-a-video)
  
  
+ **ControlVideo: Training-free Controllable Text-to-Video Generation** (22 May 2023)<details><summary>Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, et al.</summary>
  Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, Xiaopeng Zhang, Wangmeng Zuo, Qi Tian</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
  [![Code](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Star)](https://github.com/YBYBZhang/ControlVideo)

+ **Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023)<details><summary>Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, et al.</summary>
  Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, Tsung-Yi Lin, Ming-Hsuan Yang</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14797)

+ **Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators** (23 Mar 2023)<details><summary>Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, et al.</summary>
  Levon Khachatryan, Andranik Movsisyan, Vahram Tadevosyan, Roberto Henschel, Zhangyang Wang, Shant Navasardyan, Humphrey Shi</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13439)
  [![Code](https://img.shields.io/github/stars/Picsart-AI-Research/Text2Video-Zero.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/Text2Video-Zero)

+ **Show Me What and Tell Me How: Video Synthesis via Multimodal Conditioning** (4 Mar 2022)<details><summary>Ligong Han, Jian Ren, Hsin-Ying Lee, et al.</summary>
  Ligong Han, Jian Ren, Hsin-Ying Lee, Francesco Barbieri, Kyle Olszewski, Shervin Minaee, Dimitris Metaxas, Sergey Tulyakov</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.02573)
  [![Code](https://img.shields.io/github/stars/snap-research/MMVID.svg?style=social&label=Star)](https://github.com/snap-research/MMVID)

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** (30 May 2024)<details><summary>Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>
  Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
  [![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)

 + **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** (7 Jan 2025)<details><summary>Zekai Gu, Rui Yan, Jiahao Lu, et al.</summary>
  Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03847)
  [![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader)

+ **Boximator: Generating Rich and Controllable Motions for Video Synthesis** (2 Feb 2024)<details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>
  Jiawei Wang, Yuchen Zhang, Jiaxin Zou, Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.00015)
  
+ **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** (22 Feb 2024)<details><summary>Yixuan Ren, Yang Zhou, Jimei Yang, et al.</summary>
  Yixuan Ren, Yang Zhou, Jimei Yang, Jing Shi, Difan Liu, Feng Liu, Mingi Kwon, Abhinav Shrivastava</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
  [![Code](https://img.shields.io/github/stars/customize-a-video/customize-a-video.svg?style=social&label=Star)](https://github.com/customize-a-video/customize-a-video)

## ❓ To be sorted

## 🌐 Unified controllable generation
