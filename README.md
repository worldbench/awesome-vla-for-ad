[![Awesome Logo](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Visitors](https://komarev.com/ghpvc/?username=worldbench&repo=awesome-vla4ad&label=Hello,%20Visitor%20&color=yellow&style=social)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-red.svg?style=flat)](https://github.com/worldbench/awesome-vla4ad/pulls)

# :sunglasses: Awesome VLA for Autonomous Driving

This survey reviews **vision-action (VA)** models and **vision-language-action (VLA)** models for autonomous driving. 

<!--
### :books: Citation 

If you find this work helpful for your research, please kindly consider citing our paper:
```bib
@article{survey_vla4ad,
    title   = {Vision-Language-Action Models for Autonomous Driving: Past, Present, and Future},
    author  = {Tianshuai Hu and Xiaolu Liu and Song Wang and Yiyao Zhu and Guoyang Zhao and Jun Cen and Lingdong Kong and Linfeng Li and Xiangtai Li and Shaojie Shen and Jianke Zhu and Dacheng Tao and Junwei Liang},
    journal = {arXiv preprint arXiv:25xx.xxxxx},
    year    = {2025},
}
```
-->


### Table of Contents
- [**1. Vision-Action-Models**](#1-vision-action-models)
  - [:one: End-to-End VA Models](#one-end-to-end-va-models)
  - [:two: World Models](#two-world-models)
    - [Image-Based World Models](#three-image-based-world-models)
    - [Occupancy-Based World Models](#four-occupancy-based-world-models)
- [**2. Vision-Language-Action-Models**](#2-vision-language-action-models)
  - [:one: Textual Action Generator](#one-textural-action-generator)
  - [:two: Numerical Action Generator](#two-numerical-action-generator)
- [**3. Datasets & Benchmarks**](#3-datasets--benchmarks)
- [**4. Applications**](#4-applications)
- [**5. Other Resources**](#5-other-resources)



## 1. Vision-Action-Models

### :one: Action-Only Models

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `LBC` | [![arXiv](https://img.shields.io/badge/arXiv-1912.12294-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1912.12294)<br>Learning by Cheating | CoRL 2020 | - | [![GitHub](https://img.shields.io/github/stars/dotchen/LearningByCheating)](https://github.com/dotchen/LearningByCheating) |
| `Latent-DRL` | [![arXiv](https://img.shields.io/badge/arXiv-2001.08726-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1911.10868)<br>End-to-End Model-Free Reinforcement Learning for Urban Driving using Implicit Affordances | CVPR 2020 | - | - |
| `NEAT` | [![arXiv](https://img.shields.io/badge/arXiv-2109.04456-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2109.04456)<br>NEAT: Neural Attention Fields for End-to-End Autonomous Driving | ICCV 2021 | - | [![GitHub](https://img.shields.io/github/stars/autonomousvision/neat)](https://github.com/autonomousvision/neat) |
| `Roach` | [![arXiv](https://img.shields.io/badge/arXiv-2108.08265-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2108.08265)<br>End-to-End Urban Driving by Imitating a Reinforcement Learning Coach | ICCV 2021 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://zhejz.github.io/roach) | [![GitHub](https://img.shields.io/github/stars/zhejz/carla-roach)](https://github.com/zhejz/carla-roach) |
| `WoR` | [![arXiv](https://img.shields.io/badge/arXiv-2105.00636-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2105.00636)<br>Learning to Drive from A World on Rails | ICCV 2021 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://dotchen.github.io/world_on_rails/) | [![GitHub](https://img.shields.io/github/stars/dotchen/WorldOnRails)](https://github.com/dotchen/WorldOnRails) |
| `TCP` | [![arXiv](https://img.shields.io/badge/arXiv-2206.08129-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2206.08129)<br>Trajectory-guided Control Prediction for End-to-end Autonomous Driving: A Simple yet Strong Baseline | NeurIPS 2022 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/TCP)](https://github.com/OpenDriveLab/TCP) |
| `Urban-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2109.13333-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2109.13333)<br>Urban Driver: Learning to Drive from Real-world Demonstrations Using Policy Gradients | CoRL 2022 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://woven-planet.github.io/l5kit/urban_driver.html/) | [![GitHub](https://img.shields.io/github/stars/woven-planet/l5kit)](https://github.com/woven-planet/l5kit) |
| `ST-P3` | [![arXiv](https://img.shields.io/badge/arXiv-2207.07601-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2207.07601)<br>ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning | ECCV 2022 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/ST-P3)](https://github.com/OpenDriveLab/ST-P3) |
| `LAV` | [![arXiv](https://img.shields.io/badge/arXiv-2203.11934-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2203.11934)<br>Learning from All Vehicles | CVPR 2022 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://dotchen.github.io/LAV/) | [![GitHub](https://img.shields.io/github/stars/dotchen/LAV)](https://github.com/dotchen/LAV) |
| `UniAD` | [![arXiv](https://img.shields.io/badge/arXiv-2212.10156-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2212.10156)<br>Planning-oriented Autonomous Driving | CVPR 2023 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/UniAD)](https://github.com/OpenDriveLab/UniAD) |
| `TransFuser` | [![arXiv](https://img.shields.io/badge/arXiv-2205.15997-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2205.15997)<br>TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving | PAMI 2023 | - | [![GitHub](https://img.shields.io/github/stars/autonomousvision/transfuser)](https://github.com/autonomousvision/transfuser) |
| `GRI` | [![arXiv](https://img.shields.io/badge/arXiv-2111.08575-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2111.08575)<br>GRI: General Reinforced Imitation and its Application to Vision-Based Autonomous Driving | Robotics 2023 | - | - |
| `VAD` | [![arXiv](https://img.shields.io/badge/arXiv-2303.12077-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2303.12077)<br>VAD: Vectorized Scene Representation for Efficient Autonomous Driving | ICCV 2023 | - | [![GitHub](https://img.shields.io/github/stars/hustvl/VAD)](https://github.com/hustvl/VAD) |
| `OccNet` | [![arXiv](https://img.shields.io/badge/arXiv-2306.02851-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2306.02851)<br>Scene as Occupancy | ICCV 2023 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/OccNet)](https://github.com/OpenDriveLab/OccNet) |
| `Think2Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2402.16720-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.16720)<br>Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving (in CARLA-v2) | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://thinklab-sjtu.github.io/CornerCaseRepo/) | [![GitHub](https://img.shields.io/github/stars/Thinklab-SJTU/Bench2DriveZoo)](https://github.com/Thinklab-SJTU/Bench2DriveZoo) |
| `GenAD` | [![arXiv](https://img.shields.io/badge/arXiv-2402.11502-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.11502)<br>GenAD: Generative End-to-End Autonomous Driving | ECCV 2024 | - | [![GitHub](https://img.shields.io/github/stars/wzzheng/GenAD)](https://github.com/wzzheng/GenAD) |
| `PARA-Drive` | [![CVPR](https://img.shields.io/badge/CVPR-2024-b31b1b?style=flat-square)](https://openaccess.thecvf.com/content/CVPR2024/papers/Weng_PARA-Drive_Parallelized_Architecture_for_Real-time_Autonomous_Driving_CVPR_2024_paper.pdf)<br>PARA-Drive: Parallelized Architecture for Real-time Autonomous Driving | CVPR 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://xinshuoweng.github.io/paradrive/) | - |
| `BEVPlanner` | [![arXiv](https://img.shields.io/badge/arXiv-2312.03031-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.03031)<br>Is Ego Status All You Need for Open-Loop End-to-End Autonomous Driving? | CVPR 2024 | - | [![GitHub](https://img.shields.io/github/stars/NVlabs/BEV-Planner)](https://github.com/NVlabs/BEV-Planner) |
| `SparseAD` | [![arXiv](https://img.shields.io/badge/arXiv-2404.06892-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2404.06892)<br>SparseAD: Sparse Query-Centric Paradigm for Efficient End-to-End Autonomous Driving | arXiv 2024 | - | - |
| `GaussianAD` | [![arXiv](https://img.shields.io/badge/arXiv-2412.10371-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.10371)<br>GaussianAD: Gaussian-Centric End-to-End Autonomous Driving | arXiv 2024 | - | - |
| `DiFSD` | [![arXiv](https://img.shields.io/badge/arXiv-2409.09777-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.09777)<br>DiFSD: Ego-Centric Fully Sparse Paradigm with Uncertainty Denoising and Iterative Refinement for Efficient End-to-End Self-Driving | arXiv 2024 | - | [![GitHub](https://img.shields.io/github/stars/suhaisheng/DiFSD)](https://github.com/suhaisheng/DiFSD) |
| `SSR` | [![arXiv](https://img.shields.io/badge/arXiv-2409.18341-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.18341)<br>Navigation-guided Sparse Scene Representation for End-to-End Autonomous Driving | ICLR 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://openreview.net/forum?id=Vv76fCYffN) | [![GitHub](https://img.shields.io/github/stars/PeidongLi/SSR)](https://github.com/PeidongLi/SSR) |
| `DriveTransformer` | [![arXiv](https://img.shields.io/badge/arXiv-2503.07656-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.07656)<br>DriveTransformer: Unified Transformer for Scalable End-to-End Autonomous Driving | ICLR 2025 | - | [![GitHub](https://img.shields.io/github/stars/Thinklab-SJTU/DriveTransformer)](https://github.com/Thinklab-SJTU/DriveTransformer) |
| `SparseDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2405.19620-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.19620)<br>SparseDrive: End-to-End Autonomous Driving via Sparse Scene Representation | ICRA 2025 | - | [![GitHub](https://img.shields.io/github/stars/swc-17/SparseDrive)](https://github.com/swc-17/SparseDrive) |
| `DiffusionDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2411.15139-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2411.15139)<br>DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving | CVPR 2025 | - |[![GitHub](https://img.shields.io/github/stars/hustvl/DiffusionDrive)](https://github.com/hustvl/DiffusionDrive) |
| `Raw2Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16394-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.16394)<br>Raw2Drive: Reinforcement Learning with Aligned World Models for End-to-End Autonomous Driving (in CARLA v2) | arXiv 2025 | - | - |
| `RAD` | [![arXiv](https://img.shields.io/badge/arXiv-2502.13144-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2502.13144)<br>RAD: Training an End-to-End Driving Policy via Large-Scale 3DGS-based Reinforcement Learning | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://hgao-cv.github.io/RAD/) | - |


### :two: Perception-Action Models

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `OccWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2311.16038-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2311.16038)<br>OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://wzzheng.net/OccWorld/) | [![GitHub](https://img.shields.io/github/stars/wzzheng/OccWorld)](https://github.com/wzzheng/OccWorld) |
| `NeMo` | [![ECCV](https://img.shields.io/badge/ECCV-2024-b31b1b?style=flat-square)](https://eccv.ecva.net/virtual/2024/poster/250)<br>Neural Volumetric World Models for Autonomous Driving | ECCV 2024 | - | - |
| `DriveDreamer` | [![arXiv](https://img.shields.io/badge/arXiv-2309.09777-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2309.09777)<br>DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drivedreamer.github.io/) | [![GitHub](https://img.shields.io/github/stars/JeffWang987/DriveDreamer)](https://github.com/JeffWang987/DriveDreamer) |
| `GenAD` | [![arXiv](https://img.shields.io/badge/arXiv-2403.09630-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.09630)<br>GenAD: Generalized Predictive Model for Autonomous Driving | CVPR 2024 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI)](https://github.com/OpenDriveLab/DriveAGI) |
| `Drive-WM` | [![arXiv](https://img.shields.io/badge/arXiv-2311.17918-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2311.17918)<br>Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving | CVPR 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drive-wm.github.io/) | [![GitHub](https://img.shields.io/github/stars/BraveGroup/Drive-WM)](https://github.com/BraveGroup/Drive-WM) |
| `OccVAR` | [![OpenReview](https://img.shields.io/badge/OpenReview-OCCVAR-b31b1b?style=flat-square)](https://openreview.net/forum?id=OccVAR)<br>OCCVAR: Scalable 4D Occupancy Prediction via Next-Scale Prediction | OpenReview 2024 | - | - |
| `DrivingWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2412.19505-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.19505)<br>DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://huxiaotaostasy.github.io/DrivingWorld/index.html) | [![GitHub](https://img.shields.io/github/stars/YvanYin/DrivingWorld)](https://github.com/YvanYin/DrivingWorld) |
| `RenderWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2409.11356-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.11356)<br>RenderWorld: World Model with Self-Supervised 3D Label | arXiv 2024 | - | - |
| `DFIT-OccWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2412.13772-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.13772)<br>An Efficient Occupancy World Model via Decoupled Dynamic Flow and Image-assisted Training | arXiv 2024 | - | - |
| `Covariate-Shift` | [![arXiv](https://img.shields.io/badge/arXiv-2409.16663-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.16663)<br>Mitigating Covariate Shift in Imitation Learning for Autonomous Vehicles Using Latent Space Generative World Models | arXiv 2024 | - | - |
| `Imagine-2-Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2411.10171-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2411.10171)<br>Imagine-2-Drive: Leveraging High-Fidelity World Models via Multi-Modal Diffusion Policies | IROS 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://imagine-2-drive.github.io/) | - |
| `DrivingGPT` | [![arXiv](https://img.shields.io/badge/arXiv-2412.18607-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.18607)<br>DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://rogerchern.github.io/DrivingGPT/) | - |
| `Epona` | [![arXiv](https://img.shields.io/badge/arXiv-2506.24113-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.24113)<br>Epona: Autoregressive Diffusion World Model for Autonomous Driving | ICCV 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://kevin-thu.github.io/Epona/) | [![GitHub](https://img.shields.io/github/stars/Kevin-thu/Epona)](https://github.com/Kevin-thu/Epona) |
| `World4Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2507.00603-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.00603)<br>World4Drive: End-to-End Autonomous Driving via Intention-aware Physical Latent World Model | ICCV 2025 | - | - |
| `LAW` | [![arXiv](https://img.shields.io/badge/arXiv-2406.08481-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2406.08481)<br>Enhancing End-to-End Autonomous Driving with Latent World Model | ICLR 2025 | - | [![GitHub](https://img.shields.io/github/stars/BraveGroup/LAW)](https://github.com/BraveGroup/LAW) |
| `AdaWM` | [![arXiv](https://img.shields.io/badge/arXiv-2501.13072-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2501.13072)<br>AdaWM: Adaptive World Model based Planning for Autonomous Driving | ICLR 2025 | - | - |
| `Drive-OccWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2408.14197-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2408.14197)<br>Driving in the Occupancy World: Vision-Centric 4D Occupancy Forecasting and Planning via World Models for Autonomous Driving | AAAI 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drive-occworld.github.io/) | [![GitHub](https://img.shields.io/github/stars/yuyang-cloud/Drive-OccWorld)](https://github.com/yuyang-cloud/Drive-OccWorld)  |
| `T³Former` | [![arXiv](https://img.shields.io/badge/arXiv-2503.07338-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.07338)<br>Temporal Triplane Transformers as Occupancy World Models | arXiv 2025 | - | - |
| `Echo-Planning` | [![arXiv](https://img.shields.io/badge/arXiv-2505.18945-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.18945)<br>Echo Planning for Autonomous Driving: From Current Observations to Future Trajectories and Back | arXiv 2025 | - | - |
| `VeteranAD` | [![arXiv](https://img.shields.io/badge/arXiv-2508.11488-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2508.11488)<br>Perception in Plan: Coupled Perception and Planning for End-to-End Autonomous Driving | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/fudan-zvg/VeteranAD)](https://github.com/fudan-zvg/VeteranAD) |

<!-- | `Vista` | [![arXiv](https://img.shields.io/badge/arXiv-2405.17398-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.17398)<br>Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | NeurIPS 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://vista-demo.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/Vista)](https://github.com/OpenDriveLab/Vista) | -->

<!-- | `COME` | [![arXiv](https://img.shields.io/badge/arXiv-2506.13260-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.13260)<br>COME: Adding Scene-Centric Forecasting Control to Occupancy World Model | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/synsin0/COME)](https://github.com/synsin0/COME)  | -->

### :three: Image-Based World Models

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||

### :four: Occupancy-Based World Models

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||

## 2. Vision-Language-Action-Models

> :timer_clock: In chronological order, from the earliest to the latest.

### :one: Textural Action Generator

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `GPT-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2310.01415-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2310.01415)<br>GPT-Driver: Learning to Drive with GPT | NeurIPSW 2023 |[![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://pointscoder.github.io/projects/gpt_driver/index.html) | [![GitHub](https://img.shields.io/github/stars/PointsCoder/GPT-Driver)](https://github.com/PointsCoder/GPT-Driver) |
| `RAG-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2402.10828-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.10828)<br>RAG-Driver: Generalisable Driving Explanations with Retrieval-Augmented In-Context Learning in Multi-Modal Large Language Model | RSS 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://yuanjianhao508.github.io/RAG-Driver/) | [![GitHub](https://img.shields.io/github/stars/YuanJianhao508/RAG-Driver)](https://github.com/YuanJianhao508/RAG-Driver) |
| `RDA-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2408.13890-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2408.13890)<br>Making Large Language Models Better Planners with Reasoning-Decision Alignment | ECCV 2024 | - | - |
| `DriveLM` | [![arXiv](https://img.shields.io/badge/arXiv-2312.14150-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.14150)<br>DriveLM: Driving with Graph Visual Question Answering | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://opendrivelab.com/DriveLM/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveLM)](https://github.com/OpenDriveLab/DriveLM) |
| `DriveMLM` | [![arXiv](https://img.shields.io/badge/arXiv-2312.09245-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.09245)<br>DriveMLM: Aligning Multi-Modal Large Language Models with Behavioral Planning States for Autonomous Driving | arXiv 2023 | - | [![GitHub](https://img.shields.io/github/stars/OpenGVLab/DriveMLM)](https://github.com/OpenGVLab/DriveMLM) |
| `DriveGPT-4` | [![arXiv](https://img.shields.io/badge/arXiv-2310.01412-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2310.01412)<br>DriveGPT4: Interpretable End-to-end Autonomous Driving via Large Language Model | RA-L 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://tonyxuqaq.github.io/projects/DriveGPT4/) | - |
| `DriVLMe` | [![arXiv](https://img.shields.io/badge/arXiv-2406.03008-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2406.03008)<br>DriVLMe: Enhancing LLM-based Autonomous Driving Agents with Embodied and Social Experience | IROS 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://sled-group.github.io/driVLMe/) | [![GitHub](https://img.shields.io/github/stars/sled-group/driVLMe)](https://github.com/sled-group/driVLMe) |
| `SafeAuto` | [![arXiv](https://img.shields.io/badge/arXiv-2503.00211-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.00211)<br>SafeAuto: Knowledge-Enhanced Safe Autonomous Driving with Multimodal Foundation Models | ICML 2025 | - | [![GitHub](https://img.shields.io/github/stars/AI-secure/SafeAuto)](https://github.com/AI-secure/SafeAuto) |
| `OpenEMMA` | [![arXiv](https://img.shields.io/badge/arXiv-2412.15208-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.15208)<br>OpenEMMA: Open-Source Multimodal Model for End-to-End Autonomous Driving | arXiv 2024 | - | [![GitHub](https://img.shields.io/github/stars/taco-group/OpenEMMA)](https://github.com/taco-group/OpenEMMA) |
| `WKER` | [![arXiv](https://img.shields.io/badge/arXiv-2412.06324-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.06324)<br>World knowledge-enhanced Reasoning Using Instruction-guided Interactor in Autonomous Driving | AAAI 2025 | - | - |
| `OmniDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2405.01533-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.01533)<br>OmniDrive: A Holistic LLM-Agent Framework for Autonomous Driving with 3D Perception, Reasoning and Planning | CVPR 2025 | - | [![GitHub](https://img.shields.io/github/stars/NVlabs/OmniDrive)](https://github.com/NVlabs/OmniDrive) |
| `EMMA` | [![arXiv](https://img.shields.io/badge/arXiv-2410.23262-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2410.23262)<br>EMMA: End-to-End Multimodal Model for Autonomous Driving | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://waymo.com/blog/2024/10/introducing-emma/) | - |
| `AlphaDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2503.07608-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.07608)<br>AlphaDrive: Unleashing the Power of VLMs in Autonomous Driving via Reinforcement Learning and Reasoning | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/hustvl/AlphaDrive)](https://github.com/hustvl/AlphaDrive) |
| `DriveAgent-R1` | [![arXiv](https://img.shields.io/badge/arXiv-2507.20879-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.20879)<br>DriveAgent-R1: Advancing VLM-based Autonomous Driving with Hybrid Thinking and Active Perception | arXiv 2025 | - | - |
| `Sce2drivex` | [![arXiv](https://img.shields.io/badge/arXiv-2502.14917-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2502.14917)<br>Sce2DriveX: A Generalized MLLM Framework for Scene-to-Drive Learning | arXiv 2025 | - | - |
| `Drive-R1` | [![arXiv](https://img.shields.io/badge/arXiv-2506.18234-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.18234)<br>Drive-R1: Bridging Reasoning and Planning in VLMs for Autonomous Driving with Reinforcement Learning | arXiv 2025 | - | - |
| `FastDriveVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2507.23318-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.23318)<br>FastDriveVLA: Efficient End-to-End Driving via Plug-and-Play Reconstruction-based Token Pruning | arXiv 2025 | - | - |
| `Wisead` | [![arXiv](https://img.shields.io/badge/arXiv-2412.09951-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.09951)<br>WiseAD: Knowledge Augmented End-to-End Autonomous Driving with Vision-Language Model | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://wyddmw.github.io/WiseAD_demo/) | [![GitHub](https://img.shields.io/github/stars/wyddmw/WiseAD)](https://github.com/wyddmw/WiseAD) |
| `Impromptu-VLA` | [![arXiv](https://img.shields.io/badge/arXiv-2505.23757-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.23757)<br>Impromptu VLA: Open Weights and Open Data for Driving Vision-Language-Action Models | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://impromptu-vla.c7w.tech/) | [![GitHub](https://img.shields.io/github/stars/ahydchh/Impromptu-VLA)](https://github.com/ahydchh/Impromptu-VLA) |
| `LightEMMA` | [![arXiv](https://img.shields.io/badge/arXiv-2505.00284-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.00284)<br>LightEMMA: Lightweight End-to-End Multimodal Model for Autonomous Driving | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/michigan-traffic-lab/LightEMMA)](https://github.com/michigan-traffic-lab/LightEMMA) | 
| `AutoDrive-R²` | [![arXiv](https://img.shields.io/badge/arXiv-2509.01944-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.01944)<br>Impromptu VLA: Open Weights and Open Data for Driving Vision-Language-Action Models | arXiv 2025 | - | - |
| `OmniReason` | [![arXiv](https://img.shields.io/badge/arXiv-2509.00789-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.00789)<br>OmniReason: A Temporal-Guided Vision-Language-Action Framework for Autonomous Driving | arXiv 2025 | - | - |

<!-- 
| `DriVLMe` | [![arXiv](https://img.shields.io/badge/arXiv-2311.05547-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2311.05547)<br>DriVLMe: Driving Video-Language Model for Joint Perception and Generation | NeurIPS 2023 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drivelme.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriVLMe)](https://github.com/OpenDriveLab/DriVLMe) |
| `AlphaDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2403.13244-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.13244)<br>AlphaDrive: Towards Autonomous Driving with Foundation Models | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://alphadrive-opendrivelab.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/AlphaDrive)](https://github.com/OpenDriveLab/AlphaDrive) |
| `DriveAgent-R1` | [![arXiv](https://img.shields.io/badge/arXiv-2406.07879-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2406.07879)<br>DriveAgent-R1: A Benchmark for Evaluating Autonomous Driving Agents with Real-World Data | arXiv 2024 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveAgent)](https://github.com/OpenDriveLab/DriveAgent) |
| `Sce2drivex` | [![arXiv](https://img.shields.io/badge/arXiv-2404.01776-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2404.01776)<br>Sce2DriveX: A Large-Scale Dataset for Scene-Consistent 4D Driving Scene Generation | CVPR 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://sce2drivex.github.io/) | [![GitHub](https://img.shields.io/github/stars/bytedance/Sce2DriveX)](https://github.com/bytedance/Sce2DriveX) | -->

### :two: Numerical Action Generator

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `LMDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2312.07488-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.07488)<br>LMDrive: Closed-Loop End-to-End Driving with Large Language Models | CVPR 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://hao-shao.com/projects/lmdrive.html) | [![GitHub](https://img.shields.io/github/stars/opendilab/LMDrive)](https://github.com/opendilab/LMDrive) |
| `LINGO-2` | -<br>LINGO-2: Driving with Natural Language | 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://wayve.ai/thinking/lingo-2-driving-with-language/) | - |
| `CoVLA-Agent` | [![arXiv](https://img.shields.io/badge/arXiv-2408.10845-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2408.10845)<br>CoVLA: Comprehensive Vision-Language-Action Dataset for Autonomous Driving | WACV 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://turingmotors.github.io/covla-ad/) | - |
| `ORION` | [![arXiv](https://img.shields.io/badge/arXiv-2503.19755-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.19755)<br>ORION: A Holistic End-to-End Autonomous Driving Framework by Vision-Language Instructed Action Generation | ICCV 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://xiaomi-mlab.github.io/Orion/) | [![GitHub](https://img.shields.io/github/stars/xiaomi-mlab/Orion)](https://github.com/xiaomi-mlab/Orion) |
| `SimLingo` | [![arXiv](https://img.shields.io/badge/arXiv-2503.09594-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.09594)<br>SimLingo: Vision-Only Closed-Loop Autonomous Driving with Language-Action Alignment | CVPR 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://www.katrinrenz.de/simlingo/) | [![GitHub](https://img.shields.io/github/stars/RenzKa/simlingo)](https://github.com/RenzKa/simlingo) |
| `DriveGPT4-V2` | [![CVPR](https://img.shields.io/badge/CVPR-2025-b31b1b?style=flat-square)](https://eccv.ecva.net/virtual/2025/poster/250)<br>DriveGPT4-V2: Harnessing Large Language Model Capabilities for Enhanced Closed-Loop Autonomous Driving | CVPR 2025 | - | - |
| `VaViM` | [![arXiv](https://img.shields.io/badge/arXiv-2502.15672-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2502.15672)<br>VaViM and VaVAM: Autonomous Driving through Video Generative Modeling | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://valeoai.github.io/vavim-vavam/) | [![GitHub](https://img.shields.io/github/stars/valeoai/VideoActionModel)](https://github.com/valeoai/VideoActionModel) |
| `BEVDriver` | [![arXiv](https://img.shields.io/badge/arXiv-2503.03074-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.03074)<br>BEVDriver: Leveraging BEV Maps in LLMs for Robust Closed-Loop Driving | arXiv 2025 | - | - |
| `DriveMoE` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16278-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.16278)<br>DriveMoE: Mixture-of-Experts for Vision-Language-Action Model in End-to-End Autonomous Driving | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://thinklab-sjtu.github.io/DriveMoE/) | [![GitHub](https://img.shields.io/github/stars/Thinklab-SJTU/DriveMoE)](https://github.com/Thinklab-SJTU/DriveMoE) |
| `DSDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2505.05360-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.05360)<br>DSDrive: Distilling Large Language Model for Lightweight End-to-End Autonomous Driving with Unified Reasoning and Planning | arXiv 2025 | - | - |
| `S4-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2505.24139-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.24139)<br>S4-Driver: Scalable Self-Supervised Driving Multimodal Large Language Model with Spatio-Temporal Visual Representation | CVPR 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://s4-driver.github.io/) | - |
| `AutoVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2506.13757-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.13757)<br>AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://autovla.github.io/) | [![GitHub](https://img.shields.io/github/stars/ucla-mobility/AutoVLA)](https://github.com/ucla-mobility/AutoVLA) |
| `OpenDriveVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2503.23463-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.23463)<br>OpenDriveVLA: Towards End-to-end Autonomous Driving with Large Vision Language Action Model | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drivevla.github.io/) | [![GitHub](https://img.shields.io/github/stars/DriveVLA/OpenDriveVLA)](https://github.com/DriveVLA/OpenDriveVLA) |
| `PLA` | [![arXiv](https://img.shields.io/badge/arXiv-2507.23540-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.23540)<br>A Unified Perception-Language-Action Framework for Adaptive Autonomous Driving | arXiv 2025 | - | - |
| `OccVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2509.05578-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.05578)<br>OccVLA: Vision-Language-Action Model with Implicit 3D Occupancy Supervision | arXiv 2024 | - | - |

### :three: Explicit Action Guidance

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `DriveVLM` | [![arXiv](https://img.shields.io/badge/arXiv-2402.12289-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.12289)<br>DriveVLM: The convergence of autonomous driving and large vision-language models | CoRL 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://tsinghua-mars-lab.github.io/DriveVLM/) | - |
| `DualAD` | [![arXiv](https://img.shields.io/badge/arXiv-2409.18053-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.18053)<br>DualAD: Dual-Layer Planning for Reasoning in Autonomous Driving | IROS 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://dualad.github.io/) | [![GitHub](https://img.shields.io/github/stars/TUM-AVS/DualAD)](https://github.com/TUM-AVS/DualAD) |
| `FasionAD` | [![arXiv](https://img.shields.io/badge/arXiv-2411.18013-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2411.18013)<br>FASIONAD : FAst and Slow FusION Thinking Systems for Human-Like Autonomous Driving with Adaptive Feedback | arXiv 2024 | - | - |
| `Senna` | [![arXiv](https://img.shields.io/badge/arXiv-2410.22313-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2410.22313)<br>Senna: Bridging Large Vision-Language Models and End-to-End Autonomous Driving | arXiv 2024 | - | [![GitHub](https://img.shields.io/github/stars/hustvl/Senna)](https://github.com/hustvl/Senna) |
| `LeapAD` | [![arXiv](https://img.shields.io/badge/arXiv-2405.15324-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.15324)<br>Continuously Learning, Adapting, and Improving: A Dual-Process Approach to Autonomous Driving | NeurIPS 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://pjlab-adg.github.io/LeapAD/) | [![GitHub](https://img.shields.io/github/stars/PJLab-ADG/LeapAD)](https://github.com/PJLab-ADG/LeapAD) |
| `DME-Driver` | [![arXiv](https://img.shields.io/badge/arXiv-2401.03641-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2401.03641)<br>DME-Driver: Integrating human decision logic and 3D scene perception in autonomous driving |  AAAI 2025 | - | - |
| `LeapVAD` | [![arXiv](https://img.shields.io/badge/arXiv-2501.08168-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2501.08168)<br>LeapVAD: A Leap in Autonomous Driving via Cognitive Perception and Dual-Process Thinking | arXiv 2025 | - | - |
| `DiffVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2505.19381-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.19381)<br>DiffVLA: Vision-language guided diffusion planning for autonomous driving | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/RenzKa/simlingo)](https://github.com/RenzKa/simlingo) |
| `ReAL-AD` | [![arXiv](https://img.shields.io/badge/arXiv-2507.12499-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.12499)<br>ReAL-AD: Towards Human-Like Reasoning in End-to-End Autonomous Driving | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://4dvlab.github.io/project_page/realad) | - |
| `SOLVE` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16805-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.16805)<br>SOLVE: Synergy of Language-Vision and End-to-End Networks for Autonomous Driving | CVPR 2025 | - | - |


### :four: Implicit Representations Transfer

> :timer_clock: In chronological order, from the earliest to the latest.

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `VLP` | [![arXiv](https://img.shields.io/badge/arXiv-2401.05577-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2401.05577)<br>VLP: Vision language planning for autonomous driving | CVPR 2024 | - | - |
| `VLM-AD` | [![arXiv](https://img.shields.io/badge/arXiv-2412.14446-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.14446)<br>VLM-AD: End-to-end autonomous driving through vision-language model supervision | CoRL 2025 | - | - |
| `DiMA` | [![arXiv](https://img.shields.io/badge/arXiv-2501.09757-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2501.09757)<br>DiMA: Distilling multi-modal large language models for autonomous driving | CVPR 2025 | - | - |
| `ALN-P3` | [![arXiv](https://img.shields.io/badge/arXiv-2505.15158-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.15158)<br>ALN-P3: Unified language alignment for perception, prediction, and planning in autonomous driving | arXiv 2025 | - | - |
| `VERDI` | [![arXiv](https://img.shields.io/badge/arXiv-2505.15925-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.15925)<br>VERDI: VLM-embedded reasoning for autonomous driving | arXiv 2025 | - | - |
| `VLM-E2E` | [![arXiv](https://img.shields.io/badge/arXiv-2502.18042-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2502.18042)<br>VLM-E2E: Enhancing end-to-end autonomous driving with multimodal driver attention fusion | arXiv 2025 | - | - |
| `ReCogDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2506.08052-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.08052)<br>ReCogDrive: A reinforced cognitive framework for end-to-end autonomous driving | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://xiaomi-research.github.io/recogdrive/) | [![GitHub](https://img.shields.io/github/stars/xiaomi-research/ReCogDrive)](https://github.com/xiaomi-research/ReCogDrive) |
| `Insightdrive` | [![arXiv](https://img.shields.io/badge/arXiv-2503.13047-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2503.13047)<br>Insightdrive: Insight scene representation for end-to-end autonomous driving | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/ruiqi-song/InsightDrive)](https://github.com/ruiqi-song/InsightDrive) |
| `NetRoller` | [![arXiv](https://img.shields.io/badge/arXiv-2506.14589-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.14589)<br>NetRoller: Interfacing General and Specialized Models for End-to-End Autonomous Driving | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/Rex-sys-hk/NetRoller)](https://github.com/Rex-sys-hk/NetRoller) |
| `ETA` | [![arXiv](https://img.shields.io/badge/arXiv-2506.07725-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.07725)<br>ETA: Efficiency through Thinking Ahead, A Dual Approach to Self-Driving with Large Models | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/ETA)](https://github.com/OpenDriveLab/ETA) |
| `ViLaD` | [![arXiv](https://img.shields.io/badge/arXiv-2508.12603-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2508.12603)<br>ViLaD: A Large Vision Language Diffusion Framework for End-to-End Autonomous Driving | arXiv 2025 | - | - |

## 3. Datasets & Benchmarks

> :timer_clock: In chronological order, from the earliest to the latest.

### :one: Vision-Action Datasets

| Dataset | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| BDD100K | [![arXiv](https://img.shields.io/badge/arXiv-1805.04687-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1805.04687)<br>BDD100K: A diverse driving dataset for heterogeneous multitask learning | CVPR 2020 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://bair.berkeley.edu/blog/2018/05/30/bdd/) | [![GitHub](https://img.shields.io/github/stars/bdd100k/bdd100k)](https://github.com/bdd100k/bdd100k) |
| nuScenes | [![arXiv](https://img.shields.io/badge/arXiv-1903.11027-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1903.11027)<br>nuScenes: A multimodal dataset for autonomous driving | CVPR 2020 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://www.nuscenes.org/) | - |
| Waymo Open | [![arXiv](https://img.shields.io/badge/arXiv-1912.04838-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1912.04838)<br>Scalability in perception for autonomous driving: Waymo open dataset | CVPR 2020 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://waymo.com/open/) | [![GitHub](https://img.shields.io/github/stars/waymo-research/waymo-open-dataset)](https://github.com/waymo-research/waymo-open-dataset) |
| nuPlan | [![arXiv](https://img.shields.io/badge/arXiv-2106.11810-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2106.11810)<br>nuPlan: A closed-loop ML-based planning benchmark for autonomous vehicles | arXiv 2021 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://www.nuplan.org/) | [![GitHub](https://img.shields.io/github/stars/motional/nuplan-devkit)](https://github.com/motional/nuplan-devkit) |
| Argoverse 2 | [![arXiv](https://img.shields.io/badge/arXiv-2301.00493-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2301.00493)<br>Argoverse 2: Next generation datasets for self-driving perception and forecasting | NeurIPS 2021 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://www.argoverse.org/av2.html) | [![GitHub](https://img.shields.io/github/stars/argoverse/av2-api)](https://github.com/argoverse/av2-api) |
| Bench2Drive | [![arXiv](https://img.shields.io/badge/arXiv-2406.03877-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2406.03877)<br>Bench2Drive: Towards multi-ability benchmarking of closed-loop end-to-end autonomous driving | NeurIPS 2024 | - | [![GitHub](https://img.shields.io/github/stars/Thinklab-SJTU/Bench2Drive)](https://github.com/Thinklab-SJTU/Bench2Drive) |
| RoboBEV | [![arXiv](https://img.shields.io/badge/arXiv-2405.17426-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.17426)<br>Benchmarking and improving bird's eye view perception robustness in autonomous driving | T-PAMI 2025 | - | [![GitHub](https://img.shields.io/github/stars/Daniel-xsy/RoboBEV)](https://github.com/Daniel-xsy/RoboBEV) |

### :two: Vision-Language-Action Datasets

| Dataset | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `BDD-X` | [![arXiv](https://img.shields.io/badge/arXiv-1807.11546-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/1807.11546)<br>Textual explanations for self-driving vehicles | ECCV 2018 | - | [![GitHub](https://img.shields.io/github/stars/JinkyuKimUCB/BDD-X-dataset)](https://github.com/JinkyuKimUCB/BDD-X-dataset) |
| `Talk2Car-Trajectory` | [![IEEE](https://img.shields.io/badge/IEEE-2022-b31b1b?style=flat-square)](https://ieeexplore.ieee.org/document/9961196)<br>Talk2Car: Predicting physical trajectories for natural language commands | IEEE Access 2022 | - | [![GitHub](https://img.shields.io/github/stars/ThierryDeruyttere/Talk2Car-Trajectory)](https://github.com/ThierryDeruyttere/Talk2Car-Trajectory) |
| `DriveLM` | [![arXiv](https://img.shields.io/badge/arXiv-2312.14150-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.14150)<br>DriveLM: Driving with graph visual question answering | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://opendrivelab.com/DriveLM/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveLM)](https://github.com/OpenDriveLab/DriveLM) |
| `DriveLM-CARLA` | [![arXiv](https://img.shields.io/badge/arXiv-2312.14150-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.14150)<br>DriveLM: Driving with graph visual question answering | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://opendrivelab.com/DriveLM/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveLM)](https://github.com/OpenDriveLab/DriveLM) |
| `LingoQA` | [![arXiv](https://img.shields.io/badge/arXiv-2312.14115-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.14115)<br>LingoQA: Visual question answering for autonomous driving | ECCV 2024 | - | [![GitHub](https://img.shields.io/github/stars/wayveai/LingoQA)](https://github.com/wayveai/LingoQA) |
| `NuInstruct` | [![arXiv](https://img.shields.io/badge/arXiv-2401.00988-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2401.00988)<br>Holistic Autonomous Driving Understanding by Bird's-Eye-View Injected Multi-Modal Large Models | CVPR 2024 | - | [![GitHub](https://img.shields.io/github/stars/xmed-lab/NuInstruct)](https://github.com/xmed-lab/NuInstruct) |
| `WOMD-Reason` | [![arXiv](https://img.shields.io/badge/arXiv-2407.04281-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2407.04281)<br>WOMD-Reasoning: A large-scale dataset for interaction reasoning in driving | ICML 2025 |[![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://waymo.com/open/download) | [![GitHub](https://img.shields.io/github/stars/yhli123/WOMD-Reasoning)](https://github.com/yhli123/WOMD-Reasoning) |
| `Reason2Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2312.03661-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.03661)<br>Reason2Drive: Towards interpretable and chain-based reasoning for autonomous driving | ECCV 2024 | - | [![GitHub](https://img.shields.io/github/stars/fudan-zvg/Reason2Drive)](https://github.com/fudan-zvg/Reason2Drive) |
| `DriveBench` | [![arXiv](https://img.shields.io/badge/arXiv-2501.04003-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2501.04003)<br>Are VLMs ready for autonomous driving? an empirical study from the reliability, data, and metric perspectives | ICCV 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drive-bench.github.io/) | [![GitHub](https://img.shields.io/github/stars/drive-bench/toolkit)](https://github.com/drive-bench/toolkit) |
| `OmniDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2405.01533-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.01533)<br>OmniDrive: A Holistic LLM-Agent Framework for Autonomous Driving with 3D Perception, Reasoning and Planning | CVPR 2025 | - | [![GitHub](https://img.shields.io/github/stars/NVlabs/OmniDrive)](https://github.com/NVlabs/OmniDrive) |
| `NuInteract` | [![arXiv](https://img.shields.io/badge/arXiv-2505.08725-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.08725)<br>Extending Large Vision-Language Model for Diverse Interactive Tasks in Autonomous Driving | arXiv 2025 | - | - |
| `DriveAction` | [![arXiv](https://img.shields.io/badge/arXiv-2506.05667-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.05667)<br>DriveAction: A Benchmark for Exploring Human-like Driving Decisions in VLA Models | arXiv 2025 | - | - |
| `DriveCoT` | [![arXiv](https://img.shields.io/badge/arXiv-2403.16996-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.16996)<br>DriveCoT: Integrating chain-of-thought reasoning with end-to-end driving | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drivecot.github.io/) | - |
| `ImpromptuVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2505.23757-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.23757)<br>Impromptu VLA: Open weights and open data for driving vision-language-action models | arXiv 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://impromptu-vla.c7w.tech/) | [![GitHub](https://img.shields.io/github/stars/ahydchh/Impromptu-VLA)](https://github.com/ahydchh/Impromptu-VLA) |
| `CoVLA` | [![arXiv](https://img.shields.io/badge/arXiv-2408.10845-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2408.10845)<br>CoVLA: Comprehensive vision-language-action dataset for autonomous driving | WACV 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://turingmotors.github.io/covla-ad/) | - |
| `OmniReason` | [![arXiv](https://img.shields.io/badge/arXiv-2509.00789-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.00789)<br>OmniReason: A Temporal-Guided Vision-Language-Action Framework for Autonomous Driving | arXiv 2025 | - | - |
| `OmniReason-B2D` | [![arXiv](https://img.shields.io/badge/arXiv-2509.00789-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2509.00789)<br>OmniReason: A Temporal-Guided Vision-Language-Action Framework for Autonomous Driving | arXiv 2025 | - | - |

## 4. Applications



## 5. Other Resources




