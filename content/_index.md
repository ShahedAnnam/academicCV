---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
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
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: bg3.jpg #stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Mission and Vision'
      subtitle: ''
      text: |-
        **Mission**: My mission is to inspire and empower individuals, especially young minds, to explore the exciting world of technology. Through innovative teaching, engaging projects, and collaborative efforts, I aim to cultivate a passion for coding and problem-solving, enabling others to achieve their potential and contribute meaningfully to the digital landscape. 

        **Vision**: I envision a future where technology bridges gaps and creates opportunities for all. By mastering modern web development, data structures, and algorithms, I strive to build solutions that are not only visually appealing but also impactful and inclusive. My goal is to lead and inspire others to embrace creativity, innovation, and lifelong learning in the tech industry.
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publication
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 2
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: ""
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: false
  #   design:
  #     view: citation
---
