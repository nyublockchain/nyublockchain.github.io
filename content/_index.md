---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Blockchain Lab
      image:
        filename: logo.jpeg

      text: |

        <p, style="margin-bottom:0;font-size:5px;">The Blockchain Lab at NYU Stern is a research lab committed to pushing our frontier of knowledge in the blockchain and Web 3.0 space. We research technology developments and economic forces that shape blockchain platforms to understand how blockchain technologies and Web 3.0 can bring transparency, inclusivity and democracy to the internet.</p> <p>We study a broad range of research topics such as the tensions between decentralization and centralization, the tradeoffs in Layer 2 scaling solutions, and decentralized autonomous organizations. Our theoretical perspectives include platform competition, platform governance, platform policy, game theory, and mechanism design.</p> <p> We regularly attend academic and practitioner's conferences. If you are interested in chatting, please feel free to reach out. We closely collaborate with related research groups across NYU, such as the <a href="https://cs.nyu.edu/crg/">NYU Cryptography group at Courant</a>, and the <a href="https://nyubnf.com/">NYU Blockchain & Fintech </a> </p>.

  - block: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.weight
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true



  
  - block: collection
    id: talks
    content:
      title: Talks
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

 
  - block: collection
    content:
      title: Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

---
