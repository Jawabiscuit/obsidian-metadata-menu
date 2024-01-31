---
limit: 20
mapWithTag: false
icon: pin
tagNames:
  - vfx-job
filesPaths: 
bookmarksGroups: 
excludes: 
extends: job-post
savedViews: []
favoriteView: 
fieldsOrder:
  - YEhVKC
version: "2.3"
fields:
  - name: company
    type: File
    options:
      dvQueryString: dv.pages("#vfx-company").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: YEhVKC
---
