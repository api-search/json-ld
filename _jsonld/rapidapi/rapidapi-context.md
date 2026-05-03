---
api_specs:
- filename: rapidapi-rest-platform-api-openapi.yml
  format: yaml
  label: RapidAPI REST Platform API
  slug: rapidapi-rest-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-rest-platform-api-openapi.yml
- filename: rapidapi-graphql-platform-api-openapi.yml
  format: yaml
  label: RapidAPI GraphQL Platform API
  slug: rapidapi-graphql-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-graphql-platform-api-openapi.yml
- filename: rapidapi-hub-api-openapi.yml
  format: yaml
  label: RapidAPI Hub API
  slug: rapidapi-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-hub-api-openapi.yml
- filename: rapidapi-testing-api-openapi.yml
  format: yaml
  label: RapidAPI Testing API
  slug: rapidapi-testing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-testing-api-openapi.yml
- filename: rapidapi-studio-api-openapi.yml
  format: yaml
  label: RapidAPI Studio API
  slug: rapidapi-studio-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-studio-api-openapi.yml
- filename: rapidapi-gateway-api-openapi.yml
  format: yaml
  label: RapidAPI Gateway API
  slug: rapidapi-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/openapi/rapidapi-gateway-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/rapidapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/json-ld/rapidapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rapidapi from RapidAPI.
layout: jsonld
name: Rapidapi Context
namespaces:
- prefix: rapidapi
  uri: https://rapidapi.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ApiListing
  type: ''
- container: ''
  name: ApiEndpoint
  type: ''
- container: ''
  name: PricingPlan
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Collection
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Test
  type: ''
- container: ''
  name: Application
  type: ''
property_count: 11
provider_name: RapidAPI
provider_slug: rapidapi
slug: rapidapi-context
source_filename: rapidapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rapidapi\": \"https://rapidapi.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ApiListing\": {\n      \"@id\": \"rapidapi:ApiListing\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"slug\": \"rapidapi:slug\",\n        \"longDescription\": \"rapidapi:longDescription\",\n        \"category\": \"schema:category\",\n        \"tags\": \"schema:keywords\",\n        \"websiteUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"rapidapi:status\",\n        \"isVerified\": \"rapidapi:isVerified\",\n        \"provider\": \"schema:provider\",\n        \"averageRating\": \"schema:aggregateRating\"\
  ,\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiEndpoint\": {\n      \"@id\": \"rapidapi:ApiEndpoint\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"method\": \"rapidapi:httpMethod\",\n        \"path\": \"rapidapi:urlPath\",\n        \"group\": \"rapidapi:endpointGroup\",\n        \"parameters\": {\n          \"@id\": \"rapidapi:parameters\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PricingPlan\": {\n      \"@id\": \"rapidapi:PricingPlan\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"price\": \"schema:price\",\n        \"rateLimit\": \"rapidapi:rateLimit\",\n        \"features\": {\n          \"@id\": \"rapidapi:features\",\n          \"@container\"\
  : \"@set\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"thumbnail\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"role\": \"rapidapi:role\",\n        \"status\": \"rapidapi:accountStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"rapidapi:Subscription\",\n      \"@context\": {\n        \"apiId\": \"rapidapi:subscribedApi\",\n        \"planName\": \"\
  rapidapi:planName\",\n        \"status\": \"rapidapi:subscriptionStatus\",\n        \"usageCount\": \"rapidapi:usageCount\",\n        \"usageLimit\": \"rapidapi:usageLimit\",\n        \"subscribedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"rapidapi:Collection\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"apis\": {\n          \"@id\": \"rapidapi:containsApi\",\n          \"@container\": \"@set\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Category\": {\n      \"@id\": \"rapidapi:Category\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"slugifiedName\": \"rapidapi:slug\",\n        \"apiCount\": \"rapidapi:apiCount\"\n      }\n    },\n\n    \"Gateway\": {\n      \"@id\": \"rapidapi:Gateway\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"deploymentModel\": \"rapidapi:deploymentModel\",\n        \"status\": \"rapidapi:gatewayStatus\",\n        \"baseUrl\": {\n          \"@id\": \"rapidapi:baseUrl\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Test\": {\n      \"@id\": \"rapidapi:Test\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"rapidapi:testType\",\n        \"status\": \"rapidapi:testStatus\",\n        \"steps\": {\n          \"@id\": \"rapidapi:testSteps\",\n          \"@container\": \"@list\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"rapidapi:applicationStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rapidapi/refs/heads/main/json-ld/rapidapi-context.jsonld
tags:
- API Marketplace
- API Management
- API Testing
- API Gateway
- API Design
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
