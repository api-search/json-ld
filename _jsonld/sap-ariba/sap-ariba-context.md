---
api_specs:
- filename: sap-ariba-procurement-api.yml
  format: yaml
  label: SAP Ariba Procurement API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/openapi/sap-ariba-procurement-api.yml
- filename: openapi.json
  format: json
  label: SAP Ariba Sourcing API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/sourcing/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Supplier Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/supplier/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Contract Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/contracts/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Analytical Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/analytics/openapi.json
- filename: openapi.json
  format: json
  label: SAP Ariba Invoice Management API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.ariba.com/api/invoices/openapi.json
class_count: 0
classes: []
context_file: json-ld/sap-ariba-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/json-ld/sap-ariba-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Ariba from SAP Ariba.
layout: jsonld
name: Sap Ariba Context
namespaces:
- prefix: ariba
  uri: https://openapi.ariba.com/api/procurement/v1/vocab#
- prefix: sap
  uri: https://api.sap.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: unspsc
  uri: https://www.unspsc.org/code/
properties:
- container: ''
  name: PurchaseOrder
  type: ''
- container: ''
  name: PurchaseOrderLineItem
  type: ''
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: Supplier
  type: ''
- container: ''
  name: Money
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: CommodityCode
  type: ''
- container: ''
  name: AccountingInfo
  type: ''
- container: ''
  name: PaymentTerms
  type: ''
- container: ''
  name: TaxDetail
  type: ''
- container: ''
  name: UnitOfMeasure
  type: ''
- container: ''
  name: ContactInfo
  type: ''
- container: ''
  name: Requisition
  type: ''
- container: ''
  name: Receipt
  type: ''
property_count: 14
provider_name: SAP Ariba
provider_slug: sap-ariba
slug: sap-ariba-context
source_filename: sap-ariba-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"ariba\": \"https://openapi.ariba.com/api/procurement/v1/vocab#\",\n    \"sap\": \"https://api.sap.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"unspsc\": \"https://www.unspsc.org/code/\",\n\n    \"PurchaseOrder\": {\n      \"@id\": \"ariba:PurchaseOrder\",\n      \"@context\": {\n        \"orderId\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"erpPONumber\": {\n          \"@id\": \"ariba:erpPONumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versionNumber\": {\n          \"@id\": \"ariba:versionNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"\
  @type\": \"xsd:dateTime\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orderMethodCategory\": {\n          \"@id\": \"ariba:orderMethodCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"supplier\": {\n          \"@id\": \"ariba:supplier\",\n          \"@type\": \"@id\"\n        },\n        \"buyer\": {\n          \"@id\": \"ariba:buyer\",\n          \"@type\": \"@id\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"@id\"\n        },\n        \"taxAmount\": {\n          \"@id\": \"ariba:taxAmount\",\n          \"@type\": \"@id\"\n        },\n        \"shippingAmount\": {\n          \"@id\": \"ariba:shippingAmount\",\n          \"@type\": \"@id\"\n        },\n        \"paymentTerms\": {\n          \"\
  @id\": \"ariba:paymentTerms\",\n          \"@type\": \"@id\"\n        },\n        \"purchaseOrg\": {\n          \"@id\": \"ariba:purchaseOrg\",\n          \"@type\": \"xsd:string\"\n        },\n        \"purchaseGroup\": {\n          \"@id\": \"ariba:purchaseGroup\",\n          \"@type\": \"xsd:string\"\n        },\n        \"companyCode\": {\n          \"@id\": \"ariba:companyCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shipTo\": {\n          \"@id\": \"ariba:shipTo\",\n          \"@type\": \"@id\"\n        },\n        \"billTo\": {\n          \"@id\": \"ariba:billTo\",\n          \"@type\": \"@id\"\n        },\n        \"lineItems\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"requisitionId\": {\n          \"@id\": \"ariba:requisitionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contractId\": {\n          \"@id\": \"ariba:contractId\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"comments\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closedDate\": {\n          \"@id\": \"ariba:closedDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PurchaseOrderLineItem\": {\n      \"@id\": \"ariba:PurchaseOrderLineItem\",\n      \"@context\": {\n        \"numberOnPO\": {\n          \"@id\": \"ariba:numberOnPO\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:orderQuantity\",\n          \"@type\": \"xsd:double\"\n        },\n\
  \        \"unitPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"@id\"\n        },\n        \"unitOfMeasure\": {\n          \"@id\": \"gr:hasUnitOfMeasurement\",\n          \"@type\": \"@id\"\n        },\n        \"netAmount\": {\n          \"@id\": \"ariba:netAmount\",\n          \"@type\": \"@id\"\n        },\n        \"commodityCode\": {\n          \"@id\": \"ariba:commodityCode\",\n          \"@type\": \"@id\"\n        },\n        \"buyerPartNumber\": {\n          \"@id\": \"ariba:buyerPartNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"supplierPartNumber\": {\n          \"@id\": \"schema:sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manufacturerPartId\": {\n          \"@id\": \"schema:mpn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manufacturerName\": {\n          \"@id\": \"schema:manufacturer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"itemCategory\": {\n          \"@id\": \"\
  ariba:itemCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountCategory\": {\n          \"@id\": \"ariba:accountCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"needByDate\": {\n          \"@id\": \"ariba:needByDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"shipTo\": {\n          \"@id\": \"ariba:shipTo\",\n          \"@type\": \"@id\"\n        },\n        \"accountings\": {\n          \"@id\": \"ariba:accountings\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"receivingType\": {\n          \"@id\": \"ariba:receivingType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"taxCode\": {\n          \"@id\": \"ariba:taxCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceStartDate\": {\n          \"@id\": \"ariba:serviceStartDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"serviceEndDate\": {\n          \"@id\": \"ariba:serviceEndDate\"\
  ,\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"Invoice\": {\n      \"@id\": \"ariba:Invoice\",\n      \"@context\": {\n        \"invoiceId\": {\n          \"@id\": \"schema:confirmationNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceNumber\": {\n          \"@id\": \"ariba:invoiceNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": {\n          \"@id\": \"schema:paymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceType\": {\n          \"@id\": \"ariba:invoiceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"supplier\": {\n          \"@id\": \"ariba:supplier\",\n          \"@type\": \"@id\"\n        },\n        \"buyer\": {\n          \"@id\": \"ariba:buyer\",\n          \"@type\": \"@id\"\n        },\n        \"purchaseOrderReference\":\
  \ {\n          \"@id\": \"schema:referencesOrder\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subtotalAmount\": {\n          \"@id\": \"ariba:subtotalAmount\",\n          \"@type\": \"@id\"\n        },\n        \"taxAmount\": {\n          \"@id\": \"ariba:taxAmount\",\n          \"@type\": \"@id\"\n        },\n        \"shippingAmount\": {\n          \"@id\": \"ariba:shippingAmount\",\n          \"@type\": \"@id\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"@id\"\n        },\n        \"paymentTerms\": {\n          \"@id\": \"ariba:paymentTerms\",\n          \"@type\": \"@id\"\n        },\n        \"dueDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"remitTo\": {\n          \"@id\": \"ariba:remitTo\",\n          \"@type\": \"\
  @id\"\n        },\n        \"lineItems\": {\n          \"@id\": \"ariba:invoiceLineItems\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"approvalDate\": {\n          \"@id\": \"ariba:approvalDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"paymentDate\": {\n          \"@id\": \"ariba:paymentDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentReference\": {\n          \"@id\": \"ariba:paymentReference\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Supplier\": {\n      \"@id\": \"ariba:Supplier\",\n      \"@context\": {\n        \"supplierId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"name\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"doingBusinessAs\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dunsNumber\": {\n          \"@id\": \"schema:duns\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxId\": {\n          \"@id\": \"schema:taxID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"yearEstablished\": {\n          \"@id\": \"schema:foundingDate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberOfEmployees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:string\"\n        },\n        \"annualRevenue\": {\n          \"@id\": \"ariba:annualRevenue\",\n          \"@type\": \"@id\"\n        },\n        \"qualificationStatus\": {\n          \"@id\": \"ariba:qualificationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"registrationStatus\"\
  : {\n          \"@id\": \"ariba:registrationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        },\n        \"primaryContact\": {\n          \"@id\": \"schema:contactPoint\",\n          \"@type\": \"@id\"\n        },\n        \"commodityCodes\": {\n          \"@id\": \"ariba:commodityCodes\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"certifications\": {\n          \"@id\": \"ariba:certifications\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"diversityClassifications\": {\n          \"@id\": \"ariba:diversityClassifications\",\n          \"@container\": \"@set\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n   \
  \     },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Money\": {\n      \"@id\": \"ariba:Money\",\n      \"@context\": {\n        \"amount\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lines\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CommodityCode\": {\n      \"@id\": \"ariba:CommodityCode\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"schema:codeValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domain\": {\n          \"@id\": \"schema:codingSystem\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AccountingInfo\": {\n      \"@id\": \"ariba:AccountingInfo\",\n      \"@context\": {\n        \"costCenter\": {\n          \"@id\": \"ariba:costCenter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"generalLedger\": {\n          \"@id\": \"ariba:generalLedger\",\n          \"@type\": \"xsd:string\"\n        },\n        \"asset\": {\n          \"@id\": \"ariba:asset\",\n          \"@type\": \"xsd:string\"\n        },\n        \"internalOrder\": {\n          \"@id\": \"ariba:internalOrder\",\n          \"@type\": \"xsd:string\"\n        },\n        \"wbsElement\": {\n          \"@id\": \"ariba:wbsElement\",\n          \"@type\": \"xsd:string\"\n        },\n        \"amount\": {\n          \"@id\": \"ariba:amount\",\n          \"@type\": \"@id\"\n        },\n        \"percentage\": {\n          \"@id\": \"ariba:percentage\",\n          \"@type\": \"xsd:double\"\n        },\n        \"accountCategory\"\
  : {\n          \"@id\": \"ariba:accountCategory\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PaymentTerms\": {\n      \"@id\": \"ariba:PaymentTerms\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"schema:codeValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"netDays\": {\n          \"@id\": \"ariba:netDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"discountPercent\": {\n          \"@id\": \"ariba:discountPercent\",\n          \"@type\": \"xsd:double\"\n        },\n        \"discountDays\": {\n          \"@id\": \"ariba:discountDays\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"TaxDetail\": {\n      \"@id\": \"ariba:TaxDetail\",\n      \"@context\": {\n        \"taxCode\": {\n          \"@id\": \"ariba:taxCode\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"taxCategory\": {\n          \"@id\": \"ariba:taxCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxRate\": {\n          \"@id\": \"ariba:taxRate\",\n          \"@type\": \"xsd:double\"\n        },\n        \"taxAmount\": {\n          \"@id\": \"ariba:taxAmount\",\n          \"@type\": \"@id\"\n        },\n        \"taxableAmount\": {\n          \"@id\": \"ariba:taxableAmount\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"UnitOfMeasure\": {\n      \"@id\": \"ariba:UnitOfMeasure\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"schema:unitCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:unitText\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ContactInfo\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phone\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fax\": {\n          \"@id\": \"schema:faxNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Requisition\": {\n      \"@id\": \"ariba:Requisition\",\n      \"@context\": {\n        \"requisitionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestor\": {\n          \"@id\": \"ariba:requestor\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"requestorName\": {\n          \"@id\": \"ariba:requestorName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"needByDate\": {\n          \"@id\": \"ariba:needByDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lineItems\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"@id\"\n        },\n        \"purchaseOrderIds\": {\n          \"@id\": \"ariba:purchaseOrderIds\",\n          \"@container\": \"@set\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"\
  xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Receipt\": {\n      \"@id\": \"ariba:Receipt\",\n      \"@context\": {\n        \"receiptId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"purchaseOrderId\": {\n          \"@id\": \"schema:referencesOrder\",\n          \"@type\": \"xsd:string\"\n        },\n        \"receiptDate\": {\n          \"@id\": \"ariba:receiptDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"receiptType\": {\n          \"@id\": \"ariba:receiptType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineItems\": {\n          \"@id\": \"ariba:receiptLineItems\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"createdBy\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-ariba/refs/heads/main/json-ld/sap-ariba-context.jsonld
tags:
- B2B
- Contract Management
- Procurement
- Sourcing
- Spend Analysis
- Supplier Management
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
