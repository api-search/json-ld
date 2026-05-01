---
api_specs:
- filename: assured-workloads-api-openapi.yml
  format: yaml
  label: Assured Workloads API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-assured-workloads/refs/heads/main/openapi/assured-workloads-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-assured-workloads-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-assured-workloads/refs/heads/main/json-ld/google-cloud-assured-workloads-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Assured Workloads from Google Cloud Assured Workloads.
layout: jsonld
name: Google Cloud Assured Workloads Context
namespaces:
- prefix: aw
  uri: https://cloud.google.com/assured-workloads/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Workload
  type: ''
- container: ''
  name: Violation
  type: ''
property_count: 2
provider_name: Google Cloud Assured Workloads
provider_slug: google-cloud-assured-workloads
slug: google-cloud-assured-workloads-context
source_filename: google-cloud-assured-workloads-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aw\": \"https://cloud.google.com/assured-workloads/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Workload\": {\n      \"@id\": \"aw:Workload\",\n      \"@context\": {\n        \"name\": \"aw:workloadName\",\n        \"displayName\": \"schema:name\",\n        \"complianceRegime\": \"aw:complianceRegime\",\n        \"billingAccount\": \"aw:billingAccount\",\n        \"provisionedResourcesParent\": \"aw:provisionedResourcesParent\",\n        \"resources\": \"aw:resources\",\n        \"labels\": \"aw:labels\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Violation\": {\n      \"@id\": \"aw:Violation\",\n      \"@context\": {\n        \"name\": \"aw:violationName\",\n        \"description\": \"schema:description\",\n \
  \       \"category\": \"aw:category\",\n        \"state\": \"aw:state\",\n        \"orgPolicyConstraint\": \"aw:orgPolicyConstraint\",\n        \"beginTime\": {\n          \"@id\": \"aw:beginTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolveTime\": {\n          \"@id\": \"aw:resolveTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-assured-workloads/refs/heads/main/json-ld/google-cloud-assured-workloads-context.jsonld
tags:
- Compliance
- Data Residency
- FedRAMP
- Governance
- HIPAA
- Regulatory
- JSON-LD
- Linked Data
- Semantic Web
---
