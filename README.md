# Awesome-Motion-Generation-based-on-Diffusion-Model
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ucasmjc/Awesome-Motion-Generation-based-on-Diffusion-Model) 

This is a curated list of Motion Generation methods based on diffusion model, organized as the structure in our survey: ''*A Survey on Diffusion-based Motion Generation*''.

[[pdf]](pdfs/A_Survey_on_Diffusion_based_Motion_Generation.pdf), [[CN version]](pdfs/ÎÄÏ××ÛÊö.pdf)

## Abtract
Motion generation is a foundational task in artificial intelligence with broad practical applications. Compared to traditional methods such as VAE, GAN, and Normalizing Flows, diffusion models have become increasingly important in recent years and have emerged as a mainstream approach in motion generation. To harness the full potential of diffusion models, this survey comprehensively reviews literature on motion generation based on diffusion. Beginning with the fundamental principles of diffusion models, the survey focuses particularly on their evolution and conditional generation. After that, relative works on diffusion-based motion generation are categorized into three main types: **motion diffusion models, controllability enhencement, and data availability**, providing detailed discussions on each type. This survey aims to serve as a comprehensive guide, offering insights into the current landscape of diffusion-based motion generation and highlighting promising avenues for future research.

## Table of Contents
- [Awesome-Motion-Generation-based-on-Diffusion-Model](#awesome-motion-generation-based-on-diffusion-model)
  - [Abtract](#abtract)
  - [Table of Contents](#table-of-contents)
  - [Survey](#survey)
  - [Papers](#papers)
    - [Motion Diffusion Model](#motion-diffusion-model)
    - [Controllability Enhencement](#controllability-enhencement)
      - [Spatial Constraints Enhancement](#spatial-constraints-enhancement)
      - [Text Control Enhancement](#text-control-enhancement)
    - [Data Availability](#data-availability)
    - [Others](#others)
      - [Other subjects](#other-subjects)
      - [Music2Dance](#music2dance)
      - [Scene](#scene)
  - [Other Resources](#other-resources)


## Survey

- Human Motion Generation: A Survey [[paper](https://arxiv.org/abs/2307.10894)]
- A Survey on Diffusion-based Motion Generation [[paper](pdfs/A_Survey_on_Diffusion_based_Motion_Generation.pdf)]
## Papers
### Motion Diffusion Model
**Human Motion Diffusion Model**\
ICLR 2023. [[project](https://guytevet.github.io/mdm-page/)] [[paper](https://arxiv.org/abs/2209.14916)] [[code](https://github.com/GuyTevet/motion-diffusion-model)]

**MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model**\
TPAMI 2024. [[project](https://mingyuan-zhang.github.io/projects/MotionDiffuse.html)] [[paper](https://arxiv.org/abs/2208.15001)] [[code](https://github.com/mingyuan-zhang/MotionDiffuse)]

**FLAME: Free-form Language-based Motion Synthesis & Editing**\
AAAI 2023. [[project](https://kakaobrain.github.io/flame/)] [[paper](https://arxiv.org/abs/2209.00349)] [[code](https://github.com/kakaobrain/flame)]

**MLD: Executing your Commands via Motion Diffusion in Latent Space**\
CVPR 2023. [[project](https://chenxin.tech/mld/)] [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Chen_Executing_Your_Commands_via_Motion_Diffusion_in_Latent_Space_CVPR_2023_paper.pdf)] [[code](https://github.com/chenfengye/motion-latent-diffusion)]

**MoFusion: A Framework for Denoising-Diffusion-based Motion Synthesis**\
CVPR 2023. [[project](https://vcai.mpi-inf.mpg.de/projects/MoFusion/)] [[paper](https://arxiv.org/abs/2212.04495)]

**UDE: A Unified Driving Engine for Human Motion Generation**\
CVPR 2023. [[project](https://zixiangzhou916.github.io/UDE/)] [[paper](https://arxiv.org/abs/2211.16016)] [[code](https://github.com/zixiangzhou916/UDE)]

**Priority-Centric Human Motion Generation in Discrete Latent Space**\
ICCV 2023. [[paper](https://arxiv.org/abs/2308.14480)]

**PhysDiff: Physics-Guided Human Motion Diffusion Model**\
ICCV 2023. [[project](https://nvlabs.github.io/PhysDiff/)] [[paper](https://arxiv.org/abs/2212.02500)]

**AAMDM: Accelerated Auto-regressive Motion Diffusion Model**\
CVPR 2024. [[project](https://easypapersniper.github.io/projects/AAMDM/AAMDM.html)] [[paper](https://arxiv.org/abs/2401.06146)] 

**InterGen: Diffusion-based Multi-human Motion Generation under Complex Interactions**\
IJCV 2024. [[project](https://tr3e.github.io/intergen-page/)] [[paper](https://doi.org/10.1007/s11263-024-02042-6)] [[code](https://github.com/tr3e/InterGen)]

**Human Motion Diffusion as a Generative Prior**\
ICLR 2024. [[project](https://priormdm.github.io/priorMDM-page/)] [[paper](https://arxiv.org/abs/2303.01418)] [[code](https://github.com/priorMDM/priorMDM)]
 

### Controllability Enhencement
#### Spatial Constraints Enhancement
**Avatars Grow Legs: Generating Smooth Human Motion from Sparse Tracking Inputs with Diffusion Model**\
CVPR 2023. [[project](https://dulucas.github.io/agrol/)] [[paper](https://arxiv.org/pdf/2304.08577.pdf)] [[code](https://github.com/facebookresearch/AGRoL)]

**GMD: Guided Motion Diffusion for Controllable Human Motion Synthesis**\
ICCV 2023. [[project](https://korrawe.github.io/gmd-project/)] [[paper](https://arxiv.org/abs/2305.12577)] [[code](https://github.com/korrawe/guided-motion-diffusion)]

**Enhanced Fine-Grained Motion Diffusion for Text-Driven Human Motion Synthesis**\
AAAI 2024. [[paper](https://arxiv.org/abs/2305.13773)] 

**WANDR: Intention-guided Human Motion Generation**\
CVPR 2024. [[project](https://wandr.is.tue.mpg.de/)] [[paper](https://arxiv.org/pdf/2404.15383.pdf)] [[code](https://github.com/markos-diomataris/wandr)]

**Programmable Motion Generation for Open-set Motion Control Tasks**\
CVPR 2024. [[project](https://hanchaoliu.github.io/Prog-MoGen/)] [[paper](https://arxiv.org/abs/2405.19283)] [[code](https://github.com/HanchaoLiu/ProgMoGen)]

**OmniControl: Control Any Joint at Any Time for Human Motion Generation**\
ICLR 2024. [[project](https://neu-vi.github.io/omnicontrol/)] [[paper](https://arxiv.org/abs/2310.08580)] [[code](https://github.com/neu-vi/OmniControl)]

**Flexible Motion In-betweening with Diffusion Models**\
Siggraph 2024. [[project](https://setarehc.github.io/CondMDI/)] [[paper](https://arxiv.org/abs/2405.11126)] [[code](https://github.com/setarehc/diffusion-motion-inbetweening)]



#### Text Control Enhancement
**Fg-T2M: Fine-Grained Text-Driven Human Motion Generation via Diffusion Model**\
ICCV 2023. [[project](https://lhchen.top/Human-MAC/)] [[paper](https://arxiv.org/pdf/2302.03665.pdf)] [[code](https://github.com/LinghaoChan/HumanMAC)]

**FineMoGen: Fine-Grained Spatio-Temporal Motion Generation and Editing**\
NeurIPS 2024. [[project](https://mingyuan-zhang.github.io/projects/FineMoGen.html)] [[paper](https://openreview.net/pdf?id=GYjV1M5s0D)] [[code](https://github.com/mingyuan-zhang/FineMoGen)]

**LGTM: Local-to-Global Text-Driven Human Motion Diffusion Model**\
Siggraph 2024. [[paper](http://arxiv.org/abs/2405.03485)] [[code](https://github.com/l-sun/lgtm)]

**AMD: Autoregressive Motion Diffusion**\
AAAI 2024. [[paper](https://arxiv.org/abs/2305.09381)] [[code](https://github.com/fluide1022/AMD)]

**FlowMDM: Seamless Human Motion Composition with Blended Positional Encodings**\
CVPR 2024. [[project](https://barquerogerman.github.io/FlowMDM/)] [[paper](https://arxiv.org/abs/2402.15509)] [[code](https://github.com/BarqueroGerman/FlowMDM)]


### Data Availability
**Make-An-Animation: Large-Scale Text-conditional 3D Human Motion Generation**\
ICCV 2023. [[project](https://azadis.github.io/make-an-animation/)] [[paper](https://arxiv.org/pdf/2305.09662.pdf)]

**ReMoDiffuse: Retrieval-Augmented Motion Diffusion Model**\
ICCV 2023. [[project](https://mingyuan-zhang.github.io/projects/ReMoDiffuse.html)] [[paper](https://arxiv.org/abs/2304.01116)] [[code](https://github.com/mingyuan-zhang/ReMoDiffuse)]

**MotionMix: Weakly-Supervised Diffusion for Controllable Motion Generation**\
AAAI 2024. [[project](https://nhathoang2002.github.io/MotionMix-page/)] [[paper](https://arxiv.org/abs/2401.11115)] [[code](https://github.com/NhatHoang2002/MotionMix)]

**MAS: Multi-view Ancestral Sampling for 3D motion generation using 2D diffusion**\
CVPR 2024. [[project](https://guytevet.github.io/mas-page/)] [[paper](https://arxiv.org/abs/2310.14729)] [[code](https://github.com/roykapon/MAS)]

**OMG: Towards Open-vocabulary Motion Generation via Mixture of Controllers**\
CVPR 2024. [[project](https://tr3e.github.io/omg-page/)] [[paper](https://arxiv.org/abs/2312.08985)]

### Others
#### Other subjects
**OmniMotionGPT: Animal Motion Generation with Limited Data**\
CVPR 2024. [[project](https://zshyang.github.io/omgpt-website/)] [[paper](https://arxiv.org/abs/2311.18303)] [[code](https://zshyang.github.io/omgpt-website/)]

**SinMDM: Single Motion Diffusion**\
ICLR 2024. [[project](https://sinmdm.github.io/SinMDM-page/)] [[paper](https://arxiv.org/abs/2302.05905)] [[code](https://github.com/SinMDM/SinMDM)]

#### Music2Dance
**Listen, denoise, action! Audio-driven motion synthesis with diffusion models**\
Sigraph 2023. [[project](https://www.speech.kth.se/research/listen-denoise-action/)] [[paper](https://arxiv.org/abs/2211.09707)] [[code](https://github.com/simonalexanderson/ListenDenoiseAction)]

**EDGE: Editable Dance Generation From Music**\
CVPR 2023. [[project](https://edge-dance.github.io/)] [[paper](https://arxiv.org/abs/2211.10658)] [[code](https://github.com/Stanford-TML/EDGE)]

**FineDance: A Fine-grained Choreography Dataset for 3D Full Body Dance Generation**\
ICCV 2023. [[project](https://li-ronghui.github.io/finedance)] [[paper](https://arxiv.org/abs/2212.03741)] [[code](https://github.com/li-ronghui/FineDance)]

#### Scene
**Generating Continual Human Motion in Diverse 3D Scenes**\
3DV 2023.  [[paper](https://arxiv.org/abs/2304.02061)] [[code](https://github.com/miraymen/origin)]

**Move as You Say, Interact as You Can: Language-guided Human Motion Generation with Scene Affordance**\
CVPR 2024. [[project](https://afford-motion.github.io/)] [[paper](https://arxiv.org/abs/2403.18036)] [[code](https://github.com/afford-motion/afford-motion)]

**ROAM: Robust and Object-aware Motion Generation using Neural Pose Descriptors**\
3DV 2024.  [[paper](https://vcai.mpi-inf.mpg.de/projects/ROAM/)] [[code](https://github.com/RosettaWYzhang/Roam)]



## Other Resources

- [fengshiwest/Awesome-Motion-Diffusion-Models](https://github.com/fengshiwest/Awesome-Motion-Diffusion-Models)
- [zhshj0110/Awesome-Motion-Diffusion-Models](https://github.com/zhshj0110/Awesome-Motion-Diffusion-Models)

