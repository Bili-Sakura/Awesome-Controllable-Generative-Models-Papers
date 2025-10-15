# 🔥 Awesome Controllable Generative Models

A curated and continuously updated collection of **recent (2023–2025)** research papers on **controllable generative models**, with a special focus on both **UNet-based diffusion models** and **Transformer-based diffusion architectures**.

This list emphasizes core advances in:

- 🧭 **Control mechanisms** – including condition injection, adapters, multi-modal control
- 👁️ **Attention interpretation** – revealing what diffusion models focus on
- 🎛️ **Frequency-based control** – using spectral domain knowledge to guide generation
- 🔁 **Alignment & knowledge transfer** – enabling more coherent, faithful, and data-efficient synthesis
- 🧑‍🎨 **Image-to-image (I2I) editing** – flexible, structure-preserving transformation across domains

> 💡 Our goal is not only to track the state-of-the-art in controllable generation, but also to offer a **well-organized knowledge map** for newcomers and researchers building on top of diffusion models.

---

## 🧭 Control Mechanism

| Paper | Venue | Links |
|-------|-------|-------|
| ConceptCtrl: Concept Control of Zero-shot Personalized Image Generation | arXiv 2025 | [Paper](https://arxiv.org/abs/2503.06568) \| [Code](https://github.com/QY-H00/Conceptrol) |
| Is Noise Conditioning Necessary for Denoising Generative Models? | arXiv 2025 | [Paper](https://arxiv.org/abs/2502.13129) \| [Code](#) |
| CTRL-Adapter: An Efficient and Versatile Framework for Adapting Diverse Controls to Any Diffusion Model | ICLR 2025 (Oral) | [Paper](https://openreview.net/forum?id=ny8T8OuNHe) \| [Code](https://github.com/HL-hanlin/Ctrl-Adapter) |
| Ctrl-U: Robust Conditional Image Generation via Uncertainty-aware Reward Modeling | ICLR 2025 | [Paper](https://arxiv.org/abs/2410.11236) \| [Code](https://github.com/grenoble-zhang/Ctrl-U) |
| FlexControl: Computation-Aware Conditional Control with Differentiable Router | ICML 2025 (Poster) | [Paper](https://arxiv.org/abs/2502.10451) \| [Code](https://github.com/Daryu‑Fan/FlexControl) |
| Rectified Diffusion Guidance for Conditional Generation | CVPR 2025 | [Paper](https://arxiv.org/abs/2410.18737) \| [Code](#) |
| OminiControl: Minimal and Universal Control for Diffusion Transformer | ICCV 2025 (Highlight) | [Paper](https://arxiv.org/abs/2411.15098) \| [Code](https://github.com/Yuanshi9815/OminiControl) |
| Controllable Generation with Text-to-Image Diffusion Models: A Survey | T-PAMI 2024 | [Paper](https://arxiv.org/abs/2403.04279) \| [Code](#) |
| Edify Image: High-Quality Image Generation with Pixel Space Laplacian Diffusion Models | arXiv 2024 | [Paper](https://arxiv.org/abs/2411.07126) \| [Code](https://github.com/NVIDIA/Edify-Image) |
| SmartControl: Enhancing ControlNet for Handling Rough Visual Conditions | ECCV 2024 (Poster) | [Paper](https://arxiv.org/abs/2404.06451) \| [Code](https://github.com/liuxiaoyu1104/SmartControl) |
| Ctrl‑X: Controlling Structure and Appearance Without Guidance | NeurIPS 2024 | [Paper](https://arxiv.org/abs/2406.07540) \| [Code](https://github.com/genforce/ctrl-x) |
| Layout-to-Image Generation with Localized Descriptions using ControlNet with Cross-Attention Guidance | WACV 2024 | [Paper](https://arxiv.org/abs/2402.13404) \| [Code](#) |
| IP-Adapter: Text Compatible Image Prompt Adapter for Text-to-Image Diffusion Models | arXiv 2023 | [Paper](https://arxiv.org/abs/2308.06721) \| [Code](https://github.com/tencent-ailab/IP-Adapter) |
| Composer: Creative and Controllable Image Synthesis with Composable Conditions | ICML 2023 | [Paper](https://arxiv.org/abs/2302.09778) \| [Code](https://github.com/ali-vilab/composer?tab=readme-ov-file) |
| MultiDiffusion: Fusing Diffusion Paths for Controlled Image Generation | CVPR 2023 | [Paper](https://arxiv.org/abs/2302.08113) \| [Code](#) |
| UniControl: A Unified Diffusion Model for Controllable Visual Generation In the Wild | CVPR 2023 | [Paper](https://arxiv.org/abs/2305.11147) \| [Code](https://github.com/salesforce/UniControl) |
| Adding Conditional Control to Text-to-Image Diffusion Models | ICCV 2023 | [paper](https://arxiv.org/abs/2302.05543) \| [Code](https://github.com/lllyasviel/ControlNet) |
| Cocktail : Mixing Multi-Modality Controls for Text-Conditional Image Generation | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2306.00964) \| [Code](https://github.com/mhh0318/Cocktail) |
| T2I-Adapter: Learning Adapters to Dig out More Controllable Ability for Text-to-Image Diffusion | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2302.08453) \| [Code](https://github.com/TencentARC/T2I-Adapter) |
| Uni-ControlNet: All-in-One Control to Text-to-Image Diffusion Models | NeurIPS 2023 | [Paper](https://arxiv.org/abs/2305.16322) \| [Code](https://github.com/ShihaoZhaoZSH/Uni-ControlNet) |
| More Control for Free! Image Synthesis with Semantic Diffusion Guidance | WACV 2023 | [Paper](https://arxiv.org/abs/2112.05744) \| [Code](https://xh-liu.github.io/sdg/) |
| Sketch-Guided Text-to-Image Diffusion Models | arXiv 2022 | [Paper](https://arxiv.org/abs/2211.13752) \| [Code](https://github.com/ogkalu2/Sketch-Guided-Text-To-Image-Diffusion) |
| Generative Modeling by Estimating Gradients of the Data Distribution | NeurIPS 2019 | [Paper](https://arxiv.org/abs/1907.05600) \| [Code](#) |

> 🧠 These papers push the boundary of **how we guide generation**, whether through minimal prompts, learned adapters, or uncertainty-aware mechanisms.


---

## 👁️ Attention & Interpretability

| Paper | Venue | Links |
|-------|-------|-------|
| ConceptAttention: Diffusion Transformers Learn Highly Interpretable Features | ICML 2025 (Oral) | [Paper](https://arxiv.org/abs/2502.04320) \| [Code](https://github.com/helblazer811/ConceptAttention) |
| ToMA: Token Merge with Attention for Diffusion Models | ICML 2025 (Poster) | [Paper](https://openreview.net/forum?id=xhtqgW5b93) \| [Code](#) |
| Attention Distillation: A Unified Approach to Visual Characteristics Transfer | CVPR 2025 | [Paper](https://arxiv.org/abs/2502.20235) \| [Code](https://github.com/xugao97/AttentionDistillation) |
| What the DAAM: Interpreting Stable Diffusion Using Cross Attention | ACL 2024 (Oral) | [Paper](https://arxiv.org/abs/2302.12243) \| [Code](https://github.com/zhudilin/DAAM) |

> 🔬 Interpretability is **not just analysis** — it's a step toward **transparent and editable generative pipelines**.

---

## 🎛️ Frequency Domain Control

| Paper | Venue | Links |
|-------|-------|-------|
| Frequency Autoregressive Image Generation with Continuous Tokens | arXiv 2025 | [Paper](https://arxiv.org/abs/2503.05305) \| [Code](https://github.com/yuhuUSTC/FAR) |
| Diffusion-based Adversarial Purification from the Perspective of the Frequency Domain | ICML 2025 (Spotlight Poster) | [Paper](https://arxiv.org/abs/2505.01267) \| [Code](#) |
| DiffFNO: Diffusion Fourier Neural Operator for Arbitrary-Scale Super-Resolution | CVPR 2025 (Oral) | [Paper](https://arxiv.org/abs/2411.09911) \| [Code](#) |
| PTDiffusion: Free Lunch for Generating Optical Illusion Hidden Pictures with Phase-Transferred Diffusion | CVPR 2025 (Poster) | [Paper](https://arxiv.org/abs/2503.06186) \| [Code](https://github.com/XiangGao1102/PTDiffusion) |
| Frequency-Controlled Diffusion Model for Versatile Text-Guided Image-to-Image Translation | AAAI 2024 | [Paper](https://arxiv.org/abs/2407.03006) \| [Code](https://github.com/XiangGao1102/FCDiffusion) |
| FreeU: Free Lunch in Diffusion U-Net | CVPR 2024 | [Paper](https://arxiv.org/abs/2309.11497) \| [Code](https://github.com/ChenyangSi/FreeU) |
| FreeDiff: Progressive Frequency Truncation for Image Editing with Diffusion Models | ECCV 2024 (Poster) | [Paper](https://arxiv.org/abs/2404.11895) \| [Code](https://github.com/thermal-dynamics/freediff) |
| ResDiff: Combining CNN and Diffusion Model for Image Super-Resolution | AAAI 2023 | [Paper](https://arxiv.org/abs/2303.08714) \| [Code](https://github.com/LYL1015/ResDiff) |

> 📡 Spectral and signal-level control provides **low-level but powerful levers** for generative consistency, resolution, and robustness.

---

## 🔁 Alignment & Knowledge Transfer

| Paper | Venue | Links |
|-------|-------|-------|
| When Model Knowledge meets Diffusion: Data-free Synthesis with Domain-Class Alignment | ICML 2025 | [Paper](https://arxiv.org/abs/2506.15381) \| [Code](#) |

> 🧬 These works align **discrete symbolic knowledge** with **continuous generative priors**, aiming for controllability in low-data or zero-shot regimes.

---

You may also consider including some notable **image-to-image (I2I） editing methods** in your collection.
## Image Editing

| Paper | Venue | Links |
|-------|-------|-------|
| Diffusion Model-Based Image Editing: A Survey | TPAMI 2025 | [Paper](https://arxiv.org/abs/2402.17525) \| [Code](https://github.com/SiatMMLab/Awesome-Diffusion-Model-Based-Image-Editing-Methods) |
| AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea | CVPR 2025 (Oral) | [Paper](https://arxiv.org/abs/2411.15738) \| [Code](https://github.com/DCDmllm/AnyEdit) |
| Direct Inversion: Boosting Diffusion-based Editing with 3 Lines of Code | ICLR 2024 | [Paper](https://arxiv.org/abs/2310.01506) \| [Code](https://github.com/cure-lab/PnPInversion) |
| Prompt-to-Prompt Image Editing with Cross Attention Control | ICLR 2023 | [Paper](https://arxiv.org/abs/2208.01626) \| [Code](https://github.com/google/prompt-to-prompt) |
| Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation | CVPR 2023 (Poster) | [Paper](https://arxiv.org/abs/2211.12572) \| [Code](https://github.com/MichalGeyer/plug-and-play) |
| Zero-shot Image-to-Image Translation (pix2pix-zero) | SIGGRAPH 2023 | [Paper](https://arxiv.org/abs/2302.03027) \| [Code](https://github.com/pix2pixzero/pix2pix-zero) |
| RePaint: Inpainting using Denoising Diffusion Probabilistic Models | CVPR 2022 | [Paper](https://arxiv.org/abs/2201.09865) \| [Code](https://github.com/andreas128/RePaint) |

> ✏️ Editing is arguably **where controllability matters most** — precision, structure preservation, and user intent must all align.

---

## 📬 Contribute

💡 Know a paper we missed? Working on a new controllable generation method?  
Feel free to **submit a pull request** or **open an issue** — contributions are welcome!

