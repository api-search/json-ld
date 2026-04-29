---
class_count: 7
classes:
- NetworkSlice
- NetworkSliceRequest
- SecurityMetrics5G
- SecurityPolicy5G
- SecurityPolicy5GRequest
- Tenant5G
- Tenant5GRequest
context_file: json-ld/palo-alto-sase-5g-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-5g-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase 5G Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase 5G Api Context
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
  name: activeSubscribers
  type: integer
- container: ''
  name: appIdentification
  type: boolean
- container: set
  name: assignedSlices
  type: string
- container: ''
  name: bytesInspected
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: decryption
  type: boolean
- container: ''
  name: defaultPolicyId
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: end
  type: dateTime
- container: ''
  name: logForwarding
  type: boolean
- container: ''
  name: name
  type: string
- container: set
  name: perSliceMetrics
  type: reference
- container: ''
  name: period
  type: reference
- container: ''
  name: policyId
  type: string
- container: ''
  name: sd
  type: string
- container: ''
  name: securityPolicyId
  type: string
- container: ''
  name: sessions
  type: integer
- container: ''
  name: sliceId
  type: string
- container: ''
  name: sliceName
  type: string
- container: ''
  name: sliceType
  type: string
- container: ''
  name: sst
  type: integer
- container: ''
  name: start
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: threatPrevention
  type: boolean
- container: ''
  name: threats
  type: integer
- container: ''
  name: threatsBlocked
  type: integer
- container: ''
  name: threatsDetected
  type: integer
- container: set
  name: timeSeries
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: totalSessions
  type: integer
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: urlFiltering
  type: boolean
property_count: 34
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-5g-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NetworkSlice\": \"pan:NetworkSlice\",\n    \"NetworkSliceRequest\": \"pan:NetworkSliceRequest\",\n    \"SecurityMetrics5G\": \"pan:SecurityMetrics5G\",\n    \"SecurityPolicy5G\": \"pan:SecurityPolicy5G\",\n    \"SecurityPolicy5GRequest\": \"pan:SecurityPolicy5GRequest\",\n    \"Tenant5G\": \"pan:Tenant5G\",\n    \"Tenant5GRequest\": \"pan:Tenant5GRequest\",\n    \"activeSubscribers\": {\n      \"@id\": \"pan:active_subscribers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"appIdentification\": {\n      \"@id\": \"pan:app_identification\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"assignedSlices\": {\n      \"@id\": \"pan:assigned_slices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bytesInspected\"\
  : {\n      \"@id\": \"pan:bytes_inspected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"decryption\": {\n      \"@id\": \"pan:decryption\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"defaultPolicyId\": {\n      \"@id\": \"pan:default_policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"end\": {\n      \"@id\": \"pan:end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logForwarding\": {\n      \"@id\": \"pan:log_forwarding\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"perSliceMetrics\": {\n      \"@id\": \"pan:per_slice_metrics\",\n      \"@container\": \"@set\",\n  \
  \    \"@type\": \"@id\"\n    },\n    \"period\": {\n      \"@id\": \"pan:period\",\n      \"@type\": \"@id\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sd\": {\n      \"@id\": \"pan:sd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityPolicyId\": {\n      \"@id\": \"pan:security_policy_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessions\": {\n      \"@id\": \"pan:sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sliceId\": {\n      \"@id\": \"pan:slice_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sliceName\": {\n      \"@id\": \"pan:slice_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sliceType\": {\n      \"@id\": \"pan:slice_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sst\": {\n      \"@id\": \"pan:sst\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"pan:start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n\
  \      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"pan:tenant_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threatPrevention\": {\n      \"@id\": \"pan:threat_prevention\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"threats\": {\n      \"@id\": \"pan:threats\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"threatsBlocked\": {\n      \"@id\": \"pan:threats_blocked\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"threatsDetected\": {\n      \"@id\": \"pan:threats_detected\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeSeries\": {\n      \"@id\": \"pan:time_series\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"pan:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalSessions\": {\n      \"@id\": \"pan:total_sessions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n\
  \      \"@type\": \"xsd:dateTime\"\n    },\n    \"urlFiltering\": {\n      \"@id\": \"pan:url_filtering\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-5g-api-context.jsonld
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
