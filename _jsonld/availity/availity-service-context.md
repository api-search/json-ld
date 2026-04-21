---
class_count: 8
classes:
- ServiceReviewResponse
- ServiceReviewRequest
- IsAuthRequiredResponse
- IsAuthRequiredRequest
- ServiceReviewList
- AttachmentStatusResponse
- AsyncJobResponse
- AttachmentRequest
context_file: json-ld/availity-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Availity Service from availity.
layout: jsonld
name: Availity Service Context
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
  name: id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: certificationNumber
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: payerId
  type: string
- container: ''
  name: requestType
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
  name: serviceInformation
  type: reference
- container: set
  name: procedureCodes
  type: string
- container: set
  name: diagnosisCodes
  type: string
- container: ''
  name: serviceFromDate
  type: date
- container: ''
  name: serviceToDate
  type: date
- container: ''
  name: authRequired
  type: string
- container: ''
  name: payerMessage
  type: string
- container: ''
  name: serviceReview
  type: reference
- container: ''
  name: procedureCode
  type: string
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
  name: patient
  type: reference
- container: set
  name: attachments
  type: reference
- container: ''
  name: contentType
  type: string
- container: ''
  name: title
  type: string
property_count: 30
provider_name: availity
provider_slug: availity
slug: availity-service-context
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
