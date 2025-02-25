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
      subtitle: A subtitle
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      # Display content from the `content/project/` folder
      filters:
        folders:
          - project
    design:
      columns: '2'
      # Choose your content listing view 
      view: article-grid
      fill_image: true
      # For the Showcase view, do you want to flip alternate rows?
      #flip_alt_rows: true
---
