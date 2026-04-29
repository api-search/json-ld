---
class_count: 4
classes:
- BPACheck
- BPAReport
- BPARequest
- BPARequestStatus
context_file: json-ld/palo-alto-aiops-ngfw-bpa-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-aiops-ngfw-bpa-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Aiops Ngfw Bpa Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Aiops Ngfw Bpa Api Context
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
  name: category
  type: string
- container: set
  name: categoryScores
  type: reference
- container: ''
  name: checkId
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: currentValue
  type: string
- container: ''
  name: deploymentType
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: deviceInfo
  type: reference
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: failed
  type: integer
- container: ''
  name: failedChecks
  type: integer
- container: ''
  name: generatedAt
  type: dateTime
- container: ''
  name: hostname
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: notApplicable
  type: integer
- container: ''
  name: overallScore
  type: float
- container: ''
  name: panOsVersion
  type: string
- container: ''
  name: passed
  type: integer
- container: ''
  name: passedChecks
  type: integer
- container: ''
  name: recommendedValue
  type: string
- container: set
  name: references
  type: reference
- container: ''
  name: remediation
  type: string
- container: ''
  name: reportId
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: score
  type: float
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: totalChecks
  type: integer
- container: ''
  name: version
  type: string
property_count: 32
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-aiops-ngfw-bpa-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BPACheck\": \"pan:BPACheck\",\n    \"BPAReport\": \"pan:BPAReport\",\n    \"BPARequest\": \"pan:BPARequest\",\n    \"BPARequestStatus\": \"pan:BPARequestStatus\",\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryScores\": {\n      \"@id\": \"pan:category_scores\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"checkId\": {\n      \"@id\": \"pan:check_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"pan:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currentValue\": {\n      \"@id\": \"pan:current_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentType\": {\n      \"@id\": \"pan:deployment_type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceInfo\": {\n      \"@id\": \"pan:device_info\",\n      \"@type\": \"@id\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failed\": {\n      \"@id\": \"pan:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failedChecks\": {\n      \"@id\": \"pan:failed_checks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"generatedAt\": {\n      \"@id\": \"pan:generated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"hostname\": {\n      \"@id\": \"pan:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"pan:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notApplicable\": {\n      \"@id\": \"pan:not_applicable\",\n    \
  \  \"@type\": \"xsd:integer\"\n    },\n    \"overallScore\": {\n      \"@id\": \"pan:overall_score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"panOsVersion\": {\n      \"@id\": \"pan:pan_os_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passed\": {\n      \"@id\": \"pan:passed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passedChecks\": {\n      \"@id\": \"pan:passed_checks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recommendedValue\": {\n      \"@id\": \"pan:recommended_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"references\": {\n      \"@id\": \"pan:references\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportId\": {\n      \"@id\": \"pan:report_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"pan:request_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"score\":\
  \ {\n      \"@id\": \"pan:score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"serialNumber\": {\n      \"@id\": \"pan:serial_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"pan:submitted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalChecks\": {\n      \"@id\": \"pan:total_checks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-aiops-ngfw-bpa-api-context.jsonld
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
