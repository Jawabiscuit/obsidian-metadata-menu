---
limit: 20
mapWithTag: false
icon: factory
tagNames:
  - project
filesPaths:
  - project
bookmarksGroups: 
excludes: 
extends: note
savedViews: []
favoriteView: 
fieldsOrder:
  - iiK0Fy
  - HCQ2Cj
  - TmF0N9
  - i3AE7B
  - rN1q46
version: "2.37"
fields:
  - name: subtitle
    type: Input
    options: {}
    path: ""
    id: rN1q46
  - name: projectDV
    type: Input
    options: {}
    path: ""
    id: i3AE7B
  - name: bar
    type: Input
    options: {}
    path: ""
    id: TmF0N9
    style:
      italic: true
  - name: img
    type: MultiMedia
    options:
      folders:
        - attachment
      embed: false
      display: card
      thumbnailSize: "400"
      customSorting: a.stat.ctime - b.stat.ctime
    path: ""
    id: HCQ2Cj
  - name: goal
    type: File
    options:
      dvQueryString: dv.pages("#goal").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customSorting: a.created - b.created
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
    display: asArray
    path: ""
    id: iiK0Fy
---
