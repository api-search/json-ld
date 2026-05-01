---
api_specs:
- filename: eloqua-rest-openapi.yml
  format: yaml
  label: Eloqua REST API
  slug: eloqua-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/openapi/eloqua-rest-openapi.yml
- filename: eloqua-bulk-openapi.yml
  format: yaml
  label: Eloqua Bulk API
  slug: eloqua-bulk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/openapi/eloqua-bulk-openapi.yml
class_count: 0
classes: []
context_file: json-ld/eloqua-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/json-ld/eloqua-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Eloqua from Oracle Eloqua.
layout: jsonld
name: Eloqua Context
namespaces:
- prefix: eloqua
  uri: https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Email
  type: ''
- container: ''
  name: Form
  type: ''
- container: ''
  name: LandingPage
  type: ''
- container: ''
  name: ContactSegment
  type: ''
- container: ''
  name: CustomObject
  type: ''
- container: ''
  name: Program
  type: ''
- container: ''
  name: User
  type: ''
property_count: 10
provider_name: Oracle Eloqua
provider_slug: eloqua
slug: eloqua-context
source_filename: eloqua-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"eloqua\": \"https://docs.oracle.com/en/cloud/saas/marketing/eloqua-rest-api/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Contact\": {\n      \"@id\": \"eloqua:Contact\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"emailAddress\": \"schema:email\",\n        \"title\": \"schema:jobTitle\",\n        \"accountName\": \"schema:worksFor\",\n        \"address1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"province\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"businessPhone\": \"schema:telephone\",\n        \"mobilePhone\": \"schema:telephone\",\n        \"isSubscribed\"\
  : {\n          \"@id\": \"eloqua:isSubscribed\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"eloqua:Account\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"companyName\": \"schema:legalName\",\n        \"address1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"province\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\",\n        \"businessPhone\": \"schema:telephone\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"\
  @type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"eloqua:Campaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"currentStatus\": \"eloqua:currentStatus\",\n        \"campaignCategory\": \"eloqua:campaignCategory\",\n        \"startAt\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endAt\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"memberCount\": {\n          \"@id\": \"eloqua:memberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Email\": {\n      \"@id\": \"eloqua:Email\",\n      \"@context\"\
  : {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"subject\": \"eloqua:subject\",\n        \"senderName\": \"eloqua:senderName\",\n        \"senderEmail\": \"schema:email\",\n        \"replyToEmail\": \"eloqua:replyToEmail\",\n        \"previewText\": \"eloqua:previewText\",\n        \"isTracked\": {\n          \"@id\": \"eloqua:isTracked\",\n          \"@type\": \"xsd:string\"\n        },\n        \"archived\": {\n          \"@id\": \"eloqua:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Form\": {\n      \"@id\": \"eloqua:Form\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"htmlName\": \"eloqua:htmlName\"\
  ,\n        \"currentStatus\": \"eloqua:currentStatus\",\n        \"archived\": {\n          \"@id\": \"eloqua:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"LandingPage\": {\n      \"@id\": \"eloqua:LandingPage\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"relativePath\": \"schema:url\",\n        \"currentStatus\": \"eloqua:currentStatus\",\n        \"archived\": {\n          \"@id\": \"eloqua:archived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n     \
  \     \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ContactSegment\": {\n      \"@id\": \"eloqua:ContactSegment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"count\": {\n          \"@id\": \"eloqua:count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastCalculatedAt\": {\n          \"@id\": \"eloqua:lastCalculatedAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CustomObject\": {\n      \"@id\": \"eloqua:CustomObject\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"displayNameFieldId\": \"eloqua:displayNameFieldId\",\n        \"uniqueCodeFieldId\"\
  : \"eloqua:uniqueCodeFieldId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Program\": {\n      \"@id\": \"eloqua:Program\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"currentStatus\": \"eloqua:currentStatus\",\n        \"scheduledFor\": {\n          \"@id\": \"eloqua:scheduledFor\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"eloqua:User\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"loginName\"\
  : \"eloqua:loginName\",\n        \"emailAddress\": \"schema:email\",\n        \"company\": \"schema:worksFor\",\n        \"enabled\": {\n          \"@id\": \"eloqua:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:string\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/eloqua/refs/heads/main/json-ld/eloqua-context.jsonld
tags:
- CRM
- Email Marketing
- Lead Management
- Marketing Automation
- JSON-LD
- Linked Data
- Semantic Web
---
