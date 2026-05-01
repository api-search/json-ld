---
api_specs:
- filename: finops-foundation-focus-cost-and-usage-openapi.yml
  format: yaml
  label: FOCUS Cost and Usage API
  slug: focus-cost-and-usage
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/finops-foundation/refs/heads/main/openapi/finops-foundation-focus-cost-and-usage-openapi.yml
class_count: 0
classes: []
context_file: json-ld/finops-foundation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/finops-foundation/refs/heads/main/json-ld/finops-foundation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Finops Foundation from FinOps Foundation.
layout: jsonld
name: Finops Foundation Context
namespaces:
- prefix: focus
  uri: https://focus.finops.org/focus-columns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AvailabilityZone
  type: string
- container: ''
  name: BilledCost
  type: decimal
- container: ''
  name: BillingAccountId
  type: string
- container: ''
  name: BillingAccountName
  type: string
- container: ''
  name: BillingCurrency
  type: string
- container: ''
  name: BillingPeriodEnd
  type: dateTime
- container: ''
  name: BillingPeriodStart
  type: dateTime
- container: ''
  name: CapacityReservationId
  type: string
- container: ''
  name: ChargeCategory
  type: string
- container: ''
  name: ChargeClass
  type: string
- container: ''
  name: ChargeDescription
  type: string
- container: ''
  name: ChargeFrequency
  type: string
- container: ''
  name: ChargePeriodEnd
  type: dateTime
- container: ''
  name: ChargePeriodStart
  type: dateTime
- container: ''
  name: CommitmentDiscountCategory
  type: string
- container: ''
  name: CommitmentDiscountId
  type: string
- container: ''
  name: CommitmentDiscountName
  type: string
- container: ''
  name: CommitmentDiscountQuantity
  type: decimal
- container: ''
  name: CommitmentDiscountStatus
  type: string
- container: ''
  name: CommitmentDiscountType
  type: string
- container: ''
  name: CommitmentDiscountUnit
  type: string
- container: ''
  name: CommitmentStartDate
  type: dateTime
- container: ''
  name: CommitmentEndDate
  type: dateTime
- container: ''
  name: CommitmentTotalQuantity
  type: decimal
- container: ''
  name: CommitmentRemainingQuantity
  type: decimal
- container: ''
  name: CommitmentUnit
  type: string
- container: ''
  name: CommitmentDescription
  type: string
- container: ''
  name: ConsumedQuantity
  type: decimal
- container: ''
  name: ConsumedUnit
  type: string
- container: ''
  name: ContractedCost
  type: decimal
- container: ''
  name: ContractedUnitPrice
  type: decimal
- container: ''
  name: EffectiveCost
  type: decimal
- container: ''
  name: InvoiceIssuerName
  type: string
- container: ''
  name: ListCost
  type: decimal
- container: ''
  name: ListUnitPrice
  type: decimal
- container: ''
  name: PricingCategory
  type: string
- container: ''
  name: PricingQuantity
  type: decimal
- container: ''
  name: PricingUnit
  type: string
- container: ''
  name: ProviderName
  type: string
- container: ''
  name: PublisherName
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: ResourceId
  type: string
- container: ''
  name: ResourceName
  type: string
- container: ''
  name: ResourceType
  type: string
- container: ''
  name: ServiceCategory
  type: string
- container: ''
  name: ServiceName
  type: string
- container: ''
  name: ServiceSubcategory
  type: string
- container: ''
  name: SkuId
  type: string
- container: ''
  name: SkuPriceId
  type: string
- container: ''
  name: SubAccountId
  type: string
- container: ''
  name: SubAccountName
  type: string
- container: ''
  name: Tags
  type: '@json'
- container: ''
  name: x_SplitCostAllocationMethod
  type: string
- container: ''
  name: x_SplitCostAllocationPercentage
  type: decimal
property_count: 54
provider_name: FinOps Foundation
provider_slug: finops-foundation
slug: finops-foundation-context
source_filename: finops-foundation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"focus\": \"https://focus.finops.org/focus-columns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AvailabilityZone\": {\n      \"@id\": \"focus:availabilityzone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BilledCost\": {\n      \"@id\": \"focus:billedcost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"BillingAccountId\": {\n      \"@id\": \"focus:billingaccountid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingAccountName\": {\n      \"@id\": \"focus:billingaccountname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingCurrency\": {\n      \"@id\": \"focus:billingcurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BillingPeriodEnd\": {\n      \"@id\": \"focus:billingperiodend\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"BillingPeriodStart\": {\n      \"@id\": \"focus:billingperiodstart\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"CapacityReservationId\": {\n      \"@id\": \"focus:capacityreservationid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargeCategory\": {\n      \"@id\": \"focus:chargecategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargeClass\": {\n      \"@id\": \"focus:chargeclass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargeDescription\": {\n      \"@id\": \"focus:chargedescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargeFrequency\": {\n      \"@id\": \"focus:chargefrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChargePeriodEnd\": {\n      \"@id\": \"focus:chargeperiodend\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ChargePeriodStart\": {\n      \"@id\": \"focus:chargeperiodstart\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CommitmentDiscountCategory\": {\n      \"@id\": \"focus:commitmentdiscountcategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDiscountId\": {\n      \"@id\": \"focus:commitmentdiscountid\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDiscountName\": {\n      \"@id\": \"focus:commitmentdiscountname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDiscountQuantity\": {\n      \"@id\": \"focus:commitmentdiscountquantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CommitmentDiscountStatus\": {\n      \"@id\": \"focus:commitmentdiscountstatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDiscountType\": {\n      \"@id\": \"focus:commitmentdiscounttype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDiscountUnit\": {\n      \"@id\": \"focus:commitmentdiscountunit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentStartDate\": {\n      \"@id\": \"focus:commitmentstartdate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CommitmentEndDate\": {\n      \"@id\": \"focus:commitmentenddate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CommitmentTotalQuantity\": {\n      \"@id\": \"focus:commitmenttotalquantity\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CommitmentRemainingQuantity\": {\n      \"@id\": \"focus:commitmentremainingquantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CommitmentUnit\": {\n      \"@id\": \"focus:commitmentunit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitmentDescription\": {\n      \"@id\": \"focus:commitmentdescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConsumedQuantity\": {\n      \"@id\": \"focus:consumedquantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ConsumedUnit\": {\n      \"@id\": \"focus:consumedunit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContractedCost\": {\n      \"@id\": \"focus:contractedcost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ContractedUnitPrice\": {\n      \"@id\": \"focus:contractedunitprice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"EffectiveCost\": {\n      \"@id\": \"focus:effectivecost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"InvoiceIssuerName\"\
  : {\n      \"@id\": \"focus:invoiceissuername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListCost\": {\n      \"@id\": \"focus:listcost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ListUnitPrice\": {\n      \"@id\": \"focus:listunitprice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PricingCategory\": {\n      \"@id\": \"focus:pricingcategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PricingQuantity\": {\n      \"@id\": \"focus:pricingquantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"PricingUnit\": {\n      \"@id\": \"focus:pricingunit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderName\": {\n      \"@id\": \"focus:providername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublisherName\": {\n      \"@id\": \"focus:publishername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"focus:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceId\": {\n      \"@id\": \"focus:resourceid\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"ResourceName\": {\n      \"@id\": \"focus:resourcename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"focus:resourcetype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceCategory\": {\n      \"@id\": \"focus:servicecategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"focus:servicename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceSubcategory\": {\n      \"@id\": \"focus:servicesubcategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SkuId\": {\n      \"@id\": \"focus:skuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SkuPriceId\": {\n      \"@id\": \"focus:skupriceid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubAccountId\": {\n      \"@id\": \"focus:subaccountid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubAccountName\": {\n      \"@id\": \"focus:subaccountname\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"Tags\": {\n      \"@id\": \"focus:tags\",\n      \"@type\": \"@json\"\n    },\n    \"x_SplitCostAllocationMethod\": {\n      \"@id\": \"focus:x_splitcostallocationmethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"x_SplitCostAllocationPercentage\": {\n      \"@id\": \"focus:x_splitcostallocationpercentage\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/finops-foundation/refs/heads/main/json-ld/finops-foundation-context.jsonld
tags:
- Budgets
- Costs
- FinOps
- JSON-LD
- Linked Data
- Semantic Web
---
