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
      title: computer engineering
      text: computer engineering private site
      announcement:
        text: "inform"
        link:
          text: "link"
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
      title: major
      text: stdying in major
      items:
        - name: algorith
          icon: magnifying-glass
          description: Learn about various algorithms to improve efficiency
        - name: system
          icon: rectangle-group
          description: Understand basic system configuration and operating environment
        - name: programming
          icon: code-bracket
          description: Experience and practice with various programming languages ​​and environments

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: intorduction
          text: Kwon hyeokjun
          feature_icon: check
          features:
            - "Chonbuk National University Department of Computer and Artificial Intelligence"
            - "Computer Engineering Major"
          # Upload image to `assets/media/` and reference the filename here
          image: 134690506.png
          button:
            text: github link
            url: https://github.com/rsgita
            
        - title: contact
          text: Please contact at the following address
          feature_icon: check
          features:
            - "e-mail: 202011612@jbnu.ac.kr"
            - "Address: 567 Baekje-daero, Deokjin-gu, Jeonju-si, Jeollabuk-do"
          # Upload image to `assets/media/` and reference the filename here
          image: phone-call.png
          button:
            text: University
            url: https://www.jbnu.ac.kr/kor/

    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
---
