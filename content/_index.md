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
      username: me_bio
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
    id: journal-articles
    content:
      title: '📚 Journal Articles'
      text: ''
      count: 0
      filters:
        folders:
          - publications
        tag: Journal
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: conference-papers
    content:
      title: '📚 Conference Papers'
      text: ''
      count: 0
      filters:
        folders:
          - publications
        tag: Conference
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: working-papers
    content:
      title: '📚 Working Papers and Preprints'
      text: ''
      count: 0
      filters:
        folders:
          - publications
        tag:preprint
        exclude_featured: false
    design:
      view: citation
    
  - block: markdown
    id: service
    content:
      title: '🎓 Academic Service'
      subtitle: ''
      text: |-
        📰 **Reviewer** — I service as a reviewer for journals such as Humanities and Social Sciences Communications, Computers & Industrial Engineering, Information Processing and Management.

        🎤 **Invited Talks** — Recent invited talks include *Distributionally Robust Inventory Management with Independent Demands* (ISCOM 2025 @ Wuxi, Jiangsu) and *Stochastic Modeling and Operations Management of Platform Logistics under Cooperation and Competition* (POMS-China 2026 @ Xi'an, Shaanxi).
    design:
      columns: '1'
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
    design:
      date_format: 'January 2006'
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
