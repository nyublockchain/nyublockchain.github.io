---
# Leave the homepage title empty to use the site title
title: "Research and Discussion Group"
date: 2022-10-24
type: landing

sections:
  # About Us section
  - block: about.biography
    id: about
    design:
      spacing:
        padding: ["50px", "0", "50px", "0"]
    content:
      title: About Blockchain Lab
      username: admin

  # Affiliates section
  - block: experience
    id: affiliates
    content:
      title: Affiliates
      subtitle: Blockchain Lab Members
      text: |-
        {{< teamSection >}}
      count: 1
    design:
      columns: "2"
    
  # Talks section
  - block: collection
    id: future_talks
    content:
      title: Upcoming Talks
      subtitle: ""
      text: ""
  # Choose how many pages you would like to display (0 = all pages)
      count: 0
  # Filter on criteria
      filters:
        folders:
          - future_talks
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
  # Choose how many pages you would like to offset by
      offset: 0
  # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
  # Choose a layout view
      view: compact
      columns: "2"


  # Talks section
  - block: collection
    id: talks
    content:
      title: Past Talks
      subtitle: ""
      text: ""
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        folders:
          - past_talks
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: "2"


  # Working Papers
  - block: collection
    id: papers
    content:
      title: Working Papers
      filters:
        folders:
          - post
        featured_only: false
        count: 0
    design:
      columns: "2"
      view: card

  # Publications
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
        count: 0
    design:
      columns: "2"
      view: card

---
