---
api_specs:
- filename: safeline-management-openapi.yml
  format: yaml
  label: SafeLine Management API
  slug: safeline
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/openapi/safeline-management-openapi.yml
class_count: 26
classes:
- Website
- AclRule
- PolicyGroup
- Certificate
- SecurityReport
- ApiToken
- id
- name
- upstream
- ports
- enabled
- policy_group_id
- ssl_id
- create_time
- comment
- action
- conditions
- rule_name
- src_ip
- dst_host
- trigger_time
- hostname
- version
- domains
- not_valid_before
- not_valid_after
context_file: json-ld/safeline-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/json-ld/safeline-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Safeline from SafeLine.
layout: jsonld
name: Safeline Context
namespaces:
- prefix: safeline
  uri: https://waf.chaitin.com/vocab/
- prefix: security
  uri: https://w3id.org/security#
properties: []
property_count: 0
provider_name: SafeLine
provider_slug: safeline
slug: safeline-context
source_filename: safeline-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"safeline\": \"https://waf.chaitin.com/vocab/\",\n    \"security\": \"https://w3id.org/security#\",\n\n    \"Website\": \"schema:WebSite\",\n    \"AclRule\": \"safeline:AclRule\",\n    \"PolicyGroup\": \"safeline:PolicyGroup\",\n    \"Certificate\": \"schema:DigitalDocument\",\n    \"SecurityReport\": \"safeline:SecurityReport\",\n    \"ApiToken\": \"safeline:ApiToken\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"upstream\": \"safeline:upstream\",\n    \"ports\": \"safeline:ports\",\n    \"enabled\": \"schema:isAccessibleForFree\",\n    \"policy_group_id\": \"safeline:policyGroupId\",\n    \"ssl_id\": \"safeline:sslId\",\n    \"create_time\": \"schema:dateCreated\",\n    \"comment\": \"schema:description\",\n    \"action\": \"safeline:action\",\n    \"conditions\": \"safeline:conditions\",\n    \"rule_name\": \"schema:name\",\n    \"src_ip\": \"safeline:sourceIp\",\n    \"dst_host\": \"\
  safeline:destinationHost\",\n    \"trigger_time\": \"schema:startTime\",\n    \"hostname\": \"schema:hostName\",\n    \"version\": \"schema:version\",\n    \"domains\": \"schema:domain\",\n    \"not_valid_before\": \"schema:validFrom\",\n    \"not_valid_after\": \"schema:validUntil\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/json-ld/safeline-context.jsonld
tags:
- Proxy
- WAF
- Security
- Open Source
- Reverse Proxy
- API Gateway
- JSON-LD
- Linked Data
- Semantic Web
---
