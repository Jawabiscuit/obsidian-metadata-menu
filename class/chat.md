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
extends: note
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
  - DF2ISD
  - DPVusy
  - 9wWvJj
  - ABxp0u
version: "2.82"
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
  - name: system_commands
    type: YAML
    options: {}
    path: ""
    id: DF2ISD
  - name: template
    type: File
    options:
      dvQueryString: dv.pages('"_template/chat/prompt"')
    path: ""
    id: DPVusy
  - name: max_tokens
    type: Select
    options:
      valuesList:
        "1": "512"
        "2": "1024"
        "3": "2048"
        "4": "4096"
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
      dvQueryString: dv.pages("#project")
    path: ""
    id: 9wWvJj
  - name: parent
    type: File
    options: {}
    path: ""
    id: ABxp0u
---
