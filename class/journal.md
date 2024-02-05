---
fields:
  - name: series
    type: Boolean
    options: {}
    path: ""
    id: 8gJAq1
  - name: bar
    type: Input
    options: {}
    path: ""
    id: iJhqDP
  - name: nav
    type: Input
    options: {}
    style:
      italic: true
    path: ""
    id: vYcbSl
  - name: project
    type: File
    options:
      dvQueryString: dv.pages("#project").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: W3vq5Q
version: "2.12"
limit: 20
mapWithTag: false
icon: pen-tool
tagNames:
  - journal
filesPaths:
  - journal
bookmarksGroups: 
excludes: 
extends: note
savedViews: []
favoriteView: 
fieldsOrder:
  - W3vq5Q
  - 8gJAq1
  - vYcbSl
  - iJhqDP
---
