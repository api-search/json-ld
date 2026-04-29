---
class_count: 4
classes:
- GetOnboardingUrlRequest
- GetOnboardingUrlResponse
- GetPciUrlRequest
- GetPciUrlResponse
context_file: json-ld/adyen-hosted-onboarding-get-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-hosted-onboarding-get-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Hosted Onboarding Get from Adyen.
layout: jsonld
name: Adyen Hosted Onboarding Get Context
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
  name: accountHolderCode
  type: string
- container: ''
  name: collectInformation
  type: string
- container: ''
  name: editMode
  type: boolean
- container: ''
  name: mobileOAuthCallbackUrl
  type: string
- container: ''
  name: platformName
  type: string
- container: ''
  name: returnUrl
  type: string
- container: ''
  name: shopperLocale
  type: string
- container: ''
  name: showPages
  type: string
- container: set
  name: invalidFields
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: redirectUrl
  type: string
- container: ''
  name: resultCode
  type: string
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-hosted-onboarding-get-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GetOnboardingUrlRequest\": \"adyen:GetOnboardingUrlRequest\",\n    \"GetOnboardingUrlResponse\": \"adyen:GetOnboardingUrlResponse\",\n    \"GetPciUrlRequest\": \"adyen:GetPciUrlRequest\",\n    \"GetPciUrlResponse\": \"adyen:GetPciUrlResponse\",\n    \"accountHolderCode\": {\n      \"@id\": \"adyen:accountHolderCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectInformation\": {\n      \"@id\": \"adyen:collectInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"editMode\": {\n      \"@id\": \"adyen:editMode\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mobileOAuthCallbackUrl\": {\n      \"@id\": \"adyen:mobileOAuthCallbackUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platformName\": {\n      \"@id\"\
  : \"adyen:platformName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"returnUrl\": {\n      \"@id\": \"adyen:returnUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperLocale\": {\n      \"@id\": \"adyen:shopperLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showPages\": {\n      \"@id\": \"adyen:showPages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invalidFields\": {\n      \"@id\": \"adyen:invalidFields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"redirectUrl\": {\n      \"@id\": \"adyen:redirectUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultCode\": {\n      \"@id\": \"adyen:resultCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-hosted-onboarding-get-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
