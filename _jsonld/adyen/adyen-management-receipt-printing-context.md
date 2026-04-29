---
class_count: 1
classes:
- ReceiptPrinting
context_file: json-ld/adyen-management-receipt-printing-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-receipt-printing-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Receipt Printing from Adyen.
layout: jsonld
name: Adyen Management Receipt Printing Context
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
  name: merchantApproved
  type: boolean
- container: ''
  name: merchantCancelled
  type: boolean
- container: ''
  name: merchantCaptureApproved
  type: boolean
- container: ''
  name: merchantCaptureRefused
  type: boolean
- container: ''
  name: merchantRefundApproved
  type: boolean
- container: ''
  name: merchantRefundRefused
  type: boolean
- container: ''
  name: merchantRefused
  type: boolean
- container: ''
  name: merchantVoid
  type: boolean
- container: ''
  name: shopperApproved
  type: boolean
- container: ''
  name: shopperCancelled
  type: boolean
- container: ''
  name: shopperCaptureApproved
  type: boolean
- container: ''
  name: shopperCaptureRefused
  type: boolean
- container: ''
  name: shopperRefundApproved
  type: boolean
- container: ''
  name: shopperRefundRefused
  type: boolean
- container: ''
  name: shopperRefused
  type: boolean
- container: ''
  name: shopperVoid
  type: boolean
property_count: 16
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-receipt-printing-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReceiptPrinting\": \"adyen:ReceiptPrinting\",\n    \"merchantApproved\": {\n      \"@id\": \"adyen:merchantApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantCancelled\": {\n      \"@id\": \"adyen:merchantCancelled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantCaptureApproved\": {\n      \"@id\": \"adyen:merchantCaptureApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantCaptureRefused\": {\n      \"@id\": \"adyen:merchantCaptureRefused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantRefundApproved\": {\n      \"@id\": \"adyen:merchantRefundApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantRefundRefused\": {\n      \"@id\": \"adyen:merchantRefundRefused\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantRefused\": {\n      \"@id\": \"adyen:merchantRefused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"merchantVoid\": {\n      \"@id\": \"adyen:merchantVoid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperApproved\": {\n      \"@id\": \"adyen:shopperApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperCancelled\": {\n      \"@id\": \"adyen:shopperCancelled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperCaptureApproved\": {\n      \"@id\": \"adyen:shopperCaptureApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperCaptureRefused\": {\n      \"@id\": \"adyen:shopperCaptureRefused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperRefundApproved\": {\n      \"@id\": \"adyen:shopperRefundApproved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperRefundRefused\": {\n      \"@id\": \"adyen:shopperRefundRefused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"\
  shopperRefused\": {\n      \"@id\": \"adyen:shopperRefused\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shopperVoid\": {\n      \"@id\": \"adyen:shopperVoid\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-receipt-printing-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
