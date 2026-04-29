---
class_count: 2
classes:
- ShippingLocation
- name
context_file: json-ld/adyen-management-shipping-location-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-shipping-location-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Shipping Location from Adyen.
layout: jsonld
name: Adyen Management Shipping Location Context
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
  name: address
  type: string
- container: ''
  name: contact
  type: string
- container: ''
  name: id
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-shipping-location-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ShippingLocation\": \"adyen:ShippingLocation\",\n    \"address\": {\n      \"@id\": \"adyen:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contact\": {\n      \"@id\": \"adyen:contact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-shipping-location-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
