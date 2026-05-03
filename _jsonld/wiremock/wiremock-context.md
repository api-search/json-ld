---
api_specs:
- filename: wiremock-admin-api-openapi.yml
  format: yaml
  label: WireMock Admin API
  slug: wiremock-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/openapi/wiremock-admin-api-openapi.yml
class_count: 30
classes:
- StubMapping
- RequestPattern
- ResponseDefinition
- Scenario
- ServeEvent
- NearMiss
- request
- response
- stubMappingId
- requestId
- scenarioName
- requiredScenarioState
- newScenarioState
- urlPattern
- urlPath
- urlPathPattern
- bodyPatterns
- fixedDelayMilliseconds
- fault
- proxyBaseUrl
- persistent
- metadata
- priority
- transformers
- status
- method
- name
- description
- url
- SoftwareApplication
context_file: json-ld/wiremock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-ld/wiremock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wiremock from WireMock.
layout: jsonld
name: Wiremock Context
namespaces:
- prefix: wm
  uri: https://wiremock.org/vocab/
properties: []
property_count: 0
provider_name: WireMock
provider_slug: wiremock
slug: wiremock-context
source_filename: wiremock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wm\": \"https://wiremock.org/vocab/\",\n    \"StubMapping\": \"wm:StubMapping\",\n    \"RequestPattern\": \"wm:RequestPattern\",\n    \"ResponseDefinition\": \"wm:ResponseDefinition\",\n    \"Scenario\": \"wm:Scenario\",\n    \"ServeEvent\": \"wm:ServeEvent\",\n    \"NearMiss\": \"wm:NearMiss\",\n    \"request\": \"wm:request\",\n    \"response\": \"wm:response\",\n    \"stubMappingId\": \"wm:stubMappingId\",\n    \"requestId\": \"wm:requestId\",\n    \"scenarioName\": \"wm:scenarioName\",\n    \"requiredScenarioState\": \"wm:requiredScenarioState\",\n    \"newScenarioState\": \"wm:newScenarioState\",\n    \"urlPattern\": \"wm:urlPattern\",\n    \"urlPath\": \"wm:urlPath\",\n    \"urlPathPattern\": \"wm:urlPathPattern\",\n    \"bodyPatterns\": \"wm:bodyPatterns\",\n    \"fixedDelayMilliseconds\": \"wm:fixedDelayMilliseconds\",\n    \"fault\": \"wm:fault\",\n    \"proxyBaseUrl\": \"wm:proxyBaseUrl\",\n   \
  \ \"persistent\": \"wm:persistent\",\n    \"metadata\": \"wm:metadata\",\n    \"priority\": \"wm:priority\",\n    \"transformers\": \"wm:transformers\",\n    \"status\": \"wm:httpStatus\",\n    \"method\": \"wm:httpMethod\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wiremock/refs/heads/main/json-ld/wiremock-context.jsonld
tags:
- API Mocking
- Mock Server
- Mocking
- Platform
- Stubs
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
