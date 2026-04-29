---
class_count: 2
classes:
- AutonomousDatabase
- AutonomousDatabaseSummary
context_file: json-ld/oracle-cloud-database-autonomous-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-database-autonomous-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Database Autonomous from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Database Autonomous Context
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
  name: compartmentId
  type: string
- container: ''
  name: connectionUrls
  type: ''
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
  name: freeformTags
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: isAutoScalingEnabled
  type: boolean
- container: ''
  name: isFreeTier
  type: boolean
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: timeCreated
  type: dateTime
property_count: 13
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-database-autonomous-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AutonomousDatabase\": \"oci:AutonomousDatabase\",\n    \"AutonomousDatabaseSummary\": \"oci:AutonomousDatabaseSummary\",\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionUrls\": {\n      \"@id\": \"oci:connectionUrls\"\n    },\n    \"cpuCoreCount\": {\n      \"@id\": \"oci:cpuCoreCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataStorageSizeInTBs\": {\n      \"@id\": \"oci:dataStorageSizeInTBs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dbName\": {\n      \"@id\": \"oci:dbName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dbWorkload\": {\n      \"@id\": \"oci:dbWorkload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\"\
  : {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\": {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isAutoScalingEnabled\": {\n      \"@id\": \"oci:isAutoScalingEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFreeTier\": {\n      \"@id\": \"oci:isFreeTier\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-database-autonomous-context.jsonld
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
