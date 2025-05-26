# Continuous & Discrete Diffusion Models on Vision & Language Generation  

- [Continuous \& Discrete Diffusion Models on Vision \& Language Generation](#continuous--discrete-diffusion-models-on-vision--language-generation)
  - [Discrete](#discrete)
    - [Vision](#vision)
    - [Language](#language)
    - [Guidance](#guidance)
  - [Continuous](#continuous)
    - [Language](#language-1)

## Discrete

### Vision

- [NeurIPS 2021] [Structured Denoising Diffusion Models in Discrete State-Spaces](https://arxiv.org/pdf/2107.03006) 
  > D3PM, Discrete Denoising Diffusion Probabilistic Models, a framework that extends diffusion models to discrete domains. The authors evaluate D3PMs on both text and image generation tasks.

- [CVPR 2022] [MaskGIT: Masked Generative Image Transformer](https://arxiv.org/pdf/2202.04200)
  > MaskGIT first compresses the input image into a grid of discrete tokens using a convolutional encoder and vector quantization. During training, random tokens are masked, and the model learns to predict them based on the visible tokens. MaskGIT enables various applications including class-conditional image generation, image manipulation, and image extrapolation.

- [CVPR 2022] [Vector Quantized Diffusion Model for Text-to-Image Synthesis](https://arxiv.org/pdf/2111.14822)
  > An encoder maps input images to a spatial collection of image tokens. A decoder reconstructs the images from these discrete tokens. Doing masked diffusion on the image tokens.

- [arXiv 2024] [[MASK] is All You Need](https://arxiv.org/pdf/2412.06787)
  > It builds upon Discrete Flow Matching theory to establish connections between these seemingly different approaches. By treating the masking process in Masked Generative Models as a form of discrete diffusion, this paper create a bridge that allows techniques from both paradigms to be combined and compared systematically.

- [NeurIPS 2024] [Simplified and Generalized Masked Diffusion for Discrete Data](https://arxiv.org/pdf/2406.04329)
  > A continuous-time framework that clarifies the underlying mechanics of masked diffusion and provides a remarkably simple training objective. The approach not only streamlines the implementation of these models but also improves their performance across text and image generation tasks. By allowing for state-dependent masking schedules, it creates a more flexible diffusion process that outperforms previous discrete diffusion approaches.

- [arXiv 2025] [Di[M]O: Distilling Masked Diffusion Models into One-step Generator](https://arxiv.org/pdf/2503.15457)
  > Solve the problem of slow inference speed of MDM, by model distillation, transfer the generation ability of the teacher model (multi-step MDM) to a student model (single-step generator).

### Language

- [ICML 2024] [Discrete diffusion modeling by estimating the ratios of the data distribution](https://arxiv.org/pdf/2310.16834)

- [NeurIPS 2024] [Simple and Effective Masked Diffusion Language Models](https://arxiv.org/pdf/2406.07524)

- [NeurIPS 2021] [Structured Denoising Diffusion Models in Discrete State-Spaces](https://arxiv.org/pdf/2107.03006) 

- [ICLR 2025] [Beyond Autoregression: Fast LLMs via Self-Distillation Through Time](https://arxiv.org/pdf/2410.21035)

- [ICLR 2025] [Scaling Diffusion Language Models via Adaptation from Autoregressive Models](https://arxiv.org/pdf/2410.17891) 

- [ICLR 2025] [Scaling up Masked Diffusion Models on Text](https://arxiv.org/pdf/2410.18514)

- [arXiv 2025] [Large language diffusion models](https://arxiv.org/pdf/2502.09992)

### Guidance

- [arXiv 2024] [Derivative-free guidance in continuous and discrete diffusion models with soft value-based decoding](https://arxiv.org/pdf/2408.08252)
  > Images, Molecules, DNA & RNA

- [ICLR 2025] [Unlocking guidance for discrete state-space diffusion and flow models](https://arxiv.org/pdf/2406.01572)
  > DNA

- [ICLR 2025] [Steering masked discrete diffusion models via discrete denoising posterior prediction](https://arxiv.org/pdf/2410.08134)
  > Images, Text, Molecules

- [ICLR 2025] [Simple Guidance Mechanisms for Discrete Diffusion Models](https://arxiv.org/pdf/2412.10193)
  > Text

- [arXiv 2025] [A general framework for inference-time scaling and steering of diffusion models](https://arxiv.org/abs/2501.06848)
  > Images, Text



## Continuous

### Language

- [ICLR 2023] [DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models](https://arxiv.org/pdf/2210.08933)

- [EMNLP 2023] [DiffuSeq-v2: Bridging Discrete and Continuous Text Spaces for Accelerated Seq2Seq Diffusion Models](https://arxiv.org/pdf/2310.05793)

- [NeurIPS 2023] [PLANNER: Generating Diversified Paragraph via Latent Language Diffusion Model](https://arxiv.org/pdf/2306.02531)

- [NeurIPS 2023] [AR-DIFFUSION: Auto-Regressive Diffusion Model for Text Generation](https://arxiv.org/pdf/2305.09515)

- [ICML 2024] [Discrete diffusion modeling by estimating the ratios of the data distribution](https://arxiv.org/pdf/2310.16834)
