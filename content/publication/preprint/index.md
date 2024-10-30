---
title: "Toward Robust Automated Cardiovascular Arrhythmia Detection using Self-supervised Learning and 1-Dimensional Vision Transformers"
authors:
- Mitchell Chatterjee
- Majid Komeili
- Adrian Chan
date: "2024-09-01T00:00:00Z"
doi: "10.36227/techrxiv.172866031.13011158/v1"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Cardiovascular diseases are the primary cause of death globally. With the prevalence of electrocardiogram (ECG) machines within and outside the clinical environment, it is now possible to passively monitor a patient's heartbeat for cardiovascular diseases. The goal of this work is to emphasize the importance of self-supervised learning for arrhythmia detection, leveraging the large amounts of unlabelled data recently made publicly available and demonstrating significant performance improvements as it reduces overfitting to class imbalance and noise. We propose Masked Patch Modelling (MPM) and leverage 8.2 million unlabelled ECGs to perform large-scale self-supervised pre-training and create a foundational 1-dimensional Transformer model, PatchECG, that can be fine-tuned for any downstream tasks involving ECG data. We obtain state-of-the-art results on standard benchmark datasets, including PTB-XL multi-label classification, while setting new benchmarks on the largest and highest quality multi-label classification dataset to date. We find that PatchECG outperforms the current state-of-the-art with regard to computational efficiency, requiring only 1/5 of the computational resources while increasing model capacity by a factor of 14. We also compare the 1-dimensional PatchECG model to a state-of-the-art 2-dimensional vision Transformer and observe significantly higher performance. Finally, we perform ablation studies to investigate other methods for addressing the critical issues incurred with automated arrhythmia detection, resulting in a performance improvement of more than 2% under conditions of class imbalance, label noise, and over-parameterization.

# Summary. An optional shortened abstract.
summary: Cardiovascular arrhythmia detection using self-supervised learning and 1-dimensional vision transformers in noisy environments.

tags:
- Automated ECG Arrhythmia Classification

featured: true

links:
- name: Custom Link
  url: https://www.techrxiv.org/doi/full/10.36227/techrxiv.172866031.13011158/v1
url_pdf: https://www.techrxiv.org/doi/full/10.36227/techrxiv.172866031.13011158/v1
url_code: 'https://github.com/Mitchell-Chatterjee/Robust-Automated-Cardiovascular-Arrhythmia-Detection'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- content/project/automated_ecg

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---
