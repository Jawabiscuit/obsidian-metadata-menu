---
limit: 20
mapWithTag: true
icon: pin
tagNames:
  - job-post
filesPaths: 
bookmarksGroups: 
excludes: 
extends: resource
savedViews: []
favoriteView: 
fieldsOrder:
  - wWE1q5
  - enL7qi
  - 93ONbB
  - 30rn3C
  - OVaDfX
  - PIpDtX
  - 5nojoz
  - Aw6TGg
  - jSs3bH
  - 11pd5G
  - 0N3ZIi
  - uMR6kL
version: "2.44"
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
  - name: workFrom
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
  - name: jobType
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
  - name: lastContact
    type: Date
    options:
      dateFormat: YYYY-MM-DD
      defaultInsertAsLink: "false"
    path: ""
    id: jSs3bH
    command:
      id: insert__job-post__lastContact
      icon: calendar
      label: Insert lastContact field
  - name: appSent
    type: DateTime
    options:
      dateFormat: YYYY-MM-DD HH:mm
      defaultInsertAsLink: "false"
    command:
      id: insert__job-post__appSent
      icon: calendar-clock
      label: Insert appSent field
    path: ""
    id: Aw6TGg
  - name: status
    type: Cycle
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _mm/lookup/job-status.md
      valuesFromDVQuery: ""
    path: ""
    id: 5nojoz
  - name: recruiterLink
    type: Input
    options: {}
    path: ""
    id: PIpDtX
  - name: directLink
    type: Input
    options: {}
    path: ""
    id: OVaDfX
  - name: project
    type: File
    options:
      dvQueryString: dv.pages("#project").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: 30rn3C
  - name: company
    type: File
    options:
      dvQueryString: dv.pages("#company").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: 93ONbB
  - name: applied
    type: Boolean
    options: {}
    path: ""
    id: enL7qi
  - name: overview
    type: Input
    options: {}
    path: ""
    id: wWE1q5
---
