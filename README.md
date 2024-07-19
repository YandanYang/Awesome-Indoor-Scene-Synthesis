# Awesome-Indoor-Scene-Synthesis [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Indoor Scene Synthesis papers, inspired by [awesome-NeRF](https://github.com/awesome-NeRF/awesome-NeRF).


<img src="./asset/mvdream.gif" width="696px">
 


#### [How to submit a pull request?](https://github.com/hitcslj/Awesome-AIGC-3D/blob/main/how-to-PR.md)



## Table of Contents

- [Survey](#survey) 
- [Papers](#papers)
- [Benchmarks and Datasets](#Benchmarks-and-Datasets)
- [Talks](#talks)
- [Company](#company)
- [Implementations](#implementations)

## Survey

- [3D Generative Models: A Survey](https://arxiv.org/abs/2210.15663), Shi et al., arxiv 2022 | [bibtex](./citations/3d-generative-survey.txt)

## Papers

<details open>
<summary>3D Scene synthesis</summary>

- [I-Design: Personalized LLM Interior Designer](https://arxiv.org/abs/2404.02838), arxiv 2024 | [github](https://github.com/atcelen/IDesign/?tab=readme-ov-file) | [project](https://atcelen.github.io/I-Design/)
- [SceneWiz3D: Towards Text-guided 3D Scene Composition](https://arxiv.org/abs/2312.08885), Zhang et al., arxiv 2023 | [github](https://github.com/zqh0253/SceneWiz3D) | [bibtext](./citations/scenewiz3d.txt)
- [AnyHome]
- [PhyScene]
- [Holodeck: Language Guided Generation of 3D Embodied AI Environments](https://arxiv.org/abs/2312.09067) | [github](https://github.com/allenai/Holodeck) | [project](https://yueyang1996.github.io/holodeck/)
- [LayoutGPT: Compositional Visual Planning and Generation with Large Language Models](https://arxiv.org/abs/2305.15393), arxiv 2023| [github](https://github.com/weixi-feng/LayoutGPT) | [project](https://layoutgpt.github.io/)
- [GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting](https://arxiv.org/abs/2402.07207), Zhou et al., arxiv 2024 | [github](https://github.com/VDIGPKU/GALA3D) | [bibtext](./citations/gala3d.txt)
- [Learning 3D Scene Priors with 2D Supervision](https://arxiv.org/abs/2211.14157) | CVPR 2023 | [github](https://github.com/yinyunie/ScenePriors) | [peoject](https://yinyunie.github.io/sceneprior-page/)
- ATISS
- [DiffuScene: Denoising Diffusion Models for Generative Indoor Scene Synthesis](https://arxiv.org/abs/2303.14207) | CVPR 2024 | [github](https://github.com/tangjiapeng/DiffuScene) | [project](https://tangjiapeng.github.io/projects/DiffuScene/)
- Lay-A-Scene
- [Infinigen-Indoor
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
<summary>Dataset</summary>

- [Habitat Synthetic Scenes Dataset (HSSD):An Analysis of 3D Scene Scale and Realism Tradeoffs for ObjectGoal Navigation](https://arxiv.org/abs/2306.11290) | CVPR 2024 | [github](https://github.com/3dlg-hcvc/hssd/) | [project](https://3dlg-hcvc.github.io/hssd/)
- [3D-FRONT: 3D Furnished Rooms with layOuts and semaNTics](https://arxiv.org/abs/2011.09127) | ICCV 2021 | [project](https://tianchi.aliyun.com/specials/promotion/alibaba-3d-scene-dataset)

</details>

</details>

<details close>
<summary>2D Prior-based 3D Generative Methods</summary>

<details open>
<summary>Object</summary>

- [DreamFields: Zero-Shot Text-Guided Object Generation with Dream Fields](https://arxiv.org/abs/2112.01455), Jain et al., CVPR 2022 | [github](https://github.com/google-research/google-research/tree/master/dreamfields) | [bibtex](./citations/dreamfields.txt)

</details>


<details open>
<summary>Scene</summary>

- [Text2Light: Zero-Shot Text-Driven HDR Panorama Generation](https://arxiv.org/abs/2209.09898), Chen et al., TOG 2022 | [github](https://github.com/FrozenBurning/Text2Light) | [bibtext](./citations/text2light.txt) 
- [SceneScape: Text-Driven Consistent Scene Generation](https://arxiv.org/abs/2302.01133), Fridman et al., NeurIPS 2023 | [github](https://github.com/RafailFridman/SceneScape) | [bibtext](./citations/scenescape.txt) 
- [DiffuScene: Scene Graph Denoising Diffusion Probabilistic Model for Generative Indoor Scene Synthesis](https://arxiv.org/abs/2303.14207), Tang et al., arxiv 2023 | [github](https://github.com/tangjiapeng/DiffuScene) | [bibtext](./citations/diffuscene.txt) 
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
<summary>Human Avatar</summary>

- [AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars](https://arxiv.org/abs/2205.08535), Hong et al., SIGGRAPH 2022 |  [github](https://github.com/hongfz16/AvatarCLIP) | [bibtex](./citations/teca.txt)
- [DreamWaltz: Make a Scene with Complex 3D Animatable Avatars](https://arxiv.org/abs/2305.12529), Huang et al., NeurIPS 2023 |  [github](https://github.com/IDEA-Research/DreamWaltz) | [bibtex](./citations/dreamwaltz.txt)
- [DreamHuman: Animatable 3D Avatars from Text](https://arxiv.org/abs/2306.09329), Wang et al., arxiv 2023 | [bibtex](./citations/dreamhuman.txt)
- [TECA: Text-Guided Generation and Editing of Compositional 3D Avatars](https://arxiv.org/abs/2309.07125), Zhang et al., arxiv 2023 |  [github](https://github.com/HaoZhang990127/TECA) | [bibtex](./citations/teca.txt)
- [HumanGaussian: Text-Driven 3D Human Generation with Gaussian Splatting](https://arxiv.org/abs/2311.17061), Liu et al., arxiv 2023 |  [github](https://github.com/alvinliu0/HumanGaussian) | [bibtex](./citations/humangaussian.txt)
- [HeadArtist: Text-conditioned 3D Head Generation with Self Score Distillation](https://arxiv.org/abs/2312.07539), Liu et al., arxiv 2023 | [bibtex](./citations/headArtist.txt)
- [3DGS-Avatar: Animatable Avatars via Deformable 3D Gaussian Splatting](https://arxiv.org/abs/2312.09228), Qian et al., arxiv 2023 |  [github](https://github.com/mikeqzy/3dgs-avatar-release) | [bibtex](./citations/3dgsAvatar.txt)


</details>


</details>


<details close>
<summary>Hybrid 3D Generative Methods</summary>

<details open>
<summary>Object</summary>

- [SketchDream: Sketch-based Text-to-3D Generation and Editing](https://arxiv.org/abs/2405.06461), Liu et al., SIGGRAPH 2024 | [bibtex](./citations/sketchdream.txt)


</details>


<details open>
<summary>conditioned on Human Montion</summary>
- [Scene Synthesis from Human Motion](https://arxiv.org/abs/2301.01424) | SIGGRAPH Asia 2022 | [github](https://github.com/onestarYX/summon) | [project](https://lijiaman.github.io/projects/summon/)
- [Pose2Room: Understanding 3D Scenes from Human Activities](https://arxiv.org/abs/2112.03030) | ECCV 2022 | [github](https://arxiv.org/abs/2112.03030) | [project](https://yinyunie.github.io/pose2room-page/)
- [Human-centric Indoor Scene Synthesis Using Stochastic Grammar](https://arxiv.org/abs/1808.08473v1) | CVPR 2018
- [Rearrange Indoor Scenes for Human-Robot Co-Activity](https://arxiv.org/abs/2303.05676) | ICRA 2023 | [github](https://github.com/Rayckey/scene_coactivity) | [project](https://sites.google.com/view/coactivity)
</details>


</details>

<details open>
<summary>Texture</summary>

- [StyleMesh: Style Transfer for Indoor 3D Scene Reconstructions](https://arxiv.org/abs/2112.01530), Höllein et al., CVPR 2022 | [github](https://github.com/lukasHoel/stylemesh) | [bibtex](./citations/stylemesh.txt)

</details>

<details open>
<summary>Procedural 3D Modeling</summary>

- [ProcTHOR: Large-Scale Embodied AI Using Procedural Generation](https://procthor.allenai.org/), Deitke et al., NeurIPS 2022 |  [github](https://github.com/allenai/procthor) | [bibtex](./citations/procthor.txt)
- [3D-GPT: Procedural 3D Modeling with Large Language Models](https://arxiv.org/abs/2310.12945), Sun et al., arxiv 2023 |  [github](https://github.com/Chuny1/3DGPT) | [bibtex](./citations/3dgpt.txt)

</details>


<details open>
<summary>3D Representation</summary>

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934), Mildenhall et al., ECCV 2020 | [github](https://github.com/bmild/nerf) | [bibtex](./citations/nerf.txt)

</details>

</details>


## Benchmarks and Datasets

- [Objaverse-XL](https://objaverse.allenai.org/), Deitke et al., NeurIPS 2023 | [github](https://github.com/allenai/objaverse-xl) | [bibtext](./citations/objaverse-xl.txt) 

## Talks
- [AI 3D Generation, explained](https://www.youtube.com/watch?v=EoAm1yZR-ao), Jia-Bin Huang


## Company
- [TRIPOAI](https://www.tripo3d.ai/)



## Implementations

- [Threestudio](https://github.com/threestudio-project/threestudio), Yuan-Chen Guo, 2023 | [bibtex](./citations/threestudio.txt)

## License 
Awesome-Indoor-Scene-Synthesis is released under the [MIT license](./LICENSE).

## Citation
If you find this project useful in your research, please consider citing:
```BibTeX

```

## Contact
contact: `yangyandan96@gmail.com`.  
