---
class_count: 5
classes:
- FinancialService
- InsuranceAgency
- FinancialProduct
- InvestmentFund
- FinancialOrganization
context_file: json-ld/western-and-southern-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/western-and-southern-financial/refs/heads/main/json-ld/western-and-southern-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Western And Southern Financial from western-and-southern-financial.
layout: jsonld
name: Western And Southern Financial Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: wsf
  uri: https://www.westernsouthern.com/ontology/
properties:
- container: ''
  name: Policy
  type: reference
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: premium
  type: decimal
- container: ''
  name: deathBenefit
  type: decimal
- container: ''
  name: surrenderValue
  type: decimal
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: Annuity
  type: reference
- container: ''
  name: annuityType
  type: string
- container: ''
  name: accumulationValue
  type: decimal
- container: ''
  name: payoutOption
  type: string
- container: ''
  name: surrenderChargePeriod
  type: integer
- container: ''
  name: Beneficiary
  type: reference
- container: ''
  name: beneficiaryName
  type: string
- container: ''
  name: beneficiaryRelationship
  type: string
- container: ''
  name: beneficiaryShare
  type: decimal
- container: ''
  name: MutualFund
  type: reference
- container: ''
  name: fundSymbol
  type: string
- container: ''
  name: netAssetValue
  type: decimal
- container: ''
  name: expenseRatio
  type: decimal
- container: ''
  name: inceptionDate
  type: date
- container: ''
  name: Policyholder
  type: reference
- container: ''
  name: insured
  type: reference
- container: ''
  name: owner
  type: reference
property_count: 25
provider_name: western-and-southern-financial
provider_slug: western-and-southern-financial
slug: western-and-southern-financial-context
source_filename: western-and-southern-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"wsf\": \"https://www.westernsouthern.com/ontology/\",\n\n    \"FinancialService\": \"schema:FinancialService\",\n    \"InsuranceAgency\": \"schema:InsuranceAgency\",\n    \"FinancialProduct\": \"schema:FinancialProduct\",\n    \"InvestmentFund\": \"schema:InvestmentFund\",\n    \"FinancialOrganization\": \"schema:FinancialService\",\n\n    \"Policy\": {\n      \"@id\": \"wsf:Policy\",\n      \"@type\": \"@id\"\n    },\n    \"policyNumber\": {\n      \"@id\": \"wsf:policyNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"wsf:policyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"premium\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deathBenefit\": {\n      \"@id\": \"wsf:deathBenefit\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"surrenderValue\": {\n      \"@id\": \"wsf:surrenderValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"Annuity\": {\n      \"@id\": \"wsf:Annuity\",\n      \"@type\": \"@id\"\n    },\n    \"annuityType\": {\n      \"@id\": \"wsf:annuityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accumulationValue\": {\n      \"@id\": \"wsf:accumulationValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"payoutOption\": {\n      \"@id\": \"wsf:payoutOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surrenderChargePeriod\": {\n      \"@id\": \"wsf:surrenderChargePeriod\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Beneficiary\": {\n      \"@id\": \"wsf:Beneficiary\",\n      \"@type\": \"@id\"\n    },\n    \"beneficiaryName\"\
  : {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryRelationship\": {\n      \"@id\": \"wsf:beneficiaryRelationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"beneficiaryShare\": {\n      \"@id\": \"wsf:beneficiaryShare\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"MutualFund\": {\n      \"@id\": \"schema:InvestmentFund\",\n      \"@type\": \"@id\"\n    },\n    \"fundSymbol\": {\n      \"@id\": \"wsf:fundSymbol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"netAssetValue\": {\n      \"@id\": \"wsf:netAssetValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"expenseRatio\": {\n      \"@id\": \"wsf:expenseRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"inceptionDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"Policyholder\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"insured\": {\n      \"@id\": \"wsf:insured\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:owner\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/western-and-southern-financial/refs/heads/main/json-ld/western-and-southern-financial-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
