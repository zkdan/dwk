---
# Leave the homepage title empty to use the site title
title: Publication 
summary: The Eyelands Lab/ØyeLab is a lab dedicated to understanding what knowledge humans have about their languages and how they put that knowledge to use in real-time language processing. We are jointly based in the Department of Language Studies at UTSC and Department of Language and Literature at NTNU. The lab is affiliated with the CAP Lab at UTSC.

date: 2022-10-24
type: landing
cms_exclude: true

# View.
#   1 = List
#   2 = Compact
#   3 = Card
#   4 = Citation
view: 4

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''

sections:
  - block: about.biography
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

---