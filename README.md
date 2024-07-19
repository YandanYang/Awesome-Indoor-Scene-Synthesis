# Awesome-Indoor-Scene-Synthesis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Indoor Scene Synthesis papers, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).


<--img src="./asset/mvdream.gif" width="696px"-->
 


#### How to submit a pull request?
Modify the README.md and follow the format TITLE, AUTHOR, CONFERENCE YEAR | OPTIONAL LINK | BIBTEX. For example:

- [PhyScene: Physically Interactable 3D Scene Synthesis for Embodied AI](https://arxiv.org/abs/2404.09465) | CVPR 2024 | [github](https://github.com/PhyScene/PhyScene/tree/main) |[project](https://physcene.github.io/)

## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Benchmarks and Datasets](#Benchmarks-and-Datasets)
- [Talks](#talks)
- [Company](#company)
- [Implementations](#implementations)

## Survey

## Papers

<details open>
<summary>3D Scene synthesis</summary>

- [I-Design: Personalized LLM Interior Designer](https://arxiv.org/abs/2404.02838), arxiv 2024 | [github](https://github.com/atcelen/IDesign/?tab=readme-ov-file) | [project](https://atcelen.github.io/I-Design/)
- [SceneWiz3D: Towards Text-guided 3D Scene Composition](https://arxiv.org/abs/2312.08885), Zhang et al., arxiv 2023 | [github](https://github.com/zqh0253/SceneWiz3D) | [bibtext](./citations/scenewiz3d.txt)
- [AnyHome: Open-Vocabulary Generation of Structured and Textured 3D Homes](https://arxiv.org/abs/2312.06644) | arXiv 2023 | [github](https://github.com/FreddieRao/anyhome_github) | [project](https://freddierao.github.io/AnyHome/)
- [PhyScene: Physically Interactable 3D Scene Synthesis for Embodied AI](https://arxiv.org/abs/2404.09465) | CVPR 2024 | [github](https://github.com/PhyScene/PhyScene/tree/main) |[project](https://physcene.github.io/)
- [Holodeck: Language Guided Generation of 3D Embodied AI Environments](https://arxiv.org/abs/2312.09067) | [github](https://github.com/allenai/Holodeck) | [project](https://yueyang1996.github.io/holodeck/)
- [LayoutGPT: Compositional Visual Planning and Generation with Large Language Models](https://arxiv.org/abs/2305.15393), arxiv 2023| [github](https://github.com/weixi-feng/LayoutGPT) | [project](https://layoutgpt.github.io/)
- [GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting](https://arxiv.org/abs/2402.07207), Zhou et al., arxiv 2024 | [github](https://github.com/VDIGPKU/GALA3D) | [project](https://gala3d.github.io/)
- [Learning 3D Scene Priors with 2D Supervision](https://arxiv.org/abs/2211.14157) | CVPR 2023 | [github](https://github.com/yinyunie/ScenePriors) | [peoject](https://yinyunie.github.io/sceneprior-page/)
- [ATISS: Autoregressive Transformers for Indoor Scene Synthesis](https://arxiv.org/pdf/2110.03675) | NIPS 2021 | [github](https://github.com/nv-tlabs/ATISS) | [project](https://research.nvidia.com/labs/toronto-ai/ATISS/)
- [DiffuScene: Denoising Diffusion Models for Generative Indoor Scene Synthesis](https://arxiv.org/abs/2303.14207) | arXiv 2024 | CVPR 2024 | [github](https://github.com/tangjiapeng/DiffuScene) | [project](https://tangjiapeng.github.io/projects/DiffuScene/)
- [Lay-A-Scene: Personalized 3D Object Arrangement Using Text-to-Image Priors](https://arxiv.org/abs/2406.00687) | [project](https://lay-a-scene.github.io/)
- [Infinigen Indoors: Photorealistic Indoor Scenes using Procedural Generation](https://arxiv.org/abs/2406.11824)  | [github](https://github.com/princeton-vl/infinigen) | [project](https://infinigen.org/)
- [InstructScene: Instruction-Driven 3D Indoor Scene Synthesis with Semantic Graph Prior](https://arxiv.org/abs/2402.04717) | ICLR 2024 | [github](https://github.com/chenguolin/InstructScene) | [project](https://chenguolin.github.io/projects/InstructScene/)
- [Compositional 3D Scene Generation using Locally Conditioned Diffusion](https://arxiv.org/abs/2303.12218), arxiv 2023 | [project](https://ryanpo.com/comp3d/) 
- [CommonScenes: Generating Commonsense 3D Indoor Scenes with Scene Graph Diffusion](https://arxiv.org/abs/2305.16283) | NIPS 2023 | [github](https://github.com/ymxlzgy/commonscenes) | [project](https://sites.google.com/view/commonscenes)
- [Language-driven Scene Synthesis using Multi-conditional Diffusion Model](https://arxiv.org/abs/2310.15948) | arXiv 2023 | [github](https://github.com/andvg3/LSDM) | [project](https://lang-scene-synth.github.io/)
- [3D Scene Diffusion Guidance using Scene Graphs](https://arxiv.org/abs/2308.04468) | arXiv 2023
- [LEGO-Net: Learning Regular Rearrangements of Objects in Rooms](https://arxiv.org/pdf/2301.09629) | CVPR 2023 | [github](https://github.com/QiuhongAnnaWei/LEGO-Net) | [project](https://ivl.cs.brown.edu/research/lego-net.html)
- [CLIP-Layout: Style-Consistent Indoor Scene Synthesis with Semantic Furniture Embedding](https://arxiv.org/abs/2303.03565) | arXiv 2023
- [SceneGraphNet: Neural Message Passing for 3D Indoor Scene Augmentation](https://arxiv.org/abs/1907.11308) | ICCV 2019
- [Configurable 3D Scene Synthesis and 2D Image Rendering with Per-Pixel Ground Truth using Stochastic Grammars](https://arxiv.org/abs/1704.00112) | IJCV (2018)
- [SceneFormer: Indoor Scene Generation with Transformers](https://arxiv.org/abs/2012.09793) | 3DV 2021 | [github](https://github.com/cy94/sceneformer) | [project](https://xinpeng-wang.github.io/sceneformer/)
- [Learning 3D Scene Priors with 2D Supervision](https://arxiv.org/abs/2211.14157) | CVPR 2023 | [github](https://github.com/yinyunie/ScenePriors) | [project](https://yinyunie.github.io/sceneprior-page/)
- [Fast and Flexible Indoor Scene Synthesis via Deep Convolutional Generative Models](https://arxiv.org/abs/1811.12463) | CVPR 2019
- [Scene Synthesis via Uncertainty-Driven Attribute Synchronization](https://arxiv.org/abs/2108.13499) | ICCV 2021 | [github](https://github.com/brownvc/fast-synth)
- [ProcTHOR: Large-Scale Embodied AI Using Procedural Generation](https://procthor.allenai.org/), Deitke et al., NeurIPS 2022 |  [github](https://github.com/allenai/procthor) | [bibtex](./citations/procthor.txt)
- [SceneCraft: An LLM Agent for Synthesizing 3D Scenes as Blender Code](https://arxiv.org/abs/2403.01248) | ICML 2024
- .....



- [Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/abs/2310.03602), Fang et al., arxiv 2023 | [github](https://github.com/fangchuan/Ctrl-Room) | [bibtext](./citations/ctrlroom.txt) 
 
- [Ctrl-Room: Controllable Text-to-3D Room Meshes Generation with Layout Constraints](https://arxiv.org/abs/2310.03602), Fang et al., arxiv 2023 | [github](https://github.com/fangchuan/Ctrl-Room) | [bibtext](./citations/ctrlroom.txt) 
- [RoomDesigner: Encoding Anchor-latents for Style-consistent and Shape-compatible Indoor Scene Generation](https://arxiv.org/abs/2310.10027), Zhao et al., 3DV 2024 | [github](https://github.com/zhao-yiqun/RoomDesigner) | [bibtext](./citations/roomdesigner.txt)
- [ZeroNVS: Zero-Shot 360-Degree View Synthesis from a Single Real Image](https://arxiv.org/abs/2310.17994), Sargent et al., arxiv 2023 | [github](https://github.com/kylesargent/zeronvs) | [bibtext](./citations/zeroNVS.txt) 
- [GraphDreamer: Compositional 3D Scene Synthesis from Scene Graphs](https://arxiv.org/abs/2312.00093), Gao et al., arxiv 2023 | [github](https://github.com/GGGHSL/GraphDreamer) | [bibtext](./citations/graphdreamer.txt)
- [ControlRoom3D:Room Generation using Semantic Proxy Rooms](https://arxiv.org/abs/2312.05208), Schult et al., arxiv 2023 | [bibtext](./citations/controlroom3d.txt)
- [AnyHome: Open-Vocabulary Generation of Structured and Textured 3D Homes](https://arxiv.org/abs/2312.06644), Wen et al., arxiv 2023 | [bibtext](./citations/anyhome.txt)
- [Text2Immersion: Generative Immersive Scene with 3D Gaussians](https://arxiv.org/abs/2312.09242), Ouyang et al., arxiv 2023 | [bibtext](./citations/text2immersion.txt)
- [ShowRoom3D: Text to High-Quality 3D Room Generation Using 3D Priors](https://arxiv.org/abs/2312.13324), Mao et al., arxiv 2023 | [github](https://github.com/showlab/ShowRoom3D) | [bibtext](./citations/showRoom3d.txt)

- [3D-SceneDreamer: Text-Driven 3D-Consistent Scene Generation](https://arxiv.org/abs/2403.09439), Zhang et al., arxiv 2024 | [bibtext](./citations/3dscenedreamer.txt)
- [CAT3D: Create Anything in 3D with Multi-View Diffusion Models](https://arxiv.org/abs/2405.10314), Gao et al., arxiv 2024 | [bibtext](./citations/cat3d.txt)

</details>




<details open>
<summary>Scene Texture</summary>
- [Text2Scene: Text-driven Indoor Scene Stylization with Part-aware Details](https://arxiv.org/abs/2308.16880) | CVPR 2023

</details>


<details open>
<summary>2D Layout / General layout</summary>
- [LayoutTransformer: Layout Generation and Completion with Self-attention](https://arxiv.org/abs/2006.14615) | ICCV2021 | [github](https://github.com/kampta/DeepLayout) | [project](https://kampta.github.io/layout/)
-...
- [GRAF: Generative Radiance Fields for 3D-Aware Image Synthesis](https://arxiv.org/abs/2007.02442), Schwarz et al., NeurIPS 2020 | [github](https://github.com/autonomousvision/graf) | [bibtext](./citations/graf.txt)
- [ATISS: Autoregressive Transformers for Indoor Scene Synthesis](https://arxiv.org/abs/2110.03675), Paschalidou et al., NeurIPS 2021 | [github](https://github.com/nv-tlabs/atiss) | [bibtext](./citations/atiss.txt) 
- [GAUDI: A Neural Architect for Immersive 3D Scene Generation](https://arxiv.org/abs/2207.13751), Bautista et al., NeurIPS 2022 | [github](https://github.com/apple/ml-gaudi) | [bibtext](./citations/gaudi.txt)
- [NeuralField-LDM: Scene Generation with Hierarchical Latent Diffusion Models](https://arxiv.org/abs/2304.09787), Kim et al., CVPR 2023 | [bibtext](./citations/nerfldm.txt)
- [Pyramid Diffusion for Fine 3D Large Scene Generation](https://arxiv.org/abs/2311.12085), Liu et al., arxiv 2023 | [github](https://yuheng.ink/project-page/pyramid-discrete-diffusion/) | [bibtext](./citations/pyramid.txt) 
- [XCube: Large-Scale 3D Generative Modeling using Sparse Voxel Hierarchies](https://arxiv.org/abs/2312.03806), Ren et al., arxiv 2023 | [bibtex](./citations/xcube.txt)
- [DUSt3R: Geometric 3D Vision Made Easy](https://arxiv.org/abs/2312.14132), Wang et al., arxiv 2023 | [github](https://github.com/naver/dust3r) | [bibtext](./citations/dust3r.txt)


</details>


<details open>
<summary>Scene</summary>

- [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989), Höllein et al., ICCV 2023 | [github](https://github.com/lukasHoel/text2room) | [bibtext](./citations/text2room.txt) 
- [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588), Zhang et al., TVCG 2024 | [github](https://github.com/eckertzhang/Text2NeRF) | [bibtext](./citations/text2nerf.txt) 
- [CityDreamer: Compositional Generative Model of Unbounded 3D Cities](https://arxiv.org/abs/2309.00610), Xie et al., arxiv 2023 | [github](https://github.com/hzxie/city-dreamer) | [bibtext](./citations/cityDreamer.txt)
- [GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting](https://arxiv.org/abs/2311.14521), Chen et al., arxiv 2023 |  [github](https://github.com/buaacyw/GaussianEditor) | [bibtex](./citations/gaussianeditor.txt)
- [LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2311.13384), Chuang et al., arxiv 2023 | [github](https://github.com/luciddreamer-cvlab/LucidDreamer)  | [bibtext](./citations/luciddreamer-scene.txt)
- [GaussianEditor: Editing 3D Gaussians Delicately with Text Instructions](https://arxiv.org/abs/2311.16037), Fang et al., arxiv 2023 | [bibtex](./citations/gaussianEditor2.txt)
- [Gaussian Grouping: Segment and Edit Anything in 3D Scenes](https://arxiv.org/abs/2312.00732), Ye et al., arxiv 2023 |  [github](https://github.com/lkeab/gaussian-grouping) | [bibtex](./citations/gaussian-group.txt)
- [Inpaint3D: 3D Scene Content Generation using 2D Inpainting Diffusion](https://arxiv.org/abs/2312.03869), Prabhu et al., arxiv 2023 | [bibtext](./citations/inpaint3d.txt)
- [SIGNeRF: Scene Integrated Generation for Neural Radiance Fields](https://arxiv.org/abs/2401.01647), Dihlmann et al., arxiv 2024 |  [github](https://github.com/cgtuebingen/SIGNeRF) | [bibtex](./citations/sigNerf.txt)
- [Disentangled 3D Scene Generation with Layout Learning](https://arxiv.org/abs/2402.16936), Epstein, et al., arxiv 2024 | [bibtex](./citations/disentangled.txt)


</details>



<details open>
<summary>conditioned on Human Montion</summary>
- [Scene Synthesis from Human Motion](https://arxiv.org/abs/2301.01424) | SIGGRAPH Asia 2022 | [github](https://github.com/onestarYX/summon) | [project](https://lijiaman.github.io/projects/summon/)
- [Pose2Room: Understanding 3D Scenes from Human Activities](https://arxiv.org/abs/2112.03030) | ECCV 2022 | [github](https://arxiv.org/abs/2112.03030) | [project](https://yinyunie.github.io/pose2room-page/)
- [Human-centric Indoor Scene Synthesis Using Stochastic Grammar](https://arxiv.org/abs/1808.08473v1) | CVPR 2018
- [Rearrange Indoor Scenes for Human-Robot Co-Activity](https://arxiv.org/abs/2303.05676) | ICRA 2023 | [github](https://github.com/Rayckey/scene_coactivity) | [project](https://sites.google.com/view/coactivity)
- [MIME: Human-Aware 3D Scene Generation](https://arxiv.org/abs/2212.04360) | CVPR 2023 | [github](https://github.com/yhw-yhw/MIME) | [project](https://mime.is.tue.mpg.de/) 
</details>


<details open>
<summary>Condition on 2D Image</summary>

- [Total3DUnderstanding: Joint Layout, Object Pose and Mesh Reconstruction for Indoor Scenes from a Single Image](https://arxiv.org/abs/2002.12212) | CVPR 2020 | [github](https://github.com/GAP-LAB-CUHK-SZ/Total3DUnderstanding) | [project](https://yinyunie.github.io/Total3D/)
- [Holistic 3D Scene Understanding from a Single Image with Implicit Representation](https://arxiv.org/pdf/2103.06422) | CVPR 2021 | [github](https://github.com/chengzhag/Implicit3DUnderstanding) |[project](https://chengzhag.github.io/publication/im3d/)
</details>

<details open>
<summary>with Procedural </summary>
- [procthor]
- [infinigen]
</details>




## Benchmarks and Datasets
- Scene
- [Habitat Synthetic Scenes Dataset (HSSD):An Analysis of 3D Scene Scale and Realism Tradeoffs for ObjectGoal Navigation](https://arxiv.org/abs/2306.11290) | CVPR 2024 | [github](https://github.com/3dlg-hcvc/hssd/) | [project](https://3dlg-hcvc.github.io/hssd/)
- [3D-FRONT: 3D Furnished Rooms with layOuts and semaNTics](https://arxiv.org/abs/2011.09127) | ICCV 2021 | [project](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset)
- [ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes]

- Object
- [Objaverse-XL](https://objaverse.allenai.org/) | NeurIPS 2023 | [github](https://github.com/allenai/objaverse-xl)




## License 
Awesome-Indoor-Scene-Synthesis is released under the [MIT license](./LICENSE).

## Citation
If you find this project useful in your research, please consider citing:
```BibTeX

```

## Contact
contact: `yangyandan96@gmail.com`.  
