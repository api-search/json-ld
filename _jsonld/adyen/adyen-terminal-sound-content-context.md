---
class_count: 1
classes:
- SoundContent
context_file: json-ld/adyen-terminal-sound-content-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sound-content-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Sound Content from Adyen.
layout: jsonld
name: Adyen Terminal Sound Content Context
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
  name: SoundFormat
  type: string
- container: ''
  name: Language
  type: string
- container: ''
  name: ReferenceID
  type: string
- container: ''
  name: Text
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-sound-content-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SoundContent\": \"adyen:SoundContent\",\n    \"SoundFormat\": {\n      \"@id\": \"adyen:SoundFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Language\": {\n      \"@id\": \"adyen:Language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReferenceID\": {\n      \"@id\": \"adyen:ReferenceID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Text\": {\n      \"@id\": \"adyen:Text\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-sound-content-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
