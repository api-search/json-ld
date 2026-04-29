---
class_count: 10
classes:
- Order
- OrderItem
- Organization
- Product
- PriceSpecification
- name
- description
- identifier
- customer
- orderedItem
context_file: json-ld/sap-s4hana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap-s4hana/refs/heads/main/json-ld/sap-s4hana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap S4Hana from SAP S/4HANA.
layout: jsonld
name: Sap S4Hana Context
namespaces:
- prefix: sap
  uri: https://api.sap.com/ns/s4hana/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: SalesOrder
  type: reference
- container: ''
  name: SalesOrderItem
  type: reference
- container: ''
  name: SalesOrderPartner
  type: reference
- container: ''
  name: SalesOrderPricingElement
  type: reference
- container: ''
  name: SalesOrderScheduleLine
  type: reference
- container: ''
  name: SalesOrderTextRecord
  type: reference
- container: ''
  name: url
  type: anyURI
- container: ''
  name: dateCreated
  type: date
- container: ''
  name: dateModified
  type: date
- container: ''
  name: orderNumber
  type: string
- container: ''
  name: orderDate
  type: date
- container: ''
  name: orderStatus
  type: string
- container: ''
  name: totalPrice
  type: decimal
- container: ''
  name: priceCurrency
  type: string
property_count: 14
provider_name: SAP S/4HANA
provider_slug: sap-s4hana
slug: sap-s4hana-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sap\": \"https://api.sap.com/ns/s4hana/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"@vocab\": \"https://api.sap.com/ns/s4hana/\",\n\n    \"SalesOrder\": {\n      \"@id\": \"sap:SalesOrder\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"SalesOrder\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOrderType\": {\n          \"@id\": \"sap:salesOrderType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOrganization\": {\n          \"@id\": \"sap:salesOrganization\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DistributionChannel\": {\n    \
  \      \"@id\": \"sap:distributionChannel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"OrganizationDivision\": {\n          \"@id\": \"sap:organizationDivision\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesGroup\": {\n          \"@id\": \"sap:salesGroup\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOffice\": {\n          \"@id\": \"sap:salesOffice\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesDistrict\": {\n          \"@id\": \"sap:salesDistrict\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SoldToParty\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"CreatedByUser\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"xsd:string\"\n        },\n        \"LastChangeDate\": {\n          \"@id\": \"schema:dateModified\"\
  ,\n          \"@type\": \"xsd:date\"\n        },\n        \"LastChangeDateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"PurchaseOrderByCustomer\": {\n          \"@id\": \"sap:customerPurchaseOrder\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CustomerPurchaseOrderType\": {\n          \"@id\": \"sap:customerPurchaseOrderType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CustomerPurchaseOrderDate\": {\n          \"@id\": \"sap:customerPurchaseOrderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"SalesOrderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"TotalNetAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"TransactionCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SDDocumentReason\"\
  : {\n          \"@id\": \"sap:documentReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PricingDate\": {\n          \"@id\": \"sap:pricingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"RequestedDeliveryDate\": {\n          \"@id\": \"sap:requestedDeliveryDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ShippingCondition\": {\n          \"@id\": \"sap:shippingCondition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CompleteDeliveryIsDefined\": {\n          \"@id\": \"sap:completeDeliveryRequired\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ShippingType\": {\n          \"@id\": \"sap:shippingType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"HeaderBillingBlockReason\": {\n          \"@id\": \"sap:billingBlockReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DeliveryBlockReason\": {\n          \"@id\": \"sap:deliveryBlockReason\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"IncotermsClassification\": {\n          \"@id\": \"sap:incotermsClassification\",\n          \"@type\": \"xsd:string\"\n        },\n        \"IncotermsTransferLocation\": {\n          \"@id\": \"sap:incotermsLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"IncotermsVersion\": {\n          \"@id\": \"sap:incotermsVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CustomerPaymentTerms\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PaymentMethod\": {\n          \"@id\": \"schema:paymentMethod\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ReferenceSDDocument\": {\n          \"@id\": \"sap:referenceDocument\",\n          \"@type\": \"xsd:string\"\n        },\n        \"OverallSDProcessStatus\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TotalCreditCheckStatus\": {\n          \"@id\"\
  : \"sap:creditCheckStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"OverallTotalDeliveryStatus\": {\n          \"@id\": \"sap:deliveryStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"OverallSDDocumentRejectionSts\": {\n          \"@id\": \"sap:rejectionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"BillingDocumentDate\": {\n          \"@id\": \"sap:billingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"to_Item\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        },\n        \"to_Partner\": {\n          \"@id\": \"sap:headerPartners\",\n          \"@container\": \"@set\"\n        },\n        \"to_PricingElement\": {\n          \"@id\": \"sap:headerPricingElements\",\n          \"@container\": \"@set\"\n        },\n        \"to_Text\": {\n          \"@id\": \"sap:headerTexts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SalesOrderItem\"\
  : {\n      \"@id\": \"sap:SalesOrderItem\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"SalesOrder\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOrderItem\": {\n          \"@id\": \"sap:salesOrderItemNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"HigherLevelItem\": {\n          \"@id\": \"sap:higherLevelItem\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOrderItemCategory\": {\n          \"@id\": \"sap:itemCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesOrderItemText\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Material\": {\n          \"@id\": \"schema:productID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MaterialByCustomer\": {\n          \"@id\": \"sap:customerMaterialNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"RequestedQuantity\"\
  : {\n          \"@id\": \"schema:orderQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"RequestedQuantityUnit\": {\n          \"@id\": \"sap:orderQuantityUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"NetAmount\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"TransactionCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Plant\": {\n          \"@id\": \"sap:deliveringPlant\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ProductionPlant\": {\n          \"@id\": \"sap:productionPlant\",\n          \"@type\": \"xsd:string\"\n        },\n        \"StorageLocation\": {\n          \"@id\": \"sap:storageLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Batch\": {\n          \"@id\": \"sap:batchNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MaterialGroup\": {\n         \
  \ \"@id\": \"sap:materialGroup\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ShippingPoint\": {\n          \"@id\": \"sap:shippingPoint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DeliveryPriority\": {\n          \"@id\": \"sap:deliveryPriority\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ItemGrossWeight\": {\n          \"@id\": \"schema:weight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ItemNetWeight\": {\n          \"@id\": \"sap:netWeight\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ItemWeightUnit\": {\n          \"@id\": \"sap:weightUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ProfitCenter\": {\n          \"@id\": \"sap:profitCenter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CostCenter\": {\n          \"@id\": \"sap:costCenter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"WBSElement\": {\n          \"@id\": \"sap:wbsElement\",\n  \
  \        \"@type\": \"xsd:string\"\n        },\n        \"SDProcessStatus\": {\n          \"@id\": \"sap:processingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DeliveryStatus\": {\n          \"@id\": \"sap:deliveryStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"OrderRelatedBillingStatus\": {\n          \"@id\": \"sap:billingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SalesDocumentRjcnReason\": {\n          \"@id\": \"sap:rejectionReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ItemBillingBlockReason\": {\n          \"@id\": \"sap:itemBillingBlock\",\n          \"@type\": \"xsd:string\"\n        },\n        \"to_PricingElement\": {\n          \"@id\": \"sap:itemPricingElements\",\n          \"@container\": \"@set\"\n        },\n        \"to_ScheduleLine\": {\n          \"@id\": \"sap:scheduleLines\",\n          \"@container\": \"@set\"\n        },\n        \"to_Partner\": {\n          \"@id\"\
  : \"sap:itemPartners\",\n          \"@container\": \"@set\"\n        },\n        \"to_Text\": {\n          \"@id\": \"sap:itemTexts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SalesOrderPartner\": {\n      \"@id\": \"sap:SalesOrderPartner\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"PartnerFunction\": {\n          \"@id\": \"sap:partnerFunction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Customer\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Supplier\": {\n          \"@id\": \"sap:supplier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Personnel\": {\n          \"@id\": \"sap:personnel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ContactPerson\": {\n          \"@id\": \"sap:contactPerson\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SalesOrderPricingElement\": {\n      \"@id\": \"sap:SalesOrderPricingElement\"\
  ,\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"PricingProcedureStep\": {\n          \"@id\": \"sap:pricingStep\",\n          \"@type\": \"xsd:string\"\n        },\n        \"PricingProcedureCounter\": {\n          \"@id\": \"sap:pricingCounter\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionType\": {\n          \"@id\": \"sap:conditionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionRateValue\": {\n          \"@id\": \"gr:hasCurrencyValue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ConditionCurrency\": {\n          \"@id\": \"gr:hasCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionQuantity\": {\n          \"@id\": \"sap:conditionQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ConditionQuantityUnit\": {\n          \"@id\": \"sap:conditionQuantityUnit\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionAmount\": {\n          \"\
  @id\": \"sap:conditionAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"TransactionCurrency\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionIsForStatistics\": {\n          \"@id\": \"sap:isStatistical\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ConditionOrigin\": {\n          \"@id\": \"sap:conditionOrigin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionClass\": {\n          \"@id\": \"sap:conditionClass\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConditionIsManuallyChanged\": {\n          \"@id\": \"sap:isManuallyChanged\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"SalesOrderScheduleLine\": {\n      \"@id\": \"sap:SalesOrderScheduleLine\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"ScheduleLine\": {\n          \"@id\": \"sap:scheduleLineNumber\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"RequestedDeliveryDate\": {\n          \"@id\": \"sap:requestedDeliveryDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ConfirmedDeliveryDate\": {\n          \"@id\": \"sap:confirmedDeliveryDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"ScheduleLineOrderQuantity\": {\n          \"@id\": \"sap:orderedQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"ConfdOrderQtyByMatlAvailCheck\": {\n          \"@id\": \"sap:confirmedQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"DeliveredQtyInOrderQtyUnit\": {\n          \"@id\": \"sap:deliveredQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"OpenConfdDelivQtyInOrdQtyUnit\": {\n          \"@id\": \"sap:openDeliveryQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"OrderQuantityUnit\": {\n          \"@id\": \"sap:orderQuantityUnit\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n\
  \    \"SalesOrderTextRecord\": {\n      \"@id\": \"sap:SalesOrderTextRecord\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"Language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        },\n        \"LongTextID\": {\n          \"@id\": \"sap:textId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"LongText\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Order\": \"schema:Order\",\n    \"OrderItem\": \"schema:OrderItem\",\n    \"Organization\": \"schema:Organization\",\n    \"Product\": \"schema:Product\",\n    \"PriceSpecification\": \"gr:PriceSpecification\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\":\
  \ \"xsd:date\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n    \"orderNumber\": {\n      \"@id\": \"schema:orderNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalPrice\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priceCurrency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer\": \"schema:customer\",\n    \"orderedItem\": \"schema:orderedItem\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap-s4hana/refs/heads/main/json-ld/sap-s4hana-context.jsonld
tags:
- Business Applications
- Cloud
- Enterprise Resource Planning
- ERP
- Finance
- Human Resources
- Inventory
- Logistics
- Manufacturing
- Plant Maintenance
- Procurement
- S/4HANA
- Sales
- SAP
- JSON-LD
- Linked Data
- Semantic Web
---
