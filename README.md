<h1 align="center">P3: Toward Versatile Embodied Agents</h1>

<p align="center">
    <a href='https://arxiv.org/abs/2508.07033'>
      <img src='https://img.shields.io/badge/Paper-arXiv-red?style=plastic&logo=arXiv&logoColor=red' alt='Paper arXiv'>
    </a>
    <!-- <a href='https://fz-zsl.github.io/quatrope'>
      <img src='https://img.shields.io/badge/Project-Page-blue?style=plastic&logo=Google%20chrome&logoColor=blue' alt='Project Page'>
    </a>
    <a href='https://huggingface.co/fzzsl/QuatRoPE/tree/main'>
      <img src='https://img.shields.io/badge/Checkpoints-HF-yellow?style=plastic&logo=huggingface&logoColor=yellow' alt='Checkpoints'>
    </a> -->
    <a href='https://huggingface.co/datasets/fzzsl/ATP-Benchmark'>
      <img src='https://img.shields.io/badge/ATP%20Benchmark-HF-yellow?style=plastic&logo=huggingface&logoColor=yellow' alt='Benchmark'>
    </a>
</p>


This repository contains the official PyTorch implementation for the paper:

> Shengli Zhou, Xiangchen Wang, Jinrui Zhang, Ruozai Tian, Rongtao Xu, Guanhua Chen, and Feng Zheng. 2026. P3: Toward Versatile Embodied Agents.

## Overview

Embodied agents have shown promising generalization capabilities across diverse physical environments, making them essential for a wide range of real-world applications. However, building versatile embodied agents poses critical challenges due to three key issues: dynamic environment perception, open-ended tool usage, and complex multi-task planning. Most previous works rely solely on feedback from tool agents to perceive environmental changes and task status, which limits adaptability to real-time dynamics, causes error accumulation, and restricts tool flexibility. Furthermore, multi-task scheduling has received limited attention, primarily due to the inherent complexity of managing task dependencies and balancing competing priorities in dynamic and complex environments. To overcome these challenges, we introduce $\mathcal P^3$, a unified framework that integrates real-time perception and dynamic scheduling. Specifically, $\mathcal P^3$ enables agents to perceive task-relevant information actively from the environment, plug and utilize tools without feedback requirements, and plan multi-task execution by prioritizing urgent tasks and dynamically adjusting task order based on dependencies. Extensive real-world experiments show that our approach bridges the gap between benchmarks and practical deployment, delivering highly transferable, general-purpose embodied agents.

## Acknowledgement

We would like to thank the anonymous reviewers for their constructive feedback.

## Citation

If you find this project useful in your research, please consider citing:

```bibtex
@misc{zhou2026mathcalp3versatileembodiedagents,
      title={$\mathcal{P}^3$: Toward Versatile Embodied Agents}, 
      author={Shengli Zhou and Xiangchen Wang and Jinrui Zhang and Ruozai Tian and Rongtao Xu and Guanhua Chen and Feng Zheng},
      year={2026},
      eprint={2508.07033},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2508.07033}, 
}
```
