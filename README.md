# awesome-robust-depth-estimation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome robust depth estimation papers, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).

![teaser](assets/teaser.png)

#### [How to submit a pull request?](https://github.com/hitcslj/awesome-robust-depth-estimation/blob/main/how-to-PR.md)


## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Benchmarks and Datasets](#Benchmarks-and-Datasets)
- [Talks](#talks)
- [Implementations](#implementations)

## Survey

- TODO

## Papers
![knowledge_map](assets/knowledge_map.png)
<details open>
<summary>darkness & adverse weather robust</summary>

- [Defeat-net: General monocular depth via simultaneous unsupervised representation learning](https://arxiv.org/abs/2003.13446), Spencer et al., CVPR 2020 | [github](https://github.com/jspenmar/DeFeat-Net) | [bibtext](./citations/DeFeatNet.txt)
- [Unsupervised monocular depth estimation for night-time images using adversarial domain feature adaptation](https://arxiv.org/abs/2010.01402), Vankadari et al., ECCV 2020 | [bibtext](./citations/ADFA.txt)
- [Regularizing Nighttime Weirdness: Efficient Self-Supervised Monocular Depth Estimation in the Dark](https://arxiv.org/abs/2108.03830), Wang et al., ICCV 2021 | [github](https://github.com/w2kun/RNW) | [bibtext](./citations/RNW.txt)
- [Self-supervised Monocular Depth Estimation for All Day Images using Domain Separation](https://arxiv.org/abs/2108.07628), Lin et al., ICCV 2021 | [github](https://github.com/LINA-lln/ADDS-DepthNet) | [bibtext](./citations/ADDS.txt)
- [Unsupervised monocular depth estimation in highly complex environments](https://arxiv.org/abs/2107.13137), Zhao et al., ITETCI 2022 | [bibtext](./citations/ITDFA.txt)
- [When the Sun Goes Down: Repairing Photometric Losses for All-Day Depth Estimation](https://arxiv.org/abs/2206.13850), Vankadari et al., CoRL 2022 | [bibtext](./citations/WSGD.txt)
- [Self-supervised Monocular Depth Estimation: Let's Talk About The Weather](https://arxiv.org/abs/2307.08357), Kieran Saunders et al., ICCV 2023 | [github](https://github.com/kieran514/robustdepth) | [bibtext](./citations/Robust-Depth.txt)
- [Robust Monocular Depth Estimation under Challenging Conditions](https://arxiv.org/abs/2308.09711), Gasperini et al., ICCV 2023 | [github](https://github.com/md4all/md4all) | [bibtext](./citations/md4all.txt) 
- [WeatherDepth: Curriculum Contrastive Learning for Self-Supervised Depth Estimation under Adverse Weather Conditions](https://arxiv.org/abs/2310.05556), Wang et al., ICRA 2024 | [bibtext](./citations/WeatherDepth.txt)
- [RoboDepth: Robust Out-of-Distribution Depth Estimation under Corruptions](https://arxiv.org/abs/2310.15171), Kong et al., NeurIPS 2023 | [github](https://github.com/ldkong1205/RoboDepth) | [bibtext](./citations/robodepth.txt) 
- [Stealing Stable Diffusion Prior for Robust Monocular Depth Estimation](https://arxiv.org/abs/2403.05056), Mao et al., arxiv 2024 | [github](https://github.com/hitcslj/SSD) | [bibtext](./citations/ssd.txt) 
- [Physical 3D Adversarial Attacks against Monocular Depth Estimation in Autonomous Driving](https://arxiv.org/abs/2403.17301), Zheng et al., CVPR 2024 | [github](https://github.com/gandolfczjh/3d2fool) | [bibtext](./citations/3d2fool.txt) 
- [Digging into contrastive learning for robust depth estimation with diffusion models](https://arxiv.org/abs/2404.09831), Wang et al., arxiv 2024 | [bibtext](./citations/cldiffsusion.txt) 

</details>

<details open>
<summary>multimodality</summary>

- [Depth Estimation from Monocular Images and Sparse Radar Data](https://arxiv.org/abs/2010.00058), Lin et al., IROS 2020 | [github](https://github.com/brade31919/radar_depth) | [bibtext](./citations/deisr.txt)
- [R4Dyn: Exploring Radar for Self-Supervised Monocular Depth Estimation of Dynamic Scenes](https://arxiv.org/abs/2108.04814), Gasperini et al., 3DV 2021 | [bibtext](./citations/R4Dyn.txt)
- [Deep Depth Estimation From Thermal Image](https://openaccess.thecvf.com/content/CVPR2023/html/Shin_Deep_Depth_Estimation_From_Thermal_Image_CVPR_2023_paper.html), Shin et al., CVPR 2023 | [github](https://github.com/UkcheolShin/MS2-MultiSpectralStereoDataset) | [bibtext](./citations/DET.txt)

</details>

<details open>
<summary>mirror robust</summary>

- [Learning Depth Estimation for Transparent and Mirror Surfaces](https://arxiv.org/abs/2307.15052), Costanzino et al., ICCV 2023 | [github](https://github.com/CVLAB-Unibo/Depth4ToM-code#-learning-depth-estimation-for-transparent-and-mirror-surfaces-iccv-2023-) | [bibtext](./citations/Depth2M.txt)

</details>

<details open>
<summary>pose robust</summary>

- [Towards Scale-Aware, Robust, and Generalizable Unsupervised Monocular Depth Estimation by Integrating IMU Motion Dynamics](https://arxiv.org/abs/2207.04680), Zhang et al., ECCV 2022 | [github](https://github.com/SenZHANG-GitHub/ekf-imu-depth) | [bibtext](./citations/ekf-imu-depth.txt)

</details>

<details open>
<summary>robust architecture</summary>

- [Vision Transformers for Dense Prediction](https://arxiv.org/abs/2103.13413), Ranftl et al., ICCV 2021 | [github](https://github.com/isl-org/DPT) | [bibtext](./citations/dpt.txt) 
- [MonoViT: Self-Supervised Monocular Depth Estimation with a Vision Transformer](https://arxiv.org/abs/2208.03543), Zhao et al., 3DV 2022 | [github](https://github.com/zxcqlf/MonoViT) | [bibtext](./citations/monovit.txt)
- [LDM3D: Latent Diffusion Model for 3D](https://arxiv.org/abs/2305.10853), Stan et al., CVPRW 2023  | [huggingface](https://huggingface.co/Intel/ldm3d) | [bibtext](./citations/ldm3d.txt) 
</details>

<details open>
<summary>zero-shot depth estimation</summary>

- [Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer](https://arxiv.org/abs/1907.01341), Ranftl et al., TPAMI 2020 | [github](https://github.com/isl-org/MiDaS) | [bibtext](./citations/midas.txt)
- [ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth](https://arxiv.org/abs/2302.12288), Bhat et al., arxiv 2023 | [github](https://github.com/isl-org/ZoeDepth) | [bibtext](./citations/zoedepth.txt) 
- [Towards Zero-Shot Scale-Aware Monocular Depth Estimation](https://arxiv.org/abs/2306.17253), Guizilini et al., ICCV 2023 | [github](https://github.com/tri-ml/vidar) | [bibtext](./citations/zerodepth.txt) 
- [Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image](https://arxiv.org/abs/2307.10984), Yin et al., ICCV 2023 | [github](https://github.com/YvanYin/Metric3D) | [bibtext](./citations/metric3d.txt)
- [MiDaS v3.1 -- A Model Zoo for Robust Monocular Relative Depth Estimation](https://arxiv.org/abs/2307.14460), Birkl et al., arxiv 2023 | [github](https://github.com/isl-org/MiDaS) | [bibtext](./citations/midas3.txt)
- [Metric3Dv2: A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation](), Hu et al., arxiv 2024 | [github](https://github.com/YvanYin/Metric3D) | [bibtext](./citations/metric3dv2.txt)
- [Zero-Shot Metric Depth with a Field-of-View Conditioned Diffusion Model](https://arxiv.org/abs/2312.13252), Saxena et al., arxiv 2023 | [bibtext](./citations/fvcdm.txt) 
- [Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data](https://arxiv.org/abs/2401.10891), Yang et al., CVPR 2024 | [github](https://github.com/LiheYoung/Depth-Anything) | [bibtext](./citations/depthanything.txt)
- [Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation](https://arxiv.org/abs/2312.02145), Ke et al., CVPR 2024 | [github](https://github.com/prs-eth/marigold) | [bibtext](./citations/marigold.txt) 
- [DepthFM: Fast Monocular Depth Estimation with Flow Matching](https://arxiv.org/abs/2403.13788), Gui et al., arxiv 2024 | [github](https://github.com/CompVis/depth-fm) | [bibtext](./citations/depthFM.txt) 

</details>

<details open>
<summary>cross camera & scene</summary>

- [Learning to Recover 3D Scene Shape from a Single Image](https://arxiv.org/abs/2012.09365), Yin et al., CVPR 2021 | [github](https://github.com/aim-uofa/AdelaiDepth) | [bibtext](./citations/LeReS.txt)
- [Adaptive Fusion of Single-View and Multi-View Depth for Autonomous Driving](https://arxiv.org/abs/2403.07535), Cheng et al., CVPR 2024 | [github](https://github.com/Junda24/AFNet) | [bibtext](./citations/AFNet.txt) 
- [SM4Depth: Seamless Monocular Metric Depth Estimation across Multiple Cameras and Scenes by One Model](https://arxiv.org/abs/2403.08556), Liu et al., arxiv 2024 | [github](https://github.com/1hao-Liu/SM4Depth) | [bibtext](./citations/sm4depth.txt)
- [UniDepth: Universal Monocular Metric Depth Estimation](https://arxiv.org/abs/2403.18913), Piccinelli et al., CVPR 2024 | [github](https://github.com/lpiccinelli-eth/unidepth) | [bibtext](./citations/UniDepth.txt)

</details>

## Benchmarks and Datasets
- [Towards Robust Monocular Depth Estimation: A New Baseline and Benchmark](https://link.springer.com/article/10.1007/s11263-023-01979-4), Ke et al., IJCV 2024| [github](https://github.com/KexianHust/Robust-MonoDepth) | [bibtext](./citations/MDE_branchmark_2024IJCV.txt)
- [RoboDepth: Robust Out-of-Distribution Depth Estimation under Corruptions](https://arxiv.org/abs/2310.15171), Kong et al., NIPS 2023|[github](https://github.com/ldkong1205/RoboDepth) | [bibtext](./citations/RoboDepth-all-corruptions.txt)


## Talks
- TODO

## Challenge
- [ICRA 2023], [The RoboDepth Challenge](https://robodepth.github.io/)
- [第二届粤港澳大湾区(黄埔)国际算法算例大赛], [跨场景单目深度估计](http://123.138.24.155:30080/org/pazhoulab/competition/area/64a76cdb0890cb0bf38b0c57/content)
- [ICRA 2024], [The RoboDrive Challenge Track4 Robust Depth Estimation](https://robodrive-24.github.io/) | [github](https://github.com/robodrive-24/toolkit)



## Implementations
- TODO


## License 
awesome robust depth estimation is released under the [MIT license](./LICENSE).

## Contact
Primary contact: hitcslj@stu.hit.edu.cn. You can also contact: maoyf1105@163.com.