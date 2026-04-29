---
class_count: 4
classes:
- ContentSnippet
- DLPIncident
- DataPattern
- IncidentSummary
context_file: json-ld/palo-alto-dlp-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-dlp-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Dlp Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Dlp Api Context
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
  name: actionTaken
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: byChannel
  type: reference
- container: ''
  name: bySeverity
  type: reference
- container: ''
  name: category
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: confidence
  type: string
- container: ''
  name: critical
  type: integer
- container: ''
  name: dataPatternId
  type: string
- container: ''
  name: dataPatternName
  type: string
- container: ''
  name: description
  type: string
- container: set
  name: detectionRules
  type: reference
- container: ''
  name: direction
  type: string
- container: ''
  name: email
  type: integer
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: endpoint
  type: integer
- container: ''
  name: fileName
  type: string
- container: ''
  name: fileSize
  type: integer
- container: ''
  name: fileType
  type: string
- container: ''
  name: high
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: incidentCount
  type: integer
- container: ''
  name: incidentId
  type: string
- container: ''
  name: informational
  type: integer
- container: ''
  name: low
  type: integer
- container: ''
  name: masked
  type: boolean
- container: ''
  name: matchCount
  type: integer
- container: ''
  name: medium
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: openIncidents
  type: integer
- container: ''
  name: patternId
  type: string
- container: ''
  name: patternName
  type: string
- container: ''
  name: position
  type: integer
- container: ''
  name: proximity
  type: integer
- container: ''
  name: reportingPeriod
  type: reference
- container: ''
  name: resolvedIncidents
  type: integer
- container: ''
  name: reviewedAt
  type: dateTime
- container: ''
  name: reviewedBy
  type: string
- container: ''
  name: reviewerComments
  type: string
- container: ''
  name: ruleType
  type: string
- container: ''
  name: saas
  type: integer
- container: ''
  name: severity
  type: string
- container: ''
  name: snippet
  type: string
- container: ''
  name: ssl
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: set
  name: topDataPatterns
  type: reference
- container: set
  name: topUsers
  type: reference
- container: ''
  name: totalIncidents
  type: integer
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
  name: web
  type: integer
property_count: 55
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-dlp-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ContentSnippet\": \"pan:ContentSnippet\",\n    \"DLPIncident\": \"pan:DLPIncident\",\n    \"DataPattern\": \"pan:DataPattern\",\n    \"IncidentSummary\": \"pan:IncidentSummary\",\n    \"actionTaken\": {\n      \"@id\": \"pan:action_taken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"byChannel\": {\n      \"@id\": \"pan:by_channel\",\n      \"@type\": \"@id\"\n    },\n    \"bySeverity\": {\n      \"@id\": \"pan:by_severity\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"pan:channel\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"confidence\": {\n      \"@id\": \"pan:confidence\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"pan:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataPatternId\": {\n      \"@id\": \"pan:data_pattern_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataPatternName\": {\n      \"@id\": \"pan:data_pattern_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectionRules\": {\n      \"@id\": \"pan:detection_rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"direction\": {\n      \"@id\": \"pan:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:end_time\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endpoint\": {\n      \"@id\": \"pan:endpoint\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fileName\": {\n      \"@id\": \"pan:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSize\": {\n      \"@id\": \"pan:file_size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fileType\": {\n      \"@id\": \"pan:file_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"pan:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentCount\": {\n      \"@id\": \"pan:incident_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"incidentId\": {\n      \"@id\": \"pan:incident_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"informational\": {\n      \"@id\": \"pan:informational\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"low\": {\n      \"@id\": \"pan:low\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"masked\": {\n      \"@id\": \"pan:masked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"matchCount\": {\n      \"@id\": \"pan:match_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medium\": {\n      \"@id\": \"pan:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openIncidents\": {\n      \"@id\": \"pan:open_incidents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"patternId\": {\n      \"@id\": \"pan:pattern_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patternName\": {\n      \"@id\": \"pan:pattern_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"position\": {\n      \"@id\": \"pan:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"proximity\": {\n      \"@id\": \"pan:proximity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reportingPeriod\": {\n      \"@id\": \"pan:reporting_period\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"resolvedIncidents\": {\n      \"@id\": \"pan:resolved_incidents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"reviewedAt\": {\n      \"@id\": \"pan:reviewed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"reviewedBy\": {\n      \"@id\": \"pan:reviewed_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reviewerComments\": {\n      \"@id\": \"pan:reviewer_comments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleType\": {\n      \"@id\": \"pan:rule_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saas\": {\n      \"@id\": \"pan:saas\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snippet\": {\n      \"@id\": \"pan:snippet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssl\": {\n      \"@id\": \"pan:ssl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"pan:start_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n \
  \   \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"topDataPatterns\": {\n      \"@id\": \"pan:top_data_patterns\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"topUsers\": {\n      \"@id\": \"pan:top_users\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"totalIncidents\": {\n      \"@id\": \"pan:total_incidents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"pan:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"web\": {\n      \"@id\": \"pan:web\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-dlp-api-context.jsonld
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
