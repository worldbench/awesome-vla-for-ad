[![Awesome Logo](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![Visitors](https://komarev.com/ghpvc/?username=worldbench&repo=awesome-vla4ad&label=Hello,%20Visitor%20&color=yellow&style=social)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-red.svg?style=flat)](https://github.com/worldbench/awesome-vla4ad/pulls)

# :sunglasses: Awesome VLA for Autonomous Driving

This survey reviews **vision-action (VA)** models and **vision-language-action (VLA)** models for autonomous driving. We ...

For more details, kindly refer to our [paper](https://worldbench.github.io/vla4ad.pdf). :rocket:


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


### Table of Contents
- [**1. Vision-Action-Models**](#1-vision-action-models)
  - [End-to-End VA Models]()
  - [World Models]()
- [**2. Vision-Language-Action-Models**](#2-vision-language-action-models)
  - [End-to-End VLA Models]()
  - [Dual Systems]()
- [**3. Datasets \& Benchmarks**]()
- [**4. Applications**](#4-applications)
- [**5. Other Resources**](#5-other-resources)



## 1. Vision-Action-Models

### :one: End-to-End Models

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
| `VAD` | [![arXiv](https://img.shields.io/badge/arXiv-2303.12077-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2303.12077)<br>VAD: Vectorized Scene Representation for Efficient Autonomous Driving | ICCV 2023 | - | [![GitHub](https://img.shields.io/github/stars/hustvl/VAD)](https://github.com/hustvl/VAD) |
| `TransFuser` | [![arXiv](https://img.shields.io/badge/arXiv-2205.15997-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2205.15997)<br>TransFuser: Imitation with Transformer-Based Sensor Fusion for Autonomous Driving | PAMI 2023 | - | [![GitHub](https://img.shields.io/github/stars/autonomousvision/transfuser)](https://github.com/autonomousvision/transfuser) |
| `GRI` | [![arXiv](https://img.shields.io/badge/arXiv-2111.08575-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2111.08575)<br>GRI: General Reinforced Imitation and its Application to Vision-Based Autonomous Driving | Robotics 2023 | - | - |
| `Think2Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2402.16720-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.16720)<br>Think2Drive: Efficient Reinforcement Learning by Thinking in Latent World Model for Quasi-Realistic Autonomous Driving (in CARLA-v2) | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://thinklab-sjtu.github.io/CornerCaseRepo/) | [![GitHub](https://img.shields.io/github/stars/Thinklab-SJTU/Bench2DriveZoo)](https://github.com/Thinklab-SJTU/Bench2DriveZoo) |
| `GenAD` | [![arXiv](https://img.shields.io/badge/arXiv-2402.11502-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2402.11502)<br>GenAD: Generative End-to-End Autonomous Driving | ECCV 2024 | - | [![GitHub](https://img.shields.io/github/stars/wzzheng/GenAD)](https://github.com/wzzheng/GenAD) |
| `SparseAD` | [![arXiv](https://img.shields.io/badge/arXiv-2404.06892-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2404.06892)<br>SparseAD: Sparse Query-Centric Paradigm for Efficient End-to-End Autonomous Driving | arXiv 2024 | - | - |
| `GaussianAD` | [![arXiv](https://img.shields.io/badge/arXiv-2412.10371-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2412.10371)<br>GaussianAD: Gaussian-Centric End-to-End Autonomous Driving | arXiv 2024 | - | - |
| `SSR` | [![arXiv](https://img.shields.io/badge/arXiv-2409.18341-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2409.18341)<br>Navigation-guided Sparse Scene Representation for End-to-End Autonomous Driving | ICLR 2025 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://openreview.net/forum?id=Vv76fCYffN) | [![GitHub](https://img.shields.io/github/stars/PeidongLi/SSR)](https://github.com/PeidongLi/SSR) |
| `SparseDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2405.19620-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.19620)<br>SparseDrive: End-to-End Autonomous Driving via Sparse Scene Representation | ICRA 2025 | - | [![GitHub](https://img.shields.io/github/stars/swc-17/SparseDrive)](https://github.com/swc-17/SparseDrive) |
| `BEVPlanner` | [![arXiv](https://img.shields.io/badge/arXiv-2312.03031-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2312.03031)<br>Is Ego Status All You Need for Open-Loop End-to-End Autonomous Driving? | CVPR 2024 | - | [![GitHub](https://img.shields.io/github/stars/NVlabs/BEV-Planner)](https://github.com/NVlabs/BEV-Planner) |
| `DiffusionDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2411.15139-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2411.15139)<br>DiffusionDrive: Truncated Diffusion Model for End-to-End Autonomous Driving | CVPR 2025 | - |[![GitHub](https://img.shields.io/github/stars/hustvl/DiffusionDrive)](https://github.com/hustvl/DiffusionDrive) |
| `Raw2Drive` | [![arXiv](https://img.shields.io/badge/arXiv-2505.16394-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2505.16394)<br>Raw2Drive: Reinforcement Learning with Aligned World Models for End-to-End Autonomous Driving (in CARLA v2) | arXiv 2025 | - | - |
| `ETA` | [![arXiv](https://img.shields.io/badge/arXiv-2506.07725-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.07725)<br>ETA: Efficiency through Thinking Ahead, A Dual Approach to Self-Driving with Large Models | ICCV 2025 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/ETA)](https://github.com/OpenDriveLab/ETA) |


### :two: World Models

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
||
| `OccWorld` | [![arXiv](https://img.shields.io/badge/arXiv-2311.16038-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2311.16038)<br>OccWorld: Learning a 3D Occupancy World Model for Autonomous Driving | ECCV 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://wzzheng.net/OccWorld/) | [![GitHub](https://img.shields.io/github/stars/wzzheng/OccWorld)](https://github.com/wzzheng/OccWorld) |
| `NeMo` | [![ECCV](https://img.shields.io/badge/ECCV-2024-b31b1b?style=flat-square)](https://eccv.ecva.net/virtual/2024/poster/250)<br>Neural Volumetric World Models for Autonomous Driving | ECCV 2024 | - | - |
| `Vista` | [![arXiv](https://img.shields.io/badge/arXiv-2405.17398-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2405.17398)<br>Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability | NeurIPS 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://vista-demo.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/Vista)](https://github.com/OpenDriveLab/Vista) |
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


<!-- | `COME` | [![arXiv](https://img.shields.io/badge/arXiv-2506.13260-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2506.13260)<br>COME: Adding Scene-Centric Forecasting Control to Occupancy World Model | arXiv 2025 | - | [![GitHub](https://img.shields.io/github/stars/synsin0/COME)](https://github.com/synsin0/COME)  | -->
## 2. Vision-Language-Action-Models

### :one: Textural Action Generator

| Model | Paper | Venue | Website | GitHub | 
|:-:|:-|:-:|:-:|:-:|
| `DriVLMe` | [![arXiv](https://img.shields.io/badge/arXiv-2311.05547-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2311.05547)<br>DriVLMe: Driving Video-Language Model for Joint Perception and Generation | NeurIPS 2023 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://drivelme.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriVLMe)](https://github.com/OpenDriveLab/DriVLMe) |
| `AlphaDrive` | [![arXiv](https://img.shields.io/badge/arXiv-2403.13244-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2403.13244)<br>AlphaDrive: Towards Autonomous Driving with Foundation Models | arXiv 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://alphadrive-opendrivelab.github.io/) | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/AlphaDrive)](https://github.com/OpenDriveLab/AlphaDrive) |
| `DriveAgent-R1` | [![arXiv](https://img.shields.io/badge/arXiv-2406.07879-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2406.07879)<br>DriveAgent-R1: A Benchmark for Evaluating Autonomous Driving Agents with Real-World Data | arXiv 2024 | - | [![GitHub](https://img.shields.io/github/stars/OpenDriveLab/DriveAgent)](https://github.com/OpenDriveLab/DriveAgent) |
| `Sce2drivex` | [![arXiv](https://img.shields.io/badge/arXiv-2404.01776-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2404.01776)<br>Sce2DriveX: A Large-Scale Dataset for Scene-Consistent 4D Driving Scene Generation | CVPR 2024 | [![Website](https://img.shields.io/badge/Link-yellow?style=flat-square&logo=gitbook)](https://sce2drivex.github.io/) | [![GitHub](https://img.shields.io/github/stars/bytedance/Sce2DriveX)](https://github.com/bytedance/Sce2DriveX) |

## 3. Datasets & Benchmarks



## 4. Applications



## 5. Other Resources




