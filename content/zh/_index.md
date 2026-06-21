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
      username: me_zh
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
  - block: markdown
    id: research
    content:
      title: '🔬 研究方向'
      subtitle: ''
      text: |-
        我的研究致力于发展面向不确定运营决策的数据驱动优化与分布式鲁棒优化方法。我关注决策者仅掌握有限分布信息的情形，例如矩信息、历史样本或部分需求信号。

        **数据驱动的供应链网络规划** —— 研究需求激增和分布信息有限条件下的供应链网络设计问题，重点关注可处理的模型重构和近似算法。

        **鲁棒库存与易逝品系统** —— 构建面向需求不确定、固定订货成本、订货提前期和产品易逝性的鲁棒库存模型。

        **竞争、容量与服务质量** —— 研究物流与供应链系统中的容量竞争、服务质量差异化和双层决策问题。

        以上中文内容为占位文本，你可以后续自行替换。
    design:
      columns: '1'
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
      columns: 2
  - block: collection
    content:
      title: 📚 全部论文
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
      title: 🧩 研究项目
      text: |-
        以下项目概括了我在运筹优化、鲁棒优化与供应链分析方面的主要研究方向。中文内容为占位文本，后续可自行替换。
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
      title: '👩‍🏫 教学经历'
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
      title: 荣誉奖励
      username: me_zh
  - block: markdown
    id: contact
    content:
      title: '📬 联系方式'
      subtitle: ''
      text: |-
        欢迎就研究问题或合作想法与我联系。

        ✉️ **邮箱：** [sjiang@stumail.neu.edu.cn](mailto:sjiang@stumail.neu.edu.cn)

        🎓 **Google Scholar：** [scholar profile](https://scholar.google.com/citations?hl=zh-CN&user=2xokQLsAAAAJ)

        🌐 **ResearchGate：** [Songchen Jiang](https://www.researchgate.net/profile/Songchen-Jiang)
    design:
      columns: '1'
---
