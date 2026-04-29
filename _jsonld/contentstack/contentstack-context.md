---
api_specs:
- filename: contentstack-content-delivery-api-openapi.yml
  format: yaml
  label: Contentstack Content Delivery API
  slug: content-delivery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-content-delivery-api-openapi.yml
- filename: contentstack-content-management-api-openapi.yml
  format: yaml
  label: Contentstack Content Management API
  slug: content-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-content-management-api-openapi.yml
- filename: contentstack-personalize-management-api-openapi.yml
  format: yaml
  label: Contentstack Personalize Management API
  slug: personalize-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-personalize-management-api-openapi.yml
- filename: contentstack-personalize-edge-api-openapi.yml
  format: yaml
  label: Contentstack Personalize Edge API
  slug: personalize-edge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-personalize-edge-api-openapi.yml
- filename: contentstack-automate-management-api-openapi.yml
  format: yaml
  label: Contentstack Automate Management API
  slug: automate-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-automate-management-api-openapi.yml
- filename: contentstack-analytics-api-openapi.yml
  format: yaml
  label: Contentstack Analytics API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-analytics-api-openapi.yml
- filename: contentstack-scim-api-openapi.yml
  format: yaml
  label: Contentstack SCIM API
  slug: scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-scim-api-openapi.yml
- filename: contentstack-brand-kit-management-api-openapi.yml
  format: yaml
  label: Contentstack Brand Kit Management API
  slug: brand-kit-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-brand-kit-management-api-openapi.yml
- filename: contentstack-knowledge-vault-api-openapi.yml
  format: yaml
  label: Contentstack Knowledge Vault API
  slug: knowledge-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-knowledge-vault-api-openapi.yml
- filename: contentstack-generative-ai-api-openapi.yml
  format: yaml
  label: Contentstack Generative AI API
  slug: generative-ai-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-generative-ai-api-openapi.yml
- filename: contentstack-launch-api-openapi.yml
  format: yaml
  label: Contentstack Launch API
  slug: launch-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-launch-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/contentstack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/json-ld/contentstack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Contentstack from contentstack.
layout: jsonld
name: Contentstack Context
namespaces:
- prefix: cs
  uri: https://www.contentstack.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Stack
  type: ''
- container: ''
  name: ContentType
  type: ''
- container: ''
  name: Entry
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Audience
  type: ''
- container: ''
  name: Experience
  type: ''
- container: ''
  name: BrandKit
  type: ''
- container: ''
  name: VoiceProfile
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: WebhookEvent
  type: ''
property_count: 13
provider_name: contentstack
provider_slug: contentstack
slug: contentstack-context
source_filename: contentstack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cs\": \"https://www.contentstack.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Stack\": {\n      \"@id\": \"cs:Stack\",\n      \"@context\": {\n        \"apiKey\": {\n          \"@id\": \"cs:apiKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"masterLocale\": {\n          \"@id\": \"cs:masterLocale\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organization\": {\n          \"@id\": \"cs:organization\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n      \
  \    \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ContentType\": {\n      \"@id\": \"cs:ContentType\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"schema\": {\n          \"@id\": \"cs:schema\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Entry\": {\n      \"@id\": \"cs:Entry\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"title\": \"schema:name\",\n        \"locale\": {\n          \"@id\": \"cs:locale\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"cs:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"contentType\"\
  : {\n          \"@id\": \"cs:contentType\",\n          \"@type\": \"@id\"\n        },\n        \"publishDetails\": {\n          \"@id\": \"cs:publishDetails\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"cs:tags\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"cs:publishedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"cs:Asset\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"title\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"filename\": \"schema:name\",\n        \"contentType\": \"schema:encodingFormat\"\
  ,\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": \"schema:description\",\n        \"tags\": {\n          \"@id\": \"cs:tags\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"cs:Environment\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"urls\": {\n          \"@id\": \"cs:urls\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"cs:Organization\",\n      \"@context\": {\n    \
  \    \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"planId\": {\n          \"@id\": \"cs:planId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Audience\": {\n      \"@id\": \"cs:Audience\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"rules\": {\n          \"@id\": \"cs:rules\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n \
  \         \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Experience\": {\n      \"@id\": \"cs:Experience\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"type\": {\n          \"@id\": \"cs:experienceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"cs:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"variants\": {\n          \"@id\": \"cs:variants\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BrandKit\": {\n      \"@id\": \"cs:BrandKit\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"organization\": {\n          \"@id\": \"cs:organization\",\n          \"@type\": \"@id\"\n        },\n        \"voiceProfiles\"\
  : {\n          \"@id\": \"cs:voiceProfiles\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VoiceProfile\": {\n      \"@id\": \"cs:VoiceProfile\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"tone\": {\n          \"@id\": \"cs:tone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"styleGuidelines\": {\n          \"@id\": \"cs:styleGuidelines\",\n          \"@type\": \"xsd:string\"\n        },\n        \"brandKit\": {\n          \"@id\": \"cs:brandKit\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n    \
  \  }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"cs:Deployment\",\n      \"@context\": {\n        \"uid\": \"cs:uid\",\n        \"status\": {\n          \"@id\": \"cs:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"environment\": {\n          \"@id\": \"cs:environment\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"cs:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WebhookEvent\": {\n      \"@id\": \"cs:WebhookEvent\",\n      \"@context\": {\n        \"event\": {\n          \"@id\": \"cs:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"module\": {\n          \"@id\": \"cs:module\",\n          \"@type\": \"xsd:string\"\n        },\n        \"apiKey\": {\n          \"@id\": \"cs:apiKey\",\n          \"@type\": \"xsd:string\"\n      \
  \  },\n        \"triggeredAt\": {\n          \"@id\": \"cs:triggeredAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/json-ld/contentstack-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
