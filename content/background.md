---
title: 'Background'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: '2006'
      # Education or Experience section first?
      is_education_first: true
      color: blue
  - block: resume-skills
    content:
      title: Skills 
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-awards
    content:
      title: Awards
      username: admin
    design:
      # Hugo date format
      date_format: '2006'
---