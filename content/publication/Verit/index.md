---
title: 'Automated Generation of Accurate Privacy Captions From Android Source Code Using Large Language Models'
authors:
- Vijayanta Jain
- Sepideh Ghanavati
- admin
- Collin McMillan

date: "2026-01-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-01-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "Privacy captions are short sentences that succinctly describe what personal information is used, how it is used, and why, within an app. These captions can be utilized in various notice formats, such as privacy policies, app rationales, and app store descriptions. However, inaccurate captions may mislead users and expose developers to regulatory fines. Existing approaches to generating privacy notices or just privacy captions include using questionnaires, templates, static analysis, or machine learning. However, these approaches either rely heavily on developers' inputs and thus strain their efforts, use limited source code context, leading to the incomplete capture of app privacy behaviors, or depend on potentially inaccurate privacy policies as a source for creating notices. In this work, we address these limitations by developing Privacy Caption Generator (PCapGen), an approach that - i) automatically identifies and extracts large and precise source code context that implements privacy behaviors in an app, ii) uses a Large Language Model (LLM) to describe coarse- and fine-grained privacy behaviors, and iii) generates accurate, concise, and complete privacy captions to describe the privacy behaviors of the app. Our evaluation shows PCapGen generates concise, complete, and accurate privacy captions as compared to the baseline approach. Furthermore, privacy experts choose PCapGen captions at least 71% of the time, whereas LLMs-as-judge prefer PCapGen captions at least 76% of the time, indicating strong performance of our approach."

tags:
- Privacy
- Android
- Source Code Analysis
- Large Language Models
- Automation

featured: false

links:
- name: arXiv
  url: https://arxiv.org/abs/2601.06276

url_pdf: https://arxiv.org/pdf/2601.06276.pdf

---
