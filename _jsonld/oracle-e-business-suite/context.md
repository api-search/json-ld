---
class_count: 0
classes: []
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Oracle E-Business Suite.
layout: jsonld
name: context Context
namespaces:
- prefix: ebs
  uri: https://schema.oracle.com/ebs/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: org
  uri: http://www.w3.org/ns/org#
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
properties:
- container: ''
  name: PurchaseOrder
  type: ''
- container: ''
  name: PurchaseOrderLine
  type: ''
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: Employee
  type: ''
- container: ''
  name: Assignment
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Supplier
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: SalesOrder
  type: ''
- container: ''
  name: InventoryItem
  type: ''
- container: ''
  name: DiscreteJob
  type: ''
- container: ''
  name: TradingPartner
  type: ''
property_count: 12
provider_name: Oracle E-Business Suite
provider_slug: oracle-e-business-suite
slug: context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.oracle.com/ebs/\",\n    \"ebs\": \"https://schema.oracle.com/ebs/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"org\": \"http://www.w3.org/ns/org#\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"PurchaseOrder\": {\n      \"@id\": \"ebs:PurchaseOrder\",\n      \"@context\": {\n        \"poHeaderId\": {\n          \"@id\": \"ebs:poHeaderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"segment1\": {\n          \"@id\": \"ebs:purchaseOrderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"typeLookupCode\": {\n          \"@id\": \"ebs:purchaseOrderType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vendorId\": {\n          \"@id\"\
  : \"ebs:vendorId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vendorName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"authorizationStatus\": {\n          \"@id\": \"ebs:authorizationStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lines\": {\n          \"@id\": \"ebs:hasOrderLine\",\n      \
  \    \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"PurchaseOrderLine\": {\n      \"@id\": \"ebs:PurchaseOrderLine\",\n      \"@context\": {\n        \"poLineId\": {\n          \"@id\": \"ebs:poLineId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lineNum\": {\n          \"@id\": \"ebs:lineNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"itemDescription\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"schema:amount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unitPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unitMeasLookupCode\": {\n          \"@id\": \"ebs:unitOfMeasure\",\n          \"@type\": \"xsd:string\"\n        },\n        \"needByDate\": {\n          \"@id\": \"ebs:needByDate\",\n          \"@type\": \"xsd:date\"\n \
  \       }\n      }\n    },\n\n    \"Invoice\": {\n      \"@id\": \"ebs:Invoice\",\n      \"@context\": {\n        \"invoiceId\": {\n          \"@id\": \"ebs:invoiceId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"invoiceNum\": {\n          \"@id\": \"schema:confirmationNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"invoiceAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"invoiceCurrencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"invoiceType\": {\n          \"@id\": \"ebs:invoiceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vendorName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\"\
  : \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"approvalStatus\": {\n          \"@id\": \"ebs:approvalStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentStatusFlag\": {\n          \"@id\": \"ebs:paymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"amountPaid\": {\n          \"@id\": \"ebs:amountPaid\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lines\": {\n          \"@id\": \"ebs:hasInvoiceLine\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Employee\": {\n      \"@id\": \"ebs:Employee\",\n      \"@context\": {\n        \"personId\": {\n          \"@id\": \"ebs:personId\",\n      \
  \    \"@type\": \"xsd:integer\"\n        },\n        \"employeeNumber\": {\n          \"@id\": \"ebs:employeeNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:honorificPrefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"middleNames\": {\n          \"@id\": \"schema:additionalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastName\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fullName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailAddress\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"\
  nationality\": {\n          \"@id\": \"schema:nationality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hireDate\": {\n          \"@id\": \"ebs:hireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"effectiveStartDate\": {\n          \"@id\": \"ebs:effectiveStartDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"effectiveEndDate\": {\n          \"@id\": \"ebs:effectiveEndDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"assignment\": {\n          \"@id\": \"ebs:hasAssignment\",\n          \"@type\": \"@id\"\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"phones\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n\
  \        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Assignment\": {\n      \"@id\": \"ebs:Assignment\",\n      \"@context\": {\n        \"assignmentId\": {\n          \"@id\": \"ebs:assignmentId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"jobName\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"positionName\": {\n          \"@id\": \"ebs:positionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"organizationName\": {\n          \"@id\": \"schema:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"locationCode\": {\n          \"@id\": \"schema:workLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employmentCategory\": {\n          \"@id\": \"schema:employmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"normalHours\": {\n          \"\
  @id\": \"schema:hoursPerWeek\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"salary\": {\n          \"@id\": \"schema:baseSalary\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"ebs:Customer\",\n      \"@context\": {\n        \"partyId\": {\n          \"@id\": \"ebs:partyId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"partyNumber\": {\n          \"@id\": \"ebs:partyNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partyName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"partyType\": {\n          \"@id\": \"ebs:partyType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailAddress\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryPhoneNumber\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"dunsBNumber\": {\n          \"@id\": \"schema:duns\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxPayerIdentificationNumber\": {\n          \"@id\": \"schema:taxID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customerAccounts\": {\n          \"@id\": \"ebs:hasCustomerAccount\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"partySites\": {\n          \"@id\": \"ebs:hasPartySite\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"contactPoints\": {\n          \"@id\": \"ebs:hasContactPoint\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n     \
  \     \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Supplier\": {\n      \"@id\": \"ebs:Supplier\",\n      \"@context\": {\n        \"vendorId\": {\n          \"@id\": \"ebs:vendorId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"vendorName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"segment1\": {\n          \"@id\": \"ebs:vendorNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vendorType\": {\n          \"@id\": \"ebs:vendorType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"taxPayerId\": {\n          \"@id\": \"schema:taxID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dunsBNumber\": {\n          \"@id\": \"schema:duns\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentCurrencyCode\": {\n          \"@id\": \"ebs:paymentCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n          \"@id\"\
  : \"ebs:isEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"sites\": {\n          \"@id\": \"ebs:hasSupplierSite\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"contacts\": {\n          \"@id\": \"ebs:hasSupplierContact\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdateDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"addressLine1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"townOrCity\": {\n          \"\
  @id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"region2\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zip\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SalesOrder\": {\n      \"@id\": \"ebs:SalesOrder\",\n      \"@context\": {\n        \"headerId\": {\n          \"@id\": \"ebs:orderHeaderId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"orderNumber\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"orderedDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"customerName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"transactionalCurrCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"flowStatusCode\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lines\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"InventoryItem\": {\n      \"@id\": \"ebs:InventoryItem\",\n      \"@context\": {\n        \"inventoryItemId\": {\n          \"@id\": \"ebs:inventoryItemId\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"segment1\": {\n          \"@id\": \"schema:sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"primaryUomCode\": {\n          \"@id\": \"ebs:unitOfMeasure\",\n          \"@type\": \"xsd:string\"\n        },\n        \"unitWeight\": {\n          \"@id\": \"schema:weight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"listPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"DiscreteJob\": {\n      \"@id\": \"ebs:DiscreteJob\",\n      \"@context\": {\n        \"wipEntityId\": {\n          \"@id\": \"ebs:wipEntityId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"wipEntityName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statusType\": {\n          \"@id\": \"ebs:jobStatus\",\n          \"\
  @type\": \"xsd:integer\"\n        },\n        \"startQuantity\": {\n          \"@id\": \"ebs:startQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"quantityCompleted\": {\n          \"@id\": \"ebs:quantityCompleted\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"scheduledStartDate\": {\n          \"@id\": \"ebs:scheduledStartDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheduledCompletionDate\": {\n          \"@id\": \"ebs:scheduledCompletionDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TradingPartner\": {\n      \"@id\": \"ebs:TradingPartner\",\n      \"@context\": {\n        \"tradingPartnerId\": {\n          \"@id\": \"ebs:tradingPartnerId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tradingPartnerName\": {\n          \"@id\": \"schema:name\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"tradingPartnerType\": {\n          \"@id\": \"ebs:tradingPartnerType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ediLocationCode\": {\n          \"@id\": \"ebs:ediLocationCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"documentStandard\": {\n          \"@id\": \"ebs:documentStandard\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-e-business-suite/refs/heads/main/json-ld/context.jsonld
tags:
- Business Applications
- E-Business Suite
- Enterprise
- ERP
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
