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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"availity\": \"https://availity.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ServiceReviewResponse\": \"availity:ServiceReviewResponse\",\n    \"ServiceReviewRequest\": \"availity:ServiceReviewRequest\",\n    \"IsAuthRequiredResponse\": \"availity:IsAuthRequiredResponse\",\n    \"IsAuthRequiredRequest\": \"availity:IsAuthRequiredRequest\",\n    \"ServiceReviewList\": \"availity:ServiceReviewList\",\n    \"AttachmentStatusResponse\": \"availity:AttachmentStatusResponse\",\n    \"AsyncJobResponse\": \"availity:AsyncJobResponse\",\n    \"AttachmentRequest\": \"availity:AttachmentRequest\",\n    \"id\": {\n      \"@id\": \"availity:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"availity:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificationNumber\": {\n  \
  \    \"@id\": \"availity:certificationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"availity:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"availity:expirationDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"payerId\": {\n      \"@id\": \"availity:payerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestType\": {\n      \"@id\": \"availity:requestType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"availity:provider\",\n      \"@type\": \"@id\"\n    },\n    \"npi\": {\n      \"@id\": \"availity:npi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"availity:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriber\": {\n      \"@id\": \"availity:subscriber\",\n      \"@type\": \"@id\"\n    },\n    \"memberId\": {\n      \"@id\": \"availity:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  firstName\": {\n      \"@id\": \"availity:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"availity:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceInformation\": {\n      \"@id\": \"availity:serviceInformation\",\n      \"@type\": \"@id\"\n    },\n    \"procedureCodes\": {\n      \"@id\": \"availity:procedureCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diagnosisCodes\": {\n      \"@id\": \"availity:diagnosisCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceFromDate\": {\n      \"@id\": \"availity:serviceFromDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"serviceToDate\": {\n      \"@id\": \"availity:serviceToDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"authRequired\": {\n      \"@id\": \"availity:authRequired\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payerMessage\": {\n      \"@id\": \"availity:payerMessage\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceReview\": {\n      \"@id\": \"availity:serviceReview\",\n      \"@type\": \"@id\"\n    },\n    \"procedureCode\": {\n      \"@id\": \"availity:procedureCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"availity:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"availity:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"availity:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"patient\": {\n      \"@id\": \"availity:patient\",\n      \"@type\": \"@id\"\n    },\n    \"attachments\": {\n      \"@id\": \"availity:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"contentType\": {\n      \"@id\": \"availity:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"availity:title\",\n      \"@type\": \"xsd:string\"\n \
  \   }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-service-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
