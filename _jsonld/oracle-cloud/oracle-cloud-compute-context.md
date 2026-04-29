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
class_count: 3
classes:
- Shape
- Image
- Instance
context_file: json-ld/oracle-cloud-compute-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Cloud Compute from Oracle Cloud Infrastructure.
layout: jsonld
name: Oracle Cloud Compute Context
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
  name: compartmentId
  type: string
- container: ''
  name: definedTags
  type: ''
- container: ''
  name: displayName
  type: string
- container: ''
  name: freeformTags
  type: ''
- container: ''
  name: gpus
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: imageId
  type: string
- container: ''
  name: isFlexible
  type: boolean
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: memoryInGBs
  type: decimal
- container: ''
  name: networkingBandwidthInGbps
  type: decimal
- container: ''
  name: ocpus
  type: decimal
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: operatingSystemVersion
  type: string
- container: ''
  name: processorDescription
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: shape
  type: string
- container: ''
  name: sizeInMBs
  type: integer
- container: ''
  name: timeCreated
  type: dateTime
property_count: 20
provider_name: Oracle Cloud Infrastructure
provider_slug: oracle-cloud
slug: oracle-cloud-compute-context
source_filename: oracle-cloud-compute-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oci\": \"https://docs.oracle.com/en-us/iaas/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Shape\": \"oci:Shape\",\n    \"Image\": \"oci:Image\",\n    \"Instance\": \"oci:Instance\",\n    \"availabilityDomain\": {\n      \"@id\": \"oci:availabilityDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compartmentId\": {\n      \"@id\": \"oci:compartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definedTags\": {\n      \"@id\": \"oci:definedTags\"\n    },\n    \"displayName\": {\n      \"@id\": \"oci:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeformTags\": {\n      \"@id\": \"oci:freeformTags\"\n    },\n    \"gpus\": {\n      \"@id\": \"oci:gpus\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"oci:id\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"imageId\": {\n      \"@id\": \"oci:imageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFlexible\": {\n      \"@id\": \"oci:isFlexible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"oci:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryInGBs\": {\n      \"@id\": \"oci:memoryInGBs\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"networkingBandwidthInGbps\": {\n      \"@id\": \"oci:networkingBandwidthInGbps\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ocpus\": {\n      \"@id\": \"oci:ocpus\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"oci:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystemVersion\": {\n      \"@id\": \"oci:operatingSystemVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processorDescription\": {\n      \"@id\": \"oci:processorDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n\
  \      \"@id\": \"oci:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shape\": {\n      \"@id\": \"oci:shape\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeInMBs\": {\n      \"@id\": \"oci:sizeInMBs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-cloud/refs/heads/main/json-ld/oracle-cloud-compute-context.jsonld
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
