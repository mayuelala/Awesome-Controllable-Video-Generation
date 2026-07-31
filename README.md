

<div align="center">
<!-- <h2><font color="red"> Awesome-Controllable-Video-Generation </h2> -->

 <a href='https://arxiv.org/abs/2507.16869'><img src='https://img.shields.io/badge/ArXiv-2507.16869-red'></a> ![visitors](https://visitor-badge.laobi.icu/badge?page_id=mayuelala.Awesome-Controllable-Video-Generation&left_color=green&right_color=red)  [![GitHub](https://img.shields.io/github/stars/mayuelala/Awesome-Controllable-Video-Generation?style=social)](https://github.com/mayuelala/Awesome-Controllable-Video-Generation) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->


</div>

  
# 🤗 Introduction
🚀🚀🚀A curated list of papers on controllable video generation. Please join us for more comprehensive summary. If you have any additions to the list, please raise them in the issue section. 欢迎补充👏

# 💖 Citation 
If you find this repo is useful for your research, welcome to 🌟 this repo and cite our work using the following BibTeX:
```bibtex
@article{ma2025controllable,
  title={Controllable video generation: A survey},
  author={Ma, Yue and Feng, Kunyu and Hu, Zhongyuan and Wang, Xinyu and Wang, Yucheng and Zheng, Mingzhe and He, Xuanhua and Zhu, Chenyang and Liu, Hongyu and He, Yingqing and others},
  journal={arXiv preprint arXiv:2507.16869},
  year={2025}
}
```

# 📋 Contents

  * [🌐 Structure Control](#-structure-control)
    * [🏙️ Layout-Guided](#-layout-guided)
    * [🕺 Pose-Guided](#-pose-guided)
    * [📏 Depth-Guided](#-depth-guided)
    * [🗺️ Landmark-Guided](#-landmark-guided)
    * [✏️ Sketch-Guided](#-sketch-guided)
    * [📦 BBox-Guided](#-bbox-guided)
  * [🧬 ID Control](#-id-control)
    * [🧑 Person-Guided](#-person-guided)
    * [🧑‍🤝‍🧑 Subject-Guided](#-subject-guided)
  * [🖼️ Image Control](#-image-control)
  * [⏳ Temporal Control](#-temporal-control)
    * [🌊 Flow-Guided](#-flow-guided)
    * [🛤️ Trajectory-Guided](#-trajectory-guided)
    * [📸 Camera-Guided](#-camera-guided)
    * [🎬 Motion-Guided](#-motion-guided)
  * [🔊 Audio Control](#-audio-control)
    * [🗣️ Voice-Guided](#-voice-guided)
    * [🎵 Sound-Guided](#-sound-guided)
  * [🧩 Other Controls](#-other-controls)
    * [📝 Text Rendering](#-text-rendering)
    * [🎨 Style-Guided](#-style-guided)
    * [📌 Point-Guided](#-point-guided)
    * [🗺️ BEV-Guided](#-bev-guided)
  * [🧰 Survey-aligned Supporting Resources (C3)](#-survey-aligned-supporting-resources-c3)
  * [🌀 Universal Control](#-universal-control)


# 💘 Tips
- **✅ Paper searching via catalog**: directly clicking the content of the catalog to select the area of your research and browse related papers.
- **✅ Paper searching via author name**: Feel free to search papers of a specific author via `ctrl + F` and then type the author name. The dropdown list of authors will automatically expand when searching.
- **✅ Multicontrol indicator**: The tag ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=\[M]\&color=008000\&width=30\&fontSize=17\&height=17) indicates "multi-control" following the title of the paper.
- **✅ 2025 H2–2026 H1 verification**: For papers first submitted from 2025-07-01 through 2026-06-30, titles, author lists, and dates are taken from the arXiv API; categories and `[M]` are checked against the full paper. Project/code links are included only when supplied by the authors and reachable.
- **✅ Strict `[M]` rule**: `[M]` means that controls from different survey taxonomy classes jointly constrain one supported generation mode. Ordinary semantic prompts, multiple instances of one class, alternative modes, and internally derived representations of the same input do not create `[M]`.




## 🌐 Structure Control

### 🏙️ Layout-Guided
<a id="-layout-guided"></a>

<!-- RECENT_VERIFIED_START:Layout-Guided -->

+ **CoMoGen: COntrollable MOtion Dynamics and Interactions with Mask-Guided Video GENeration** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 May 2026)
  <details><summary>Adil Meric, Lin Geng Foo, Mert Kiray, et al.</summary>Adil Meric, Lin Geng Foo, Mert Kiray, Benjamin Busam, Rishabh Dabral, Christian Theobalt</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.22996) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mericadil.github.io/CoMoGen)

+ **Controllable Video Object Insertion via Multiview Priors** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Apr 2026)
  <details><summary>Xia Qi, Peishan Cong, Yichen Yao, et al.</summary>Xia Qi, Peishan Cong, Yichen Yao, Ziyi Wang, Yaoqin Ye, Yuexin Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.14556)

+ **Towards Controllable Video Synthesis of Routine and Rare OR Events** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Feb 2026)
  <details><summary>Dominik Schneider, Lalithkumar Seenivasan, Sampath Rapuri, et al.</summary>Dominik Schneider, Lalithkumar Seenivasan, Sampath Rapuri, Vishalroshan Anil, Aiza Maksutova, Yiqing Shen, Jan Emily Mangulabnan, Hao Ding, Jose L. Porras, Masaru Ishii, Mathias Unberath</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.21365)

+ **ACD: Direct Conditional Control for Video Diffusion Models via Attention Supervision** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Dec 2025)
  <details><summary>Weiqi Li, Zehao Zhang, Liang Lin, et al.</summary>Weiqi Li, Zehao Zhang, Liang Lin, Guangrun Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.21268)

+ **Mask2IV: Interaction-Centric Video Generation via Mask Trajectories** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Oct 2025)
  <details><summary>Gen Li, Bo Zhao, Jianfei Yang, et al.</summary>Gen Li, Bo Zhao, Jianfei Yang, Laura Sevilla-Lara</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.03135) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://reagan1311.github.io/mask2iv)

<!-- RECENT_VERIFIED_END:Layout-Guided -->

+ **DynamicCity: Large-Scale 4D Occupancy Generation from Dynamic Scenes** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 Oct 2024)
   <details><summary>[ICLR 2025 Spotlight] Hengwei Bian, Lingdong Kong, et al.</summary>  
        Hengwei Bian, Lingdong Kong, Haozhe Xie, Liang Pan, Yu Qiao, Ziwei Liu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.18084)
   [![Code](https://img.shields.io/github/stars/3DTopia/DynamicCity.svg?style=social&label=Star)](https://github.com/3DTopia/DynamicCity)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dynamic-city.github.io/)

### 🕺 Pose-Guided
<a id="-pose-guided"></a>

<!-- RECENT_VERIFIED_START:Pose-Guided -->

+ **Directing the World: Fast Autoregressive Video Generation with Compositional Human-Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Jun 2026)
  <details><summary>Haoyuan Wang, Yabo Chen, Haibin Huang, et al.</summary>Haoyuan Wang, Yabo Chen, Haibin Huang, Chi Zhang, Xuelong Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.27964) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://whydahuzi.github.io/Directing-the-World.github.io/)

+ **FreeAnimate: Training-Free Human Image Animation with Preview-Guided Denoising** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Jun 2026)
  <details><summary>Yuan Zeng, Yujia Shi, Zongqing Lu, et al.</summary>Yuan Zeng, Yujia Shi, Zongqing Lu, QingMin Liao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.06885) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://freeani.github.io/)

+ **Towards 3D-Aware Video Diffusion Models: Render-Free Human Motion Control with Mesh Tokenization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Jun 2026)
  <details><summary>Jingyun Liang, Min Wei, Shikai Li, et al.</summary>Jingyun Liang, Min Wei, Shikai Li, Yizeng Han, Hangjie Yuan, Lei Sun, Weihua Chen, Fan Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.02000) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyunliang.github.io/MeshToken/)

+ **Exploring the Role of Synthetic Data Augmentation in Controllable Human-Centric Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 Apr 2026)
  <details><summary>Yuanchen Fei, Yude Zou, Zejian Kang, et al.</summary>Yuanchen Fei, Yude Zou, Zejian Kang, Ming Li, Jiaying Zhou, Xiangru Huang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.21291)

+ **ReImagine: Rethinking Controllable High-Quality Human Video Generation via Image-First Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2026)
  <details><summary>Zhengwentai Sun, Keru Zheng, Chenghong Li, et al.</summary>Zhengwentai Sun, Keru Zheng, Chenghong Li, Hongjie Liao, Xihe Yang, Heyuan Li, Yihao Zhi, Shuliang Ning, Shuguang Cui, Xiaoguang Han</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.19720) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Taited/ReImagine)

+ **ONE-SHOT: Compositional Human-Environment Video Synthesis via Spatial-Decoupled Motion Injection and Hybrid Context Integration** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Apr 2026)
  <details><summary>Fengyuan Yang, Luying Huang, Jiazhi Guan, et al.</summary>Fengyuan Yang, Luying Huang, Jiazhi Guan, Quanwei Yang, Dongwei Pan, Jianglin Fu, Haocheng Feng, Wei He, Kaisiyuan Wang, Hang Zhou, Angela Yao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.01043) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://martayang.github.io/ONE-SHOT/)

+ **LOME: Learning Human-Object Manipulation with Action-Conditioned Egocentric World Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Mar 2026)
  <details><summary>Quankai Gao, Jiawei Yang, Qiangeng Xu, et al.</summary>Quankai Gao, Jiawei Yang, Qiangeng Xu, Le Chen, Yue Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.27449) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zerg-overmind.github.io/LOME.github.io/)

+ **PAM: A Pose-Appearance-Motion Engine for Sim-to-Real HOI Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 Mar 2026)
  <details><summary>Mingju Gao, Kaisen Yang, Huan-ang Gao, et al.</summary>Mingju Gao, Kaisen Yang, Huan-ang Gao, Bohan Li, Ao Ding, Wenyi Li, Yangcheng Yu, Jinkun Liu, Shaocong Xu, Yike Niu, Haohan Chi, Hao Chen, Hao Tang, Yu Zhang, Li Yi, Hao Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.22193) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gasaiyu.github.io/PAM.github.io)

+ **AnyCrowd: Instance-Isolated Identity-Pose Binding for Arbitrary Multi-Character Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Mar 2026)
  <details><summary>Zhenyu Xie, Ji Xia, Michael Kampffmeyer, et al.</summary>Zhenyu Xie, Ji Xia, Michael Kampffmeyer, Panwen Hu, Zehua Ma, Yujian Zheng, Jing Wang, Zheng Chong, Xujie Zhang, Xianhang Cheng, Xiaodan Liang, Hao Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.15415) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiezhy6.github.io/anycrowd)

+ **Controllable Egocentric Video Generation via Occlusion-Aware Sparse 3D Hand Joints** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Mar 2026)
  <details><summary>Chenyangguang Zhang, Botao Ye, Boqi Chen, et al.</summary>Chenyangguang Zhang, Botao Ye, Boqi Chen, Alexandros Delitzas, Fangjinhua Wang, Marc Pollefeys, Xi Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.11755) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhangcyg.github.io/handcontrolvideo/)

+ **DISPLAY: Directable Human-Object Interaction Video Generation via Sparse Motion Guidance and Multi-Task Auxiliary** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Mar 2026)
  <details><summary>Jiazhi Guan, Quanwei Yang, Luying Huang, et al.</summary>Jiazhi Guan, Quanwei Yang, Luying Huang, Junhao Liang, Borong Liang, Haocheng Feng, Wei He, Kaisiyuan Wang, Hang Zhou, Jingdong Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.09883) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mumuwei.github.io/DISPLAY/)

+ **Controllable Complex Human Motion Video Generation via Text-to-Skeleton Cascades** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Mar 2026)
  <details><summary>Ashkan Taghipour, Morteza Ghahremani, Zinuo Li, et al.</summary>Ashkan Taghipour, Morteza Ghahremani, Zinuo Li, Hamid Laga, Farid Boussaid, Mohammed Bennamoun</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.08028)

+ **MultiAnimate: Pose-Guided Image Animation Made Extensible** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Feb 2026)
  <details><summary>Yingcheng Hu, Haowen Gong, Chuanguang Yang, et al.</summary>Yingcheng Hu, Haowen Gong, Chuanguang Yang, Zhulin An, Yongjun Xu, Songhua Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.21581) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyc001.github.io/MultiAnimate/)

+ **Human Video Generation from a Single Image with 3D Pose and View Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Feb 2026)
  <details><summary>Tiantian Wang, Chun-Han Yao, Tao Hu, et al.</summary>Tiantian Wang, Chun-Han Yao, Tao Hu, Mallikarjun Byrasandra Ramalinga Reddy, Ming-Hsuan Yang, Varun Jampani</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.21188)

+ **Ani3DHuman: Photorealistic 3D Human Animation with Self-guided Stochastic Sampling** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Feb 2026)
  <details><summary>Qi Sun, Can Wang, Jiaxiang Shang, et al.</summary>Qi Sun, Can Wang, Jiaxiang Shang, Yingchun Liu, Jing Liao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.19089) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/qiisun/ani3dhuman)

+ **Generated Reality: Human-centric World Simulation using Interactive Video Generation with Hand and Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (20 Feb 2026)
  <details><summary>Linxi Xie, Lisong C. Sun, Ashley Neall, et al.</summary>Linxi Xie, Lisong C. Sun, Ashley Neall, Tong Wu, Shengqu Cai, Gordon Wetzstein</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.18422) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://codeysun.github.io/generated-reality/)

+ **Hand2World: Autoregressive Egocentric Interaction Generation via Free-Space Hand Gestures** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Feb 2026)
  <details><summary>Yuxi Wang, Wenqi Ouyang, Tianyi Wei, et al.</summary>Yuxi Wang, Wenqi Ouyang, Tianyi Wei, Yi Dong, Zhiqi Shen, Xingang Pan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.09600) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hand2world.github.io/)

+ **CoDance: An Unbind-Rebind Paradigm for Robust Multi-Subject Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Jan 2026)
  <details><summary>Shuai Tan, Biao Gong, Ke Ma, et al.</summary>Shuai Tan, Biao Gong, Ke Ma, Yutong Feng, Qiyuan Zhang, Yan Wang, Yujun Shen, Hengshuang Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.11096) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lucaria-academy.github.io/CoDance)

+ **MagicFight: Personalized Martial Arts Combat Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Jan 2026)
  <details><summary>Jiancheng Huang, Mingfu Yan, Songyan Chen, et al.</summary>Jiancheng Huang, Mingfu Yan, Songyan Chen, Yi Huang, Shifeng Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.02107) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://MingfuYAN.github.io/MagicFight/)

+ **PoseAnything: Universal Pose-guided Video Generation with Part-aware Temporal Coherence** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Dec 2025)
  <details><summary>Ruiyan Wang, Teng Hu, Kaihui Huang, et al.</summary>Ruiyan Wang, Teng Hu, Kaihui Huang, Zihan Su, Ran Yi, Lizhuang Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.13465) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ryan-w2024.github.io/project/PoseAnything/)

+ **FactorPortrait: Controllable Portrait Animation via Disentangled Expression, Pose, and Viewpoint** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Dec 2025)
  <details><summary>Jiapeng Tang, Kai Li, Chengxiang Yin, et al.</summary>Jiapeng Tang, Kai Li, Chengxiang Yin, Liuhao Ge, Fei Jiang, Jiu Xu, Matthias Nießner, Christian Häne, Timur Bagautdinov, Egor Zakharov, Peihong Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.11645)

+ **SteadyDancer: Harmonized and Coherent Human Image Animation with First-Frame Preservation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Nov 2025)
  <details><summary>Jiaming Zhang, Shengming Cao, Rui Li, et al.</summary>Jiaming Zhang, Shengming Cao, Rui Li, Xiaotong Zhao, Yutao Cui, Xinglin Hou, Gangshan Wu, Haolan Chen, Yu Xu, Limin Wang, Kai Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.19320) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mcg-nju.github.io/steadydancer-web)

+ **EgoControl: Controllable Egocentric Video Generation via 3D Full-Body Poses** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Nov 2025)
  <details><summary>Enrico Pallotta, Sina Mokhtarzadeh Azar, Lars Doorenbos, et al.</summary>Enrico Pallotta, Sina Mokhtarzadeh Azar, Lars Doorenbos, Serdar Ozsoy, Umar Iqbal, Juergen Gall</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.18173)

+ **AdaViewPlanner: Adapting Video Diffusion Models for Viewpoint Planning in 4D Scenes** (12 Oct 2025)
  <details><summary>Yu Li, Menghan Xia, Gongye Liu, et al.</summary>Yu Li, Menghan Xia, Gongye Liu, Jianhong Bai, Xintao Wang, Conglang Zhang, Yuxuan Lin, Ruihang Chu, Pengfei Wan, Yujiu Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.10670) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yuli0103.github.io/AdaViewPlanner/)

+ **MoSA: Motion-Coherent Human Video Generation via Structure-Appearance Decoupling** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Aug 2025)
  <details><summary>Haoyu Wang, Hao Tang, Donglin Di, et al.</summary>Haoyu Wang, Hao Tang, Donglin Di, Zhilu Zhang, Wangmeng Zuo, Feng Gao, Siwei Ma, Shiliang Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.17404)

+ **Precise Action-to-Video Generation Through Visual Action Prompts** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Aug 2025)
  <details><summary>Yuang Wang, Chao Wen, Haoyu Guo, et al.</summary>Yuang Wang, Chao Wen, Haoyu Guo, Sida Peng, Minghan Qin, Hujun Bao, Xiaowei Zhou, Ruizhen Hu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.13104) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zju3dv.github.io/VAP/)

+ **PoseGen: In-Context LoRA Finetuning for Pose-Controllable Long Human Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Aug 2025)
  <details><summary>Jingxuan He, Busheng Su, Finn Wong</summary>Jingxuan He, Busheng Su, Finn Wong</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.05091) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Jessie459/PoseGen)

<!-- RECENT_VERIFIED_END:Pose-Guided -->

+ **MTVCrafter: 4D Motion Tokenization for Open-World Human Image Animation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 May 2025) <details><summary>Yanbo Ding, Xirui Hu, Zhizhi Guo, et al.</summary> Yanbo Ding, Xirui Hu, Zhizhi Guo, Chi Zhang, Yali Wang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.10238) [![Code](https://img.shields.io/github/stars/DINGYANB/MTVCrafter.svg?style=social&label=Star)](https://github.com/DINGYANB/MTVCrafter) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dingyanb.github.io/MTVCtafter/)

 + **HyperMotion: DiT-Based Pose-Guided Human Image Animation of Complex Motions**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 May 2025) <details><summary>Shuolin Xu, Siming Zheng, Ziyi Wang, et al.</summary> Shuolin Xu, Siming Zheng, Ziyi Wang, HC Yu, Jinwei Chen, Huaqi Zhang, Bo Li, Peng-Tao Jiang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.22977)[![Code](https://img.shields.io/github/stars/vivoCameraResearch/Hyper-Motion.svg?style=social&label=Star)](https://github.com/vivoCameraResearch/Hyper-Motion) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://vivocameraresearch.github.io/hypermotion/)  


+ **FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 May 2025) <details><summary>[SIGGRAPH 2025] Shiyi Zhang*, Junhao Zhuang*, et al.</summary> Shiyi Zhang*, Junhao Zhuang*, Zhaoyang Zhang, Ying Shan, Yansong Tang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730) [![Code](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social&label=Star)](https://github.com/shiyi-zh0408/FlexiAct) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)

+ **DualReal: Joint Training for Lossless Identity-Motion Fusion in Video Customization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 May 2025) <details><summary>Wenchuan Wang, Mengqi Huang, Yijing Tu, et al.</summary> Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.02192)

+ **DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 May 2025) <details><summary>Junhao Chen, Mingjin Chen, Jianjin Xu, et al.</summary> Junhao Chen, Mingjin Chen, Jianjin Xu, Xiang Li, Junting Dong, Mingze Sun, Puhua Jiang, Hongxiang Li, Yuhang Yang, Hao Zhao, Xiaoxiao Long, Ruqi Huang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.18078)

+ **TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Mar 2025) <details><summary>Hongxiang Zhao, Xingchen Liu, et al.</summary> Hongxiang Zhao, Xingchen Liu, Mutian Xu, Yiming Hao, Weikai Chen, Xiaoguang Han</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11423) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://taste-rob.github.io/)

+ **Point-to-Point Video Generation** (14 Mar 2025) <details><summary>Tsun-Hsuan Wang, Yen-Chi Cheng, et al.</summary> Tsun-Hsuan Wang, Yen-Chi Cheng, Chieh Hubert Lin, Hwann-Tzong Chen, Min Sun</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1904.02912) [![Code](https://img.shields.io/github/stars/yccyenchicheng/p2pvg.svg?style=social&label=Star)](https://github.com/yccyenchicheng/p2pvg)

+ **Pose Guided Human Video Generation** (14 Mar 2025) <details><summary>Ceyuan Yang, Zhe Wang, et al.</summary> Ceyuan Yang, Zhe Wang, Xinge Zhu, Chen Huang, Jianping Shi, Dahua Lin</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1807.11152)

+ **SkyReels-A1: Expressive Portrait Animation in Video Diffusion Transformers** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Feb 2025) <details><summary>Di Qiu, Zhengcong Fei, et al.</summary> Di Qiu, Zhengcong Fei, Rui Wang, Jialin Bai, Changqian Yu, Mingyuan Fan, Guibin Chen, Xiang Wen</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2502.10841) [![Code](https://img.shields.io/github/stars/SkyworkAI/SkyReels-A1.svg?style=social&label=Star)](https://github.com/SkyworkAI/SkyReels-A1) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://skyworkai.github.io/skyreels-a1.github.io/)

+ **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Feb 2025) <details><summary>Zhao Wang, Hao Wen, et al.</summary> Zhao Wang, Hao Wen, Lingting Zhu, Chenming Shang, Yujiu Yang, Qi Dou</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189) [![Code](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social&label=Star)](https://github.com/AnyCharV/AnyCharV) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anycharv.github.io/)

+ **Animate Anyone 2: High-Fidelity Character Image Animation with Environment Affordance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Feb 2025) <details><summary>Li Hu, Guangyuan Wang, et al.</summary> Li Hu, Guangyuan Wang, Zhen Shen, Xin Gao, Dechao Meng, Lian Zhuo, Peng Zhang, Bang Zhang, Liefeng Bo</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.06145) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone-2/)

+ **DirectorLLM for Human-Centric Video Generation** (19 Dec 2024) <details><summary>Kunpeng Song, Tingbo Hou, et al.</summary> Kunpeng Song, Tingbo Hou, Zecheng He, Haoyu Ma, Jialiang Wang, Animesh Sinha, Sam Tsai, Yaqiao Luo, Xiaoliang Dai, Li Chen, Xide Xia, Peizhao Zhang, Peter Vajda, Ahmed Elgammal, Felix Juefei-Xu</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14484)

+ **Generative Inbetweening through Frame-wise Conditions-Driven Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Dec 2024) <details><summary>[CVPR 2025] Tianyi Zhu, Dongwei Ren, et al.</summary> Tianyi Zhu, Dongwei Ren, Qilong Wang, Xiaohe Wu, Wangmeng Zuo</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.11755) [![Code](https://img.shields.io/github/stars/Tian-one/FCVG.svg?style=social&label=Star)](https://github.com/Tian-one/FCVG) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fcvg-inbetween.github.io/)

+ **DisPose: Disentangling Pose Guidance for Controllable Human Image Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Dec 2024) <details><summary>[ICLR2025] Hongxiang Li, Yaowei Li, et al.</summary> Hongxiang Li, Yaowei Li, Yuhang Yang, Junjie Cao, Zhihong Zhu, Xuxin Cheng, Long Chen</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09349) [![Code](https://img.shields.io/github/stars/lihxxx/DisPose.svg?style=social&label=Star)](https://github.com/lihxxx/DisPose) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lihxxx.github.io/DisPose/)

+ **StableAnimator: High-Quality Identity-Preserving Human Image Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Nov 2024) <details><summary>[CVPR 2025] Shuyuan Tu, Zhen Xing, Xintong Han, et al.</summary> Shuyuan Tu, Zhen Xing, Xintong Han, Zhi-Qi Cheng, Qi Dai, Chong Luo, Zuxuan Wu</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17697) [![Code](https://img.shields.io/github/stars/Francis-Rings/StableAnimator.svg?style=social&label=Star)](https://github.com/Francis-Rings/StableAnimator) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://francis-rings.github.io/StableAnimator)

+ **AnimateAnywhere: Context-Controllable Human Video Generation with ID-Consistent One-shot Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Oct 2024) <details><summary>[ACMMM 2024] Hengyuan Liu, Xiaodong Chen, Xinchen Liu, et al.</summary> Hengyuan Liu, Xiaodong Chen, Xinchen Liu, Xiaoyan Gu, Wu Liu</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/3688865.3689477)

+ **ControlNeXt: Powerful and Efficient Control for Image and Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Aug 2024) <details><summary>Bohao Peng, Jian Wang, et al.</summary> Bohao Peng, Jian Wang, Yuechen Zhang, Wenbo Li, Ming-Chang Yang, Jiaya Jia</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06070) [![Code](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star)](https://github.com/dvlab-research/ControlNeXt) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pbihao.github.io/projects/controlnext/index.html)

+ **TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Jul 2024) <details><summary>Jeongho Kim, Min-Jung Kim, Junsoo Lee, et al.</summary> Jeongho Kim, Min-Jung Kim, Junsoo Lee, Jaegul Choo</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09012) [![Code](https://img.shields.io/github/stars/eccv2024tcan/TCAN.svg?style=social&label=Star)](https://github.com/eccv2024tcan/TCAN) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://eccv2024tcan.github.io)

+ **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Jun 2024) <details><summary>Yuang Zhang, Jiaxi Gu, Li-Wen Wang, et al.</summary> Yuang Zhang, Jiaxi Gu, Li-Wen Wang, Han Wang, Junqi Cheng, Yuefeng Zhu, Fangyuan Zou</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.19680) [![Code](https://img.shields.io/github/stars/Tencent/MimicMotion.svg?style=social&label=Star)](https://github.com/Tencent/MimicMotion) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://tencent.github.io/MimicMotion/)

+ **Follow-Your-Pose v2: Multiple-Condition Guided Character Image Animation for Stable Pose Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (05 Jun 2024) <details><summary>Jingyun Xue, Hongfa Wang, Qi Tian, et al.</summary> Jingyun Xue, Hongfa Wang, Qi Tian, Yue Ma, Andong Wang, Zhiyuan Zhao, Shaobo Min, Wenzhe Zhao, Kaihao Zhang, Heung-Yeung Shum, Wei Liu, Mengyang Liu, Wenhan Luo</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.03035v3) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose-v2.github.io)

+ **UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Jun 2024) <details><summary>Xiang Wang, Shiwei Zhang, Changxin Gao, et al.</summary> Xiang Wang, Shiwei Zhang, Changxin Gao, Jiayu Wang, Xiaoqiang Zhou, Yingya Zhang, Luxin Yan, Nong Sang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01188) [![Code](https://img.shields.io/github/stars/ali-vilab/UniAnimate.svg?style=social&label=Star)](https://github.com/ali-vilab/UniAnimate) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://unianimate.github.io)

+ **VividPose: Advancing Stable Video Diffusion for Realistic Human Image Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 May 2024) <details><summary>Qilin Wang, Zhengkai Jiang, Chengming Xu, et al.</summary> Qilin Wang, Zhengkai Jiang, Chengming Xu, Jiangning Zhang, Yabiao Wang, Xinyi Zhang, Yun Cao, Weijian Cao, Chengjie Wang, Yanwei Fu</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18156) [![Code](https://img.shields.io/github/stars/Kelu007/VividPose.svg?style=social&label=Star)](https://github.com/Kelu007/VividPose) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://kelu007.github.io/vivid-pose/)

+ **Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 May 2024) <details><summary>Jinlin Liu, Kai Yu, Mengyang Feng, et al.</summary> Jinlin Liu, Kai Yu, Mengyang Feng, Xiefan Guo, Miaomiao Cui</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.16393v2) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://liujl09.github.io/humanvideo_movingbackground/)

+ **PoseCrafter: One-Shot Personalized Video Synthesis Following Flexible Pose Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 May 2024) <details><summary>[ECCV 2024] Yong Zhong, Min Zhao, Zebin You, et al.</summary> Yong Zhong, Min Zhao, Zebin You, Xiaofeng Yu, Changwang Zhang, Chongxuan Li</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14582) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://ml-gsai.github.io/PoseCrafter-demo/)

+ **Zero-shot High-fidelity and Pose-controllable Character Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2024) <details><summary>[IJCAI 2024] Bingwen Zhu, Fanyi Wang, Tianyi Lu, et al.</summary> Bingwen Zhu, Fanyi Wang, Tianyi Lu, Peng Liu, Jingwen Su, Jinxiu Liu, Yanhao Zhang, Zuxuan Wu, Guo-Jun Qi, Yu-Gang Jiang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.13680)

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Mar 2024) <details><summary>[ECCV 2024] Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary> Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781) [![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/)

+ **Do You Guys Want to Dance: Zero-Shot Compositional Human Dance Generation with Multiple Persons** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Jan 2024) <details><summary>Zhe Xu, Kun Wei, et al.</summary> Zhe Xu, Kun Wei, Xu Yang, Cheng Deng</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.13363)

+ **DreaMoving: A Human Video Generation Framework based on Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Dec 2023) <details><summary>Mengyang Feng, Jinlin Liu, Kai Yu, et al.</summary> Mengyang Feng, Jinlin Liu, Kai Yu, Yuan Yao, Zheng Hui, Xiefan Guo, Xianhui Lin, Haolan Xue, Chen Shi, Xiaowen Li, Aojie Li, Xiaoyang Kang, Biwen Lei, Miaomiao Cui, Peiran Ren, Xuansong Xie</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.05107) [![Code](https://img.shields.io/github/stars/dreamoving/dreamoving-project.svg?style=social&label=Star)](https://github.com/dreamoving/dreamoving-project) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamoving.github.io/dreamoving/)

+ **Generative Rendering: Controllable 4D-Guided Video Generation with 2D Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2023) <details><summary>[CVPR 2024] Shengqu Cai, Duygu Ceylan, et al.</summary> Shengqu Cai, Duygu Ceylan, Matheus Gadelha, Chun-Hao Paul Huang, Tuanfeng Yang Wang, Gordon Wetzstein</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://primecai.github.io/generative_rendering/)

+ **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2023) <details><summary>[CVPR 2024] Li Hu, Xin Gao, Peng Zhang, et al.</summary> Li Hu, Xin Gao, Peng Zhang, Ke Sun, Bang Zhang, Liefeng Bo</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17117v3) [![Code](https://img.shields.io/github/stars/HumanAIGC/AnimateAnyone.svg?style=social&label=Star)](https://github.com/HumanAIGC/AnimateAnyone) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/animate-anyone/)

+ **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Nov 2023) <details><summary>[CVPR 2024] Zhongcong Xu, Jianfeng Zhang, et al.</summary> Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16498) [![Code](https://img.shields.io/github/stars/magic-research/magic-animate.svg?style=social&label=Star)](https://github.com/magic-research/magic-animate) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/magicanimate/)

+ **MagicPose: Realistic Human Poses and Facial Expressions Retargeting with Identity-aware Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Nov 2023) <details><summary>[ICML 2024] Di Chang, Yichun Shi, Quankai Gao, et al.</summary> Di Chang, Yichun Shi, Quankai Gao, Jessica Fu, Hongyi Xu, Guoxian Song, Qing Yan, Yizhe Zhu, Xiao Yang, Mohammad Soleymani</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12052) [![Code](https://img.shields.io/github/stars/Boese0601/MagicDance.svg?style=social&label=Star)](https://github.com/Boese0601/MagicDance) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boese0601.github.io/magicdance/)

+ **Dancing Avatar: Pose and Text-Guided Human Motion Videos Synthesis with Image Diffusion Model** (15 Aug 2023) <details><summary>Bosheng Qin, Wentao Ye, et al.</summary> Bosheng Qin, Wentao Ye, Qifan Yu, Siliang Tang, Yueting Zhuang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.07749)

+ **DISCO: Disentangled Control for Realistic Human Dance Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Jun 2023) <details><summary>[CVPR 2024] Tan Wang, Linjie Li, Kevin Lin, et al.</summary> Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.00040) [![Code](https://img.shields.io/github/stars/Wangt-CN/DisCo.svg?style=social&label=Star)](https://github.com/Wangt-CN/DisCo) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://disco-dance.github.io)

+ **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Apr 2023) <details><summary>[ICCV 2023] Johanna Karras, Aleksander Holynski, Ting-Chun Wang, et al.</summary> Johanna Karras, Aleksander Holynski, Ting-Chun Wang, Ira Kemelmacher-Shlizerman</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06025) [![Code](https://img.shields.io/github/stars/johannakarras/DreamPose.svg?style=social&label=Star)](https://github.com/johannakarras/DreamPose) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://grail.cs.washington.edu/projects/dreampose/)

+ **Follow Your Pose: Pose-Guided Text-to-Video Generation using Pose-Free Videos** (3 Apr 2023) <details><summary>[AAAI 2024] Yue Ma, Yingqing He, et al.</summary> Yue Ma, Yingqing He, Xiaodong Cun, Xintao Wang, Siran Chen, Ying Shan, Xiu Li, Qifeng Chen</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.01186) [![Code](https://img.shields.io/github/stars/mayuelala/FollowYourPose.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourPose) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-pose.github.io/)

+ **vid2vid:Video-to-Video Synthesis**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2018) <details><summary>Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, et al.</summary> Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Guilin Liu, Andrew Tao, Jan Kautz, Bryan Catanzaro</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1808.06601) [![Code](https://img.shields.io/github/stars/NVIDIA/vid2vid.svg?style=social&label=Star)](https://github.com/NVIDIA/vid2vid) [![Project](https://img.shields.io/badge/Project_Page-00CED1)]((https://tcwang0509.github.io/vid2vid/))

 
### 📏 Depth-Guided
<a id="-depth-guided"></a>

<!-- RECENT_VERIFIED_START:Depth-Guided -->

+ **DriveCtrl: Conditioned Sim-to-Real Driving Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 May 2026)
  <details><summary>Haonan Zhao, Yiting Wang, Jingkun Chen, et al.</summary>Haonan Zhao, Yiting Wang, Jingkun Chen, Valentina Donzella, Thomas Bashford-Rogers, Kurt Debattista</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.15116)

+ **DepthPilot: From Controllability to Interpretability in Colonoscopy Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Apr 2026)
  <details><summary>Junhu Fu, Ke Chen, Weidong Guo, et al.</summary>Junhu Fu, Ke Chen, Weidong Guo, Shuyu Liang, Jie Xu, Chen Ma, Kehao Wang, Shengli Lin, Zeju Li, Yuanyuan Wang, Yi Guo, Shuo Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.26232)

<!-- RECENT_VERIFIED_END:Depth-Guided -->

+ **Frame Guidance: Training-Free Guidance for Frame-Level Control in Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jun 2025)
   <details><summary>Sangwon Jang, Taekyung Ki, Jaehyeong Jo, et al.</summary>  
         Sangwon Jang, Taekyung Ki, Jaehyeong Jo, Jaehong Yoon, Soo Ye Kim, Zhe Lin, Sung Ju Hwang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07177)
   [![Code](https://img.shields.io/github/stars/agwmon/frame-guidance.svg?style=social&label=Star)](https://github.com/agwmon/frame-guidance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://frame-guidance-video.github.io/)

+ **OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Apr 2025)<details><summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, et al.</summary>
Xi Qiu, Yuchi Huo, Rui Wang, Chi Zhang, Xuelong Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.10825)
[![Code](https://img.shields.io/github/stars/Tele-AI/OmniVDiff.svg?style=social&label=Star)](https://github.com/Tele-AI/OmniVDiff.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tele-ai.github.io/OmniVDiff/)


+ **DreamDance: Animating Human Images by Enriching 3D Geometry Cues from 2D Poses** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Nov 2024)<details><summary>Yatian Pang, Bin Zhu, Bin Lin, et al.</summary>
        Mingzhe Zheng, Francis E. H. Tay, Ser-Nam Lim, Harry Yang, Li Yuan </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00397)
[![Code](https://img.shields.io/github/stars/YongjinLiu/DreamDance.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/DreamDance.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pang-yatian.github.io/Dreamdance-webpage/)

+ **ControlNeXt: Powerful and Efficient Control for Image and Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Aug 2024)<details><summary>Bohao Peng, Jian Wang, Yuechen Zhang, et al.</summary>
        Wenbo Li, Ming-Chang Yang, Jiaya Jia</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.06070)
[![Code](https://img.shields.io/github/stars/dvlab-research/ControlNeXt.svg?style=social&label=Star)](https://github.com/dvlab-research/ControlNeXt.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pbihao.github.io/projects/controlnext/index.html)

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Mar 2024)<details><summary>[ECCV 2024] Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>
      Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/champ.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/champ.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **MoonShot: Towards Controllable Video Generation and Editing with Multimodal Conditions** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Jan 2024)<details><summary>David Junhao Zhang, Dongxu Li, Hung Le, et al.</summary>
      Mike Zheng Shou, Caiming Xiong, Doyen Sahoo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01827)
[![Code](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Star)](https://github.com/salesforce/LAVIS.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://showlab.github.io/Moonshot/)

+ **SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models** (28 Nov 2023)<details><summary>[ECCV 2024] Yuwei Guo, Ceyuan Yang, Anyi Rao, et al.</summary>
        Maneesh Agrawala, Dahua Lin, Bo Dai</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933)
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff.svg?style=social&label=Star)](https://github.com/guoyww/AnimateDiff.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoyww.github.io/projects/SparseCtrl/)

+ **GD-VDM: Generated Depth for better Diffusion-based Video Generation** (19 Jun 2023)<details><summary>Ariel Lapid, Idan Achituve, Lior Bracha, et al.</summary>
        Ethan Fetaya</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.11173)
[![Code](https://img.shields.io/github/stars/lapid92/GD-VDM.svg?style=social&label=Star)](https://github.com/lapid92/GD-VDM.git)


+ **Make-Your-Video: Customized Video Generation Using Textual and Structural Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Jun 2023)<details><summary>[IEEE TVCG 2024] Jinbo Xing, Menghan Xia, Yuxin Liu, et al.</summary>
        Yuechen Zhang, Yong Zhang, Yingqing He, Hanyuan Liu, Haoxin Chen, Xiaodong Cun, Xintao Wang, Ying Shan, Tien-Tsin Wong</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00943)
[![Code](https://img.shields.io/github/stars/AILab-CVC/Make-Your-Video.svg?style=social&label=Star)](https://github.com/AILab-CVC/Make-Your-Video.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/Make-Your-Video/)

+ **Control-A-Video: Controllable Text-to-Video Diffusion Models with Motion Prior and Reward Feedback Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 May 2023)<details><summary>Weifeng Chen, Yatai Ji, Jie Wu, et al.</summary>
        Hefeng Wu, Pan Xie, Jiashi Li, Xin Xia, Xuefeng Xiao, Liang Lin</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13840)
[![Code](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Star)](https://github.com/Weifeng-Chen/control-a-video.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlavideo.github.io/)

+ **ControlVideo: Training-free Controllable Text-to-Video Generation** (22 May 2023)<details><summary>[ICLR 2024] Yabo Zhang, Yuxiang Wei, Dongsheng Jiang, et al.</summary>
      Xiaopeng Zhang, Wangmeng Zuo, Qi Tian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.13077)
[![Code](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Star)](https://github.com/YBYBZhang/ControlVideo.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://controlvideov1.github.io/)

### 🗺️ Landmark-Guided
<a id="-landmark-guided"></a>

<!-- RECENT_VERIFIED_START:Landmark-Guided -->

+ **AUHead: Realistic Emotional Talking Head Generation via Action Units Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Feb 2026)
  <details><summary>Jiayi Lyu, Leigang Qu, Wenjing Zhang, et al.</summary>Jiayi Lyu, Leigang Qu, Wenjing Zhang, Hanyu Jiang, Kai Liu, Zhenglin Zhou, Xiaobo Xia, Jian Xue, Tat-Seng Chua</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.09534) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/laura990501/AUHead_ICLR)

+ **Follow-Your-Emoji-Faster: Towards Efficient, Fine-Controllable, and Expressive Freestyle Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (20 Sep 2025)
  <details><summary>Yue Ma, Zexuan Yan, Hongyu Liu, et al.</summary>Yue Ma, Zexuan Yan, Hongyu Liu, Hongfa Wang, Heng Pan, Yingqing He, Junkun Yuan, Ailing Zeng, Chengfei Cai, Heung-Yeung Shum, Zhifeng Li, Wei Liu, Linfeng Zhang, Qifeng Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.16630) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-emoji.github.io/)

<!-- RECENT_VERIFIED_END:Landmark-Guided -->

+ **HunyuanPortrait: Implicit Condition Control for Enhanced Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Mar 2024)
   <details><summary>[CVPR 2025] Zunnan Xu, Zhentao Yu, et al.</summary>  
        Zunnan Xu, Zhentao Yu, Zixiang Zhou, Jun Zhou, Xiaoyu Jin, Fa-Ting Hong, Xiaozhong Ji, Junwei Zhu, Chengfei Cai, Shiyu Tang, Qin Lin, Xiu Li, Qinglin Lu </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18860)
   [![Code](https://img.shields.io/github/stars/kkakkkka/HunyuanPortrait.svg?style=social&label=Star)](https://github.com/kkakkkka/HunyuanPortrait)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kkakkkka.github.io/HunyuanPortrait)

+ **TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Mar 2025)
   <details><summary>Hongxiang Zhao, Xingchen Liu, et al.</summary>  
        Hongxiang Zhao, Xingchen Liu, Mutian Xu, Yiming Hao, Weikai Chen, Xiaoguang Han </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11423)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://taste-rob.github.io/)

+ **Identity-Preserving Text-to-Video Generation by Frequency Decomposition** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Nov 2024)
   <details><summary>[CVPR 2025] Shenghai Yuan, Jinfa Huang, et al.</summary>  
        Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
   [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ConsisID)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/ConsisID/)

+ **EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Nov 2024)<details><summary>[CVPR 2025] Rang Meng, Xingyu Zhang, Yuming Li, et al.</summary>
Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://antgroup.github.io/ai/echomimic_v2/)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic_v2.svg?style=social&label=Star)](https://github.com/antgroup/echomimic_v2)

+ **Takin-ADA: Emotion Controllable Audio-Driven Animation with Canonical and Landmark Loss Optimization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Oct 2024)
   <details><summary>Bin Lin, Yanzhen Yu, et al.</summary>  
        Bin Lin, Yanzhen Yu, Jianhao Ye, Ruitao Lv, Yuguang Yang, Ruoye Xie, Pan Yu, Hongbin Zhou </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.14283)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://everest-ai.github.io/takinada/)

+ **EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Jul 2024)<details><summary>[AAAI 2025] Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, et al.</summary>
Yuming Li, Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic.svg?style=social&label=Star)](https://github.com/antgroup/echomimic)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BadToBest/EchoMimic)

+ **LivePortrait: Efficient Portrait Animation with Stitching and Retargeting Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Jul 2024)
   <details><summary>Jianzhu Guo, Dingyun Zhang, et al.</summary>  
        Jianzhu Guo, Dingyun Zhang, Xiaoqiang Liu, Zhizhou Zhong, Yuan Zhang, Pengfei Wan, Di Zhang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.03168)
   [![Code](https://img.shields.io/github/stars/KwaiVGI/LivePortrait.svg?style=social&label=Star)](https://github.com/KwaiVGI/LivePortrait)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://liveportrait.github.io/)

+ **Follow-Your-Emoji: Fine-Controllable and Expressive Freestyle Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Jun 2024)
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

### ✏️ Sketch-Guided
<a id="-sketch-guided"></a>

<!-- RECENT_VERIFIED_START:Sketch-Guided -->

+ **SketchKeyAnime: Reference-anchored Sparse Key-Sketch Animation Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Jun 2026)
  <details><summary>Meixi Li, Xianlin Zhang, Yue Zhang, et al.</summary>Meixi Li, Xianlin Zhang, Yue Zhang, Xueming Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.19958)

+ **DrawVideo: Generating Long Video from Storyboard Keyframe Sketches** (22 May 2026)
  <details><summary>Chuanzhi Xu, Huiqi Liang, Bang Shi, et al.</summary>Chuanzhi Xu, Huiqi Liang, Bang Shi, Huiming Zhang, Yifan Xiao, Guangcheng Lin, Haodong Chen, Qiang Qu, Zhicheng Lu, Weidong Cai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.23508)

+ **Planning with Sketch-Guided Verification for Physics-Aware Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Nov 2025)
  <details><summary>Yidong Huang, Zun Wang, Han Lin, et al.</summary>Yidong Huang, Zun Wang, Han Lin, Dong-Ki Kim, Shayegan Omidshafiei, Jaehong Yoon, Yue Zhang, Mohit Bansal</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.17450) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sketchverify.github.io/)

+ **EVCtrl: Efficient Control Adapter for Visual Generation** (14 Aug 2025)
  <details><summary>Zixiang Yang, Yue Ma, Yinhan Zhang, et al.</summary>Zixiang Yang, Yue Ma, Yinhan Zhang, Shanhui Mo, Dongrui Liu, Linfeng Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.10963)

+ **SketchAnimator: Animate Sketch via Motion Customization of Text-to-Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Aug 2025)
  <details><summary>Ruolin Yang, Da Li, Honggang Zhang, et al.</summary>Ruolin Yang, Da Li, Honggang Zhang, Yi-Zhe Song</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.07149)

<!-- RECENT_VERIFIED_END:Sketch-Guided -->

+ **Frame Guidance: Training-Free Guidance for Frame-Level Control in Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jun 2025)
   <details><summary>Sangwon Jang, Taekyung Ki, Jaehyeong Jo, et al.</summary>  
         Sangwon Jang, Taekyung Ki, Jaehyeong Jo, Jaehong Yoon, Soo Ye Kim, Zhe Lin, Sung Ju Hwang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07177)
   [![Code](https://img.shields.io/github/stars/agwmon/frame-guidance.svg?style=social&label=Star)](https://github.com/agwmon/frame-guidance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://frame-guidance-video.github.io/)
+ **OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding** (15 Apr 2025)<details><summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, et al.</summary>
Xi Qiu, Yuchi Huo, Rui Wang, Chi Zhang, Xuelong Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.10825)
[![Code](https://img.shields.io/github/stars/Tele-AI/OmniVDiff.svg?style=social&label=Star)](https://github.com/Tele-AI/OmniVDiff.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tele-ai.github.io/OmniVDiff/)




+ **SketchVideo: Sketch-based Video Generation and Editing** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Mar 2025)
   <details><summary>Feng-Lin Liu, Hongbo Fu, Xintao Wang, et al.</summary> Feng-Lin Liu, Hongbo Fu, Xintao Wang, Weicai Ye, Pengfei Wan, Di Zhang, Lin Gao</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.23284) [![Code](https://img.shields.io/github/stars/IGLICT/SketchVideo.svg?style=social&label=Star)](https://github.com/IGLICT/SketchVideo)

+ **LayerAnimate: Layer-level Control for Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Mar 2025)
   <details><summary>Yuxue Yang, Lue Fan, Zuzeng Lin, et al.</summary> Feng Wang, Zhaoxiang Zhang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08295) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layeranimate.github.io/) [![Code](https://img.shields.io/github/stars/IamCreateAI/LayerAnimate.svg?style=social&label=Star)](https://github.com/IamCreateAI/LayerAnimate) [![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/IamCreateAI/LayerAnimate)


+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Mar 2025)
   <details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary> Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592) [![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/Projects-CameraCtrl-II/)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Mar 2025)
   <details><summary>[ICLR 2025] Hao He, Yinghao Xu, Yuwei Guo, et al.</summary> Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/) [![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl) [![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/hehao13/CameraCtrl-svd)


+ **VidSketch: Hand-drawn Sketch-Driven Video Generation with Diffusion Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Feb 2025)
   <details><summary>Lifan Jiang, Shuang Chen, Boxi Wu, et al.</summary> Xiaotong Guan, Jiahui Zhang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01101) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://csfufu.github.io/vid_sketch/) [![Code](https://img.shields.io/github/stars/CSfufu/VidSketch.svg?style=social&label=Star)](https://github.com/CSfufu/VidSketch)



+ **AniDoc: Animation Creation Made Easier** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Jan 2025)
   <details><summary>[CVPR 2025] Yihao Meng, Hao Ouyang, Hanlin Wang, et al.</summary> Qiuyu Wang, Wen Wang, Ka Leong Cheng, Zhiheng Liu, Yujun Shen, Huamin Qu</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14173) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yihao-meng.github.io/AniDoc_demo/) [![Code](https://img.shields.io/github/stars/ant-research/AniDoc.svg?style=social&label=Star)](https://github.com/ant-research/AniDoc)

+ **Latent-Reframe: Enabling Camera Control for Video Diffusion Model without Training** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Dec 2024)
   <details><summary>Zhenghong Zhou, Jie An, Jiebo Luo, et al.</summary></details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06029) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://latent-reframe.github.io/)

+ **CamI2V: Camera-Controlled Image-to-Video Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Dec 2024)
   <details><summary>Guangcong Zheng, Teng Li, Rui Jiang, et al.</summary> Yehao Lu, Tao Wu, Xi Li</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15957) [![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zgctroy.github.io/CamI2V/?ref=aiartweekly)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories(frame+track+text)** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2024)
   <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary> Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1) [![Code](https://img.shields.io/github/stars/HyelinNAM/MotionPrompt.svg?style=social&label=Star)](https://github.com/HyelinNAM/MotionPrompt) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)

+ **MOTIONFLOW: Learning Implicit Motion Flow for Complex Camera Trajectory Control in Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (Dec 2024)
   <details><summary>Author list not fully provided</summary></details> 

   [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=OBTmkKBmQW) [![Code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://motion-prompting.github.io/)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Nov 2024)
   <details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)

+ **Trajectory Attention: Enhancing Video Generation with Fine-Grained Motion Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2024)
   <details><summary>Zeqi Xiao, Wenqi Ouyang, Yifan Zhou, et al.</summary> Shuai Yang, Lei Yang, Jianlou Si, Xingang Pan</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19324) [![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deep-diver.github.io/ai-paper-reviewer/paper-reviews/2411.19324/)

+ **Open-Sora Plan: Open-Source Large Video Generation Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2024)
   <details><summary>Bin Lin, Yunyang Ge, Xinhua Cheng, et al.</summary> Zongjian Li, Bin Zhu, Shaodong Wang, Xianyi He, Yang Ye, Shenghai Yuan, Liuhan Chen, Tanghui Jia, Junwu Zhang, Zhenyu Tang, Yatian Pang, Bin She, Cen Yan, Zhiheng Hu, Xiaoyi Dong, Lin Chen, Zhang Pan, Xing Zhou, Shaoling Dong, Yonghong Tian, Li Yuan</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.00131) [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)

+ **ToonCrafter: Generative Cartoon Interpolation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Nov 2024)
   <details><summary>[ACM TOG] Jinbo Xing, Hanyuan Liu, Menghan Xia, et al.</summary> Yong Zhang, Xintao Wang, Ying Shan, Tien-Tsin Wong</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3687761) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/ToonCrafter/) [![Code](https://img.shields.io/github/stars/Doubiiu/ToonCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/ToonCrafter) [![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Doubiiu/tooncrafter)

+ **MagicStick: Controllable Video Editing via Control Handle Transformations** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Nov 2024)
   <details><summary>[WACV 2025] Yue Ma, Xiaodong Cun, Sen Liang, et al.</summary> Jinbo Xing, Yingqing He, Chenyang Qi, Siran Chen, Qifeng Chen</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03047) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://magic-stick-edit.github.io/) 


 + **Video Diffusion Models are Training-free Motion Interpreter and Controller** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Nov 2024)
   <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan, et al.</summary></details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864) [![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

+ **DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Nov 2024)
   <details><summary>Wenqiang Sun, Shuo Chen, Fangfu Liu, et al.</summary> Zilong Chen, Yueqi Duan, Jun Zhang, Yikai Wang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04928) [![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Star)](https://github.com/wenqsun/DimensionX) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenshuo20.github.io/DimensionX/)

+ **MotionClone: Training-Free Motion Cloning for Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Oct 2024)
   <details><summary>Pengyang Ling, Jiazi Bu, Pan Zhang, et al.</summary> Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian Chen, Jiaqi Wang, Yi Jin</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05338) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bujiazi.github.io/motionclone.github.io/) [![Code](https://img.shields.io/github/stars/LPengYang/MotionClone.svg?style=social&label=Star)](https://github.com/LPengYang/MotionClone)

+ **Boosting Camera Motion Control for Video Diffusion Transformers** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Oct 2024)
   <details><summary>Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, et al.</summary> Andrew Gilbert, Chun-Hao Paul Huang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10802) [![Code](https://img.shields.io/github/stars/soon-yau/CameraMotionGuidance.svg?style=social&label=Star)](https://github.com/soon-yau/CameraMotionGuidance) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://soon-yau.github.io/CameraMotionGuidance/)

+ **Cavia: Camera-controllable Multi-view Video Diffusion with View-Integrated Attention** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Oct 2024)
   <details><summary>Dejia Xu, Yifan Jiang, Chen Huang, et al.</summary> Liangchen Song, Thorsten Gernoth, Liangliang Cao, Zhangyang Wang, Hao Tang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10774) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ir1d.github.io/Cavia/)

+ **LVCD: Reference-based Lineart Video Colorization with Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Sep 2024)
   <details><summary> Zhitong Huang, Mohan Zhang, Jing Liao</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.12960) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://luckyhzt.github.io/lvcd) [![Code](https://img.shields.io/github/stars/luckyhzt/LVCD.svg?style=social&label=Star)](https://github.com/luckyhzt/LVCD)

+ **EasyControl: Transfer ControlNet to Video Diffusion for Controllable Generation and Interpolation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Sep 2024)
   <details><summary>Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary> Haoyu Zhao, Yuanfan Guo, Jianhua Han, Hang Xu, Xiaodan Liang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13005)

+ **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Sep 2024)
   <details><summary>Wangbo Yu, Jinbo Xing, Li Yuan, et al.</summary> Wenbo Hu, Xiaoyu Li, Zhipeng Huang, Xiangjun Gao, Tien-Tsin Wong, Ying Shan, Yonghong Tian</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048) [![Code](https://img.shields.io/github/stars/Drexubery/ViewCrafter.svg?style=social&label=Star)](https://github.com/Drexubery/ViewCrafter) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drexubery.github.io/ViewCrafter/)

+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Jul 2024)
   <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary> Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162) [![Code](https://img.shields.io/github/stars/Yangzhangcst/Transformer-in-Computer-Vision.svg?style=social&label=Star)](https://github.com/Yangzhangcst/Transformer-in-Computer-Vision/blob/main/main/diffusion.md) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/vd3d/gallery.html)

+ **MotionCtrl: A Unified and Flexible Motion Controller for Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Jul 2024)
   <details><summary>Zhouxia Wang, Ziyang Yuan, Xintao Wang, et al.</summary> Zhouxia Wang, Ziyang Yuan, Xintao Wang, Tianshui Chen, Menghan Xia, Ping Luo, Ying Shan</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641) [![Project Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wzhouxiff.github.io/projects/MotionCtrl/) [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/TencentARC/MotionCtrl)



+ **Ctrl-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 May 2024)
   <details><summary>[ICLR 2025] Han Lin, Jaemin Cho, Abhay Zala, et al.</summary> Mohit Bansal</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.09967) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ctrl-adapter.github.io/) [![Code](https://img.shields.io/github/stars/HL-hanlin/Ctrl-Adapter.svg?style=social&label=Star)](https://github.com/HL-hanlin/Ctrl-Adapter)


+ **A Recipe for Scaling up Text-to-Video Generation with Text-free Videos** (25 Dec 2023)<details><summary>[CVPR 2024] Xiang Wang, Shiwei Zhang, Hangjie Yuan, et al.</summary>
Zhiwu Qing, Biao Gong, Yingya Zhang, Yujun Shen, Changxin Gao, Nong Sang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.15770)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tf-t2v.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)

+ **VideoLCM: Video Latent Consistency Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Dec 2023)
   <details><summary>Xiang Wang, Shiwei Zhang, Han Zhang, et al.</summary> Yu Liu, Yingya Zhang, Changxin Gao, Nong Sang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09109)

+ **SparseCtrl: Adding Sparse Controls to Text-to-Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2023)
   <details><summary>Yuwei Guo, Ceyuan Yang, Anyi Rao, et al.</summary> Maneesh Agrawala, Dahua Lin, Bo Dai</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16933) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoyww.github.io/projects/SparseCtrl/) [![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl.svg?style=social&label=Star)](https://github.com/guoyww/AnimateDiff#202312-animatediff-v3-and-sparsectrl)


+ **Make Pixels Dance: High-Dynamic Video Generation** (18 Nov 2023)<details><summary>[CVPR 2024] Yan Zeng, Guoqiang Wei, Jiani Zheng, et al.</summary>
Jiaxin Zou, Yang Wei, Yuchen Zhang, Hang Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10982)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://arxiv.org/abs/2311.10982)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://makepixelsdance.github.io/demo.html)

+ **TaleCrafter: Interactive Story Visualization with Multiple Characters** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 May 2023)
   <details><summary>[SIGGRAPH Asia 2023] Yuan Gong, Youxin Pang, Xiaodong Cun, et al.</summary> Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/TaleCrafter/) [![Code](https://img.shields.io/github/stars/AILab-CVC/TaleCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/TaleCrafter)

+ **Sketching the Future(STF): Applying Conditional Control Techniques to Text-to-Video Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 May 2023)
   <details><summary>Rohan Dhesikan, Vignesh Rajmohan</summary></details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05845) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sketchingthefuture.github.io/) [![Code](https://img.shields.io/github/stars/rohandkn/skribble2vid.svg?style=social&label=Star)](https://github.com/rohandkn/skribble2vid) [![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://docs.google.com/forms/d/e/1FAIpQLSd9EGien53IkxOlbPkUx9n9ANu2N_FG6ySJaZASr_A1VCdxUQ/viewform?usp=sf_link)

+ **SketchBetween: Video-to-Video Synthesis for Sprite Animation via Sketches**  (1 Sep 2022)
   <details><summary>Dagmar Lukka Loftsdóttir, Matthew Guzdial</summary></details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.00185) 
   [![Code](https://img.shields.io/github/stars/ribombee/SketchBetween.svg?style=social&label=Star)](https://github.com/ribombee/SketchBetween)

+ **Sketch Me A Video**  (10 Oct 2021)
   <details><summary>Haichao Zhang, Gang Yu, Tao Chen, et al.</summary> Haichao Zhang, Gang Yu, Tao Chen, Guozhong Luo</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2110.04710)

+ **vid2vid:Video-to-Video Synthesis**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2018) <details><summary>Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, et al.</summary> Ting-Chun Wang, Ming-Yu Liu, Jun-Yan Zhu, Guilin Liu, Andrew Tao, Jan Kautz, Bryan Catanzaro</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1808.06601) [![Code](https://img.shields.io/github/stars/NVIDIA/vid2vid.svg?style=social&label=Star)](https://github.com/NVIDIA/vid2vid) [![Project](https://img.shields.io/badge/Project_Page-00CED1)]((https://tcwang0509.github.io/vid2vid/))


### 📦 BBox-Guided
<a id="-bbox-guided"></a>

<!-- RECENT_VERIFIED_START:BBox-Guided -->

+ **TrajectoryMover: Generative Movement of Object Trajectories in Videos** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (31 Mar 2026)
  <details><summary>Kiran Chhatre, Hyeonho Jeong, Yulia Gryaditskaya, et al.</summary>Kiran Chhatre, Hyeonho Jeong, Yulia Gryaditskaya, Christopher E. Peters, Chun-Hao Paul Huang, Paul Guerrero</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.29092) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chhatrekiran.github.io/trajectorymover/)

+ **InstanceV: Instance-Level Video Generation** (28 Nov 2025)
  <details><summary>Yuheng Chen, Teng Hu, Jiangning Zhang, et al.</summary>Yuheng Chen, Teng Hu, Jiangning Zhang, Zhucun Xue, Ran Yi, Lizhuang Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.23146) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aliothchen.github.io/projects/InstanceV)

+ **Realistic and Controllable 3D Gaussian-Guided Object Editing for Driving Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Aug 2025)
  <details><summary>Jiusi Li, Jackson Jiang, Jinyu Miao, et al.</summary>Jiusi Li, Jackson Jiang, Jinyu Miao, Miao Long, Tuopu Wen, Peijin Jia, Shengxiang Liu, Chunlei Yu, Maolin Liu, Yuzhan Cai, Kun Jiang, Mengmeng Yang, Diange Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.20471)

<!-- RECENT_VERIFIED_END:BBox-Guided -->

+ **HoloDrive: Holistic 2D-3D Multi-Modal Street Scene Generation for Autonomous Driving** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (02 Dec 2024)
   <details><summary>Zehuan Wu, Jingcheng Ni, Xiaodong Wang, et al.</summary>

   Zehuan Wu, Jingcheng Ni, Xiaodong Wang, Yuxin Guo, Rui Chen, Lewei Lu, Jifeng Dai, Yuwen Xiong</details>
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01407)

+ **Higher fidelity autonomous vehicle video generation with bounding-box controlled object motion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Dec 2024 )
   <details><summary>Ge Ya Luo, Zhi Hao Luo, et al.</summary>
   Ge Ya Luo, Zhi Hao Luo, Anthony Gosselin, Alexia Jolicoeur-Martineau, Christopher Pal</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.05630) [![Code](https://img.shields.io/github/stars/oooolga/Ctrl-V.svg?style=social&label=Star)](https://github.com/oooolga/Ctrl-V)

+ **MagicDrive-V2: High-Resolution Long Video Generation for Autonomous Driving with Adaptive Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Nov 2024)
   <details><summary>Ruiyuan Gao, Kai Chen, Bo Xiao, et al.</summary>
   Ruiyuan Gao, Kai Chen, Bo Xiao, Lanqing Hong, Zhenguo Li, Qiang Xu</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.13807)
   [![Code](https://img.shields.io/github/stars/flymin/MagicDrive-V2.svg?style=social&label=Star)](https://github.com/flymin/MagicDrive-V2)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](http://gaoruiyuan.com/magicdrive-v2/)

+ **DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View Driving Scenes** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (06 Sep 2024)
   <details><summary>Jianbiao Mei, Tao Hu, Xuemeng Yang, et al.</summary>
   Jianbiao Mei, Tao Hu, Xuemeng Yang, Licheng Wen, Yu Yang, Tiantian Wei, Yukai Ma, Min Dou, Botian Shi, Yong Liu</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.04003)
   [![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star)](https://github.com/PJLab-ADG/DriveArena)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pjlab-adg.github.io/DriveArena/dreamforge/)

+ **DriveScape: Towards High-Resolution Controllable Multi-View Driving Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (09 Sep 2024)
   <details><summary>Wei Wu, Xi Guo, Weixuan Tang, et al.</summary>
   Wei Wu, Xi Guo, Weixuan Tang, Tingxuan Huang, Chiyu Wang, Dongyue Chen, Chenjing Ding</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05463)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://metadrivescape.github.io/papers_project/drivescapev1/index.html)

+ **DriveScape: Towards High-Resolution Controllable Multi-View Driving Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (09 Sep 2024)
   <details><summary>Wei Wu, Xi Guo, Weixuan Tang, et al.</summary>
   Wei Wu, Xi Guo, Weixuan Tang, Tingxuan Huang, Chiyu Wang, Dongyue Chen, Chenjing Ding</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.05463)

+ **DiVE: DiT-based Video Generation with Enhanced Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (03 Sep 2024)
   <details><summary>Junpeng Jiang, Gangyi Hong, Lijun Zhou, et al.</summary>
   Junpeng Jiang, Gangyi Hong, Lijun Zhou, Enhui Ma, Hengtong Hu, Xia Zhou, Jie Xiang, Fan Liu, Kaicheng Yu, Haiyang Sun, Kun Zhan, Peng Jia, Miao Zhang</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01595)
   [![Code](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Star)](https://github.com/LiAutoAD/DIVE)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://liautoad.github.io/DIVE/)

+ **Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Jun 2024)
   <details><summary>Enhui Ma, Lijun Zhou, Tao Tang, et al.</summary>
   Enhui Ma, Lijun Zhou, Tao Tang, Zhan Zhang, Dong Han, Junpeng Jiang, Kun Zhan, Peng Jia, Xianpeng Lang, Haiyang Sun, Di Lin, Kaicheng Yu</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.01349)
   [![Code](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Star)](https://github.com/westlake-autolab/Delphi)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://westlake-autolab.github.io/delphi.github.io/)

- **Boximator: Generating Rich and Controllable Motions for Video Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Feb 2024)  
   <details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details> 

   
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01566)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boximator.github.io/)

+ **Panacea: Panoramic and Controllable Video Generation for Autonomous Driving** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2023)
   <details><summary>Yuqing Wen, Yucheng Zhao, Yingfei Liu, et al.</summary>
   Yuqing Wen, Yucheng Zhao, Yingfei Liu, Fan Jia, Yanhui Wang, Chong Luo, Chi Zhang, Tiancai Wang, Xiaoyan Sun, Xiangyu Zhang</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.16813)
   [![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://panacea-ad.github.io)

+ **MagicDrive: Street View Generation with Diverse 3D Geometry Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (04 Oct 2023)
   <details><summary>Ruiyuan Gao, Kai Chen, Enze Xie, et al.</summary>
   Ruiyuan Gao, Kai Chen, Enze Xie, Lanqing Hong, Zhenguo Li, Dit-Yan Yeung, Qiang Xu</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.02601)
   [![Code](https://img.shields.io/github/stars/cure-lab/MagicDrive.svg?style=social&label=Star)](https://github.com/cure-lab/MagicDrive)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](http://gaoruiyuan.com/magicdrive/)

+ **DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Sep 2023)
   <details><summary>Xiaofeng Wang, Zheng Zhu, Guan Huang, et al.</summary>
   Xiaofeng Wang, Zheng Zhu, Guan Huang, Xinze Chen, Jiagang Zhu, Jiwen Lu</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.09777)
   [![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/DriveDreamer)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://drivedreamer.github.io)

+ **LLM-grounded Video Diffusion Models**  (29 Sep 2023)
   <details><summary>Long Lian, Baifeng Shi, Adam Yala, et al.</summary>
   Long Lian, Baifeng Shi, Adam Yala, Trevor Darrell, Boyi Li</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.17444)
   [![Code](https://img.shields.io/github/stars/TonyLianLong/LLM-groundedVideoDiffusion.svg?style=social&label=Star)](https://github.com/TonyLianLong/LLM-groundedVideoDiffusion)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://llm-grounded-video-diffusion.github.io)

+ **Multi-object Video Generation from Single Frame Layouts** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (06 May 2023)
   <details><summary>Yang Wu, Zhibin Liu, Hefeng Wu, et al.</summary>
   Yang Wu, Zhibin Liu, Hefeng Wu, Liang Lin</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03983)

## 🧬 ID Control

### 🧑 Person-Guided
<a id="-person-guided"></a>

<!-- RECENT_VERIFIED_START:Person-Guided -->

+ **Customizing Video Portraits via Identity-ActionDecoupling** (21 Jun 2026)
  <details><summary>Junxiong Lin, Haoran Wang, Xinji Mai, et al.</summary>Junxiong Lin, Haoran Wang, Xinji Mai, Zeng Tao, Xuan Tong, Ivy Pan, Wenqiang Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.22347)

+ **ARGUS: Stacked Multi-View Identity Mosaic Injection for Subject-Preserving Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Jun 2026)
  <details><summary>Zijie Meng, Jiwen Liu, Yufei Liu, et al.</summary>Zijie Meng, Jiwen Liu, Yufei Liu, Chengzhuo Tong, Xiaoqiang Liu, Yuanxing Zhang, Yulong Xu, Pengfei Wan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.11670)

+ **HarmoView: Harmonizing Multi-View Constraints for Identity-Consistent Video Generation** (9 Jun 2026)
  <details><summary>Cong Wang, Zhentao Yu, Hongmei Wang, et al.</summary>Cong Wang, Zhentao Yu, Hongmei Wang, Weicong Liang, Zixiang Zhou, Zilin Yang, Jiarong Ou, Rui Chen, Yuan Zhou, Qinglin Lu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.10839) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://conallwang.github.io/HarmoView_Pages)

+ **Spatial-Temporal Decoupled Reference Conditioning for Identity-Preserving Text-to-Video Generation** (1 Jun 2026)
  <details><summary>Yuheng Chen, Teng Hu, Yuji Wang, et al.</summary>Yuheng Chen, Teng Hu, Yuji Wang, Qingdong He, Lizhuang Ma, Jiangning Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.02441)

+ **Advancing Narrative Long Video Generation via Training-Free Identity-Aware Memory** (18 May 2026)
  <details><summary>Jinzhuo Liu, Jiangning Zhang, Wencan Jiang, et al.</summary>Jinzhuo Liu, Jiangning Zhang, Wencan Jiang, Yabiao Wang, Dingkang Liang, Zhucun Xue, Ran Yi, Yong Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.18733) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eddie0521.github.io/projects/iamflow/)

+ **Omni-Customizer: End-to-End MultiModal Customization for Joint Audio-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 May 2026)
  <details><summary>Yuheng Chen, Qingdong He, Teng Hu, et al.</summary>Yuheng Chen, Qingdong He, Teng Hu, Yuji Wang, Yabiao Wang, Lizhuang Ma, Jiangning Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.17488)

+ **FaithfulFaces: Pose-Faithful Facial Identity Preservation for Text-to-Video Generation** (6 May 2026)
  <details><summary>Yuanzhi Wang, Xuhua Ren, Jiaxiang Cheng, et al.</summary>Yuanzhi Wang, Xuhua Ren, Jiaxiang Cheng, Bing Ma, Kai Yu, Sen Liang, Wenyue Li, Tianxiang Zheng, Qinglin Lu, Zhen Cui</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.04702)

+ **Gloria: Consistent Character Video Generation via Content Anchors** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (31 Mar 2026)
  <details><summary>Yuhang Yang, Fan Zhang, Huaijin Pi, et al.</summary>Yuhang Yang, Fan Zhang, Huaijin Pi, Shuai Guo, Guowei Xu, Wei Zhai, Yang Cao, Zheng-Jun Zha</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.29931) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yyvhang.github.io/Gloria_Page)

+ **AnyID: Ultra-Fidelity Universal Identity-Preserving Video Generation from Any Visual References** (26 Mar 2026)
  <details><summary>Jiahao Wang, Hualian Sheng, Sijia Cai, et al.</summary>Jiahao Wang, Hualian Sheng, Sijia Cai, Yuxiao Yang, Weizhan Zhang, Caixia Yan, Bing Deng, Jieping Ye</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.25188) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://johnneywang.github.io/AnyID-webpage)

+ **Identity-Consistent Video Generation under Large Facial-Angle Variations** (22 Mar 2026)
  <details><summary>Bin Hu, Zipeng Qi, Guoxi Huang, et al.</summary>Bin Hu, Zipeng Qi, Guoxi Huang, Zunnan Xu, Ruicheng Zhang, Chongjie Ye, Jun Zhou, Xiu Li, Jingdong Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.21299)

+ **LumosX: Relate Any Identities with Their Attributes for Personalized Video Generation** (20 Mar 2026)
  <details><summary>Jiazheng Xing, Fei Du, Hangjie Yuan, et al.</summary>Jiazheng Xing, Fei Du, Hangjie Yuan, Pengwei Liu, Hongbin Xu, Hai Ci, Ruigang Niu, Weihua Chen, Fan Wang, Yong Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.20192) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jiazheng-xing.github.io/lumosx-home/)

+ **Identity as Presence: Towards Appearance and Voice Personalized Joint Audio-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Mar 2026)
  <details><summary>Yingjie Chen, Shilun Lin, Cai Xing, et al.</summary>Yingjie Chen, Shilun Lin, Cai Xing, Binxin Yang, Long Zhou, Qixin Yan, Wenjing Wang, Dingming Liu, Hao Liu, Chen Li, Jing Lyu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.17889) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Identity-as-Presence)

+ **ID-LoRA: Identity-Driven Audio-Video Personalization with In-Context LoRA** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Mar 2026)
  <details><summary>Aviad Dahan, Moran Yanuka, Noa Kraicer, et al.</summary>Aviad Dahan, Moran Yanuka, Noa Kraicer, Lior Wolf, Raja Giryes</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.10256) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://id-lora.github.io)

+ **WildActor: Unconstrained Identity-Preserving Video Generation** (28 Feb 2026)
  <details><summary>Qin Guo, Tianyu Yang, Xuanhua He, et al.</summary>Qin Guo, Tianyu Yang, Xuanhua He, Fei Shen, Yong Zhang, Zhuoliang Kang, Xiaoming Wei, Dan Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00586) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wildactor.github.io)

+ **Slot-ID: Identity-Preserving Video Generation from Reference Videos via Slot-Based Temporal Identity Encoding** (4 Jan 2026)
  <details><summary>Yixuan Lai, He Wang, Kun Zhou, et al.</summary>Yixuan Lai, He Wang, Kun Zhou, Tianjia Shao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.01352)

+ **From Mannequin to Human: A Pose-Aware and Identity-Preserving Video Generation Framework for Lifelike Clothing Display** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Oct 2025)
  <details><summary>Xiangyu Mu, Dongliang Zhou, Jie Hou, et al.</summary>Xiangyu Mu, Dongliang Zhou, Jie Hou, Haijun Zhang, Weili Guan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.16833)

+ **Identity-GRPO: Optimizing Multi-Human Identity-preserving Video Generation via Reinforcement Learning** (16 Oct 2025)
  <details><summary>Xiangyu Meng, Zixian Zhang, Zhenghao Zhang, et al.</summary>Xiangyu Meng, Zixian Zhang, Zhenghao Zhang, Junchao Liao, Long Qin, Weizhi Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.14256)

+ **Identity-Preserving Image-to-Video Generation via Reward-Guided Optimization** (16 Oct 2025)
  <details><summary>Liao Shen, Wentao Jiang, Yiran Zhu, et al.</summary>Liao Shen, Wentao Jiang, Yiran Zhu, Jiahe Li, Tiezheng Ge, Zhiguo Cao, Bo Zheng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.14255) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ipro-alimama.github.io/)

+ **Lynx: Towards High-Fidelity Personalized Video Generation** (19 Sep 2025)
  <details><summary>Shen Sang, Tiancheng Zhi, Tianpei Gu, et al.</summary>Shen Sang, Tiancheng Zhi, Tianpei Gu, Jing Liu, Linjie Luo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.15496) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://byteaigc.github.io/Lynx/)

+ **Identity-Preserving Text-to-Video Generation via Training-Free Prompt, Image, and Guidance Enhancement** (1 Sep 2025)
  <details><summary>Jiayi Gao, Changcheng Hua, Qingchao Chen, et al.</summary>Jiayi Gao, Changcheng Hua, Qingchao Chen, Yuxin Peng, Yang Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.01362) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/Andyplus1/IPT2V.git)

+ **Collaborative Face Experts Fusion in Video Generation: Boosting Identity Consistency Across Large Face Poses** (13 Aug 2025)
  <details><summary>Yuji Wang, Moran Li, Xiaobin Hu, et al.</summary>Yuji Wang, Moran Li, Xiaobin Hu, Ran Yi, Jiangning Zhang, Chengming Xu, Weijian Cao, Yabiao Wang, Chengjie Wang, Lizhuang Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.09476) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://rain152.github.io/CoFE/)

+ **Stand-In: A Lightweight and Plug-and-Play Identity Control for Video Generation** (11 Aug 2025)
  <details><summary>Bowen Xue, Zheng-Peng Duan, Qixin Yan, et al.</summary>Bowen Xue, Zheng-Peng Duan, Qixin Yan, Wenjing Wang, Hao Liu, Chun-Le Guo, Chongyi Li, Chen Li, Jing Lyu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.07901)

+ **MoCA: Identity-Preserving Text-to-Video Generation via Mixture of Cross Attention** (5 Aug 2025)
  <details><summary>Qi Xie, Yongjia Ma, Donglin Di, et al.</summary>Qi Xie, Yongjia Ma, Donglin Di, Xuehao Gao, Xun Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.03034)

+ **Identity-Preserving Text-to-Video Generation Guided by Simple yet Effective Spatial-Temporal Decoupled Representations** (7 Jul 2025)
  <details><summary>Yuji Wang, Moran Li, Xiaobin Hu, et al.</summary>Yuji Wang, Moran Li, Xiaobin Hu, Ran Yi, Jiangning Zhang, Han Feng, Weijian Cao, Yabiao Wang, Chengjie Wang, Lizhuang Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.04705) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/rain152/IPVG)

<!-- RECENT_VERIFIED_END:Person-Guided -->

* **DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 May 2025)
   <details><summary>Junhao Chen, Mingjin Chen, Jianjin Xu, et al.</summary>  
         Junhao Chen, Mingjin Chen, Jianjin Xu, Xiang Li, Junting Dong, Mingze Sun, Puhua Jiang, Hongxiang Li, Yuhang Yang, Hao Zhao, Xiaoxiao Long, Ruqi Huang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.18078)


+ **MTVCrafter: 4D Motion Tokenization for Open-World Human Image Animation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(30 May 2025)
   <details><summary>Yanbo Ding, Xirui Hu, Zhizhi Guo, et al.</summary>  
         Yanbo Ding, Xirui Hu, Zhizhi Guo, Chi Zhang, Yali Wang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.10238)
   [![Code](https://img.shields.io/github/stars/DINGYANB/MTVCrafter.svg?style=social&label=Star)](https://github.com/DINGYANB/MTVCrafter)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://dingyanb.github.io/MTVCtafter/)

- **Frame In-N-Out: Unbounded Controllable Image-to-Video Generation** (27 May 2025)
  <details><summary>Boyang Wang, Xuweiyi Chen, Matheus Gadelha, et al.</summary> Boyang Wang, Xuweiyi Chen, Matheus Gadelha, Zezhou Cheng</details>  

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.21491)   [![Code](https://img.shields.io/github/stars/UVA-Computer-Vision-Lab/FrameINO.svg?style=social&label=Star)](https://github.com/UVA-Computer-Vision-Lab/FrameINO) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://uva-computer-vision-lab.github.io/Frame-In-N-Out/)


* **SkyReels-A2: Compose Anything in Video Diffusion Transformers**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Apr 2025)

  <details><summary>Zhengcong Fei, Debang Li, Di Qiu, et al.</summary>  
       Zhengcong Fei, Debang Li, Di Qiu, Jiahua Wang, Yikun Dou, Rui Wang, Jingtao Xu, Mingyuan Fan, Guibin Chen, Yang Li, Yahui Zhou</details>  
       
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730)  [![Code](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social&label=Star)](https://github.com/shiyi-zh0408/FlexiAct)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)


+ **AnimateAnywhere: Rouse the Background in Human Image Animation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Apr 2025)
   <details><summary>Xiaoyu Liu, Mingshuai Yao, Yabo Zhang, et al.</summary>  
         Xiaoyu Liu, Mingshuai Yao, Yabo Zhang, Xianhui Lin, Peiran Ren, Xiaoming Li, Ming Liu, Wangmeng Zuo</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.19834)


+ **Concat-ID: Towards Universal Identity-Preserving Video Synthesis**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Apr 2025)
   <details><summary>Yong Zhong, Zhuoyi Yang, Jiayan Teng, et al.</summary>  
         Yong Zhong, Zhuoyi Yang, Jiayan Teng, Xiaotao Gu, Chongxuan Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14151)
   [![Code](https://img.shields.io/github/stars/ML-GSAI/Concat-ID.svg?style=social&label=Star)](https://github.com/ML-GSAI/Concat-ID)







* **PERSONALVIDEO: High ID-Fidelity Video Customization with Static Images** (16 Mar 2025)

  <details><summary>Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, et al.</summary>  
         Hengjia Li, Haonan Qiu, Shiwei Zhang, Xiang Wang, Yujie Wei, Zekun Li, Yingya Zhang, Boxi Wu, Deng Cai</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17048)





* **AnyCharV: Bootstrap Controllable Character Video Generation with Fine-to-Coarse Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(12 Feb 2025)

  <details><summary>Zhao Wang, Hao Wen, Lingting Zhu, et al.</summary>  
         Zhao Wang, Hao Wen, Lingting Zhu, Chenming Shang, Yujiu Yang, Qi Dou</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08189)  [![Code](https://img.shields.io/github/stars/AnyCharV/AnyCharV.svg?style=social&label=Star)](https://github.com/AnyCharV/AnyCharV)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anycharv.github.io/)


* **Movie Weaver: Tuning-Free Multi-Concept Video Personalization with Anchored Prompts** (4 Feb 2025)

  <details><summary>Feng Liang, Haoyu Ma, Zecheng He, et al.</summary>  
         Feng Liang, Haoyu Ma, Zecheng He, Tingbo Hou, Ji Hou, Kunpeng Li, Xiaoliang Dai, Felix Juefei-Xu, Samaneh Azadi, Animesh Sinha, Peizhao Zhang, Peter Vajda, Diana Marculescu</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07802)





* **EchoVideo: Identity-Preserving Human Video Generation by Multimodal Feature Fusion** (23 Jan 2025)

  <details><summary>Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, et al.</summary>  
         Jiangchuan Wei, Shiyue Yan, Wenfeng Lin, Boyuan Liu, Renjie Chen, Mingyu Guo</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.13452)    [![Code](https://img.shields.io/github/stars/bytedance/EchoVideo.svg?style=social&label=Star)](https://github.com/bytedance/EchoVideo)




+ **VideoGen-of-Thought: Step-by-step generating multi-shot video with minimal manual intervention** (03 Dec 2024)<details><summary>Mingzhe Zheng, Yongqi Xu, Haojian Huang, et al.</summary>
        Mingzhe Zheng, Yongqi Xu, Haojian Huang, Xuran Ma, Yexin Liu, Wenjie Shu, Yatian Pang, Feilong Tang, Qifeng Chen, Harry Yang, Ser-Nam Lim</details>
      [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02259)
      [![Code](https://img.shields.io/github/stars/DuNGEOnmassster/VideoGen-of-Thought.svg?style=social&label=Star)](https://github.com/DuNGEOnmassster/VideoGen-of-Thought)
      [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://cheliosoops.github.io/VGoT/)


+ **Identity-Preserving Text-to-Video Generation by Frequency Decomposition** (25 Nov 2024)
  <details><summary> Shenghai Yuan, Jinfa Huang, et al.</summary>
        Shenghai Yuan, Jinfa Huang, Xianyi He, Yunyuan Ge, Yujun Shi, Liuhan Chen, Jiebo Luo, Li Yuan</details>

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17440)
   [![Code](https://img.shields.io/github/stars/PKU-YuanGroup/ConsisID.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/ConsisID)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://pku-yuangroup.github.io/ConsisID/)


+ **MIMO: Controllable Character Video Synthesis with Spatial Decomposed Modeling**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Sep 2024)<details><summary>Yifang Men, Yuan Yao, Miaomiao Cui, et al.</summary>
        Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.16160)
        [![Code](https://img.shields.io/github/stars/menyifang/MIMO.svg?style=social&label=Star)](https://github.com/menyifang/MIMO)
        [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://menyifang.github.io/projects/MIMO/index.html)


* **ID-Animator: Zero-Shot Identity-Preserving Human Video Generation** (25 Jun 2024)  
   <details><summary>Xuanhua He, Quande Liu, et al.</summary>  
         Xuanhua He, Quande Liu, Shengju Qian, Xin Wang, Tao Hu, Ke Cao, Keyu Yan, Jie Zhang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15275) 
   [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/ID-Animator/ID-Animator)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://id-animator.github.io)


* **Magic-Me: Identity-Specific Video Customized Diffusion** (14 Feb 2024)<details><summary>Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, et al.</summary>
        Ze Ma, Daquan Zhou, Chun-Hsiao Yeh, Xue-She Wang, Xiuyu Li, Huanrui Yang, Zhen Dong, Kurt Keutzer, Jiashi Feng</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.09368)
        [![Code](https://img.shields.io/github/stars/Zhen-Dong/Magic-Me.svg?style=social&label=Star)](https://github.com/Zhen-Dong/Magic-Me)


* **Vlogger: Make Your Dream A Vlog** (17 Jan 2024)<details><summary>Shaobin Zhuang, Kunchang Li, Xinyuan Chen, et al.</summary>
        Shaobin Zhuang, Kunchang Li, Xinyuan Chen, Yaohui Wang, Ziwei Liu, Yu Qiao, Yali Wang</details>
        [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09414)
        [![Code](https://img.shields.io/github/stars/zhuangshaobin/Vlogger.svg?style=social&label=Star)](https://github.com/zhuangshaobin/Vlogger)



### 🧑‍🤝‍🧑 Subject-Guided
<a id="-subject-guided"></a>

<!-- RECENT_VERIFIED_START:Subject-Guided -->

+ **DomainShuttle: Freeform Open Domain Subject-driven Text-to-video Generation** (24 Jun 2026)
  <details><summary>Nan Chen, Yiyang Cai, Rongchang Xie, et al.</summary>Nan Chen, Yiyang Cai, Rongchang Xie, Junwen Pan, Cheng Chen, Weinan Jia, Zhuowei Chen, Wen Zhou, Zhenbang Sun, Wenhan Luo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.26058)

+ **A Comprehensive Ecosystem for Open-Domain Customized Video Generation** (10 Jun 2026)
  <details><summary>Jingxu Zhang, Yuqian Hong, Daneul Kim, et al.</summary>Jingxu Zhang, Yuqian Hong, Daneul Kim, Kai Qiu, Qi Dai, Jianmin Bao, Yifan Yang, Xiaoyan Sun, Chong Luo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.11783)

+ **FashionChameleon: Towards Real-Time and Interactive Human-Garment Video Customization** (15 May 2026)
  <details><summary>Quanjian Song, Yefeng Shen, Mengting Chen, et al.</summary>Quanjian Song, Yefeng Shen, Mengting Chen, Hao Sun, Jinsong Lan, Xiaoyong Zhu, Bo Zheng, Liujuan Cao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.15824) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://quanjiansong.github.io/projects/FashionChameleon/)

+ **DreamShot: Personalized Storyboard Synthesis with Video Diffusion Prior** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Apr 2026)
  <details><summary>Junjia Huang, Binbin Yang, Pengxiang Yan, et al.</summary>Junjia Huang, Binbin Yang, Pengxiang Yan, Jiyang Liu, Bin Xia, Zhao Wang, Yitong Wang, Liang Lin, Guanbin Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.17195)

+ **Rethinking Position Embedding as a Context Controller for Multi-Reference and Multi-Shot Video Generation** (4 Apr 2026)
  <details><summary>Binyuan Huang, Yuning Lu, Weinan Jia, et al.</summary>Binyuan Huang, Yuning Lu, Weinan Jia, Hualiang Wang, Mu Liu, Daiqing Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.03738)

+ **RefAlign: Representation Alignment for Reference-to-Video Generation** (26 Mar 2026)
  <details><summary>Lei Wang, YuXin Song, Ge Wu, et al.</summary>Lei Wang, YuXin Song, Ge Wu, Haocheng Feng, Hang Zhou, Jingdong Wang, Yaxing Wang, Jian Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.25743) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/gudaochangsheng/RefAlign)

+ **3DreamBooth: High-Fidelity 3D Subject-Driven Video Generation Model** (19 Mar 2026)
  <details><summary>Hyun-kyu Ko, Jihyeon Park, Younghyun Kim, et al.</summary>Hyun-kyu Ko, Jihyeon Park, Younghyun Kim, Dongheok Park, Eunbyung Park</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.18524) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ko-lani.github.io/3DreamBooth/)

+ **LibraGen: Playing a Balance Game in Subject-Driven Video Generation** (13 Mar 2026)
  <details><summary>Jiahao Zhu, Shanshan Lao, Lijie Liu, et al.</summary>Jiahao Zhu, Shanshan Lao, Lijie Liu, Gen Li, Tianhao Qi, Wei Han, Bingchuan Li, Fangfang Liu, Zhuowei Chen, Tianxiang Ma, Qian HE, Yi Zhou, Xiaohua Xie</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.13506) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://phantom-video.github.io/LibraGen/)

+ **ConsID-Gen: View-Consistent and Identity-Preserving Image-to-Video Generation** (10 Feb 2026)
  <details><summary>Mingyang Wu, Ashirbad Mishra, Soumik Dey, et al.</summary>Mingyang Wu, Ashirbad Mishra, Soumik Dey, Shuo Xing, Naveen Ravipati, Hansi Wu, Binbin Li, Zhengzhong Tu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.10113) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://myangwu.github.io/ConsID-Gen)

+ **MV-S2V: Multi-View Subject-Consistent Video Generation** (25 Jan 2026)
  <details><summary>Ziyang Song, Xinyu Gong, Bangya Liu, et al.</summary>Ziyang Song, Xinyu Gong, Bangya Liu, Zelin Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.17756) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://szy-young.github.io/mv-s2v)

+ **RoboVIP: Multi-View Video Generation with Visual Identity Prompting Augments Robot Manipulation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jan 2026)
  <details><summary>Boyang Wang, Haoran Zhang, Shujie Zhang, et al.</summary>Boyang Wang, Haoran Zhang, Shujie Zhang, Jinkun Hao, Mingda Jia, Qi Lv, Yucheng Mao, Zhaoyang Lyu, Jia Zeng, Xudong Xu, Jiangmiao Pang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.05241) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://robovip.github.io/RoboVIP)

+ **V-Warper: Appearance-Consistent Video Diffusion Personalization via Value Warping** (13 Dec 2025)
  <details><summary>Hyunkoo Lee, Wooseok Jang, Jini Yang, et al.</summary>Hyunkoo Lee, Wooseok Jang, Jini Yang, Taehwan Kim, Sangoh Kim, Sangwon Jung, Seungryong Kim</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.12375) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cvlab-kaist.github.io/V-Warper)

+ **SMRABooth: Subject and Motion Representation Alignment for Customized Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Dec 2025)
  <details><summary>Xuancheng Xu, Yaning Li, Sisi You, et al.</summary>Xuancheng Xu, Yaning Li, Sisi You, Bing-Kun Bao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.12193) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://smrabooth.github.io)

+ **ContextAnyone: Context-Aware Diffusion for Character-Consistent Text-to-Video Generation** (8 Dec 2025)
  <details><summary>Ziyang Mai, Yu-Wing Tai</summary>Ziyang Mai, Yu-Wing Tai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.07328) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/ziyang1106/ContextAnyone)

+ **Scaling Zero-Shot Reference-to-Video Generation** (7 Dec 2025)
  <details><summary>Zijian Zhou, Shikun Liu, Haozhe Liu, et al.</summary>Zijian Zhou, Shikun Liu, Haozhe Liu, Haonan Qiu, Zhaochong An, Weiming Ren, Zhiheng Liu, Xiaoke Huang, Kam Woh Ng, Tian Xie, Xiao Han, Yuren Cong, Hang Li, Chuyan Zhu, Aditya Patel, Tao Xiang, Sen He</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.06905) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://franciszzj.github.io/Saber/)

+ **Bring Your Dreams to Life: Continual Text-to-Video Customization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Dec 2025)
  <details><summary>Jiahua Dong, Xudong Wang, Wenqi Liang, et al.</summary>Jiahua Dong, Xudong Wang, Wenqi Liang, Zongyan Han, Meng Cao, Duzhen Zhang, Hanbin Zhao, Zhi Han, Salman Khan, Fahad Shahbaz Khan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.05802) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/JiahuaDong/CCVD)

+ **BindWeave: Subject-Consistent Video Generation via Cross-Modal Integration** (1 Oct 2025)
  <details><summary>Zhaoyang Li, Dongjun Qian, Kai Su, et al.</summary>Zhaoyang Li, Dongjun Qian, Kai Su, Qishuai Diao, Xiangyang Xia, Chang Liu, Wenfei Yang, Tianzhu Zhang, Zehuan Yuan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.00438) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lzy-dot.github.io/BindWeave/)

+ **Tora2: Motion and Appearance Customized Diffusion Transformer for Multi-Entity Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jul 2025)
  <details><summary>Zhenghao Zhang, Junchao Liao, Xiangyu Meng, et al.</summary>Zhenghao Zhang, Junchao Liao, Xiangyu Meng, Long Qin, Weizhi Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.05963) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-videoai.github.io/Tora2_page/)

<!-- RECENT_VERIFIED_END:Subject-Guided -->

+ **DualReal: Joint Training for Lossless Identity-Motion Fusion in Video Customization**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 May 2025)
   <details><summary>Wenchuan Wang, Mengqi Huang, Yijing Tu, et al.</summary>  
         Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.02192)
  
+ **Concat-ID: Towards Universal Identity-Preserving Video Synthesis**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Apr 2025)
   <details><summary>Yong Zhong, Zhuoyi Yang, Jiayan Teng, et al.</summary>  
         Yong Zhong, Zhuoyi Yang, Jiayan Teng, Xiaotao Gu, Chongxuan Li</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14151)
   [![Code](https://img.shields.io/github/stars/ML-GSAI/Concat-ID.svg?style=social&label=Star)](https://github.com/ML-GSAI/Concat-ID)

+ **VideoMage: Multi-Subject and Motion Customization of Text-to-Video Diffusion Models**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Mar 2025)
   <details><summary>Chi-Pin Huang, Yen-Siang Wu, Hung-Kai Chung, et al.</summary>  
         Chi-Pin Huang, Yen-Siang Wu, Hung-Kai Chung, Kai-Po Chang, Fu-En Yang, Yu-Chiang Frank Wang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21781)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://jasper0314-huang.github.io/videomage-customization/)
  
* **DreamRelation: Relation-Centric Video Customization** (10 Mar 2025)

  <details><summary>Yujie Wei, Shiwei Zhang, Hangjie Yuan, et al.</summary>  
         Yujie Wei, Shiwei Zhang, Hangjie Yuan, Biao Gong, Longxiang Tang, Xiang Wang, Haonan Qiu, Hengjia Li, Shuai Tan, Yingya Zhang, Hongming Shan</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06033)

* **Get In Video: Add Anything You Want to the Video** (8 Mar 2025)

  <details><summary>Shaobin Zhuang, Zhipeng Huang, Binxin Yang, et al.</summary>  
         Shaobin Zhuang, Zhipeng Huang, Binxin Yang, Ying Zhang, Fangyikang Wang, Canmiao Fu, Chong Sun, Zheng-Jun Zha, Chen Li, Yali Wang</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.06268)

* **Phantom: Subject-consistent Video Generation via Cross-modal Alignment** (16 Feb 2025)

  <details><summary>Lijie Liu, Tianxiang Ma, Bingchuan Li, et al.</summary>  
         Lijie Liu, Tianxiang Ma, Bingchuan Li, Zhuowei Chen, Jiawei Liu, Qian He, Xinglong Wu</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11079)  [![Code](https://img.shields.io/github/stars/Phantom-video/Phantom.svg?style=social&label=Star)](https://github.com/Phantom-video/Phantom)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://phantom-video.github.io/Phantom/)

 


* **Multi-subject Open-set Personalization in Video Generation** (10 Jan 2025)

  <details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, et al.</summary>  
         Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Kwot Sin Lee, Ivan Skorokhodov, Kfir Aberman, Jun-Yan Zhu, Ming-Hsuan Yang, Sergey Tulyakov</details> 
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.06187)  
  [![Code](https://img.shields.io/github/stars/snap-research/MSRVTT-Personalization.svg?style=social&label=Star)](https://github.com/snap-research/MSRVTT-Personalization)  
  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/open-set-video-personalization/)

* **ConceptMaster: Multi-Concept Video Customization on Diffusion Transformer Models Without Test-Time Tuning** (8 Jan 2025)

  <details><summary>Yuzhou Huang, Ziyang Yuan, Quande Liu, et al.</summary>  
         Yuzhou Huang, Ziyang Yuan, Quande Liu, Qiulin Wang, Xintao Wang, Ruimao Zhang, Pengfei Wan, Di Zhang, Kun Gai</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.04698)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yuzhou914.github.io/ConceptMaster/)

* **VideoMaker: Zero-shot Customized Video Generation with the Inherent Force of Video Diffusion Models** (27 Dec 2024)

  <details><summary>Tao Wu, Yong Zhang, Xiaodong Cun, et al.</summary>  
         Tao Wu, Yong Zhang, Xiaodong Cun, Zhongang Qi, Junfu Pu, Huanzhang Dou, Guangcong Zheng, Ying Shan, Xi Li</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.19645)  [![Code](https://img.shields.io/github/stars/WuTao-CS/VideoMaker.svg?style=social&label=Star)](https://github.com/WuTao-CS/VideoMaker)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wutao-cs.github.io/VideoMaker/)

* **Customcrafter: Customized Video Generation with Preserving Motion and Concept Composition Abilities** (27 Dec 2024)

  <details><summary>Tao Wu, Yong Zhang, Xintao Wang, et al.</summary>  
         Tao Wu, Yong Zhang, Xintao Wang, Xianpan Zhou, Guangcong Zheng, Zhongang Qi, Ying Shan, Xi Li</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.13239)  [![Code](https://img.shields.io/github/stars/WuTao-CS/CustomCrafter.svg?style=social&label=Star)](https://github.com/WuTao-CS/CustomCrafter)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://customcrafter.github.io/)

* **CustomTTT: Motion and Appearance Customized Video Generation via Test-Time Training** (20 Dec 2024)

  <details><summary>Xiuli Bi, Jian Lu, Bo Liu, et al.</summary>  
         Xiuli Bi, Jian Lu, Bo Liu, Xiaodong Cun, Yong Zhang, Weisheng Li, Bin Xiao</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15646)  [![Code](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/RongPiKing/CustomTTT)

* **SUGAR: Subject-Driven Video Customization in a Zero-Shot Manner** (13 Dec 2024)

  <details><summary>Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, et al.</summary>  
         Yufan Zhou, Ruiyi Zhang, Jiuxiang Gu, Nanxuan Zhao, Jing Shi, Tong Sun</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.10533)

* **DreamRunner: Fine-Grained Compositional Story-to-Video Generation with Retrieval-Augmented Motion Adaptation** (25 Nov 2024)

  <details><summary>Zun Wang, Jialu Li, Han Lin, et al.</summary>  
         Zun Wang, Jialu Li, Han Lin, Jaehong Yoon, Mohit Bansal</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16657)   [![Code](https://img.shields.io/github/stars/wz0919/DreamRunner.svg?style=social&label=Star)](https://github.com/wz0919/DreamRunner)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zunwang1.github.io/DreamRunner)

* **VideoAlchemy: Open-set Personalization in Video Generation** (15 Nov 2024)

  <details><summary>Tsai-Shien Chen, Aliaksandr Siarohin, et al.</summary>  
         Tsai-Shien Chen, Aliaksandr Siarohin, Willi Menapace, Yuwei Fang, Ivan Skorokhodov, Jun-Yan Zhu, Kfir Aberman, Ming-Hsuan Yang, Sergey Tulyakov</details>  
         
  [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=popKM1zAYa)

* **StoryAgent: Customized Storytelling Video Generation via Multi-Agent Collaboration** (7 Nov 2024)

  <details><summary>Panwen Hu, Jin Jiang, Jianqi Chen, et al.</summary>  
         Panwen Hu, Jin Jiang, Jianqi Chen, Mingfei Han, Shengcai Liao, Xiaojun Chang, Xiaodan Liang</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04925)

* **MotionBooth: Motion-Aware Customized Text-to-Video Generation** (29 Oct 2024)

  <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>  
         Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)    [![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/motionbooth/)

* **Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation** (19 Aug 2024)

  <details><summary>Yunxin Li, Haoyuan Shi, Baotian Hu, et al.</summary>  
         Yunxin Li, Haoyuan Shi, Baotian Hu, Longyue Wang, Jiashun Zhu, Jinyi Xu, Zhen Zhao, Min Zhang</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.09787)    [![Code](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)](https://github.com/HITsz-TMG/Anim-Director)

* **Still-Moving: Customized Video Generation Without Customized Video Data** (11 Jul 2024)

  <details><summary>Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, et al.</summary>  
         Hila Chefer, Shiran Zada, Roni Paiss, Ariel Ephrat, Omer Tov, Michael Rubinstein, Lior Wolf, Tali Dekel, Tomer Michaeli, Inbar Mosseri</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08674)  [![Code](https://img.shields.io/github/stars/harshbhatt7585/StillMoving.svg?style=social&label=Star)](https://github.com/harshbhatt7585/StillMoving)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://still-moving.github.io/)

* **VIMI: Grounding Video Generation through Multi-modal Instruction** (8 Jul 2024)

  <details><summary>Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, et al.</summary>  
         Yuwei Fang, Willi Menapace, Aliaksandr Siarohin, Tsai-Shien Chen, Kuan-Chien Wang, Ivan Skorokhodov, Graham Neubig, Sergey Tulyakov</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.06304)

* **Customvideo: Customizing Text-to-Video Generation with Multiple Subjects** (22 May 2024)

  <details><summary>Zhao Wang, Aoxue Li, et al.</summary>  
         Zhao Wang, Aoxue Li, Lingting Zhu, Yong Guo, Qi Dou, Zhenguo Li</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09962)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kyfafyd.wang/projects/customvideo/)

* **DisenStudio: Customized Multi-subject Text-to-Video Generation with Disentangled Spatial Control** (21 May 2024)

  <details><summary>Hong Chen, Xin Wang, Yipeng Zhang, et al.</summary>  
         Hong Chen, Xin Wang, Yipeng Zhang, Yuwei Zhou, Zeyang Zhang, Siao Tang, Wenwu Zhu</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.12796)   [![GitHub](https://img.shields.io/github/stars/forchchch/disenstudio.github.io.svg?style=social&label=Star)](https://github.com/forchchch/disenstudio.github.io)

* **Lumina-T2X: Transforming Text into Any Modality, Resolution, and Duration via Flow-based Large Diffusion Transformers** (9 May 2024)

  <details><summary>Peng Gao, Le Zhuo, Dongyang Liu, et al.</summary>  
         Peng Gao, Le Zhuo, Dongyang Liu, Ruoyi Du, Xu Luo, Longtian Qiu, Yuhang Zhang, Chen Lin, Rongjie Huang, Shijie Geng, Renrui Zhang, Junlin Xi, Wenqi Shao, Zhengkai Jiang, Tianshuo Yang, Weicai Ye, He Tong, Jingwen He, Yu Qiao, Hongsheng Li</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.05945)   [![Code](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-T2X.svg?style=social&label=Star)](https://github.com/Alpha-VLLM/Lumina-T2X)

* **SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control** (28 Mar 2024)

  <details><summary>Zheng Chen, Di Qiu, Rui Wang, et al.</summary>  
         Zheng Chen, Di Qiu, Rui Wang, Binyuan Huang, Yuqing Wen, Yucheng Zhao, Yaosi Hu, Yingfei Liu, Fan Jia, Weixin Mao, Tiancai Wang, Chi Zhang, Chang Wen Chen, Zhenzhong Chen, Xiangyu Zhang</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.19438)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://subjectdrive.github.io/)

* **AesopAgent: Agent-driven Evolutionary System on Story-to-Video Production** (12 Mar 2024)

  <details><summary>Jiuniu Wang, Zehua Du, Yuyuan Zhao, et al.</summary>  
         Jiuniu Wang, Zehua Du, Yuyuan Zhao, Bo Yuan, Kexiang Wang, Jian Liang, Yaxi Zhao, Yihen Lu, Gengliang Li, Junlong Gao, Xin Tu, Zhenyu Guo</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07952)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aesopai.github.io/)

* **VideoDrafter: Content-Consistent Multi-Scene Video Generation with LLM** (2 Jan 2024)

  <details><summary>Fuchen Long, Zhaofan Qiu, Ting Yao, et al.</summary>  
         Fuchen Long, Zhaofan Qiu, Ting Yao, Tao Mei</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.01256)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodrafter.github.io/)

* **Dreamvideo: Composing Your Dream Videos with Customized Subject and Motion** (7 Dec 2023)

  <details><summary>Yujie Wei, Shiwei Zhang, Zhiwu Qing, et al.</summary>  
         Yujie Wei, Shiwei Zhang, Zhiwu Qing, Hangjie Yuan, Zhiheng Liu, Yu Liu, Yingya Zhang, Jingren Zhou, Hongming Shan</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.04433)   [![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamvideo-t2v.github.io/)

* **VideoBooth: Diffusion-based Video Generation with Image Prompts** (1 Dec 2023)

  <details><summary>Yuming Jiang, Tianxing Wu, Shuai Yang, et al.</summary>  
         Yuming Jiang, Tianxing Wu, Shuai Yang, Chenyang Si, Dahua Lin, Yu Qiao, Chen Change Loy, Ziwei Liu</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00777)   [![Code](https://img.shields.io/github/stars/Vchitect/VideoBooth.svg?style=social&label=Star)](https://github.com/Vchitect/VideoBooth)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/VideoBooth-project/)

* **Videodreamer: Customized Multi-Subject Text-to-Video Generation with Disen-Mix Finetuning** (2 Nov 2023)

  <details><summary>Hong Chen, Xin Wang, Guanning Zeng, et al.</summary>  
         Hong Chen, Xin Wang, Guanning Zeng, Yipeng Zhang, Yuwei Zhou, Feilin Han, Wenwu Zhu</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.00990)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://videodreamer23.github.io/)

* **Animate-A-Story: Storytelling with Retrieval-Augmented Video Generation** (13 Jul 2023)

  <details><summary>Yingqing He, Menghan Xia, Haoxin Chen, et al.</summary>  
         Yingqing He, Menghan Xia, Haoxin Chen, Xiaodong Cun, Yuan Gong, Jinbo Xing, Yong Zhang, Xintao Wang, Chao Weng, Ying Shan, Qifeng Chen</details> 
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.06940)   [![Code](https://img.shields.io/github/stars/VideoCrafter/Animate-A-Story.svg?style=social&label=Star)](https://github.com/VideoCrafter/Animate-A-Story)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/Animate-A-Story/)

* **TaleCrafter: Interactive Story Visualization with Multiple Characters** (30 May 2023)

  <details><summary>Yuan Gong, Youxin Pang, et al.</summary>  
         Yuan Gong, Youxin Pang, Xiaodong Cun, Menghan Xia, Yingqing He, Haoxin Chen, Longyue Wang, Yong Zhang, Xintao Wang, Ying Shan, Yujiu Yang</details>  
         
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.18247)    [![GitHub](https://img.shields.io/github/stars/RongPiKing/CustomTTT.svg?style=social&label=Star)](https://github.com/VideoCrafter/TaleCrafter)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/TaleCrafter/)

* **Dreamix: Video Diffusion Models are General Video Editors** (2 Feb 2023)

  <details><summary>Eyal Molad, Eliahu Horwitz, et al.</summary>  
         Eyal Molad, Eliahu Horwitz, Dani Valevski, Alex Rav Acha, Yossi Matias, Yael Pritch, Yaniv Leviathan, Yedid Hoshen</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.01329)  


## 🖼️ Image Control

<!-- RECENT_VERIFIED_START:Image Control -->

+ **SmartDirector: Keyframe-Conditioned Cinematic Video Generation with Narrative Pacing Control** (27 May 2026)
  <details><summary>Zhida Zhang, Jie Ma, Zhan Peng, et al.</summary>Zhida Zhang, Jie Ma, Zhan Peng, Haoxue Wu, Yang Han, Jun Liang, Jie Cao, Jing Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.27891) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://orange-3dv-team.github.io/SmartDirector/)

+ **PhysLayer: Language-Guided Layered Animation with Depth-Aware Physics** (26 Apr 2026)
  <details><summary>Tianyidan Xie, Zhentao Huang, Mingjie Wang, et al.</summary>Tianyidan Xie, Zhentao Huang, Mingjie Wang, Xin Huang, Jun Zhou, Minglun Gong, Zili Yi</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.23574)

+ **PISCO: Precise Video Instance Insertion with Sparse Control** (9 Feb 2026)
  <details><summary>Xiangbo Gao, Renjie Li, Xinghao Chen, et al.</summary>Xiangbo Gao, Renjie Li, Xinghao Chen, Yuheng Wu, Suofei Feng, Qing Yin, Zhengzhong Tu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.08277) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiangbogaobarry.github.io/PISCO)

+ **Focal Guidance: Unlocking Controllability from Semantic-Weak Layers in Video Diffusion Models** (12 Jan 2026)
  <details><summary>Yuanyang Yin, Yufan Deng, Shenghai Yuan, et al.</summary>Yuanyang Yin, Yufan Deng, Shenghai Yuan, Kaipeng Zhang, Xiao Yang, Feng Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.07287)

+ **DreaMontage: Arbitrary Frame-Guided One-Shot Video Generation** (24 Dec 2025)
  <details><summary>Jiawei Liu, Junqiao Li, Jiangfan Deng, et al.</summary>Jiawei Liu, Junqiao Li, Jiangfan Deng, Gen Li, Siyu Zhou, Zetao Fang, Shanshan Lao, Zengde Deng, Jianing Zhu, Tingting Ma, Jiayi Li, Yunqiu Wang, Qian He, Xinglong Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.21252) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamontage.github.io/DreaMontage)

+ **SneakPeek: Future-Guided Instructional Streaming Video Generation** (15 Dec 2025)
  <details><summary>Cheeun Hong, German Barquero, Fadime Sener, et al.</summary>Cheeun Hong, German Barquero, Fadime Sener, Markos Georgopoulos, Edgar Schönfeld, Stefan Popov, Yuming Du, Oscar Mañas, Albert Pumarola</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.13019)

+ **STAGE: Storyboard-Anchored Generation for Cinematic Multi-shot Narrative** (13 Dec 2025)
  <details><summary>Peixuan Zhang, Zijian Jia, Kaiqi Liu, et al.</summary>Peixuan Zhang, Zijian Jia, Kaiqi Liu, Shuchen Weng, Si Li, Boxin Shi</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.12372)

+ **Open-world Hand-Object Interaction Video Generation Based on Structure and Contact-aware Representation** (1 Dec 2025)
  <details><summary>Haodong Yan, Hang Yu, Zhide Zhong, et al.</summary>Haodong Yan, Hang Yu, Zhide Zhong, Weilin Yuan, Xin Gong, Zehang Luo, Chengxi Heyu, Junfeng Li, Wenxuan Song, Shunbo Zhou, Haoang Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.01677) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hgzn258.github.io/SCAR/)

+ **Show Me: Unifying Instructional Image and Video Generation with Diffusion Models** (21 Nov 2025)
  <details><summary>Yujiang Pu, Zhanbo Huang, Vishnu Boddeti, et al.</summary>Yujiang Pu, Zhanbo Huang, Vishnu Boddeti, Yu Kong</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.17839) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yujiangpu20.github.io/showme/)

+ **Video-As-Prompt: Unified Semantic Control for Video Generation** (23 Oct 2025)
  <details><summary>Yuxuan Bian, Xin Chen, Zenan Li, et al.</summary>Yuxuan Bian, Xin Chen, Zenan Li, Tiancheng Zhi, Shen Sang, Linjie Luo, Qiang Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.20888) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bytedance.github.io/Video-As-Prompt)

+ **VideoCanvas: Unified Video Completion from Arbitrary Spatiotemporal Patches via In-Context Conditioning** (9 Oct 2025)
  <details><summary>Minghong Cai, Qiulin Wang, Zongli Ye, et al.</summary>Minghong Cai, Qiulin Wang, Zongli Ye, Wenze Liu, Quande Liu, Weicai Ye, Xintao Wang, Pengfei Wan, Kun Gai, Xiangyu Yue</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08555) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://onevfall.github.io/project_page/videocanvas/)

+ **SSG-Dit: A Spatial Signal Guided Framework for Controllable Video Generation** (23 Aug 2025)
  <details><summary>Peng Hu, Yu Gu, Liang Luo, et al.</summary>Peng Hu, Yu Gu, Liang Luo, Fuji Ren</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.17062)

+ **Consistent and Controllable Image Animation with Motion Linear Diffusion Transformers** (10 Aug 2025)
  <details><summary>Xin Ma, Yaohui Wang, Genyun Jia, et al.</summary>Xin Ma, Yaohui Wang, Genyun Jia, Xinyuan Chen, Tien-Tsin Wong, Cunjian Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.07246)

<!-- RECENT_VERIFIED_END:Image Control -->

<a id="-image-control"></a>

+ **Frame Guidance: Training-Free Guidance for Frame-Level Control in Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jun 2025)
   <details><summary>Sangwon Jang, Taekyung Ki, Jaehyeong Jo, et al.</summary>  
         Sangwon Jang, Taekyung Ki, Jaehyeong Jo, Jaehong Yoon, Soo Ye Kim, Zhe Lin, Sung Ju Hwang</details> 

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07177)
   [![Code](https://img.shields.io/github/stars/agwmon/frame-guidance.svg?style=social&label=Star)](https://github.com/agwmon/frame-guidance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://frame-guidance-video.github.io/)
* **DanceTogether! Identity-Preserving Multi-Person Interactive Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 May 2025)
   <details><summary>Junhao Chen, Mingjin Chen, Jianjin Xu, et al.</summary>  
         Junhao Chen, Mingjin Chen, Jianjin Xu, Xiang Li, Junting Dong, Mingze Sun, Puhua Jiang, Hongxiang Li, Yuhang Yang, Hao Zhao, Xiaoxiao Long, Ruqi Huang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.18078)

+ **OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding** (15 Apr 2025)<details><summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, et al.</summary>
Xi Qiu, Yuchi Huo, Rui Wang, Chi Zhang, Xuelong Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.10825)
[![Code](https://img.shields.io/github/stars/Tele-AI/OmniVDiff.svg?style=social&label=Star)](https://github.com/Tele-AI/OmniVDiff.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tele-ai.github.io/OmniVDiff/)

+ **HunyuanVideo: A Systematic Framework For Large Video Generative Models**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Mar 2025)<details><summary>Weijie Kong, Qi Tian, Zijian Zhang, et al.</summary>Rox Min, Zuozhuo Dai, Jin Zhou, Jiangfeng Xiong, Xin Li, Bo Wu, Jianwei Zhang, Kathrina Wu, Qin Lin, Junkun Yuan, Yanxin Long, Aladdin Wang, Andong Wang, Changlin Li, Duojun Huang, Fang Yang, Hao Tan, Hongmei Wang, Jacob Song, Jiawang Bai, Jianbing Wu, Jinbao Xue, Joey Wang, Kai Wang, Mengyang Liu, Pengyu Li, Shuai Li, Weiyan Wang, Wenqing Yu, Xinchi Deng, Yang Li, Yi Chen, Yutao Cui, Yuanbo Peng, Zhentao Yu, Zhiyu He, Zhiyong Xu, Zixiang Zhou, Zunnan Xu, Yangyu Tao, Qinglin Lu, Songtao Liu, Dax Zhou, Hongfa Wang, Yong Yang, Di Wang, Yuhong Liu, Jie Jiang, Caesar Zhong</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://arxiv.org/abs/2412.03603)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aivideo.hunyuan.tencent.com/)
[![Code](https://img.shields.io/github/stars/Tencent/HunyuanVideo-I2V.svg?style=social&label=Star)](https://github.com/Tencent/HunyuanVideo-I2V)

+ **Extrapolating and Decoupling Image-to-Video Generation Models: Motion Modeling is Easier Than You Think** (2 Mar 2025)<details><summary>[CVPR 2025] Jie Tian, Xiaoye Qu, Zhenyi Lu, et al.</summary>Wei Wei, Sichen Liu, Yu Cheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00948)
[![Code](https://img.shields.io/github/stars/Chuge0335/EDG.svg?style=social&label=Star)](https://github.com/Chuge0335/EDG)

+ **Adapting Image-to-Video Diffusion Models for Large-Motion Frame Interpolation** (17 Feb 2025)<details><summary>Luoxu Jin, Hiroshi Watanabe</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.17042)

+ **Generative Inbetweening: Adapting Image-to-Video Models for Keyframe Interpolation** (12 Feb 2025)<details><summary>[ICLR 2025] Xiaojuan Wang, Boyang Zhou, Brian Curless, et al.</summary>Ira Kemelmacher-Shlizerman, Aleksander Holynski, Steven M. Seitz</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.15239)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://svd-keyframe-interpolation.github.io/)
[![Code](https://img.shields.io/github/stars/jeanne-wang/svd_keyframe_interpolation.svg?style=social&label=Star)](https://github.com/jeanne-wang/svd_keyframe_interpolation)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/svd_keyframe_interpolation)


+ **Autoregressive Video Generation without Vector Quantization** (9 Jan 2025)<details><summary>[ICLR 2025] Haoge Deng, Ting Pan, Haiwen Diao, et al.</summary>Zhengxiong Luo, Yufeng Cui, Huchuan Lu, Shiguang Shan, Yonggang Qi, Xinlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.14169)
[![Code](https://img.shields.io/github/stars/baaivision/NOVA.svg?style=social&label=Star)](https://github.com/baaivision/NOVA)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BAAI/nova-d48w1024-osp480)


+ **Through-The-Mask: Mask-based Motion Trajectories for Image-to-Video Generation** (6 Jan 2025)<details><summary>[CVPR 2025] Guy Yariv, Yuval Kirstain, Amit Zohar, et al.</summary>Shelly Sheynin, Yaniv Taigman, Yossi Adi, Sagie Benaim, Adam Polyak</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03059)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guyyariv.github.io/TTM/)





+ **STIV: Scalable Text and Image Conditioned Video Generation** (10 Dec 2024)<details><summary>Zongyu Lin, Wei Liu, Chen Chen, et al.</summary>Jiasen Lu, Wenze Hu, Tsu-Jui Fu, Jesse Allardice, Zhengfeng Lai, Liangchen Song, Bowen Zhang, Cha Chen, Yiran Fei, Yifan Jiang, Lezhi Li, Yizhou Sun, Kai-Wei Chang, Yinfei Yang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07730)

+ **MotionStone: Decoupled Motion Intensity Modulation with Diffusion Transformer for Image-to-Video Generation** (8 Dec 2024)<details><summary>Shuwei Shi, Biao Gong, Xi Chen, et al.</summary>Dandan Zheng, Shuai Tan, Zizheng Yang, Yuyuan Li, Jingwen He, Kecheng Zheng, Jingdong Chen, Ming Yang, Yinqiang Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.05848)

+ **Lumiere: A Space-Time Diffusion Model for Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2024)<details><summary>[SIGGRAPH Asia 2024] Omer Bar-Tal, Hila Chefer, Omer Tov, et al.</summary>Charles Herrmann, Roni Paiss, Shiran Zada, Ariel Ephrat, Junhwa Hur, Guanghui Liu, Amit Raj, Yuanzhen Li, Michael Rubinstein, Tomer Michaeli, Oliver Wang, Deqing Sun, Tali Dekel, Inbar Mosseri</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/full/10.1145/3680528.3687614)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lumiere-video.github.io/)

+ **Identifying and Solving Conditional Image Leakage in Image-to-Video Diffusion Model** (6 Nov 2024)<details><summary>[NeurIPS 2024] Min Zhao, Hongzhou Zhu, Chendong Xiang, et al.</summary>Kaiwen Zheng, Chongxuan Li, Jun Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15735)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cond-image-leak.github.io/)
[![Code](https://img.shields.io/github/stars/thu-ml/cond-image-leakage.svg?style=social&label=Star)](https://github.com/thu-ml/cond-image-leakage)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Xiang-cd/DynamiCrafter-CIL)


+ **FrameBridge: Improving Image-to-Video Generation with Bridge Models** (20 Oct 2024)<details><summary>Yuji Wang, Zehua Chen, Xiaoyu Chen, et al.</summary>Jun Zhu, Jianfei Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15371)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://framebridge-demo.github.io/)



+ **I4VGen: Image as Free Stepping Stone for Text-to-Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Oct 2024)<details><summary>Xiefan Guo, Jinlin Liu, Miaomiao Cui, et al.</summary>Liefeng Bo, Di Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02230)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiefan-guo.github.io/i4vgen/)
[![Code](https://img.shields.io/github/stars/xiefan-guo/i4vgen.svg?style=social&label=Star)](https://github.com/xiefan-guo/i4vgen)


+ **DynamiCrafter: Animating Open-Domain Images with Video Diffusion Priors** (1 Oct 2024)<details><summary>[ECCV 2024] Jinbo Xing, Menghan Xia, Yong Zhang,  et al.</summary>Haoxin Chen, Wangbo Yu, Hanyuan Liu, Gongye Liu, Xintao Wang, Ying Shan, Tien-Tsin Wong</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://link.springer.com/chapter/10.1007/978-3-031-72952-2_23)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://doubiiu.github.io/projects/DynamiCrafter/)
[![Code](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Star)](https://github.com/Doubiiu/DynamiCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/Doubiiu/DynamiCrafter)



+ **PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation** (27 Sep 2024)<details><summary>[ECCV 2024] Shaowei Liu, Zhongzheng Ren, Saurabh Gupta, et al.</summary>Shenlong Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.18964)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://stevenlsw.github.io/physgen/)
[![Code](https://img.shields.io/github/stars/stevenlsw/physgen.svg?style=social&label=Star)](https://github.com/stevenlsw/physgen)


+ **Structure and Content-Guided Video Synthesis with Diffusion Models** (27 Sep 2024)<details><summary>[ICCV 2023] Patrick Esser, Johnathan Chiu, Parmida Atighehchian, et al.</summary>Jonathan Granskog, Anastasis Germanidis</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/html/Esser_Structure_and_Content-Guided_Video_Synthesis_with_Diffusion_Models_ICCV_2023_paper.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://runwayml.com/research/gen-1)

+ **DreamVideo: High-Fidelity Image-to-Video Generation with Image Retention and Text Guidance** (16 Sep 2024)<details><summary>[ICASSP 2025] Cong Wang, Jiaxi Gu, Panwen Hu, et al.</summary>Songcen Xu, Hang Xu, Xiaodan Liang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/abstract/document/10887583)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anonymous0769.github.io/DreamVideo/)
[![Code](https://img.shields.io/github/stars/anonymous0769/DreamVideo.svg?style=social&label=Star)](https://github.com/anonymous0769/DreamVideo)



+ **Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning** (2 Aug 2024)<details><summary>[ECCV 2024] Rohit Girdhar, Mannat Singh, Andrew Brown, et al.</summary>Quentin Duval, Samaneh Azadi, Sai Saketh Rambhatla, Akbar Shah, Xi Yin, Devi Parikh, Ishan Misra</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.10709)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://emu-video.metademolab.com/)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://emu-video.metademolab.com/#/demo)


+ **MoVideo: Motion-Aware Video Generation with Diffusion Model** (29 Jul 2024)<details><summary>[ECCV 2024] Jingyun Liang, Yuchen Fan, Kai Zhang, et al.</summary>Radu Timofte, Luc Van Gool, Rakesh Ranjan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.11325)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyunliang.github.io/MoVideo/)


+ **I2V-Adapter: A General Image-to-Video Adapter for Diffusion Models** (13 Jul 2024)<details><summary>[ACM SIGGRAPH 2024] Xun Guo1, Mingwu Zheng, Liang Hou, et al.</summary>Yuan Gao, Yufan Deng, Pengfei Wan,
Di Zhang, Yufan Liu, Weiming Hu, Zhengjun Zha, Haibin Huang, Chongyang Ma</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657407)



+ **EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture** (5 Jul 2024)<details><summary>Jiaqi Xu, Xinyi Zou, Kunzhe Huang, et al.</summary>Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.18991)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://easyanimate.github.io/)
[![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Star)](https://github.com/aigc-apps/EasyAnimate)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/alibaba-pai/EasyAnimate)


+ **ConsistI2V: Enhancing Visual Consistency for Image-to-Video Generation** (1 Jul 2024)<details><summary>[TMLR 2024] Weiming Ren, Huan Yang, Ge Zhang, et al.</summary>Cong Wei, Xinrun Du, Wenhao Huang, Wenhu Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.04324)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tiger-ai-lab.github.io/ConsistI2V/)
[![Code](https://img.shields.io/github/stars/TIGER-AI-Lab/ConsistI2V.svg?style=social&label=Star)](https://github.com/TIGER-AI-Lab/ConsistI2V)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/TIGER-Lab/ConsistI2V)



+ **OmniTokenizer: A Joint Image-Video Tokenizer for Visual Generation** (13 Jun 2024)<details><summary>[NeurIPS 2024] Junke Wang, Yi Jiang, Zehuan Yuan, et al.</summary>Binyue Peng, Zuxuan Wu, Yu-Gang Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.09399)
[![Code](https://img.shields.io/github/stars/FoundationVision/OmniTokenizer.svg?style=social&label=Star)](https://github.com/FoundationVision/OmniTokenizer)



+ **AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction** (10 Jun 2024)<details><summary>Zhen Xing, Qi Dai, Zejia Weng, et al.</summary>Zuxuan Wu, Yu-Gang Jiang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.06465)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenhsing.github.io/AID/)
[![Code](https://img.shields.io/github/stars/ChenHsing/AID.svg?style=social&label=Star)](https://github.com/ChenHsing/AID)


+ **TI2V-Zero: Zero-Shot Image Conditioning for Text-to-Video Diffusion Models** (25 Apr 2024)<details><summary>[CVPR 2024] Haomiao Ni, Bernhard Egger, Suhas Lohit, et al.</summary>Anoop Cherian, Ye Wang, Toshiaki Koike-Akino, Sharon X. Huang, Tim K. Marks</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.16306)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.merl.com/demos/TI2V-Zero)
[![Code](https://img.shields.io/github/stars/merlresearch/TI2V-Zero.svg?style=social&label=Star)](https://github.com/merlresearch/TI2V-Zero)



+ **TRIP: Temporal Residual Learning with Image Noise Prior for Image-to-Video Diffusion Models** (25 Mar 2024)<details><summary>[CVPR 2024] Zhongwei Zhang, Fuchen Long, Yingwei Pan, et al.</summary>Zhaofan Qiu, Ting Yao, Yang Cao, Tao Mei</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_TRIP_Temporal_Residual_Learning_with_Image_Noise_Prior_for_Image-to-Video_CVPR_2024_paper.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://trip-i2v.github.io/TRIP/)
+ **Follow-Your-Click: Open-domain Regional Image Animation via Short Prompts** (13 Mar 2024)<details><summary>Yue Ma, Yingqing He, Hongfa Wang, et al.</summary>Andong Wang, Chenyang Qi, Chengfei Cai, Xiu Li, Zhifeng Li, Heung-Yeung Shum, Wei Liu, Qifeng Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.08268)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-click.github.io/)
[![Code](https://img.shields.io/github/stars/mayuelala/FollowYourClick.svg?style=social&label=Star)](https://github.com/mayuelala/FollowYourClick)

+ **AtomoVideo: High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Litong Gong, Yiran Zhu, Weijie Li, et al.</summary>Xiaoyang Kang, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.01800)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://atomo-video.github.io/)


+ **Tuning-Free Noise Rectification for High Fidelity Image-to-Video Generation** (5 Mar 2024)<details><summary>Weijie Li, Litong Gong, Yiran Zhu, et al.</summary>Fanda Fan, Biao Wang, Tiezheng Ge, Bo Zheng</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.02827)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://noise-rectification.github.io/)
[![Code](https://img.shields.io/github/stars/alimama-creative/Noise-Rectification.svg?style=social&label=Star)](https://github.com/alimama-creative/Noise-Rectification)

+ **Motion-i2v: Consistent and controllable image-to-video generation with explicit motion modeling** (31 Jan 2024)<details><summary>[ACM SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3641519.3657497)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)


+ **UniVG: Towards UNIfied-modal Video Generation** (17 Jan 2024)<details><summary>Ludan Ruan, Lei Tian, Chuanwei Huang, et al.</summary>Xu Zhang, Xinyan Xiao</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.09084)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://univg-baidu.github.io/)


+ **Decouple Content and Motion for Conditional Image-to-Video Generation** (14 Dec 2023)<details><summary>[AAAI 2024] Cuifeng Shen, Yulu Gan, Chen Chen, et al.</summary>Xiongwei Zhu, Lele Cheng, Tingting Gao, Jinzhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.14294)


+ **AnimateAnything: Fine-Grained Open Domain Image Animation with Motion Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(4 Dec 2023)<details><summary>[TMLR 2024] Zuozhuo Dai, Zhenghao Zhang, Yao Yao, et al.</summary>Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.12886)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://animationai.github.io/AnimateAnything/)
[![Code](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)



+ **Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets** (25 Nov 2023)<details><summary>Andreas Blattmann, Tim Dockhorn, Sumith Kulal, et al.</summary>Daniel Mendelevitch, Maciej Kilian, Dominik Lorenz, Yam Levi, Zion English, Vikram Voleti, Adam Letts, Varun Jampani, Robin Rombach</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.15127)
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)

+ **I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Nov 2023)<details><summary>Shiwei Zhang, Jiayu Wang, Yingya Zhang, et al.</summary>Kang Zhao, Hangjie Yuan, Zhiwu Qin, Xiang Wang, Deli Zhao, Jingren Zhou</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.04145)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://i2vgen-xl.github.io/)
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Star)](https://github.com/ali-vilab/VGen)







+ **VideoCrafter1: Open Diffusion Models for High-Quality Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(30 Oct 2023)<details><summary>Haoxin Chen, Menghan Xia, Yingqing He, et al.</summary>Yong Zhang, Xiaodong Cun, Shaoshu Yang, Jinbo Xing, Yaofang Liu, Qifeng Chen, Xintao Wang, Chao Weng, Ying Shan</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.19512)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ailab-cvc.github.io/videocrafter2/)
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Star)](https://github.com/AILab-CVC/VideoCrafter)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/VideoCrafter/VideoCrafter)



+ **Synthesizing Videos from Images for Image-to-Video Adaptation** (27 Oct 2023)<details><summary>[ACM MM 2023] Junbao Zhuo, Xingyu Zhao, Shuhui Wang, et al.</summary>Huimin Ma, Qingming Huang</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3581783.3611897)
[![Code](https://img.shields.io/github/stars/junbaoZHUO/ST-I2V.svg?style=social&label=Star)](https://github.com/junbaoZHUO/ST-I2V)


+ **VideoDoodles: Hand-Drawn Animations on Videos with Scene-Aware Canvases**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Jul 2023)<details><summary>[ACM Transactions on Graphics] Emilie Yu, Kevin Blackburn-Matzen, Cuong Nguyen, et al.</summary>Oliver Wang, Rubaiat Habib Kazi, Adrien Bousseau</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3592413)

+ **LaMD: Latent Motion Diffusion for Video Generation** (23 Apr 2023)<details><summary>Yaosi Hu, Zhenzhong Chen, Chong Luo</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.11603)




+ **Prompt Image to Life: Training-Free Text-Driven Image-to-Video Generation** (2023)<details><summary>Jinxiu Liu, Yuan Yao, Bingwen Zhu, et al.</summary>Fanyi Wang, Weijian Luo, Jingwen Su,
Yanhao Zhang, Yuxiao Wang, Liyuan Ma, Qi Liu, Jiebo Luo, Guo-Jun Qi</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.cs.rochester.edu/u/yyao39/files/PiLife.pdf)




+ **Make It Move: Controllable Image-to-Video Generation With Text Descriptions** (31 Mar 2022)<details><summary>[CVPR 2022] Yaosi Hu, Chong Luo, Zhenzhong Chen</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2022/html/Hu_Make_It_Move_Controllable_Image-to-Video_Generation_With_Text_Descriptions_CVPR_2022_paper.html)
[![Code](https://img.shields.io/github/stars/Youncy-Hu/MAGE.svg?style=social&label=Star)](https://github.com/Youncy-Hu/MAGE)

+ **VideoGPT: Video Generation using VQ-VAE and Transformers** (14 Sep 2021)<details><summary>Wilson Yan, Yunzhi Zhang, Pieter Abbeel, et al.</summary>Wilson Yan, Yunzhi Zhang, Pieter Abbeel, Aravind Srinivas</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_WACV_2020/html/WANG_ImaGINator_Conditional_Spatio-Temporal_GAN_for_Video_Generation_WACV_2020_paper.html)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wilsonyan.com/videogpt/index.html)
[![Code](https://img.shields.io/github/stars/wilson1yan/VideoGPT.svg?style=social&label=Star)](https://github.com/wilson1yan/VideoGPT)


+ **ImaGINator: Conditional Spatio-Temporal GAN for Video Generation** (2020)<details><summary>[WACV 2020] Yaohui Wang, Piotr Bilinski, Francois Bremond, et al.</summary>Yaohui Wang, Piotr Bilinski, Francois Bremond, Antitza Dantcheva</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_WACV_2020/html/WANG_ImaGINator_Conditional_Spatio-Temporal_GAN_for_Video_Generation_WACV_2020_paper.html)
[![Code](https://img.shields.io/github/stars/wyhsirius/ImaGINator.svg?style=social&label=Star)](https://github.com/wyhsirius/ImaGINator)




## ⏳ Temporal Control

### 🌊 Flow-Guided
<a id="-flow-guided"></a>

<!-- RECENT_VERIFIED_START:Flow-Guided -->

+ **FlowMotion: Training-Free Flow Guidance for Video Motion Transfer** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Mar 2026)
  <details><summary>Zhen Wang, Youcan Xu, Jun Xiao, et al.</summary>Zhen Wang, Youcan Xu, Jun Xiao, Long Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.06289) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/HKUST-LongGroup/FlowMotion)

+ **PanFlow: Decoupled Motion Control for Panoramic Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Nov 2025)
  <details><summary>Cheng Zhang, Hanwen Liang, Donny Y. Chen, et al.</summary>Cheng Zhang, Hanwen Liang, Donny Y. Chen, Qianyi Wu, Konstantinos N. Plataniotis, Camilo Cruz Gambardella, Jianfei Cai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.00832) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/chengzhag/PanFlow)

<!-- RECENT_VERIFIED_END:Flow-Guided -->

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 May 2024)  
   <details><summary>[ECCV 2024] Muyao Niu, Xiaodong Cun, et al.</summary>  
        Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)  [![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://myniuuu.github.io/MOFA_Video/)

+ **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (29 Jan 2024)  
   <details><summary>[SIGGRAPH 2024] Xiaoyu Shi, Zhaoyang Huang, et al.</summary>  
        Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)  [![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xiaoyushi97.github.io/Motion-I2V/)

+ **Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023)  
   <details><summary>Tsai-Shien Chen, Chieh Hubert Lin, et al.</summary>  
        Tsai-Shien Chen, Chieh Hubert Lin, Hung-Yu Tseng, Tsung-Yi Lin, Ming-Hsuan Yang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tsaishien-chen.github.io/MCDiff/)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(26 Nov 2024)  
   <details><summary>Wanquan Feng, Tianhao Qi, et al.</summary>  
        Wanquan Feng, Tianhao Qi, Jiawei Liu, Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)


### 🛤️ Trajectory-Guided
<a id="-trajectory-guided"></a>

<!-- RECENT_VERIFIED_START:Trajectory-Guided -->

+ **3D Scene-Adaptive Trajectory-Controllable Human Image Animation with Camera Movement** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Jun 2026)
  <details><summary>Deyin Liu, Jicheng Xu, Lin Yuanbo Wu, et al.</summary>Deyin Liu, Jicheng Xu, Lin Yuanbo Wu, Xiaowei Zhao, Xiatian Zhu, Zhe Jin, Anjan Dutta</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.30514) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://robinhood256100.github.io/web-disp)

+ **OrthoMotion:Disentangling Camera and Subject Motion via Geometry Semantics Orthogonal Attention** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Jun 2026)
  <details><summary>Zijie Meng</summary>Zijie Meng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.22835)

+ **CausalMotion: Structured Physical Reasoning as Keyframe and Trajectory Guidance for Training-Free Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Jun 2026)
  <details><summary>Sihan Zhuang, Xinyuan Chen, Tianfan Xue, et al.</summary>Sihan Zhuang, Xinyuan Chen, Tianfan Xue, Yaohui Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.14317) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhuangsh0713.github.io/CausalMotion/)

+ **WorldCraft: From Camera Navigation to Object Manipulation in Interactive Video World Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 May 2026)
  <details><summary>Bohai Gu, Taiyi Wu, Yueyang Yuan, et al.</summary>Bohai Gu, Taiyi Wu, Yueyang Yuan, Jian Liu, Xiaocheng Lu, Dazhao Du, Jie Zhang, Jinxiang Lai, Shuai Yang, Xiaotong Zhao, Alan Zhao, Song Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.25077) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://nevsnev.github.io/WorldCraft/)

+ **MotiMotion: Motion-Controlled Video Generation with Visual Reasoning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 May 2026)
  <details><summary>Lee Hsin-Ying, Hanwen Jiang, Yiqun Mei, et al.</summary>Lee Hsin-Ying, Hanwen Jiang, Yiqun Mei, Jing Shi, Ming-Hsuan Yang, Zhixin Shu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.22818) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motimotion.github.io/)

+ **Tora3: Trajectory-Guided Audio-Video Generation with Physical Coherence** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Apr 2026)
  <details><summary>Junchao Liao, Zhenghao Zhang, Xiangyu Meng, et al.</summary>Junchao Liao, Zhenghao Zhang, Xiangyu Meng, Litao Li, Ziying Zhang, Siyu Zhu, Long Qin, Weizhi Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.09057)

+ **SAW: Toward a Surgical Action World Model via Controllable and Scalable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Mar 2026)
  <details><summary>Sampath Rapuri, Lalithkumar Seenivasan, Dominik Schneider, et al.</summary>Sampath Rapuri, Lalithkumar Seenivasan, Dominik Schneider, Roger Soberanis-Mukul, Yufan He, Hao Ding, Jiru Xu, Chenhao Yu, Chenyan Jing, Pengfei Guo, Daguang Xu, Mathias Unberath</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.13024)

+ **FlashMotion: Few-Step Controllable Video Generation with Trajectory Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Mar 2026)
  <details><summary>Quanhao Li, Zhen Xing, Rui Wang, et al.</summary>Quanhao Li, Zhen Xing, Rui Wang, Haidong Cao, Qi Dai, Daoguo Dong, Zuxuan Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.12146) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://quanhaol.github.io/flashmotion-site/)

+ **DreamLoop: Controllable Cinemagraph Generation from a Single Photograph** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Jan 2026)
  <details><summary>Aniruddha Mahapatra, Long Mai, Cusuh Ham, et al.</summary>Aniruddha Mahapatra, Long Mai, Cusuh Ham, Feng Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.02646) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://anime26398.github.io/dreamloop.github.io/)

+ **DRAW2ACT: Turning Depth-Encoded Trajectories into Robotic Demonstration Videos** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Dec 2025)
  <details><summary>Yang Bai, Liudi Yang, George Eskandar, et al.</summary>Yang Bai, Liudi Yang, George Eskandar, Fengyi Shen, Mohammad Altillawi, Ziyuan Liu, Gitta Kutyniok</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.14217)

+ **VHOI: Controllable Video Generation of Human-Object Interactions from Sparse Trajectories via Motion Densification** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Dec 2025)
  <details><summary>Wanyue Zhang, Lin Geng Foo, Thabo Beeler, et al.</summary>Wanyue Zhang, Lin Geng Foo, Thabo Beeler, Rishabh Dabral, Christian Theobalt</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.09646) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vcai.mpi-inf.mpg.de/projects/vhoi/)

+ **Wan-Move: Motion-controllable Video Generation via Latent Trajectory Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Dec 2025)
  <details><summary>Ruihang Chu, Yefei He, Zhekai Chen, et al.</summary>Ruihang Chu, Yefei He, Zhekai Chen, Shiwei Zhang, Xiaogang Xu, Bin Xia, Dingdong Wang, Hongwei Yi, Xihui Liu, Hengshuang Zhao, Yu Liu, Yingya Zhang, Yujiu Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.08765) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/ali-vilab/Wan-Move)

+ **LAMP: Language-Assisted Motion Planning for Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2025)
  <details><summary>Muhammed Burak Kizil, Enes Sanli, Niloy J. Mitra, et al.</summary>Muhammed Burak Kizil, Enes Sanli, Niloy J. Mitra, Erkut Erdem, Aykut Erdem, Duygu Ceylan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.03619) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cyberiada.github.io/LAMP/)

+ **MotionStream: Real-Time Video Generation with Interactive Motion Controls** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Nov 2025)
  <details><summary>Joonghyuk Shin, Zhengqi Li, Richard Zhang, et al.</summary>Joonghyuk Shin, Zhengqi Li, Richard Zhang, Jun-Yan Zhu, Jaesik Park, Eli Shechtman, Xun Huang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.01266)

+ **TGT: Text-Grounded Trajectories for Locally Controlled Video Generation** (16 Oct 2025)
  <details><summary>Guofeng Zhang, Angtian Wang, Jacob Zhiyuan Fang, et al.</summary>Guofeng Zhang, Angtian Wang, Jacob Zhiyuan Fang, Liming Jiang, Haotian Yang, Bo Liu, Yiding Yang, Guang Chen, Longyin Wen, Alan Yuille, Chongyang Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.15104) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://textgroundedtraj.github.io)

+ **FlexTraj: Image-to-Video Generation with Flexible Point Trajectory Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Oct 2025)
  <details><summary>Zhiyuan Zhang, Can Wang, Dongdong Chen, et al.</summary>Zhiyuan Zhang, Can Wang, Dongdong Chen, Jing Liao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08527) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://bestzzhang.github.io/FlexTraj)

+ **Real-Time Motion-Controllable Autoregressive Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Oct 2025)
  <details><summary>Kesen Zhao, Jiaxin Shi, Beier Zhu, et al.</summary>Kesen Zhao, Jiaxin Shi, Beier Zhu, Junbao Zhou, Xiaolong Shen, Yuan Zhou, Qianru Sun, Hanwang Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08131) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kesenzhao.github.io/AR-Drag.github.io/)

+ **Streaming Drag-Oriented Interactive Video Manipulation: Drag Anything, Anytime!** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Oct 2025)
  <details><summary>Junbao Zhou, Yuan Zhou, Kesen Zhao, et al.</summary>Junbao Zhou, Yuan Zhou, Kesen Zhao, Qingshan Xu, Beier Zhu, Richang Hong, Hanwang Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.03550) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://junbao-zhou.github.io/DragStream.github.io/)

+ **From Seeing to Predicting: A Vision-Language Framework for Trajectory Forecasting and Controlled Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Oct 2025)
  <details><summary>Fan Yang, Zhiyang Chen, Yousong Zhu, et al.</summary>Fan Yang, Zhiyang Chen, Yousong Zhu, Xin Li, Jinqiao Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.00806)

+ **FreeAction: Training-Free Techniques for Enhanced Fidelity of Trajectory-to-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Sep 2025)
  <details><summary>Seungwook Kim, Seunghyeon Lee, Minsu Cho</summary>Seungwook Kim, Seunghyeon Lee, Minsu Cho</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.24241)

+ **DiTraj: training-free trajectory control for video diffusion transformer** (26 Sep 2025)
  <details><summary>Cheng Lei, Jiayu Zhang, Yue Ma, et al.</summary>Cheng Lei, Jiayu Zhang, Yue Ma, Xinyu Wang, Long Chen, Liang Tang, Yiqiang Yan, Fei Su, Zhicheng Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.21839) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xduzhangjiayu.github.io/DiTraj_Project_Page/)

+ **Zo3T: Zero-Shot 3D-Aware Trajectory-Guided Image-to-Video Generation via Test-Time Training** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Sep 2025)
  <details><summary>Ruicheng Zhang, Jun Zhou, Zunnan Xu, et al.</summary>Ruicheng Zhang, Jun Zhou, Zunnan Xu, Zihao Liu, Jiehui Huang, Mingyang Zhang, Yu Sun, Xiu Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.06723)

+ **Physics-Grounded Motion Forecasting via Equation Discovery for Trajectory-Guided Image-to-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Jul 2025)
  <details><summary>Tao Feng, Xianbing Zhao, Zhenhua Chen, et al.</summary>Tao Feng, Xianbing Zhao, Zhenhua Chen, Tien Tsin Wong, Hamid Rezatofighi, Gholamreza Haffari, Lizhen Qu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.06830)

<!-- RECENT_VERIFIED_END:Trajectory-Guided -->

- **ATI: Any Trajectory Instruction for Controllable Video Generation** (10 Jun 2025)  
  <details><summary>Angtian Wang, Haibin Huang, Jacob Zhiyuan Fang, et al.</summary>Angtian Wang, Haibin Huang, Jacob Zhiyuan Fang, Yiding Yang, Chongyang Ma</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.22944)    [![Code](https://img.shields.io/github/stars/bytedance/ATI.svg?style=social&label=Star)](https://github.com/bytedance/ATI)    [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://anytraj.github.io/)

- **MOVi: Training-free Text-conditioned Multi-Object Video Generation** (29 May 2025)  
  <details><summary>Aimon Rahman, Jiang Liu, Ze Wang, et al.</summary>Aimon Rahman, Jiang Liu, Ze Wang, Ximeng Sun, Jialian Wu, Xiaodong Yu, Yusheng Su, Vishal M. Patel, Zicheng Liu, Emad Barsoum</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.22980)

- **Frame In-N-Out: Unbounded Controllable Image-to-Video Generation** (27 May 2025)
  <details><summary>Boyang Wang, Xuweiyi Chen, Matheus Gadelha, et al.</summary> Boyang Wang, Xuweiyi Chen, Matheus Gadelha, Zezhou Cheng</details>  

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.21491)   [![Code](https://img.shields.io/github/stars/UVA-Computer-Vision-Lab/FrameINO.svg?style=social&label=Star)](https://github.com/UVA-Computer-Vision-Lab/FrameINO) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://uva-computer-vision-lab.github.io/Frame-In-N-Out/)

- **AnimateAnywhere: Rouse the Background in Human Image Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(28 Apr 2025)  
  <details><summary>Xiaoyu Liu, Mingshuai Yao, Yabo Zhang, et al.</summary>Xiaoyu Liu, Mingshuai Yao, Yabo Zhang, Xianhui Lin, Peiran Ren, Xiaoming Li, Ming Liu, Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.19834)

- **Uni3C: Unifying Precisely 3D-Enhanced Camera and Human Motion Controls for Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2025)  
  <details><summary>Chenjie Cao, Jingkai Zhou, Shikai Li, et al.</summary>Chenjie Cao, Jingkai Zhou, Shikai Li, Jingyun Liang, Chaohui Yu, Fan Wang, Xiangyang Xue, Yanwei Fu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.14899)

 

- **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025)  
  <details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531)    [![Code](https://img.shields.io/github/stars/tandaily/Awesome-Relighting.svg?style=social&label=Star)](https://github.com/tandaily/Awesome-Relighting)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VidCRAFT3/)

- **LeviTor: 3D Trajectory Oriented Image-to-Video Synthesis** (28 Mar 2025)  
  <details><summary>Hanlin Wang, Hao Ouyang, Qiuyu Wang, et al.</summary>Wen Wang, Ka Leong Cheng, Qifeng Chen, Yujun Shen, Limin Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.15214)    [![Code](https://img.shields.io/github/stars/ant-research/LeviTor.svg?style=social&label=Star)](https://github.com/ant-research/LeviTor)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ppetrichor.github.io/levitor.github.io/)

- **MagicMotion: Controllable Video Generation with Dense-to-Sparse Trajectory Guidance** (20 Mar 2025)  
  <details><summary>Quanhao Li, Zhen Xing, Rui Wang, et al.</summary>Quanhao Li, Zhen Xing, Rui Wang, Hui Zhang, Qi Dai, Zuxuan Wu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.16421v1)    [![Code](https://img.shields.io/github/stars/quanhaol/MagicMotion.svg?style=social&label=Star)](https://github.com/quanhaol/MagicMotion)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.radneurons.com/magicmotion/)

- **Tora: Trajectory-oriented Diffusion Transformer for Video Generation** (14 Mar 2025)  
  <details><summary>Zhenghao Zhang, Junchao Liao, Menghao Li, et al.</summary>Zhenghao Zhang, Junchao Liao, Menghao Li, ZuoZhuo Dai, Bingxue Qiu, Siyu Zhu, Long Qin, Weizhi Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.21705)    [![Code](https://img.shields.io/github/stars/alibaba/Tora.svg?style=social&label=Star)](https://github.com/alibaba/Tora)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-videoai.github.io/tora_video/)

- **LayerAnimate: Layer-level Control for Animation** (22 Mar 2025)  
  <details><summary>Yuxue Yang, Lue Fan, Zuzeng Lin, et al.</summary>Feng Wang, Zhaoxiang Zhang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.08295)    [![Code](https://img.shields.io/github/stars/IamCreateAI/LayerAnimate.svg?style=social&label=Star)](https://github.com/IamCreateAI/LayerAnimate)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://layeranimate.github.io/)

- **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** (22 Mar 2025)  
  <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.12781)    [![Code](https://img.shields.io/github/stars/snap-research/vd3d.svg?style=social&label=Star)](https://github.com/snap-research/vd3d/blob/main/index.html)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/vd3d/)

- **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Mar 2025)  
  <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05020)    [![Code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/)

- **C-Drag: Chain-of-Thought Driven Motion Controller for Video Generation** (27 Feb 2025)  
  <details><summary>Yuhao Li, Mirana Claire Angel, Salman Khan, et al.</summary>Yu Zhu, Jinqiu Sun, Yanning Zhang, Fahad Shahbaz Khan</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.19868)    [![Code](https://img.shields.io/github/stars/WesLee88524/C-Drag-Official-Repo.svg?style=social&label=Star)](https://github.com/WesLee88524/C-Drag-Official-Repo)

- **SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Feb 2025)  
  <details><summary>Koichi Namekata, Sherwin Bahmani, Ziyi Wu, et al.</summary>Yash Kant, Igor Gilitschenski, David B. Lindell</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2411.04989)    [![Code](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social&label=Star)](https://github.com/Kmcode1/SG-I2V)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kmcode1.github.io/Projects/SG-I2V/)

- **MotionCanvas: Cinematic Shot Design with Controllable Image-to-Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Feb 2025)  
  <details><summary>Jinbo Xing, Long Mai, Cusuh Ham, et al.</summary>Jinbo Xing, Long Mai, Cusuh Ham, Jiahui Huang, Aniruddha Mahapatra, Chi-Wing Fu, Tien-Tsin Wong, Feng Liu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2502.04299v1)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-canvas25.github.io/)

- **MotionBridge: Dynamic Video Inbetweening with Flexible Controls** (7 Jan 2025)  
  <details><summary>Maham Tanveer, Yang Zhou, Simon Niklaus, et al.</summary>Ali Mahdavi Amiri, Hao Zhang, Krishna Kumar Singh, Nanxuan Zhao</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.13190v1)    [![Code](https://img.shields.io/github/stars/lwq20020127/OmniDrag.svg?style=social&label=Star)](https://github.com/lwq20020127/OmniDrag)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motionbridge.github.io/)

- **TrackGo: A Flexible and Efficient Method for Controllable Video Generation** (5 Jan 2025)  
  <details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.11475)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhtjtcz.github.io/TrackGo-Page/)

- **Motion-Zero: A Zero-Shot Trajectory Control Framework of Moving Object** (8 Jan 2025)  
  <details><summary>Changgu Chen, Junwei Shu, Gaoqi He, et al.</summary>Changgu Chen, Junwei Shu, Gaoqi He, Changbo Wang, Yang Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2401.10150v4)    [![Code](https://img.shields.io/github/stars/vpx-ecnu/MotionZero-website.svg?style=social&label=Star)](https://github.com/vpx-ecnu/MotionZero-website/blob/main/index.html)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://litaoguo.github.io/MotionZero.github.io/)

- **OmniDrag: Enabling Motion Control for Omnidirectional Image-to-Video Generation** (12 Dec 2024)  
  <details><summary>Weiqi Li, Shijie Zhao, Chong Mou, et al.</summary>Xuhan Sheng, Zhenyu Zhang, Qian Wang, Junlin Li, Li Zhang, Jian Zhang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.09623)    [![Code](https://img.shields.io/github/stars/lwq20020127/OmniDrag.svg?style=social&label=Star)](https://github.com/lwq20020127/OmniDrag)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lwq20020127.github.io/OmniDrag/)

- **ObjCtrl-2.5D: Training-free Object Control with Camera Poses** (10 Dec 2024)  
  <details><summary>Zhouxia Wang, Yushi Lan, Shangchen Zhou, Chen Change Loy, et al.</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07721)    [![Code](https://img.shields.io/github/stars/wzhouxiff/ObjCtrl-2.5D.svg?style=social&label=Star)](https://github.com/wzhouxiff/ObjCtrl-2.5D)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wzhouxiff.github.io/projects/ObjCtrl-2.5D/)

- **Motion Prompting: Controlling Video Generation with Motion Trajectories** (3 Dec 2024)  
  <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2412.02700v1)    [![Code](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)

- **I2VControl: Disentangled and Unified Video Motion Synthesis Control**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Nov 2024)  
  <details><summary>Wanquan Feng, Tianhao Qi, Jiawei Liu, et al.</summary>Mingzhen Sun, Pengqi Tu, Tianxiang Ma, Fei Dai, Songtao Zhao, Siyu Zhou, Qian He</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)

- **InTraGen: Trajectory-controlled Video Generation for Object Interactions** (25 Nov 2024)  
  <details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.16804)   [![Code](https://img.shields.io/github/stars/insait-institute/InTraGen.svg?style=social&label=Star)](https://github.com/insait-institute/InTraGen)

- **MotionBooth: Motion-Aware Customized Text-to-Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Oct 2024)  
  <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)    [![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianzongwu.github.io/projects/motionbooth/?ref=aiartweekly)

- **DragEntity: Trajectory Guided Video Generation using Entity and Positional Relationships** (14 Oct 2024)  
  <details><summary>Zhang Wan, Sheng Tang, Jiawei Wei</summary></details>  
  
  [![Paper](https://img.shields.io/badge/ACM-b31b1b.svg)](https://arxiv.org/abs/2410.10751)    [![Code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md)


- **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(11 Jul 2024)  
  <details><summary>Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>Yong Zhang, Ying Shan, Yinqiang Zheng</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)    [![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://myniuuu.github.io/MOFA_Video/)

- **Freetraj: Tuning-free Trajectory Control in Video Diffusion Models (T2V)** (24 Jun 2024)  
  <details><summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, et al.</summary>Haonan Qiu, Zhaoxi Chen, Zhouxia Wang, Yingqing He, Menghan Xia, Ziwei Liu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16863)    [![Code](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Star)](http://github.com/arthur-qiu/FreeTraj)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://freetraj.github.io)

- **Image Conductor: Precision Control for Interactive Video Synthesis** (21 Jun 2024)  
  <details><summary>Yaowei Li, Xintao Wang, Zhaoyang Zhang, et al.</summary>Zhouxia Wang, Ziyang Yuan, Liangbin Xie, Yuexian Zou, Ying Shan</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.15339)    [![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Star)](https://github.com/liyaowei-stu/ImageConductor)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://liyaowei-stu.github.io/project/ImageConductor/)

- **ReVideo: Remake a Video with Motion and Content** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(22 May 2024)  
  <details><summary>Zuhao Liu, Aleksandar Yanev, Ahmad Mahmood, et al.</summary>Ivan Nikolov, Saman Motamed, Wei-Shi Zheng, Xi Wang, Luc Van Gool, Danda Pani Paudel</details>  
  
  [![Paper](https://img.shields.io/badge/NeurIPS-b31b1b.svg)](https://proceedings.neurips.cc)    [![Code](https://img.shields.io/github/stars/MC-E/ReVideo.svg?style=social&label=Star)](https://github.com/MC-E/ReVideo)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mc-e.github.io/project/ReVideo/)

- **Collaborative Video Diffusion: Consistent Multi-video Generation with Camera Control** (27 May 2024)  
  <details><summary>Zhengfei Kuang, Shengqu Cai, Hao He, et al.</summary>Zhengfei Kuang, Shengqu Cai, Hao He, Yinghao Xu, Hongsheng Li, Leonidas Guibas, Gordon Wetzstein</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.17414)    [![Code](https://img.shields.io/github/stars/CollaborativeVideoDiffusion/collaborativevideodiffusion.github.io.svg?style=social&label=Star)](https://github.com/CollaborativeVideoDiffusion/collaborativevideodiffusion.github.io/blob/main/index.html)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://collaborativevideodiffusion.github.io/)

- **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)(6 May 2024)  
  <details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, et al.</summary>Shiyuan Yang, Liang Hou, Haibin Huang, Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)    [![Code](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://direct-a-video.github.io/?ref=aiartweekly)

- **Peekaboo: Interactive Video Generation via Masked-Diffusion (T2V)** (19 Apr 2024)  
  <details><summary>Yash Jain, Anshul Nasery, Vibhav Vineet, et al.</summary>Yash Jain, Anshul Nasery, Vibhav Vineet, Harkirat Behl</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2312.07509)    [![Code](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Star)](https://github.com/microsoft/Peekaboo)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yash-jain.com/projects/Peekaboo/)

- **Video Diffusion Models are Training-free Motion Interpreter and Controller** (19 Apr 2024)  
  <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan, et al.</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://arxiv.org/abs/2312.07509)    [![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

- **TrailBlazer: Trajectory Control for Diffusion-Based Video Generation (T2V)** (8 Apr 2024)  
  <details><summary>Wan-Duo Kurt Ma, J.P. Lewis, W. Bastiaan Kleijn, et al.</summary>Wan-Duo Kurt Ma, J.P. Lewis, W. Bastiaan Kleijn</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.00896)    [![Code](https://img.shields.io/github/stars/hohonu-vicml/TrailBlazer.svg?style=social&label=Star)](https://github.com/hohonu-vicml/TrailBlazer)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hohonu-vicml.github.io/Trailblazer.Page/)

- **Draganything: Motion Control for Anything Using Entity Representation** (15 Mar 2024)  
  <details><summary>Weijia Wu, Zhuang Li, Yuchao Gu, et al.</summary>Rui Zhao, Yefei He, David Junhao Zhang, Mike Zheng Shou, Yan Li, Tingting Gao, Di Zhang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.07420)    [![Code](https://img.shields.io/github/stars/showlab/DragAnything.svg?style=social&label=Star)](https://github.com/showlab/DragAnything)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://weijiawu.github.io/draganything_page/)

- **Boximator: Generating Rich and Controllable Motions for Video Synthesis**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Feb 2024)  
  <details><summary>Jiawei Wang, Yuchen Zhang, Jiaxin Zou, et al.</summary>Yan Zeng, Guoqiang Wei, Liping Yuan, Hang Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.01566)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://boximator.github.io/)

- **Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling** (31 Jan 2024)  
  <details><summary>Xiaoyu Shi, Zhaoyang Huang, Fu-Yun Wang, et al.</summary>Weikang Bian, Dasong Li, Yi Zhang, Manyuan Zhang, Ka Chun Cheung, Simon See, Hongwei Qin, Jifeng Dai, Hongsheng Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2401.15977)    [![Code](https://img.shields.io/github/stars/G-U-N/Motion-I2V.svg?style=social&label=Star)](https://github.com/G-U-N/Motion-I2V)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cpii.hk/inventions/motion-i2v-consistent-and-controllable-image-to-video-generation-with-explicit-motion-modeling/)

- **DragNuwa (Image+Text_Traj)** (16 Aug 2023)  
  <details><summary>Shengming Yin, Chenfei Wu, Jian Liang, et al.</summary>Jie Shi, Houqiang Li, Gong Ming, Nan Duan</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.08089)    [![Code](https://img.shields.io/github/stars/ProjectNUWA/DragNUWA.svg?style=social&label=Star)](https://github.com/ProjectNUWA/DragNUWA)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aiartweekly.com/tools/dragnuwa-fine-grained-control-in-video-generation-by-integrating-text-image-and-trajectory)

- **MCDiff Motion-Conditioned Diffusion Model for Controllable Video Synthesis** (27 Apr 2023)  
  <details><summary>Haitao Zhou, Chuang Wang, Rui Nie, et al.</summary>Jinlin Liu, Dongdong Yu, Qian Yu, Changhu Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.14404)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tsaishien-chen.github.io/MCDiff/)

- **Controllable Video Generation With Sparse Trajectories** (16 Dec 2018)  
  <details><summary>Zekun Hao, Xun Huang, Serge Belongie, et al.</summary>Zekun Hao, Xun Huang, Serge Belongie</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_cvpr_2018/html/Hao_Controllable_Video_Generation_CVPR_2018_paper.html)   [![Code](https://img.shields.io/github/stars/zekunhao1995/ControllableVideoGen.svg?style=social&label=Star)](https://github.com/zekunhao1995/ControllableVideoGen)   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)






### 📸 Camera-Guided
<a id="-camera-guided"></a>

<!-- RECENT_VERIFIED_START:Camera-Guided -->

+ **TriMotion: Modality-Agnostic Camera Control for Video Generation** (18 Jun 2026)
  <details><summary>Seunghyun Shin, Jifei Song, Wooseok Jeon, et al.</summary>Seunghyun Shin, Jifei Song, Wooseok Jeon, Hae-Gon Jeon, Jiankang Deng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.20774) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://seunghyuns98.github.io/TriMotion/)

+ **SierpinskiCam: Camera-Controlled Video Retaking with Sierpinski Triangle Pattern Cues** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Jun 2026)
  <details><summary>Suttisak Wizadwongsa, Hyelin Nam, Supasorn Suwajanakorn, et al.</summary>Suttisak Wizadwongsa, Hyelin Nam, Supasorn Suwajanakorn, Jeong Joon Park</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.17310) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyelinnam.github.io/SierpinskiCam/)

+ **PermaVid: Consistent Video Generation Across Edits via Disentangled Context Memory** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Jun 2026)
  <details><summary>Shuai Yang, Bingjie Gao, Ziwei Liu, et al.</summary>Shuai Yang, Bingjie Gao, Ziwei Liu, Jiaqi Wang, Dahua Lin, Tong Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.16449) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ys-imtech.github.io/projects/PermaVid/)

+ **Track2View: 4D-Consistent Camera-Controlled Video Generation via Paired 3D Point Tracks** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Jun 2026)
  <details><summary>Feng Qiao, Zhaochong An, Zhexiao Xiong, et al.</summary>Feng Qiao, Zhaochong An, Zhexiao Xiong, Serge Belongie, Nathan Jacobs</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.15534) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://qjizhi.github.io/track2view)

+ **GeoStream: Toward Precise Camera Controlled Streaming Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Jun 2026)
  <details><summary>Yizhou Zhao, Yifan Wang, Xiaoyuan Wang, et al.</summary>Yizhou Zhao, Yifan Wang, Xiaoyuan Wang, Yushu Wu, Hao Zhang, Moayed Haji-Ali, Rameen Abdal, Ashkan Mirzaei, Yanyu Li, Willi Menapace, Laszlo Jeni, Sergey Tulyakov, Peter Wonka, Chaoyang Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.15162)

+ **Prisma-World: Camera-Controllable Multi-Agent Video World Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jun 2026)
  <details><summary>Huiqiang Sun, Zhan Peng, Size Wu, et al.</summary>Huiqiang Sun, Zhan Peng, Size Wu, Kun Wang, Kang Liao, Dianyi Wang, Xingyu Zeng, Sheng Jin, Yangguang Li, Zhiguo Cao, Ziwei Liu, Wei Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.09507) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://huiqiang-sun.github.io/prisma-world/)

+ **DisCo: World Models with Discrete Camera Motion Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Jun 2026)
  <details><summary>Hongrui Huang, Junke Wang, Quanhao Li, et al.</summary>Hongrui Huang, Junke Wang, Quanhao Li, Yu-Gang Jiang, Zuxuan Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.07967)

+ **Robust Dreamer: Deviation-Aware Latent Gaussian Memory for Action-Controlled AR Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 May 2026)
  <details><summary>Hanlin Chen, Jiaxin Wei, Xibin Song, et al.</summary>Hanlin Chen, Jiaxin Wei, Xibin Song, Yifu Wang, Steve Wang, Hongdong Li, Pan Ji, Gim Hee Lee</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.30855) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hlinchen.github.io/projects/Robust_Dreamer/)

+ **CameraNoise: Enabling Faithful Camera Control in Video Diffusion through Geometry-Flow-Guided Noise Warping** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 May 2026)
  <details><summary>Haoyu Zhao, Jiaxi Gu, Haoran Chen, et al.</summary>Haoyu Zhao, Jiaxi Gu, Haoran Chen, Qingping Zheng, Yeying Jin, Hongyi Yang, Junqi Cheng, Yuang Zhang, Zenghui Lu, Huan Yu, Jie Jiang, Peng Shu, Zuxuan Wu, Yu-Gang Jiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.30774) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gulucaptain.github.io/CameraNoise/)

+ **DeltaCam: Differential Intrinsic Camera Modeling for Video Generation** (24 May 2026)
  <details><summary>Debabrata Mandal, Zhihan Peng, Yujie Wang, et al.</summary>Debabrata Mandal, Zhihan Peng, Yujie Wang, Praneeth Chakravarthula</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.25266)

+ **Aero-World: Action-Conditioned Aerial Video Generation from Inertial Controls** (19 May 2026)
  <details><summary>Abdul Mohaimen Al Radi, Kunyang Li, Yuzhang Shang, et al.</summary>Abdul Mohaimen Al Radi, Kunyang Li, Yuzhang Shang, Mubarak Shah, Yu Tian</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.19728)

+ **Warp-as-History: Generalizable Camera-Controlled Video Generation from One Training Video** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 May 2026)
  <details><summary>Yifan Wang, Tong He</summary>Yifan Wang, Tong He</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.15182) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yyfz.github.io/warp-as-history/)

+ **Probing into Camera Control of Video Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 May 2026)
  <details><summary>Chen Hou, Christian Rupprecht</summary>Chen Hou, Christian Rupprecht</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.14815) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xrchitech.github.io/camprobe-page/)

+ **CRePE: Curved Ray Expectation Positional Encoding for Unified-Camera-Controlled Video Generation** (13 May 2026)
  <details><summary>Seonghyun Jin, Youngmin Kim, Sunwoo Park, et al.</summary>Seonghyun Jin, Youngmin Kim, Sunwoo Park, Jong Chul Ye</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.12938)

+ **$h$-control: Training-Free Camera Control via Block-Conditional Gibbs Refinement** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 May 2026)
  <details><summary>Yuzhu Wang, Xi Ye, Duo Su, et al.</summary>Yuzhu Wang, Xi Ye, Duo Su, Yangyang Xu, Jun Zhu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.11871)

+ **ActCam: Zero-Shot Joint Camera and 3D Motion Control for Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 May 2026)
  <details><summary>Omar El Khalifi, Thomas Rossi, Oscar Fossey, et al.</summary>Omar El Khalifi, Thomas Rossi, Oscar Fossey, Thibault Fouque, Ulysse Mizrahi, Philip Torr, Ivan Laptev, Fabio Pizzati, Baptiste Bellot-Gurlet</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.06667) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://elkhomar.github.io/actcam/)

+ **RealCam: Real-Time Novel-View Video Generation with Interactive Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 May 2026)
  <details><summary>Youcan Xu, Jiaxin Shi, Zhen Wang, et al.</summary>Youcan Xu, Jiaxin Shi, Zhen Wang, Wensong Song, Feifei Shao, Chen Liang, Jun Xiao, Long Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.06051) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xyc-fly.github.io/RealCam/)

+ **Rays as Pixels: Learning A Joint Distribution of Videos and Camera Trajectories** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Apr 2026)
  <details><summary>Wonbong Jang, Shikun Liu, Soubhik Sanyal, et al.</summary>Wonbong Jang, Shikun Liu, Soubhik Sanyal, Juan Camilo Perez, Kam Woh Ng, Sanskar Agrawal, Juan-Manuel Perez-Rua, Yiannis Douratsos, Tao Xiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.09429) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wbjang.github.io/raysaspixels/)

+ **CT-1: Vision-Language-Camera Models Transfer Spatial Reasoning Knowledge to Camera-Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Apr 2026)
  <details><summary>Haoyu Zhao, Zihao Zhang, Jiaxi Gu, et al.</summary>Haoyu Zhao, Zihao Zhang, Jiaxi Gu, Haoran Chen, Qingping Zheng, Pin Tang, Yeyin Jin, Yuang Zhang, Junqi Cheng, Zenghui Lu, Peng Shu, Zuxuan Wu, Yu-Gang Jiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.09201)

+ **OmniCamera: A Unified Framework for Multi-task Video Generation with Arbitrary Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Apr 2026)
  <details><summary>Yukun Wang, Ruihuang Li, Jiale Tao, et al.</summary>Yukun Wang, Ruihuang Li, Jiale Tao, Shiyuan Yang, Liyi Chen, Zhantao Yang, Handz, Yulan Guo, Shuai Shao, Qinglin Lu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.06010)

+ **SymphoMotion: Joint Control of Camera Motion and Object Dynamics for Coherent Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Apr 2026)
  <details><summary>Guiyu Zhang, Yabo Chen, Xunzhi Xiang, et al.</summary>Guiyu Zhang, Yabo Chen, Xunzhi Xiang, Junchao Huang, Zhongyu Wang, Li Jiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.03723) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://grenoble-zhang.github.io/SymphoMotion/)

+ **MemCam: Memory-Augmented Camera Control for Consistent Video Generation** (27 Mar 2026)
  <details><summary>Xinhang Gao, Junlin Guan, Shuhan Luo, et al.</summary>Xinhang Gao, Junlin Guan, Shuhan Luo, Wenzhuo Li, Guanghuan Tan, Jiacheng Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.26193) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/newhorizon2005/MemCam)

+ **I3DM: Implicit 3D-aware Memory Retrieval and Injection for Consistent Video Scene Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Mar 2026)
  <details><summary>Jia Li, Han Yan, Yihang Chen, et al.</summary>Jia Li, Han Yan, Yihang Chen, Siqi Li, Xibin Song, Yifu Wang, Jianfei Cai, Tien-Tsin Wong, Pan Ji</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.23413) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://riga2.github.io/i3dm)

+ **GO-Renderer: Generative Object Rendering with 3D-aware Controllable Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Mar 2026)
  <details><summary>Zekai Gu, Shuoxuan Feng, Yansong Wang, et al.</summary>Zekai Gu, Shuoxuan Feng, Yansong Wang, Hanzhuo Huang, Zhongshuo Du, Chengfeng Zhao, Chengwei Ren, Peng Wang, Yuan Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.23246) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://igl-hkust.github.io/GO-Renderer)

+ **Stereo World Model: Camera-Guided Stereo Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Mar 2026)
  <details><summary>Yang-Tian Sun, Zehuan Huang, Yifan Niu, et al.</summary>Yang-Tian Sun, Zehuan Huang, Yifan Niu, Lin Ma, Yan-Pei Cao, Yuewen Ma, Xiaojuan Qi</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.17375) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sunyangtian.github.io/StereoWorld-web/)

+ **MosaicMem: Hybrid Spatial Memory for Controllable Video World Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Mar 2026)
  <details><summary>Wei Yu, Runjia Qian, Yumeng Li, et al.</summary>Wei Yu, Runjia Qian, Yumeng Li, Liquan Wang, Songheng Yin, Sri Siddarth Chakaravarthy P, Dennis Anthony, Yang Ye, Yidi Li, Weiwei Wan, Animesh Garg</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.17117)

+ **CamLit: Unified Video Diffusion with Explicit Camera and Lighting Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Mar 2026)
  <details><summary>Zhiyi Kuang, Chengan He, Egor Zakharov, et al.</summary>Zhiyi Kuang, Chengan He, Egor Zakharov, Yuxuan Xue, Shunsuke Saito, Olivier Maury, Timur Bagautdinov, Youyi Zheng, Giljoo Nam</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.14241)

+ **ConfCtrl: Enabling Precise Camera Control in Video Diffusion via Confidence-Aware Interpolation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Mar 2026)
  <details><summary>Liudi Yang, George Eskandar, Fengyi Shen, et al.</summary>Liudi Yang, George Eskandar, Fengyi Shen, Mohammad Altillawi, Yang Bai, Chi Zhang, Ziyuan Liu, Abhinav Valada</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.09819)

+ **FaceCam: Portrait Video Camera Control via Scale-Aware Conditioning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Mar 2026)
  <details><summary>Weijie Lyu, Ming-Hsuan Yang, Zhixin Shu</summary>Weijie Lyu, Ming-Hsuan Yang, Zhixin Shu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.05506) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://weijielyu.github.io/FaceCam)

+ **WorldStereo: Bridging Camera-Guided Video Generation and Scene Reconstruction via 3D Geometric Memories** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Mar 2026)
  <details><summary>Yisu Zhang, Chenjie Cao, Tengfei Wang, et al.</summary>Yisu Zhang, Chenjie Cao, Tengfei Wang, Xuhui Zuo, Junta Wu, Jianke Zhu, Chunchao Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.02049) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/FuchengSu/WorldStereo)

+ **UCM: Unified Modeling of Camera Control and Memory with Time-aware Positional Encoding Warping for World Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Feb 2026)
  <details><summary>Tianxing Xu, Zixuan Wang, Guangyuan Wang, et al.</summary>Tianxing Xu, Zixuan Wang, Guangyuan Wang, Li Hu, Zhongyi Zhang, Peng Zhang, Bang Zhang, Songhai Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.22960) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/ucm-webpage)

+ **ReRoPE: Repurposing RoPE for Relative Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Feb 2026)
  <details><summary>Chunyang Li, Yuanbo Yang, Jiahao Shao, et al.</summary>Chunyang Li, Yuanbo Yang, Jiahao Shao, Hongyu Zhou, Katja Schwarz, Yiyi Liao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.08068) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sisyphe-lee.github.io/ReRoPE/)

+ **CamPilot: Improving Camera Control in Video Diffusion Model with Efficient Camera Reward Feedback** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Jan 2026)
  <details><summary>Wenhang Ge, Guibao Shen, Jiawei Feng, et al.</summary>Wenhang Ge, Guibao Shen, Jiawei Feng, Luozhou Wang, Hao Lu, Xingye Tian, Xin Tao, Ying-Cong Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.16214) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://a-bigbao.github.io/CamPilot/)

+ **Beyond Inpainting: Unleash 3D Understanding for Precise Camera-Controlled Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Jan 2026)
  <details><summary>Dong-Yu Chen, Yixin Guo, Shuojin Yang, et al.</summary>Dong-Yu Chen, Yixin Guo, Shuojin Yang, Tai-Jiang Mu, Shi-Min Hu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.10214) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eleanor6725.github.io/DepthDirector)

+ **Efficient Camera-Controlled Video Generation of Static Scenes via Sparse Diffusion and 3D Rendering** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Jan 2026)
  <details><summary>Jieying Chen, Jeffrey Hu, Joan Lasenby, et al.</summary>Jieying Chen, Jeffrey Hu, Joan Lasenby, Ayush Tewari</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.09697)

+ **Pixel-to-4D: Camera-Controlled Image-to-Video Generation with Dynamic 3D Gaussians** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Jan 2026)
  <details><summary>Melonie de Almeida, Daniela Ivanova, Tong Shi, et al.</summary>Melonie de Almeida, Daniela Ivanova, Tong Shi, John H. Williamson, Paul Henderson</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.00678) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://meloniedealmeida.github.io/Pixel-to-4D-Website/)

+ **CETCAM: Camera-Controllable Video Generation via Consistent and Extensible Tokenization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Dec 2025)
  <details><summary>Zelin Zhao, Xinyu Gong, Bangya Liu, et al.</summary>Zelin Zhao, Xinyu Gong, Bangya Liu, Ziyang Song, Jun Zhang, Suhui Wu, Yongxin Chen, Hao Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.19020) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sjtuytc.github.io/CETCam_project_page.github.io/)

+ **Infinite-Homography as Robust Conditioning for Camera-Controlled Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Dec 2025)
  <details><summary>Min-Jung Kim, Jeongho Kim, Hoiyeong Jin, et al.</summary>Min-Jung Kim, Jeongho Kim, Hoiyeong Jin, Junha Hyung, Jaegul Choo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.17040) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://emjay73.github.io/InfCam/)

+ **ShotDirector: Directorially Controllable Multi-Shot Video Generation with Cinematographic Transitions** (11 Dec 2025)
  <details><summary>Xiaoxue Wu, Xinyuan Chen, Yaohui Wang, et al.</summary>Xiaoxue Wu, Xinyuan Chen, Yaohui Wang, Yu Qiao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.10286) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://uknowsth.github.io/ShotDirector/)

+ **GimbalDiffusion: Gravity-Aware Camera Control for Video Generation** (9 Dec 2025)
  <details><summary>Frédéric Fortier-Chouinard, Yannick Hold-Geoffroy, Valentin Deschaintre, et al.</summary>Frédéric Fortier-Chouinard, Yannick Hold-Geoffroy, Valentin Deschaintre, Matheus Gadelha, Jean-François Lalonde</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.09112) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lvsn.github.io/GimbalDiffusion)

+ **Unified Camera Positional Encoding for Controlled Video Generation** (8 Dec 2025)
  <details><summary>Cheng Zhang, Boying Li, Meng Wei, et al.</summary>Cheng Zhang, Boying Li, Meng Wei, Yan-Pei Cao, Camilo Cruz Gambardella, Dinh Phung, Jianfei Cai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.07237) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/chengzhag/UCPE)

+ **Light-X: Generative 4D Video Rendering with Camera and Illumination Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Dec 2025)
  <details><summary>Tianqi Liu, Zhaoxi Chen, Zihao Huang, et al.</summary>Tianqi Liu, Zhaoxi Chen, Zihao Huang, Shaocong Xu, Saining Zhang, Chongjie Ye, Bohan Li, Zhiguo Cao, Wei Li, Hao Zhao, Ziwei Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.05115) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lightx-ai.github.io/)

+ **BulletTime: Decoupled Control of Time and Camera Pose for Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Dec 2025)
  <details><summary>Yiming Wang, Qihang Zhang, Shengqu Cai, et al.</summary>Yiming Wang, Qihang Zhang, Shengqu Cai, Tong Wu, Jan Ackermann, Zhengfei Kuang, Yang Zheng, Frano Rajič, Siyu Tang, Gordon Wetzstein</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.05076) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://19reborn.github.io/Bullet4D/)

+ **ReCamDriving: LiDAR-Free Camera-Controlled Novel Trajectory Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Dec 2025)
  <details><summary>Yaokun Li, Shuaixian Wang, Mantang Guo, et al.</summary>Yaokun Li, Shuaixian Wang, Mantang Guo, Jiehui Huang, Taojun Ding, Mu Hu, Kaixuan Wang, Shaojie Shen, Guang Tan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.03621) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://recamdriving.github.io/)

+ **Taming Camera-Controlled Video Generation with Verifiable Geometry Reward** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Dec 2025)
  <details><summary>Zhaoqing Wang, Xiaobo Xia, Zhuolin Bie, et al.</summary>Zhaoqing Wang, Xiaobo Xia, Zhuolin Bie, Jinlin Liu, Dongdong Yu, Jia-Wang Bian, Changhu Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.02870)

+ **DualCamCtrl: Dual-Branch Diffusion Model for Geometry-Aware Camera-Controlled Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2025)
  <details><summary>Hongfei Zhang, Kanghao Chen, Zixin Zhang, et al.</summary>Hongfei Zhang, Kanghao Chen, Zixin Zhang, Harold Haodong Chen, Yuanhuiyi Lyu, Yuqi Zhang, Shuai Yang, Kun Zhou, Yingcong Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.23127) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://soyouthinkyoucantell.github.io/dualcamctrl-page/)

+ **Less is More: Data-Efficient Adaptation for Controllable Text-to-Video Generation** (21 Nov 2025)
  <details><summary>Shihan Cheng, Nilesh Kulkarni, David Hyde, et al.</summary>Shihan Cheng, Nilesh Kulkarni, David Hyde, Dmitriy Smirnov</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.17844) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/csh-apprentice/Less_Is_More)

+ **PostCam: Camera-Controllable Novel-View Video Generation with Query-Shared Cross-Attention** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Nov 2025)
  <details><summary>Yipeng Chen, Zhichao Ye, Zhenzhou Fang, et al.</summary>Yipeng Chen, Zhichao Ye, Zhenzhou Fang, Xinyu Chen, Xiaoyu Zhang, Jialing Liu, Nan Wang, Guofeng Zhang, Haomin Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.17185) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cccqaq.github.io/PostCam.github.io/)

+ **3D Scene Prompting for Scene-Consistent Camera-Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Oct 2025)
  <details><summary>JoungBin Lee, Jaewoo Jung, Jisang Han, et al.</summary>JoungBin Lee, Jaewoo Jung, Jisang Han, Takuya Narihira, Kazumi Fukuda, Junyoung Seo, Sunghwan Hong, Yuki Mitsufuji, Seungryong Kim</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.14945) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cvlab-kaist.github.io/3DScenePrompt/)

+ **Virtually Being: Customizing Camera-Controllable Video Diffusion Models with Multi-View Performance Captures** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Oct 2025)
  <details><summary>Yuancheng Xu, Wenqi Xian, Li Ma, et al.</summary>Yuancheng Xu, Wenqi Xian, Li Ma, Julien Philip, Ahmet Levent Taşel, Yiwei Zhao, Ryan Burgert, Mingming He, Oliver Hermann, Oliver Pilarski, Rahul Garg, Paul Debevec, Ning Yu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.14179) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eyeline-labs.github.io/Virtually-Being)

+ **MotionFlow:Learning Implicit Motion Flow for Complex Camera Trajectory Control in Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Sep 2025)
  <details><summary>Guojun Lei, Chi Wang, Yikai Wang, et al.</summary>Guojun Lei, Chi Wang, Yikai Wang, Hong Li, Ying Song, Weiwei Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.21119)

+ **CamPVG: Camera-Controlled Panoramic Video Generation with Epipolar-Aware Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Sep 2025)
  <details><summary>Chenhao Ji, Chaohui Yu, Junyao Gao, et al.</summary>Chenhao Ji, Chaohui Yu, Junyao Gao, Fan Wang, Cairong Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.19979)

+ **Dream4D: Lifting Camera-Controlled I2V towards Spatiotemporally Consistent 4D Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Aug 2025)
  <details><summary>Xiaoyan Liu, Kangrui Li, Yuehao Song, et al.</summary>Xiaoyan Liu, Kangrui Li, Yuehao Song, Jiaxin Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.07769)

+ **IDCNet: Guided Video Diffusion for Metric-Consistent RGBD Scene Generation with Precise Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Aug 2025)
  <details><summary>Lijuan Liu, Wenfa Li, Dongbo Zhang, et al.</summary>Lijuan Liu, Wenfa Li, Dongbo Zhang, Shuo Wang, Shaohui Jiao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.04147) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://idcnet-scene.github.io)

+ **QuaDreamer: Controllable Panoramic Video Generation for Quadruped Robots** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Aug 2025)
  <details><summary>Sheng Wu, Fei Teng, Hao Shi, et al.</summary>Sheng Wu, Fei Teng, Hao Shi, Qi Jiang, Kai Luo, Kaiwei Wang, Kailun Yang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.02512) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/losehu/QuaDreamer)

+ **LiON-LoRA: Rethinking LoRA Fusion to Unify Controllable Spatial and Temporal Generation for Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jul 2025)
  <details><summary>Yisu Zhang, Chenjie Cao, Chaohui Yu, et al.</summary>Yisu Zhang, Chenjie Cao, Chaohui Yu, Jianke Zhu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.05678) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fuchengsu.github.io/lionlora.github.io/)

<!-- RECENT_VERIFIED_END:Camera-Guided -->

+ **Follow-Your-Creation: Empowering 4D Creation through Video Inpainting** (5 Jun 2025)  
  <details><summary>Yue Ma, Kunyu Feng, Xinhua Zhang, et al.</summary> Yue Ma, Kunyu Feng, Xinhua Zhang, Hongyu Liu, David Junhao Zhang, Jinbo Xing, Yinhan Zhang, Ayden Yang, Zeyu Wang, Qifeng Chen</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.04590)

+ **Voyager: Long-Range and World-Consistent Video Diffusion for Explorable 3D Scene Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Jun 2025)  
  <details><summary>Tianyu Huang, Wangguandong Zheng, Tengfei Wang, et al.</summary> Tianyu Huang, Wangguandong Zheng, Tengfei Wang, Yuhao Liu, Zhenwei Wang, Junta Wu, Jie Jiang, Hui Li, Rynson W. H. Lau, Wangmeng Zuo, Chunchao Guo</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.04225)    [![Code](https://img.shields.io/github/stars/Voyager-World/Voyager.svg?style=social&label=Star)](https://github.com/Voyager-World/Voyager)   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://voyager-world.github.io/)

+ **AKiRa: Augmentation Kit on Rays for optical video generation** (Jun 2025) <details><summary>[CVPR 2024] Xi Wang, Robin Courant, et al.</summary>Xi Wang, Robin Courant, Marc Christie, Vicky Kalogeiton</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_AKiRa_Augmentation_Kit_on_Rays_for_Optical_Video_Generation_CVPR_2025_paper.pdf) [![Code](https://img.shields.io/github/stars/Triocrossing/AKiRa.svg?style=social&label=Star)](https://github.com/Triocrossing/AKiRa)   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://www.lix.polytechnique.fr/vista/projects/2024_akira_wang/)
  
+ **Uni3C: Unifying Precisely 3D-Enhanced Camera and Human Motion Controls for Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2025)  
  <details><summary>Chenjie Cao, Jingkai Zhou, Shikai Li, et al.</summary> Chenjie Cao, Jingkai Zhou, Shikai Li, Jingyun Liang, Chaohui Yu, Fan Wang, Xiangyang Xue, Yanwei Fu</details>  

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.14899)

+ **GenDoP: Auto-regressive Camera Trajectory Generation as a Director of Photography** (10 Apr 2025)  
  <details><summary>Mengchen Zhang, Tong Wu, Jing Tan, et al.</summary> Mengchen Zhang, Tong Wu, Jing Tan, Ziwei Liu, Gordon Wetzstein, Dahua Lin</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.07083)    [![Code](https://img.shields.io/github/stars/3DTopia/GenDoP.svg?style=social&label=Star)](https://github.com/3DTopia/GenDoP)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kszpxxzmc.github.io/GenDoP/)

+ **OmniCam: Unified Multimodal Video Generation via Camera Control** (3 Apr 2025)  
  <details><summary>Yang, Xiaoda; Xu, Jiayang; Luan, Kaixuan, et al.</summary> Yang, Xiaoda; Xu, Jiayang; Luan, Kaixuan; Zhan, Xinyu; Qiu, Hongshun; Shi, Shijun; Li, Hao; Yang, Shuai; Zhang, Li; Yu, Checheng; Lu, Cewu; Yang, Lixin</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02312)

+ **VidCRAFT3: Camera, Object, and Lighting Control for Image-to-Video Generation** (2 Apr 2025)  
  <details><summary>Sixiao Zheng, Zimian Peng, Yanpeng Zhou, et al.</summary> Yi Zhu, Hang Xu, Xiangru Huang, Yanwei Fu</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.07531)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VidCRAFT3/)

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories** (27 Mar 2025)  
  <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary> Daniel Geng, Charles Herrmann, Junhwa Hur, Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02700)    [![code](https://img.shields.io/github/stars/HyelinNAM/MotionPrompt.svg?style=social&label=Star)](https://github.com/HyelinNAM/MotionPrompt)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://motion-prompting.github.io/)

+ **Optical Flow Meets Video Diffusion Model for Enhanced Camera-Controlled Video Synthesis** (25 Mar 2025)  
  <details><summary>Wonjoon Jin, Qi Dai, Chong Luo, et al.</summary> Seung-Hwan Baek, Sunghyun Cho, POSTECH, Microsoft Research Asia</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08244)    [![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cvpr.thecvf.com/virtual/2025/poster/33323)

+ **AC3D: Analyzing and Improving 3D Camera Control in Video Diffusion Transformers** (22 Mar 2025)  
  <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Guocheng Qian, et al.</summary> Aliaksandr Siarohin, Willi Menapace, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.18673)    [![Code](https://img.shields.io/github/stars/snap-research/ac3d.svg?style=social&label=Star)](https://github.com/snap-research/ac3d)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sherwinbahmani.github.io/)

+ **Aether: Geometric-Aware Unified World Modeling**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Mar 2025)  
  <details><summary>Aether Team, et al.</summary> Haoyi Zhu, Yifan Wang, Jianjun Zhou, Wenzheng Chang, Yang Zhou, Zizun Li, Junyi Chen, Chunhua Shen, Jiangmiao Pang, Tong He</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18945)    [![GitHub](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Star)](https://github.com/OpenRobotLab/Aether)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aether-world.github.io/)

+ **EgoSim: Egocentric Exploration in Virtual Worlds with Multi-modal Conditioning** (16 Mar 2025)  
  <details><summary>Wei Yu, Songheng Yin, Steve Easterbrook, Animesh Garg, et al.</summary></details>  
  
  [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=zAyS5aRKV8)    [![code](https://img.shields.io/github/stars/opendilab/awesome-exploration-rl.svg?style=social&label=Star)](https://github.com/opendilab/awesome-exploration-rl)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://iplab.dmi.unict.it/egoism-hoi/)

+ **I2V3D: Controllable Image-to-Video Generation with 3D Guidance**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Mar 2025)  
  <details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.09733)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://arxiv.org/html/2503.09733v1)

+ **CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Mar 2025)  
  <details><summary>Hao He, Ceyuan Yang, Shanchuan Lin, et al.</summary> Yinghao Xu, Meng Wei, Liangke Gui, Qi Zhao, Gordon Wetzstein, Lu Jiang, Hongsheng Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.10592)    [![code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/Projects-CameraCtrl-II/)

+ **CameraCtrl: Enabling Camera Control for Text-to-Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Mar 2025)  
  <details><summary>Hao He, Yinghao Xu, Yuwei Guo, et al.</summary> Gordon Wetzstein, Bo Dai, Hongsheng Li, Ceyuan Yang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.02101)    [![Code](https://img.shields.io/github/stars/hehao13/CameraCtrl.svg?style=social&label=Star)](https://github.com/hehao13/CameraCtrl)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hehao13.github.io/projects-CameraCtrl/)

+ **ReCamMaster: Camera-Controlled Generative Rendering from A Single Video**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Mar 2025)  
  <details><summary>Jianhong Bai, Menghan Xia, Xiao Fu, et al.</summary> Xintao Wang, Lianrui Mu, Jinwen Cao, Zuozhu Liu, Haoji Hu, Xiang Bai, Pengfei Wan, Di Zhang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.11647)    [![code](https://img.shields.io/github/stars/KwaiVGI/ReCamMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/ReCamMaster)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jianhongbai.github.io/ReCamMaster/)

+ **GEN3C: 3D-Informed World-Consistent Video Generation with Precise Camera Control**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Mar 2025)  
  <details><summary>Xuanchi Ren, Tianchang Shen, Jiahui Huang, et al.</summary> Huan Ling, Yifan Lu, Merlin Nimier-David, Thomas Müller, Alexander Keller, Sanja Fidler, Jun Gao</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.03751)    [![Code](https://img.shields.io/github/stars/nv-tlabs/GEN3C.svg?style=social&label=Star)](https://github.com/nv-tlabs/GEN3C)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aiartweekly.com/tools/gen3c-3d-informed-world-consistent-video-generation-with-precise-camera-control)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** (10 Mar 2025)  
  <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary> Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.05020)    [![Project Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chen-yingjie.github.io/projects/Perception-as-Control/)    [![code](https://img.shields.io/github/stars/chen-yingjie/Perception-as-Control.svg?style=social&label=Star)](https://github.com/chen-yingjie/Perception-as-Control)

+ **I2VCONTROL-CAMERA: Precise Video Camera Control with Adjustable Motion Strength** (28 Feb 2025)  
  <details><summary>Wanquan Feng, Jiawei Liu, Pengqi Tu, et al.</summary> Tianhao Qi, Mingzhen Sun, Tianxiang Ma, Songtao Zhao, Siyu Zhou, Qian He</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.06525)    [![code](https://img.shields.io/github/stars/WanquanF/I2VControl-Camera.svg?style=social&label=Star)](https://github.com/WanquanF/I2VControl-Camera)

+ **CineMaster: A 3D-Aware and Controllable Framework for Cinematic Text-to-Video Generation** (12 Feb 2025)  
  <details><summary>Qinghe Wang, Yawen Luo, Xiaoyu Shi, et al.</summary> Xu Jia, Huchuan Lu, Tianfan Xue, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.08639)    [![code](https://img.shields.io/github/stars/yzhang2016/video-generation-survey.svg?style=social&label=Star)](https://github.com/yzhang2016/video-generation-survey/blob/main/video-generation.md)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deeplearn.org/arxiv/575817/cinemaster:-a-3d-aware-and-controllable-framework-for-cinematic-text-to-video-generation)

+ **Direct-a-Video: Customized Video Generation with User-Directed Camera Movement and Object Motion**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Feb 2025)  
  <details><summary>Shiyuan Yang, Liang Hou, Haibin Huang, et al.</summary> Chongyang Ma, Pengfei Wan, Di Zhang, Xiaodong Chen, Jing Liao</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)    [![Code](https://img.shields.io/github/stars/ysy31415/direct_a_video.svg?style=social&label=Star)](https://github.com/ysy31415/direct_a_video)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://direct-a-video.github.io/)

+ **RealCam-I2V: Real-World Image-to-Video Generation with Interactive Complex Camera Control** (14 Feb 2025)  
  <details><summary>Teng Li, Guangcong Zheng, Rui Jiang, et al.</summary> Shuigenzhan, Tao Wu, Yehao Lu, Yining Lin, Xi Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.10059)    [![Code](https://img.shields.io/github/stars/ZGCTroy/RealCam-I2V.svg?style=social&label=Star)](https://github.com/ZGCTroy/RealCam-I2V)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zgctroy.github.io/RealCam-I2V/)

+ **3DTrajMaster: Mastering 3D Trajectory for Multi-Entity Motion in Video Generation** (7 Feb 2025)  
  <details><summary>Xiao Fu, Xian Liu, Xintao Wang, et al.</summary> Sida Peng, Menghan Xia, Xiaoyu Shi, Ziyang Yuan, Pengfei Wan, Di Zhang, Dahua Lin</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07759)    [![code](https://img.shields.io/github/stars/KwaiVGI/3DTrajMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/3DTrajMaster)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.aimodels.fyi/papers/arxiv/3dtrajmaster-mastering-3d-trajectory-multi-entity-motion)

+ **You See it, You Got it: Learning 3D Creation on Pose-Free Videos at Scale** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Dec 2024)  
  <details><summary>[CVPR 2025] Baorui Ma, Huachen Gao, Haoge Deng, et al.</summary> Baorui Ma, Huachen Gao, Haoge Deng, Zhengxiong Luo, Tiejun Huang, Lulu Tang, Xinlong Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06699/)    [![Code](https://img.shields.io/github/stars/baaivision/See3D)](https://github.com/baaivision/See3D)   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://vision.baai.ac.cn/see3d/)

+ **Latent-Reframe: Enabling Camera Control for Video Diffusion Model without Training** (8 Dec 2024)  
  <details><summary>Zhenghong Zhou, Jie An, Jiebo Luo, et al.</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06029)  [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://img.shields.io/badge/Project_Pa)

+ **CamI2V: Camera-Controlled Image-to-Video Diffusion Model** (4 Dec 2024)  
  <details><summary>Guangcong Zheng, Teng Li, Rui Jiang, et al.</summary> Yehao Lu, Tao Wu, Xi Li</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.15957)    [![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zgctroy.github.io/CamI2V/?ref=aiartweekly)

+ **I2VControl: Disentangled and Unified Video Motion Synthesis Control**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Nov 2024)  
  <details><summary>Zhiyuan Zhang, Dongdong Chen, Jing Liao</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.17765)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wanquanf.github.io/I2VControl)

+ **Trajectory Attention: Enhancing Video Generation with Fine-Grained Motion Control** (28 Nov 2024)  
  <details><summary>Zeqi Xiao, Wenqi Ouyang, Yifan Zhou, et al.</summary> Shuai Yang, Lei Yang, Jianlou Si, Xingang Pan</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2411.19324)    [![Code](https://img.shields.io/github/stars/JinWonjoon/FloVD.svg?style=social&label=Star)](https://github.com/JinWonjoon/FloVD)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deep-diver.github.io/ai-paper-reviewer/paper-reviews/2411.19324/)

+ **Video Diffusion Models are Training-free Motion Interpreter and Controller** (12 Nov 2024)  
  <details><summary>Zeqi Xiao, Yifan Zhou, Shuai Yang, Xingang Pan, et al.</summary></details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.14864)   [![Code](https://img.shields.io/github/stars/xizaoqu/MOFT.svg?style=social&label=Star)](https://github.com/xizaoqu/MOFT)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xizaoqu.github.io/moft/)

+ **DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Nov 2024)  
  <details><summary>Wenqiang Sun, Shuo Chen, Fangfu Liu, et al.</summary> Zilong Chen, Yueqi Duan, Jun Zhang, Yikai Wang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.04928)    [![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Star)](https://github.com/wenqsun/DimensionX)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://chenshuo20.github.io/DimensionX/)

+ **Boosting Camera Motion Control for Video Diffusion Transformers** (14 Oct 2024)  
  <details><summary>Soon Yau Cheong, Duygu Ceylan, Armin Mustafa, et al.</summary> Andrew Gilbert, Chun-Hao Paul Huang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10802)    [![code](https://img.shields.io/github/stars/soon-yau/CameraMotionGuidance.svg?style=social&label=Star)](https://github.com/soon-yau/CameraMotionGuidance)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://soon-yau.github.io/CameraMotionGuidance/)

+ **Cavia: Camera-controllable Multi-view Video Diffusion with View-Integrated Attention** (14 Oct 2024)  
  <details><summary>Dejia Xu, Yifan Jiang, Chen Huang, et al.</summary> Liangchen Song, Thorsten Gernoth, Liangliang Cao, Zhangyang Wang, Hao Tang</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10774)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ir1d.github.io/Cavia/)

+ **ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis** (3 Sep 2024)  
  <details><summary>Wangbo Yu, Jinbo Xing, Li Yuan, et al.</summary> Wenbo Hu, Xiaoyu Li, Zhipeng Huang, Xiangjun Gao, Tien-Tsin Wong, Ying Shan, Yonghong Tian</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.02048)    [![Code](https://img.shields.io/github/stars/Drexubery/ViewCrafter.svg?style=social&label=Star)](https://github.com/Drexubery/ViewCrafter)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drexubery.github.io/ViewCrafter/)

+ **VD3D: Taming Large Video Diffusion Transformers for 3D Camera Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Jul 2024)  
  <details><summary>Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, et al.</summary> Sherwin Bahmani, Ivan Skorokhodov, Aliaksandr Siarohin, Willi Menapace, Guocheng Qian, Michael Vasilkovsky, Hsin-Ying Lee, Chaoyang Wang, Jiaxu Zou, Andrea Tagliasacchi, David B. Lindell, Sergey Tulyakov</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.03162)    [![code](https://img.shields.io/github/stars/Yangzhangcst/Transformer-in-Computer-Vision.svg?style=social&label=Star)](https://github.com/Yangzhangcst/Transformer-in-Computer-Vision/blob/main/main/diffusion.md)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/vd3d/gallery.html)

+ **MotionCtrl: A Unified and Flexible Motion Controller for Video Generation** (16 Jul 2024)  
  <details><summary>Zhouxia Wang, Ziyang Yuan, Xintao Wang, et al.</summary> Zhouxia Wang, Ziyang Yuan, Xintao Wang, Tianshui Chen, Menghan Xia, Ping Luo, Ying Shan</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.03641)    [![Project Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wzhouxiff.github.io/projects/MotionCtrl/)    [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/TencentARC/MotionCtrl)

+ **CamCo: Camera-Controllable 3D-Consistent Image-to-Video Generation** (4 Jun 2024)  
  <details><summary>Dejia Xu, Weili Nie, Chao Liu, et al.</summary> Sifei Liu, Jan Kautz, Zhangyang Wang, Arash Vahdat</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ir1d.github.io/CamCo/)    [![code](https://img.shields.io/github/stars/wangqiang9/Awesome-Controllable-Video-Diffusion.svg?style=social&label=Star)](https://github.com/wangqiang9/Awesome-Controllable-Video-Diffusion)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ir1d.github.io/CamCo/)

+ **MotionMaster: Training-free Camera Motion Transfer For Video Generation** (1 May 2024)  
  <details><summary>Teng Hu, Jiangning Zhang, Ran Yi, et al.</summary> Yating Wang, Hongrui Huang, Jieyu Weng, Yabiao Wang, Lizhuang Ma</details>  
  
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.15789)   [![Code](https://img.shields.io/github/stars/sjtuplayer/MotionMaster.svg?style=social&label=Star)](https://github.com/sjtuplayer/MotionMaster)    [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dsin.ai/news/article/cBZRAtg/motionmaster_training_free_camera_motion_transfer_for_video_generation)

+ **MOTIONFLOW: Learning Implicit Motion Flow for Complex Camera Trajectory Control in Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (Dec 2024)  
  <details><summary>Author list not fully provided</summary></details>  
  
  [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=OBTmkKBmQW)   
### 🎬 Motion-Guided
<a id="-motion-guided"></a>

<!-- RECENT_VERIFIED_START:Motion-Guided -->

+ **Temporally Consistent and Controllable Video Generation of 2D Cine CMR via Latent Space Motion Modeling** (8 Jun 2026)
  <details><summary>Yiheng Cao, Gustavo Andrade-Miranda, Jiatian Zhang, et al.</summary>Yiheng Cao, Gustavo Andrade-Miranda, Jiatian Zhang, Guillaume Sallé, Xin Gao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.14759)

+ **Streaming Video Generation with Streaming Force Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Jun 2026)
  <details><summary>Hanhui Wang, Yiming Xie, Haiwen Feng, et al.</summary>Hanhui Wang, Yiming Xie, Haiwen Feng, Zhaoyang Lv, Shenlong Wang, Huaizu Jiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.07508) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://neu-vi.github.io/StreamForce/)

+ **SKIP: Sparse Keyframe Interpolation Paradigm for Efficient Embodied World Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 May 2026)
  <details><summary>Ziheng He, Yixiang Chen, Ning Yang, et al.</summary>Ziheng He, Yixiang Chen, Ning Yang, Zhanqian Wu, Qisen Ma, Yuan Xu, Jiabing Yang, Peiyan Li, Xiangnan Wu, Xiaofeng Wang, Zheng Zhu, Jing Liu, Nianfeng Liu, Yan Huang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.00664)

+ **From Articulated Kinematics to Routed Visual Control for Action-Conditioned Surgical Video Generation** (9 May 2026)
  <details><summary>Bohan Li, Shuojue Yang, Baorui Peng, et al.</summary>Bohan Li, Shuojue Yang, Baorui Peng, Xianda Guo, Erli Zhang, Youqi Tao, Junfeng Duan, Daguang Xu, Qi Dou, Xin Jin, Wenjun Zeng, Hao Zhao, Yueming Jin</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.08712)

+ **Prompt Relay: Inference-Time Temporal Control for Multi-Event Video Generation** (11 Apr 2026)
  <details><summary>Gordon Chen, Ziqi Huang, Ziwei Liu</summary>Gordon Chen, Ziqi Huang, Ziwei Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.10030)

+ **MotionGrounder: Grounded Multi-Object Motion Transfer via Diffusion Transformer** (1 Apr 2026)
  <details><summary>Samuel Teodoro, Yun Chen, Agus Gunawan, et al.</summary>Samuel Teodoro, Yun Chen, Agus Gunawan, Soo Ye Kim, Jihyong Oh, Munchurl Kim</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.00853) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kaist-viclab.github.io/motiongrounder-site/)

+ **Search2Motion: Training-Free Object-Level Motion Control via Attention-Consensus Search** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Mar 2026)
  <details><summary>Sainan Liu, Tz-Ying Wu, Hector A Valdez, et al.</summary>Sainan Liu, Tz-Ying Wu, Hector A Valdez, Subarna Tripathi</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.16711)

+ **RealWonder: Real-Time Physical Action-Conditioned Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Mar 2026)
  <details><summary>Wei Liu, Ziyu Chen, Zizhang Li, et al.</summary>Wei Liu, Ziyu Chen, Zizhang Li, Yue Wang, Hong-Xing Yu, Jiajun Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.05449) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://liuwei283.github.io/RealWonder/)

+ **Kling-MotionControl Technical Report** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Mar 2026)
  <details><summary>Kling Team, Jialu Chen, Yikang Ding, et al.</summary>Kling Team, Jialu Chen, Yikang Ding, Zhixue Fang, Kun Gai, Kang He, Xu He, Jingyun Hua, Mingming Lao, Xiaohan Li, Hui Liu, Jiwen Liu, Xiaoqiang Liu, Fan Shi, Xiaoyu Shi, Peiqin Sun, Songlin Tang, Pengfei Wan, Tiancheng Wen, Zhiyong Wu, Haoxian Zhang, Runze Zhao, Yuanxing Zhang, Yan Zhou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.03160) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://app.klingai.com/global/video-motion-control/new)

+ **Let Your Image Move with Your Motion! -- Implicit Multi-Object Multi-Motion Transfer** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Mar 2026)
  <details><summary>Yuze Li, Dong Gong, Xiao Cao, et al.</summary>Yuze Li, Dong Gong, Xiao Cao, Junchao Yuan, Dongsheng Li, Lei Zhou, Yun Sing Koh, Cheng Yan, Xinyu Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.01000) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ethan-li123.github.io/FlexiMMT_page/)

+ **IM-Animation: An Implicit Motion Representation for Identity-decoupled Character Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Feb 2026)
  <details><summary>Zhufeng Xu, Xuan Gao, Feng-Lin Liu, et al.</summary>Zhufeng Xu, Xuan Gao, Feng-Lin Liu, Haoxian Zhang, Zhixue Fang, Yu-Kun Lai, Xiaoqiang Liu, Pengfei Wan, Lin Gao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.07498)

+ **3D-Aware Implicit Motion Control for View-Adaptive Human Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Feb 2026)
  <details><summary>Zhixue Fang, Xu He, Songlin Tang, et al.</summary>Zhixue Fang, Xu He, Songlin Tang, Haoxian Zhang, Qingfeng Li, Xiaoqiang Liu, Pengfei Wan, Kun Gai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.03796) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hjrphoebus.github.io/3DiMo)

+ **Making Avatars Interact: Towards Text-Driven Human-Object Interaction for Controllable Talking Avatars** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Feb 2026)
  <details><summary>Youliang Zhang, Zhengguang Zhou, Zhentao Yu, et al.</summary>Youliang Zhang, Zhengguang Zhou, Zhentao Yu, Ziyao Huang, Teng Hu, Sen Liang, Guozhen Zhang, Ziqiao Peng, Shunkai Li, Yi Chen, Zixiang Zhou, Yuan Zhou, Qinglin Lu, Xiu Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.01538) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://interactavatar.github.io)

+ **DreamActor-M2: Universal Character Image Animation via Spatiotemporal In-Context Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Jan 2026)
  <details><summary>Mingshuang Luo, Shuang Liang, Zhengkun Rong, et al.</summary>Mingshuang Luo, Shuang Liang, Zhengkun Rong, Yuxuan Luo, Tianshu Hu, Ruibing Hou, Hong Chang, Yong Li, Yuan Zhang, Mingyuan Gao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.21716) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://grisoon.github.io/DreamActor-M2/)

+ **CoVAR: Co-generation of Video and Action for Robotic Manipulation via Multi-Modal Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Dec 2025)
  <details><summary>Liudi Yang, Yang Bai, George Eskandar, et al.</summary>Liudi Yang, Yang Bai, George Eskandar, Fengyi Shen, Mohammad Altillawi, Dong Chen, Ziyuan Liu, Abhinav Valada</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.16023)

+ **MultiMotion: Multi Subject Video Motion Transfer via Video Diffusion Transformer** (8 Dec 2025)
  <details><summary>Penghui Liu, Jiangshan Wang, Yutong Shen, et al.</summary>Penghui Liu, Jiangshan Wang, Yutong Shen, Shanhui Mo, Chenyang Qi, Yue Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.07500)

+ **World Models That Know When They Don't Know - Controllable Video Generation with Calibrated Uncertainty** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Dec 2025)
  <details><summary>Zhiting Mei, Tenny Yin, Micah Baker, et al.</summary>Zhiting Mei, Tenny Yin, Micah Baker, Ola Shorinwa, Anirudha Majumdar</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.05927) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://c-cubed-uq.github.io)

+ **Infinity-RoPE: Action-Controllable Infinite Video Generation Emerges From Autoregressive Self-Rollout** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Nov 2025)
  <details><summary>Hidir Yesiltepe, Tuna Han Salih Meral, Adil Kaan Akan, et al.</summary>Hidir Yesiltepe, Tuna Han Salih Meral, Adil Kaan Akan, Kaan Oktay, Pinar Yanardag</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.20649) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://infinity-rope.github.io)

+ **PhysChoreo: Physics-Controllable Video Generation with Part-Aware Semantic Grounding** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Nov 2025)
  <details><summary>Haoze Zhang, Tianyu Huang, Zichen Wan, et al.</summary>Haoze Zhang, Tianyu Huang, Zichen Wan, Xiaowei Jin, Hongzhi Zhang, Hui Li, Wangmeng Zuo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.20562) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://kakaka0521.github.io/physchoreo_web)

+ **Time-to-Move: Training-Free Motion Controlled Video Generation via Dual-Clock Denoising** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Nov 2025)
  <details><summary>Assaf Singer, Noam Rotstein, Amir Mann, et al.</summary>Assaf Singer, Noam Rotstein, Amir Mann, Ron Kimmel, Or Litany</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.08633) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://time-to-move.github.io/)

+ **CoMo: Compositional Motion Customization for Text-to-Video Generation** (27 Oct 2025)
  <details><summary>Youcan Xu, Zhen Wang, Jiaxin Shi, et al.</summary>Youcan Xu, Zhen Wang, Jiaxin Shi, Kexin Li, Feifei Shao, Jun Xiao, Yi Yang, Jun Yu, Long Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.23007) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://como6.github.io/)

+ **MultiModal Action Conditioned Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Oct 2025)
  <details><summary>Yichen Li, Antonio Torralba</summary>Yichen Li, Antonio Torralba</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.02287) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://people.csail.mit.edu/yichenl/projects/multimodalvideo/)

+ **ControlHair: Synergizing Physics Simulator and Video Diffusion for Controllable Dynamic Hair Rendering** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Sep 2025)
  <details><summary>Weikai Lin, Haoxiang Li, Yuhao Zhu</summary>Weikai Lin, Haoxiang Li, Yuhao Zhu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.21541) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://linwk20.github.io/controlhair-web)

+ **NewtonGen: Physics-Consistent and Controllable Text-to-Video Generation via Neural Newtonian Dynamics** (25 Sep 2025)
  <details><summary>Yu Yuan, Xijun Wang, Tharindu Wickremasinghe, et al.</summary>Yu Yuan, Xijun Wang, Tharindu Wickremasinghe, Zeeshan Nadir, Bole Ma, Stanley H. Chan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.21309) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/pandayuanyu/NewtonGen)

+ **PhysCtrl: Generative Physics for Controllable and Physics-Grounded Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Sep 2025)
  <details><summary>Chen Wang, Chuhao Chen, Yiming Huang, et al.</summary>Chen Wang, Chuhao Chen, Yiming Huang, Zhiyang Dou, Yuan Liu, Jiatao Gu, Lingjie Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.20358) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cwchenwang.github.io/physctrl)

+ **EDTalk++: Full Disentanglement for Controllable Talking Head Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Aug 2025)
  <details><summary>Shuai Tan, Bin Ji</summary>Shuai Tan, Bin Ji</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.13442)

+ **RealisMotion: Decomposed Human Motion Control and Video Generation in the World Space** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Aug 2025)
  <details><summary>Jingyun Liang, Jingkai Zhou, Shikai Li, et al.</summary>Jingyun Liang, Jingkai Zhou, Shikai Li, Chenjie Cao, Lei Sun, Yichen Qian, Weihua Chen, Fan Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.08588) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://jingyunliang.github.io/RealisMotion)

+ **MotionShot: Adaptive Motion Transfer across Arbitrary Objects for Text-to-Video Generation** (22 Jul 2025)
  <details><summary>Yanchen Liu, Yanan Sun, Zhening Xing, et al.</summary>Yanchen Liu, Yanan Sun, Zhening Xing, Junyao Gao, Kai Chen, Wenjie Pei</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.16310)

+ **FixTalk: Taming Identity Leakage for High-Quality Talking Head Generation in Extreme Cases** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Jul 2025)
  <details><summary>Shuai Tan, Bill Gong, Bin Ji, et al.</summary>Shuai Tan, Bill Gong, Bin Ji, Ye Pan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.01390)

<!-- RECENT_VERIFIED_END:Motion-Guided -->

+ **FlexiAct: Towards Flexible Action Control in Heterogeneous Scenarios** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 May 2025)
   <details><summary> [SIGGRAPH 2025] Shiyi Zhang*, Junhao Zhuang*, et al.</summary>  
        Shiyi Zhang*, Junhao Zhuang*, Zhaoyang Zhang, Ying Shan, Yansong Tang </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.03730)
   [![Code](https://img.shields.io/github/stars/shiyi-zh0408/FlexiAct.svg?style=social&label=Star)](https://github.com/shiyi-zh0408/FlexiAct)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shiyi-zh0408.github.io/projectpages/FlexiAct/)
  
+ **Follow-Your-Motion: Video Motion Transfer via Efficient Spatial-Temporal Decoupled Finetuning** (5 Jun 2025)
   <details><summary>Yue Ma, Yulong Liu, Qiyuan Zhu, et al.</summary>  
         Yue Ma, Yulong Liu, Qiyuan Zhu, Ayden Yang, Kunyu Feng, Xinhua Zhang, Zhifeng Li, Sirui Han, Chenyang Qi, Qifeng Chen</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.05207)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://follow-your-motion.github.io/)
+ **MotionPro: A Precise Motion Controller for Image-to-Video Generation** (29 May 2025)
   <details><summary>Zhongwei Zhang, Fuchen Long, Zhaofan Qiu, et al.</summary>  
         Zhongwei Zhang, Fuchen Long, Zhaofan Qiu, Yingwei Pan, Wu Liu, Ting Yao, Tao Mei</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.20287)
   [![Code](https://img.shields.io/github/stars/HiDream-ai/MotionPro.svg?style=social&label=Star)](https://github.com/HiDream-ai/MotionPro)
   [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://zhw-zhang.github.io/MotionPro-page/)

+ **DualReal: Joint Training for Lossless Identity-Motion Fusion in Video Customization**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 May 2025)
   <details><summary>Wenchuan Wang, Mengqi Huang, Yijing Tu, et al.</summary>  
         Wenchuan Wang, Mengqi Huang, Yijing Tu, Zhendong Mao</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2505.02192)
  

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

+ **Motion Prompting: Controlling Video Generation with Motion Trajectories** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Mar 2025) <details><summary>Daniel Geng, Charles Herrmann, Junhwa Hur, et al.</summary>Daniel Geng, Charles Herrmann, Junhwa Hur, Forrester Cole, Serena Zhang, Tobias Pfaff, Tatiana Lopez-Guevara, Carl Doersch, Yusuf Aytar, Michael Rubinstein, Chen Sun, Oliver Wang, Andrew Owens, Deqing Sun</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02700)
+ **EfficientMT: Efficient Temporal Adaptation for Motion Transfer in Text-to-Video Diffusion Models** (25 Mar 2025)  
   <details><summary>Yufei Cai, et al.</summary>  
         Yufei Cai, Hu Han, Yuxiang Wei, Shiguang Shan, Xilin Chen</details>  
         
   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.19369)

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

+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Jan 2025) <details><summary>Zekai Gu, Rui Yan, Jiahao Lu, et al.</summary>Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu</details>
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

+ **AnimateAnything: Consistent and Controllable Animation for Video Generation**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Nov 2024) <details><summary>Guojun Lei, Chi Wang, Hong Li, et al.</summary>Guojun Lei, Chi Wang, Hong Li, Rong Zhang, Yikai Wang, Weiwei Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://animationai.github.io/AnimateAnything/)
[![Code](https://img.shields.io/github/stars/alibaba/animate-anything.svg?style=social&label=Star)](https://github.com/alibaba/animate-anything)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://yu-shaonian.github.io/Animate_Anything/)

+ **Motionbooth: Motion-aware customized text-to-video generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Oct 2024) <details><summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, et al.</summary>Jianzong Wu, Xiangtai Li, Yanhong Zeng, Jiangning Zhang, Qianyu Zhou, Yining Li, Yunhai Tong, Kai Chen</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17758)
[![Code](https://img.shields.io/github/stars/jianzongwu/MotionBooth.svg?style=social&label=Star)](https://github.com/jianzongwu/MotionBooth)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](http://jianzongwu.github.io/projects/motionbooth/)

+ **MotionClone: Training-Free Motion Cloning for Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Oct 2024) <details><summary>Pengyang Ling, Jiazi Bu, Pan Zhang, et al.</summary>Pengyang Ling, Jiazi Bu, Pan Zhang, Xiaoyi Dong, Yuhang Zang, Tong Wu, Huaian Chen, Jiaqi Wang, Yi Jin</details>
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

+ **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Jun 2024) <details><summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.14781)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/champ/#/)

+ **Customize-A-Video: One-Shot Motion Customization of Text-to-Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Aug 2024)  <details><summary>Yixuan Ren, Yang Zhou, Jimei Yang, et al.</summary>Yixuan Ren, Yang Zhou, Jimei Yang, Jing Shi, Difan Liu, Feng Liu, Mingi Kwon, Abhinav Shrivastava</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.14780)
[![Code](https://img.shields.io/github/stars/customize-a-video/customize-a-video.svg?style=social&label=Star)](https://github.com/customize-a-video/customize-a-video)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.aimodels.fyi/papers/arxiv/customize-video-one-shot-motion-customization-text)

+ **Perception-as-Control: Fine-grained Controllable Image Animation with 3D-aware Motion Representation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Dec 2023) <details><summary>Yingjie Chen, Yifang Men, Yuan Yao, et al.</summary>Yingjie Chen, Yifang Men, Yuan Yao, Miaomiao Cui, Liefeng Bo</details>
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

+ **MotionDirector: Motion Customization for Text-to-Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Oct 2023)<details><summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, et al.</summary>Rui Zhao, Yuchao Gu, Jay Zhangjie Wu, David Junhao Zhang, Jia-Wei Liu, Weijia Wu, Jussi Keppo, and Mike Zheng Shou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08465)
[![Code](https://img.shields.io/github/stars/showlab/MotionDirector.svg?style=social&label=Star)](https://github.com/showlab/MotionDirector)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ruizhaocv.github.io/)


## 🔊 Audio Control

### 🗣️ Voice-Guided
<a id="-voice-guided"></a>

<!-- RECENT_VERIFIED_START:Voice-Guided -->

+ **SyncCache: Exploiting Asymmetric Dynamics for Fast Audio-Driven Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Jun 2026)
  <details><summary>Juncheng Ma, Yuxuan Du, Yanan Sun, et al.</summary>Juncheng Ma, Yuxuan Du, Yanan Sun, Zhening Xing, Changlin Li, Zhenyu Tang, Bo Li, Peng-Tao Jiang, Li Yuan, Daquan Zhou, Yonghong Tian</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.30849)

+ **EmoZone-Talker: Regional Semantic Control of Audio-Driven 3DGS Talking Heads via Facial Action Units** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Jun 2026)
  <details><summary>Tingting Chen, Shaojun Wang, Huaye Zhang, et al.</summary>Tingting Chen, Shaojun Wang, Huaye Zhang, Diqiong Jiang, Chenglizhao Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.15848)

+ **ReFree: Towards Realistic Co-Speech Video Generation via Reward-Free RL and Multilevel Speech Guidance** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Jun 2026)
  <details><summary>Salaheldin Mohamed, M. Hamza Mughal, Rishabh Dabral, et al.</summary>Salaheldin Mohamed, M. Hamza Mughal, Rishabh Dabral, Christian Theobalt</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.13304)

+ **Mamba-Enhanced Implicit Motion Learning for Audio-Driven Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Jun 2026)
  <details><summary>Xuan Wei, Jiahui Chen, Kaiheng Li, et al.</summary>Xuan Wei, Jiahui Chen, Kaiheng Li, Mingyu Shao, Qingqi Hong</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.03402)

+ **Real-Time Generation of Streamable Talking Portrait Video with Reference-Guided Deep Compression VAEs** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Jun 2026)
  <details><summary>Sicheng Xu, Yu Deng, Shoukang Hu, et al.</summary>Sicheng Xu, Yu Deng, Shoukang Hu, Yichuan Wang, Yizhong Zhang, Zhan Chen, Jiaolong Yang, Baining Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.01620)

+ **CogPortrait: Fine-Grained Eye-Region Control in Portrait Animation via Hierarchical Agent Planning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 May 2026)
  <details><summary>He Feng, Yongjia Ma, Donglin Di, et al.</summary>He Feng, Yongjia Ma, Donglin Di, Lei Fan, Tonghua Su</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.28056)

+ **Test-Time Self-Adaptive Conditioning for Stable Audio-Driven Talking-Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 May 2026)
  <details><summary>Zhicheng Zhang, Lei Wang, Yu Zhang, et al.</summary>Zhicheng Zhang, Lei Wang, Yu Zhang, Yongsheng Gao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.25488)

+ **MoCoTalk: Multi-Conditional Diffusion with Adaptive Router for Controllable Talking Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 May 2026)
  <details><summary>Xinyan Ye, Jiankang Deng, Abbas Edalat</summary>Xinyan Ye, Jiankang Deng, Abbas Edalat</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.08050)

+ **CoInteract: Physically-Consistent Human-Object Interaction Video Synthesis via Spatially-Structured Co-Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2026)
  <details><summary>Xiangyang Luo, Xiaozhe Xin, Tao Feng, et al.</summary>Xiangyang Luo, Xiaozhe Xin, Tao Feng, Xu Guo, Meiguang Jin, Junfeng Ma</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.19636) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xinxiaozhe12345.github.io/CoInteract_Project/)

+ **TurboTalk: Progressive Distillation for One-Step Audio-Driven Talking Avatar Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Apr 2026)
  <details><summary>Xiangyu Liu, Feng Gao, Xiaomei Zhang, et al.</summary>Xiangyu Liu, Feng Gao, Xiaomei Zhang, Yong Zhang, Xiaoming Wei, Zhen Lei, Xiangyu Zhu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.14580)

+ **PrivFedTalk: Privacy-Aware Federated Diffusion with Identity-Stable Adapters for Personalized Talking-Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Apr 2026)
  <details><summary>Soumya Mazumdar, Vineet Kumar Rakesh, Tapas Samanta</summary>Soumya Mazumdar, Vineet Kumar Rakesh, Tapas Samanta</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.08037)

+ **EmoTaG: Emotion-Aware Talking Head Synthesis on Gaussian Splatting with Few-Shot Personalization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (22 Mar 2026)
  <details><summary>Haolan Xu, Keli Cheng, Lei Wang, et al.</summary>Haolan Xu, Keli Cheng, Lei Wang, Ning Bi, Xiaoming Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.21332)

+ **EARTalking: End-to-end GPT-style Autoregressive Talking Head Synthesis with Frame-wise Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Mar 2026)
  <details><summary>Yuzhe Weng, Haotian Wang, Yuanhong Yu, et al.</summary>Yuzhe Weng, Haotian Wang, Yuanhong Yu, Jun Du, Shan He, Xiaoyan Wu, Haoran Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.20307)

+ **TempoSyncDiff: Distilled Temporally-Consistent Diffusion for Low-Latency Audio-Driven Talking Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Mar 2026)
  <details><summary>Soumya Mazumdar, Vineet Kumar Rakesh</summary>Soumya Mazumdar, Vineet Kumar Rakesh</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.06057) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://mazumdarsoumya.github.io/TempoSyncDiff)

+ **FlowPortrait: Reinforcement Learning for Audio-Driven Portrait Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Feb 2026)
  <details><summary>Weiting Tan, Andy T. Liu, Ming Tu, et al.</summary>Weiting Tan, Andy T. Liu, Ming Tu, Xinghua Qu, Philipp Koehn, Lu Lu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.00159)

+ **3DXTalker: Unifying Identity, Lip Sync, Emotion, and Spatial Dynamics in Expressive 3D Talking Avatars** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Feb 2026)
  <details><summary>Zhongju Wang, Zhenhong Sun, Beier Wang, et al.</summary>Zhongju Wang, Zhenhong Sun, Beier Wang, Yifu Wang, Daoyi Dong, Huadong Mo, Hongdong Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.10516) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://engineeringai-lab.github.io/3DXTalker.github.io/)

+ **EditYourself: Audio-Driven Generation and Manipulation of Talking Head Videos with Diffusion Transformers** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Jan 2026)
  <details><summary>John Flynn, Wolfgang Paier, Dimitar Dinev, et al.</summary>John Flynn, Wolfgang Paier, Dimitar Dinev, Sam Nhut Nguyen, Hayk Poghosyan, Manuel Toribio, Sandipan Banerjee, Guy Gafni</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.22127) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://edit-yourself.github.io)

+ **MM-Sonate: Multimodal Controllable Audio-Video Generation with Zero-Shot Voice Cloning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Jan 2026)
  <details><summary>Chunyu Qiang, Jun Wang, Xiaopeng Wang, et al.</summary>Chunyu Qiang, Jun Wang, Xiaopeng Wang, Kang Yin, Yuxin Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.01568)

+ **In-Context Audio Control of Video Diffusion Transformers** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Dec 2025)
  <details><summary>Wenze Liu, Weicai Ye, Minghong Cai, et al.</summary>Wenze Liu, Weicai Ye, Minghong Cai, Quande Liu, Xintao Wang, Xiangyu Yue</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.18772)

+ **TalkVerse: Democratizing Minute-Long Audio-Driven Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Dec 2025)
  <details><summary>Zhenzhi Wang, Jian Wang, Ke Ma, et al.</summary>Zhenzhi Wang, Jian Wang, Ke Ma, Dahua Lin, Bing Zhou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.14938) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhenzhiwang.github.io/talkverse/)

+ **STARCaster: Spatio-Temporal AutoRegressive Video Diffusion for Identity- and View-Aware Talking Portraits** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Dec 2025)
  <details><summary>Foivos Paraperas Papantoniou, Stathis Galanakis, Rolandos Alexandros Potamias, et al.</summary>Foivos Paraperas Papantoniou, Stathis Galanakis, Rolandos Alexandros Potamias, Bernhard Kainz, Stefanos Zafeiriou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.13247) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://foivospar.github.io/STARCaster/)

+ **JoyStreamer-Flash: Real-time and Infinite Audio-Driven Avatar Generation with Autoregressive Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Dec 2025)
  <details><summary>Chaochao Li, Ruikui Wang, Liangbo Zhou, et al.</summary>Chaochao Li, Ruikui Wang, Liangbo Zhou, Jinheng Feng, Huaishao Luo, Huan Zhang, Youzheng Wu, Xiaodong He</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.11423)

+ **AI killed the video star. Audio-driven diffusion model for expressive talking head generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Nov 2025)
  <details><summary>Baptiste Chopin, Tashvik Dhamija, Pranav Balaji, et al.</summary>Baptiste Chopin, Tashvik Dhamija, Pranav Balaji, Yaohui Wang, Antitza Dantcheva</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.22488) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tashvikdhamija.github.io/dimitra/)

+ **ConsistTalk: Intensity Controllable Temporally Consistent Talking Head Generation with Diffusion Noise Search** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Nov 2025)
  <details><summary>Zhenjie Liu, Jianzhang Lu, Renjie Lu, et al.</summary>Zhenjie Liu, Jianzhang Lu, Renjie Lu, Cong Liang, Shangfei Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.06833)

+ **Playmate2: Training-Free Multi-Character Audio-Driven Animation via Diffusion Transformer with Reward Feedback** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Oct 2025)
  <details><summary>Xingpei Ma, Shenneng Huang, Jiaran Cai, et al.</summary>Xingpei Ma, Shenneng Huang, Jiaran Cai, Yuansheng Guan, Shen Zheng, Hanfeng Zhao, Qiang Zhang, Shunsi Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.12089) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://playmate111.github.io/Playmate2/)

+ **DEMO: Disentangled Motion Latent Flow Matching for Fine-Grained Controllable Talking Portrait Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Oct 2025)
  <details><summary>Peiyin Chen, Zhuowei Yang, Hui Feng, et al.</summary>Peiyin Chen, Zhuowei Yang, Hui Feng, Sheng Jiang, Rui Yan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.10650)

+ **Wan-S2V: Audio-Driven Cinematic Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Aug 2025)
  <details><summary>Xin Gao, Li Hu, Siqi Hu, et al.</summary>Xin Gao, Li Hu, Siqi Hu, Mingyang Huang, Chaonan Ji, Dechao Meng, Jinwei Qi, Penchong Qiao, Zhen Shen, Yafei Song, Ke Sun, Linrui Tian, Guangyuan Wang, Qi Wang, Zhongjian Wang, Jiayu Xiao, Sheng Xu, Bang Zhang, Peng Zhang, Xindi Zhang, Zhe Zhang, Jingren Zhou, Lian Zhuo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.18621)

+ **InfiniteTalk: Audio-driven Video Generation for Sparse-Frame Video Dubbing** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Aug 2025)
  <details><summary>Shaoshu Yang, Zhe Kong, Feng Gao, et al.</summary>Shaoshu Yang, Zhe Kong, Feng Gao, Meng Cheng, Xiangyu Liu, Yong Zhang, Zhuoliang Kang, Wenhan Luo, Xunliang Cai, Ran He, Xiaoming Wei</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.14033) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/MeiGen-AI/InfiniteTalk)

+ **StableAvatar: Infinite-Length Audio-Driven Avatar Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Aug 2025)
  <details><summary>Shuyuan Tu, Yueming Pan, Yinming Huang, et al.</summary>Shuyuan Tu, Yueming Pan, Yinming Huang, Xintong Han, Zhen Xing, Qi Dai, Chong Luo, Zuxuan Wu, Yu-Gang Jiang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.08248)

+ **RAP: Real-time Audio-driven Portrait Animation with Video Diffusion Transformer** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Aug 2025)
  <details><summary>Fangyu Du, Taiqing Li, Qian Qiao, et al.</summary>Fangyu Du, Taiqing Li, Qian Qiao, Tan Yu, Ziwei Zhang, Dingcheng Zhen, Xu Jia, Yang Yang, Shunshun Yin, Siyuan Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.05115)

+ **READ: Real-time and Efficient Asynchronous Diffusion for Audio-driven Talking Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Aug 2025)
  <details><summary>Haotian Wang, Yuzhe Weng, Jun Du, et al.</summary>Haotian Wang, Yuzhe Weng, Jun Du, Haoran Xu, Xiaoyan Wu, Shan He, Bing Yin, Cong Liu, Jianqing Gao, Qingfeng Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.03457) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://readportrait.github.io/READ)

+ **X-Actor: Emotional and Expressive Long-Range Portrait Acting from Audio** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Aug 2025)
  <details><summary>Chenxu Zhang, Zenan Li, Hongyi Xu, et al.</summary>Chenxu Zhang, Zenan Li, Hongyi Xu, You Xie, Xiaochen Zhao, Tianpei Gu, Guoxian Song, Xin Chen, Chao Liang, Jianwen Jiang, Linjie Luo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.02944) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://byteaigc.github.io/X-Actor/)

+ **ATL-Diff: Audio-Driven Talking Head Generation with Early Landmarks-Guide Noise Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Jul 2025)
  <details><summary>Hoang-Son Vo, Quang-Vinh Nguyen, Seungwon Kim, et al.</summary>Hoang-Son Vo, Quang-Vinh Nguyen, Seungwon Kim, Hyung-Jeong Yang, Soonja Yeom, Soo-Hyung Kim</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.12804) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/sonvth/ATL-Diff)

<!-- RECENT_VERIFIED_END:Voice-Guided -->

+ **Unlock Pose Diversity: Accurate and Efficient Implicit Keypoint-based Spatiotemporal Diffusion for Audio-driven Talking Portrait** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Sep 2025)<details><summary>[IJCV 2025] Chaolong Yang, Kai Yao, Yuyao Yan, et al.</summary>
Chenru Jiang, Weiguang Zhao, Jie Sun, Guangliang Cheng, Yifei Zhang, Bin Dong, Kaizhu Huang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.12963)
[![Code](https://img.shields.io/github/stars/chaolongy/KDTalker.svg?style=social&label=Star)](https://github.com/chaolongy/KDTalker)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://kdtalker.com/)

+ **Audio-visual Controlled Video Diffusion with Masked Selective State Spaces Modeling for Natural Talking Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Apr 2025)<details><summary>Fa-Ting Hong, Zunnan Xu, Zixiang Zhou, et al.</summary>
Jun Zhou, Xiu Li, Qin Lin, Qinglin Lu, Dan Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.02542)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://harlanhong.github.io/publications/actalker/index.html)
[![Code](https://img.shields.io/github/stars/harlanhong/ACTalker.svg?style=social&label=Star)](https://github.com/harlanhong/ACTalker)


+ **ChatAnyone: Stylized Real-time Portrait Video Generation with Hierarchical Motion Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Mar 2025)<details><summary>Jinwei Qi, Chaonan Ji, Sheng Xu, et al.</summary>
Peng Zhang, Bang Zhang, Liefeng Bo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.21144)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/chat-anyone/)

+ **MuseTalk: Real-Time High-Fidelity Video Dubbing via Spatio-Temporal Sampling** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Mar 2025)<details><summary>Yue Zhang, Zhizhou Zhong, Minhao Liu, et al.</summary>Zhaokang Chen, Bin Wu, Yubin Zeng, Chao Zhan, Junxin Huang, Yingjie He, Wenjiang Zhou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10122)
  [![Code](https://img.shields.io/github/stars/TMElyralab/MuseTalk.svg?style=social&label=Star)](https://github.com/TMElyralab/MuseTalk)

+ **Cafe-Talk: Generating 3D Talking Face Animation with Multimodal Coarse- and Fine-grained Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (14 Mar 2025)<details><summary>[ICLR 2025] Hejia Chen, Haoxian Zhang, Shoulong Zhang, et al.</summary>
Xiaoqiang Liu, Sisi Zhuang, Yuan Zhang, Pengfei Wan, Di Zhang, Shuai Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.14517)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://harryxd2018.github.io/cafe-talk/)

+ **Towards High-fidelity 3D Talking Avatar with Personalized Dynamic Texture** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (1 Mar 2025)<details><summary>[CVPR 2025] Xuanchen Li, Jianyu Wang, Yuhao Cheng, et al.</summary>
Yikun Zeng, Xingyu Ren, Wenhan Zhu, Weiming Zhao, Yichao Yan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.00495)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://xuanchenli.github.io/TexTalk/)
[![Code](https://img.shields.io/github/stars/XuanchenLi/TexTalk.svg?style=social&label=Star)](https://github.com/XuanchenLi/TexTalk)

+ **SayAnything: Audio-Driven Lip Synchronization with Conditional Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Feb 2025)<details><summary>Junxian Ma, Shiwen Wang, Jian Yang, et al.</summary>
Junyi Hu, Jian Liang, Guosheng Lin, Jingbo chen, Kai Li, Yu Meng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.11515)

+ **Long-Term TalkingFace Generation via Motion-Prior Conditional Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Feb 2025)<details><summary>Fei Shen, Cong Wang, Junyao Gao, et al.</summary>
Qin Guo, Jisheng Dang, Jinhui Tang, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.09533)


+ **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Feb 2025)<details><summary>Gaojie Lin, Jianwen Jiang, Jiaqi Yang, et al.</summary>
Zerong Zheng, Chao Liang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2502.01061)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://omnihuman-lab.github.io/)

+ **CyberHost: A One-stage Diffusion Framework for Audio-driven Talking Body Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (23 Jan 2025)<details><summary>[ICLR 2025] Gaojie Lin, Jianwen Jiang, Chao Liang, et al.</summary>
Tianyun Zhong, Jiaqi Yang, Yanbo Zheng</details>

  [![Paper](https://img.shields.io/badge/OpenReview-b31b1b.svg)](https://openreview.net/forum?id=vaEPihQsAA)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cyberhost.github.io/)

+ **Float: Generative Motion Latent Flow Matching for Audio-driven Talking Portrait** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Dec 2024)<details><summary>Taekyung Ki, Dongchan Min, Gyeongsu Chae</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.01064)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://deepbrainai-research.github.io/float/)
  [![Code](https://img.shields.io/github/stars/deepbrainai-research/float.svg?style=social&label=Star)](https://github.com/deepbrainai-research/float)

+ **SVP: Style-Enhanced Vivid Portrait Talking Head Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Nov 2024)<details><summary>Weipeng Tan, Chuming Lin, Chengming Xu, et al.</summary>
Xiaozhong Ji, Junwei Zhu, Chengjie Wang, Yunsheng Wu, Yanwei Fu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.03270)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://svportrait.github.io/)

+ **EchoMimicV2: Towards Striking, Simplified, and Semi-Body Human Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Nov 2024)<details><summary>[CVPR 2025] Rang Meng, Xingyu Zhang, Yuming Li, et al.</summary>
Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2411.10061)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://antgroup.github.io/ai/echomimic_v2/)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic_v2.svg?style=social&label=Star)](https://github.com/antgroup/echomimic_v2)

+ **VASA-1: Lifelike Audio-Driven Talking Faces Generated in Real Time** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (31 Oct 2024)<details><summary>[NeurIPS 2024] Sicheng Xu, Guojun Chen, Yu-Xiao Guo, et al.</summary>
Jiaolong Yang, Chong Li, Zhenyu Zang, Yizhong Zhang, Xin Tong, Baining Guo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.10667)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.microsoft.com/en-us/research/project/vasa-1/)


+ **MegActor-Σ: Unlocking Flexible Mixed-Modal Control in Portrait Animation with Diffusion Transformer** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Aug 2024)<details><summary>[AAAI 2025] Shurong Yang, Huadong Li, Juhao Wu, et al.</summary>
Minhao Jing, Linze Li, Renhe Ji, Jiajun Liang, Haoqiang Fan, Jin Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2408.14975)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/megvii-research/MegActor.svg?style=social&label=Star)](https://github.com/megvii-research/MegActor)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://f4c5-58-240-80-18.ngrok-free.app/)

+ **MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Aug 2024)<details><summary>Yuxuan Bian, Ailing Zeng, Xuan Ju, et al.</summary>Xian Liu, Zhaoyang Zhang, Wei Liu, Qiang Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2407.21136)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cure-lab.github.io/MotionCraft/)
  [![Code](https://img.shields.io/github/stars/cure-lab/MotionCraft.svg?style=social&label=Star)](https://github.com/cure-lab/MotionCraft)

+ **Dreamtalk: When Expressive Talking Head Generation Meets Diffusion Probabilistic Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Aug 2024)<details><summary>Yifeng Ma, Shiwei Zhang, Jiayu Wang, et al.</summary>Xiang Wang, Yingya Zhang, Zhidong Deng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.09767)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamtalk-project.github.io/)
  [![Code](https://img.shields.io/github/stars/ali-vilab/dreamtalk.svg?style=social&label=Star)](https://github.com/ali-vilab/dreamtalk)
+ **EchoMimic: Lifelike Audio-Driven Portrait Animations through Editable Landmark Conditions** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Jul 2024)<details><summary>[AAAI 2025] Zhiyuan Chen, Jiajiong Cao, Zhiquan Chen, et al.</summary>
Yuming Li, Chenguang Ma</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.08136)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://badtobest.github.io/echomimic.html)
[![Code](https://img.shields.io/github/stars/antgroup/echomimic.svg?style=social&label=Star)](https://github.com/antgroup/echomimic)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/BadToBest/EchoMimic)

+ **Hallo: Hierarchical Audio-Driven Visual Synthesis for Portrait Image Animation** (16 Jun 2024)<details><summary>Mingwang Xu, Hui Li, Qingkun Su, et al.</summary>Hanlin Shang, Liwei Zhang, Ce Liu, Jingdong Wang, Yao Yao, Siyu Zhu</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.08801)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fudan-generative-vision.github.io/hallo/#/)
[![Code](https://img.shields.io/github/stars/fudan-generative-vision/hallo.svg?style=social&label=Star)](https://github.com/fudan-generative-vision/hallo)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/fffiloni/tts-hallo-talking-portrait)

+ **V-Express: Conditional Dropout for Progressive Training of Portrait Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (4 Jun 2024)<details><summary>Cong Wang, Kuan Tian, Jun Zhang, et al.</summary>
Yonghang Guan, Feng Luo, Fei Shen, Zhiwei Jiang, Qing Gu, Xiao Han, Wei Yang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.02511)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tenvence.github.io/p/v-express/)
[![Code](https://img.shields.io/github/stars/tencent-ailab/V-Express.svg?style=social&label=Star)](https://github.com/tencent-ailab/V-Express)

+ **MOFA-Video: Controllable Image Animation via Generative Motion Field Adaptions in Frozen Image-to-Video Diffusion Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 May 2024) <details><summary>[ECCV 2024] Muyao Niu, Xiaodong Cun, Xintao Wang, et al.</summary>
Muyao Niu, Xiaodong Cun, Xintao Wang, Yong Zhang, Ying Shan, Yinqiang Zheng</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.20222)
[![Code](https://img.shields.io/github/stars/MyNiuuu/MOFA-Video.svg?style=social&label=Star)](https://github.com/MyNiuuu/MOFA-Video)

+ **InstructAvatar: Text-Guided Emotion and Motion Control for Avatar Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 May 2024)<details><summary>Yuchi Wang, Junliang Guo, Jianhong Bai, et al.</summary>
Runyi Yu, Tianyu He, Xu Tan, Xu Sun, Jiang Bian</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.15758)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wangyuchi369.github.io/InstructAvatar/)
+ **SyncTalk: The Devil is in the Synchronization for Talking Head Synthesis**  ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Apr 2024)<details><summary>[CVPR 2024] Ziqiao Peng, Wentao Hu, Yue Shi, et al.</summary>Xiangyu Zhu, Xiaomei Zhang, Hao Zhao, Jun He, Hongyan Liu, Zhaoxin Fan</details>
  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2311.17590)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ziqiaopeng.github.io/synctalk/)
  [![Code](https://img.shields.io/github/stars/ZiqiaoPeng/SyncTalk.svg?style=social&label=Star)](https://github.com/ZiqiaoPeng/SyncTalk)
+ **EDTalk: Efficient Disentanglement for Emotional Talking Head Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Apr 2024)<details><summary>Shuai Tan, Bin Ji, Mengxiao Bi, et al.</summary>
Ye Pan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.01647)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tanshuai0219.github.io/EDTalk/)
[![Code](https://img.shields.io/github/stars/tanshuai0219/EDTalk.svg?style=social&label=Star)](https://github.com/tanshuai0219/EDTalk)

+ **AniPortrait: Audio-Driven Synthesis of Photorealistic Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Mar 2024)<details><summary>Huawei Wei, Zejun Yang, Zhisheng Wang</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.17694)
[![Code](https://img.shields.io/github/stars/Zejun-Yang/AniPortrait.svg?style=social&label=Star)](https://github.com/Zejun-Yang/AniPortrait)
[![Demo](https://img.shields.io/badge/Demo-EEAD0E)](https://huggingface.co/spaces/ZJYang/AniPortrait_official)

+ **EMO: Emote Portrait Alive - Generating Expressive Portrait Videos with Audio2Video Diffusion Model under Weak Conditions** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (27 Feb 2024)<details><summary>[ECCV 2024] Linrui Tian, Qi Wang, Bang Zhang, et al.</summary>
Liefeng Bo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17485)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/EMO.svg?style=social&label=Star)](https://github.com/HumanAIGC/EMO)

+ **VividTalk: One-Shot Audio-Driven Talking Head Generation Based on 3D Hybrid Prior** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Dec 2023)<details><summary>Xusen Sun, Longhao Zhang, Hao Zhu, et al.</summary>Peng Zhang, Bang Zhang, Xinya Ji, Kangneng Zhou, Daiheng Gao, Liefeng Bo, Xun Cao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2312.01841)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://humanaigc.github.io/vivid-talk/)
  [![Code](https://img.shields.io/github/stars/HumanAIGC/VividTalk.svg?style=social&label=Star)](https://github.com/HumanAIGC/VividTalk)


+ **Audio-Driven Co-Speech Gesture Video Generation** (5 Dec 2022)<details><summary>[NeurIPS 2022] Xian Liu, Qianyi Wu, Hang Zhou, et al.</summary>Xian Liu, Qianyi Wu, Hang Zhou, Yuanqi Du, Wayne Wu, Dahua Lin, Ziwei Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.02350)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://alvinliu0.github.io/projects/ANGIE)
  [![Code](https://img.shields.io/github/stars/alvinliu0/ANGIE.svg?style=social&label=Star)](https://github.com/alvinliu0/ANGIE)

+ **A Lip Sync Expert Is All You Need for Speech to Lip Generation In The Wild**  (23 Aug 2020)<details><summary>K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, et al.</summary>[ACM MM 2020] K R Prajwal, Rudrabha Mukhopadhyay, Vinay Namboodiri, C V Jawahar</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2008.10010)
  [![Code](https://img.shields.io/github/stars/Rudrabha/Wav2Lip.svg?style=social&label=Star)](https://github.com/Rudrabha/Wav2Lip)

+ **Audio-driven Talking Face Video Generation with Learning-based Personalized Head Pose**  (5 Mar 2020)<details><summary>[TMM 2022] Ran Yi, Zipeng Ye, Juyong Zhang, et al.</summary>Ran Yi, Zipeng Ye, Juyong Zhang, Hujun Bao, Yong-Jin Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2002.10137)
  [![Code](https://img.shields.io/github/stars/yiranran/Audio-driven-TalkingFace-HeadPose.svg?style=social&label=Star)](https://github.com/yiranran/Audio-driven-TalkingFace-HeadPose)

+ **Robust One Shot Audio to Video Generation** (2020)<details><summary>[CVPRW 2020] Neeraj Kumar, Srishti Goel, Ankur Narang, et al.</summary>Neeraj Kumar, Srishti Goel, Ankur Narang, Mujtaba Hasan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content_CVPRW_2020/html/w45/Kumar_Robust_One_Shot_Audio_to_Video_Generation_CVPRW_2020_paper.html)



### 🎵 Sound-Guided
<a id="-sound-guided"></a>

<!-- RECENT_VERIFIED_START:Sound-Guided -->

+ **MACE-Dance: Motion-Appearance Cascaded Experts for Music-Driven Dance Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (20 Dec 2025)
  <details><summary>Kaixing Yang, Jiashu Zhu, Xulong Tang, et al.</summary>Kaixing Yang, Jiashu Zhu, Xulong Tang, Ziqiao Peng, Xiangyue Zhang, Puwei Wang, Jiahong Wu, Xiangxiang Chu, Hongyan Liu, Jun He</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.18181) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/AMAP-ML/MACE-Dance)

+ **YingVideo-MV: Music-Driven Multi-Stage Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Dec 2025)
  <details><summary>Jiahui Chen, Weida Wang, Runhua Shi, et al.</summary>Jiahui Chen, Weida Wang, Runhua Shi, Huan Yang, Chaofan Ding, Zihao Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.02492) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://giantailab.github.io/YingVideo-MV/)

+ **SpA2V: Harnessing Spatial Auditory Cues for Audio-driven Spatially-aware Video Generation** (1 Aug 2025)
  <details><summary>Kien T. Pham, Yingqing He, Yazhou Xing, et al.</summary>Kien T. Pham, Yingqing He, Yazhou Xing, Qifeng Chen, Long Chen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.00782) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/tkpham3105/SpA2V)

+ **ChoreoMuse: Robust Music-to-Dance Video Generation with Style Transfer and Beat-Adherent Motion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Jul 2025)
  <details><summary>Xuanchen Wang, Heng Wang, Weidong Cai</summary>Xuanchen Wang, Heng Wang, Weidong Cai</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.19836) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://choreomuse.github.io)

<!-- RECENT_VERIFIED_END:Sound-Guided -->

+ *MagicInfinite: Generating Infinite Talking Videos with Your Words and Voice**![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (7 Mar 2025) <details><summary>Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, et al.</summary> Hongwei Yi, Tian Ye, Shitong Shao, Xuancheng Yang, Jiantong Zhao, Hanzhong Guo, Terrance Wang, Qingyu Yin, Zeke Xie, Lei Zhu, Wei Li, Michael Lingelbach, Daquan Zhou</details> [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)]([https://arxiv.org/abs/2505.10238](https://arxiv.org/abs/2503.05978v1)) 

+ **MotionCraft: Crafting Whole-Body Motion with Plug-and-Play Multimodal Controls** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 Dec 2024)<details><summary>[AAAI 2025] Yuxuan Bian, Ailing Zeng, Xuan Ju, et al.</summary>
Yuxuan Bian, Ailing Zeng, Xuan Ju, Xian Liu, Zhaoyang Zhang, Wei Liu, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ojs.aaai.org/index.php/AAAI/article/view/32183)
[![Code](https://img.shields.io/github/stars/cure-lab/MotionCraft.svg?style=social&label=Star)](https://github.com/cure-lab/MotionCraft)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://cure-lab.github.io/MotionCraft/)

+ **AV-Link: Temporally-Aligned Diffusion Features for Cross-Modal Audio-Video Generation** (19 Dec 2024)<details><summary>Moayed Haji-Ali, Willi Menapace, Aliaksandr Siarohin, et al.</summary>
Moayed Haji-Ali, Willi Menapace, Aliaksandr Siarohin, Ivan Skorokhodov, Alper Canberk, Kwot Sin Lee, Vicente Ordonez, Sergey Tulyakov</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.16429)
[![Code](https://img.shields.io/github/stars/snap-research/AVLink.svg?style=social&label=Star)](https://github.com/snap-research/AVLink)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/AVLink/)


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


## 🧩 Other Controls

### 📝 Text Rendering
<a id="-text-rendering"></a>

+ **Wan: Open and Advanced Large-Scale Video Generative Models** (2025)<details><summary>WanTeam, Ang Wang, Baole Ai, et al.</summary>Bin Wen,Chaojie Mao,Chen-Wei Xie,Di Chen,Feiwu Yu,Haiming Zhao,Jianxiao Yang,Jianyuan Zeng,Jiayu Wang,Jingfeng Zhang,Jingren Zhou,Jinkai Wang,Jixuan Chen,Kai Zhu,Kang Zhao,Keyu Yan,Lianghua Huang,Mengyang Feng,Ningyi Zhang,Pandeng Li,Pingyu Wu,Ruihang Chu,Ruili Feng,Shiwei Zhang,Siyang Sun,Tao Fang,Tianxing Wang,Tianyi Gui,Tingyu Weng,Tong Shen,Wei Lin,Wei Wang~1,Wei Wang~2,Wenmeng Zhou,Wente Wang,Wenting Shen,Wenyuan Yu,Xianzhong Shi,Xiaoming Huang,Xin Xu,Yan Kou,Yangyu Lv,Yifei Li,Yijing Liu,Yiming Wang,Yingya Zhang,Yitong Huang,Yong Li,You Wu,Yu Liu,Yulin Pan,Yun Zheng,Yuntao Hong,Yupeng Shi,Yutong Feng,Zeyinzi Jiang,Zhen Han,Zhi-Fan Wu,Ziyu Liu</details></details>
[![Paper](https://img.shields.io/badge/Technical%20Report-b31b1b.svg)](https://files.alicdn.com/tpsservice/5c9de1c74de03972b7aa657e5a54756b.pdf)
[![Code](https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social&label=Star)](https://github.com/Wan-Video/Wan2.1)

+ **Text-Animator: Controllable Visual Text Video Generation** (25 Jun 2024)<details><summary>Lin Liu, Quande Liu, Shengju Qian, et al.</summary>Yuan Zhou, Wengang Zhou, Houqiang Li, Lingxi Xie, Qi Tian</details></details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.17777)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://laulampaul.github.io/text-animator)


### 🎨 Style-Guided
<a id="-style-guided"></a>

<!-- RECENT_VERIFIED_START:Style-Guided -->

+ **Lighting-grounded Video Generation with Renderer-based Agent Reasoning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Apr 2026)
  <details><summary>Ziqi Cai, Taoyu Yang, Zheng Chang, et al.</summary>Ziqi Cai, Taoyu Yang, Zheng Chang, Si Li, Han Jiang, Shuchen Weng, Boxin Shi</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.07966)

+ **LightCtrl: Training-free Controllable Video Relighting** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (28 Mar 2026)
  <details><summary>Yizuo Peng, Xuelin Chen, Kai Zhang, et al.</summary>Yizuo Peng, Xuelin Chen, Kai Zhang, Xiaodong Cun</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.27083) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/GVCLab/LightCtrl)

+ **DreamStyle: A Unified Framework for Video Stylization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (6 Jan 2026)
  <details><summary>Mengtian Li, Jinshu Chen, Songtao Zhao, et al.</summary>Mengtian Li, Jinshu Chen, Songtao Zhao, Wanquan Feng, Pengqi Tu, Qian He</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.02785) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://lemonsky1995.github.io/dreamstyle)

+ **DiTalker: A Unified DiT-based Framework for High-Quality and Speaking Styles Controllable Portrait Animation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (29 Jul 2025)
  <details><summary>He Feng, Yongjia Ma, Donglin Di, et al.</summary>He Feng, Yongjia Ma, Donglin Di, Lei Fan, Tonghua Su, Xiangqian Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.06511)

+ **Think-Before-Draw: Decomposing Emotion Semantics & Fine-Grained Controllable Expressive Talking Head Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (17 Jul 2025)
  <details><summary>Hanlei Shi, Leyuan Qu, Yu Liu, et al.</summary>Hanlei Shi, Leyuan Qu, Yu Liu, Di Gao, Yuhua Zheng, Taihao Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.12761)

<!-- RECENT_VERIFIED_END:Style-Guided -->

+ **Frame Guidance: Training-Free Guidance for Frame-Level Control in Video Diffusion Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jun 2025)
   <details><summary>Sangwon Jang, Taekyung Ki, Jaehyeong Jo, et al.</summary>  
         Sangwon Jang, Taekyung Ki, Jaehyeong Jo, Jaehong Yoon, Soo Ye Kim, Zhe Lin, Sung Ju Hwang</details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2506.07177)
   [![Code](https://img.shields.io/github/stars/agwmon/frame-guidance.svg?style=social&label=Star)](https://github.com/agwmon/frame-guidance)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://frame-guidance-video.github.io/)
  
+ **OmniVDiff: Omni Controllable Video Diffusion for Generation and Understanding** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Apr 2025)<details><summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, et al.</summary>
Xi Qiu, Yuchi Huo, Rui Wang, Chi Zhang, Xuelong Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2504.10825)
[![Code](https://img.shields.io/github/stars/Tele-AI/OmniVDiff.svg?style=social&label=Star)](https://github.com/Tele-AI/OmniVDiff.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tele-ai.github.io/OmniVDiff/)

+ **StyleMaster: Stylize Your Video with Artistic Generation and Translation** (10 Dec 2024)<details><summary>Zixuan Ye, Huijuan Huang, Xintao Wang, et al.</summary>
Pengfei Wan, Di Zhang, Wenhan Luo</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.07744)
[![Code](https://img.shields.io/github/stars/KwaiVGI/StyleMaster.svg?style=social&label=Star)](https://github.com/KwaiVGI/StyleMaster.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zixuan-ye.github.io/stylemaster/)

+ **FRESCO: Spatial-Temporal Correspondence for Zero-Shot Video Translation** (19 Mar 2024)<details><summary>[CVPR 2024] Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.12962)
[![Code](https://img.shields.io/github/stars/williamyang1991/FRESCO.svg?style=social&label=Star)](https://github.com/williamyang1991/FRESCO.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/fresco/)

+ **StyleCrafter: Enhancing Stylized Text-to-Video Generation with Style Adapter** (1 Dec 2023)<details><summary>[TOG 2024] Gongye Liu, Menghan Xia, Yong Zhang, et al.</summary>
Haoxin Chen, Jinbo Xing, Yibo Wang, Xintao Wang, Yujiu Yang, Ying Shan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.00330)
[![Code](https://img.shields.io/github/stars/GongyeLiu/StyleCrafter.svg?style=social&label=Star)](https://github.com/GongyeLiu/StyleCrafter.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://gongyeliu.github.io/StyleCrafter.github.io/)

+ **UniVST: A Unified Framework for Training-free Localized Video Style Transfer** (26 Oct 2024)<details><summary>Quanjian Song, Mingbao Lin, Wengyi Zhan, et al.</summary>
Shuicheng Yan, Liujuan Cao, Rongrong Ji</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.20084)
[![Code](https://img.shields.io/github/stars/QuanjianSong/UniVST.svg?style=social&label=Star)](https://github.com/QuanjianSong/UniVST)

+ **Rerender A Video: Zero-Shot Text-Guided Video-to-Video Translation** (13 Jun 2023)<details><summary>[Siggraph Asia 2023] Shuai Yang, Yifan Zhou, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07954)
[![Code](https://img.shields.io/github/stars/williamyang1991/Rerender_A_Video.svg?style=social&label=Star)](https://github.com/williamyang1991/Rerender_A_Video.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/rerender/)

+ **VToonify: Controllable High-Resolution Portrait Video Style Transfer** (22 Sep 2022)<details><summary>[Siggraph Asia 2022] Shuai Yang, Liming Jiang, Ziwei Liu, et al.</summary>
Chen Change Loy</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.11224)
[![Code](https://img.shields.io/github/stars/williamyang1991/VToonify.svg?style=social&label=Star)](https://github.com/williamyang1991/VToonify.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://www.mmlab-ntu.com/project/vtoonify/)


### 📌 Point-Guided
<a id="-point-guided"></a>

<!-- RECENT_VERIFIED_START:Point-Guided -->

+ **Go-with-the-Track: Video Compositing and Motion Control with Point Tracking** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Jun 2026)
  <details><summary>Koichi Namekata, Yash Kant, Zhizheng Liu, et al.</summary>Koichi Namekata, Yash Kant, Zhizheng Liu, Ryan D Burgert, Yuancheng Xu, Kuan Heng Lin, Emmett Steven, Julien Philip, Li Ma, Andrea Vedaldi, Paul Debevec, Ning Yu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.20891) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://eyeline-labs.github.io/Go-with-the-Track/)

+ **HVG-3D: Bridging Real and Simulation Domains for 3D-Conditional Hand-Object Interaction Video Synthesis** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (31 Mar 2026)
  <details><summary>Mingjin Chen, Junhao Chen, Zhaoxin Fan, et al.</summary>Mingjin Chen, Junhao Chen, Zhaoxin Fan, Yujian Lee, Zichen Dang, Lili Wang, Yawen Cui, Lap-Pui Chau, Yi Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.03305) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hvg3d.github.io)

+ **In-Video Instructions: Visual Signals as Generative Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (24 Nov 2025)
  <details><summary>Gongfan Fang, Xinyin Ma, Xinchao Wang</summary>Gongfan Fang, Xinyin Ma, Xinchao Wang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.19401) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fangggf.github.io/In-Video/)

<!-- RECENT_VERIFIED_END:Point-Guided -->

+ **Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control** (7 Jan 2025)<details><summary>Zekai Gu, Rui Yan, Jiahao Lu, Peng Li, et al.</summary>
Zhiyang Dou, Chenyang Si, Zhen Dong, Qifeng Liu, Cheng Lin, Ziwei Liu, Wenping Wang, Yuan Liu </details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.03847)
[![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Star)](https://github.com/IGL-HKUST/DiffusionAsShader.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://igl-hkust.github.io/das/)

+ **GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking** (5 Jan 2025)<details><summary>Weikang Bian, Zhaoyang Huang, Xiaoyu Shi, et al.</summary>
Yijin Li, Fu-Yun Wang, Hongsheng Li</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2501.02690)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://wkbian.github.io/Projects/GS-DiT/)


+ **Track4Gen: Teaching Video Diffusion Models to Track Points Improves Video Generation** (8 Dec 2024)<details><summary>[CVPR 2025] Hyeonho Jeong, Chun-Hao Paul Huang, et al.</summary>
Jong Chul Ye, Niloy Mitra, Duygu Ceylan</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.06016)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://hyeonho99.github.io/track4gen/)


- **This&That: Language-Gesture Controlled Video Generation for Robot Planning** (8 Jul 2024)
  <details><summary>Boyang Wang, Nikhil Sridhar, Chao Feng, et al.</summary> Boyang Wang, Nikhil Sridhar, Chao Feng, Mark Van der Merwe, Adam Fishman, Nima Fazeli, Jeong Joon Park</details>  

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.05530)   [![Code](https://img.shields.io/github/stars/Kiteretsu77/This_and_That_VDM.svg?style=social&label=Star)](https://github.com/Kiteretsu77/This_and_That_VDM) [![Project](https://img.shields.io/badge/Project_Page-00CED1)](https://cfeng16.github.io/this-and-that/)


+ **Drag-A-Video: Non-rigid Video Editing with Point-based Interaction** (5 Dec 2023)<details><summary>Yao Teng, Enze Xie, Yue Wu, Haoyu Han, et al.</summary>
Zhenguo Li, Xihui Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.02936)
[![Code](https://img.shields.io/github/stars/tyshiwo1/drag-a-video.svg?style=social&label=Star)](https://github.com/tyshiwo1/drag-a-video.git)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://drag-a-video.github.io/)

### 🗺️ BEV-Guided
<a id="-bev-guided"></a>

<!-- RECENT_VERIFIED_START:BEV-Guided -->

+ **X-World: Controllable Ego-Centric Multi-Camera World Models for Scalable End-to-End Driving** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (20 Mar 2026)
  <details><summary>Chaoda Zheng, Sean Li, Jinhao Deng, et al.</summary>Chaoda Zheng, Sean Li, Jinhao Deng, Zhennan Wang, Shijia Chen, Liqiang Xiao, Ziheng Chi, Hongbin Lin, Kangjie Chen, Boyang Wang, Yu Zhang, Xianming Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.19979) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://x-world-1.github.io)

+ **ConsisDrive: Identity-Preserving Driving World Models for Video Generation by Instance Mask** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Feb 2026)
  <details><summary>Zhuoran Yang, Yanyong Zhang</summary>Zhuoran Yang, Yanyong Zhang</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.03213) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://shanpoyang654.github.io/ConsisDrive/page.html)

+ **GenieDrive: Towards Physics-Aware Driving World Model with 4D Occupancy Guided Video Generation** (14 Dec 2025)
  <details><summary>Zhenya Yang, Zhe Liu, Yuxiang Lu, et al.</summary>Zhenya Yang, Zhe Liu, Yuxiang Lu, Liping Hou, Chenxuan Miao, Siyi Peng, Bailan Feng, Xiang Bai, Hengshuang Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.12751)

<!-- RECENT_VERIFIED_END:BEV-Guided -->

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

## 🧰 Survey-aligned Supporting Resources (C3)

<!-- RECENT_VERIFIED_START:Supporting C3 -->

+ **Autonomous Video Generation with Counterfactual Controllability for Self-Evolving World Models** (23 Jun 2026)
  <details><summary>Xin Wang, Wenxuan Liu, Tongtong Feng, et al.</summary>Xin Wang, Wenxuan Liu, Tongtong Feng, Wenwu Zhu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.24152)

+ **EduStory: A Unified Framework for Pedagogically-Consistent Multi-Shot STEM Instructional Video Generation** (10 May 2026)
  <details><summary>Xinyi Wu, Jayant Teotia, Shuai Zhao, et al.</summary>Xinyi Wu, Jayant Teotia, Shuai Zhao, Erik Cambria</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.09378)

<!-- RECENT_VERIFIED_END:Supporting C3 -->

<a id="-survey-aligned-supporting-resources-c3"></a>

This section contains datasets, benchmarks, analyses, and user/inference tools admitted by survey criterion C3 but not forced into an input-modality category.

## 🌀 Universal Control

<!-- RECENT_VERIFIED_START:Universal Control -->

+ **World Narrative Model for Highly Controllable Video Generation: A Paradigm Shift from Pixel Sampling to Physical World Orchestration** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (30 Jun 2026)
  <details><summary>Ye Chen, Xuanhong Chen, Yupeng Zhu, et al.</summary>Ye Chen, Xuanhong Chen, Yupeng Zhu, Liming Tan, Zhewen Wan, Yuxuan Xiong, Tielong Wang, Jinfan Liu, Wuze Zhang, Xiongzhen Zhang, Feifei Li, Xianglin Luo, Zhehan Zhao, Zhifan Zhang, Laisheng Kou, Zhujin Liang, Yugang Chen, Muchun Chen, Xu Miao, Yijing Zhang, Xiaojie Sheng, Qiang Hu, Jialiang Chen, Weimin Zhang, Wenjun Zhang, Bingbing Ni</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.31946) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://glassroom.sjtu.edu.cn/WNM/)

+ **Disco-LoRA: Disentangled Composition of Content, Style, and Motion for Multi-concept Video Customization** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Jun 2026)
  <details><summary>Xuancheng Xu, Gengyun Jia, Bing-Kun Bao</summary>Xuancheng Xu, Gengyun Jia, Bing-Kun Bao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.26668) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://discolora.github.io/)

+ **CineOrchestra: Unified Entity-Centric Conditioning for Cinematic Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Jun 2026)
  <details><summary>Sharath Girish, Tsai-Shien Chen, Zhikang Dong, et al.</summary>Sharath Girish, Tsai-Shien Chen, Zhikang Dong, Mukesh Singhal, Hao Chen, Sergey Tulyakov, Aliaksandr Siarohin</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2606.13768) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snap-research.github.io/CineOrchestra)

+ **CogOmniControl: Reasoning-Driven Controllable Video Generation via Creative Intent Cognition** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (19 May 2026)
  <details><summary>Hongji Yang, Songlian Li, Yucheng Zhou, et al.</summary>Hongji Yang, Songlian Li, Yucheng Zhou, Xiaotong Zhao, Alan Zhao, Chengzhong Xu, Jianbing Shen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2605.19995) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://um-lab.github.io/CogOmniControl/)

+ **MMControl: Unified Multi-Modal Control for Joint Audio-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (21 Apr 2026)
  <details><summary>Liyang Li, Wen Wang, Canyu Zhao, et al.</summary>Liyang Li, Wen Wang, Canyu Zhao, Tianjian Feng, Zhiyue Zhao, Hao Chen, Chunhua Shen</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.19679) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aim-uofa.github.io/MMControl/)

+ **OmniShow: Unifying Multimodal Conditions for Human-Object Interaction Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Apr 2026)
  <details><summary>Donghao Zhou, Guisheng Liu, Hao Yang, et al.</summary>Donghao Zhou, Guisheng Liu, Hao Yang, Jiatong Li, Jingyu Lin, Xiaohu Huang, Yichen Liu, Xin Gao, Cunjian Chen, Shilei Wen, Chi-Wing Fu, Pheng-Ann Heng</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.11804) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://correr-zhou.github.io/OmniShow/)

+ **Control-DINO: Feature Space Conditioning for Controllable Image-to-Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Apr 2026)
  <details><summary>Edoardo A. Dominici, Thomas Deixelberger, Konstantinos Vardis, et al.</summary>Edoardo A. Dominici, Thomas Deixelberger, Konstantinos Vardis, Markus Steinberger</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2604.01761) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dedoardo.github.io/projects/control-dino/)

+ **Tri-Prompting: Video Diffusion with Unified Control over Scene, Subject, and Motion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (16 Mar 2026)
  <details><summary>Zhenghong Zhou, Xiaohang Zhan, Zhiqin Chen, et al.</summary>Zhenghong Zhou, Xiaohang Zhan, Zhiqin Chen, Soo Ye Kim, Nanxuan Zhao, Haitian Zheng, Qing Liu, He Zhang, Zhe Lin, Yuqian Zhou, Jiebo Luo</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.15614) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://zhouzhenghong-gt.github.io/Tri-Prompting-Page/)

+ **DreamVideo-Omni: Omni-Motion Controlled Multi-Subject Video Customization with Latent Identity Reinforcement Learning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Mar 2026)
  <details><summary>Yujie Wei, Xinyu Liu, Shiwei Zhang, et al.</summary>Yujie Wei, Xinyu Liu, Shiwei Zhang, Hangjie Yuan, Jinbo Xing, Zhekai Chen, Xiang Wang, Haonan Qiu, Rui Zhao, Yutong Feng, Ruihang Chu, Yingya Zhang, Yike Guo, Xihui Liu, Hongming Shan</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.12257) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://dreamvideo-omni.github.io)

+ **Video2LoRA: Unified Semantic-Controlled Video Generation via Per-Reference-Video LoRA** (9 Mar 2026)
  <details><summary>Zexi Wu, Baolu Li, Jing Dai, et al.</summary>Zexi Wu, Baolu Li, Jing Dai, Yiming Zhang, Yue Ma, Qinghe Wang, Xu Jia, Hongming Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2603.08210) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/BerserkerVV/Video2LoRA)

+ **FlexAM: Flexible Appearance-Motion Decomposition for Versatile Video Generation Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (13 Feb 2026)
  <details><summary>Mingzhi Sheng, Zekai Gu, Peng Li, et al.</summary>Mingzhi Sheng, Zekai Gu, Peng Li, Cheng Lin, Hao-Xiang Guo, Ying-Cong Chen, Yuan Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.13185) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/IGL-HKUST/FlexAM)

+ **DreamID-Omni: Unified Framework for Controllable Human-Centric Audio-Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (12 Feb 2026)
  <details><summary>Xu Guo, Fulong Ye, Qichao Sun, et al.</summary>Xu Guo, Fulong Ye, Qichao Sun, Liyang Chen, Bingchuan Li, Pengze Zhang, Jiawei Liu, Songtao Zhao, Qian He, Xiangwang Hou</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.12160) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://guoxu1233.github.io/DreamID-Omni/)

+ **Tele-Omni: a Unified Multimodal Framework for Video Generation and Editing** (10 Feb 2026)
  <details><summary>Jialun Liu, Tian Li, Xiao Cao, et al.</summary>Jialun Liu, Tian Li, Xiao Cao, Yukuo Ma, Gonghu Shang, Haibin Huang, Chi Zhang, Xiangzhen Chang, Zhiyong Huang, Jiakui Hu, Zuoxin Li, Yuanzhi Liang, Cong Liu, Junqi Liu, Robby T. Tan, Haitong Tang, Qizhen Weng, Yifan Xu, Liying Yang, Xiaoyan Yang, Peng Yu, Shiwen Zhang, Xuelong Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2602.09609)

+ **VerseCrafter: Dynamic Realistic Video World Model with 4D Geometric Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Jan 2026)
  <details><summary>Sixiao Zheng, Minghao Yin, Wenbo Hu, et al.</summary>Sixiao Zheng, Minghao Yin, Wenbo Hu, Xiaoyu Li, Ying Shan, Yanwei Fu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2601.05138) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sixiaozheng.github.io/VerseCrafter_page)

+ **CustomX: Unified Character, Action, and Scene Customization in Video World Models** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (18 Dec 2025)
  <details><summary>Yitong Wang, Fangyun Wei, Hongyang Zhang, et al.</summary>Yitong Wang, Fangyun Wei, Hongyang Zhang, Bo Dai, Yan Lu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.17796) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://snowflakewang.github.io/CustomX_Page/)

+ **LongVie 2: Multimodal Controllable Ultra-Long Video World Model** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (15 Dec 2025)
  <details><summary>Jianxiong Gao, Zhaoxi Chen, Xian Liu, et al.</summary>Jianxiong Gao, Zhaoxi Chen, Xian Liu, Junhao Zhuang, Chengming Xu, Jianfeng Feng, Yu Qiao, Yanwei Fu, Chenyang Si, Ziwei Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.13604) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://vchitect.github.io/LongVie2-project/)

+ **UnityVideo: Unified Multi-Modal Multi-Task Learning for Enhancing World-Aware Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (8 Dec 2025)
  <details><summary>Jiehui Huang, Yuechen Zhang, Xu He, et al.</summary>Jiehui Huang, Yuechen Zhang, Xu He, Yuan Gao, Zhi Cen, Bin Xia, Yan Zhou, Xin Tao, Pengfei Wan, Jiaya Jia</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.07831) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/dvlab-research/UnityVideo)

+ **MultiShotMaster: A Controllable Multi-Shot Video Generation Framework** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Dec 2025)
  <details><summary>Qinghe Wang, Xiaoyu Shi, Baolu Li, et al.</summary>Qinghe Wang, Xiaoyu Shi, Baolu Li, Weikang Bian, Quande Liu, Huchuan Lu, Xintao Wang, Pengfei Wan, Kun Gai, Xu Jia</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.03041) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://qinghew.github.io/MultiShotMaster)

+ **OmniPerson: Unified Identity-Preserving Pedestrian Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (2 Dec 2025)
  <details><summary>Changxiao Ma, Chao Yuan, Xincheng Shi, et al.</summary>Changxiao Ma, Chao Yuan, Xincheng Shi, Yuzhuo Ma, Yongfei Zhang, Longkun Zhou, Yujia Zhang, Shangze Li, Yifan Xu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2512.02554) [![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github)](https://github.com/maxiaoxsi/OmniPerson)

+ **CtrlVDiff: Controllable Video Generation via Unified Multimodal Video Diffusion** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (26 Nov 2025)
  <details><summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, et al.</summary>Dianbing Xi, Jiepeng Wang, Yuanzhi Liang, Xi Qiu, Jialun Liu, Hao Pan, Yuchi Huo, Rui Wang, Haibin Huang, Chi Zhang, Xuelong Li</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.21129) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://tele-ai.github.io/CtrlVDiff/)

+ **A Reason-then-Describe Instruction Interpreter for Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (25 Nov 2025)
  <details><summary>Shengqiong Wu, Weicai Ye, Yuanxing Zhang, et al.</summary>Shengqiong Wu, Weicai Ye, Yuanxing Zhang, Jiahao Wang, Quande Liu, Xintao Wang, Pengfei Wan, Kun Gai, Hao Fei, Tat-Seng Chua</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2511.20563) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sqwu.top/ReaDe/)

+ **MultiCOIN: Multi-Modal COntrollable Video INbetweening** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Oct 2025)
  <details><summary>Maham Tanveer, Yang Zhou, Simon Niklaus, et al.</summary>Maham Tanveer, Yang Zhou, Simon Niklaus, Ali Mahdavi Amiri, Hao Zhang, Krishna Kumar Singh, Nanxuan Zhao</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.08561)

+ **Ctrl-VI: Controllable Video Synthesis via Variational Inference** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (9 Oct 2025)
  <details><summary>Haoyi Duan, Yunzhi Zhang, Yilun Du, et al.</summary>Haoyi Duan, Yunzhi Zhang, Yilun Du, Jiajun Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2510.07670) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://video-synthesis-variational.github.io/)

+ **HuMo: Human-Centric Video Generation via Collaborative Multi-Modal Conditioning** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (10 Sep 2025)
  <details><summary>Liyang Chen, Tianxiang Ma, Jiawei Liu, et al.</summary>Liyang Chen, Tianxiang Ma, Jiawei Liu, Bingchuan Li, Zhuowei Chen, Lijie Liu, Xu He, Gen Li, Qian He, Zhiyong Wu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2509.08519) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://phantom-video.github.io/HuMo)

+ **Omni-Effects: Unified and Spatially-Controllable Visual Effects Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (11 Aug 2025)
  <details><summary>Fangyuan Mao, Aiming Hao, Jintao Chen, et al.</summary>Fangyuan Mao, Aiming Hao, Jintao Chen, Dongxia Liu, Xiaokun Feng, Jiashu Zhu, Meiqi Wu, Chubin Chen, Jiahong Wu, Xiangxiang Chu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.07981)

+ **LongVie: Multimodal-Guided Controllable Ultra-Long Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (5 Aug 2025)
  <details><summary>Jianxiong Gao, Zhaoxi Chen, Xian Liu, et al.</summary>Jianxiong Gao, Zhaoxi Chen, Xian Liu, Jianfeng Feng, Chenyang Si, Yanwei Fu, Yu Qiao, Ziwei Liu</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2508.03694)

+ **AnyI2V: Animating Any Conditional Image with Motion Control** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17) (3 Jul 2025)
  <details><summary>Ziye Li, Hao Luo, Xincheng Shuai, et al.</summary>Ziye Li, Hao Luo, Xincheng Shuai, Henghui Ding</details>

  [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2507.02857) [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://henghuiding.com/AnyI2V/)

<!-- RECENT_VERIFIED_END:Universal Control -->

<a id="-universal-control"></a>

+ **Aether: Geometric-Aware Unified World Modeling** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)  (18 Mar 2025)
   <details><summary>Aether Team, et al.</summary>  
        Haoyi Zhu, Yifan Wang, Jianjun Zhou, Wenzheng Chang, Yang Zhou, Zizun Li, Junyi Chen, Chunhua Shen, Jiangmiao Pang, Tong He </details>  

   [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.18945)
   [![GitHub](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Star)](https://github.com/OpenRobotLab/Aether)
   [![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://aether-world.github.io/)
+ **VACE: All-in-One Video Creation and Editing** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)  (11 Mar 2025)<details><summary>Zeyinzi Jiang, Zhen Han, Chaojie Mao, et al.</summary>Zeyinzi Jiang, Zhen Han, Chaojie Mao, Jingfeng Zhang, Yulin Pan, Yu Liu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.07598)
[![Code](https://img.shields.io/github/stars/ali-vilab/VACE.svg?style=social&label=Star)](https://github.com/ali-vilab/VACE)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://ali-vilab.github.io/VACE-Page/)

+ **FullDiT: Multi-Task Video Generative Foundation Model with Full Attention** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)  (25 Mar 2025)<details><summary>Xuan Ju, Weicai Ye, Quande Liu, et al.</summary>Xuan Ju, Weicai Ye, Quande Liu, Qiulin Wang, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Qiang Xu</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/html/2503.19907v1)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://fulldit.github.io/)
+ **Any2Caption:Interpreting Any Condition to Caption for Controllable Video Generation** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)  (31 Mar 2025)<details><summary>Shengqiong Wu, Weicai Ye, Jiahao Wang, et al.</summary>Shengqiong Wu, Weicai Ye, Jiahao Wang, Quande Liu, Xintao Wang, Pengfei Wan, Di Zhang, Kun Gai, Shuicheng Yan, Hao Fei, Tat-Seng Chua</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2503.24379) 
[![Code](https://img.shields.io/github/stars/ChocoWu/Any2Caption.svg?style=social&label=Star)](https://github.com/ChocoWu/Any2Caption)
[![Project_Page](https://img.shields.io/badge/Project_Page-00CED1)](https://sqwu.top/Any2Cap/)




+ **VideoComposer: Compositional Video Synthesis with Motion Controllability** ![M](https://github-colored-text-fn3z.vercel.app/api/index?text=[M]&color=008000&width=30&fontSize=17&height=17)  (6 Jun 2023)<details><summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, et al.</summary>Xiang Wang, Hangjie Yuan, Shiwei Zhang, Dayou Chen, Jiuniu Wang, Yingya Zhang, Yujun Shen, Deli Zhao, Jingren Zhou</details>
[![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.02018)
[![Code](https://img.shields.io/github/stars/ali-vilab/videocomposer.svg?style=social&label=Star)](https://github.com/ali-vilab/videocomposer)


