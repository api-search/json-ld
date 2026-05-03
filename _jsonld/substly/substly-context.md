---
class_count: 14
classes:
- name
- description
- url
- vendor
- renewalDate
- cost
- currency
- licenseCount
- userCount
- category
- status
- shadowIT
- department
- owner
context_file: json-ld/substly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/substly/refs/heads/main/json-ld/substly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Substly from Substly.
layout: jsonld
name: Substly Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: substly
  uri: https://www.substly.com/vocab#
properties:
- container: ''
  name: Subscription
  type: reference
- container: ''
  name: SaaSApplication
  type: reference
- container: ''
  name: Vendor
  type: reference
- container: ''
  name: License
  type: reference
- container: ''
  name: UserAccess
  type: reference
property_count: 5
provider_name: Substly
provider_slug: substly
slug: substly-context
source_filename: substly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"substly\": \"https://www.substly.com/vocab#\",\n\n    \"Subscription\": {\n      \"@id\": \"substly:Subscription\",\n      \"@type\": \"@id\",\n      \"schema:description\": \"A recurring SaaS software subscription tracked in Substly\"\n    },\n    \"SaaSApplication\": {\n      \"@id\": \"substly:SaaSApplication\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:SoftwareApplication\"\n    },\n    \"Vendor\": {\n      \"@id\": \"substly:Vendor\",\n      \"@type\": \"@id\",\n      \"schema:sameAs\": \"schema:Organization\"\n    },\n    \"License\": {\n      \"@id\": \"substly:License\",\n      \"@type\": \"@id\"\n    },\n    \"UserAccess\": {\n      \"@id\": \"substly:UserAccess\",\n      \"@type\": \"@id\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"vendor\": \"substly:vendor\",\n    \"renewalDate\"\
  : \"substly:renewalDate\",\n    \"cost\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"licenseCount\": \"substly:licenseCount\",\n    \"userCount\": \"substly:userCount\",\n    \"category\": \"schema:applicationCategory\",\n    \"status\": \"substly:status\",\n    \"shadowIT\": \"substly:shadowIT\",\n    \"department\": \"schema:department\",\n    \"owner\": \"schema:accountablePerson\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/substly/refs/heads/main/json-ld/substly-context.jsonld
tags:
- SaaS Management
- Subscription Management
- Spend Management
- IT Management
- Shadow IT
- JSON-LD
- Linked Data
- Semantic Web
---
