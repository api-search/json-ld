---
api_specs:
- filename: api-docs
  format: yaml
  label: Regulations.gov API
  slug: regulations-gov
  spec_type: OpenAPI
  url: https://api.regulations.gov/v4/api-docs
class_count: 6
classes:
- name
- description
- url
- identifier
- datePublished
- dateModified
context_file: json-ld/regulation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-ld/regulation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Regulation from Regulation.
layout: jsonld
name: Regulation Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: reg
  uri: https://api-evangelist.github.io/regulation/vocab#
properties:
- container: ''
  name: Regulation
  type: schema:Legislation
- container: ''
  name: RegulatoryAgency
  type: schema:GovernmentOrganization
- container: ''
  name: Docket
  type: schema:CreativeWork
- container: ''
  name: ProposedRule
  type: schema:Legislation
- container: ''
  name: FinalRule
  type: schema:Legislation
- container: ''
  name: PublicComment
  type: schema:Comment
- container: ''
  name: RegulatoryChange
  type: schema:Event
property_count: 7
provider_name: Regulation
provider_slug: regulation
slug: regulation-context
source_filename: regulation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"reg\": \"https://api-evangelist.github.io/regulation/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"datePublished\": \"schema:datePublished\",\n    \"dateModified\": \"schema:dateModified\",\n    \"Regulation\": {\n      \"@id\": \"reg:Regulation\",\n      \"@type\": \"schema:Legislation\",\n      \"@context\": {\n        \"legislationIdentifier\": \"schema:legislationIdentifier\",\n        \"jurisdiction\": \"schema:legislationJurisdiction\",\n        \"effectiveDate\": \"schema:legislationDate\",\n        \"agency\": \"reg:regulatoryAgency\",\n        \"cfr\": \"reg:cfrCitation\",\n        \"status\": \"reg:regulationStatus\"\n      }\n    },\n    \"RegulatoryAgency\": {\n      \"@id\": \"reg:RegulatoryAgency\",\n      \"@type\": \"schema:GovernmentOrganization\"\
  ,\n      \"@context\": {\n        \"acronym\": \"schema:alternateName\",\n        \"parentAgency\": \"schema:parentOrganization\",\n        \"jurisdiction\": \"schema:locationCreated\"\n      }\n    },\n    \"Docket\": {\n      \"@id\": \"reg:Docket\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"docketId\": \"reg:docketId\",\n        \"agency\": \"reg:regulatoryAgency\",\n        \"ruleType\": \"reg:ruleType\",\n        \"commentCount\": \"reg:commentCount\",\n        \"openForComment\": \"reg:openForComment\"\n      }\n    },\n    \"ProposedRule\": {\n      \"@id\": \"reg:ProposedRule\",\n      \"@type\": \"schema:Legislation\",\n      \"@context\": {\n        \"docketId\": \"reg:docketId\",\n        \"commentDeadline\": \"reg:commentDeadline\",\n        \"cfr\": \"reg:cfrCitation\"\n      }\n    },\n    \"FinalRule\": {\n      \"@id\": \"reg:FinalRule\",\n      \"@type\": \"schema:Legislation\",\n      \"@context\": {\n        \"effectiveDate\": \"schema:legislationDate\"\
  ,\n        \"cfr\": \"reg:cfrCitation\"\n      }\n    },\n    \"PublicComment\": {\n      \"@id\": \"reg:PublicComment\",\n      \"@type\": \"schema:Comment\",\n      \"@context\": {\n        \"docketId\": \"reg:docketId\",\n        \"commentId\": \"reg:commentId\",\n        \"submittedDate\": \"schema:dateSubmitted\",\n        \"commenter\": \"schema:author\"\n      }\n    },\n    \"RegulatoryChange\": {\n      \"@id\": \"reg:RegulatoryChange\",\n      \"@type\": \"schema:Event\",\n      \"@context\": {\n        \"changeType\": \"reg:changeType\",\n        \"effectiveDate\": \"schema:startDate\",\n        \"regulation\": \"reg:Regulation\",\n        \"impactedEntities\": \"reg:impactedEntities\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-ld/regulation-context.jsonld
tags:
- Compliance
- Governance
- Government
- Legal
- Policy
- Regulation
- Regulatory Change
- Risk Management
- JSON-LD
- Linked Data
- Semantic Web
---
