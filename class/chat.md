---
limit: 20
mapWithTag: false
icon: message-square
tagNames:
  - chat
filesPaths:
  - chat
bookmarksGroups: 
excludes: 
extends: all
savedViews: []
favoriteView: 
fieldsOrder:
  - T3pJKS
  - jpLBRa
  - SCIpxB
  - XeoeTm
  - uQ2PV6
  - QIp4L6
  - VxWSX7
  - HWEH6r
  - 5qj65J
  - WIpc8v
  - DPVusy
  - 9wWvJj
version: "2.147"
fields:
  - name: temperature
    type: Number
    options:
      step: 0.1
      min: 0
      max: 1
    path: ""
    id: jpLBRa
  - name: top_p
    type: Number
    options:
      step: 0.1
      min: 0
      max: 1
    path: ""
    id: SCIpxB
  - name: presence_penalty
    type: Number
    options:
      step: 0.1
      min: 0
      max: 2
    path: ""
    id: uQ2PV6
  - name: frequency_penalty
    type: Number
    options:
      step: 0.1
      min: 0
      max: 2
    path: ""
    id: QIp4L6
  - name: stream
    type: Boolean
    options: {}
    path: ""
    id: VxWSX7
  - name: stop
    type: Input
    options: {}
    path: ""
    id: HWEH6r
  - name: n
    type: Number
    options: {}
    path: ""
    id: 5qj65J
  - name: template
    type: File
    options:
      dvQueryString: dv.pages('"_templates/chat/prompt"')
    path: ""
    id: DPVusy
  - name: max_tokens
    type: Select
    options:
      valuesList:
        "1": "4096"
        "2": "512"
        "3": "1024"
        "4": "2048"
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: XeoeTm
  - name: model
    type: Select
    options:
      valuesList: {}
      sourceType: ValuesListNotePath
      valuesListNotePath: _mm/lookup/model.md
      valuesFromDVQuery: ""
    path: ""
    id: T3pJKS
  - name: project
    type: File
    options:
      dvQueryString: dv.pages("#project").where(p => ["_templates", "_mm"].every(path => !p.file.path.includes(path)))
      customRendering: "page.file.aliases.length ? page.file.aliases[0] : page.file.name"
      customSorting: a.created - b.created
    path: ""
    id: 9wWvJj
  - name: system_commands
    type: YAML
    options: {}
    path: ""
    id: WIpc8v
---
