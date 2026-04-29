---
class_count: 3
classes:
- CreateVcnDetails
- CreateSubnetDetails
- CreateInternetGatewayDetails
context_file: json-ld/oracle-cloud-networking-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-networking-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Networking Create from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Networking Create Context
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
  name: cidrBlock
  type: string
- container: set
  name: cidrBlocks
  type: string
- container: ''
  name: compartmentId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: dnsLabel
  type: string
- container: ''
  name: freeformTags
  type: ''
- container: ''
  name: isEnabled
  type: boolean
- container: ''
  name: prohibitPublicIpOnVnic
  type: boolean
- container: ''
  name: routeTableId
  type: string
- container: set
  name: securityListIds
  type: string
- container: ''
  name: vcnId
  type: string
property_count: 11
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-networking-create-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateVcnDetails\": \"oci:CreateVcnDetails\",\n    \"CreateSubnetDetails\": \"oci:CreateSubnetDetails\",\n    \"CreateInternetGatewayDetails\": \"oci:CreateInternetGatewayDetails\",\n    \"cidrBlock\": {\n      \"@id\": \"oci:cidrBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidrBlocks\": {\n      \"@id\": \"oci:cidrBlocks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsLabel\": {\n      \"@id\": \"oci:dnsLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\"\
  : {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"isEnabled\": {\n      \"@id\": \"oci:isEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"prohibitPublicIpOnVnic\": {\n      \"@id\": \"oci:prohibitPublicIpOnVnic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"routeTableId\": {\n      \"@id\": \"oci:routeTableId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityListIds\": {\n      \"@id\": \"oci:securityListIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vcnId\": {\n      \"@id\": \"oci:vcnId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-networking-create-context.jsonld
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
