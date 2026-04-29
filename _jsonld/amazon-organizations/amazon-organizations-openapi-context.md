---
class_count: 4
classes:
- Account
- Organization
- OrganizationalUnit
- Policy
context_file: json-ld/amazon-organizations-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/json-ld/amazon-organizations-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Organizations Openapi from Amazon Organizations.
layout: jsonld
name: Amazon Organizations Openapi Context
namespaces:
- prefix: organizations
  uri: https://organizations.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Arn
  type: string
- container: ''
  name: Content
  type: string
- container: ''
  name: Email
  type: string
- container: ''
  name: FeatureSet
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: JoinedMethod
  type: string
- container: ''
  name: JoinedTimestamp
  type: dateTime
- container: ''
  name: MasterAccountArn
  type: string
- container: ''
  name: MasterAccountEmail
  type: string
- container: ''
  name: MasterAccountId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: PolicySummary
  type: reference
- container: ''
  name: Status
  type: string
- container: ''
  name: Type
  type: string
property_count: 14
provider_name: Amazon Organizations
provider_slug: amazon-organizations
slug: amazon-organizations-openapi-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"organizations\": \"https://organizations.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": \"organizations:Account\",\n    \"Organization\": \"organizations:Organization\",\n    \"OrganizationalUnit\": \"organizations:OrganizationalUnit\",\n    \"Policy\": \"organizations:Policy\",\n    \"Arn\": {\n      \"@id\": \"organizations:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Content\": {\n      \"@id\": \"organizations:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Email\": {\n      \"@id\": \"organizations:Email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FeatureSet\": {\n      \"@id\": \"organizations:FeatureSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"organizations:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JoinedMethod\"\
  : {\n      \"@id\": \"organizations:JoinedMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JoinedTimestamp\": {\n      \"@id\": \"organizations:JoinedTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"MasterAccountArn\": {\n      \"@id\": \"organizations:MasterAccountArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MasterAccountEmail\": {\n      \"@id\": \"organizations:MasterAccountEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MasterAccountId\": {\n      \"@id\": \"organizations:MasterAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"organizations:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicySummary\": {\n      \"@id\": \"organizations:PolicySummary\",\n      \"@type\": \"@id\"\n    },\n    \"Status\": {\n      \"@id\": \"organizations:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"organizations:Type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/json-ld/amazon-organizations-openapi-context.jsonld
tags:
- Account Management
- AWS
- Consolidated Billing
- Governance
- Multi-Account
- Organizations
- Policies
- JSON-LD
- Linked Data
- Semantic Web
---
