# Awesome Papers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 

## ✨ About

This repo contains a curated list of **Computer Vision papers** and **Robotics** , inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) and [Awesome-Robotics-3D
](https://github.com/zubair-irshad/Awesome-Robotics-3D)

If you find this repository useful, please consider **STARing** ⭐ this repository.

> **Note**: This repository is under active development. If you have any suggestions or want to contribute, feel free to open an issue or a pull request.

**Disclaimer**: This repository is not meant to be a comprehensive list of all computer vision but rather a curated list of papers that I find interesting. I have left out many fundamental papers and focused on the more recent and interesting ones. If you are looking for a comprehensive list of papers, I think the above-mentioned repositories and other resources are a better fit!

## 📚 Table of Contents
- [Awesome Papers   ](#awesome-papers---)
  - [✨ About](#-about)
  - [📚 Table of Contents](#-table-of-contents)
  - [Awesome Computer Vision Papers](#awesome-computer-vision-papers)
    - [Matching](#matching)
    - [3D Gaussians and its Variants](#3d-gaussians-and-its-variants)
    - [Human Pose Tracking / Human Pose Estimation](#human-pose-tracking--human-pose-estimation)
    - [RAFT](#raft)
    - [4D Reconstruction](#4d-reconstruction)
      - [Monocular Dynamic Reconstruction](#monocular-dynamic-reconstruction)
    - [Robust, Calibration-free Reconstruction](#robust-calibration-free-reconstruction)
    - [VLLM](#vllm)
    - [Generative Models](#generative-models)
    - [3D Data Synthesis](#3d-data-synthesis)
  - [Awesome Robotics Papers](#awesome-robotics-papers)
    - [Vision-Language-Action Models](#vision-language-action-models)
    - [Sim2Real/Real2Sim](#sim2realreal2sim)

## Awesome Computer Vision Papers

### Matching

* **Efficient LoFTR**: "Efficient LoFTR: Semi-Dense Local Feature Matching with Sparse-Like Speed", *CVPR 2024*. [[Paper](https://zju3dv.github.io/efficientloftr/files/EfficientLoFTR.pdf)] [[Webpage](https://zju3dv.github.io/efficientloftr/)][[Code](https://github.com/zju3dv/efficientloftr)]

* **RoMa**: "RoMa: Robust Dense Feature Matching", *CVPR 2024*. [[Paper](https://arxiv.org/abs/2305.15404)] [[Webpage](https://parskatt.github.io/RoMa/)] [[Code](https://github.com/Parskatt/RoMa)]

* **MatchAnything**: "MatchAnything: Universal Cross-Modality Image Matching with Large-Scale Pre-Training", *arXiv Jan 2025*. [[Paper](https://arxiv.org/abs/2501.07556)] [[Webpage](https://zju3dv.github.io/MatchAnything/)] [[Code](https://github.com/zju3dv/MatchAnything)]

------------------------------

### 3D Gaussians and its Variants

**[`Compressing` 3D Gaussians]**

* **[Survey]** : 3DGS.zip: A survey on 3D Gaussian Splatting Compression Methods [[Webpage](https://w-m.github.io/3dgs-compression-survey/)]

------------------------------

### Human Pose Tracking / Human Pose Estimation

* **HuMoR**: 3D Human Motion Model for Robust Pose Estimation, *ICCV 21*. [[Paper](https://geometry.stanford.edu/projects/humor/docs/humor.pdf)] [[Webpage](https://geometry.stanford.edu/projects/humor/)] [[Code](https://github.com/davrempe/humor)]

* **Dynamic 3D Gaussians** : "Dynamic 3D Gaussians:Tracking by Persistent Dynamic View Synthesis", *International Conference on 3D Vision (3DV) 2024*. [[Paper](https://arxiv.org/pdf/2308.09713)] [[Webpage](https://dynamic3dgaussians.github.io/)] [[Code](https://github.com/JonathonLuiten/Dynamic3DGaussians)]

* **Humans in 4D**: Reconstructing and Tracking Humans with Transformers, *ICCV 23*. [[Paper](https://arxiv.org/pdf/2305.20091)] [[Webpage](https://shubham-goel.github.io/4dhumans/)] [[Code](https://github.com/shubham-goel/4D-Humans)]

> My Personal Note for Diffusions in Motion: [[Diffusion in Motion](https://solid-citrus-f4e.notion.site/Diffusion-1cd41d453f588066b3a7f791533116f5)]
------------------------------

### RAFT

* **RAFT**: Recurrent All-Pairs Field Transforms for **Optical Flow**, *ECCV 2020* [[Paper](https://arxiv.org/pdf/2003.12039)] [[Code](https://github.com/princeton-vl/RAFT)]

* **RAFT-Stereo**: Multilevel Recurrent Field Transforms for **Stereo Matching**, *3DV 2021* [[Paper](https://arxiv.org/abs/2109.07547)] [[Code](https://github.com/princeton-vl/RAFT-Stereo)]

> We only have to `scan` a `line` for correspondence [Epipolar Geometry]

* **RAFT-3D**: Scene Flow using Rigid-Motion Embeddings, *CVPR 2021* [[Paper](https://arxiv.org/abs/2012.00726)] [[Code](https://github.com/princeton-vl/RAFT-3D)]

* **DROID-SLAM**: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras, *Neurips 2021* [[Paper](https://arxiv.org/abs/2108.10869)] [[Code](https://github.com/princeton-vl/DROID-SLAM)]

* **MegaSaM** :"Accurate, Fast and Robust Structure and Motion from Casual Dynamic Videos", *arXiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.04463)] [[Webpage](https://mega-sam.github.io/)][[Code](https://github.com/mega-sam/mega-sam)]


------------------------------
### 4D Reconstruction

* **4D Gaussian Splatting** : "Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting", *ICLR 2024*. [[Paper](https://arxiv.org/pdf/2310.10642)] [[Webpage](https://fudan-zvg.github.io/4d-gaussian-splatting/)] [[Code](https://github.com/fudan-zvg/4d-gaussian-splatting)]


* **Temporal Gaussians** : "Representing Long Volumetric Video
with Temporal Gaussian Hierarchy", *SIGGRAPH Asia 2024 (TOG)*, [[Paper](https://arxiv.org/pdf/2412.09608)] [[Webpage](https://zju3dv.github.io/longvolcap/)] [[Code](https://github.com/zju3dv/EasyVolcap)]

------------------------------
#### Monocular Dynamic Reconstruction

* **4D Reconstruction from a Single Video** : "Shape of Motion:
4D Reconstruction from a Single Video", *arXiv Jul 2024*. [[Paper](https://arxiv.org/pdf/2405.02280)] [[Webpage](https://dreamscene4d.github.io/)] [[Code](https://github.com/dreamscene4d/dreamscene4d)]

* **DreamScene4D**: "DreamScene4D: Dynamic Multi-Object Scene Generation from Monocular Videos" *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2406.01584)] [[Webpage](https://www.anjiecheng.me/DreamScene4D)] [[Code](https://github.com/dreamscene4d/dreamscene4d)]

------------------------------


### Robust, Calibration-free Reconstruction

* **pixelSplat** : "pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction", *CVPR 2024*. [[Paper](https://arxiv.org/pdf/2312.12337)] [[Webpage](https://davidcharatan.com/pixelsplat/)] [[Code](https://github.com/dcharatan/pixelsplat)]

* **DUSt3R**: "DUSt3R:Geometric 3D Vision Made Easy", *CVPR 2024*. [[Paper](https://arxiv.org/pdf/2312.14132)] [[Webpage](https://dust3r.europe.naverlabs.com/)] [[Code](https://github.com/naver/dust3r)]

* **MASt3R** : "Grounding Image Matching in 3D with MASt3R", [[Paper](https://arxiv.org/pdf/2406.09756)] [[Webpage](https://europe.naverlabs.com/blog/mast3r-matching-and-stereo-3d-reconstruction/)] [[Code](https://github.com/naver/mast3r)]

* **Splatt3R** : "Splatt3R: Zero-shot Gaussian Splatting from Uncalibrated Image Pairs", *arXiv Aug 2024*. [[Paper](https://arxiv.org/pdf/2408.13912)] [[Webpage](https://splatt3r.active.vision/)] [[Code](https://github.com/btsmart/splatt3r)]

* **SLAM3R** "SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos", *arXiv Dec 2024*. [[Paper](https://arxiv.org/abs/2412.09401)] [[Code](https://github.com/PKU-VCL-3DV/SLAM3R)]

* **CUT3R** : "Continuous 3D Perception Model with Persistent State", *arXiv Dec 2024*. [[Paper](https://arxiv.org/abs/2501.12387)] [[Webpage](https://cut3r.github.io/)] [[Code](https://github.com/CUT3R/CUT3R)]

* **Align3R** "Align3R : Aligned Monocular Depth Estimation for Dynamic Videos" *arXiv Dec 2024* [[Paper](https://arxiv.org/abs/2412.03079)] [[Webpage](https://igl-hkust.github.io/Align3R.github.io/)] [[Code](https://github.com/jiah-cloud/Align3R)]

* **MoGe** : "MoGe: Unlocking Accurate Monocular Geometry Estimation for Open-Domain Images with Optimal Training Supervision", *arXiv Nov 2024*. [[Paper](https://arxiv.org/pdf/2410.19115)] [[Webpage](https://wangrc.site/MoGePage/)] [[Code](https://github.com/microsoft/MoGe)]

* **3DGUT** : "3DGUT: Enabling Distorted Cameras and Secondary Rays in Gaussian Splatting", *arXiv Dec 2024*. [[Paper](https://arxiv.org/abs/2412.12507)] [[Webpage](https://research.nvidia.com/labs/toronto-ai/3DGUT/)]

* **FreeSplatter** : "FreeSplatter: Pose-free Gaussian Splatting for Sparse-view 3D Reconstruction", *arXiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.09573)] [[Webpage](https://bluestyle97.github.io/projects/freesplatter/)] [[Code](https://github.com/TencentARC/FreeSplatter)]

* **MegaSaM** :"Accurate, Fast and Robust Structure and Motion from Casual Dynamic Videos", *arXiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.04463)] [[Webpage](https://mega-sam.github.io/)][[Code](https://github.com/mega-sam/mega-sam)]


------------------------------


### VLLM

* **VSI-Bench** : "Thinking in Space:How Multimodal Large Language Models See, Remember and Recall Spaces", *arXiv Aug 2024*. [[Paper](https://arxiv.org/pdf/2412.14171)] [[Webpage](https://vision-x-nyu.github.io/thinking-in-space.github.io/)]

* **Video-3D LLM** "Video-3D LLM : Learning Position-Aware Video Representation for 3D Scene Understanding"  *arXiv Nov 2024*. [[Paper](https://arxiv.org/abs/2412.00493)] [[Code](https://github.com/LaVi-Lab/Video-3D-LLM)]

* **SpatialRGPT** "SpatialRGPT: Grounded Spatial Reasoning in Vision Language Models" *NeurIPS 2024* [[Paper](https://arxiv.org/abs/2406.01584)] [[Webpage](https://www.anjiecheng.me/SpatialRGPT)] [[Code](https://github.com/AnjieCheng/SpatialRGPT)]

------------------------------


### Generative Models

* **Flow Matching** : "Flow Matching for Generative Modeling", *CVPR 2022*. [[Paper](https://arxiv.org/abs/2210.02747)][[Tutorial](https://neurips.cc/virtual/2024/tutorial/99531)]
* **Interactive 3D Scene Generation from a Single Image**: "WonderWorld: Interactive 3D Scene Generation from a Single Image", *CVPR 2024*. [[Paper](https://arxiv.org/pdf/2406.09394)] [[Webpage](https://kovenyu.com/wonderworld/)] [[Code](https://github.com/KovenYu/WonderWorld)]


------------------------------

### 3D Data Synthesis

* **MegaSynth**: "MegaSynth: scaling up feed-forward 3D scene reconstruction with synthesized scenes", *arxiv Dec 2024*. [[Paper](https://arxiv.org/pdf/2412.14166)] [[Webpage](https://hwjiang1510.github.io/MegaSynth/)] [[Code](https://github.com/hwjiang1510/MegaSynth)]


------------------------------

## Awesome Robotics Papers

### Vision-Language-Action Models
* **OpenVLA**: "OpenVLA: An Open-Source Vision-Language-Action Model" *CoRL 2024*. [[Paper](https://arxiv.org/abs/2406.09246)] [[Webpage](https://openvla.github.io/)] [[Code](https://github.com/openvla/openvla)]

* **Octo**: An Open-Source Generalist Robot Policy, *RSS 2024* [[Paper](https://arxiv.org/pdf/2405.12213)] [[Webpage](https://octo-models.github.io/)] [[Code](https://github.com/octo-models/octo)]

* **SimplerEnv**: Simulated Manipulation Policy Evaluation Environments for Real Robot Setups, *CoRL 2024* [[Paper](https://arxiv.org/pdf/2405.05941)] [[Webpage](https://simpler-env.github.io/)] [[Code](https://github.com/simpler-env/SimplerEnv)]

* **$\Pi_0$**: "A Vision-Language-Action Flow Model for
General Robot Control". [[Paper](https://www.physicalintelligence.company/download/pi0.pdf)] [[Webpage](https://www.physicalintelligence.company/blog/pi0)] [[Code](https://github.com/Physical-Intelligence/openpi)]

------------------------------

### Sim2Real/Real2Sim

* **ReBot**: Scaling Robot Learning with Real-to-Sim-to-Real Robotic Video Synthesis, *arXiv 2025* [[Paper](https://arxiv.org/abs/2503.14526)] 

* **RoboVerse**: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning, *arXiv 2025* [[Webpage](https://roboverseorg.github.io)] [[Code](https://github.com/RoboVerseOrg/RoboVerse)]