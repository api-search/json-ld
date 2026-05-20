---
api_specs:
- filename: ifs-cloud-erp-openapi.yml
  format: yaml
  label: IFS Cloud ERP API
  slug: ifs-cloud-erp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ifs/refs/heads/main/openapi/ifs-cloud-erp-openapi.yml
class_count: 19
classes:
- WoNo
- OrderNo
- Description
- WoStatus
- WoType
- Priority
- MchCode
- MchName
- ContractId
- OrgCode
- EmployeeId
- VoucherNo
- CurrencyCode
- Account
- VendorNo
- VendorName
- OrderStatus
- PartNo
- UnitMeas
context_file: json-ld/ifs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ifs/refs/heads/main/json-ld/ifs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ifs from IFS.
layout: jsonld
name: Ifs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: WorkOrder
  type: reference
- container: ''
  name: PurchaseOrder
  type: reference
- container: ''
  name: Voucher
  type: reference
- container: ''
  name: Part
  type: reference
- container: ''
  name: EarlyStart
  type: date
- container: ''
  name: EarlyFinish
  type: date
- container: ''
  name: ActualStart
  type: dateTime
- container: ''
  name: ActualFinish
  type: dateTime
- container: ''
  name: CostAmount
  type: decimal
- container: ''
  name: VoucherDate
  type: date
- container: ''
  name: Amount
  type: decimal
- container: ''
  name: AccountingYear
  type: string
- container: ''
  name: OrderDate
  type: date
- container: ''
  name: TotalOrderAmount
  type: decimal
property_count: 14
provider_name: IFS
provider_slug: ifs
slug: ifs-context
source_filename: ifs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"WorkOrder\": {\n      \"@id\": \"schema:Action\",\n      \"@type\": \"@id\"\n    },\n    \"PurchaseOrder\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"Voucher\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"@id\"\n    },\n    \"Part\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n\n    \"WoNo\": \"schema:identifier\",\n    \"OrderNo\": \"schema:identifier\",\n    \"Description\": \"schema:description\",\n    \"WoStatus\": \"schema:actionStatus\",\n    \"WoType\": \"schema:additionalType\",\n    \"Priority\": \"schema:priority\",\n    \"EarlyStart\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"EarlyFinish\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\
  \n    },\n    \"ActualStart\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ActualFinish\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CostAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MchCode\": \"schema:identifier\",\n    \"MchName\": \"schema:name\",\n    \"ContractId\": \"schema:identifier\",\n    \"OrgCode\": \"schema:identifier\",\n    \"EmployeeId\": \"schema:identifier\",\n\n    \"VoucherNo\": \"schema:identifier\",\n    \"VoucherDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"Amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CurrencyCode\": \"schema:priceCurrency\",\n    \"Account\": \"schema:identifier\",\n    \"AccountingYear\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"VendorNo\": \"schema:identifier\"\
  ,\n    \"VendorName\": \"schema:name\",\n    \"OrderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"OrderStatus\": \"schema:orderStatus\",\n    \"TotalOrderAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"PartNo\": \"schema:productID\",\n    \"UnitMeas\": \"schema:unitCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ifs/refs/heads/main/json-ld/ifs-context.jsonld
tags:
- ERP
- Field Service
- Asset Management
- Manufacturing
- Energy
- Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
