---
class_count: 3
classes:
- FinancialProduct
- InsuranceAgency
- FinancialService
context_file: json-ld/symetra-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/symetra-financial/refs/heads/main/json-ld/symetra-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Symetra Financial from Symetra Financial.
layout: jsonld
name: Symetra Financial Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: symetra
  uri: https://www.symetra.com/vocab#
properties:
- container: ''
  name: Annuity
  type: reference
- container: ''
  name: FixedAnnuity
  type: reference
- container: ''
  name: FixedIndexedAnnuity
  type: reference
- container: ''
  name: RegisteredIndexLinkedAnnuity
  type: reference
- container: ''
  name: IncomeAnnuity
  type: reference
- container: ''
  name: LifeInsurancePolicy
  type: reference
- container: ''
  name: TermLifeInsurance
  type: reference
- container: ''
  name: PermanentLifeInsurance
  type: reference
- container: ''
  name: SwiftTerm
  type: reference
- container: ''
  name: EmployeeBenefits
  type: reference
- container: ''
  name: MedicalStopLoss
  type: reference
- container: ''
  name: GroupLifeInsurance
  type: reference
- container: ''
  name: DisabilityIncome
  type: reference
- container: ''
  name: SupplementalHealth
  type: reference
- container: ''
  name: EvidenceOfInsurability
  type: reference
- container: ''
  name: Enrollment
  type: reference
- container: ''
  name: Underwriting
  type: reference
- container: ''
  name: PolicyIllustration
  type: reference
- container: ''
  name: InForcePolicy
  type: reference
- container: ''
  name: Claim
  type: reference
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: terminationDate
  type: date
- container: ''
  name: premium
  type: decimal
- container: ''
  name: benefitAmount
  type: decimal
- container: ''
  name: coverageTier
  type: string
- container: ''
  name: groupNumber
  type: string
- container: ''
  name: memberID
  type: string
- container: ''
  name: claimNumber
  type: string
- container: ''
  name: claimStatus
  type: string
- container: ''
  name: accumulationValue
  type: decimal
- container: ''
  name: surrenderValue
  type: decimal
- container: ''
  name: indexStrategy
  type: string
- container: ''
  name: participationRate
  type: decimal
- container: ''
  name: capRate
  type: decimal
- container: ''
  name: bufferRate
  type: decimal
- container: ''
  name: stopLossThreshold
  type: decimal
property_count: 37
provider_name: Symetra Financial
provider_slug: symetra-financial
slug: symetra-financial-context
source_filename: symetra-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"symetra\": \"https://www.symetra.com/vocab#\",\n\n    \"FinancialProduct\": \"schema:FinancialProduct\",\n    \"InsuranceAgency\": \"schema:InsuranceAgency\",\n    \"FinancialService\": \"schema:FinancialService\",\n\n    \"Annuity\": {\n      \"@id\": \"symetra:Annuity\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"A financial product providing a stream of payments, typically for retirement income.\"\n    },\n    \"FixedAnnuity\": {\n      \"@id\": \"symetra:FixedAnnuity\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:Annuity\" }\n    },\n    \"FixedIndexedAnnuity\": {\n      \"@id\": \"symetra:FixedIndexedAnnuity\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:Annuity\" }\n    },\n    \"RegisteredIndexLinkedAnnuity\"\
  : {\n      \"@id\": \"symetra:RegisteredIndexLinkedAnnuity\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:Annuity\" },\n      \"skos:altLabel\": \"RILA\"\n    },\n    \"IncomeAnnuity\": {\n      \"@id\": \"symetra:IncomeAnnuity\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:Annuity\" }\n    },\n\n    \"LifeInsurancePolicy\": {\n      \"@id\": \"symetra:LifeInsurancePolicy\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:FinancialProduct\" }\n    },\n    \"TermLifeInsurance\": {\n      \"@id\": \"symetra:TermLifeInsurance\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:LifeInsurancePolicy\" }\n    },\n    \"PermanentLifeInsurance\": {\n      \"@id\": \"symetra:PermanentLifeInsurance\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:LifeInsurancePolicy\" }\n    },\n    \"SwiftTerm\": {\n      \"@id\": \"symetra:SwiftTerm\",\n      \"@type\"\
  : \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:TermLifeInsurance\" },\n      \"skos:definition\": \"Symetra's instant-issue online term life insurance product.\"\n    },\n\n    \"EmployeeBenefits\": {\n      \"@id\": \"symetra:EmployeeBenefits\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:FinancialProduct\" }\n    },\n    \"MedicalStopLoss\": {\n      \"@id\": \"symetra:MedicalStopLoss\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:EmployeeBenefits\" },\n      \"skos:definition\": \"Insurance protecting self-funded employers against catastrophic medical claims.\"\n    },\n    \"GroupLifeInsurance\": {\n      \"@id\": \"symetra:GroupLifeInsurance\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:EmployeeBenefits\" }\n    },\n    \"DisabilityIncome\": {\n      \"@id\": \"symetra:DisabilityIncome\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:EmployeeBenefits\"\
  \ }\n    },\n    \"SupplementalHealth\": {\n      \"@id\": \"symetra:SupplementalHealth\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"symetra:EmployeeBenefits\" }\n    },\n\n    \"EvidenceOfInsurability\": {\n      \"@id\": \"symetra:EvidenceOfInsurability\",\n      \"@type\": \"@id\",\n      \"skos:altLabel\": \"EOI\"\n    },\n    \"Enrollment\": {\n      \"@id\": \"symetra:Enrollment\",\n      \"@type\": \"@id\"\n    },\n    \"Underwriting\": {\n      \"@id\": \"symetra:Underwriting\",\n      \"@type\": \"@id\"\n    },\n    \"PolicyIllustration\": {\n      \"@id\": \"symetra:PolicyIllustration\",\n      \"@type\": \"@id\"\n    },\n    \"InForcePolicy\": {\n      \"@id\": \"symetra:InForcePolicy\",\n      \"@type\": \"@id\"\n    },\n    \"Claim\": {\n      \"@id\": \"symetra:Claim\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:PayAction\" }\n    },\n\n    \"policyNumber\": { \"@id\": \"symetra:policyNumber\", \"@type\": \"xsd:string\"\
  \ },\n    \"effectiveDate\": { \"@id\": \"symetra:effectiveDate\", \"@type\": \"xsd:date\" },\n    \"terminationDate\": { \"@id\": \"symetra:terminationDate\", \"@type\": \"xsd:date\" },\n    \"premium\": { \"@id\": \"symetra:premium\", \"@type\": \"xsd:decimal\" },\n    \"benefitAmount\": { \"@id\": \"symetra:benefitAmount\", \"@type\": \"xsd:decimal\" },\n    \"coverageTier\": { \"@id\": \"symetra:coverageTier\", \"@type\": \"xsd:string\" },\n    \"groupNumber\": { \"@id\": \"symetra:groupNumber\", \"@type\": \"xsd:string\" },\n    \"memberID\": { \"@id\": \"symetra:memberID\", \"@type\": \"xsd:string\" },\n    \"claimNumber\": { \"@id\": \"symetra:claimNumber\", \"@type\": \"xsd:string\" },\n    \"claimStatus\": { \"@id\": \"symetra:claimStatus\", \"@type\": \"xsd:string\" },\n    \"accumulationValue\": { \"@id\": \"symetra:accumulationValue\", \"@type\": \"xsd:decimal\" },\n    \"surrenderValue\": { \"@id\": \"symetra:surrenderValue\", \"@type\": \"xsd:decimal\" },\n    \"indexStrategy\"\
  : { \"@id\": \"symetra:indexStrategy\", \"@type\": \"xsd:string\" },\n    \"participationRate\": { \"@id\": \"symetra:participationRate\", \"@type\": \"xsd:decimal\" },\n    \"capRate\": { \"@id\": \"symetra:capRate\", \"@type\": \"xsd:decimal\" },\n    \"bufferRate\": { \"@id\": \"symetra:bufferRate\", \"@type\": \"xsd:decimal\" },\n    \"stopLossThreshold\": { \"@id\": \"symetra:stopLossThreshold\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/symetra-financial/refs/heads/main/json-ld/symetra-financial-context.jsonld
tags:
- Annuities
- Benefits
- Employee Benefits
- Financial Services
- Insurance
- Life Insurance
- Stop Loss
- JSON-LD
- Linked Data
- Semantic Web
---
