---
api_specs:
- filename: waste-management-customer-api-openapi.yml
  format: yaml
  label: Waste Management Customer API
  slug: waste-management-customer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/waste-management/refs/heads/main/openapi/waste-management-customer-api-openapi.yml
class_count: 10
classes:
- Customer
- Invoice
- Service
- ServiceSchedule
- ServiceETA
- Contact
- Address
- ServiceMaterial
- ServiceEquipment
- InvoiceFee
context_file: json-ld/waste-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/waste-management/refs/heads/main/json-ld/waste-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Waste Management from Waste Management.
layout: jsonld
name: Waste Management Context
namespaces:
- prefix: wm
  uri: https://api.wm.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: customerId
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: balanceDue
  type: decimal
- container: ''
  name: serviceId
  type: string
- container: ''
  name: lineOfBusiness
  type: string
- container: ''
  name: occurrenceFrequency
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: invoiceId
  type: string
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: monthlyBaseCost
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: materialCode
  type: string
- container: ''
  name: materialName
  type: string
- container: ''
  name: estimatedArrivalStart
  type: time
- container: ''
  name: estimatedArrivalEnd
  type: time
- container: ''
  name: feeType
  type: string
- container: ''
  name: paperlessBilling
  type: boolean
- container: ''
  name: autoPayEnrolled
  type: boolean
property_count: 21
provider_name: Waste Management
provider_slug: waste-management
slug: waste-management-context
source_filename: waste-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wm\": \"https://api.wm.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Customer\": \"schema:Customer\",\n    \"Invoice\": \"schema:Invoice\",\n    \"Service\": \"wm:WasteCollectionService\",\n    \"ServiceSchedule\": \"wm:ServiceSchedule\",\n    \"ServiceETA\": \"wm:ServiceETA\",\n    \"Contact\": \"schema:ContactPoint\",\n    \"Address\": \"schema:PostalAddress\",\n    \"ServiceMaterial\": \"wm:ServiceMaterial\",\n    \"ServiceEquipment\": \"wm:ServiceEquipment\",\n    \"InvoiceFee\": \"wm:InvoiceFee\",\n\n    \"customerId\": {\n      \"@id\": \"wm:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balanceDue\": {\n      \"@id\": \"wm:balanceDue\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"serviceId\": {\n      \"@id\": \"wm:serviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineOfBusiness\": {\n      \"@id\": \"wm:lineOfBusiness\",\n      \"@type\": \"xsd:string\"\n    },\n    \"occurrenceFrequency\": {\n      \"@id\": \"wm:occurrenceFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"status\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"monthlyBaseCost\"\
  : {\n      \"@id\": \"wm:monthlyBaseCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"materialCode\": {\n      \"@id\": \"wm:materialCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"materialName\": {\n      \"@id\": \"wm:materialName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedArrivalStart\": {\n      \"@id\": \"wm:estimatedArrivalStart\",\n      \"@type\": \"xsd:time\"\n    },\n    \"estimatedArrivalEnd\": {\n      \"@id\": \"wm:estimatedArrivalEnd\",\n      \"@type\": \"xsd:time\"\n    },\n    \"feeType\": {\n      \"@id\": \"wm:feeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paperlessBilling\": {\n      \"@id\": \"wm:paperlessBilling\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"autoPayEnrolled\": {\n      \"@id\": \"wm:autoPayEnrolled\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/waste-management/refs/heads/main/json-ld/waste-management-context.jsonld
tags:
- Environmental Services
- Fortune 500
- Recycling
- Solid Waste
- Sustainability
- Waste Management
- JSON-LD
- Linked Data
- Semantic Web
---
