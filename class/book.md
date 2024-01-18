---
limit: 20
mapWithTag: false
icon: book
tagNames:
  - book
filesPaths:
  - book
bookmarksGroups: 
excludes: 
extends: note
savedViews: []
favoriteView: 
fieldsOrder:
  - 8tIqiz
  - auZbcA
  - O4nlmp
  - 0NzPSI
  - bNCjJU
version: "2.13"
fields:
  - name: author
    type: Input
    options: {}
    path: ""
    id: bNCjJU
  - name: reference
    type: Input
    options: {}
    path: ""
    id: 0NzPSI
  - name: rating
    type: Cycle
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _lookup/star-rating.md
      valuesFromDVQuery: ""
    command:
      id: insert__book__rating
      icon: repeat
      label: Insert rating field
    path: ""
    id: O4nlmp
  - name: reviewed
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: auZbcA
  - name: finished
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: 8tIqiz
---
