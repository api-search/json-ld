---
class_count: 1
classes:
- CreateAutonomousDatabaseDetails
context_file: json-ld/oracle-cloud-database-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-database-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Database Create from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Database Create Context
namespaces:
- prefix: oci
  uri: https://docs.oracle.com/en-us/iaas/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: adminPassword
  type: string
- container: ''
  name: compartmentId
  type: string
- container: ''
  name: cpuCoreCount
  type: integer
- container: ''
  name: dataStorageSizeInTBs
  type: integer
- container: ''
  name: dbName
  type: string
- container: ''
  name: dbWorkload
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: isAutoScalingEnabled
  type: boolean
- container: ''
  name: isFreeTier
  type: boolean
property_count: 9
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-database-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateAutonomousDatabaseDetails\": \"oci:CreateAutonomousDatabaseDetails\",\n    \"adminPassword\": {\n      \"@id\": \"oci:adminPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuCoreCount\": {\n      \"@id\": \"oci:cpuCoreCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataStorageSizeInTBs\": {\n      \"@id\": \"oci:dataStorageSizeInTBs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dbName\": {\n      \"@id\": \"oci:dbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbWorkload\": {\n      \"@id\": \"oci:dbWorkload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n\
  \      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAutoScalingEnabled\": {\n      \"@id\": \"oci:isAutoScalingEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFreeTier\": {\n      \"@id\": \"oci:isFreeTier\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-database-create-context.jsonld
tags:
- Cloud Computing
- Enterprise Cloud
- Infrastructure as a Service
- Oracle
- Platform as a Service
- JSON-LD
- Linked Data
- Semantic Web
---
