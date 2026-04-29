---
api_specs:
- filename: bankruptcywatch-pacer-api-openapi.yml
  format: yaml
  label: BankruptcyWatch PACER API
  slug: pacer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/openapi/bankruptcywatch-pacer-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/bankruptcywatch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/json-ld/bankruptcywatch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bankruptcywatch from BankruptcyWatch.
layout: jsonld
name: Bankruptcywatch Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bwapi
  uri: https://api-evangelist.github.io/bankruptcywatch/vocab#
properties:
- container: ''
  name: Case
  type: ''
- container: ''
  name: caseId
  type: string
- container: ''
  name: caseNumber
  type: string
- container: ''
  name: debtorName
  type: string
- container: ''
  name: chapter
  type: string
- container: ''
  name: district
  type: string
- container: ''
  name: dateFiled
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: judge
  type: string
- container: ''
  name: trustee
  type: string
- container: ''
  name: assets
  type: string
- container: ''
  name: liabilities
  type: string
- container: ''
  name: CaseSearchResponse
  type: ''
- container: ''
  name: cases
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: DocketEntry
  type: ''
- container: ''
  name: entryId
  type: string
- container: ''
  name: entryNumber
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: documentUrl
  type: string
- container: ''
  name: filer
  type: string
- container: ''
  name: DocketResponse
  type: ''
- container: ''
  name: entries
  type: string
- container: ''
  name: Claim
  type: ''
- container: ''
  name: claimId
  type: string
- container: ''
  name: claimNumber
  type: string
- container: ''
  name: creditorName
  type: string
- container: ''
  name: claimAmount
  type: decimal
- container: ''
  name: securedAmount
  type: decimal
- container: ''
  name: unsecuredAmount
  type: decimal
- container: ''
  name: ClaimsResponse
  type: ''
- container: ''
  name: claims
  type: string
- container: ''
  name: ProofOfClaimRequest
  type: ''
- container: ''
  name: creditorAddress
  type: string
- container: ''
  name: basisForClaim
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: attachmentUrls
  type: string
- container: ''
  name: ProofOfClaimResponse
  type: ''
- container: ''
  name: confirmationNumber
  type: string
- container: ''
  name: filedAt
  type: string
- container: ''
  name: MonitorRequest
  type: ''
- container: ''
  name: monitorType
  type: string
- container: ''
  name: criteria
  type: string
- container: ''
  name: notificationEmail
  type: string
- container: ''
  name: webhookUrl
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: Monitor
  type: ''
- container: ''
  name: monitorId
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: lastTriggeredAt
  type: string
- container: ''
  name: alertCount
  type: integer
- container: ''
  name: MonitorListResponse
  type: ''
- container: ''
  name: monitors
  type: string
- container: ''
  name: ErrorResponse
  type: ''
- container: ''
  name: errorCode
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: requestId
  type: string
property_count: 59
provider_name: BankruptcyWatch
provider_slug: bankruptcywatch
slug: bankruptcywatch-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bwapi\": \"https://api-evangelist.github.io/bankruptcywatch/vocab#\",\n    \"Case\": {\n      \"@id\": \"bwapi:Case\"\n    },\n    \"caseId\": {\n      \"@id\": \"bwapi:caseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caseNumber\": {\n      \"@id\": \"bwapi:caseNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"debtorName\": {\n      \"@id\": \"bwapi:debtorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chapter\": {\n      \"@id\": \"bwapi:chapter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"district\": {\n      \"@id\": \"bwapi:district\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateFiled\": {\n      \"@id\": \"bwapi:dateFiled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"bwapi:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"judge\": {\n      \"@id\"\
  : \"bwapi:judge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trustee\": {\n      \"@id\": \"bwapi:trustee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assets\": {\n      \"@id\": \"bwapi:assets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liabilities\": {\n      \"@id\": \"bwapi:liabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CaseSearchResponse\": {\n      \"@id\": \"bwapi:CaseSearchResponse\"\n    },\n    \"cases\": {\n      \"@id\": \"bwapi:cases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"bwapi:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"bwapi:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"bwapi:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DocketEntry\": {\n      \"@id\": \"bwapi:DocketEntry\"\n    },\n    \"entryId\": {\n      \"@id\": \"bwapi:entryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  entryNumber\": {\n      \"@id\": \"bwapi:entryNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"bwapi:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentUrl\": {\n      \"@id\": \"bwapi:documentUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filer\": {\n      \"@id\": \"bwapi:filer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DocketResponse\": {\n      \"@id\": \"bwapi:DocketResponse\"\n    },\n    \"entries\": {\n      \"@id\": \"bwapi:entries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Claim\": {\n      \"@id\": \"bwapi:Claim\"\n    },\n    \"claimId\": {\n      \"@id\": \"bwapi:claimId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimNumber\": {\n      \"@id\": \"bwapi:claimNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorName\": {\n      \"@id\": \"bwapi:creditorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"claimAmount\": {\n      \"@id\": \"bwapi:claimAmount\",\n \
  \     \"@type\": \"xsd:decimal\"\n    },\n    \"securedAmount\": {\n      \"@id\": \"bwapi:securedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unsecuredAmount\": {\n      \"@id\": \"bwapi:unsecuredAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ClaimsResponse\": {\n      \"@id\": \"bwapi:ClaimsResponse\"\n    },\n    \"claims\": {\n      \"@id\": \"bwapi:claims\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProofOfClaimRequest\": {\n      \"@id\": \"bwapi:ProofOfClaimRequest\"\n    },\n    \"creditorAddress\": {\n      \"@id\": \"bwapi:creditorAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basisForClaim\": {\n      \"@id\": \"bwapi:basisForClaim\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"bwapi:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachmentUrls\": {\n      \"@id\": \"bwapi:attachmentUrls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProofOfClaimResponse\": {\n      \"\
  @id\": \"bwapi:ProofOfClaimResponse\"\n    },\n    \"confirmationNumber\": {\n      \"@id\": \"bwapi:confirmationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filedAt\": {\n      \"@id\": \"bwapi:filedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MonitorRequest\": {\n      \"@id\": \"bwapi:MonitorRequest\"\n    },\n    \"monitorType\": {\n      \"@id\": \"bwapi:monitorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"criteria\": {\n      \"@id\": \"bwapi:criteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationEmail\": {\n      \"@id\": \"bwapi:notificationEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webhookUrl\": {\n      \"@id\": \"bwapi:webhookUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"bwapi:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Monitor\": {\n      \"@id\": \"bwapi:Monitor\"\n    },\n    \"monitorId\": {\n      \"@id\": \"bwapi:monitorId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"createdAt\": {\n      \"@id\": \"bwapi:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTriggeredAt\": {\n      \"@id\": \"bwapi:lastTriggeredAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertCount\": {\n      \"@id\": \"bwapi:alertCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MonitorListResponse\": {\n      \"@id\": \"bwapi:MonitorListResponse\"\n    },\n    \"monitors\": {\n      \"@id\": \"bwapi:monitors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"bwapi:ErrorResponse\"\n    },\n    \"errorCode\": {\n      \"@id\": \"bwapi:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"bwapi:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"bwapi:requestId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bankruptcywatch/refs/heads/main/json-ld/bankruptcywatch-context.jsonld
tags:
- Bankruptcy
- Compliance
- Court Data
- Legal
- Lending
- PACER
- JSON-LD
- Linked Data
- Semantic Web
---
