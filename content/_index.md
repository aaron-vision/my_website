---
title: 首页
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: "rb3 我是一名从事视觉科学与眼科临床研究的研究者，关注双眼视觉、间歇性外斜视、眼动与视觉信息处理、视觉神经科学与意识等方向。"
      button:
        text: 更多信息
        url: /about/
      headings:
        about: 关于我 rb3 headings about
        education: 教育背景 rb3 headings 
        interests: 研究兴趣 rb3 headings 
    design:
      background:
        gradient_mesh:
          enable: true
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  # - block: markdown
    # content:
      # title: 个人简介
      # text: |
        

        # [更多...](/about/)

  - block: markdown
    content:
      title: 研究与成果
      text: |
        围绕双眼视觉异常、眼动特征、视觉信息处理及相关机制开展研究。
        
        [查看详情](/research/)

  - block: collection
    content:
      title: 学术动态
      filters:
        folders:
          - news
      count: 3

  - block: collection
    content:
      title: 科普与随笔
      filters:
        folders:
          - outreach
      count: 3

  - block: markdown
    content:
      title: rb3 联系方式
      text: |
        aaronchangshuai@outlook.com  
        单位：中山大学中山眼科中心  
        [查看完整联系方式](/contact/)
---