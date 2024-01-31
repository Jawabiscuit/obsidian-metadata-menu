---
limit: 20
mapWithTag: false
icon: file-text
tagNames: 
filesPaths:
  - document
bookmarksGroups: 
excludes: 
extends: note
savedViews: []
favoriteView: 
fieldsOrder:
  - nYNr1r
version: "2.5"
fields:
  - name: project
    type: File
    options:
      dvQueryString: dv.pages("#project").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: nYNr1r
---
