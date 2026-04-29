---
api_specs:
- filename: oracle-cloud-compute-openapi.yaml
  format: yaml
  label: Compute API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-compute-openapi.yaml
- filename: oracle-cloud-object-storage-openapi.yaml
  format: yaml
  label: Object Storage API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-object-storage-openapi.yaml
- filename: oracle-cloud-networking-openapi.yaml
  format: yaml
  label: Networking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-networking-openapi.yaml
- filename: oracle-cloud-database-openapi.yaml
  format: yaml
  label: Database API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-database-openapi.yaml
- filename: oracle-cloud-iam-openapi.yaml
  format: yaml
  label: Identity and Access Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-iam-openapi.yaml
- filename: oracle-cloud-oke-openapi.yaml
  format: yaml
  label: Container Engine for Kubernetes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-oke-openapi.yaml
- filename: oracle-cloud-functions-openapi.yaml
  format: yaml
  label: Functions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-functions-openapi.yaml
- filename: oracle-cloud-monitoring-openapi.yaml
  format: yaml
  label: Monitoring API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/openapi/oracle-cloud-monitoring-openapi.yaml
class_count: 2
classes:
- Vcn
- Subnet
context_file: json-ld/oracle-cloud-networking-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-networking-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Networking from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Networking Context
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
  name: availabilityDomain
  type: string
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
  name: defaultDhcpOptionsId
  type: string
- container: ''
  name: defaultRouteTableId
  type: string
- container: ''
  name: defaultSecurityListId
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
  name: id
  type: string
- container: ''
  name: lifecycleState
  type: string
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
  name: timeCreated
  type: dateTime
- container: ''
  name: vcnId
  type: string
property_count: 17
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-networking-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Vcn\": \"oci:Vcn\",\n    \"Subnet\": \"oci:Subnet\",\n    \"availabilityDomain\": {\n      \"@id\": \"oci:availabilityDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidrBlock\": {\n      \"@id\": \"oci:cidrBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidrBlocks\": {\n      \"@id\": \"oci:cidrBlocks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultDhcpOptionsId\": {\n      \"@id\": \"oci:defaultDhcpOptionsId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultRouteTableId\": {\n      \"@id\": \"oci:defaultRouteTableId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"defaultSecurityListId\": {\n      \"@id\": \"oci:defaultSecurityListId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsLabel\": {\n      \"@id\": \"oci:dnsLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\": {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prohibitPublicIpOnVnic\": {\n      \"@id\": \"oci:prohibitPublicIpOnVnic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"routeTableId\": {\n      \"@id\": \"oci:routeTableId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityListIds\": {\n      \"@id\": \"oci:securityListIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeCreated\": {\n      \"@id\"\
  : \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vcnId\": {\n      \"@id\": \"oci:vcnId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-networking-context.jsonld
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
