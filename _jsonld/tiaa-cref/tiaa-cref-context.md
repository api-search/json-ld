---
class_count: 21
classes:
- name
- description
- url
- provider
- TIAATraditional
- CREFStock
- CREFBondMarket
- CREFSocialChoice
- CREFGlobalEquities
- CREFEquityIndex
- CREFMoneyMarket
- CREFInflationLinkedBond
- TIAAMyChoiceMYGA
- TIAASecureIncomeAccount
- TIAARetirePlus
- NuveenLifecycleIncome
- Fortune100
- legalName
- foundingDate
- headquarters
- nonprofit
context_file: json-ld/tiaa-cref-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-ld/tiaa-cref-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tiaa Cref from TIAA-CREF.
layout: jsonld
name: Tiaa Cref Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: tiaa
  uri: https://www.tiaa.org/vocab#
properties:
- container: ''
  name: RetirementPlan
  type: ''
- container: ''
  name: AnnuityProduct
  type: ''
- container: ''
  name: InvestmentAccount
  type: ''
- container: ''
  name: PlanSponsor
  type: ''
- container: ''
  name: PlanParticipant
  type: ''
- container: ''
  name: LifetimeIncome
  type: ''
- container: ''
  name: planType
  type: ''
- container: ''
  name: accountBalance
  type: decimal
- container: ''
  name: annualContribution
  type: decimal
- container: ''
  name: guaranteedMinimumRate
  type: decimal
- container: ''
  name: creditedRate
  type: decimal
- container: ''
  name: assetsUnderManagement
  type: decimal
- container: ''
  name: participantCount
  type: integer
- container: ''
  name: institutionalClientCount
  type: integer
- container: ''
  name: targetRetirementYear
  type: integer
- container: ''
  name: isLifetimeIncome
  type: boolean
- container: ''
  name: isParticipating
  type: boolean
- container: ''
  name: isVariableAnnuity
  type: boolean
- container: ''
  name: isTaxDeferred
  type: boolean
- container: ''
  name: isESG
  type: boolean
- container: list
  name: retirementAccounts
  type: ''
- container: list
  name: investmentOptions
  type: ''
property_count: 22
provider_name: TIAA-CREF
provider_slug: tiaa-cref
slug: tiaa-cref-context
source_filename: tiaa-cref-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.tiaa.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"tiaa\": \"https://www.tiaa.org/vocab#\",\n\n    \"RetirementPlan\": {\n      \"@id\": \"tiaa:RetirementPlan\",\n      \"rdfs:comment\": \"A tax-advantaged retirement savings plan administered by TIAA\"\n    },\n    \"AnnuityProduct\": {\n      \"@id\": \"tiaa:AnnuityProduct\",\n      \"rdfs:comment\": \"An annuity contract for retirement accumulation or income\"\n    },\n    \"InvestmentAccount\": {\n      \"@id\": \"tiaa:InvestmentAccount\",\n      \"rdfs:comment\": \"A CREF or mutual fund investment account within a retirement plan\"\n    },\n    \"PlanSponsor\": {\n      \"@id\": \"tiaa:PlanSponsor\",\n      \"rdfs:comment\": \"An institution sponsoring a retirement plan administered\
  \ by TIAA\"\n    },\n    \"PlanParticipant\": {\n      \"@id\": \"tiaa:PlanParticipant\",\n      \"rdfs:comment\": \"An individual enrolled in a TIAA-administered retirement plan\"\n    },\n    \"LifetimeIncome\": {\n      \"@id\": \"tiaa:LifetimeIncome\",\n      \"rdfs:comment\": \"A guaranteed income stream lasting the participant's entire lifetime\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n\n    \"planType\": {\n      \"@id\": \"tiaa:planType\",\n      \"rdfs:comment\": \"Retirement plan type code: 403(b), 457(b), 401(k), IRA\"\n    },\n    \"accountBalance\": {\n      \"@id\": \"tiaa:accountBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"annualContribution\": {\n      \"@id\": \"tiaa:annualContribution\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"guaranteedMinimumRate\": {\n      \"@id\": \"tiaa:guaranteedMinimumRate\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"creditedRate\": {\n      \"@id\": \"tiaa:creditedRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"assetsUnderManagement\": {\n      \"@id\": \"tiaa:assetsUnderManagement\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"participantCount\": {\n      \"@id\": \"tiaa:participantCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"institutionalClientCount\": {\n      \"@id\": \"tiaa:institutionalClientCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"targetRetirementYear\": {\n      \"@id\": \"tiaa:targetRetirementYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isLifetimeIncome\": {\n      \"@id\": \"tiaa:isLifetimeIncome\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isParticipating\": {\n      \"@id\": \"tiaa:isParticipating\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isVariableAnnuity\": {\n      \"@id\": \"tiaa:isVariableAnnuity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isTaxDeferred\": {\n      \"@id\": \"tiaa:isTaxDeferred\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isESG\": {\n      \"@id\": \"tiaa:isESG\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"retirementAccounts\": {\n      \"@id\": \"tiaa:hasRetirementAccounts\",\n      \"@container\": \"@list\"\n    },\n    \"investmentOptions\": {\n      \"@id\": \"tiaa:hasInvestmentOptions\",\n      \"@container\": \"@list\"\n    },\n\n    \"TIAATraditional\": \"tiaa:ProductTIAATraditional\",\n    \"CREFStock\": \"tiaa:AccountCREFStock\",\n    \"CREFBondMarket\": \"tiaa:AccountCREFBondMarket\",\n    \"CREFSocialChoice\": \"tiaa:AccountCREFSocialChoice\",\n    \"CREFGlobalEquities\": \"tiaa:AccountCREFGlobalEquities\",\n    \"CREFEquityIndex\": \"tiaa:AccountCREFEquityIndex\",\n    \"CREFMoneyMarket\": \"tiaa:AccountCREFMoneyMarket\",\n    \"CREFInflationLinkedBond\": \"tiaa:AccountCREFInflationLinkedBond\",\n    \"TIAAMyChoiceMYGA\": \"tiaa:ProductTIAAMyChoiceMYGA\",\n    \"TIAASecureIncomeAccount\": \"tiaa:ProductTIAASecureIncomeAccount\",\n  \
  \  \"TIAARetirePlus\": \"tiaa:SolutionTIAARetirePlus\",\n    \"NuveenLifecycleIncome\": \"tiaa:ProductNuveenLifecycleIncome\",\n\n    \"Fortune100\": \"schema:award\",\n    \"legalName\": \"schema:legalName\",\n    \"foundingDate\": \"schema:foundingDate\",\n    \"headquarters\": \"schema:location\",\n    \"nonprofit\": \"schema:nonprofitStatus\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-ld/tiaa-cref-context.jsonld
tags:
- 403b
- Annuities
- Asset Management
- Fortune 100
- Higher Education
- Institutional
- Insurance
- Investments
- Non Profit
- Nuveen
- Retirement
- TIAA
- JSON-LD
- Linked Data
- Semantic Web
---
