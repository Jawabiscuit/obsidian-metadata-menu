---
limit: 20
mapWithTag: true
icon: pin
tagNames: 
filesPaths:
  - library
bookmarksGroups: 
excludes: 
extends: note
savedViews: []
favoriteView: 
fieldsOrder:
  - Aw6TGg
  - jSs3bH
  - 11pd5G
  - 0N3ZIi
  - uMR6kL
version: "2.20"
fields:
  - name: active
    type: Boolean
    options: {}
    command:
      id: insert__job-post__active
      icon: switch
      label: Insert active field
    path: ""
    id: uMR6kL
  - name: work-from
    type: Select
    options:
      valuesList:
        "1": remote
        "2": on-site
        "3": hybrid
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: 0N3ZIi
  - name: job-type
    type: Select
    options:
      valuesList:
        "1": full-time
        "2": part-time
        "3": contract
        "4": freelance
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: 11pd5G
  - name: last-contact
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: jSs3bH
    command:
      id: insert__jSs3bH
      icon: calendar
      label: Insert last-contact field
  - name: app-sent
    type: DateTime
    options:
      dateFormat: YYYY-MM-DD HH:mm
      defaultInsertAsLink: "false"
    command:
      id: insert__job-post__app-sent
      icon: calendar-clock
      label: Insert app-sent field
    path: ""
    id: Aw6TGg
---
