---
title: "Toward robust automated cardiovascular arrhythmia detection using self-supervised learning and 1-dimensional vision transformers"
summary: "Mitchell Chatterjee, Adrian D. C. Chan, Majid Komeili · Scientific Reports, 2026"
date: 2026-03-03
tags: ["Self-supervised learning", "Medical AI"]
---

**Mitchell Chatterjee**, Adrian D. C. Chan, Majid Komeili · *Scientific Reports* 16, 11793 (2026) · DOI [10.1038/s41598-026-41549-5](https://doi.org/10.1038/s41598-026-41549-5)

<div class="flex flex-wrap gap-3 not-prose my-4">
{{< button href="https://doi.org/10.1038/s41598-026-41549-5" target="_blank" >}}Journal{{< /button >}}
{{< button href="https://pmc.ncbi.nlm.nih.gov/articles/PMC13066006/" target="_blank" >}}Open access (PMC){{< /button >}}
{{< button href="https://github.com/Mitchell-Chatterjee/Robust-Automated-Cardiovascular-Arrhythmia-Detection" target="_blank" >}}Code{{< /button >}}
{{< button href="/projects/automated_ecg/" >}}Project summary{{< /button >}}
</div>

## Abstract

Cardiovascular diseases are the leading cause of death worldwide. With electrocardiogram (ECG) machines becoming more accessible, passive monitoring for arrhythmia detection is now possible. This work highlights the importance of self-supervised learning in detecting arrhythmias by leveraging large-scale unlabelled ECG data to improve performance and reduce overfitting to class imbalance and noise. We propose Masked Patch Modelling (MPM) and use 8.2 million unlabelled ECGs for self-supervised pre-training, introducing PatchECG, a 1D Transformer model that can be fine-tuned for various ECG tasks. PatchECG achieves state-of-the-art results on standard datasets, including PTB-XL multi-label classification, and sets new benchmarks on the largest and highest-quality multi-label dataset to date. Compared to existing methods, PatchECG is five times more computationally efficient while increasing model capacity by a factor of 14. We also compare the 1D PatchECG model to a state-of-the-art 2D vision Transformer, HeartBEiT, and observe significantly higher performance. Finally, ablation studies reveal a 2% performance improvement in handling class imbalance, label noise, and over-parameterization. These findings demonstrate the potential of self-supervised learning in advancing automated arrhythmia detection.

## Other versions

- **Preprint:** *TechRxiv*, 2024 · DOI [10.36227/techrxiv.172866031.13011158/v1](https://doi.org/10.36227/techrxiv.172866031.13011158/v1)
- **Master's thesis:** Carleton University, 2024 · DOI [10.22215/etd/2024-16267](https://doi.org/10.22215/etd/2024-16267)

## Cite

```bibtex
@article{chatterjee2026patchecg,
  title   = {Toward robust automated cardiovascular arrhythmia detection using self-supervised learning and 1-dimensional vision transformers},
  author  = {Chatterjee, Mitchell and Chan, Adrian D. C. and Komeili, Majid},
  journal = {Scientific Reports},
  volume  = {16},
  pages   = {11793},
  year    = {2026},
  doi     = {10.1038/s41598-026-41549-5}
}
```

<p class="text-xs text-neutral-500">Cover image: "ECG and CVP Curves" by Stefan Bellini, public domain (CC0) via <a href="https://commons.wikimedia.org/w/index.php?curid=40154875">Wikimedia Commons</a>.</p>
