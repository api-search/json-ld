---
class_count: 3
classes:
- AceHardwareAffiliateReferral
- AceHardwareEdiPurchaseOrder
- description
context_file: json-ld/ace-hardware-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ace-hardware/refs/heads/main/json-ld/ace-hardware-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ace Hardware from Ace Hardware.
layout: jsonld
name: Ace Hardware Context
namespaces:
- prefix: ace
  uri: https://www.acehardware.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: aceItemNumber
  type: string
- container: ''
  name: affiliateId
  type: string
- container: ''
  name: affiliateName
  type: string
- container: ''
  name: clickDate
  type: dateTime
- container: ''
  name: commissionAmount
  type: decimal
- container: ''
  name: commissionRate
  type: decimal
- container: ''
  name: conversionDate
  type: dateTime
- container: ''
  name: currency
  type: string
- container: ''
  name: destinationUrl
  type: reference
- container: ''
  name: extendedCost
  type: decimal
- container: set
  name: lineItems
  type: string
- container: ''
  name: lineNumber
  type: integer
- container: ''
  name: orderDate
  type: date
- container: ''
  name: orderId
  type: string
- container: ''
  name: orderValue
  type: decimal
- container: ''
  name: poNumber
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: referralId
  type: string
- container: ''
  name: referralUrl
  type: reference
- container: ''
  name: shipByDate
  type: date
- container: ''
  name: shipToAddress
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: unitCost
  type: decimal
- container: ''
  name: upc
  type: string
- container: ''
  name: vendorId
  type: string
- container: ''
  name: vendorName
  type: string
- container: ''
  name: vendorSku
  type: string
property_count: 28
provider_name: Ace Hardware
provider_slug: ace-hardware
slug: ace-hardware-context
source_filename: ace-hardware-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ace\": \"https://www.acehardware.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AceHardwareAffiliateReferral\": \"ace:AceHardwareAffiliateReferral\",\n    \"AceHardwareEdiPurchaseOrder\": \"ace:AceHardwareEdiPurchaseOrder\",\n    \"aceItemNumber\": {\n      \"@id\": \"ace:aceItemNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affiliateId\": {\n      \"@id\": \"ace:affiliateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affiliateName\": {\n      \"@id\": \"ace:affiliateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clickDate\": {\n      \"@id\": \"ace:clickDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"commissionAmount\": {\n      \"@id\": \"ace:commissionAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"commissionRate\": {\n      \"@id\": \"ace:commissionRate\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"conversionDate\": {\n      \"@id\": \"ace:conversionDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currency\": {\n      \"@id\": \"ace:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"destinationUrl\": {\n      \"@id\": \"ace:destinationUrl\",\n      \"@type\": \"@id\"\n    },\n    \"extendedCost\": {\n      \"@id\": \"ace:extendedCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lineItems\": {\n      \"@id\": \"ace:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineNumber\": {\n      \"@id\": \"ace:lineNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"orderDate\": {\n      \"@id\": \"ace:orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"orderId\": {\n      \"@id\": \"ace:orderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderValue\": {\n      \"@id\": \"ace:orderValue\",\n      \"@type\"\
  : \"xsd:decimal\"\n    },\n    \"poNumber\": {\n      \"@id\": \"ace:poNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"ace:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"referralId\": {\n      \"@id\": \"ace:referralId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referralUrl\": {\n      \"@id\": \"ace:referralUrl\",\n      \"@type\": \"@id\"\n    },\n    \"shipByDate\": {\n      \"@id\": \"ace:shipByDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"shipToAddress\": {\n      \"@id\": \"ace:shipToAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ace:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"ace:totalAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unitCost\": {\n      \"@id\": \"ace:unitCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"upc\": {\n      \"@id\": \"ace:upc\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"vendorId\": {\n      \"@id\": \"ace:vendorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorName\": {\n      \"@id\": \"ace:vendorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorSku\": {\n      \"@id\": \"ace:vendorSku\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ace-hardware/refs/heads/main/json-ld/ace-hardware-context.jsonld
tags:
- Retail
- Hardware
- Home Improvement
- Tools
- Paint
- Cooperative
- EDI
- Affiliate
- JSON-LD
- Linked Data
- Semantic Web
---
