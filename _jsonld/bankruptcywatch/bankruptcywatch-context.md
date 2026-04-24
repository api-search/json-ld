---
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
