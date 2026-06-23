---
title: ''
summary: ''
date: 2026-06-21
type: landing

design:
  spacing: '2rem'

sections:
  - block: resume-biography-3
    content:
      username: me_zh_bio
      text: ''
      headings:
        about: '个人简介'
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
      username: me_zh
    design:
      date_format: 'January 2006'
      is_education_first: false
    
  - block: collection
    id: papers
    content:
      title: 📄 代表性论文
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
    
  - block: collection
    id: journal-articles
    content:
      title: '📚 期刊论文'
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
      title: '📚 会议论文'
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
      title: '📚 工作论文'
      text: ''
      count: 0
      filters:
        folders:
          - publications
        tag: Working Paper
        exclude_featured: false
    design:
      view: citation
    
  - block: markdown
    id: service
    content:
      title: '🎓 学术服务'
      subtitle: ''
      text: |-
        📰 **审稿人** — 我目前担任Nature子刊Humanities and Social Sciences Communications, 国际期刊Computers & Industrial Engineering, Information Processing and Management等领域期刊审稿人.

        🎤 **受邀报告**— *Distributionally Robust Inventory Management with Independent Demands* (ISCOM 2025 @ 江苏·无锡) *Stochastic Modeling and Operations Management of Platform Logistics under Cooperation and Competition* (POMS-China 2026 @ 陕西·西安).
    design:
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: '👩‍🏫 教学'
      subtitle: ''
      text: |-
        **助教经历**

        - 应用随机模型与排队论，博士课程，东北大学，2020。
        - 生产与库存理论，硕士课程，东北大学，2021。
        - 系统工程导论，本科课程，东北大学，2020–2022。
    design:
      columns: '1'
  - block: resume-awards
    id: awards
    content:
      title: 获奖与荣誉
      username: me_zh
    design:
      date_format: 'January 2006'
  - block: markdown
    id: contact
    content:
      title: '📬 联系方式'
      subtitle: ''
      text: |-
        欢迎就研究问题或合作想法与我联系。
    
        ✉️ **Email:** [sjiang@stumail.neu.edu.cn](mailto:sjiang@stumail.neu.edu.cn)

        🎓 **Google Scholar:** [scholar profile](https://scholar.google.com/citations?hl=zh-CN&user=2xokQLsAAAAJ)

        🌐 **ResearchGate:** [Songchen Jiang](https://www.researchgate.net/profile/Songchen-Jiang)
    design:
      columns: '1'
---
