---
title: "What's on My Network? Using Large Language Models to Identify Real-World IoT Devices at Scale"
authors:
- Rameen Mahmood
- admin
- Tousif Ahmed
- Danny Yuxing Huang

date: "2025-12-01T00:00:00Z"
doi: "10.1145/3808674"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the ACM on Networking (CoNEXT)"
publication_short: "CoNEXT"

abstract: The growth of IoT devices in shared environments has outpaced our ability to identify them, posing urgent risks to privacy, safety, and accountability. This challenge is especially pronounced in open-world environments, where network traffic metadata is often sparse, noisy, or adversarial. To address this problem, we introduce a semantic inference pipeline that reframes device identification as a language modeling task over real-world network metadata. As this approach depends on reliable supervision, we first construct high-fidelity vendor labels for the IoT Inspector dataset—the largest real-world corpus of its kind—using an ensemble of large language models guided by mutual-information and entropy-based stability scores. We then instruction-tune a quantized LLaMA 3.1 8B model on this dataset using curriculum learning to support generalization under sparsity and long-tail vendor distributions. Our model achieves 98.69% top-1 and 90.73% macro accuracy across 2,015 vendors, while remaining robust to missing fields, protocol drift, and adversarial manipulation. We also evaluate the model on an independent IoT testbed dataset, assess explanation quality, and conduct adversarial tests to probe robustness under spoofed and obfuscated input. These results position instruction-tuned LLMs as a scalable, interpretable foundation for trustworthy device identification at scale.

tags:
- Large Language Models
- IoT
- Device identification

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2510.13817

url_pdf: https://dl.acm.org/doi/10.1145/3808674
# url_slides: https://www.usenix.org/sites/default/files/conference/protected-files/soups2025_slides_meisenbacher.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

---

Preprint and an earlier version is available on [arXiv](https://arxiv.org/abs/2510.13817).