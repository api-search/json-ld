---
api_specs:
- filename: amazon-waf-openapi.yml
  format: yaml
  label: Amazon WAF REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/openapi/amazon-waf-openapi.yml
class_count: 7
classes:
- name
- description
- url
- identifier
- dateCreated
- dateModified
- status
context_file: json-ld/amazon-waf-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/json-ld/amazon-waf-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Waf from Amazon WAF.
layout: jsonld
name: Amazon Waf Context
namespaces:
- prefix: waf
  uri: https://docs.aws.amazon.com/waf/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
properties:
- container: ''
  name: provider
  type: schema:Organization
- container: ''
  name: WebACL
  type: ''
- container: ''
  name: RuleGroup
  type: ''
- container: ''
  name: IPSet
  type: ''
- container: ''
  name: Tag
  type: ''
property_count: 5
provider_name: Amazon WAF
provider_slug: amazon-waf
slug: amazon-waf-context
source_filename: amazon-waf-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"waf\": \"https://docs.aws.amazon.com/waf/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"status\": \"schema:status\",\n    \"provider\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"WebACL\": {\n      \"@id\": \"waf:API_CreateWebACL.html\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Id\": \"schema:identifier\",\n        \"ARN\": \"schema:identifier\",\n        \"Description\": \"schema:description\",\n        \"DefaultAction\": \"waf:DefaultAction\",\n        \"Rules\": \"waf:Rules\",\n        \"Capacity\": \"waf:Capacity\"\n      }\n    },\n    \"RuleGroup\": {\n\
  \      \"@id\": \"waf:API_CreateRuleGroup.html\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Id\": \"schema:identifier\",\n        \"ARN\": \"schema:identifier\",\n        \"Description\": \"schema:description\",\n        \"Capacity\": \"waf:Capacity\",\n        \"Rules\": \"waf:Rules\"\n      }\n    },\n    \"IPSet\": {\n      \"@id\": \"waf:API_CreateIPSet.html\",\n      \"@context\": {\n        \"Name\": \"schema:name\",\n        \"Id\": \"schema:identifier\",\n        \"ARN\": \"schema:identifier\",\n        \"Description\": \"schema:description\",\n        \"IPAddressVersion\": \"waf:IPAddressVersion\",\n        \"Addresses\": \"waf:Addresses\"\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"waf:Tag\",\n      \"@context\": {\n        \"Key\": \"schema:name\",\n        \"Value\": \"schema:value\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-waf/refs/heads/main/json-ld/amazon-waf-context.jsonld
tags:
- Bot Management
- Ddos Protection
- Security
- WAF
- Web Application Firewall
- JSON-LD
- Linked Data
- Semantic Web
---
