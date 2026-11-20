---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Jingkai Huang
======
* Email: 202364820481@mail.scut.edu.cn

Education
======
* **South China University of Technology**, School of Future Technology, B.Eng. in Artificial Intelligence, 2023 -- Present

Research Experience
======
<!-- * **Research on Spatiotemporally Adaptive Inference Acceleration for Dynamic Video Generation Models**, Shanghai Jiao Tong University, advised by Linfeng Zhang, Mar. 2026 -- Jun. 2026
  * Proposed a dynamic spatiotemporal adaptive acceleration framework to reduce the high inference cost and latency of video diffusion models.
  * Formulated computation allocation in video generation as a resource allocation problem between spatial resolution and temporal frame rate, and used an early low-cost latent sketch to estimate spatial detail demand and motion demand under a fixed compute budget.
  * Evaluated the method on multiple text-to-video and image-to-video models, achieving up to 7× inference speedup; when combined with distillation, the speedup reached up to 18× while preserving strong generation quality. -->

* **DeltaSight: Architecting Efficient Video AIoT Systems via Cross-Stage Consistent Redundancy Elimination**, South China University of Technology, advised by Cen Chen, Nov. 2025 -- Feb. 2026
  * Designed an end-to-end collaborative architecture that unifies processing granularity and eliminates cross-stage redundancy in video AIoT systems, addressing the mismatch between pixel-level sensing and tile-level model computation.
  * Submitted to DAC with the advisor as second author and the student as third author; accepted.

* **MANS+: Efficient and Portable ANS Encoding for Multi-Byte Integer Data on CPUs and GPUs**, Institute of Computing Technology, Chinese Academy of Sciences, advised by Dingwen Tao, Dec. 2025 -- Feb. 2026
  * Extended the SC paper MANS into MANS+ for entropy coding of multi-byte integer data, with the goal of improving throughput and stability across different data scales.
  * Packaged the method as an HDF5 filter plugin and conducted large-scale parallel I/O experiments to validate its effectiveness.
  * Co-first author; manuscript completed and under revision at IEEE TPDS.

Competitions and Leadership
======
* **RobotIC**, Algorithms Team Lead, Oct. 2023 -- Feb. 2026
* **23rd National University Student Robot Competition (ROBOCON)**, National First Prize, Jul. 2024
* **RAICOM Robot Developer Competition**, Runner-up in the National Finals (First Prize), Aug. 2024
* **8th National University Embedded Chip and System Design Competition (Chip Application Track)**, National Second Prize, Aug. 2025
* **Young Professionals Exhibition & Competition (YPEC) 2024**, Certificate of Attendance, Jul. 2024
* **14th MathorCup Mathematical Application Challenge**, National Third Prize (Undergraduate Division), Apr. 2024

Technical Skills
======
* **Programming Languages:** Proficient in C/C++ and Python; familiar with the CUDA C++ parallel programming model.
* **Deep Learning Frameworks:** Strong experience with modular network construction in PyTorch, including custom operator layers and model implementation; proficient in reproducing and extending SOTA models with the Hugging Face Transformers ecosystem.
* **Kernel and Performance Optimization:** Solid understanding of the FlashAttention algorithm and completed an independent CUDA reimplementation; capable of profiling computational bottlenecks with performance analysis tools.
* **Toolchain:** Pytorch, Nsight Systems, Nsight Compute, Linux, Git, CMake, GDB, and CUDA-GDB.
