---
title: 'Large Language Models for Real-World IoT Device Identification'
authors:
- Rameen Mahmood
- Tousif Ahmed
- admin
- Danny Yuxing Huang

date: "2025-11-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Preprint"
publication_short: "arXiv"

abstract: The rapid expansion of IoT devices has outpaced current identification methods, creating significant risks for security, privacy, and network accountability. These challenges are heightened in open-world environments, where traffic metadata is often incomplete, noisy, or intentionally obfuscated. We introduce a semantic inference pipeline that reframes device identification as a language modeling task over heterogeneous network metadata. To construct reliable supervision, we generate high-fidelity vendor labels for the IoT Inspector dataset, the largest real-world IoT traffic corpus, using an ensemble of large language models guided by mutual-information and entropy-based stability scores. We then instruction-tune a quantized LLaMA3.18B model with curriculum learning to support generalization under sparsity and long-tail vendor distributions. Our model achieves 98.25% top-1 accuracy and 90.73% macro accuracy across 2,015 vendors while maintaining resilience to missing fields, protocol drift, and adversarial manipulation. Evaluation on an independent IoT testbed, coupled with explanation quality and adversarial stress tests, demonstrates that instruction-tuned LLMs provide a scalable and interpretable foundation for real-world device identification at scale.

tags:
- Large Language Models
- IoT
- Device identification

featured: true

links:
- name: arXiv
  url: https://arxiv.org/abs/2510.13817

url_pdf: https://arxiv.org/pdf/2510.13817
# url_slides: https://www.usenix.org/sites/default/files/conference/protected-files/soups2025_slides_meisenbacher.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

---