---
api_specs:
- filename: expense-report.json
  format: json
  label: Concur Expense API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.concur.com/api-reference/expense/expense-report/expense-report.json
- filename: itinerary.json
  format: json
  label: Concur Travel API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.concur.com/api-reference/travel/itinerary/itinerary.json
- filename: v3.invoice.json
  format: json
  label: Concur Invoice API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.concur.com/api-reference/invoice/v3.invoice.json
- filename: v4.request.json
  format: json
  label: Concur Request API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.concur.com/api-reference/request/v4.request.json
class_count: 0
classes: []
context_file: json-ld/sap-concur-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-concur/refs/heads/main/json-ld/sap-concur-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Concur from SAP Concur.
layout: jsonld
name: Sap Concur Context
namespaces:
- prefix: concur
  uri: https://developer.concur.com/schema/expense/v4/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: ExpenseReport
  type: ''
- container: ''
  name: ExpenseEntry
  type: ''
- container: ''
  name: Allocation
  type: ''
- container: ''
  name: Amount
  type: ''
- container: ''
  name: CustomData
  type: ''
- container: ''
  name: ExpenseType
  type: ''
- container: ''
  name: PaymentType
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Vendor
  type: ''
- container: ''
  name: ExchangeRate
  type: ''
- container: ''
  name: Mileage
  type: ''
- container: ''
  name: Travel
  type: ''
- container: ''
  name: TravelAllowance
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: ExpenseItemization
  type: ''
property_count: 15
provider_name: SAP Concur
provider_slug: sap-concur
slug: sap-concur-context
source_filename: sap-concur-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"concur\": \"https://developer.concur.com/schema/expense/v4/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"ExpenseReport\": {\n      \"@id\": \"concur:ExpenseReport\",\n      \"@context\": {\n        \"reportId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessPurpose\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"reportDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:startDate\"\
  ,\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"countryCode\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countrySubDivisionCode\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"policyId\": {\n          \"@id\": \"concur:policyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"reportFormId\": {\n          \"@id\": \"concur:reportFormId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ledgerId\": {\n          \"@id\": \"concur:ledgerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"approvalStatus\": {\n          \"@id\": \"concur:approvalStatus\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"approvalStatusId\": {\n          \"@id\": \"concur:approvalStatusId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentStatus\": {\n          \"@id\": \"concur:paymentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"paymentStatusId\": {\n          \"@id\": \"concur:paymentStatusId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"claimedAmount\": {\n          \"@id\": \"concur:claimedAmount\",\n          \"@type\": \"@id\"\n        },\n        \"approvedAmount\": {\n          \"@id\": \"concur:approvedAmount\",\n          \"@type\": \"@id\"\n        },\n        \"reportTotal\": {\n          \"@id\": \"concur:reportTotal\",\n          \"@type\": \"@id\"\n        },\n        \"amountDueEmployee\": {\n          \"@id\": \"concur:amountDueEmployee\",\n          \"@type\": \"@id\"\n        },\n        \"userId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n       \
  \ \"isSubmitted\": {\n          \"@id\": \"concur:isSubmitted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isSentBack\": {\n          \"@id\": \"concur:isSentBack\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"submitDate\": {\n          \"@id\": \"concur:submitDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"reportVersion\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"customData\": {\n          \"@id\": \"concur:customData\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"expenses\": {\n          \"@id\": \"concur:hasExpense\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"allocations\": {\n          \"@id\": \"concur:hasAllocation\",\n          \"@type\": \"@id\",\n\
  \          \"@container\": \"@set\"\n        },\n        \"comments\": {\n          \"@id\": \"concur:hasComment\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ExpenseEntry\": {\n      \"@id\": \"concur:ExpenseEntry\",\n      \"@context\": {\n        \"expenseId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"transactionDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"transactionAmount\": {\n          \"@id\": \"concur:transactionAmount\",\n          \"@type\": \"@id\"\n        },\n        \"postedAmount\": {\n          \"@id\": \"concur:postedAmount\",\n          \"@type\": \"@id\"\n        },\n        \"approvedAmount\": {\n          \"@id\": \"concur:approvedAmount\",\n          \"@type\": \"@id\"\n        },\n        \"approverAdjustedAmount\": {\n          \"@id\": \"concur:approverAdjustedAmount\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"businessPurpose\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expenseType\": {\n          \"@id\": \"concur:expenseType\",\n          \"@type\": \"@id\"\n        },\n        \"paymentType\": {\n          \"@id\": \"concur:paymentType\",\n          \"@type\": \"@id\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"@id\"\n        },\n        \"vendor\": {\n          \"@id\": \"concur:vendor\",\n          \"@type\": \"@id\"\n        },\n        \"exchangeRate\": {\n          \"@id\": \"concur:exchangeRate\",\n          \"@type\": \"@id\"\n        },\n        \"allocationState\": {\n          \"@id\": \"concur:allocationState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isPersonalExpense\": {\n          \"@id\": \"concur:isPersonalExpense\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isExpenseRejected\"\
  : {\n          \"@id\": \"concur:isExpenseRejected\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPaperReceiptReceived\": {\n          \"@id\": \"concur:isPaperReceiptReceived\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasExceptions\": {\n          \"@id\": \"concur:hasExceptions\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"mileage\": {\n          \"@id\": \"concur:mileage\",\n          \"@type\": \"@id\"\n        },\n        \"travel\": {\n          \"@id\": \"concur:travel\",\n          \"@type\": \"@id\"\n        },\n        \"travelAllowance\": {\n          \"@id\": \"concur:travelAllowance\",\n          \"@type\": \"@id\"\n        },\n        \"invoiceId\": {\n          \"@id\": \"concur:invoiceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customData\": {\n          \"@id\": \"concur:customData\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"lastModifiedDate\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Allocation\": {\n      \"@id\": \"concur:Allocation\",\n      \"@context\": {\n        \"allocationId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expenseId\": {\n          \"@id\": \"concur:expenseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountCode\": {\n          \"@id\": \"concur:accountCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"overLimitAccountCode\": {\n          \"@id\": \"concur:overLimitAccountCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"allocationAmount\": {\n          \"@id\": \"concur:allocationAmount\",\n          \"@type\": \"@id\"\n        },\n        \"approvedAmount\": {\n          \"@id\": \"concur:approvedAmount\",\n          \"@type\": \"@id\"\n        },\n        \"claimedAmount\": {\n          \"@id\": \"concur:claimedAmount\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"percentage\": {\n          \"@id\": \"concur:percentage\",\n          \"@type\": \"xsd:double\"\n        },\n        \"isSystemAllocation\": {\n          \"@id\": \"concur:isSystemAllocation\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isPercentEdited\": {\n          \"@id\": \"concur:isPercentEdited\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"customData\": {\n          \"@id\": \"concur:customData\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Amount\": {\n      \"@id\": \"concur:Amount\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:double\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"CustomData\": {\n      \"@id\": \"concur:CustomData\",\n      \"@context\"\
  : {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isValid\": {\n          \"@id\": \"concur:isValid\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ExpenseType\": {\n      \"@id\": \"concur:ExpenseType\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"schema:codeValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isDeleted\": {\n          \"@id\": \"concur:isDeleted\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"PaymentType\": {\n      \"@id\": \"concur:PaymentType\",\n      \"@context\": {\n\
  \        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"code\": {\n          \"@id\": \"schema:codeValue\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countryCode\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countrySubDivisionCode\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\
  \n        }\n      }\n    },\n\n    \"Vendor\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"ExchangeRate\": {\n      \"@id\": \"concur:ExchangeRate\",\n      \"@context\": {\n        \"value\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:double\"\n        },\n        \"operation\": {\n          \"@id\": \"concur:exchangeRateOperation\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Mileage\": {\n      \"@id\": \"concur:Mileage\",\n      \"@context\": {\n        \"totalDistance\": {\n          \"@id\": \"schema:distance\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"vehicleId\": {\n          \"@id\": \"concur:vehicleId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"odometerStart\": {\n          \"@id\": \"concur:odometerStart\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"odometerEnd\": {\n          \"@id\": \"concur:odometerEnd\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"passengerCount\": {\n          \"@id\": \"concur:passengerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"personalDistance\": {\n          \"@id\": \"concur:personalDistance\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"routeId\": {\n          \"@id\": \"concur:routeId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Travel\": {\n      \"@id\": \"concur:Travel\",\n      \"@context\": {\n        \"startLocation\": {\n          \"@id\": \"schema:fromLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"endLocation\": {\n\
  \          \"@id\": \"schema:toLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticketNumber\": {\n          \"@id\": \"schema:confirmationNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"hotelCheckinDate\": {\n          \"@id\": \"schema:checkinTime\",\n          \"@type\": \"xsd:date\"\n        },\n        \"hotelCheckoutDate\": {\n          \"@id\": \"schema:checkoutTime\",\n          \"@type\": \"xsd:date\"\n        },\n        \"carRentalDays\": {\n          \"@id\": \"concur:carRentalDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"airlineServiceClassCode\": {\n          \"@id\": \"concur:airlineServiceClassCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"airlineFeeTypeCode\": {\n          \"@id\": \"concur:airlineFeeTypeCode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TravelAllowance\": {\n      \"@id\": \"concur:TravelAllowance\",\n      \"@context\": {\n        \"\
  isExpensePartOfTravelAllowance\": {\n          \"@id\": \"concur:isExpensePartOfTravelAllowance\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dailyTravelAllowanceId\": {\n          \"@id\": \"concur:dailyTravelAllowanceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dailyLimitAmount\": {\n          \"@id\": \"concur:dailyLimitAmount\",\n          \"@type\": \"xsd:double\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"concur:Comment\",\n      \"@context\": {\n        \"comment\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isLatest\": {\n          \"@id\": \"concur:isLatest\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isAuditLog\": {\n\
  \          \"@id\": \"concur:isAuditLog\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"ExpenseItemization\": {\n      \"@id\": \"concur:ExpenseItemization\",\n      \"@context\": {\n        \"itemizationId\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"expenseId\": {\n          \"@id\": \"concur:expenseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"transactionDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"transactionAmount\": {\n          \"@id\": \"concur:transactionAmount\",\n          \"@type\": \"@id\"\n        },\n        \"expenseType\": {\n          \"@id\": \"concur:expenseType\",\n          \"@type\": \"@id\"\n        },\n        \"businessPurpose\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-concur/refs/heads/main/json-ld/sap-concur-context.jsonld
tags:
- Business Travel
- Expense Management
- Financial Services
- Invoice Management
- Travel Management
- JSON-LD
- Linked Data
- Semantic Web
---
