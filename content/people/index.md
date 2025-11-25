---
title: People
type: landing

sections:
  - block: hero
    content:
      title: Meet the team     
      text: From the University College London, the University of Zürich and Arup 
    design:
      background:
        image: 
          filename: 'welcome.jpg'
          filters:
            brightness: '0.5'
        text_color_light: true
        color: '#333'
  - block: people
    content:
      title: 
      user_groups:
          - Principal Investigators
          - Postdoc Researchers
          - PhD Researchers
          - Research Assistants
          - Administration
      sort_by: Params.last_name
      sort_ascending: false
    design:
      show_interests: false
      show_role: true
      show_social: true
---