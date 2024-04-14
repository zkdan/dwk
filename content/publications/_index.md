---
# Leave the homepage title empty to use the site title
title: Publications
summary: Published articles

date: 2022-10-24
type: page
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
  # - block: about.biography
  #   id: about
  #   content:
  #     title: Biography
  - block: collection
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