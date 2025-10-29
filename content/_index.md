---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      avatar:
        size: medium    # small | medium | large | xl | xxl
        shape: circle   # circle | square | rounded
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    content:
      title: "📚 My Research"
      subtitle: ""
      text: |-
        My research develops data-driven frameworks at the intersection of innovation, corporate environmental sustainability, and organizational performance. I combine econometrics, machine learning, natural language processing, and network analytics to study how firms communicate, innovate, and respond to societal pressures such as climate change. Much of my work leverages unstructured and distributed data sources, including news, social media, and patents, to uncover insights that traditional datasets often miss. By applying causal inference and computational methods, I aim to advance academic knowledge while providing actionable intelligence for managers and policymakers.
    design:
      columns: "1"

  - block: markdown
    id: research
    content:
      title: "Research"
      text: |-
        ## Publications 

        - **Safaei, N.**, & Pant, G. (2024). Safaei, N., & Pant, G. (2025). No News About Climate Action is Good News for Low-Polluting Firms. Production and Operations Management, 0(0). https://doi.org/10.1177/10591478251387803. [Link](https://journals.sagepub.com/doi/full/10.1177/10591478251387803)

        - **Safaei, N.**, Pant, G., Namdar, J., & Pant, S. (Ongoing). The Green Ripple Effect: Unraveling Green Innovation Spillover in Supply Chain Networks. Working paper. [Link](#)

        - Namdar, J., Liu, Y., **Safaei, N.**, & Modi, S. (Ongoing). Beyond Headcount: Embedding AI in Supply Chain and Operations Knowledge to Move the Productivity Needle. Working paper. [Link](#)

        - **Safaei, N.**, Namdar, J., & Pant, G. (Ongoing). A Theory-Driven Graph Neural Network System for Greenwashing Detection. Working paper. [Link](#)

        ## Journal articles (Practitioner-oriented)

        - Khaki, S., **Safaei, N.**, Pham, H., & Wang, L. (2022). WheatNet: A lightweight convolutional neural network for high-throughput image-based wheat head detection and counting. *Neurocomputing, 489*, 78–89. [Link](#)

        - Srivastava, A. K., **Safaei, N.**, Khaki, S., Lopez, G., Zeng, W., Ewert, F., Rahimi, J., *et al.* (2021). Winter wheat yield prediction using convolutional neural networks from environmental and phenological data. *Scientific Reports, 12*(1), 3215. [Link](#)

        - **Safaei, N.**, Safaei, B., Seyedekrami, S., Talafidaryani, M., Masoud, A., Wang, S., Moqri, M., *et al.* (2022). E-CatBoost: An efficient machine learning framework for predicting ICU mortality using the eICU Collaborative Research Database. *PLOS ONE, 17*(5), e0262895. [Link](#)

        - Khaki, S., Pham, H., Khalilzadeh, Z., Masoud, A., **Safaei, N.**, Han, Y., ... & Wang, L. (2022). High-throughput image-based plant stand count estimation using convolutional neural networks. Plos one, 17(7), e0268762.

        - **Safaei, N.**, Smadi, O., Masoud, A., & Safaei, B. (2022). An automatic image processing algorithm based on crack pixel density for pavement crack detection and classification. International Journal of Pavement Research and Technology, 15(1), 159-172.

        - **Safaei, N.**, Smadi, O., Safaei, B., & Masoud, A. (2021). Efficient road crack detection based on an adaptive pixel-level segmentation algorithm. Transportation Research Record, 2675(9), 370-381.

        - **Safaei, N.**, Zhou, C., Safaei, B., & Masoud, A. (2021). Gasoline prices and their relationship to the number of fatal crashes on US roads. Transportation Engineering, 4, 100053.

        ## Conference proceedings

        - Rajabalizadeh, A., Norouzi Nia, J., **Safaei, N.**, Talafidaryani, M., Bijari, R., Zarindast, A., Moqri, M., *et al.* (2020). An exploratory analysis of Electronic Intensive Care Unit (eICU) Collaborative Research Database. In *Proceedings of the International Conference on Information Systems (ICIS)*. [Link](#)

        - Rajabalizadeh, A., Wang, S., Javadi, M., **Safaei, N.**, Talafidaryani, M., Li, Q., Moqri, M., *et al.* (2020). In-depth evaluation of APACHE scoring system using eICU database. In *Proceedings of the International Conference on Information Systems (ICIS)*. [Link](#)

        - Safaei, B., Yuan, Y., & **Safaei, N.** (2024). Empowering organizations through big data: A framework for digital resilience. In *Proceedings of the Americas Conference on Information Systems (AMCIS)*. [Link](#)
    design:
      columns: "1"

  - block: collection
    id: talks
    content:
      title: "Recent & Upcoming Talks"
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: cta-card
    demo: false
    content:
      title: "👉 Build your own academic website like this"
      text: |-
        This site is generated by Hugo Blox Builder.
        Easily build anything with blocks—no code required!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
