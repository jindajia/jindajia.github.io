---
title: Home
layout: home
---

<!-- # Jinda Jia -->
<!-- <br/><br/> -->
**Email:** jindjia@iu.edu  [LinkedIn](https://www.linkedin.com/in/jindajia/)

Ph.D. in Computer Engineering, Indiana University Bloomington (Jan. 2024 - Present) \
M.S. in Computer Science, University of Florida (Aug. 2021 - Dec. 2022) \
B.S. in Software Engineering, Shandong University (Sept. 2016 - June 2020)

## Bio
I am a Ph.D. student at Indiana University Bloomington, supervised by Prof. Fengguang Song. My research focuses on Efficient Machine Learning Systems, particularly in efficient LLM pre-training and inference, collective communication, and quantization/compression techniques for distributed training. I work extensively with systems like Megatron-LM, Deepspeed, vLLM, and SGLang.

My current work involves reducing communication overhead in large language model (LLM) training through advanced compression techniques and computation-communication overlapping strategies to improve training efficiency at scale.

## Research Interests
- HPC
- Efficient Machine Learning System
- Efficient LLM pre-training and inference
- NCCL, Collective Communication
- Quantization, Compression, and Overlapping of Communication during LLM pretraining
- Megatron-LM, Deepspeed, vLLM, SGLang

## Experience

**Research Intern, TogetherAI** \
*Oct. 2025 - Present* \
Implementing KV Cache Quantization in SGLang

**Research Intern, Bytedance Seed Infra** \
*May 2025 - Aug. 2025* \
Working on Hybrid LocalSGD-HSDP for Hierarchical Communication Reduction

**Research Assistant, Indiana University Bloomington** \
*Aug. 2023 - Present* \
Accelerating LLM Training by Compressing Communication

**iOS Developer, Meituan** \
*July 2020 - July 2021*

## News

- **Oct 2025**: Join **TogetherAI** as a Research Intern, working on KV Cache Quantization in SGLang.
- **Sept 2025**: Our paper **DUO: No Compromise to Accuracy Degradation** was accepted to **NeurIPS 2025**, where I am the first author!!
- **July 2025**: Attend **DAC 2025** (Design Automation Conference) in San Francisco, California, where our paper **BirdMoE** was presented.
- **June 2025**: Our paper **STZ: A High Quality and High Speed Streaming Lossy Compression Framework for Scientific Data** was accepted to **SC 2025**.
- **May 2025**: Join **Bytedance Seed Infra** as a Research Intern, working on Hybrid LocalSGD-HSDP for Hierarchical Communication Reduction.
- **Dec 2024**: Presented **SDP4Bit** as a poster at **NeurIPS 2024** in Vancouver, Canada.
- **Nov 2024**: Attend [SC 2024](https://sc24.supercomputing.org/program/) (The International Conference for High Performance Computing, Networking, Storage, and Analysis) in Atlanta, Georgia.
- **Nov 2024**: Our paper **COMPSO** was accepted to **PPoPP 2025**.
- **Oct 2024**: Our paper **SDP4Bit** was accepted to **NeurIPS 2024**, where I am the first author!

## Publications

- **DUO: No Compromise to Accuracy Degradation** \
    <u>Jinda Jia</u>, Cong Xie, Fanjiang Ye, Hao Feng, Hanlin Lu, Daoce Wang, Haibin Lin\
    *NeurIPS 2025* \
    DUO is a distributed training framework that mitigates accuracy loss from gradient communication quantization without extra overhead by introducing an asynchronous high-precision gradient communication step on the host. This enables baseline-level training accuracy even with 1-bit gradients quantization.

- **SDP4Bit: Toward 4-bit Communication Quantization in Sharded Data Parallelism for LLM Training** \
    <u>Jinda Jia</u>, Cong Xie, Hanlin Lu, Daoce Wang, Hao Feng, Chengming Zhang, Baixi Sun, Haibin Lin, Zhi Zhang, Xin Liu, Dingwen Tao \
    *NeurIPS 2024* \
    [Paper](https://openreview.net/forum?id=PEEqnXlSCk) | [Code](https://github.com/jindajia/SDP4Bit) \
    Achieves a 4.08× speedup in e2e throughput on a scale of 128 H800 GPUs by reducing weight and gradient communication to 4 bits.

- **COMPSO: Optimizing Gradient Compression for Distributed Training with Second-Order Optimizers** \
    Baixi Sun, Weijin Liu, J. Gregory Pauloski, Jiannan Tian, <u>Jinda Jia</u>, Daoce Wang, Boyuan Zhang, Mingkai Zheng, Sheng Di, Sian Jin, Zhao Zhang, Xiaodong Yu, Kamil A. Iskra, Pete Beckman, Guangming Tan, Dingwen Tao \
    *PPoPP 2025* \
    Achieves a communication compression ratio of 22.1×, reducing communication time by 14.2× without sacrificing model accuracy.

- **BirdMoE: Reducing Communication Costs for Mixture-of-Experts Training Using Load-Aware Bi-random Quantization** \
    (Fourth Author) \
    *DAC 2025* \
    Employs lightweight Random Quantization with expectation invariance property to efficiently map floating-point results into integers while maintaining MoE training quality.

- **STZ: A High Quality and High Speed Streaming Lossy Compression Framework for Scientific Data** \
    (Sixth Author) \
    *SC 2025* \
    The first streaming lossy compression framework supporting both progressive and random-access decompression, achieving up to 6.7× higher compression and decompression throughput.

## Awards and Service

**Conference Reviewing**
- NeurIPS 2025 Reviewer
- NeurIPS 2024 Reviewer
- ICML 2025 Reviewer

**Awards**
- University of Florida Graduate Academic Achievement Award ($4,500)
- Indiana University Travel Award ($3,000)
