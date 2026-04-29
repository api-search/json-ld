---
class_count: 6
classes:
- EdgarCompanySubmission
- GaapAccountingStandard
- XbrlFinancialFact
- description
- name
- url
context_file: json-ld/accounting-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/json-ld/accounting-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Accounting Standards from Accounting Standards.
layout: jsonld
name: Accounting Standards Context
namespaces:
- prefix: acct
  uri: https://xbrl.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: accessionNumber
  type: string
- container: ''
  name: accn
  type: string
- container: ''
  name: applicability
  type: string
- container: ''
  name: cik
  type: string
- container: ''
  name: concept
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: end
  type: date
- container: ''
  name: entityName
  type: string
- container: ''
  name: entityType
  type: string
- container: set
  name: exchanges
  type: string
- container: set
  name: facts
  type: string
- container: ''
  name: filed
  type: date
- container: set
  name: filingDate
  type: date
- container: ''
  name: filings
  type: string
- container: ''
  name: fiscalYearEnd
  type: string
- container: set
  name: form
  type: string
- container: ''
  name: fp
  type: string
- container: ''
  name: frame
  type: string
- container: ''
  name: fy
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: issuedDate
  type: date
- container: ''
  name: label
  type: string
- container: set
  name: primaryDocument
  type: string
- container: ''
  name: recent
  type: string
- container: set
  name: relatedTopics
  type: string
- container: ''
  name: sic
  type: string
- container: ''
  name: sicDescription
  type: string
- container: ''
  name: start
  type: date
- container: ''
  name: stateOfIncorporation
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: taxonomy
  type: string
- container: set
  name: tickers
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: topicName
  type: string
- container: ''
  name: unit
  type: string
- container: set
  name: units
  type: string
- container: ''
  name: val
  type: decimal
- container: ''
  name: website
  type: reference
property_count: 39
provider_name: Accounting Standards
provider_slug: accounting-standards
slug: accounting-standards-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acct\": \"https://xbrl.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EdgarCompanySubmission\": \"acct:EdgarCompanySubmission\",\n    \"GaapAccountingStandard\": \"acct:GaapAccountingStandard\",\n    \"XbrlFinancialFact\": \"acct:XbrlFinancialFact\",\n    \"accessionNumber\": {\n      \"@id\": \"acct:accessionNumber\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accn\": {\n      \"@id\": \"acct:accn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicability\": {\n      \"@id\": \"acct:applicability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cik\": {\n      \"@id\": \"acct:cik\",\n      \"@type\": \"xsd:string\"\n    },\n    \"concept\": {\n      \"@id\": \"acct:concept\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\"\
  ,\n    \"effectiveDate\": {\n      \"@id\": \"acct:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"end\": {\n      \"@id\": \"acct:end\",\n      \"@type\": \"xsd:date\"\n    },\n    \"entityName\": {\n      \"@id\": \"acct:entityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"acct:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exchanges\": {\n      \"@id\": \"acct:exchanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facts\": {\n      \"@id\": \"acct:facts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filed\": {\n      \"@id\": \"acct:filed\",\n      \"@type\": \"xsd:date\"\n    },\n    \"filingDate\": {\n      \"@id\": \"acct:filingDate\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:date\"\n    },\n    \"filings\": {\n      \"@id\": \"acct:filings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fiscalYearEnd\": {\n      \"\
  @id\": \"acct:fiscalYearEnd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"form\": {\n      \"@id\": \"acct:form\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fp\": {\n      \"@id\": \"acct:fp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frame\": {\n      \"@id\": \"acct:frame\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fy\": {\n      \"@id\": \"acct:fy\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"acct:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuedDate\": {\n      \"@id\": \"acct:issuedDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"label\": {\n      \"@id\": \"acct:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"primaryDocument\": {\n      \"@id\": \"acct:primaryDocument\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recent\": {\n      \"@id\": \"acct:recent\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"relatedTopics\": {\n      \"@id\": \"acct:relatedTopics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sic\": {\n      \"@id\": \"acct:sic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sicDescription\": {\n      \"@id\": \"acct:sicDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"acct:start\",\n      \"@type\": \"xsd:date\"\n    },\n    \"stateOfIncorporation\": {\n      \"@id\": \"acct:stateOfIncorporation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"acct:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxonomy\": {\n      \"@id\": \"acct:taxonomy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tickers\": {\n      \"@id\": \"acct:tickers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"acct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"acct:topic\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"topicName\": {\n      \"@id\": \"acct:topicName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"acct:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"units\": {\n      \"@id\": \"acct:units\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"val\": {\n      \"@id\": \"acct:val\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"website\": {\n      \"@id\": \"acct:website\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/json-ld/accounting-standards-context.jsonld
tags:
- Accounting Standards
- Finance
- GAAP
- IFRS
- XBRL
- Financial Reporting
- SEC
- FASB
- JSON-LD
- Linked Data
- Semantic Web
---
