---
class_count: 2
classes:
- InstallAndroidAppDetails
- InstallAndroidCertificateDetails
context_file: json-ld/adyen-management-install-android-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-install-android-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Install Android from Adyen.
layout: jsonld
name: Adyen Management Install Android Context
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
  name: appId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: certificateId
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-install-android-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InstallAndroidAppDetails\": \"adyen:InstallAndroidAppDetails\",\n    \"InstallAndroidCertificateDetails\": \"adyen:InstallAndroidCertificateDetails\",\n    \"appId\": {\n      \"@id\": \"adyen:appId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateId\": {\n      \"@id\": \"adyen:certificateId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-install-android-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
