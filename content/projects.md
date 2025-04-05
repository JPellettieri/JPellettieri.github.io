---
title: 'Projects'
date: 2024-05-19
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  # A section to display blog posts
  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: ""
      text: A selection of projects I've worked on in the past few years
      # Display content from the `content/project/` folder
      filters:
        folders:
          - project
    design:
      columns: '3'
      # Choose your content listing view 
      view: article-grid
      fill_image: true
      # For the Showcase view, do you want to flip alternate rows?
      #flip_alt_rows: true
---
