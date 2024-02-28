---
limit: 20
mapWithTag: false
icon: users
tagNames:
  - interview
  - meeting
filesPaths:
  - meeting
bookmarksGroups: 
excludes: 
extends: meeting
savedViews: []
favoriteView: 
fieldsOrder:
  - VETGWV
  - Dvznsa
version: "2.9"
fields:
  - name: job-post
    type: File
    options:
      dvQueryString: 'dv.pages("#job-post or #games-job or #vfx-job").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))'
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: Dvznsa
  - name: company
    type: File
    options:
      dvQueryString: 'dv.pages("#company or #game-company or #vfx-company").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))'
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: VETGWV
---
