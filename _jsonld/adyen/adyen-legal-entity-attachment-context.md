---
class_count: 1
classes:
- Attachment
context_file: json-ld/adyen-legal-entity-attachment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-attachment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Attachment from Adyen.
layout: jsonld
name: Adyen Legal Entity Attachment Context
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
  name: content
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: pageName
  type: string
- container: ''
  name: pageType
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-attachment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Attachment\": \"adyen:Attachment\",\n    \"content\": {\n      \"@id\": \"adyen:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"adyen:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"adyen:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageName\": {\n      \"@id\": \"adyen:pageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageType\": {\n      \"@id\": \"adyen:pageType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-attachment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
