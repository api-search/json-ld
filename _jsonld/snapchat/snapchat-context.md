---
api_specs:
- filename: snapchat-ads-api-openapi.yml
  format: yaml
  label: Snapchat Ads API
  slug: snapchat-ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-ads-api-openapi.yml
- filename: snapchat-conversions-api-openapi.yml
  format: yaml
  label: Snapchat Conversions API
  slug: snapchat-conversions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-conversions-api-openapi.yml
- filename: snapchat-login-kit-openapi.yml
  format: yaml
  label: Snapchat Login Kit API
  slug: snapchat-login-kit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/openapi/snapchat-login-kit-openapi.yml
class_count: 0
classes: []
context_file: json-ld/snapchat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/json-ld/snapchat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Snapchat from Snapchat.
layout: jsonld
name: Snapchat Context
namespaces:
- prefix: snap
  uri: https://developers.snap.com/ns/
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
  name: AdAccount
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: AdSquad
  type: ''
- container: ''
  name: Ad
  type: ''
- container: ''
  name: Creative
  type: ''
- container: ''
  name: Media
  type: ''
- container: ''
  name: ConversionEvent
  type: ''
- container: ''
  name: AudienceSegment
  type: ''
- container: ''
  name: UserProfile
  type: ''
property_count: 10
provider_name: Snapchat
provider_slug: snapchat
slug: snapchat-context
source_filename: snapchat-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"snap\": \"https://developers.snap.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Organization\": {\n      \"@id\": \"snap:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"snap:organizationType\",\n        \"addressLine1\": \"schema:streetAddress\",\n        \"locality\": \"schema:addressLocality\",\n        \"administrativeDistrictLevel1\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\",\n        \"postalCode\": \"schema:postalCode\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AdAccount\": {\n      \"@id\": \"snap:AdAccount\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"organization\": {\n          \"@id\": \"snap:organization\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"snap:status\",\n        \"currency\": \"schema:currency\",\n        \"timezone\": \"snap:timezone\",\n        \"advertiser\": \"snap:advertiser\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Campaign\": {\n      \"@id\": \"snap:Campaign\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"adAccount\": {\n          \"@id\": \"snap:adAccount\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"snap:status\",\n        \"dailyBudget\": {\n          \"@id\": \"snap:dailyBudgetMicro\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lifetimeSpendCap\"\
  : {\n          \"@id\": \"snap:lifetimeSpendCapMicro\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AdSquad\": {\n      \"@id\": \"snap:AdSquad\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"campaign\": {\n          \"@id\": \"snap:campaign\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"snap:status\",\n        \"type\": \"snap:adSquadType\",\n        \"placement\": \"snap:placement\",\n        \"bid\": {\n          \"@id\": \"snap:bidMicro\",\n  \
  \        \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Ad\": {\n      \"@id\": \"snap:Ad\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"adSquad\": {\n          \"@id\": \"snap:adSquad\",\n          \"@type\": \"@id\"\n        },\n        \"creative\": {\n          \"@id\": \"snap:creative\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"snap:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n    \
  \    },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Creative\": {\n      \"@id\": \"snap:Creative\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"snap:creativeType\",\n        \"headline\": \"schema:headline\",\n        \"brandName\": \"schema:brand\",\n        \"shareable\": \"snap:shareable\",\n        \"callToAction\": \"snap:callToAction\",\n        \"topSnapMediaId\": {\n          \"@id\": \"snap:topSnapMedia\",\n          \"@type\": \"@id\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Media\": {\n      \"@id\": \"snap:Media\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"snap:mediaType\"\
  ,\n        \"mediaStatus\": \"snap:mediaStatus\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ConversionEvent\": {\n      \"@id\": \"snap:ConversionEvent\",\n      \"@context\": {\n        \"eventName\": \"snap:eventName\",\n        \"eventTime\": {\n          \"@id\": \"snap:eventTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventSourceUrl\": {\n          \"@id\": \"snap:eventSourceUrl\",\n          \"@type\": \"@id\"\n        },\n        \"actionSource\": \"snap:actionSource\",\n        \"currency\": \"schema:currency\",\n        \"price\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"AudienceSegment\": {\n      \"@id\": \"snap:AudienceSegment\",\n      \"@context\": {\n       \
  \ \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"snap:status\",\n        \"sourceType\": \"snap:sourceType\",\n        \"approximateNumberUsers\": {\n          \"@id\": \"snap:approximateNumberUsers\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"snap:UserProfile\",\n      \"@context\": {\n        \"externalId\": \"snap:externalId\",\n        \"displayName\": \"schema:name\",\n        \"bitmojiAvatar\": {\n          \"@id\": \"snap:bitmojiAvatar\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/snapchat/refs/heads/main/json-ld/snapchat-context.jsonld
tags:
- Advertising
- AR
- Augmented Reality
- Marketing
- Messaging
- Social Media
- JSON-LD
- Linked Data
- Semantic Web
---
