---
# 首页配置
title: ''
summary: ''
date: 2026-03-11
type: landing

design:
  spacing: '6rem'

sections:
  # 1. 个人简介模块
  - block: resume-biography-3
    content:
      # 核心修正：关联到你的 content/authors/admin/ 文件夹
      username: admin 
      text: ''
      button:
        text: 下载简历 (CV)
        url: uploads/resume.pdf
      headings:
        about: '关于我'
        education: '教育背景'
        interests: '研究兴趣'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # 2. 核心科研使命模块
  - block: markdown
    content:
      title: '📚 研究使命 (My Research)'
      subtitle: ''
      text: |-
        我的研究致力于构建**“视觉韧性 (Visual Resilience)”**评估体系。 
        
        通过结合心理物理学、多模态成像 ($fMRI/EEG$) 和眼动追踪技术，我试图解析大脑在面对视觉损伤（如斜视、复视）时，如何通过神经可塑性进行代偿。 
        
        目前主持国家自然科学基金项目：探索心盲症个体在视觉工作记忆中的灵活表征机制。
    design:
      columns: '1'

  # 3. 最近动态 (News)
  - block: collection
    id: news
    content:
      title: 最新动态
      subtitle: ''
      text: ''
      page_type: events # 对应 content/post/ 下的内容
      count: 5
      filters:
        exclude_featured: false
    design:
      view: card
      columns: 2

  # 4. 代表性论著 (Publications)
  - block: collection
    id: papers
    content:
      title: 代表性论文
      filters:
        folders:
          - publication # 对应 content/publication/
        featured_only: true
    design:
      view: article-grid
      columns: 2
---