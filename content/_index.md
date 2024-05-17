---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: 有缘点进这个网页的朋友，你好
      text: 我是一直懒得给自己起名字的普通同人作者小A，这是一个通过hugo和github以及visual studio实现的一个存档库，里面收集了我17年至今所有的全职高手、乙女游戏等的同人作品，希望你阅读愉快~
      primary_action:
        text: 归档目录
        url: https://hugoblox.com/templates/details/docs/
        icon: rocket-launch
      secondary_action:
        text: 开始阅读
        url: /docs/
      announcement:
        text: "如果你也想要构建一个自己的网站"
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: ""
      background:
        color: ""
        image:
          # Add your image background to `assets/media/`.
          filename: ""
          filters:
            brightness: 0.5
  - block: features
    id: features
    content:
      title: Features
      text: Collaborate, publish, and maintain technical knowledge with an all-in-one documentation site. Used by 100,000+ startups, enterprises, and researchers.
      items:
        - name: Optimized SEO
          icon: magnifying-glass
          description: Automatic sitemaps, RSS feeds, and rich metadata take the pain out of SEO and syndication.
        - name: Fast
          icon: bolt
          description: Super fast page load with Tailwind CSS and super fast site building with Hugo.
        - name: Easy
          icon: sparkles
          description: One-click deployment to GitHub Pages. Have your new website live within 5 minutes!
        - name: No-Code
          icon: code-bracket
          description: Edit and design your site just using rich text (Markdown) and configurable YAML parameters.
        - name: Highly Rated
          icon: star
          description: Rated 5-stars by the community.
        - name: Swappable Blocks
          icon: rectangle-group
          description: Build your pages with blocks - no coding required!
  - block: cta-card
    content:
      title: "Start Writing with the #1 Effortless Documentation Platform"
      text: Hugo Blox Docs Theme brings all your technical knowledge together in a single, centralized knowledge base. Easily search and edit it with the tools you use every day!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/details/docs/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
