---
class_count: 6
classes:
- Classification
- DSPMPolicy
- DataAsset
- DataRisk
- DataSecurityAlert
- DataStore
context_file: json-ld/palo-alto-prisma-cloud-dspm-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-dspm-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Cloud Dspm Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Cloud Dspm Api Context
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
- container: set
  name: affectedClassifications
  type: string
- container: ''
  name: affectedDataAssetCount
  type: integer
- container: ''
  name: alertType
  type: string
- container: ''
  name: assetType
  type: string
- container: ''
  name: automatedRemediationAvailable
  type: boolean
- container: ''
  name: category
  type: string
- container: ''
  name: classification
  type: string
- container: ''
  name: classificationLabel
  type: string
- container: set
  name: classificationLabels
  type: string
- container: ''
  name: cloudAccountId
  type: string
- container: ''
  name: cloudProvider
  type: string
- container: set
  name: cloudProviders
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: dataAssetCount
  type: integer
- container: ''
  name: dataStoreCount
  type: integer
- container: ''
  name: dataStoreId
  type: string
- container: ''
  name: dataStoreName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: detectedAt
  type: dateTime
- container: ''
  name: discoveredAt
  type: dateTime
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: encryptionEnabled
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: isBuiltIn
  type: boolean
- container: ''
  name: isPubliclyAccessible
  type: boolean
- container: ''
  name: lastEvaluatedAt
  type: dateTime
- container: ''
  name: lastScannedAt
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: pattern
  type: string
- container: ''
  name: recordCount
  type: integer
- container: ''
  name: region
  type: string
- container: set
  name: regulatoryFrameworks
  type: string
- container: ''
  name: remediation
  type: reference
- container: set
  name: requiredControls
  type: string
- container: ''
  name: resolvedAt
  type: dateTime
- container: ''
  name: riskCategory
  type: string
- container: ''
  name: riskLevel
  type: string
- container: set
  name: sampleFindings
  type: reference
- container: ''
  name: sampleValue
  type: string
- container: ''
  name: sensitiveDataCount
  type: integer
- container: ''
  name: sensitivityLevel
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: steps
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: updatedAt
  type: dateTime
property_count: 50
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-cloud-dspm-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Classification\": \"pan:Classification\",\n    \"DSPMPolicy\": \"pan:DSPMPolicy\",\n    \"DataAsset\": \"pan:DataAsset\",\n    \"DataRisk\": \"pan:DataRisk\",\n    \"DataSecurityAlert\": \"pan:DataSecurityAlert\",\n    \"DataStore\": \"pan:DataStore\",\n    \"affectedClassifications\": {\n      \"@id\": \"pan:affectedClassifications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedDataAssetCount\": {\n      \"@id\": \"pan:affectedDataAssetCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"alertType\": {\n      \"@id\": \"pan:alertType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetType\": {\n      \"@id\": \"pan:assetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automatedRemediationAvailable\"\
  : {\n      \"@id\": \"pan:automatedRemediationAvailable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classification\": {\n      \"@id\": \"pan:classification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classificationLabel\": {\n      \"@id\": \"pan:classificationLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classificationLabels\": {\n      \"@id\": \"pan:classificationLabels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudAccountId\": {\n      \"@id\": \"pan:cloudAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudProvider\": {\n      \"@id\": \"pan:cloudProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudProviders\": {\n      \"@id\": \"pan:cloudProviders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"pan:count\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"pan:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dataAssetCount\": {\n      \"@id\": \"pan:dataAssetCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataStoreCount\": {\n      \"@id\": \"pan:dataStoreCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataStoreId\": {\n      \"@id\": \"pan:dataStoreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataStoreName\": {\n      \"@id\": \"pan:dataStoreName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectedAt\": {\n      \"@id\": \"pan:detectedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"discoveredAt\": {\n      \"@id\": \"pan:discoveredAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"encryptionEnabled\": {\n      \"@id\"\
  : \"pan:encryptionEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isBuiltIn\": {\n      \"@id\": \"pan:isBuiltIn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPubliclyAccessible\": {\n      \"@id\": \"pan:isPubliclyAccessible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastEvaluatedAt\": {\n      \"@id\": \"pan:lastEvaluatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScannedAt\": {\n      \"@id\": \"pan:lastScannedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"pan:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pattern\": {\n      \"@id\": \"pan:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordCount\": {\n      \"@id\": \"pan:recordCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"region\": {\n      \"\
  @id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regulatoryFrameworks\": {\n      \"@id\": \"pan:regulatoryFrameworks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"@id\"\n    },\n    \"requiredControls\": {\n      \"@id\": \"pan:requiredControls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedAt\": {\n      \"@id\": \"pan:resolvedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"riskCategory\": {\n      \"@id\": \"pan:riskCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"pan:riskLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sampleFindings\": {\n      \"@id\": \"pan:sampleFindings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sampleValue\": {\n      \"@id\": \"pan:sampleValue\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"sensitiveDataCount\": {\n      \"@id\": \"pan:sensitiveDataCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sensitivityLevel\": {\n      \"@id\": \"pan:sensitivityLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"pan:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"pan:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"pan:steps\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"pan:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-cloud-dspm-api-context.jsonld
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
