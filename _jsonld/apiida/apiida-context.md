---
class_count: 25
classes:
- id
- type
- Api
- Gateway
- Deployment
- Alarm
- Metrics
- name
- description
- version
- status
- host
- port
- gatewayType
- apiCount
- apiId
- currentVersion
- threshold
- condition
- metric
- enabled
- requestCount
- errorCount
- averageLatency
- throughput
context_file: json-ld/apiida-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apiida/refs/heads/main/json-ld/apiida-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apiida from APIIDA.
layout: jsonld
name: Apiida Context
namespaces:
- prefix: apiida
  uri: https://apiida.com/ns/
properties:
- container: set
  name: targetGateways
  type: reference
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
- container: ''
  name: completedAt
  type: schema:DateTime
- container: set
  name: tags
  type: ''
property_count: 5
provider_name: APIIDA
provider_slug: apiida
slug: apiida-context
tags:
- API Gateway
- API Management
- Federated API Management
- Governance
- Layer7
- JSON-LD
- Linked Data
- Semantic Web
---
