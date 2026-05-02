---
api_specs:
- filename: hmrc-vat-mtd-openapi.yml
  format: yaml
  label: HMRC VAT (Making Tax Digital) API
  slug: hmrc-vat-mtd-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/openapi/hmrc-vat-mtd-openapi.yml
class_count: 4
classes:
- periodKey
- finalised
- formBundleNumber
- status
context_file: json-ld/hmrc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/json-ld/hmrc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Hmrc from HMRC UK Tax Authority.
layout: jsonld
name: Hmrc Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gov
  uri: https://www.gov.uk/api-schema/
- prefix: tax
  uri: https://www.w3.org/ns/oa#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: VatReturn
  type: reference
- container: ''
  name: VatObligation
  type: reference
- container: ''
  name: TaxLiability
  type: reference
- container: ''
  name: vatDueSales
  type: decimal
- container: ''
  name: vatDueAcquisitions
  type: decimal
- container: ''
  name: totalVatDue
  type: decimal
- container: ''
  name: vatReclaimedCurrPeriod
  type: decimal
- container: ''
  name: netVatDue
  type: decimal
- container: ''
  name: totalValueSalesExVAT
  type: decimal
- container: ''
  name: totalValuePurchasesExVAT
  type: decimal
- container: ''
  name: totalValueGoodsSuppliedExVAT
  type: decimal
- container: ''
  name: totalAcquisitionsExVAT
  type: decimal
- container: ''
  name: processingDate
  type: dateTime
- container: ''
  name: start
  type: date
- container: ''
  name: end
  type: date
- container: ''
  name: due
  type: date
- container: ''
  name: received
  type: date
- container: ''
  name: amount
  type: decimal
- container: ''
  name: originalAmount
  type: decimal
- container: ''
  name: outstandingAmount
  type: decimal
- container: ''
  name: vrn
  type: string
property_count: 21
provider_name: HMRC UK Tax Authority
provider_slug: hmrc
slug: hmrc-context
source_filename: hmrc-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gov\": \"https://www.gov.uk/api-schema/\",\n    \"tax\": \"https://www.w3.org/ns/oa#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"VatReturn\": {\n      \"@id\": \"schema:TaxForm\",\n      \"@type\": \"@id\"\n    },\n    \"VatObligation\": {\n      \"@id\": \"schema:Service\",\n      \"@type\": \"@id\"\n    },\n    \"TaxLiability\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"@id\"\n    },\n\n    \"periodKey\": \"schema:identifier\",\n    \"vatDueSales\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vatDueAcquisitions\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalVatDue\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vatReclaimedCurrPeriod\": {\n      \"@id\": \"schema:price\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"netVatDue\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalValueSalesExVAT\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalValuePurchasesExVAT\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalValueGoodsSuppliedExVAT\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalAcquisitionsExVAT\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"finalised\": \"schema:disambiguatingDescription\",\n    \"processingDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"formBundleNumber\": \"schema:identifier\",\n\n    \"start\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n\
  \    \"due\": {\n      \"@id\": \"schema:paymentDue\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": \"schema:orderStatus\",\n    \"received\": {\n      \"@id\": \"schema:dateReceived\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"originalAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"outstandingAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"vrn\": {\n      \"@id\": \"schema:taxID\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/hmrc/refs/heads/main/json-ld/hmrc-context.jsonld
tags:
- Government
- Making Tax Digital
- Regulatory
- Tax
- UK
- JSON-LD
- Linked Data
- Semantic Web
---
