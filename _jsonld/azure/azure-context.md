---
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
