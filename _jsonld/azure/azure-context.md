---
api_specs:
- filename: azure-management-openapi.yaml
  format: yaml
  label: Azure Compute API
  slug: azure-compute-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml
- filename: azure-management-openapi.yaml
  format: yaml
  label: Azure Storage API
  slug: azure-storage-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml
- filename: azure-management-openapi.yaml
  format: yaml
  label: Azure Cognitive Services API
  slug: azure-cognitive-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/openapi/azure-management-openapi.yaml
class_count: 7
classes:
- Subscription
- SubscriptionListResult
- ResourceGroup
- ResourceGroupListResult
- GenericResource
- ResourceListResult
- name
context_file: json-ld/azure-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/json-ld/azure-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure from Microsoft Azure.
layout: jsonld
name: Azure Context
namespaces:
- prefix: azure
  uri: https://azure.microsoft.com/azure/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: subscriptionPolicies
  type: reference
- container: ''
  name: authorizationSource
  type: string
- container: set
  name: managedByTenants
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: nextLink
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: properties
  type: reference
- container: ''
  name: kind
  type: string
- container: ''
  name: managedBy
  type: string
- container: ''
  name: sku
  type: reference
property_count: 16
provider_name: Microsoft Azure
provider_slug: azure
slug: azure-context
source_filename: azure-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azure\": \"https://azure.microsoft.com/azure/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Subscription\": \"azure:Subscription\",\n    \"SubscriptionListResult\": \"azure:SubscriptionListResult\",\n    \"ResourceGroup\": \"azure:ResourceGroup\",\n    \"ResourceGroupListResult\": \"azure:ResourceGroupListResult\",\n    \"GenericResource\": \"azure:GenericResource\",\n    \"ResourceListResult\": \"azure:ResourceListResult\",\n    \"id\": {\n      \"@id\": \"azure:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"azure:subscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"azure:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"azure:state\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"subscriptionPolicies\": {\n      \"@id\": \"azure:subscriptionPolicies\",\n      \"@type\": \"@id\"\n    },\n    \"authorizationSource\": {\n      \"@id\": \"azure:authorizationSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managedByTenants\": {\n      \"@id\": \"azure:managedByTenants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azure:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azure:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"azure:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azure:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"azure:tags\",\n      \"@type\": \"@id\"\n    },\n    \"properties\": {\n      \"@id\": \"azure:properties\",\n      \"@type\": \"@id\"\n   \
  \ },\n    \"kind\": {\n      \"@id\": \"azure:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managedBy\": {\n      \"@id\": \"azure:managedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"azure:sku\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/json-ld/azure-context.jsonld
tags:
- Cloud Computing
- Databases
- Infrastructure
- Machine Learning
- Networking
- Platform as a Service
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
