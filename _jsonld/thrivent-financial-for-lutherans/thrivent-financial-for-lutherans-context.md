---
class_count: 20
classes:
- name
- description
- url
- provider
- areaServed
- category
- legalName
- foundingDate
- headquarters
- nonprofitStatus
- Fortune500
- MoneyCoaching
- DedicatedPlanningServices
- ManagedAccountsProgram
- TrustServices
- ThriventBank
- ThriventCharitable
- ThriventActionTeams
- ChoiceDollars
- DonorAdvisedFund
context_file: json-ld/thrivent-financial-for-lutherans-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thrivent-financial-for-lutherans/refs/heads/main/json-ld/thrivent-financial-for-lutherans-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thrivent Financial For Lutherans from Thrivent Financial.
layout: jsonld
name: Thrivent Financial For Lutherans Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: thrivent
  uri: https://www.thrivent.com/vocab#
properties:
- container: ''
  name: FinancialAdvisoryService
  type: ''
- container: ''
  name: InsuranceProduct
  type: ''
- container: ''
  name: InvestmentProduct
  type: ''
- container: ''
  name: BankingProduct
  type: ''
- container: ''
  name: CharitableProgram
  type: ''
- container: ''
  name: annualFeeMin
  type: decimal
- container: ''
  name: annualFeeMax
  type: decimal
- container: ''
  name: minimumInvestment
  type: decimal
- container: ''
  name: feeRangeMin
  type: decimal
- container: ''
  name: feeRangeMax
  type: decimal
- container: ''
  name: assetsUnderManagement
  type: decimal
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: employeeCount
  type: integer
- container: ''
  name: isMemberOnly
  type: boolean
- container: ''
  name: isFeeBased
  type: boolean
- container: ''
  name: requiresMinimumInvestment
  type: boolean
- container: list
  name: planningServices
  type: ''
- container: list
  name: insuranceProducts
  type: ''
- container: list
  name: investmentProducts
  type: ''
- container: list
  name: bankingProducts
  type: ''
- container: list
  name: generosityPrograms
  type: ''
property_count: 21
provider_name: Thrivent Financial
provider_slug: thrivent-financial-for-lutherans
slug: thrivent-financial-for-lutherans-context
source_filename: thrivent-financial-for-lutherans-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.thrivent.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"thrivent\": \"https://www.thrivent.com/vocab#\",\n\n    \"FinancialAdvisoryService\": {\n      \"@id\": \"schema:FinancialService\",\n      \"rdfs:comment\": \"A financial advisory or planning service offered by Thrivent\"\n    },\n    \"InsuranceProduct\": {\n      \"@id\": \"schema:InsuranceAgency\",\n      \"rdfs:comment\": \"An insurance product offered by Thrivent\"\n    },\n    \"InvestmentProduct\": {\n      \"@id\": \"schema:InvestmentOrDeposit\",\n      \"rdfs:comment\": \"An investment product managed or offered by Thrivent\"\n    },\n    \"BankingProduct\": {\n      \"@id\": \"schema:BankAccount\",\n      \"rdfs:comment\": \"A banking product offered through Thrivent Bank\"\
  \n    },\n    \"CharitableProgram\": {\n      \"@id\": \"schema:DonateAction\",\n      \"rdfs:comment\": \"A Thrivent charitable giving or generosity program\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"areaServed\": \"schema:areaServed\",\n    \"category\": \"schema:category\",\n\n    \"annualFeeMin\": {\n      \"@id\": \"thrivent:annualFeeMin\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"annualFeeMax\": {\n      \"@id\": \"thrivent:annualFeeMax\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"minimumInvestment\": {\n      \"@id\": \"thrivent:minimumInvestment\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"feeRangeMin\": {\n      \"@id\": \"thrivent:feeRangeMin\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"feeRangeMax\": {\n      \"@id\": \"thrivent:feeRangeMax\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"assetsUnderManagement\": {\n    \
  \  \"@id\": \"thrivent:assetsUnderManagement\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"memberCount\": {\n      \"@id\": \"thrivent:memberCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"employeeCount\": {\n      \"@id\": \"thrivent:employeeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"isMemberOnly\": {\n      \"@id\": \"thrivent:isMemberOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isFeeBased\": {\n      \"@id\": \"thrivent:isFeeBased\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requiresMinimumInvestment\": {\n      \"@id\": \"thrivent:requiresMinimumInvestment\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"planningServices\": {\n      \"@id\": \"thrivent:hasPlanningServices\",\n      \"@container\": \"@list\"\n    },\n    \"insuranceProducts\": {\n      \"@id\": \"thrivent:hasInsuranceProducts\",\n      \"@container\": \"@list\"\n    },\n    \"investmentProducts\": {\n      \"@id\": \"thrivent:hasInvestmentProducts\",\n      \"\
  @container\": \"@list\"\n    },\n    \"bankingProducts\": {\n      \"@id\": \"thrivent:hasBankingProducts\",\n      \"@container\": \"@list\"\n    },\n    \"generosityPrograms\": {\n      \"@id\": \"thrivent:hasGenerosityPrograms\",\n      \"@container\": \"@list\"\n    },\n\n    \"legalName\": \"schema:legalName\",\n    \"foundingDate\": \"schema:foundingDate\",\n    \"headquarters\": \"schema:location\",\n    \"nonprofitStatus\": \"schema:nonprofitStatus\",\n    \"Fortune500\": \"schema:award\",\n\n    \"MoneyCoaching\": \"thrivent:ServiceMoneyCoaching\",\n    \"DedicatedPlanningServices\": \"thrivent:ServiceDedicatedPlanning\",\n    \"ManagedAccountsProgram\": \"thrivent:ServiceManagedAccounts\",\n    \"TrustServices\": \"thrivent:ServiceTrust\",\n    \"ThriventBank\": \"thrivent:EntityThriventBank\",\n    \"ThriventCharitable\": \"thrivent:EntityThriventCharitable\",\n    \"ThriventActionTeams\": \"thrivent:ProgramActionTeams\",\n    \"ChoiceDollars\": \"thrivent:BenefitChoiceDollars\"\
  ,\n    \"DonorAdvisedFund\": \"thrivent:ProductDonorAdvisedFund\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thrivent-financial-for-lutherans/refs/heads/main/json-ld/thrivent-financial-for-lutherans-context.jsonld
tags:
- Annuities
- Banking
- ETFs
- Financial Advice
- Financial Planning
- Fortune 500
- Generosity
- Insurance
- Investments
- Mutual Funds
- Non Profit
- JSON-LD
- Linked Data
- Semantic Web
---
