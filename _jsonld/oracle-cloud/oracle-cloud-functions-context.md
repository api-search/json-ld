---
class_count: 2
classes:
- Function
- Application
context_file: json-ld/oracle-cloud-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Functions from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Functions Context
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
  name: applicationId
  type: string
- container: ''
  name: compartmentId
  type: string
- container: ''
  name: config
  type: ''
- container: ''
  name: displayName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: invokeEndpoint
  type: string
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: memoryInMBs
  type: integer
- container: set
  name: subnetIds
  type: string
- container: ''
  name: timeCreated
  type: dateTime
- container: ''
  name: timeoutInSeconds
  type: integer
property_count: 12
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-functions-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Function\": \"oci:Function\",\n    \"Application\": \"oci:Application\",\n    \"applicationId\": {\n      \"@id\": \"oci:applicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"config\": {\n      \"@id\": \"oci:config\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"oci:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invokeEndpoint\": {\n      \"@id\": \"oci:invokeEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryInMBs\": {\n      \"@id\": \"oci:memoryInMBs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"oci:subnetIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeoutInSeconds\": {\n      \"@id\": \"oci:timeoutInSeconds\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-functions-context.jsonld
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
