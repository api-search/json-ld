---
api_specs:
- filename: optimizely-web-experimentation-openapi.yml
  format: yaml
  label: Optimizely Web Experimentation REST API
  slug: web-experimentation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-web-experimentation-openapi.yml
- filename: optimizely-feature-experimentation-openapi.yml
  format: yaml
  label: Optimizely Feature Experimentation REST API
  slug: feature-experimentation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-feature-experimentation-openapi.yml
- filename: optimizely-campaign-openapi.yml
  format: yaml
  label: Optimizely Campaign REST API
  slug: campaign
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-campaign-openapi.yml
- filename: optimizely-content-delivery-openapi.yml
  format: yaml
  label: Optimizely Content Delivery API
  slug: content-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-content-delivery-openapi.yml
- filename: optimizely-content-management-openapi.yml
  format: yaml
  label: Optimizely Content Management API
  slug: content-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-content-management-openapi.yml
- filename: optimizely-graph-openapi.yml
  format: yaml
  label: Optimizely Graph API
  slug: graph
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-graph-openapi.yml
- filename: optimizely-data-platform-openapi.yml
  format: yaml
  label: Optimizely Data Platform REST API
  slug: data-platform
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-data-platform-openapi.yml
- filename: optimizely-cmp-openapi.yml
  format: yaml
  label: Optimizely CMP Open REST API
  slug: cmp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-cmp-openapi.yml
- filename: optimizely-commerce-service-openapi.yml
  format: yaml
  label: Optimizely Commerce Service API
  slug: commerce-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/openapi/optimizely-commerce-service-openapi.yml
class_count: 0
classes: []
context_file: json-ld/optimizely-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/json-ld/optimizely-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Optimizely from Optimizely.
layout: jsonld
name: Optimizely Context
namespaces:
- prefix: opti
  uri: https://api.optimizely.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Experiment
  type: ''
- container: ''
  name: Variation
  type: ''
- container: ''
  name: FeatureFlag
  type: ''
- container: ''
  name: Audience
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: CustomerProfile
  type: ''
- container: ''
  name: ContentItem
  type: ''
- container: ''
  name: CatalogEntry
  type: ''
- container: ''
  name: Order
  type: ''
property_count: 12
provider_name: Optimizely
provider_slug: optimizely
slug: optimizely-context
source_filename: optimizely-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"opti\": \"https://api.optimizely.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"opti:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"platform\": \"opti:platform\",\n        \"status\": \"opti:status\",\n        \"accountId\": \"opti:accountId\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Experiment\": {\n      \"@id\": \"opti:Experiment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"opti:status\"\
  ,\n        \"experimentType\": \"opti:experimentType\",\n        \"holdback\": \"opti:holdback\",\n        \"project\": {\n          \"@id\": \"opti:project\",\n          \"@type\": \"@id\"\n        },\n        \"variations\": {\n          \"@id\": \"opti:variations\",\n          \"@container\": \"@set\"\n        },\n        \"metrics\": {\n          \"@id\": \"opti:metrics\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Variation\": {\n      \"@id\": \"opti:Variation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"key\": \"opti:key\",\n        \"weight\": \"opti:weight\"\n      }\n    },\n\n    \"FeatureFlag\": {\n      \"@id\": \"opti:FeatureFlag\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"key\": \"opti:key\",\n        \"description\": \"schema:description\",\n        \"variables\": {\n          \"@id\": \"opti:variables\",\n          \"@container\": \"@set\"\n        },\n        \"variations\": {\n          \"@id\": \"opti:flagVariations\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Audience\": {\n      \"@id\": \"opti:Audience\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"conditions\": \"opti:conditions\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"opti:Campaign\",\n      \"@context\": {\n\
  \        \"name\": \"schema:name\",\n        \"status\": \"opti:status\",\n        \"experiments\": {\n          \"@id\": \"opti:experiments\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"opti:Page\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"editUrl\": {\n          \"@id\": \"opti:editUrl\",\n          \"@type\": \"@id\"\n        },\n        \"activationType\": \"opti:activationType\",\n        \"conditions\": \"opti:conditions\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"opti:Event\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"key\": \"opti:key\",\n        \"eventType\": \"opti:eventType\"\n      }\n    },\n\n    \"CustomerProfile\": {\n      \"@id\": \"opti:CustomerProfile\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"\
  firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"zipCode\": \"schema:postalCode\",\n        \"segments\": {\n          \"@id\": \"opti:segments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ContentItem\": {\n      \"@id\": \"opti:ContentItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"contentType\": \"opti:contentType\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"language\": \"schema:inLanguage\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"published\": {\n          \"@id\": \"schema:datePublished\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"CatalogEntry\": {\n      \"@id\": \"opti:CatalogEntry\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"code\": \"schema:sku\",\n        \"entryType\": \"opti:entryType\",\n        \"price\": \"schema:price\",\n        \"currency\": \"schema:priceCurrency\",\n        \"isActive\": \"schema:availability\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"opti:Order\",\n      \"@context\": {\n        \"orderId\": \"schema:orderNumber\",\n        \"customer\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"@id\"\n        },\n        \"total\": \"schema:totalPrice\",\n        \"currency\": \"schema:priceCurrency\",\n        \"status\": \"schema:orderStatus\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/optimizely/refs/heads/main/json-ld/optimizely-context.jsonld
tags:
- A/B Testing
- Content Management
- Customer Data
- E-Commerce
- Experimentation
- Feature Flags
- Marketing
- JSON-LD
- Linked Data
- Semantic Web
---
