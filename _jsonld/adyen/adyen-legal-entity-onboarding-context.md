---
class_count: 6
classes:
- OnboardingLinkInfo
- OnboardingLink
- OnboardingTheme
- OnboardingThemes
- url
- description
context_file: json-ld/adyen-legal-entity-onboarding-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-onboarding-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Onboarding from Adyen.
layout: jsonld
name: Adyen Legal Entity Onboarding Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: locale
  type: string
- container: ''
  name: redirectUrl
  type: string
- container: ''
  name: settings
  type: reference
- container: ''
  name: themeId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: next
  type: string
- container: ''
  name: previous
  type: string
- container: set
  name: themes
  type: string
property_count: 11
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-onboarding-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OnboardingLinkInfo\": \"adyen:OnboardingLinkInfo\",\n    \"OnboardingLink\": \"adyen:OnboardingLink\",\n    \"OnboardingTheme\": \"adyen:OnboardingTheme\",\n    \"OnboardingThemes\": \"adyen:OnboardingThemes\",\n    \"locale\": {\n      \"@id\": \"adyen:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"adyen:redirectUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"settings\": {\n      \"@id\": \"adyen:settings\",\n      \"@type\": \"@id\"\n    },\n    \"themeId\": {\n      \"@id\": \"adyen:themeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"createdAt\": {\n      \"@id\": \"adyen:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\"\
  : \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"adyen:properties\",\n      \"@type\": \"@id\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"adyen:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"next\": {\n      \"@id\": \"adyen:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previous\": {\n      \"@id\": \"adyen:previous\",\n      \"@type\": \"xsd:string\"\n    },\n    \"themes\": {\n      \"@id\": \"adyen:themes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-onboarding-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
