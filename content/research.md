---
title: 'Research and Development'
date: 2024-05-19
type: landing
url: /research/

design:
  # Section spacing
  spacing: '5rem'

# Page Sections
sections:
  - block: markdown
    id: papers
    content:
      title: "My Research"
      subtitle: ""
      text: |-
        I design **secure cloud architectures** with a focus on **Confidential Computing** and
        **defence-grade data platforms**. My work covers attestation, data integrity and
        compliance in multi-cloud settings – from healthcare data (DigiMed) to **NATO-aligned**
        architectures.

        **Focus areas**
        - Confidential Computing (AMD SEV-SNP, Nitro Enclaves) & remote attestation  
        - Cloud security architecture & data sovereignty (NAFv4, ISO 27001)  
        - Risk & resilience with AI support in critical infrastructures

        **Selected theses:**  
        → [Master’s Thesis – Connected Defence](/project/master-thesis/) ·
        [Bachelor's Thesis – Confidential Computing in HPC Clouds](/project/bachelor-thesis/)
    design:
      columns: '1'
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
#   - block: collection
#     id: talks
#     content:
#       title: Events
#       filters:
#         folders:
#           - event
#     design:
#       view: article-grid
#       columns: 1
#   - block: collection
#     id: news
#     content:
#       title: News
#       subtitle: ''
#       text: ''
#       # Page type to display. E.g. post, talk, publication...
#       page_type: post
#       # Choose how many pages you would like to display (0 = all pages)
#       count: 5
#       # Filter on criteria
#       filters:
#         author: ""
#         category: ""
#         tag: ""
#         exclude_featured: false
#         exclude_future: false
#         exclude_past: false
#         publication_type: ""
#       # Choose how many pages you would like to offset by
#       offset: 0
#       # Page order: descending (desc) or ascending (asc) date.
#       order: desc
#     design:
#       # Choose a layout view
#       view: date-title-summary
#       # Reduce spacing
#       spacing:
#         padding: [0, 0, 0, 0]
---