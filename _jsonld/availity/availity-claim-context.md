---
class_count: 9
classes:
- ClaimStatusRequest
- ClaimAttachmentResponse
- DetailSearchRequest
- ClaimStatusResponse
- SummarySearchRequest
- AsyncJobResponse
- SearchBy276Request
- ClaimStatusList
- ClaimAttachmentRequest
context_file: json-ld/availity-claim-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-claim-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Availity Claim from availity.
layout: jsonld
name: Availity Claim Context
namespaces:
- prefix: availity
  uri: https://availity.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: payerId
  type: string
- container: ''
  name: provider
  type: reference
- container: ''
  name: npi
  type: string
- container: ''
  name: taxId
  type: string
- container: ''
  name: subscriber
  type: reference
- container: ''
  name: memberId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: claimNumber
  type: string
- container: ''
  name: fromDate
  type: date
- container: ''
  name: toDate
  type: date
- container: ''
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: controlNumber
  type: string
- container: ''
  name: requestType
  type: string
- container: ''
  name: providerTaxId
  type: string
- container: ''
  name: providerNpi
  type: string
- container: ''
  name: processedDate
  type: date
- container: ''
  name: traceIds
  type: reference
- container: ''
  name: AVAILITYTraceId
  type: string
- container: ''
  name: PAYERTraceId
  type: string
- container: ''
  name: amounts
  type: reference
- container: ''
  name: billed
  type: decimal
- container: ''
  name: allowed
  type: decimal
- container: ''
  name: paid
  type: decimal
- container: ''
  name: patientResponsibility
  type: decimal
- container: ''
  name: completeCode
  type: string
- container: set
  name: errors
  type: reference
- container: ''
  name: code
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: checkNumber
  type: string
- container: ''
  name: requestedStatus
  type: string
- container: ''
  name: patientLastName
  type: string
- container: ''
  name: patientFirstName
  type: string
- container: ''
  name: patientBirthDate
  type: date
- container: ''
  name: providerLastName
  type: string
- container: ''
  name: patientSameAsSubscriber
  type: boolean
- container: set
  name: data
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: attachmentType
  type: string
- container: set
  name: attachments
  type: reference
- container: ''
  name: contentType
  type: string
- container: ''
  name: title
  type: string
property_count: 45
provider_name: availity
provider_slug: availity
slug: availity-claim-context
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
