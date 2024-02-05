---
fields:
  - name: title
    type: Input
    options: {}
    path: ""
    id: yWSQQW
  - name: tags
    type: Multi
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _mm/lookup/tags.md
      valuesFromDVQuery: ""
    path: ""
    id: krAekW
  - name: status
    type: Cycle
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _mm/lookup/note-status.md
      valuesFromDVQuery: ""
    command:
      id: insert__note__status
      icon: repeat
      label: Insert status field
    path: ""
    id: teB04C
  - name: cssClasses
    type: YAML
    options: {}
    path: ""
    id: T8p6oo
version: "2.37"
limit: 20
mapWithTag: false
icon: pen
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: all
savedViews: []
favoriteView: 
fieldsOrder:
  - yWSQQW
  - krAekW
  - teB04C
  - T8p6oo
---
