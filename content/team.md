---
title: "Grasper Lab Team"
type: landing
show_date: false

sections:
  - block: markdown  
    content:
      text: |
        <div style="margin-bottom: -10rem;">
          <h2 style="margin-bottom: 0.5rem;">Welcome to Our Lab</h2>
          <p>We all love our research and share a passion for food.
          If you want to join our team, please get in touch!</p>
        </div>
        <style>
          /* Hide the date inside card views on this page */
          .section-heading + .article-grid time,
          .section-heading + .article-grid .article-metadata {
            display: none !important;
          }
        </style>
  - block: collection
    content:
      title: "Meet the Team"
      count: 0            
      filters:
        folders:
          - people   
        exclude:
          kinds: 
          - section
      sort_by: weight
      sort_ascending: true
    design:
      view: card          
      columns: 3
      show_role: true
      show_organizations: true
      show_date: false
  - block: markdown
    content:
      text: |
        <style>
          h2#alumni { margin-top: -35rem !important; }
        </style>
      title: "Alumni"
      text: |
        {{< alumni >}}
---
