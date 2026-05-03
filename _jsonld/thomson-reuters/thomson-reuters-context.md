---
class_count: 22
classes:
- LegalDocument
- Case
- Statute
- Regulation
- TaxDocument
- RiskProfile
- IdentityRecord
- Organization
- LegalMatter
- Invoice
- ComplianceCheck
- AdverseMediaResult
- jurisdiction
- citation
- filingDate
- caseNumber
- courtName
- taxYear
- taxJurisdiction
- riskScore
- kycStatus
- amlStatus
context_file: json-ld/thomson-reuters-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thomson-reuters/refs/heads/main/json-ld/thomson-reuters-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thomson Reuters from Thomson Reuters.
layout: jsonld
name: Thomson Reuters Context
namespaces:
- prefix: tr
  uri: https://developers.thomsonreuters.com/vocab#
properties: []
property_count: 0
provider_name: Thomson Reuters
provider_slug: thomson-reuters
slug: thomson-reuters-context
source_filename: thomson-reuters-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tr\": \"https://developers.thomsonreuters.com/vocab#\",\n    \"LegalDocument\": \"LegalDocument\",\n    \"Case\": \"tr:LegalCase\",\n    \"Statute\": \"tr:Statute\",\n    \"Regulation\": \"tr:Regulation\",\n    \"TaxDocument\": \"tr:TaxDocument\",\n    \"RiskProfile\": \"tr:RiskProfile\",\n    \"IdentityRecord\": \"Person\",\n    \"Organization\": \"Organization\",\n    \"LegalMatter\": \"tr:LegalMatter\",\n    \"Invoice\": \"Invoice\",\n    \"ComplianceCheck\": \"tr:ComplianceCheck\",\n    \"AdverseMediaResult\": \"tr:AdverseMediaResult\",\n    \"jurisdiction\": \"tr:jurisdiction\",\n    \"citation\": \"tr:citation\",\n    \"filingDate\": \"dateCreated\",\n    \"caseNumber\": \"tr:caseNumber\",\n    \"courtName\": \"tr:court\",\n    \"taxYear\": \"tr:taxYear\",\n    \"taxJurisdiction\": \"tr:taxJurisdiction\",\n    \"riskScore\": \"tr:riskScore\",\n    \"kycStatus\": \"tr:kycStatus\",\n    \"amlStatus\"\
  : \"tr:amlStatus\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thomson-reuters/refs/heads/main/json-ld/thomson-reuters-context.jsonld
tags:
- Legal
- Tax
- Finance
- Risk
- Fraud
- Compliance
- Data
- JSON-LD
- Linked Data
- Semantic Web
---
