---
api_specs:
- filename: trabex-trade-compliance-openapi.yml
  format: yaml
  label: Trabex Trade Compliance API
  slug: trade-compliance
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/openapi/trabex-trade-compliance-openapi.yml
class_count: 39
classes:
- Shipment
- shipmentId
- status
- screeningStatus
- aesStatus
- itn
- shipper
- consignee
- freightForwarder
- destinationCountry
- exportDate
- carrier
- trackingNumber
- referenceNumber
- lineItems
- Party
- name
- address
- city
- state
- country
- postalCode
- ExportLineItem
- description
- scheduleBNumber
- quantity
- unitOfMeasure
- valueUSD
- countryOfOrigin
- eccnNumber
- ScreeningResult
- riskLevel
- matches
- matchScore
- listName
- Company
- role
- AESFiling
- Document
context_file: json-ld/trabex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/json-ld/trabex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trabex from Trabex.
layout: jsonld
name: Trabex Context
namespaces:
- prefix: trabex
  uri: https://api-evangelist.com/context/trabex/
- prefix: customs
  uri: https://api-evangelist.com/context/customs/
properties: []
property_count: 0
provider_name: Trabex
provider_slug: trabex
slug: trabex-context
source_filename: trabex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"trabex\": \"https://api-evangelist.com/context/trabex/\",\n    \"customs\": \"https://api-evangelist.com/context/customs/\",\n    \"Shipment\": \"schema:DeliveryEvent\",\n    \"shipmentId\": \"schema:identifier\",\n    \"status\": \"trabex:complianceStatus\",\n    \"screeningStatus\": \"trabex:screeningStatus\",\n    \"aesStatus\": \"trabex:aesStatus\",\n    \"itn\": \"trabex:internalTransactionNumber\",\n    \"shipper\": \"schema:sender\",\n    \"consignee\": \"schema:recipient\",\n    \"freightForwarder\": \"trabex:freightForwarder\",\n    \"destinationCountry\": \"schema:addressCountry\",\n    \"exportDate\": \"schema:departureDate\",\n    \"carrier\": \"schema:provider\",\n    \"trackingNumber\": \"schema:trackingNumber\",\n    \"referenceNumber\": \"schema:referenceNumber\",\n    \"lineItems\": \"schema:orderedItem\",\n    \"Party\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"address\"\
  : \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"postalCode\": \"schema:postalCode\",\n    \"ExportLineItem\": \"customs:ExportLineItem\",\n    \"description\": \"schema:description\",\n    \"scheduleBNumber\": \"customs:scheduleBNumber\",\n    \"quantity\": \"schema:orderQuantity\",\n    \"unitOfMeasure\": \"customs:unitOfMeasure\",\n    \"valueUSD\": \"schema:price\",\n    \"countryOfOrigin\": \"customs:countryOfOrigin\",\n    \"eccnNumber\": \"customs:eccnNumber\",\n    \"ScreeningResult\": \"trabex:ScreeningResult\",\n    \"riskLevel\": \"trabex:riskLevel\",\n    \"matches\": \"trabex:screeningMatches\",\n    \"matchScore\": \"trabex:matchScore\",\n    \"listName\": \"trabex:listName\",\n    \"Company\": \"schema:Organization\",\n    \"role\": \"schema:roleName\",\n    \"AESFiling\": \"trabex:AESFiling\",\n    \"Document\": \"schema:DigitalDocument\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trabex/refs/heads/main/json-ld/trabex-context.jsonld
tags:
- Compliance
- Export Control
- Logistics
- Restricted Party Screening
- Shipment Management
- Trade Compliance
- JSON-LD
- Linked Data
- Semantic Web
---
