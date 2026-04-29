---
class_count: 13
classes:
- attr_based_filter
- check_group_membership
- check_user_in_particular_group
- domain_param
- fetch_all_users_attrs
- group_filter
- list_all_groups_in_domain
- list_all_users_in_domain
- list_groups_user_belongs_to
- list_specific_groups
- list_specific_users
- list_users_in_particular_group
- pagination_params
context_file: json-ld/palo-alto-cloud-identity-engine-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cloud-identity-engine-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cloud Identity Engine Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cloud Identity Engine Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: attrName
  type: string
- container: ''
  name: attrValue
  type: string
- container: set
  name: attrs
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: filter
  type: reference
- container: ''
  name: level
  type: string
- container: ''
  name: match
  type: string
- container: ''
  name: name
  type: reference
- container: ''
  name: pageNum
  type: integer
- container: ''
  name: pageSz
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: useNormalizedAttrs
  type: string
property_count: 12
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cloud-identity-engine-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"attr_based_filter\": \"pan:attr_based_filter\",\n    \"check_group_membership\": \"pan:check_group_membership\",\n    \"check_user_in_particular_group\": \"pan:check_user_in_particular_group\",\n    \"domain_param\": \"pan:domain_param\",\n    \"fetch_all_users_attrs\": \"pan:fetch_all_users_attrs\",\n    \"group_filter\": \"pan:group_filter\",\n    \"list_all_groups_in_domain\": \"pan:list_all_groups_in_domain\",\n    \"list_all_users_in_domain\": \"pan:list_all_users_in_domain\",\n    \"list_groups_user_belongs_to\": \"pan:list_groups_user_belongs_to\",\n    \"list_specific_groups\": \"pan:list_specific_groups\",\n    \"list_specific_users\": \"pan:list_specific_users\",\n    \"list_users_in_particular_group\": \"pan:list_users_in_particular_group\"\
  ,\n    \"pagination_params\": \"pan:pagination_params\",\n    \"attrName\": {\n      \"@id\": \"pan:attrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attrValue\": {\n      \"@id\": \"pan:attrValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attrs\": {\n      \"@id\": \"pan:attrs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"pan:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"@id\"\n    },\n    \"level\": {\n      \"@id\": \"pan:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"match\": {\n      \"@id\": \"pan:match\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"@id\"\n    },\n    \"pageNum\": {\n      \"@id\": \"pan:pageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSz\": {\n      \"@id\": \"pan:pageSz\",\n      \"@type\": \"xsd:integer\"\n   \
  \ },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useNormalizedAttrs\": {\n      \"@id\": \"pan:useNormalizedAttrs\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cloud-identity-engine-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
