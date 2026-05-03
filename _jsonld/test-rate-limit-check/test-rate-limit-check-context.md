---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Kong Gateway Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.konghq.com/gateway/latest/admin-api/
- filename: x-tyk-gateway.json
  format: json
  label: Tyk API Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/TykTechnologies/tyk/master/apidef/oas/schema/x-tyk-gateway.json
- filename: api-spec.json
  format: json
  label: Grafana API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/grafana/grafana/main/public/api-spec.json
class_count: 3
classes:
- APIQuota
- RateLimitConfig
- RateLimitResponse
context_file: json-ld/test-rate-limit-check-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/test-rate-limit-check/refs/heads/main/json-ld/test-rate-limit-check-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Test Rate Limit Check from Test Rate Limit Check.
layout: jsonld
name: Test Rate Limit Check Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: testratelimitcheck
  uri: https://api-evangelist.github.io/test-rate-limit-check/schema/
properties:
- container: ''
  name: apiName
  type: string
- container: ''
  name: burstLimit
  type: integer
- container: ''
  name: consumerId
  type: string
- container: ''
  name: documentationUrl
  type: reference
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: error
  type: string
- container: ''
  name: headers
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: limit
  type: integer
- container: ''
  name: limitHeader
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: overageEnabled
  type: boolean
- container: ''
  name: overageRate
  type: decimal
- container: ''
  name: percentageUsed
  type: decimal
- container: ''
  name: period
  type: string
- container: ''
  name: periodEnd
  type: dateTime
- container: ''
  name: periodStart
  type: dateTime
- container: ''
  name: remaining
  type: integer
- container: ''
  name: remainingHeader
  type: string
- container: ''
  name: resetAt
  type: dateTime
- container: ''
  name: resetHeader
  type: string
- container: ''
  name: responseStatus
  type: integer
- container: ''
  name: retryAfterHeader
  type: string
- container: ''
  name: retryAfterSeconds
  type: integer
- container: ''
  name: scope
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: tier
  type: string
- container: ''
  name: totalLimit
  type: integer
- container: ''
  name: used
  type: integer
- container: ''
  name: windowSeconds
  type: integer
- container: ''
  name: windowType
  type: string
property_count: 32
provider_name: Test Rate Limit Check
provider_slug: test-rate-limit-check
slug: test-rate-limit-check-context
source_filename: test-rate-limit-check-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"testratelimitcheck\": \"https://api-evangelist.github.io/test-rate-limit-check/schema/\",\n    \"APIQuota\": \"testratelimitcheck:APIQuota\",\n    \"RateLimitConfig\": \"testratelimitcheck:RateLimitConfig\",\n    \"RateLimitResponse\": \"testratelimitcheck:RateLimitResponse\",\n    \"apiName\": {\n      \"@id\": \"testratelimitcheck:api_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"burstLimit\": {\n      \"@id\": \"testratelimitcheck:burst_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"consumerId\": {\n      \"@id\": \"testratelimitcheck:consumer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentationUrl\": {\n      \"@id\": \"testratelimitcheck:documentation_url\",\n      \"@type\": \"@id\"\n    },\n    \"enabled\": {\n      \"@id\": \"testratelimitcheck:enabled\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"error\": {\n      \"@id\": \"testratelimitcheck:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headers\": {\n      \"@id\": \"testratelimitcheck:headers\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"limit\": {\n      \"@id\": \"testratelimitcheck:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limitHeader\": {\n      \"@id\": \"testratelimitcheck:limit_header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"testratelimitcheck:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"overageEnabled\": {\n      \"@id\": \"testratelimitcheck:overage_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"overageRate\": {\n      \"@id\": \"testratelimitcheck:overage_rate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"percentageUsed\": {\n      \"@id\": \"testratelimitcheck:percentage_used\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"period\": {\n      \"@id\": \"testratelimitcheck:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodEnd\": {\n      \"@id\": \"testratelimitcheck:period_end\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"periodStart\": {\n      \"@id\": \"testratelimitcheck:period_start\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"remaining\": {\n      \"@id\": \"testratelimitcheck:remaining\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remainingHeader\": {\n      \"@id\": \"testratelimitcheck:remaining_header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resetAt\": {\n      \"@id\": \"testratelimitcheck:reset_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"resetHeader\": {\n      \"@id\": \"testratelimitcheck:reset_header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseStatus\": {\n      \"@id\": \"testratelimitcheck:response_status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"retryAfterHeader\"\
  : {\n      \"@id\": \"testratelimitcheck:retry_after_header\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retryAfterSeconds\": {\n      \"@id\": \"testratelimitcheck:retry_after_seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": {\n      \"@id\": \"testratelimitcheck:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"testratelimitcheck:status_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tier\": {\n      \"@id\": \"testratelimitcheck:tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalLimit\": {\n      \"@id\": \"testratelimitcheck:total_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"used\": {\n      \"@id\": \"testratelimitcheck:used\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"windowSeconds\": {\n      \"@id\": \"testratelimitcheck:window_seconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"windowType\": {\n      \"@id\": \"testratelimitcheck:window_type\",\n      \"@type\": \"\
  xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/test-rate-limit-check/refs/heads/main/json-ld/test-rate-limit-check-context.jsonld
tags:
- API Governance
- API Management
- API Testing
- Performance Testing
- Rate Limiting
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
