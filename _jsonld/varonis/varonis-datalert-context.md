---
api_specs:
- filename: varonis-datalert-openapi.yml
  format: yaml
  label: Varonis DatAlert API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/openapi/varonis-datalert-openapi.yml
class_count: 13
classes:
- AddNoteRequest
- Alert
- AlertedEvent
- AlertedEventsResponse
- AlertsResponse
- CloseAlertRequest
- GetAlertedEventsRequest
- GetAlertsRequest
- SuccessResponse
- ThreatModel
- ThreatModelsResponse
- UpdateAlertStatusRequest
- name
context_file: json-ld/varonis-datalert-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/json-ld/varonis-datalert-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Varonis Datalert from Varonis.
layout: jsonld
name: Varonis Datalert Context
namespaces:
- prefix: varonis
  uri: https://www.varonis.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: alertId
  type: string
- container: ''
  name: note
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: time
  type: dateTime
- container: ''
  name: severity
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: closeReason
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: userAccountType
  type: string
- container: ''
  name: userDepartment
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: isMaliciousIP
  type: boolean
- container: ''
  name: assetPath
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: eventCount
  type: integer
- container: ''
  name: isFlagged
  type: boolean
- container: ''
  name: containsSensitiveData
  type: boolean
- container: ''
  name: operationType
  type: string
- container: ''
  name: sourceAccount
  type: string
- container: ''
  name: destinationAccount
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: ipReputation
  type: string
- container: set
  name: events
  type: string
- container: ''
  name: totalCount
  type: integer
- container: set
  name: alerts
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: lastDays
  type: integer
- container: set
  name: extraFields
  type: string
- container: ''
  name: descendingOrder
  type: boolean
- container: set
  name: threatModelName
  type: string
- container: set
  name: alertStatus
  type: string
- container: set
  name: alertSeverity
  type: string
- container: ''
  name: maxResults
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: success
  type: boolean
- container: ''
  name: message
  type: string
- container: ''
  name: source
  type: string
- container: set
  name: threatModels
  type: string
property_count: 43
provider_name: Varonis
provider_slug: varonis
slug: varonis-datalert-context
source_filename: varonis-datalert-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"varonis\": \"https://www.varonis.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddNoteRequest\": \"varonis:AddNoteRequest\",\n    \"Alert\": \"varonis:Alert\",\n    \"AlertedEvent\": \"varonis:AlertedEvent\",\n    \"AlertedEventsResponse\": \"varonis:AlertedEventsResponse\",\n    \"AlertsResponse\": \"varonis:AlertsResponse\",\n    \"CloseAlertRequest\": \"varonis:CloseAlertRequest\",\n    \"GetAlertedEventsRequest\": \"varonis:GetAlertedEventsRequest\",\n    \"GetAlertsRequest\": \"varonis:GetAlertsRequest\",\n    \"SuccessResponse\": \"varonis:SuccessResponse\",\n    \"ThreatModel\": \"varonis:ThreatModel\",\n    \"ThreatModelsResponse\": \"varonis:ThreatModelsResponse\",\n    \"UpdateAlertStatusRequest\": \"varonis:UpdateAlertStatusRequest\",\n    \"alertId\": {\n      \"@id\": \"varonis:alertId\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"note\": {\n      \"@id\": \"varonis:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"varonis:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"time\": {\n      \"@id\": \"varonis:time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"severity\": {\n      \"@id\": \"varonis:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"varonis:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"varonis:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeReason\": {\n      \"@id\": \"varonis:closeReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"varonis:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"varonis:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"varonis:userName\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"userAccountType\": {\n      \"@id\": \"varonis:userAccountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userDepartment\": {\n      \"@id\": \"varonis:userDepartment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"varonis:deviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isMaliciousIP\": {\n      \"@id\": \"varonis:isMaliciousIP\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"assetPath\": {\n      \"@id\": \"varonis:assetPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"varonis:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventCount\": {\n      \"@id\": \"varonis:eventCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isFlagged\": {\n      \"@id\": \"varonis:isFlagged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"containsSensitiveData\": {\n      \"@id\": \"varonis:containsSensitiveData\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"operationType\": {\n      \"@id\": \"varonis:operationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceAccount\": {\n      \"@id\": \"varonis:sourceAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationAccount\": {\n      \"@id\": \"varonis:destinationAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"varonis:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"varonis:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipReputation\": {\n      \"@id\": \"varonis:ipReputation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"varonis:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"varonis:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alerts\": {\n      \"@id\": \"varonis:alerts\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"varonis:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"varonis:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastDays\": {\n      \"@id\": \"varonis:lastDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"extraFields\": {\n      \"@id\": \"varonis:extraFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descendingOrder\": {\n      \"@id\": \"varonis:descendingOrder\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"threatModelName\": {\n      \"@id\": \"varonis:threatModelName\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertStatus\": {\n      \"@id\": \"varonis:alertStatus\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertSeverity\": {\n      \"@id\": \"varonis:alertSeverity\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"maxResults\": {\n      \"@id\": \"varonis:maxResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"varonis:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"success\": {\n      \"@id\": \"varonis:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"message\": {\n      \"@id\": \"varonis:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"varonis:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatModels\": {\n      \"@id\": \"varonis:threatModels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/varonis/refs/heads/main/json-ld/varonis-datalert-context.jsonld
tags:
- Cloud Security
- Compliance
- Data Analytics
- Data Governance
- Data Security
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
