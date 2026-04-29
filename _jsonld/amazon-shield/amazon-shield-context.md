---
class_count: 0
classes: []
context_file: json-ld/amazon-shield-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/json-ld/amazon-shield-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Shield from Amazon Shield.
layout: jsonld
name: Amazon Shield Context
namespaces:
- prefix: shield
  uri: https://docs.aws.amazon.com/waf/latest/DDOSAPIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: iam
  uri: https://docs.aws.amazon.com/IAM/latest/UserGuide/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Protection
  type: ''
- container: ''
  name: Attack
  type: ''
- container: ''
  name: Subscription
  type: ''
property_count: 3
provider_name: Amazon Shield
provider_slug: amazon-shield
slug: amazon-shield-context
source_filename: amazon-shield-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"shield\": \"https://docs.aws.amazon.com/waf/latest/DDOSAPIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"iam\": \"https://docs.aws.amazon.com/IAM/latest/UserGuide/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Protection\": {\n      \"@id\": \"shield:API_DescribeProtection.html\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ResourceArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"ProtectionArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Attack\": {\n\
  \      \"@id\": \"shield:API_DescribeAttack.html\",\n      \"@context\": {\n        \"AttackId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ResourceArn\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"StartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"EndTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"shield:API_DescribeSubscription.html\",\n      \"@context\": {\n        \"StartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"EndTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"TimeCommitmentInSeconds\": {\n          \"@id\": \"shield:TimeCommitment\",\n          \"@type\": \"xsd:long\"\
  \n        },\n        \"AutoRenew\": {\n          \"@id\": \"shield:AutoRenew\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/json-ld/amazon-shield-context.jsonld
tags:
- AWS
- DDoS Protection
- Networking
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
