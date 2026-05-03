---
api_specs:
- filename: traceable-platform-openapi.yml
  format: yaml
  label: Traceable Platform GraphQL API
  slug: traceable-platform-graphql
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/openapi/traceable-platform-openapi.yml
class_count: 33
classes:
- APIEntity
- id
- name
- entityType
- service
- domain
- method
- authenticated
- authType
- riskScore
- isInternal
- discoveryState
- lastActivity
- callVolume
- errorRate
- latencyP99
- labels
- attributes
- Vulnerability
- severity
- owaspCategory
- status
- ThreatActivity
- threatActor
- attackPattern
- blockedAt
- SecurityTestSuite
- scan
- MCPTool
- tool
- GraphQLQuery
- query
- variables
context_file: json-ld/traceable-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/json-ld/traceable-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Traceable from Traceable.
layout: jsonld
name: Traceable Context
namespaces:
- prefix: traceable
  uri: https://api-evangelist.com/context/traceable/
- prefix: sec
  uri: https://api-evangelist.com/context/security/
properties: []
property_count: 0
provider_name: Traceable
provider_slug: traceable
slug: traceable-context
source_filename: traceable-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"traceable\": \"https://api-evangelist.com/context/traceable/\",\n    \"sec\": \"https://api-evangelist.com/context/security/\",\n    \"APIEntity\": \"traceable:APIEntity\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"entityType\": \"traceable:entityType\",\n    \"service\": \"traceable:service\",\n    \"domain\": \"traceable:domain\",\n    \"method\": \"traceable:httpMethod\",\n    \"authenticated\": \"traceable:requiresAuthentication\",\n    \"authType\": \"traceable:authType\",\n    \"riskScore\": \"sec:riskScore\",\n    \"isInternal\": \"traceable:isInternal\",\n    \"discoveryState\": \"traceable:discoveryState\",\n    \"lastActivity\": \"schema:dateModified\",\n    \"callVolume\": \"traceable:callVolume\",\n    \"errorRate\": \"traceable:errorRate\",\n    \"latencyP99\": \"traceable:latencyP99\",\n    \"labels\": \"schema:keywords\",\n    \"attributes\": \"traceable:attributes\"\
  ,\n    \"Vulnerability\": \"sec:Vulnerability\",\n    \"severity\": \"sec:severity\",\n    \"owaspCategory\": \"sec:owaspCategory\",\n    \"status\": \"traceable:vulnerabilityStatus\",\n    \"ThreatActivity\": \"sec:ThreatActivity\",\n    \"threatActor\": \"sec:threatActor\",\n    \"attackPattern\": \"sec:attackPattern\",\n    \"blockedAt\": \"traceable:blockedAt\",\n    \"SecurityTestSuite\": \"sec:TestSuite\",\n    \"scan\": \"sec:scan\",\n    \"MCPTool\": \"traceable:MCPTool\",\n    \"tool\": \"traceable:toolName\",\n    \"GraphQLQuery\": \"traceable:GraphQLQuery\",\n    \"query\": \"traceable:graphqlQuery\",\n    \"variables\": \"traceable:queryVariables\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/traceable/refs/heads/main/json-ld/traceable-context.jsonld
tags:
- API Discovery
- API Protection
- API Security
- API Testing
- Observability
- Security
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
