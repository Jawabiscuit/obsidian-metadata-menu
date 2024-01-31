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
  - ctApQa
  - 8tIqiz
  - auZbcA
  - O4nlmp
  - bNCjJU
version: "2.16"
fields:
  - name: author
    type: Input
    options: {}
    path: ""
    id: bNCjJU
  - name: rating
    type: Cycle
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _mm/lookup/star-rating.md
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
  - name: status
    type: Cycle
    options:
      valuesList:
        "1": read-later
        "2": reading
        "3": finished
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: ctApQa
---
