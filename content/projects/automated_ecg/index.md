---
title: "PatchECG: Self-Supervised ECG Arrhythmia Detection"
summary: "Master's thesis. A 1D transformer pre-trained on 8.2M unlabelled ECGs with Masked Patch Modelling; state-of-the-art on PTB-XL at 1/5 the compute."
date: 2024-09-01
weight: 3
tags: ["Self-supervised learning", "Transformers", "Medical AI", "Time-series"]
---

<div class="flex flex-wrap gap-3 not-prose my-4">
{{< button href="/publications/patchecg/" >}}Paper{{< /button >}}
{{< button href="https://github.com/Mitchell-Chatterjee/Robust-Automated-Cardiovascular-Arrhythmia-Detection" target="_blank" >}}Code{{< /button >}}
</div>

## Problem

ECG machines are everywhere, inside and outside the clinic, so passive arrhythmia monitoring is possible. But labelled ECG data is scarce, imbalanced, and noisy, and supervised models overfit to those problems.

## Approach

- **Masked Patch Modelling (MPM):** a self-supervised pre-training objective that masks patches of the ECG signal and learns to reconstruct them.
- **Large-scale pre-training** on 8.2 million unlabelled ECGs to produce **PatchECG**, a foundational 1D transformer that can be fine-tuned for any downstream ECG task.
- **Ablations** on other remedies for class imbalance, label noise, and over-parameterization.

## Results

- State-of-the-art on standard benchmarks, including PTB-XL multi-label classification, and new benchmarks on the largest, highest-quality multi-label dataset to date.
- Outperforms the previous state-of-the-art using **1/5 of the compute** while increasing model capacity **14×**.
- Significantly outperforms a state-of-the-art 2D vision transformer.
- More than **2%** improvement under class imbalance, label noise, and over-parameterization.
