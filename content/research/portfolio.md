---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://wowchemy.com/docs/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 0

title: 'Research'
subtitle: 'Research Projects within the PEASE Lab'

content:
  # Page type to display. E.g. project.
  page_type: project
  exclude_tags:
    -SoN
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 1

  Filter toolbar (optional).
  Add or remove as many filters (`filter_button` instances) as you like.
  To show all items, set `tag` to "*".
  To filter by a specific tag, set `tag` to an existing tag name.
  To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Current Projects
      tag: CP
    - name: Past Projects
      tag: PP

design:
  columns: '1'
  view: 5
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---