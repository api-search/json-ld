---
api_specs:
- filename: sap-sd-sales-order-openapi.yml
  format: yaml
  label: Sales Order API
  slug: sales-order
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-order-openapi.yml
- filename: sap-sd-customer-master-data-openapi.yml
  format: yaml
  label: Customer Master Data API
  slug: customer-master-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-master-data-openapi.yml
- filename: sap-sd-outbound-delivery-openapi.yml
  format: yaml
  label: Outbound Delivery API
  slug: outbound-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-outbound-delivery-openapi.yml
- filename: sap-sd-billing-document-openapi.yml
  format: yaml
  label: Billing Document API
  slug: billing-document
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-billing-document-openapi.yml
- filename: sap-sd-pricing-openapi.yml
  format: yaml
  label: Pricing API
  slug: pricing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-pricing-openapi.yml
- filename: sap-sd-sales-quotation-openapi.yml
  format: yaml
  label: Sales Quotation API
  slug: sales-quotation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-quotation-openapi.yml
- filename: sap-sd-credit-management-openapi.yml
  format: yaml
  label: Credit Management API
  slug: credit-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-credit-management-openapi.yml
- filename: sap-sd-material-master-openapi.yml
  format: yaml
  label: Material Master API
  slug: material-master
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-material-master-openapi.yml
- filename: sap-sd-credit-memo-request-openapi.yml
  format: yaml
  label: Credit Memo Request API
  slug: credit-memo-request
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-credit-memo-request-openapi.yml
- filename: sap-sd-debit-memo-request-openapi.yml
  format: yaml
  label: Debit Memo Request API
  slug: debit-memo-request
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-debit-memo-request-openapi.yml
- filename: sap-sd-sales-contract-openapi.yml
  format: yaml
  label: Sales Contract API
  slug: sales-contract
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-contract-openapi.yml
- filename: sap-sd-sales-inquiry-openapi.yml
  format: yaml
  label: Sales Inquiry API
  slug: sales-inquiry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-inquiry-openapi.yml
- filename: sap-sd-sales-scheduling-agreement-openapi.yml
  format: yaml
  label: Sales Scheduling Agreement API
  slug: sales-scheduling-agreement
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-sales-scheduling-agreement-openapi.yml
- filename: sap-sd-customer-return-openapi.yml
  format: yaml
  label: Customer Return API
  slug: customer-return
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-return-openapi.yml
- filename: sap-sd-customer-returns-delivery-openapi.yml
  format: yaml
  label: Customer Returns Delivery API
  slug: customer-returns-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-returns-delivery-openapi.yml
- filename: sap-sd-customer-material-openapi.yml
  format: yaml
  label: Customer Material API
  slug: customer-material
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-customer-material-openapi.yml
- filename: sap-sd-inbound-delivery-openapi.yml
  format: yaml
  label: Inbound Delivery API
  slug: inbound-delivery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/openapi/sap-sd-inbound-delivery-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sap-sd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/json-ld/sap-sd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap Sd from SAP Sales and Distribution (SD).
layout: jsonld
name: Sap Sd Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sap
  uri: https://api.sap.com/vocabulary/
- prefix: sapsd
  uri: https://api.sap.com/vocabulary/sd/
properties:
- container: ''
  name: SalesOrder
  type: reference
- container: ''
  name: SalesOrderNumber
  type: string
- container: ''
  name: SalesOrderType
  type: string
- container: ''
  name: SalesOrganization
  type: string
- container: ''
  name: DistributionChannel
  type: string
- container: ''
  name: OrganizationDivision
  type: string
- container: ''
  name: SoldToParty
  type: reference
- container: ''
  name: ShipToParty
  type: reference
- container: ''
  name: PayerParty
  type: reference
- container: ''
  name: TotalNetAmount
  type: decimal
- container: ''
  name: TransactionCurrency
  type: string
- container: ''
  name: CreationDate
  type: date
- container: ''
  name: LastChangeDate
  type: date
- container: ''
  name: PurchaseOrderByCustomer
  type: string
- container: ''
  name: RequestedDeliveryDate
  type: date
- container: ''
  name: SalesOrderItem
  type: reference
- container: ''
  name: Material
  type: string
- container: ''
  name: RequestedQuantity
  type: decimal
- container: ''
  name: RequestedQuantityUnit
  type: string
- container: ''
  name: NetAmount
  type: decimal
- container: ''
  name: Plant
  type: string
- container: ''
  name: Batch
  type: string
- container: ''
  name: BusinessPartner
  type: reference
- container: ''
  name: BusinessPartnerCategory
  type: string
- container: ''
  name: BusinessPartnerName
  type: string
- container: ''
  name: FirstName
  type: string
- container: ''
  name: LastName
  type: string
- container: ''
  name: OrganizationBPName1
  type: string
- container: ''
  name: BusinessPartnerAddress
  type: reference
- container: ''
  name: StreetName
  type: string
- container: ''
  name: CityName
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: PostalCode
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: Product
  type: reference
- container: ''
  name: ProductType
  type: string
- container: ''
  name: ProductGroup
  type: string
- container: ''
  name: ProductDescription
  type: string
- container: ''
  name: GrossWeight
  type: decimal
- container: ''
  name: WeightUnit
  type: string
- container: ''
  name: ProductStandardID
  type: string
- container: ''
  name: OutboundDelivery
  type: reference
- container: ''
  name: DeliveryDocument
  type: string
- container: ''
  name: DeliveryDate
  type: date
- container: ''
  name: ShippingPoint
  type: string
- container: ''
  name: BillingDocument
  type: reference
- container: ''
  name: BillingDocumentType
  type: string
- container: ''
  name: BillingDocumentDate
  type: date
- container: ''
  name: TotalGrossAmount
  type: decimal
- container: ''
  name: TotalTaxAmount
  type: decimal
- container: ''
  name: PricingConditionRecord
  type: reference
- container: ''
  name: ConditionType
  type: string
- container: ''
  name: ConditionRateValue
  type: decimal
- container: ''
  name: SalesQuotation
  type: reference
- container: ''
  name: SalesInquiry
  type: reference
- container: ''
  name: SalesContract
  type: reference
- container: ''
  name: SchedulingAgreement
  type: reference
- container: ''
  name: CustomerReturn
  type: reference
- container: ''
  name: CreditMemoRequest
  type: reference
- container: ''
  name: DebitMemoRequest
  type: reference
- container: ''
  name: CustomerPaymentTerms
  type: string
- container: ''
  name: IncotermsClassification
  type: string
- container: ''
  name: OverallSDProcessStatus
  type: string
- container: ''
  name: PartnerFunction
  type: string
- container: ''
  name: Language
  type: string
property_count: 65
provider_name: SAP Sales and Distribution (SD)
provider_slug: sap-sales-and-distribution-sd
slug: sap-sd-context
source_filename: sap-sd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.sap.com/vocabulary/sd/\",\n    \"schema\": \"https://schema.org/\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sap\": \"https://api.sap.com/vocabulary/\",\n    \"sapsd\": \"https://api.sap.com/vocabulary/sd/\",\n\n    \"SalesOrder\": {\n      \"@id\": \"sapsd:SalesOrder\",\n      \"@type\": \"@id\",\n      \"comment\": \"Sales order document in SAP S/4HANA SD module\"\n    },\n    \"SalesOrderNumber\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SalesOrderType\": {\n      \"@id\": \"sapsd:SalesOrderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SalesOrganization\": {\n      \"@id\": \"sapsd:SalesOrganization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DistributionChannel\": {\n      \"@id\": \"sapsd:DistributionChannel\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"OrganizationDivision\": {\n      \"@id\": \"sapsd:OrganizationDivision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SoldToParty\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"@id\"\n    },\n    \"ShipToParty\": {\n      \"@id\": \"sapsd:ShipToParty\",\n      \"@type\": \"@id\"\n    },\n    \"PayerParty\": {\n      \"@id\": \"sapsd:PayerParty\",\n      \"@type\": \"@id\"\n    },\n    \"TotalNetAmount\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TransactionCurrency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"dct:created\",\n      \"@type\": \"xsd:date\"\n    },\n    \"LastChangeDate\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"PurchaseOrderByCustomer\": {\n      \"@id\": \"sapsd:PurchaseOrderByCustomer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestedDeliveryDate\": {\n\
  \      \"@id\": \"sapsd:RequestedDeliveryDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"SalesOrderItem\": {\n      \"@id\": \"sapsd:SalesOrderItem\",\n      \"@type\": \"@id\",\n      \"comment\": \"Line item within a sales order\"\n    },\n    \"Material\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestedQuantity\": {\n      \"@id\": \"schema:orderQuantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"RequestedQuantityUnit\": {\n      \"@id\": \"schema:unitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetAmount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Plant\": {\n      \"@id\": \"sapsd:Plant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Batch\": {\n      \"@id\": \"sapsd:Batch\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"BusinessPartner\": {\n      \"@id\": \"sapsd:BusinessPartner\",\n      \"@type\": \"@id\",\n      \"comment\": \"Business partner record\
  \ in SAP representing a customer, vendor, or person\"\n    },\n    \"BusinessPartnerCategory\": {\n      \"@id\": \"sapsd:BusinessPartnerCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BusinessPartnerName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FirstName\": {\n      \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastName\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrganizationBPName1\": {\n      \"@id\": \"schema:legalName\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"BusinessPartnerAddress\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@type\": \"@id\"\n    },\n    \"StreetName\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CityName\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"schema:addressRegion\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"PostalCode\": {\n      \"@id\": \"schema:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\",\n      \"comment\": \"Material master record (product) in SAP S/4HANA\"\n    },\n    \"ProductType\": {\n      \"@id\": \"sapsd:ProductType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductGroup\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductDescription\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GrossWeight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"WeightUnit\": {\n      \"@id\": \"sapsd:WeightUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductStandardID\": {\n      \"@id\": \"schema:gtin\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n\n    \"OutboundDelivery\": {\n      \"@id\": \"sapsd:OutboundDelivery\",\n      \"@type\": \"@id\",\n      \"comment\": \"Outbound delivery document for shipping goods\"\n    },\n    \"DeliveryDocument\": {\n      \"@id\": \"sapsd:DeliveryDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeliveryDate\": {\n      \"@id\": \"sapsd:DeliveryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"ShippingPoint\": {\n      \"@id\": \"sapsd:ShippingPoint\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"BillingDocument\": {\n      \"@id\": \"sapsd:BillingDocument\",\n      \"@type\": \"@id\",\n      \"comment\": \"Billing document (invoice, credit memo, or debit memo)\"\n    },\n    \"BillingDocumentType\": {\n      \"@id\": \"sapsd:BillingDocumentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingDocumentDate\": {\n      \"@id\": \"sapsd:BillingDocumentDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"TotalGrossAmount\": {\n\
  \      \"@id\": \"sapsd:TotalGrossAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"TotalTaxAmount\": {\n      \"@id\": \"sapsd:TotalTaxAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"PricingConditionRecord\": {\n      \"@id\": \"sapsd:PricingConditionRecord\",\n      \"@type\": \"@id\",\n      \"comment\": \"Sales pricing condition record for price determination\"\n    },\n    \"ConditionType\": {\n      \"@id\": \"sapsd:ConditionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionRateValue\": {\n      \"@id\": \"gr:hasCurrencyValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"SalesQuotation\": {\n      \"@id\": \"sapsd:SalesQuotation\",\n      \"@type\": \"@id\",\n      \"comment\": \"Sales quotation document for pre-sales process\"\n    },\n    \"SalesInquiry\": {\n      \"@id\": \"sapsd:SalesInquiry\",\n      \"@type\": \"@id\",\n      \"comment\": \"Sales inquiry document capturing customer interest\"\n    },\n    \"SalesContract\": {\n\
  \      \"@id\": \"sapsd:SalesContract\",\n      \"@type\": \"@id\",\n      \"comment\": \"Sales contract (quantity or value) for recurring business\"\n    },\n    \"SchedulingAgreement\": {\n      \"@id\": \"sapsd:SchedulingAgreement\",\n      \"@type\": \"@id\",\n      \"comment\": \"Scheduling agreement for recurring deliveries\"\n    },\n    \"CustomerReturn\": {\n      \"@id\": \"sapsd:CustomerReturn\",\n      \"@type\": \"@id\",\n      \"comment\": \"Customer return document for reverse logistics\"\n    },\n    \"CreditMemoRequest\": {\n      \"@id\": \"sapsd:CreditMemoRequest\",\n      \"@type\": \"@id\",\n      \"comment\": \"Credit memo request for issuing credit to customers\"\n    },\n    \"DebitMemoRequest\": {\n      \"@id\": \"sapsd:DebitMemoRequest\",\n      \"@type\": \"@id\",\n      \"comment\": \"Debit memo request for charging additional amounts\"\n    },\n\n    \"CustomerPaymentTerms\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"IncotermsClassification\": {\n      \"@id\": \"sapsd:IncotermsClassification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OverallSDProcessStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PartnerFunction\": {\n      \"@id\": \"sapsd:PartnerFunction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Language\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-sales-and-distribution-sd/refs/heads/main/json-ld/sap-sd-context.jsonld
tags:
- Distribution
- ERP
- OData
- S/4HANA
- Sales
- SAP
- JSON-LD
- Linked Data
- Semantic Web
---
