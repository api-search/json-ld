---
api_specs:
- filename: treblle-api-openapi.yml
  format: yaml
  label: Treblle Platform API
  slug: treblle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/treblle/refs/heads/main/openapi/treblle-api-openapi.yml
class_count: 32
classes:
- id
- type
- Project
- ApiRequest
- Endpoint
- GovernanceResult
- Member
- name
- description
- email
- createdAt
- updatedAt
- api_id
- sdk_token
- environment
- total_requests
- status_code
- response_time
- ip_address
- method
- url
- has_errors
- overall_score
- overall_grade
- design_score
- security_score
- performance_score
- role
- path
- severity
- issues
- errors
context_file: json-ld/treblle-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/treblle/refs/heads/main/json-ld/treblle-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Treblle from Treblle.
layout: jsonld
name: Treblle Context
namespaces:
- prefix: treblle
  uri: https://treblle.com/ns/
properties: []
property_count: 0
provider_name: Treblle
provider_slug: treblle
slug: treblle-context
source_filename: treblle-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"treblle\": \"https://treblle.com/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Project\": \"treblle:Project\",\n    \"ApiRequest\": \"treblle:ApiRequest\",\n    \"Endpoint\": \"treblle:Endpoint\",\n    \"GovernanceResult\": \"treblle:GovernanceResult\",\n    \"Member\": \"treblle:Member\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"api_id\": \"treblle:apiId\",\n    \"sdk_token\": \"treblle:sdkToken\",\n    \"environment\": \"treblle:environment\",\n    \"total_requests\": \"treblle:totalRequests\",\n    \"status_code\": \"treblle:statusCode\",\n    \"response_time\": \"treblle:responseTime\",\n    \"ip_address\": \"treblle:ipAddress\",\n    \"method\": \"treblle:httpMethod\",\n    \"url\": \"schema:url\",\n    \"has_errors\": \"\
  treblle:hasErrors\",\n    \"overall_score\": \"treblle:overallScore\",\n    \"overall_grade\": \"treblle:overallGrade\",\n    \"design_score\": \"treblle:designScore\",\n    \"security_score\": \"treblle:securityScore\",\n    \"performance_score\": \"treblle:performanceScore\",\n    \"role\": \"treblle:role\",\n    \"path\": \"treblle:path\",\n    \"severity\": \"treblle:severity\",\n    \"issues\": \"treblle:issues\",\n    \"errors\": \"treblle:errors\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/treblle/refs/heads/main/json-ld/treblle-context.jsonld
tags:
- Analytics
- Artificial Intelligence
- Developer Experience
- Documentation
- Governance
- Insights
- Observability
- Platform
- Security
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
