[English](README.md)<br>**简体中文 · English–Chinese**

> 本中英对照版从上游 `README.md` 派生；原始英文版保持不变，以便后续同步。

<div align="center">
  <h1> Awesome Spatial VLMs 空间视觉—语言模型精选资源 </h1>
  <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge" style="vertical-align: middle;"> </a> <a href="https://github.com/DishengLL/Awesome-Spatial-VLMs/commits/main/"> <img src="https://img.shields.io/github/last-commit/DishengLL/Awesome-Spatial-VLMs" alt="GitHub Last Commit" style="vertical-align: middle;"></a>
</div>

<p align="center">
  <video src="https://github.com/DishengLL/Awesome-Spatial-VLMs/raw/main/spatial_survey.mov" width="88%" controls autoplay muted loop>
    Your browser does not support the video tag.<br>你的浏览器不支持 video 标签。
  </video>
</p>

<!-- <h1 align="center" style="font-size: 1.7rem">
  🚀 Awesome Spatial VLMs
  <a href="https://github.com/sindresorhus/awesome">
    <img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome Badge" style="vertical-align: middle;">
  </a>
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/commits/main/">
    <img src="https://img.shields.io/github/last-commit/vulab-AI/Awesome-Spatial-VLMs" alt="GitHub Last Commit" style="vertical-align: middle;">
  </a>
</h1> -->
<!-- 
  <p align="center">
    <a href="https://scholar.google.com/citations?user=xlIBwREAAAAJ&hl=en">Disheng Liu</a>,
    <a href="https://jiagengliu02.github.io/">Tuo Liang</a>,
    <a href="https://scholar.google.com/citations?user=oV8sqb0AAAAJ&hl=zh-CN">Zhe Hu</a>,
    <a href="https://scholar.google.com/citations?user=7CLFLX0AAAAJ&hl=en">Jierui Peng</a>,
    <a href="https://yiren-lu.com/">Yiren Lu</a>,
    <a href="https://sites.google.com/view/homepage-of-yi-xu">Yi Xu</a>,
    <a href="https://www1.ece.neu.edu/~yunfu/">Yun Fu</a>,
    <a href="https://yin-yu.github.io/">Yu Yin</a>
  </p> -->

>A curated hub for Spatial Intelligence in Vision-Language Models.   
>面向视觉—语言模型空间智能研究的精选资源中心。<br>
>Actively maintained—watch for updates, benchmark your VLM with our evaluation code, and consider starring 🌟 and sharing if helpful.
>本仓库持续维护中——欢迎关注后续更新，使用我们的评测代码测试你的 VLM；如果这些内容对你有帮助，也欢迎点亮 Star 🌟 并分享。

This repository is the official, community-maintained resource for our survey paper:  **Spatial Intelligence in Vision-Language Models: A Comprehensive Survey**.  
本仓库是我们的综述论文 **《视觉—语言模型中的空间智能：一项综合综述》** 的官方社区维护资源。<br>
We host an official website for streamlined navigation and well-organized resources: 👉 [Website 🔗](https://dishengll.github.io/Awesome-Spatial-VLMs/)
我们还提供了一个官方网页，以便更高效地浏览经过系统整理的资源：👉 [网站 🔗](https://dishengll.github.io/Awesome-Spatial-VLMs/)

<p align="center">
  <a href="./website.png">
    <img src="./website.png" alt="Cover Image" width="88%">
  </a>
</p>


<p align="center">
<a href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.176231405.57942913/v2">
  <img src="https://img.shields.io/badge/TechRxiv-Preprint-00629B?style=flat&logo=ieee&logoColor=white" alt="TechRxiv"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/Spatial_VLM_survey.pdf"><img src="https://img.shields.io/badge/Paper-PDF-0066CC?style=flat&logo=adobeacrobatreader&logoColor=white" alt="Paper PDF"></a>&nbsp;
  <a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://img.shields.io/badge/Evaluated-Dataset-yellow?style=flat&logo=huggingface&logoColor=yellow" alt="Evaluated Data"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/evaluation/README.md"><img src="https://img.shields.io/badge/Evaluation-Code-black?style=flat&logo=github&logoColor=black" alt="Evaluation Code"></a>
  <br/>
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Dataset_SVQA.md"><img src="https://img.shields.io/badge/Training-24%20datasets-teal?style=flat"alt="Training - 24 datasets"></a>&nbsp;
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Benchmark_SVQA.md"><img src="https://img.shields.io/badge/Evaluation-54%20benchmarks-orange?style=flat" alt="Evaluation - 54 benchmarks"></a>&nbsp;
</p>

🤝 This repository will be continuously updated, and we warmly invite contributions. **If you have a paper, dataset, or model to add, please submit a pull request or open an issue for discussion.**
<br>🤝 本仓库将持续更新，也诚挚欢迎社区贡献。**如果你希望补充论文、数据集或模型，请提交 Pull Request，或创建 Issue 参与讨论。**


## Table of Contents 目录
- [Table of Contents 目录](#table-of-contents)
- [Overview 概览](#overview)
- [🚀 Awesome Papers 精选论文](#-awesome-papers)
  - [Training-Free Prompting 免训练提示方法](#training-free-prompting)
  - [Model-Centric Enhancements 模型中心增强](#model-centric-enhancements)
  - [Explicit 2D Information Injection 显式二维信息注入](#explicit-2d-information-injection)
  - [3D Information Enhancement 三维信息增强](#3d-information-enhancement)
  - [Data-Centric Spatial Enhancement 数据中心空间能力增强](#data-centric-spatial-enhancement)
- [📚 Datasets and Benchmarks 数据集与基准](#-datasets-and-benchmarks)
  - [Spatially-Oriented Training Corpora 面向空间能力的训练语料](#spatially-oriented-training-corpora)
  - [Evaluation Benchmarks 评估基准](#evaluation-benchmarks)
- [🏆 Spatial VLM Leaderboard \& Evaluation Toolkit 空间视觉—语言模型排行榜与评估工具包](#-spatial-vlm-leaderboard--evaluation-toolkit)
  - [🏅 Main Leaderboard 主排行榜](#-main-leaderboard)
  - [🧑‍🔬 How to Evaluate Your Model 如何评估你的模型](#-how-to-evaluate-your-model)
- [Citation 引用](#citation)


## Overview 概览
This repository uses the framework from our survey paper to systematically organize the field of Spatial Intelligence in VLMs.
<br>本仓库采用综述论文提出的框架，系统梳理视觉—语言模型中的空间智能研究。
- **The “What”: A Cognitive Hierarchy<br>“是什么”：认知层级** 🧩  
  We define spatial intelligence as a 3-level hierarchy, and group tasks, datasets, and benchmarks by required capability:  
  我们将空间智能划分为三个层级，并按照所需能力对任务、数据集和基准进行归类：<br>
  **L1** *Perception* of intrinsic 3D attributes (e.g., size, orientation) &rarr; **L2** relational *Understanding* &rarr; **L3** *Extrapolation* (e.g., hidden-state inference, future prediction).
  <br>**L1** 对固有三维属性的*感知*（如尺寸、朝向）&rarr; **L2** 对空间关系的*理解* &rarr; **L3** *外推*（如隐藏状态推断、未来预测）。
- **The “How”: A Taxonomy of Methods<br>“怎么做”：方法分类体系** 🚀  
  Methods are organized into five families, giving you a clear map of the current landscape. See details in [🚀 Awesome Papers 精选论文](#-awesome-papers).
  <br>我们将方法划分为五大类，从而清晰呈现当前研究版图。详见[🚀 Awesome Papers 精选论文](#-awesome-papers)。
- **Where We Are: Evaluation Results and Toolkit<br>现状：评估结果与工具包** 🏆  
  See how current models perform! 
  <br>了解当前模型的表现！
  - **Standardized Leaderboard:** We report results for **37+ VLMs** across all L1/L2/L3 tasks.
    <br>**标准化排行榜：** 我们报告了 **37+ 个 VLM** 在 L1/L2/L3 各层级任务上的评测结果。
  - **Open Evaluation Toolkit:** Reproduce our protocols and **evaluate your own models** under the same settings.
    <br>**开放评测工具包：** 复现我们的评测流程，并在相同设置下**评估你自己的模型**。

<div align='center'><img src="./samples/outline.jpg"  alt="Overview Diagram" width="95%"/></div>

  <!-- - **L1: Spatial Perception:** Recognizing individual objects and their intrinsic 3D attributes (e.g., size, orientation, 3D segmentation).
  - **L2: Spatial Understanding:** Reasoning about the extrinsic, relational properties among multiple objects (e.g., "the dog to the left of the cat").
  - **L3: Spatial Extrapolation:** Inferring hidden states, predicting future configurations, or reasoning from a situated perspective (e.g., mental rotation, pathfinding). -->


## 🚀 Awesome Papers 精选论文
### Training-Free Prompting 免训练提示方法
<a id="textual-prompting-methods"></a>
<details>
  <summary><b>Textual Prompting Methods<br>文本提示方法</b></summary>

  - [CoRR2025] SoFar: Language-Grounded Orientation Bridges Spatial Reasoning and Object Manipulation<br>到目前为止：以语言为基础的方向连接空间推理和对象操作 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2502.13143) [[code]](https://github.com/qizekun/SoFar);

  - [CVPR2024] Compositional Chain-of-Thought Prompting for Large Multimodal Models<br>大型多模态模型的组合思维链提示 (_University of California, Berkeley_) [[paper]](https://arxiv.org/pdf/2311.17076) [[code]](https://github.com/chancharikmitra/CCoT);

  - [EMNLP2024] Reasoning Paths with Reference Objects Elicit Quantitative Spatial Reasoning in Large Vision-Language Models<br>具有参考对象的推理路径引发大型视觉—语言模型中的定量空间推理 (_University of Toronto_) [[paper]](https://arxiv.org/abs/2409.09788) [[code]](https://github.com/andrewliao11/Q-Spatial-Bench-code);

  - [NeurIPS2024] SpatialPIN: Enhancing Spatial Reasoning Capabilities of Vision-Language Models through Prompting and Interacting 3D Priors<br>SpatialPIN：通过提示和交互 3D 先验增强视觉—语言模型的空间推理能力 (_University of Oxford_) [[paper]](https://arxiv.org/pdf/2403.13438) [[code]](https://github.com/dannymcy/zeroshot_task_hallucination_code);

  - [CoRR2023] Enhancing the Spatial Awareness Capability of Multi-Modal Large Language Model<br>增强多模态大语言模型的空间感知能力 (_Peking University_) [[paper]](https://arxiv.org/pdf/2310.20357);

</details>

<a id="visual-prompting-methods"></a>
<details>
  <summary><b>Visual Prompting Methods<br>视觉提示方法</b></summary>

  - [arXiv2026] Think3D: Thinking with Space for Spatial Reasoning<br>Think3D：用空间思考进行空间推理 (_Dalian University of Technology_) [[paper]](https://arxiv.org/pdf/2601.13029) [[code]](https://github.com/zhangzaibin/spagent) [[checkpoint]](https://huggingface.co/jialianjie/SPAgent-4B);

  - [arXiv2025] Abstract 3D Perception for Spatial Intelligence in Vision-Language Models<br>视觉—语言模型中空间智能的抽象 3D 感知 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2511.10946)

  - [CVPR2025] Coarse Correspondences Boost Spatial-Temporal Reasoning in Multimodal Language Model<br>粗略对应促进多模态语言模型中的时空推理 (_University of Washington_) [[paper]](https://arxiv.org/pdf/2408.00754);

  - [NeurIPS2025] Mindjourney: Test-time scaling with world models for spatial reasoning<br>Mindjourney：使用空间推理的世界模型进行测试时间缩放 (_UMass Amherst_) [[paper]](https://arxiv.org/pdf/2507.12508) [[code]](https://github.com/UMass-Embodied-AGI/MindJourney);

  - [Neurocomputing2025] 3DAxisPrompt: Promoting the 3d grounding and reasoning in gpt-4o<br>3DAxisPrompt：促进gpt-4o中的3D 定位和推理 (_Shanghai AI Lab_) [[paper]](https://arxiv.org/pdf/2503.13185);

  - [NeurIPS2025] See&Trek: Training-Free Spatial Prompting for Multimodal Large Language Model<br>See&Trek：多模态大语言模型的免训练空间提示 (_HKUST(GZ)_) [[paper]](https://arxiv.org/pdf/2509.16087) [[code]](https://github.com/Hoantrbl/SeeTrek?tab=readme-ov-file);

  - [arXiv2024] I Know About “Up”! Enhancing Spatial Reasoning in Visual Language Models Through 3D Reconstruction<br>我知道“向上”！通过 3D 重建增强视觉—语言模型的空间推理 (_Guangdong Polytechnic Normal University_) [[paper]](https://arxiv.org/pdf/2407.14133);

  - [arXiv2023] Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V<br>标记组提示在 GPT-4V 中释放非凡的视觉定位 (_Microsoft Research, Redmond_) [[paper]](https://arxiv.org/pdf/2310.11441) [[code]](https://github.com/microsoft/SoM);

  - [NeurIPS2023] Fine-Grained Visual Prompting<br>细粒度的视觉提示 (_Nanjing University of Science and Technology_) [[paper]](https://arxiv.org/pdf/2306.04356) [[code]](https://github.com/ylingfeng/FGVP);

  <!-- New paper, excluded in survey -->

</details>

<a id="hybrid-prompting"></a>

<details>
  <summary><b>Hybrid Prompting<br>混合提示方法</b></summary>
  - [arXiv2026] CoV: Chain-of-View Prompting for Spatial Reasoning<br>CoV：促进空间推理的视图链 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2601.05172) [[code]](https://github.com/ziplab/CoV?tab=readme-ov-file);

  - [arXiv2025] SpatialPrompting: Keyframe-driven Zero-Shot Spatial Reasoning with Off-the-Shelf Multimodal Large Language Models<br>SpatialPrompting：使用现成的多模态大语言模型进行关键帧驱动的零样本空间推理 (_Toyota Central R&D Labs_) [[paper]](https://arxiv.org/pdf/2505.04911v1);

  - [COLING2025] Scaffolding coordinates to promote vision-language coordination in large multi-modal models<br>脚手架坐标促进大型多模态模型中的视觉—语言协调 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2402.12058) [[code]](https://github.com/THUNLP-MT/Scaffold);

  - [CVPR2025] SeeGround: See and Ground for Zero-Shot Open-Vocabulary 3D Visual Grounding<br>SeeGround：零样本开放词汇 3D 视觉定位的查看和接地 (_HKUST(GZ)_) [[paper]](https://arxiv.org/pdf/2412.04383) [[code]](https://github.com/iris0329/SeeGround);

  - [arXiv2024] Image-of-Thought Prompting for Visual Reasoning Refinement in Multimodal Large Language Models<br>多模态大语言模型中视觉推理细化的思维图像提示 (_Westlake University_) [[paper]](https://arxiv.org/pdf/2405.13872);

  - [NeurIPS2024] Mind's Eye of LLMs: Visualization-of-Thought Elicits Spatial Reasoning in Large Language Models<br>大语言模型的心灵之眼：思维可视化在大型语言模型中引发空间推理 (_Microsoft Research_) [[paper]](https://proceedings.neurips.cc/paper_files/paper/2024/file/a45296e83b19f656392e0130d9e53cb1-Paper-Conference.pdf) [[code]](https://github.com/microsoft/visualization-of-thought/);

  - [NeurIPS2024] Visual SKETCHPAD: Sketching as a visual chain of thought for multimodal language models<br>Visual SKETCHPAD：草图作为多模态语言模型的视觉思维链 (_University of Washington_) [[paper]](https://arxiv.org/pdf/2406.09403) [[code]](https://github.com/Yushi-Hu/VisualSketchpad);



</details>

---

### Model-Centric Enhancements 模型中心增强
<a id="advanced-training-strategies"></a>
<details>
  <summary><b>Advanced Training Strategies<br>高级训练策略</b></summary>

  - [AAAI2026] SIFThinker: Spatially-Aware Image Focus for Visual Reasoning<br>SIFThinker：用于视觉推理的空间感知图像聚焦 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2508.06259) [[code]](https://github.com/zhangquanchen/SIFThinker?tab=readme-ov-file);

  - [arXiv2025] SpatialCoT: Advancing Spatial Reasoning through Coordinate Alignment and Chain-of-Thought for Embodied Task Planning<br>SpatialCoT：通过坐标对齐和具体任务规划的思维链推进空间推理 (_Huawei Noah's Ark Lab_) [[paper]](https://arxiv.org/pdf/2501.10074);

  - [arXiv2025] Enhancing Spatial Reasoning through Visual and Textual Thinking<br>通过视觉和文本思维增强空间推理 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2507.20529);

  - [arXiv2025] SpaceTools: Tool-Augmented Spatial Reasoning via Double Interactive RL<br>SpaceTools：通过双交互式强化学习进行工具增强空间推理 (_Umich_) [[paper]](https://arxiv.org/pdf/2512.04069)

  - [arXiv2025] SpaceR: Reinforcing MLLMs in Video Spatial Reasoning<br>SpaceR：强化视频空间推理中的 多模态大语言模型 (_Peking University_) [[paper]](https://arxiv.org/pdf/2504.01805v2) [[code]](https://github.com/OuyangKun10/SpaceR?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/RUBBISHLIKE/SpaceR);

  - [arXiv2025] ViLaSR: Reinforcing Spatial Reasoning in Vision-Language Models with Interwoven Thinking and Visual Drawing<br>ViLaSR：通过交织思维和视觉绘图强化视觉—语言模型中的空间推理 (_Institute of Automation, Chinese Academy of Sciences_) [[paper]](https://arxiv.org/abs/2506.09965) [[code]](https://github.com/AntResearchNLP/ViLaSR) [[checkpoint]](https://huggingface.co/inclusionAI/ViLaSR/tree/main);

  - [arXiv2025] M2-Reasoning: Empowering MLLMs with Unified General and Spatial Reasoning<br>M2-推理：为 多模态大语言模型 提供统一的通用推理和空间推理 (_Inclusion AI, Ant Group_) [[paper]](https://arxiv.org/pdf/2507.08306) [[code]](https://github.com/inclusionAI/M2-Reasoning) [[checkpoint]](https://huggingface.co/inclusionAI/M2-Reasoning);

  - [arXiv2025] Improved Visual-Spatial Reasoning via R1-Zero-Like Training<br>通过 R1 类零训练改进视觉空间推理 (_Shanghai Jiao Tong University_) [[paper]](https://arxiv.org/pdf/2504.00883) [[code]](https://github.com/zhijie-group/R1-Zero-VSI)

  - [arXiv2025] SVQA-R1: Reinforcing Spatial Reasoning in MLLMs via View-Consistent Reward Optimization<br>SVQA-R1：通过视图一致奖励优化强化 多模态大语言模型 中的空间推理 (_Stony Brook University_) [[paper]](https://arxiv.org/pdf/2506.01371);

  - [arXiv2025] Embodied-R: Collaborative Framework for Activating Embodied Spatial Reasoning in Foundation Models via Reinforcement Learning<br>Embodied-R：通过强化学习激活基础模型中的体现空间推理的协作框架 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2504.12680) [[code]](https://github.com/EmbodiedCity/Embodied-R.code) [[checkpoint]](https://huggingface.co/EmbodiedCity/Embodied-R);

  - [arXiv2025] SpatialLadder: Progressive Training for Spatial Reasoning in Vision-Language Models<br>SpatialLadder：视觉—语言模型中空间推理的渐进训练 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2510.08531) [[code]](https://github.com/zju-real/SpatialLadder) [[checkpoint]](https://huggingface.co/hongxingli/SpatialLadder-3B);

  - [arXiv2025] MetaSpatial: Reinforcing 3D Spatial Reasoning in VLMs for the Metaverse<br>MetaSpatial：在 Metaverse 的 VLM 中强化 3D 空间推理 (_Northwestern University_) [[paper]](https://arxiv.org/pdf/2503.18470) [[code]](https://github.com/PzySeere/MetaSpatial);

  - [arXiv2025] SpatialThinker: Reinforcing 3D Reasoning in Multimodal LLMs via Spatial Rewards<br>SpatialThinker：通过空间奖励强化多模态大语言模型中的 3D 推理 (_University of Oxford_) [[paper]](https://arxiv.org/pdf/2511.07403) [[code]](https://github.com/hunarbatra/SpatialThinker) [[checkpoint]](https://huggingface.co/collections/OX-PIXL/spatialthinker);

  - [arXiv2025] Think with 3D: Geometric Imagination Grounded Spatial Reasoning from Limited Views<br>用 3D 思考：基于几何想象力的有限视角空间推理 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2510.18632) [[code]](https://github.com/zhangquanchen/3DThinker)

  - [arXiv2025] SpaceMind: Camera-Guided Modality Fusion for Spatial Reasoning in Vision-Language Models<br>SpaceMind：用于视觉—语言模型中空间推理的相机引导模态融合 (_Huawei_) [[paper]](https://arxiv.org/pdf/2511.23075)

  - [arXiv2025] DepthLM: Metric Depth From Vision Language Models<br>DepthLM：视觉—语言模型的度量深度 (_Meta_) [[paper]](https://arxiv.org/pdf/2509.25413#page=4.00) [[code]](https://github.com/facebookresearch/DepthLM_Official) [[checkpoint]](https://huggingface.co/facebook/DepthLM)

  - [CVPR2025] Perception Tokens Enhance Visual Reasoning in Multimodal Language Models<br>感知标记增强多模态语言模型中的视觉推理 (_University of Washington_) [[paper]](https://arxiv.org/pdf/2412.03548v1) [[code]](https://github.com/mahtabbigverdi/Aurora-perception) [[checkpoint]](https://drive.google.com/file/d/1r7WYQWYA6VDpzfxPIHP1zEUgBYQmwNIj/view);

  - [ICLR2025] Ross: Reconstructive Visual Instruction Tuning<br>罗斯：重建视觉指令调整 (_Institute of Automation, Chinese Academy of Sciences_) [[paper]](https://arxiv.org/pdf/2410.09575) [[code]](https://github.com/haochen-wang409/ross) [[checkpoint]](https://huggingface.co/HaochenWang/ross-qwen2-7b);

  - [ICLR2025] Language-Image Models with 3D Understanding (Cube-LLM)<br>具有 3D 理解的语言图像模型 (Cube-大语言模型) (_UT Austin_) [[paper]](https://arxiv.org/pdf/2405.03685);

  - [ICLR2025] Locality Alignment Improves Vision-Language Models<br>局部性对齐改进了视觉—语言模型 (_Stanford University_) [[paper]](https://arxiv.org/pdf/2410.11087) [[code]](https://github.com/iancovert/locality-alignment/?tab=readme-ov-file);

  - [ICML2025] Imagine while Reasoning in Space: Multimodal Visualization-of-Thought<br>在空间中推理的同时想象：思维的多模态可视化 (_Microsoft Research_) [[paper]](https://arxiv.org/pdf/2501.07542) [[code]](https://github.com/chengzu-li/MVoT);

  - [NeurIPS2025] SpatialReasoner: Towards Explicit and Generalizable 3D Spatial Reasoning,<br>SpatialReasoner：迈向显式且可推广的 3D 空间推理， (_Johns Hopkins University_) [[paper]](https://arxiv.org/pdf/2504.20024) [[code]](https://github.com/johnson111788/SpatialReasoner) [[checkpoint]](https://huggingface.co/collections/ccvl/spatialreasoner-68114caec81774edbf1781d3);

  - [NeurIPS2025] Fine-Grained Preference Optimization Improves Spatial Reasoning in VLMs<br>细粒度偏好优化改善 VLM 中的空间推理 (_UIUC_) [[paper]](https://arxiv.org/pdf/2506.21656);

  - [arXiv2023] What Makes for Good Visual Tokenizers for Large Language Models<br>大型语言模型的良好视觉分词器的要素是什么 (_National University of Singapore 2ARC Lab_) [[paper]](https://arxiv.org/pdf/2305.12223) [[code]](https://github.com/TencentARC/GVT) [[checkpoint]](https://github.com/TencentARC/GVT/tree/master/gvt);

  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
    <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->
  <!-- New paper, excluded in survey -->
    <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
    <!-- ![RL-based](https://img.shields.io/badge/RL--based-blue?) -->
    </details>

<a id="architectural-enhancements"></a>
<details>
  <summary><b>Architectural Enhancements<br>架构增强</b></summary>

  - [arXiv2025] Cambrian-S: Towards Spatial Supersensing in Video<br>Cambrian-S：迈向视频中的空间超感 (_New York University_) [[paper]](https://arxiv.org/pdf/2511.04670) [[code]](https://github.com/cambrian-mllm/cambrian-s) [[checkpoint]](https://huggingface.co/collections/nyu-visionx/cambrian-s-models);

  - [ICML2025] Why is Spatial Reasoning Hard for VLMs? An Attention Mechanism Perspective on Focus Areas<br>为什么空间推理对于 VLM 来说很难？关注机制视角下的重点领域 (_City University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2503.01773) [[code]](https://github.com/shiqichen17/AdaptVis) [[checkpoint]](https://github.com/shiqichen17/AdaptVis);

  - [CVPR2024] Honeybee: Locality Enhanced Projector for Multimodal LLM<br>Honeybee：多模态大语言模型的局部增强投影仪 (_Kakao Brain_) [[paper]](https://arxiv.org/pdf/2312.06742) [[code]](https://github.com/khanrc/honeybee) [[checkpoint]](https://github.com/khanrc/honeybee);

  - [ECCV2024] Contrastive Region Guidance: Improving Grounding in Vision-Language Models without Training<br>对比区域指导：无需训练即可改善视觉—语言模型的基础 (_UNC_) [[paper]](https://arxiv.org/pdf/2403.02325) [[code]](https://github.com/meetdavidwan/crg) [[checkpoint]](https://github.com/meetdavidwan/crg);

  - [EMNLP2024] To Preserve or To Compress: An In-Depth Study of Connector Selection in Multimodal Large Language Models<br>保留还是压缩：多模态大语言模型中连接器选择的深入研究 (_Digital Twin Institute, Eastern Institute of Technology, China_) [[paper]](https://arxiv.org/pdf/2410.06765v1) [[code]](https://github.com/EIT-NLP/Connector-Selection-for-MLLM);

  - [NeurIPS2024] Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLM<br>Cambrian-1：完全开放、以视觉为中心的多模态大语言模型探索 (_New York University_) [[paper]](https://arxiv.org/pdf/2406.16860) [[code]](https://github.com/cambrian-mllm/cambrian) [[checkpoint]](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23c);

  <!-- New paper, excluded in survey -->
</details>

<a id="encoder-level-improvements"></a>
<details>
  <summary><b>Encoder-Level Improvements<br>编码器层级改进</b></summary>

  - [arXiv2025] Introducing Visual Perception Token into Multimodal Large Language Model<br>将视觉感知令牌引入多模态大语言模型 (_National University of Singapore_) [[paper]](https://arxiv.org/pdf/2502.17425) [[code]](https://github.com/yu-rp/VisualPerceptionToken?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/collections/rp-yu/vpt-models-67b6afdc8679a05a2876f07a);

  - [arXiv2025] G2VLM: Geometry Grounded Vision Language Model with Unified 3D Reconstruction and Spatial Reasoning<br>G2VLM：具有统一 3D 重建和空间推理的几何基础视觉—语言模型 (_Shanghai AI Lab_) [[paper]](https://arxiv.org/pdf/2511.21688) [[code]](https://github.com/InternRobotics/G2VLM) [[checkpoint]](https://huggingface.co/InternRobotics/G2VLM-2B-MoT)

  - [CVPR2025] SpatialCLIP: Learning 3D-aware Image Representations from Spatially Discriminative Language<br>SpatialCLIP：从空间判别语言学习 3D 感知图像表示 (_Zhejiang University_) [[paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Wang_SpatialCLIP_Learning_3D-aware_Image_Representations_from_Spatially_Discriminative_Language_CVPR_2025_paper.pdf) [[code]](https://github.com/SpatialVision/Spatial-CLIP);

  - [CVPR2025] SpatialLLM: A Compound 3D-Informed Design towards Spatially-Intelligent Large Multimodal Models<br>Spatial大语言模型：针对空间智能大型多模态模型的复合 3D 设计 (_Johns Hopkins University_) [[paper]](https://arxiv.org/pdf/2505.00788) [[code]](https://3d-spatial-reasoning.github.io/spatial-llm/#public);

  - [CVPR2025] Argus: A Compact and Versatile Foundation Model for Vision<br>Argus：紧凑且多功能的视觉定位模型 (_University of Illinois Urbana-Champaign_) [[paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhuang_Argus_A_Compact_and_Versatile_Foundation_Model_for_Vision_CVPR_2025_paper.pdf);

  - [ICLR2025] Eagle 2: Building Post-Training Data Strategies from Scratch for Frontier Vision-Language Models<br>Eagle 2：从头开始构建前沿视觉—语言模型的训练后数据策略 (_NVIDIA_) [[paper]](https://arxiv.org/pdf/2501.14818) [[code]](https://github.com/NVlabs/EAGLE?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/nvidia/Eagle2.5-8B);

  - [IJCAI2025] Incorporating Visual Experts to Resolve the Information Loss in Multimodal Large Language Models<br>结合视觉专家解决多模态大语言模型中的信息丢失问题 (_Huawei_) [[paper]](https://arxiv.org/pdf/2401.03105);

  - [ICML2024] Prismatic VLMs: Investigating the Design Space of Visually-Conditioned Language Models<br>Prismatic VLM：研究视觉条件语言模型的设计空间 (_Stanford University_) [[paper]](https://arxiv.org/pdf/2402.07865) [[code]](https://github.com/TRI-ML/prismatic-vlms?tab=readme-ov-file#pretrained-models) [[checkpoint]](https://github.com/TRI-ML/prismatic-vlms);

  - [NeurIPS2024] Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLM<br>Cambrian-1：完全开放、以视觉为中心的多模态大语言模型探索 (_New York University_) [[paper]](https://arxiv.org/pdf/2406.16860) [[code]](https://github.com/cambrian-mllm/cambrian) [[checkpoint]](https://huggingface.co/collections/nyu-visionx/cambrian-1-models-666fa7116d5420e514b0f23c);

  <!-- New paper, excluded in survey -->
</details>

--------

### Explicit 2D Information Injection 显式二维信息注入
<a id="object-region-guidance"></a>
<details>
  <summary><b>Object Region Guidance<br>目标区域引导</b></summary>

  - [arXiv2025] Lyrics: Boosting Fine-grained Language-Vision Alignment and Comprehension via Semantic-aware Visual Objects<br>歌词：通过语义感知的视觉对象促进细粒度的语言视觉对齐和理解 (_International Digital Economy Academy_) [[paper]](https://arxiv.org/pdf/2312.05278);

  - [CVPR2025] Argus: A Compact and Versatile Foundation Model for Vision<br>Argus：紧凑且多功能的视觉定位模型 (_University of Illinois Urbana-Champaign_) [[paper]](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhuang_Argus_A_Compact_and_Versatile_Foundation_Model_for_Vision_CVPR_2025_paper.pdf);

  - [CVPR2024] RegionGPT: Towards Region Understanding Vision Language Model<br>RegionGPT：迈向区域理解视觉—语言模型 (_Nvidia_) [[paper]](https://arxiv.org/pdf/2403.02330);

  - [CVPR2024] VCoder: Versatile Vision Encoders for Multimodal Large Language Models<br>VCoder：用于多模态大语言模型的多功能视觉编码器 (_Georgia Tech_) [[paper]](https://arxiv.org/pdf/2312.14233) [[code]](https://github.com/SHI-Labs/VCoder) [[checkpoint]](https://huggingface.co/models?search=vcoder);

  - [CVPR2024] Learning to Localize Objects Improves Spatial Reasoning in Visual-LLMs<br>学习定位对象可提高视觉大语言模型的空间推理能力 (_Meta_) [[paper]](https://arxiv.org/pdf/2404.07449);

  - [ECCVWorkshops2024] GPT4RoI: Instruction Tuning Large Language Model on Region-of-Interest<br>GPT4RoI：在感兴趣区域上调整大型语言模型的指令 (_The University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2307.03601) [[code]](https://github.com/jshilong/GPT4RoI?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/shilongz/GPT4RoI-7B-delta-V0);

  - [ICLR2024] CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding<br>CoVLM：通过通信解码在大型语言模型中组合视觉实体和关系 (_UMass Amherst_) [[paper]](https://arxiv.org/abs/2311.03354) [[code]](https://github.com/UMass-Embodied-AGI/CoVLM?tab=readme-ov-file) [[checkpoint]](https://github.com/UMass-Embodied-AGI/CoVLM?tab=readme-ov-file);

  - [CoRR2023] Position-Enhanced Visual Instruction Tuning for Multimodal Large Language Models<br>多模态大语言模型的位置增强视觉指令调整 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2308.13437) [[code]](https://github.com/PVIT-official/PVIT?tab=readme-ov-file#pvit-weights) [[checkpoint]](https://huggingface.co/PVIT/pvit);

  - [EMNLP2022] PEVL: Position-enhanced Pre-training and Prompt Tuning for Vision-language Models<br>PEVL：视觉—语言模型的位置增强预训练和提示调整 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2205.11169) [[code]](https://github.com/thunlp/PEVL) [[checkpoint]](https://github.com/thunlp/PEVL);

</details>

<a id="explicit-spatial-relationship"></a>
<details>
  <summary><b>Explicit Spatial Relationship<br>显式空间关系</b></summary>

  - [arXiv2025] Object-centric Binding in Contrastive Language-Image Pretraining<br>对比语言-图像预训练中的以对象为中心的绑定 (_Meta_) [[paper]](https://arxiv.org/pdf/2502.14113);

  - [arXiv2025] Seeing Beyond the Scene: Enhancing Vision-Language Models with Interactional Reasoning<br>超越场景：通过交互推理增强视觉—语言模型 (_South China University of Technology_) [[paper]](https://arxiv.org/pdf/2505.09118);

  - [arXiv2025] LLaVA-SG: Leveraging Scene Graphs as Visual Semantic Expression in Vision-Language Models<br>LLaVA-SG：利用场景图作为视觉—语言模型中的视觉语义表达 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2408.16224);

  - [ACL2023] Incorporating Structured Representations into Pretrained Vision & Language Models Using Scene Graphs<br>使用场景图将结构化表示合并到预训练的视觉和语言模型中 (_Tel-Aviv University_) [[paper]](https://arxiv.org/pdf/2305.06343) [[code]](https://github.com/AlonMendelson/SGVL) [[checkpoint]](https://drive.google.com/file/d/13jzpcLgGalO3hkiqVwziNAlCEZD90ENN/view);

</details>

---

### 3D Information Enhancement 三维信息增强
<a id="explicit-3d-geometric-representations"></a>
<details>
  <summary><b>Explicit 3D Geometric Representations<br>显式三维几何表示</b></summary>

  - [arXiv2025] Spatial 3D-LLM: Progressive Spatial Awareness for Advanced 3D Vision-Language Understanding<br>空间 3D-大语言模型：先进的 3D 视觉—语言理解的渐进式空间意识 (_Beijing Digital Native Digital City Research Center_) [[paper]](https://openreview.net/pdf?id=JzLcKWtGnl);

  - [CVPR2025] 3D-LLaVA: Towards Generalist 3D LMMs with Omni Superpoint Transformer<br>3D-LLaVA：使用 Omni Superpoint Transformer 迈向通用 3D LMM (_The University of Adelaide_) [[paper]](https://arxiv.org/pdf/2501.01163) [[code]](https://github.com/djiajunustc/3D-LLaVA?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/djiajunustc/3D-LLaVA-7B-LoRA);

  - [CVPR2025] LSceneLLM: Enhancing Large 3D Scene Understanding Using Adaptive Visual Preferences<br>LScene大语言模型：使用自适应视觉首选项增强大型 3D 场景理解 (_South China University of Technology_) [[paper]](https://arxiv.org/pdf/2412.01292) [[code]](https://github.com/Hoyyyaard/LSceneLLM) [[checkpoint]](https://huggingface.co/Hoyard/LSceneLLM);

  - [ICCVW2025] SmolRGPT: Efficient Spatial Reasoning for Warehouse Environments with 600M Parameters<br>SmolRGPT：600M参数的仓库环境高效空间推理 (_Universit de Moncton_) [[paper]](https://arxiv.org/pdf/2509.15490) [[code]](https://github.com/abtraore/SmolRGPT) [[checkpoint]](https://huggingface.co/collections/Abdrah/smolrgpt-checkpoints-6893bad56127440ef250486e);

  - [ICRA2025] SpatialBot: Precise Spatial Understanding with Vision Language Models<br>SpatialBot：利用视觉—语言模型精确理解空间 (_Shanghai Jiao Tong University_) [[paper]](https://arxiv.org/pdf/2406.13642) [[code]](https://github.com/BAAI-DCAI/SpatialBot) [[checkpoint]](https://huggingface.co/RussRobin/SpatialBot-3B);

  - [NeurIPS2025] RoboRefer: Towards Spatial Referring with Reasoning in Vision-Language Models for Robotics<br>RoboRefer：通过机器人视觉—语言模型中的推理实现空间指代 (_Beihang University_) [[paper]](https://arxiv.org/pdf/2506.04308) [[code]](https://github.com/Zhoues/RoboRefer) [[checkpoint]](https://huggingface.co/collections/Zhoues/roborefer-and-refspatial-6857c97848fab02271310b89);

  - [NeurIPS2025] SSR: Enhancing Depth Perception in Vision-Language Models via Rationale-Guided Spatial Reasoning<br>SSR：通过基本原理引导的空间推理增强视觉—语言模型的深度感知 (_Westlake University_) [[paper]](https://arxiv.org/pdf/2505.12448) [[code]](https://github.com/yliu-cs/SSR) [[checkpoint]](https://huggingface.co/collections/yliu-cs/ssr-682d44496b64e4edd94092bb);

  - [NeurIPS2025] SD-VLM: Spatial Measuring and Understanding with Depth-Encoded Vision-Language Models<br>SD-VLM：利用深度编码视觉—语言模型进行空间测量和理解 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2509.17664) [[code]](https://github.com/cpystan/SD-VLM) [[checkpoint]](https://huggingface.co/cpystan/SD-VLM-7B);

  - [NeurIPS2025] SPATIALLM: Training Large Language Models for Structured Indoor Modeling<br>SPATIA大语言模型：训练结构化室内建模的大型语言模型 (_Manycore Tech Inc._) [[paper]](https://arxiv.org/pdf/2506.07491) [[code]](https://github.com/manycore-research/SpatialLM) [[checkpoint]](https://huggingface.co/manycore-research/SpatialLM1.1-Qwen-0.5B)

  - [Arxiv2025] 3D Aware Region Prompted Vision Language Model<br>3D感知区域提示视觉—语言模型 (_UC San Diego_) [[paper]](https://arxiv.org/pdf/2509.13317);

  - [CVPR2024] LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning<br>LL3DA：用于 Omni-3D 理解、推理和规划的视觉交互指令调整 (_Fudan University_) [[paper]](https://arxiv.org/pdf/2311.18651) [[code]](https://github.com/Open3DA/LL3DA);

  - [CVPR2024] Situational Awareness Matters in 3D Vision Language Reasoning<br>情境意识在 3D 视觉—语言推理中很重要 (_UIUC_) [[paper]](https://arxiv.org/pdf/2406.07544) [[code]](https://github.com/YunzeMan/Situation3D);

  - [CVPR2024] VCoder: Versatile Vision Encoders for Multimodal Large Language Models<br>VCoder：用于多模态大语言模型的多功能视觉编码器 (_Georgia Tech_) [[paper]](https://arxiv.org/pdf/2312.14233) [[code]](https://github.com/SHI-Labs/VCoder) [[checkpoint]](https://huggingface.co/models?search=vcoder);

  - [ECCV2024] SegPoint: Segment Any Point Cloud via Large Language Model<br>SegPoint：通过大型语言模型分割任何点云 (_Nanyang Technological University_) [[paper]](https://arxiv.org/pdf/2407.13761) [[code]](https://github.com/heshuting555/);

  - [NeurIPS2024] SpatialRGPT: Grounded Spatial Reasoning in Vision-Language Models<br>SpatialRGPT：视觉—语言模型中的扎根空间推理 (_UC San Diego_) [[paper]](https://arxiv.org/pdf/2406.01584) [[code]](https://github.com/AnjieCheng/SpatialRGPT) [[checkpoint]](https://huggingface.co/collections/a8cheng/spatialrgpt-grounded-spatial-reasoning-in-vlms-66fef10465966adc81819723);

  - [NeurIPS2023] 3D-LLM: Injecting the 3D World into Large Language Models<br>3D-大语言模型：将 3D 世界注入大型语言模型 (_UCLA_) [[paper]](https://arxiv.org/pdf/2307.12981) [[code]](https://github.com/UMass-Embodied-AGI/3D-LLM);

  - [CVPR2022] ScanQA: 3D Question Answering for Spatial Scene Understanding<br>ScanQA：用于空间场景理解的 3D 问答 (_Kyoto University_) [[paper]](https://arxiv.org/pdf/2112.10482) [[code]](https://github.com/ATR-DBI/ScanQA);

  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
    <!-- leveraging depth for training a position embedding -->
    </details>

<a id="implicit-3d-from-egocentric-views"></a>
<details>
  <summary><b>Implicit 3D from Egocentric Views<br>来自第一视角的隐式三维信息</b></summary>

  - [arXiv2026] Spa3R: Predictive Spatial Field Modeling for 3D Visual Reasoning<br>Spa3R：用于 3D 视觉推理的预测空间场建模 (_Huazhong University of Science & Technology_) [[paper]](https://arxiv.org/pdf/2602.21186) [[code]](https://github.com/hustvl/Spa3R) [[checkpoint]](https://huggingface.co/hustvl/Spa3-VLM)

  - [arXiv2025] VLM-3R: Vision-Language Models Augmented with Instruction-Aligned 3D Reconstruction<br>VLM-3R：通过指令对齐 3D 重建增强视觉—语言模型 (_UT Austin_) [[paper]](https://arxiv.org/pdf/2505.20279) [[code]](https://github.com/VITA-Group/VLM-3R);

  - [arXiv2025] Spatial-MLLM: Boosting MLLM Capabilities in Visual-based Spatial Intelligence<br>Spatial-多模态大语言模型：增强基于视觉的空间智能中的 多模态大语言模型 能力 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2505.23747) [[code]](https://github.com/diankun-wu/Spatial-MLLM);

  - [arXiv2025] Vision-Language Memory for Spatial Reasoning<br>用于空间推理的视觉—语言记忆 (_University at Buffalo_) [[paper]](https://arxiv.org/pdf/2511.20644)

  - [ICCV2025] SplatTalk: 3D VQA with Gaussian Splatting<br>SplatTalk：采用高斯泼溅的 3D VQA (_Georgia Institute of Technology_) [[paper]](https://arxiv.org/pdf/2503.06271) [[code]](https://splat-talk.github.io/);

  - [NeurIPS2025] Learning from Videos for 3D World: Enhancing MLLMs with 3D Vision Geometry Priors<br>从 3D 世界视频中学习：利用 3D 视觉几何先验增强 多模态大语言模型 (_CUHK_) [[paper]](https://arxiv.org/pdf/2505.24625#page=3.50) [[code]](https://github.com/LaVi-Lab/VG-LLM)

  - [NeurIPS2025] 3DRS: MLLMs Need 3D-Aware Representation Supervision for Scene Understanding<br>3DRS：多模态大语言模型 需要 3D 感知表示监督来进行场景理解 (_HKU_) [[paper]](https://arxiv.org/pdf/2506.01946) [[code]](https://github.com/Visual-AI/3DRS) [[checkpoint]](https://huggingface.co/OliverHuang1998/3DRS)

  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
</details>

<a id="scene-level-information--ego-centric"></a>
<details>
  <summary><b>Scene-level Information + Ego-centric<br>场景级信息与第一视角</b></summary>

  - [arXiv2025] GPT4Scene: Understand 3D Scenes from Videos with Vision-Language Models<br>GPT4Scene：使用视觉—语言模型从视频中理解 3D 场景 (_The University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2501.01428) [[code]](https://github.com/Qi-Zhangyang/GPT4Scene-and-VLN-R1) [[checkpoint]](https://huggingface.co/alexzyqi/GPT4Scene-qwen2vl_full_sft_mark_32_3D_img512);

  - [arXiv2025] Beyond Flatlands: Unlocking Spatial Intelligence by Decoupling 3D Reasoning from Numerical Regression<br>超越平地：通过将 3D 推理与数值回归解耦来解锁空间智能 (_Beijing Institute of Technology_) [[paper]](https://arxiv.org/pdf/2511.11239)

  - [CVPR2025] Inst3D-LMM: Instance-Aware 3D Scene Understanding with Multi-modal Instruction Tuning<br>Inst3D-LMM：具有多模态指令调整的实例感知 3D 场景理解 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2503.00513) [[code]](https://github.com/hanxunyu/Inst3D-LMM);

  - [CVPR2025] DSPNet: Dual-vision Scene Perception for Robust 3D Question Answering<br>DSPNet：双视觉场景感知，实现稳健的 3D 问答 (_Sun Yat-sen University_) [[paper]](https://arxiv.org/pdf/2503.03190) [[code]](https://github.com/LZ-CH/DSPNet) [[checkpoint]](https://github.com/LZ-CH/DSPNet);

  - [ICCV2025] LLaVA-3D: A Simple yet Effective Pathway to Empowering LMMs with 3D Capabilities<br>LLaVA-3D：为 LMM 提供 3D 功能的简单而有效的途径 (_The University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2409.18125) [[code]](https://github.com/ZCMax/LLaVA-3D) [[checkpoint]](https://huggingface.co/ChaimZhu/LLaVA-3D-7B);

  - [ICCV2025] Robin3D: Improving 3D Large Language Model via Robust Instruction Tuning<br>Robin3D：通过稳健的指令调整改进 3D 大语言模型 (_University of Illinois Chicago_) [[paper]](https://arxiv.org/pdf/2410.00255) [[code]](https://github.com/WeitaiKang/Robin3D?tab=readme-ov-file) [[checkpoint]](https://drive.google.com/drive/folders/14Si8bdWI3N5NEeVDLhmAlxilWPl0f_Wp?usp=sharing);

  - [ICCV2025] MM-Spatial: Exploring 3D Spatial Understanding in Multimodal LLMs<br>MM-Spatial：探索多模态大语言模型中的 3D 空间理解 (_Apple_) [[paper]](https://arxiv.org/pdf/2503.13111) [[code]](https://github.com/apple/ml-cubifyanything);

  - [WACV2025] Scene-LLM: Extending Language Model for 3D Visual Understanding and Reasoning<br>Scene-大语言模型：扩展 3D 视觉理解和推理的语言模型 (_Brown University_) [[paper]](https://arxiv.org/pdf/2403.11401);

  - [ECCV2024] ScanReason: Empowering 3D Visual Grounding with Reasoning Capabilities<br>ScanReason：通过推理能力增强 3D 视觉定位 (_The University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2407.01525) [[code]](https://github.com/ZCMax/ScanReason);

  - [ICML2024] An Embodied Generalist Agent in 3D World<br>3D 世界中的多面手代理 (_Beijing Institute for General Artificial Intelligence (BIGAI)_) [[paper]](https://arxiv.org/pdf/2311.12871) [[code]](https://github.com/embodied-generalist/embodied-generalist) [[checkpoint]](https://huggingface.co/datasets/huangjy-pku/LEO_data/tree/main);

  - [NeurIPS2024] Chat-Scene: Bridging 3D Scene and Large Language Models with Object Identifiers<br>聊天场景：使用对象标识符桥接 3D 场景和大型语言模型 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2312.08168) [[code]](https://github.com/ZzZZCHS/Chat-Scene);

  - [CVPR2023] 3D Concept Learning and Reasoning from Multi-View Images<br>多视图图像的 3D 概念学习和推理 (_UCLA_) [[paper]](https://arxiv.org/pdf/2303.11327) [[code]](https://github.com/evelinehong/3D-CLR-Official);

  <!-- New paper, excluded in survey -->
</details>

---

### Data-Centric Spatial Enhancement 数据中心空间能力增强
<a id="manifesting-spatial-relations-in-2d-images"></a>
<details>
  <summary><b>Manifesting Spatial Relations in 2D Images<br>在二维图像中呈现空间关系</b></summary>

  - [arXiv2025] SpaRE: Enhancing Spatial Reasoning in Vision-Language Models with Synthetic Data<br>SpaRE：利用合成数据增强视觉—语言模型的空间推理 (_University of Waterloo_) [[paper]](https://arxiv.org/pdf/2504.20648);

  - [arXiv2025] Scaling Spatial Intelligence with Multimodal Foundation<br>利用多模态基础扩展空间智能  (_SenseTime Research_) [[paper]](https://arxiv.org/pdf/2511.13719) [[code]](https://github.com/OpenSenseNova/SenseNova-SI) [[checkpoint]](https://huggingface.co/collections/sensenova/sensenova-si);

  - [NeurIPS2025] Stitch and Tell: A Structured Multimodal Data Augmentation Method for Spatial Understanding<br>Stitch and Tell：一种用于空间理解的结构化多模态数据增强方法 (_Beijing Institute of Technology_) [[paper]](https://www.arxiv.org/pdf/2512.06769);

  - [ECCV2024] The All-Seeing Project V2: Towards General Relation Comprehension of the Open World<br>全视计划V2：迈向开放世界的一般关系理解 (_Shanghai AI Laboratory_) [[paper]](https://arxiv.org/pdf/2402.19474) [[code]](https://github.com/OpenGVLab/all-seeing?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/OpenGVLab/ASMv2);

  - [ICLR2024] KOSMOS-2: Grounding Multimodal Large Language Models to the World<br>KOSMOS-2：为世界奠定多模态大型语言模型的基础 (_Microsoft Research_) [[paper]](https://arxiv.org/pdf/2306.14824) [[code]](https://github.com/microsoft/unilm/tree/master/kosmos-2) [[checkpoint]](https://huggingface.co/microsoft/kosmos-2-patch14-224);

  - [arXiv2023] Position-Enhanced Visual Instruction Tuning for Multimodal Large Language Models<br>多模态大语言模型的位置增强视觉指令调整 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2308.13437) [[code]](https://github.com/PVIT-official/PVIT) [[checkpoint]](https://huggingface.co/PVIT/pvit);

  - [CVPR2022] Pseudo-Q: Generating Pseudo Language Queries for Visual Grounding<br>Pseudo-Q：生成视觉定位的伪语言查询 (_Tsinghua University_) [[paper]](https://arxiv.org/pdf/2203.08481) [[code]](https://github.com/LeapLabTHU/Pseudo-Q?tab=readme-ov-file);

  <!-- New paper, excluded in survey -->
</details>

<a id="manifesting-spatial-priors-in-3d-and-synthetic-worlds"></a>
<details>
  <summary><b>Manifesting Spatial Priors in 3D and Synthetic Worlds<br>在三维与合成世界中呈现空间先验</b></summary>

  - [arXiv2025] Multi-SpatialMLLM: Multi-Frame Spatial Understanding with MultiModal Large Language Models<br>Multi-Spatial多模态大语言模型：使用多模态大语言模型进行多帧空间理解 (_Meta FAIR_) [[paper]](https://arxiv.org/pdf/2505.17015) [[code]](https://github.com/facebookresearch/Multi-SpatialMLLM?tab=readme-ov-file#-model-training);

  - [arXiv2025] Sparkle: Mastering Basic Spatial Capabilities in Vision Language Models Elicits Generalization to Spatial Reasoning<br>Sparkle：掌握视觉—语言模型中的基本空间能力可推广到空间推理 (_Massachusetts Institute of Technology_) [[paper]](https://arxiv.org/pdf/2410.16162);

  - [arXiv2025] SCoT: Teaching 3D-LLMs to Think Spatially with Million-scale CoT Annotations<br>SCoT：利用百万级 CoT 注释教授 3D-大语言模型 进行空间思考 (_Anonymous_) [[paper]](https://openreview.net/pdf?id=5Tph6wFMOm);

  - [arXiv2025] Scaling Spatial Reasoning in MLLMs through Programmatic Data Synthesis<br>通过编程数据合成扩展 多模态大语言模型 中的空间推理 (_Harbin Institute of Technology_) [[paper]](https://arxiv.org/pdf/2512.16237#page=7.00) [[code]](https://github.com/AI9Stars/SPRITE);

  - [arXiv2025] Visual Spatial Tuning<br>视觉空间调整 (_The University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2511.05491) [[code]](https://github.com/Yangr116/VST) [[checkpoint]](https://huggingface.co/collections/rayruiyang/vst);

  - [arXiv2025] INTERNSPATIAL: A COMPREHENSIVE DATASET FOR SPATIAL REASONING IN VISION-LANGUAGE MODELS<br>国际空间：视觉—语言模型中空间推理的综合数据集 (_Shanghai AI Laboratory_) [[paper]](https://arxiv.org/pdf/2506.18385)

  - [CVPR2025] RoboSpatial: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics<br>RoboSpatial：教授机器人 2D 和 3D 视觉—语言模型的空间理解 (_NVIDIA_) [[paper]](https://arxiv.org/pdf/2411.16537) [[code]](https://github.com/NVlabs/RoboSpatial);

  - [ICLR2025] SPARTUN3D: Situated Spatial Understanding of 3D World in Large Language Models<br>SPARTUN3D：在大型语言模型中对 3D 世界进行定位空间理解 (_Michigan State University & UC Davis_) [[paper]](https://arxiv.org/pdf/2410.03878);

  - [ICML2025] Orient Anything: Learning Robust Object Orientation Estimation from Rendering 3D Models<br>定向任何东西：通过渲染 3D 模型学习稳健的对象方向估计 (_Zhejiang University_) [[paper]](https://arxiv.org/pdf/2412.18605) [[code]](https://github.com/SpatialVision/Orient-Anything?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/Viglong/Orient-Anything/blob/main/croplargeEX2/dino_weight.pt);

  - [WACV2025] LLaVA-SpaceSGG: Visual Instruct Tuning for Open-vocabulary Scene Graph Generation with Enhanced Spatial Relations<br>LLaVA-SpaceSGG：用于具有增强空间关系的开放词汇场景图生成的视觉指令调整 (_City University of Hong Kong_) [[paper]](https://arxiv.org/pdf/2412.06322) [[code]](https://github.com/Endlinc/LLaVA-SpaceSGG?tab=readme-ov-file) [[checkpoint]](https://huggingface.co/wumengyangok/LLaVA-SpaceSGG/tree/main);

  - [NeurIPS2025] Actial: Activate Spatial Reasoning Ability of Multimodal Large Language Models<br>Actial：激活多模态大语言模型的空间推理能力 (_Nanjing University_) [[paper]](https://openreview.net/pdf?id=jquTBzt3Av) [[code]](https://github.com/warmsnow-sh/Actial) [[checkpoint]](https://huggingface.co/Osilly/Acital-Qwen-2.5VL-7B);

  - [CVPR2024] SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities<br>SpatialVLM：赋予视觉—语言模型空间推理能力 (_Google DeepMind_) [[paper]](https://arxiv.org/pdf/2401.12168) [[code]](https://spatial-vlm.github.io/#community-implementation) [[checkpoint]](https://github.com/remyxai/VQASynth?tab=readme-ov-file#models-trained-using-vqasynth-);

  - [NeurIPS2024] Multi-modal Situated Reasoning in 3D Scenes<br>3D 场景中的多模态情景推理 (_BIGAI_) [[paper]](https://arxiv.org/pdf/2409.02389) [[code]](https://github.com/MSR3D/MSR3D);

  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->
  <!-- New paper, excluded in survey -->

</details>

## 📚 Datasets and Benchmarks 数据集与基准
> A comprehensive list of datasets for training and evaluation.
> 用于训练和评估的数据集完整列表。

### Spatially-Oriented Training Corpora 面向空间能力的训练语料
<p align="left">
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Dataset_SVQA.md">
    <img src="https://img.shields.io/badge/Training Data-Collection-green?style=flat&logo=mdbook&logoColor=white" alt="Dataset"> 
  </a>
</p>


### Evaluation Benchmarks 评估基准
<p align="left">
  <a href="https://github.com/vulab-AI/Awesome-Spatial-VLMs/blob/main/data_benchmark/Benchmark_SVQA.md">
    <img src="https://img.shields.io/badge/Benchmark-Collection-green?style=flat&logo=mdbook&logoColor=white" alt="Benchmark">
  </a>
</p>


## 🏆 Spatial VLM Leaderboard & Evaluation Toolkit 空间视觉—语言模型排行榜与评估工具包
### 🏅 Main Leaderboard 主排行榜
The table below presents the main results from our survey, comparing [38 VLMs](evaluation/README.md#model-details-and-original-repositories) across [9 benchmarks](#evaluated-benchmarks). Scores are QA Accuracy (%). Benchmarks are grouped by our Cognitive Hierarchy.
<br>下表展示了综述中的主要评测结果，在 [9 个基准](#evaluated-benchmarks)上比较了 [38 个 VLM](evaluation/README.md#model-details-and-original-repositories)。分数采用问答准确率（%），各项基准按照我们的认知层级进行分组。

<div align='center'><img src="./samples/leaderboard.jpg"  alt="Leaderboard" width="100%"/></div>

We invite the community to benchmark new models using our suite. Please to add your model's results!
<br>我们欢迎社区使用这套评测工具测试新模型，并提交你的模型结果！


### 🧑‍🔬 How to Evaluate Your Model 如何评估你的模型
1. **Selected Benchmarks for the Leaderboard 排行榜选用的基准**<br>
    We collect existing spatial benchmarks used in the literature and standardize their usage for evaluation in the hugging face repo<a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face" width="20"/></a>.  
    <br>我们收集了文献中已有的空间能力基准，并在 Hugging Face 仓库<a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face" width="20"/></a>中对其评测用法进行了标准化。<br>
    The table below summarizes the key datasets used to benchmark spatial VLMs on our leaderboard.  
    <br>下表汇总了排行榜中用于评估空间 VLM 的主要数据集。<br>
    <a id="evaluated-benchmarks"></a>
    <table>
      <tr>
        <th>Dataset Name 数据集名称</th>
        <th>Description 描述</th>
        <th>Link 链接</th>
      </tr>
      <tr>
        <td>EgoOrientBench</td>
        <td>Egocentric spatial understanding benchmark<br>第一视角空间理解基准</td>
        <td rowspan="10"><a href="https://huggingface.co/datasets/LLDDSS/Awesome_Spatial_VQA_Benchmarks"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face Link" width="20"/> Link 链接</a></td>
      </tr>
      <tr><td>GeoMeter(real)</td><td>A depth-aware spatial reasoning benchmark<br>深度感知空间推理基准</td></tr>
      <tr><td>SEED-Bench (Spatial section)</td><td>Subset focusing on spatial relations<br>专注于空间关系的子集</td></tr>
      <tr><td>What’s Up</td><td>Spatial relation in visual grounding<br>视觉定位中的空间关系基准</td></tr>
      <tr><td>CV-Bench</td><td>Visual-center spatial benchmark<br>以视觉为中心的空间能力基准</td></tr>
      <tr><td>SRBench</td><td>The extrapolation of spatial benchmark<br>空间外推能力基准</td></tr>
      <tr><td>MindCube</td><td>The extrapolation of spatial benchmark<br>空间外推能力基准</td></tr>
      <tr><td>OmniSpatial</td><td>Comprehensive spatial reasoning dataset<br>综合空间推理数据集</td></tr>
      <tr><td>RealWorldQA</td><td>Comprehensive spatial reasoning dataset<br>综合空间推理数据集</td></tr>
    </table>

2. **Evaluation Toolkit 评测工具包**<br>
   To facilitate fair and reproducible evaluation on these benchmarks, we provide a dedicated evaluation toolkit. The related code is available in [`evaluation/README.md`](evaluation/README.md).  
   <br>为便于在这些基准上开展公平且可复现的评测，我们提供了专用评测工具包，相关代码位于 [`evaluation/README.md`](evaluation/README.md)。<br>
   It supports running experiments with:
   <br>该工具包支持对以下模型和方法开展实验：
   - [Commercial VLMs](evaluation/Commercial_General/README.md) (*e.g.,* GPT, Gemini)
     <br>[商业 VLM](evaluation/Commercial_General/README.md)（例如 GPT、Gemini）
   - [General-purpose VLMs](evaluation/Commercial_General/README.md) (*e.g.,* Qwen2.5, LLava1.5, LLava_Next, LLava_Onevision)   
     <br>[通用 VLM](evaluation/Commercial_General/README.md)（例如 Qwen2.5、LLaVA 1.5、LLaVA-NeXT、LLaVA-OneVision）<br>
   - Specialized Spatial VLMs:  
     <br>专用空间 VLM：<br>
      (1) [Train-Free Promptings](evaluation/Train_Free_Promptings/README.md)  
      (1) [免训练提示方法](evaluation/Train_Free_Promptings/README.md)<br>
      (2) [Model-Centric Enhancement](evaluation/Model_Centric/README.md)  
      (2) [模型中心增强](evaluation/Model_Centric/README.md)<br>
      (3) [Explicit 2D Information Injection](evaluation/2D_Information/README.md)  
      (3) [显式二维信息注入](evaluation/2D_Information/README.md)<br>
      (4) [3D Spatial Information Enhancement](evaluation/3D_Information/README.md)  
      (4) [三维空间信息增强](evaluation/3D_Information/README.md)<br>
      (5) [Data-Centric Spatial Enhancement](evaluation/Data_Centric/README.md)
      (5) [数据中心空间能力增强](evaluation/Data_Centric/README.md)


   Follow the instructions there to plug in your own model and report results under the same protocol as our leaderboard.
   <br>按照其中的说明接入你自己的模型，即可采用与排行榜一致的协议完成评测并报告结果。




---

## Citation 引用
If you find this survey or repository useful for your research, please cite our paper:
<br>如果本综述或仓库对你的研究有所帮助，请引用我们的论文：
```
 @article{Liu_2025,
  title={Spatial Intelligence in Vision-Language Models: A Comprehensive Survey},
  url={http://dx.doi.org/10.36227/techrxiv.176231405.57942913/v2},
  DOI={10.36227/techrxiv.176231405.57942913/v2},
  publisher={Institute of Electrical and Electronics Engineers (IEEE)},
  author={Liu, Disheng and Liang, Tuo and Hu, Zhe and Peng, Jierui and Lu, Yiren and Xu, Yi and Fu, Yun and Yin, Yu},
  year={2025},
  month=nov }
```
