---
limit: 20
mapWithTag: true
icon: pin
tagNames:
  - games-job
filesPaths: 
bookmarksGroups: 
excludes: 
extends: job-post
savedViews: []
favoriteView: 
fieldsOrder:
  - 72HgLW
version: "2.10"
fields:
  - name: company
    type: File
    options:
      dvQueryString: dv.pages("#game-company").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: 72HgLW
---
