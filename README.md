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
          + **StableAnimator: High-Quality Identity-Preserving Human Image Animation**
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          
          
          + **AnimateAnywhere: Context-Controllable Human Video Generation with ID-Consistent One-shot Learning**
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          
          
          + **AnchorCrafter: Animate CyberAnchors Saling Your Products via Human-Object Interacting Video Generation**
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          
          
          + **OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models**
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          
          
          + **Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation**
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          
          
          + **Champ: Controllable and Consistent Human Image Animation with 3D Parametric Guidance** (21 Mar 2024)
          <details><summary>Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, et al.</summary>
          Shenhao Zhu, Junming Leo Chen, Zuozhuo Dai, Qingkun Su, Yinghui Xu, Xun Cao, Yao Yao, Hao Zhu, Siyu Zhu</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2403.14781v2-b31b1b.svg)](https://arxiv.org/abs/2403.14781v2)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2403.14781v2)
          
          
          + **TCAN: Animating Human Images with Temporally Consistent Pose Guidance using Diffusion Models** (12 Jul 2024)
          <details><summary>Jeongho Kim, Min-Jung Kim, Junsoo Lee, et al.</summary>
          Jeongho Kim, Min-Jung Kim, Junsoo Lee, Jaegul Choo</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2407.09012v1-b31b1b.svg)](https://arxiv.org/abs/2407.09012v1)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2407.09012v1)
          
          
          + **VividPose: Advancing Stable Video Diffusion for Realistic Human Image Animation** (28 May 2024)
          <details><summary>Qilin Wang, Zhengkai Jiang, Chengming Xu, et al.</summary>
          Qilin Wang, Zhengkai Jiang, Chengming Xu, Jiangning Zhang, Yabiao Wang, Xinyi Zhang, Yun Cao, Weijian Cao, Chengjie Wang, Yanwei Fu</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2405.18156v1-b31b1b.svg)](https://arxiv.org/abs/2405.18156v1)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2405.18156v1)
          
          
          + **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion**
            ⚠️ 未找到arXiv信息
          
          
          + **DISCO: Disentangled Control for Realistic Human Dance Generation** (30 Jun 2023)
          <details><summary>Tan Wang, Linjie Li, Kevin Lin, et al.</summary>
          Tan Wang, Linjie Li, Kevin Lin, Yuanhao Zhai, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2307.00040v3-b31b1b.svg)](https://arxiv.org/abs/2307.00040v3)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2307.00040v3)
          
          
          + **MimicMotion: High-Quality Human Motion Video Generation with Confidence-aware Pose Guidance**
            ⚠️ 未找到arXiv信息
          
          
          + **PoseCrafter: One-Shot Personalized Video Synthesis Following Flexible Pose Control**
            ⚠️ 未找到arXiv信息
          
          
          + **Follow-Your-Pose v2: Multiple-Condition Guided Character Image Animation for Stable Pose Control**
            ⚠️ 未找到arXiv信息
          
          
          + **UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation** (03 Jun 2024)
          <details><summary>Xiang Wang, Shiwei Zhang, Changxin Gao, et al.</summary>
          Xiang Wang, Shiwei Zhang, Changxin Gao, Jiayu Wang, Xiaoqiang Zhou, Yingya Zhang, Luxin Yan, Nong Sang</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2406.01188v1-b31b1b.svg)](https://arxiv.org/abs/2406.01188v1)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2406.01188v1)
          
          
          + **Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation** (26 May 2024)
          <details><summary>Jinlin Liu, Kai Yu, Mengyang Feng, et al.</summary>
          Jinlin Liu, Kai Yu, Mengyang Feng, Xiefan Guo, Miaomiao Cui</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2405.16393v2-b31b1b.svg)](https://arxiv.org/abs/2405.16393v2)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2405.16393v2)
          
          
          + **Zero-shot High-fidelity and Pose-controllable Character Animation**
            ⚠️ 未找到arXiv信息
          
          
          + **MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model** (27 Nov 2023)
          <details><summary>Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, et al.</summary>
          Zhongcong Xu, Jianfeng Zhang, Jun Hao Liew, Hanshu Yan, Jia-Wei Liu, Chenxu Zhang, Jiashi Feng, Mike Zheng Shou</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2311.16498v1-b31b1b.svg)](https://arxiv.org/abs/2311.16498v1)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2311.16498v1)
          
          
          + **DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion**
            ⚠️ 未找到arXiv信息
          
          
          + **DreaMoving: A Human Video Generation Framework based on Diffusion Models** (08 Dec 2023)
          <details><summary>Mengyang Feng, Jinlin Liu, Kai Yu, et al.</summary>
          Mengyang Feng, Jinlin Liu, Kai Yu, Yuan Yao, Zheng Hui, Xiefan Guo, Xianhui Lin, Haolan Xue, Chen Shi, Xiaowen Li, Aojie Li, Xiaoyang Kang, Biwen Lei, Miaomiao Cui, Peiran Ren, Xuansong Xie</details>
          
          [![Paper](https://img.shields.io/badge/arXiv-2312.05107v2-b31b1b.svg)](https://arxiv.org/abs/2312.05107v2)
          [![citation](https://img.shields.io/badge/citation-0-blue.svg)](https://www.semanticscholar.org/search?q=2312.05107v2)
          
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

### ✍️ + 🔊 Text + Sound

### 🌟 + 🎥 Personalized + Motion

## ❓ To be sorted

## 🌐 Unified controllable generation
