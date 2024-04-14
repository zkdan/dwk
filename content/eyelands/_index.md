---
# Leave the homepage title empty to use the site title
title: Eyelands Lab
summary: The Eyelands Lab/ØyeLab is a lab dedicated to understanding what knowledge humans have about their languages and how they put that knowledge to use in real-time language processing. We are jointly based in the Department of Language Studies at UTSC and Department of Language and Literature at NTNU. The lab is affiliated with the CAP Lab at UTSC.

date: 2022-10-24
type: page

sections:
  - block: about
    id: about
    author: admin
    username: admin
    content:
      title: About Eyelands Lab
  - block: collection
    id: members
    text: Hello this is the lab
    content:
      title: Lab members
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