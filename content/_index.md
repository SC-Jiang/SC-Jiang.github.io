---
title: ''
summary: ''
date: 2026-06-21
type: landing

design:
  spacing: '3rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      headings:
        about: 'Biography'
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: false
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: resume-experience
  id: experience
  content:
    username: me
  design:
    date_format: 'January 2006'
    is_education_first: false
  - block: markdown
    id: research
    content:
      title: '🔬 Research'
      subtitle: ''
      text: |-
        My research aims to develop data-driven and distributionally robust optimization methods for operational decision-making under uncertainty. I focus on settings where decision makers have limited distributional information, such as moment information, historical samples, or partial demand signals.

        **Data-driven Supply Chain Network Planning** — I study supply chain network design problems under demand surges and limited distributional information, with an emphasis on tractable reformulations and approximation algorithms.

        **Robust Inventory and Perishable Systems** — I develop robust inventory models for uncertain demand, fixed ordering costs, lead times, and product perishability.

        **Competition, Capacity, and Service Quality** — I study capacity competition, service-quality differentiation, and bilevel decision-making in logistics and supply chain systems.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 📄 Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 📚 All Publications
      text: ''
      count: 0
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: 🧩 Research Projects
      text: |-
        These projects summarize my main research directions in operations research, robust optimization, and supply chain analytics.
      count: 0
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: markdown
    id: teaching
    content:
      title: '👩‍🏫 Teaching'
      subtitle: ''
      text: |-
        **Teaching Assistant**

        - Applied Stochastic Models and Queues, Ph.D. Course, Northeastern University, 2020.
        - Theory of Production and Inventory, Master Course, Northeastern University, 2021.
        - Introduction to System Engineering, Undergraduate Course, Northeastern University, 2020–2022.
    design:
      columns: '1'
  - block: resume-awards
    id: awards
    content:
      title: Awards & Honors
      username: me
  - block: markdown
    id: contact
    content:
      title: '📬 Contact'
      subtitle: ''
      text: |-
        Feel free to reach out if you would like to discuss research ideas or collaborations.

        ✉️ **Email:** [sjiang@stumail.neu.edu.cn](mailto:sjiang@stumail.neu.edu.cn)

        🎓 **Google Scholar:** [scholar profile](https://scholar.google.com/citations?hl=zh-CN&user=2xokQLsAAAAJ)

        🌐 **ResearchGate:** [Songchen Jiang](https://www.researchgate.net/profile/Songchen-Jiang)
    design:
      columns: '1'
---
