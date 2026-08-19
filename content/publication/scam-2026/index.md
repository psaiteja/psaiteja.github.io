---
title: "Verity: A Framework to Generate Privacy Captions from Android Source Code using LLMs"
authors:
- Vijayanta Jain
- Sepideh Ghanavati
- admin
- Collin McMillan

date: "2026-09-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 26th IEEE International Conference on Source Code Analysis and Manipulation (SCAM)"
publication_short: "SCAM"

abstract: Privacy captions are short sentences that succinctly describe what personal information is used, how it is used, and why. They can be utilized in various notice formats, such as privacy policies and permission rationales. However, inaccurate captions may mislead users and expose developers to regulatory fines. Existing approaches to generating privacy notices either rely heavily on developers’ inputs and thus strain their efforts, use limited code context, leading to the incomplete capture of app privacy behaviors, or depend on potentially inaccurate privacy policies as their source for creating notices. We address these limitations by developing Verity, an approach that uses heuristics-based static and taint analysis to automatically identify and extract large and precise source code implementing an app’s privacy behaviors, and uses a Large Language Model (LLM) to generate concise, complete, and accurate privacy captions describing both coarse- and fine-grained privacy behaviors. Our evaluation shows that Verity generates high-quality privacy captions that human privacy experts choose 61% of the time over the baseline, whereas LLMs-as-judge prefer Verity captions at least 83% of the time, indicating strong performance.

tags:
- Privacy
- Android
- Source Code Analysis
- Large Language Models
- Automation

featured: false

links:
- name: SCAM'26
  url: https://conf.researchr.org/details/scam-2026/scam-2026-research-track/11/Verity-A-Framework-to-Generate-Privacy-Captions-from-Android-Source-Code-using-LLMs

url_pdf: https://arxiv.org/pdf/2601.06276.pdf

---

Preprint and an earlier version is available on [arXiv](https://arxiv.org/abs/2601.06276).