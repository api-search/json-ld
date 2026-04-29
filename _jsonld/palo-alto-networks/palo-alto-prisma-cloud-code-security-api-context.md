---
class_count: 6
classes:
- CodeError
- Fix
- Repository
- ScanIntegration
- ScanStatus
- Suppression
context_file: json-ld/palo-alto-prisma-cloud-code-security-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-code-security-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud Code Security Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Code Security Api Context
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
  name: branch
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: ''
  name: critical
  type: integer
- container: ''
  name: defaultBranch
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: errorCounts
  type: reference
- container: ''
  name: errorId
  type: string
- container: ''
  name: errorsBySeverity
  type: reference
- container: ''
  name: expirationDate
  type: dateTime
- container: set
  name: fileLineRange
  type: integer
- container: ''
  name: filePath
  type: string
- container: ''
  name: filesScanned
  type: integer
- container: ''
  name: firstDetected
  type: dateTime
- container: ''
  name: fixId
  type: string
- container: ''
  name: framework
  type: string
- container: ''
  name: fullName
  type: string
- container: ''
  name: guideline
  type: string
- container: ''
  name: high
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: info
  type: integer
- container: ''
  name: isPublic
  type: boolean
- container: ''
  name: justification
  type: string
- container: ''
  name: lastDetected
  type: dateTime
- container: ''
  name: lastScanDate
  type: dateTime
- container: ''
  name: lastScanStatus
  type: string
- container: set
  name: lineRange
  type: integer
- container: ''
  name: low
  type: integer
- container: ''
  name: medium
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: originalCode
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: policyName
  type: string
- container: ''
  name: repositoryId
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: resourcesScanned
  type: integer
- container: set
  name: scanTypes
  type: string
- container: ''
  name: scanId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: sourceType
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: suggestedCode
  type: string
- container: ''
  name: summary
  type: reference
- container: ''
  name: suppressedErrorCount
  type: integer
- container: ''
  name: suppressionId
  type: string
- container: ''
  name: suppressionType
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: string
property_count: 53
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-code-security-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CodeError\": \"pan:CodeError\",\n    \"Fix\": \"pan:Fix\",\n    \"Repository\": \"pan:Repository\",\n    \"ScanIntegration\": \"pan:ScanIntegration\",\n    \"ScanStatus\": \"pan:ScanStatus\",\n    \"Suppression\": \"pan:Suppression\",\n    \"branch\": {\n      \"@id\": \"pan:branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"pan:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"pan:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"pan:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultBranch\": {\n   \
  \   \"@id\": \"pan:defaultBranch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"errorCounts\": {\n      \"@id\": \"pan:errorCounts\",\n      \"@type\": \"@id\"\n    },\n    \"errorId\": {\n      \"@id\": \"pan:errorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorsBySeverity\": {\n      \"@id\": \"pan:errorsBySeverity\",\n      \"@type\": \"@id\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"pan:expirationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fileLineRange\": {\n      \"@id\": \"pan:fileLineRange\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"filePath\": {\n      \"@id\": \"pan:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filesScanned\": {\n      \"@id\": \"pan:filesScanned\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"firstDetected\": {\n      \"@id\": \"pan:firstDetected\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fixId\": {\n      \"@id\": \"pan:fixId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"framework\": {\n      \"@id\": \"pan:framework\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fullName\": {\n      \"@id\": \"pan:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guideline\": {\n      \"@id\": \"pan:guideline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"pan:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"pan:info\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isPublic\": {\n      \"@id\": \"pan:isPublic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"justification\": {\n      \"@id\": \"pan:justification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastDetected\": {\n      \"@id\"\
  : \"pan:lastDetected\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScanDate\": {\n      \"@id\": \"pan:lastScanDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScanStatus\": {\n      \"@id\": \"pan:lastScanStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineRange\": {\n      \"@id\": \"pan:lineRange\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"low\": {\n      \"@id\": \"pan:low\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medium\": {\n      \"@id\": \"pan:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originalCode\": {\n      \"@id\": \"pan:originalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"pan:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"pan:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyName\": {\n \
  \     \"@id\": \"pan:policyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryId\": {\n      \"@id\": \"pan:repositoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"pan:resourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"pan:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourcesScanned\": {\n      \"@id\": \"pan:resourcesScanned\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scanTypes\": {\n      \"@id\": \"pan:scanTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanId\": {\n      \"@id\": \"pan:scan_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceType\": {\n      \"@id\": \"pan:sourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"pan:startTime\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedCode\": {\n      \"@id\": \"pan:suggestedCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"pan:summary\",\n      \"@type\": \"@id\"\n    },\n    \"suppressedErrorCount\": {\n      \"@id\": \"pan:suppressedErrorCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"suppressionId\": {\n      \"@id\": \"pan:suppressionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suppressionType\": {\n      \"@id\": \"pan:suppressionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-code-security-api-context.jsonld
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
