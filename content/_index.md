---
title: ""
summary: ""
date: 2026-03-11
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ""
      button:
        text: 下载简历 (CV)
        url: uploads/resume.pdf
      headings:
        about: 关于我
        education: 教育背景
        interests: 研究兴趣
    design:
      background:
        gradient_mesh:
          enable: true
      # Name heading sizing to accommodate long or short names
      name:
        size: lg # Options: xs, sm, md, lg (default), xl

      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    content:
      title: "研究使命 (My Research)"
      subtitle: ""
      text: |
        我的研究致力于构建**“视觉韧性 (Visual Resilience)”**评估体系。

        通过结合心理物理学、多模态成像（fMRI/EEG）和眼动追踪技术，我试图解析大脑在面对视觉损伤（如斜视、复视）时，如何通过神经可塑性进行代偿。

        目前主持国家自然科学基金项目：探索心盲症个体在视觉工作记忆中的灵活表征机制。
    design:
      columns: "1"

  - block: collection
    id: news
    content:
      title: 最新动态
      page_type: event
      count: 5
    design:
      view: card
      columns: 2

  - block: collection
    id: papers
    content:
      title: 代表性论文
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
---
