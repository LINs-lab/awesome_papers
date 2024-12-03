#### Awesome Repositories
- [Diffusion Models and Representation Learning: A Survey](https://github.com/dongzhuoyao/Diffusion-Representation-Learning-Survey-Taxonomy)


#### Efficacy

- [Glow: Generative Flow with Invertible 1x1 Convolutions](https://arxiv.org/abs/1807.03039)

- [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747v2)
  - Mini Code: https://github.com/gle-bellier/flow-matching/tree/main
  - Mini Code: https://gist.github.com/francois-rozet/fd6a820e052157f8ac6e2aa39e16c1aa

- [Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow](https://arxiv.org/abs/2209.03003)
  - https://github.com/MaximeVandegar/Papers-in-100-Lines-of-Code/tree/main/Flow_Straight_and_Fast_Learning_to_Generate_and_Transfer_Data_with_Rectified_Flow

- [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456)
  - Code: https://github.com/yang-song/score_sde

- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
  - Code: https://github.com/hojonathanho/diffusion
  - Mini Code: https://github.com/tqch/ddpm-torch
  - Mini Code: https://github.com/w86763777/pytorch-ddpm

- [Generative Modeling by Estimating Gradients of the Data Distribution](https://arxiv.org/abs/1907.05600)
  - Code: https://github.com/ermongroup/ncsn

- [Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/abs/2206.00364)
  - Code: https://github.com/nvlabs/edm
  - Mini Code: https://github.com/yuanzhi-zhu/mini_edm/tree/main

- [Analyzing and Improving the Training Dynamics of Diffusion Models](https://arxiv.org/abs/2312.02696)
  - Code: https://github.com/nvlabs/edm2
  - Mini Code: https://github.com/mmathew23/improved_edm
  - Mini Code: https://github.com/FutureXiang/edm2
  - Mini Code: https://github.com/YichengDWu/tinyedm


#### Sampling Efficiency

- [Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502)
  - Code: https://github.com/ermongroup/ddim
  - Mini Code: https://github.com/Alokia/diffusion-DDIM-pytorch

- [DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps](https://arxiv.org/abs/2206.00927)

- [Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models](https://arxiv.org/abs/2201.06503)

- [Consistency Models](https://arxiv.org/abs/2303.01469)
  - Code: https://github.com/openai/consistency_models
  - Mini Code: https://github.com/openai/consistency_models_cifar10
  - Mini Code: https://github.com/Kinyugo/consistency_models
  - Mini Code: https://github.com/junhsss/consistency-models

- [Improved Techniques for Training Consistency Models](https://arxiv.org/abs/2310.14189)
  - Code: https://github.com/Kinyugo/consistency_models

- [Simplifying, Stabilizing and Scaling Continuous-Time Consistency Models](https://arxiv.org/abs/2410.11081)

- [Consistency Models Made Easy](https://arxiv.org/abs/2406.14548)
  - Code: https://github.com/locuslab/ect

- [Stable Consistency Tuning: Understanding and Improving Consistency Models](https://arxiv.org/abs/2410.18958)
  - Code: https://github.com/G-U-N/Stable-Consistency-Tuning

- [Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2403.03206)

- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
  - Code: https://github.com/CompVis/latent-diffusion

- [Phased Consistency Model](https://arxiv.org/abs/2405.18407)
  - Code: https://github.com/G-U-N/Phased-Consistency-Model


#### Training Efficiency


- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)



- [Representation Alignment for Generation: Training Diffusion Transformers Is Easier Than You Think](https://arxiv.org/abs/2410.06940)
  - Code: https://github.com/sihyun-yu/REPA


- [Return of Unconditional Generation: A Self-supervised Representation Generation Method](https://arxiv.org/abs/2312.03701)
  - Code: https://github.com/LTH14/rcg

- [Immiscible Diffusion: Accelerating Diffusion Training with Noise Assignment](https://arxiv.org/abs/2406.12303)
  - Code: https://github.com/yhli123/immiscible-diffusion

#### Interesting Applications

- [Diffusion Model as Representation Learner](https://arxiv.org/abs/2308.10916)
  - Code: https://github.com/Adamdad/Repfusion
  - Interesting Point: Our study begins by examining the feature space of DPMs, revealing that DPMs are inherently denoising autoencoders that balance the representation learning with regularizing model capacity.

- [Denoising Diffusion Autoencoders are Unified Self-supervised Learners](https://arxiv.org/abs/2303.09769)
  - Code: https://github.com/FutureXiang/ddae
  - Interesting Point: This paper shows that the networks in diffusion models, namely denoising diffusion autoencoders (DDAE), are unified self-supervised learners: by pre-training on unconditional image generation, DDAE has already learned strongly linear-separable representations within its intermediate layers without auxiliary encoders, thus making diffusion pre-training emerge as a general approach for generative-and-discriminative dual learning.

- [SODA: Bottleneck Diffusion Models for Representation Learning](https://arxiv.org/abs/2311.17901)
  - Interesting Point: What I cannot create, I do not understand.

- [Self-Improving Diffusion Models with Synthetic Data](https://arxiv.org/abs/2408.16333v1)
  - Interesting Point: Self-IMproving diffusion models with Synthetic data (SIMS) is a new training concept for diffusion models that uses self-synthesized data to provide negative guidance during the generation process to steer a model's generative process away from the non-ideal synthetic data manifold and towards the real data distribution.

- [In-Context LoRA for Diffusion Transformers](https://arxiv.org/abs/2410.23775v3)
  - Code: https://github.com/ali-vilab/In-Context-LoRA


- [Zero-Shot Image Restoration Using Denoising Diffusion Null-Space Model](https://arxiv.org/abs/2212.00490v2)
  - Code: https://github.com/wyhuai/ddnm

- [Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2403.03206)


- [OmniGen: Unified Image Generation](https://arxiv.org/abs/2409.11340v1)

- [Poisson Flow Generative Models](https://arxiv.org/abs/2209.11178)
  - https://github.com/Newbeeer/Poisson_flow

- [Adversarial Diffusion Distillation](https://arxiv.org/abs/2311.17042)

- [PaGoDA: Progressive Growing of a One-Step Generator from a Low-Resolution Diffusion Teacher](https://arxiv.org/abs/2405.14822v1)

- [Denoising Diffusion Restoration Models](https://arxiv.org/abs/2201.11793)

- [ResShift: Efficient Diffusion Model for Image Super-resolution by Residual Shifting](https://arxiv.org/abs/2307.12348)

- [PixArt-α: Fast Training of Diffusion Transformer for Photorealistic Text-to-Image Synthesis](https://arxiv.org/abs/2310.00426)
  - Code: https://github.com/PixArt-alpha/PixArt-alpha

- [Progressive Compositionality In Text-to-Image Generative Models](https://arxiv.org/abs/2410.16719)

- [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954v1)
  - Code: https://github.com/jy0205/Pyramid-Flow

- [Improved Distribution Matching Distillation for Fast Image Synthesis](https://arxiv.org/abs/2405.14867)
  - Code: https://github.com/tianweiy/DMD2

- [OminiControl: Minimal and Universal Control for Diffusion Transformer](https://arxiv.org/abs/2411.15098v3)

- [WF-VAE: Enhancing Video VAE by Wavelet-Driven Energy Flow for Latent Video Diffusion Model](https://arxiv.org/abs/2411.17459v2)

#### Interesting Explorations


- [Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise](https://arxiv.org/abs/2208.09392)
  - Code: https://github.com/arpitbansal297/Cold-Diffusion-Models/tree/main
  - Mini Code: https://github.com/arpitbansal297/Cold-Diffusion-Models/blob/main/demixing-diffusion-pytorch/demixing_diffusion_pytorch/demixing_diffusion_pytorch.py

- [Soft Diffusion: Score Matching for General Corruptions](https://arxiv.org/abs/2209.05442)

- [Dual Diffusion Implicit Bridges for Image-to-Image Translation](https://arxiv.org/abs/2203.08382)
  - Code: https://github.com/suxuann/ddib/
  - Mini Code: https://github.com/suxuann/ddib/blob/main/guided_diffusion/gaussian_diffusion.py


- [Generator Matching: Generative modeling with arbitrary Markov processes](https://arxiv.org/abs/2410.20587)


- [$\epsilon$-VAE: Denoising as Visual Decoding](https://arxiv.org/abs/2410.04081)
  - Interesting Point: In this work, we offer a new perspective by proposing denoising as decoding, shifting from single-step reconstruction to iterative refinement.

- [Diffusion Models are Evolutionary Algorithms](https://arxiv.org/abs/2410.02543v2)


#### Theoritical Analysis

- [Generalization in diffusion models arises from geometry-adaptive harmonic representations](https://arxiv.org/abs/2310.02557)
  - Code: https://github.com/LabForComputationalVision/memorization_generalization_in_diffusion_models
  - Interesting Point: Finally, we show that when trained on regular image classes for which the optimal basis is known to be geometry-adaptive and harmonic, the denoising performance of the networks is near-optimal.

- [Understanding Diffusion Objectives as the ELBO with Simple Data Augmentation](https://arxiv.org/abs/2303.00848)