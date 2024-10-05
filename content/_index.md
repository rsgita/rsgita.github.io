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
      title: 컴퓨터 공학
      text: 컴퓨터 공학 개인용 홈페이지 입니다.
      announcement:
        text: "자료"
        link:
          text: "바로가기"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gray-100 dark:bg-gray-900"
      
  
    
  - block: features
    id: features
    content:
      title: 전공
      text: 전공 과정에서 배우는것들
      items:
        - name: 알고리즘
          icon: magnifying-glass
          description: 효율 개선을 위한 다양한 알고리즘들에 대해 배움
        - name: 시스템
          icon: rectangle-group
          description: 기본적인 시스템의 구성과 그 작동 환경에 대해 이해
        - name: 프로그래밍
          icon: code - bracket
          description: 다양한 프로그래밍 언어와 환경을 접해보며 실습

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: 자기소개
          text: 권혁준
          feature_icon: box
          features:
            - "전북대학교 컴퓨터인공지능학부"
            - "컴퓨터 공학 전공"
          # Upload image to `assets/media/` and reference the filename here
          image: 134690506.png
          
            
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: check
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
