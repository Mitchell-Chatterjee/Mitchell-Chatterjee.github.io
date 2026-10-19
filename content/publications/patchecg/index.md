---
title: "Toward Robust Automated Cardiovascular Arrhythmia Detection using Self-supervised Learning and 1-Dimensional Vision Transformers"
summary: "Mitchell Chatterjee, Majid Komeili, Adrian Chan · TechRxiv preprint, 2024"
date: 2024-09-01
tags: ["Self-supervised learning", "Medical AI"]
---

**Mitchell Chatterjee**, Majid Komeili, Adrian Chan · *TechRxiv* preprint, 2024 · DOI [10.36227/techrxiv.172866031.13011158/v1](https://doi.org/10.36227/techrxiv.172866031.13011158/v1)

<div class="flex flex-wrap gap-3 not-prose my-4">
{{< button href="https://www.techrxiv.org/doi/full/10.36227/techrxiv.172866031.13011158/v1" target="_blank" >}}PDF{{< /button >}}
{{< button href="https://github.com/Mitchell-Chatterjee/Robust-Automated-Cardiovascular-Arrhythmia-Detection" target="_blank" >}}Code{{< /button >}}
{{< button href="/projects/automated_ecg/" >}}Project summary{{< /button >}}
</div>

## Abstract

Cardiovascular diseases are the primary cause of death globally. With the prevalence of electrocardiogram (ECG) machines within and outside the clinical environment, it is now possible to passively monitor a patient's heartbeat for cardiovascular diseases. The goal of this work is to emphasize the importance of self-supervised learning for arrhythmia detection, leveraging the large amounts of unlabelled data recently made publicly available and demonstrating significant performance improvements as it reduces overfitting to class imbalance and noise. We propose Masked Patch Modelling (MPM) and leverage 8.2 million unlabelled ECGs to perform large-scale self-supervised pre-training and create a foundational 1-dimensional Transformer model, PatchECG, that can be fine-tuned for any downstream tasks involving ECG data. We obtain state-of-the-art results on standard benchmark datasets, including PTB-XL multi-label classification, while setting new benchmarks on the largest and highest quality multi-label classification dataset to date. We find that PatchECG outperforms the current state-of-the-art with regard to computational efficiency, requiring only 1/5 of the computational resources while increasing model capacity by a factor of 14. We also compare the 1-dimensional PatchECG model to a state-of-the-art 2-dimensional vision Transformer and observe significantly higher performance. Finally, we perform ablation studies to investigate other methods for addressing the critical issues incurred with automated arrhythmia detection, resulting in a performance improvement of more than 2% under conditions of class imbalance, label noise, and over-parameterization.

## Cite

```bibtex
@article{chatterjee2024patchecg,
  title   = {Toward Robust Automated Cardiovascular Arrhythmia Detection using Self-supervised Learning and 1-Dimensional Vision Transformers},
  author  = {Chatterjee, Mitchell and Komeili, Majid and Chan, Adrian},
  journal = {TechRxiv},
  year    = {2024},
  doi     = {10.36227/techrxiv.172866031.13011158/v1}
}
```
