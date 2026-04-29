---
class_count: 11
classes:
- CreateEntryRequest
- CreateIncidentRequest
- Entry
- Incident
- IncidentSearchRequest
- IncidentSearchResponse
- Integration
- IntegrationInstance
- Investigation
- Playbook
- UpdateIncidentRequest
context_file: json-ld/palo-alto-cortex-xsoar-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsoar-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cortex Xsoar Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cortex Xsoar Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CustomFields
  type: reference
- container: ''
  name: asc
  type: boolean
- container: ''
  name: beta
  type: boolean
- container: ''
  name: brand
  type: string
- container: ''
  name: byFrom
  type: dateTime
- container: ''
  name: byTo
  type: dateTime
- container: ''
  name: category
  type: string
- container: ''
  name: closeNotes
  type: string
- container: ''
  name: closeReason
  type: string
- container: ''
  name: closed
  type: dateTime
- container: ''
  name: configuration
  type: reference
- container: ''
  name: contents
  type: string
- container: ''
  name: createInvestigation
  type: boolean
- container: ''
  name: created
  type: dateTime
- container: ''
  name: data
  type: string
- container: ''
  name: deprecated
  type: boolean
- container: ''
  name: description
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: display
  type: string
- container: ''
  name: enabled
  type: string
- container: set
  name: entries
  type: reference
- container: ''
  name: field
  type: string
- container: ''
  name: filter
  type: reference
- container: ''
  name: fromDate
  type: dateTime
- container: ''
  name: fromVersion
  type: string
- container: ''
  name: humanReadable
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: incidentId
  type: string
- container: set
  name: incidents
  type: reference
- container: ''
  name: incomingMapperId
  type: string
- container: ''
  name: investigationId
  type: string
- container: ''
  name: isIntegrationScript
  type: boolean
- container: set
  name: labels
  type: reference
- container: ''
  name: mappingId
  type: string
- container: ''
  name: markdown
  type: boolean
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: occurred
  type: dateTime
- container: ''
  name: owner
  type: string
- container: ''
  name: page
  type: integer
- container: ''
  name: period
  type: reference
- container: ''
  name: playbookId
  type: string
- container: ''
  name: query
  type: string
- container: ''
  name: rawJson
  type: string
- container: ''
  name: relation
  type: string
- container: set
  name: runningPlaybooks
  type: string
- container: ''
  name: searchResultTotal
  type: integer
- container: ''
  name: severity
  type: integer
- container: ''
  name: size
  type: integer
- container: set
  name: sort
  type: reference
- container: ''
  name: sourceBrand
  type: string
- container: ''
  name: sourceInstance
  type: string
- container: ''
  name: status
  type: integer
- container: set
  name: tags
  type: string
- container: ''
  name: toDate
  type: dateTime
- container: ''
  name: toVersion
  type: string
- container: ''
  name: total
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: version
  type: integer
property_count: 61
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cortex-xsoar-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateEntryRequest\": \"pan:CreateEntryRequest\",\n    \"CreateIncidentRequest\": \"pan:CreateIncidentRequest\",\n    \"Entry\": \"pan:Entry\",\n    \"Incident\": \"pan:Incident\",\n    \"IncidentSearchRequest\": \"pan:IncidentSearchRequest\",\n    \"IncidentSearchResponse\": \"pan:IncidentSearchResponse\",\n    \"Integration\": \"pan:Integration\",\n    \"IntegrationInstance\": \"pan:IntegrationInstance\",\n    \"Investigation\": \"pan:Investigation\",\n    \"Playbook\": \"pan:Playbook\",\n    \"UpdateIncidentRequest\": \"pan:UpdateIncidentRequest\",\n    \"CustomFields\": {\n      \"@id\": \"pan:CustomFields\",\n      \"@type\": \"@id\"\n    },\n    \"asc\": {\n      \"@id\": \"pan:asc\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  beta\": {\n      \"@id\": \"pan:beta\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"brand\": {\n      \"@id\": \"pan:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"byFrom\": {\n      \"@id\": \"pan:byFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"byTo\": {\n      \"@id\": \"pan:byTo\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeNotes\": {\n      \"@id\": \"pan:closeNotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeReason\": {\n      \"@id\": \"pan:closeReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closed\": {\n      \"@id\": \"pan:closed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"configuration\": {\n      \"@id\": \"pan:configuration\",\n      \"@type\": \"@id\"\n    },\n    \"contents\": {\n      \"@id\": \"pan:contents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createInvestigation\": {\n      \"@id\": \"pan:createInvestigation\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"created\": {\n      \"@id\": \"pan:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deprecated\": {\n      \"@id\": \"pan:deprecated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"pan:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"display\": {\n      \"@id\": \"pan:display\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"pan:entries\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"field\": {\n      \"@id\": \"pan:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"@id\"\
  \n    },\n    \"fromDate\": {\n      \"@id\": \"pan:fromDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fromVersion\": {\n      \"@id\": \"pan:fromVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"humanReadable\": {\n      \"@id\": \"pan:humanReadable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incidentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidents\": {\n      \"@id\": \"pan:incidents\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"incomingMapperId\": {\n      \"@id\": \"pan:incomingMapperId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"investigationId\": {\n      \"@id\": \"pan:investigationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isIntegrationScript\": {\n      \"@id\": \"pan:isIntegrationScript\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"labels\": {\n      \"@id\": \"\
  pan:labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"mappingId\": {\n      \"@id\": \"pan:mappingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"markdown\": {\n      \"@id\": \"pan:markdown\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"modified\": {\n      \"@id\": \"pan:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"occurred\": {\n      \"@id\": \"pan:occurred\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"owner\": {\n      \"@id\": \"pan:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"page\": {\n      \"@id\": \"pan:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"period\": {\n      \"@id\": \"pan:period\",\n      \"@type\": \"@id\"\n    },\n    \"playbookId\": {\n      \"@id\": \"pan:playbookId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"query\": {\n      \"@id\": \"pan:query\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"rawJson\": {\n      \"@id\": \"pan:rawJson\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relation\": {\n      \"@id\": \"pan:relation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runningPlaybooks\": {\n      \"@id\": \"pan:runningPlaybooks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchResultTotal\": {\n      \"@id\": \"pan:searchResultTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"size\": {\n      \"@id\": \"pan:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sort\": {\n      \"@id\": \"pan:sort\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sourceBrand\": {\n      \"@id\": \"pan:sourceBrand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceInstance\": {\n      \"@id\": \"pan:sourceInstance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\"\
  : \"pan:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toDate\": {\n      \"@id\": \"pan:toDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"toVersion\": {\n      \"@id\": \"pan:toVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"pan:total\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"pan:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsoar-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
