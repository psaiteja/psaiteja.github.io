---
# Leave the homepage title empty to use the site title
title: Sai Teja Peddinti
date: 2025-06-19
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/SaiTejaPeddintiResume-Nov1,2022.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I'm a research scientist in the privacy research team at Google. I publish in the areas of privacy & security, artificial intelligence (AI), machine learning, and data mining. 

        My research leverages a dual approach—combining qualitative and quantitative methods—to comprehensively investigate user and developer privacy preferences and concerns. I then employ large-scale data analysis and Machine Learning/AI (including LLMs) techniques to design and implement novel privacy and security features.

        Most recently, I have been leveraging and critically analyzing Large Language Models (LLMs) to address fundamental, real-world challenges in cybersecurity and privacy. This vision spans two main areas: first, employing LLMs as a scalable and interpretable foundation to solve complex security and privacy problems, such as high-accuracy IoT device identification from incomplete network metadata; and second, conducting large-scale empirical studies to understand and mitigate the emerging privacy risks associated with AI. This critical analysis involves investigating how users and developers perceive and respond to threats like implicit attribute inference by LLMs, as well as studying real-world, large-scale trends in user concerns (e.g., analyzing millions of Android app reviews) to inform and drive the development of more effective, human-centered mitigation strategies for AI systems.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
