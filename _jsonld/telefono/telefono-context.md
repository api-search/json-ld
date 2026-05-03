---
api_specs:
- filename: telefono-validation-openapi.yml
  format: yaml
  label: Telefono Phone Validation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-validation-openapi.yml
- filename: telefono-carrier-openapi.yml
  format: yaml
  label: Telefono Carrier Lookup API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-carrier-openapi.yml
- filename: telefono-format-openapi.yml
  format: yaml
  label: Telefono Number Formatting API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/openapi/telefono-format-openapi.yml
class_count: 4
classes:
- ValidationResult
- CarrierResult
- FormatResult
- PhoneNumber
context_file: json-ld/telefono-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/json-ld/telefono-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telefono from Telefono.
layout: jsonld
name: Telefono Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: telefono
  uri: https://developers.telefono.com/schema/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: number
  type: string
- container: ''
  name: valid
  type: boolean
- container: ''
  name: number_type
  type: string
- container: ''
  name: e164_format
  type: string
- container: ''
  name: national_format
  type: string
- container: ''
  name: international_format
  type: string
- container: ''
  name: country_code
  type: string
- container: ''
  name: country_name
  type: string
- container: ''
  name: carrier
  type: string
- container: ''
  name: carrier_name
  type: string
- container: ''
  name: mcc
  type: string
- container: ''
  name: mnc
  type: string
- container: ''
  name: network_type
  type: string
- container: ''
  name: is_virtual
  type: boolean
- container: ''
  name: is_ported
  type: boolean
- container: ''
  name: is_reachable
  type: string
- container: ''
  name: calling_code
  type: integer
- container: ''
  name: roaming
  type: boolean
property_count: 18
provider_name: Telefono
provider_slug: telefono
slug: telefono-context
source_filename: telefono-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"telefono\": \"https://developers.telefono.com/schema/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ValidationResult\": \"telefono:ValidationResult\",\n    \"CarrierResult\": \"telefono:CarrierResult\",\n    \"FormatResult\": \"telefono:FormatResult\",\n    \"PhoneNumber\": \"schema:ContactPoint\",\n\n    \"number\": {\n      \"@id\": \"schema:telephone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valid\": {\n      \"@id\": \"telefono:isValid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"number_type\": {\n      \"@id\": \"telefono:numberType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"e164_format\": {\n      \"@id\": \"telefono:e164Format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"national_format\": {\n      \"@id\": \"telefono:nationalFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"international_format\": {\n      \"@id\": \"\
  telefono:internationalFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_code\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_name\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier\": {\n      \"@id\": \"telefono:carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"carrier_name\": {\n      \"@id\": \"telefono:carrierName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcc\": {\n      \"@id\": \"telefono:mobileCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mnc\": {\n      \"@id\": \"telefono:mobileNetworkCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network_type\": {\n      \"@id\": \"telefono:networkType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_virtual\": {\n      \"@id\": \"telefono:isVirtual\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_ported\": {\n      \"@id\": \"telefono:isPorted\",\n      \"@type\":\
  \ \"xsd:boolean\"\n    },\n    \"is_reachable\": {\n      \"@id\": \"telefono:isReachable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"calling_code\": {\n      \"@id\": \"telefono:callingCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"roaming\": {\n      \"@id\": \"telefono:isRoaming\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telefono/refs/heads/main/json-ld/telefono-context.jsonld
tags:
- Carrier Lookup
- Data Enrichment
- Fraud Prevention
- Number Intelligence
- Number Verification
- Phone Lookup
- Phone Validation
- Telecommunications
- JSON-LD
- Linked Data
- Semantic Web
---
