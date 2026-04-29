---
api_specs:
- filename: amazon-organizations-openapi.yml
  format: yaml
  label: AWS Organizations API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/openapi/amazon-organizations-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-organizations-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/json-ld/amazon-organizations-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Organizations from Amazon Organizations.
layout: jsonld
name: Amazon Organizations Context
namespaces:
- prefix: orgs
  uri: https://docs.aws.amazon.com/organizations/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: OrganizationalUnit
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Root
  type: ''
property_count: 5
provider_name: Amazon Organizations
provider_slug: amazon-organizations
slug: amazon-organizations-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"orgs\": \"https://docs.aws.amazon.com/organizations/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"orgs:API_DescribeOrganization\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"orgs:organizationArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"FeatureSet\": {\n          \"@id\": \"orgs:featureSet\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MasterAccountArn\": {\n          \"@id\": \"orgs:masterAccountArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MasterAccountId\": {\n          \"@id\": \"orgs:masterAccountId\",\n  \
  \        \"@type\": \"xsd:string\"\n        },\n        \"MasterAccountEmail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"AvailablePolicyTypes\": {\n          \"@id\": \"orgs:availablePolicyTypes\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"orgs:API_DescribeAccount\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"orgs:accountArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"orgs:accountStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"JoinedMethod\": {\n   \
  \       \"@id\": \"orgs:joinedMethod\",\n          \"@type\": \"xsd:string\"\n        },\n        \"JoinedTimestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"OrganizationalUnit\": {\n      \"@id\": \"orgs:API_DescribeOrganizationalUnit\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"orgs:ouArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"orgs:API_DescribePolicy\",\n      \"@context\": {\n        \"PolicySummary\": {\n          \"@id\": \"orgs:policySummary\",\n          \"@type\": \"orgs:PolicySummary\"\n        },\n        \"Content\": {\n          \"@id\": \"orgs:policyContent\",\n          \"@type\": \"xsd:string\"\
  \n        }\n      }\n    },\n\n    \"Root\": {\n      \"@id\": \"orgs:API_ListRoots\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"orgs:rootArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PolicyTypes\": {\n          \"@id\": \"orgs:policyTypes\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-organizations/refs/heads/main/json-ld/amazon-organizations-context.jsonld
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
