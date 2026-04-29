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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"availity\": \"https://availity.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ClaimStatusRequest\": \"availity:ClaimStatusRequest\",\n    \"ClaimAttachmentResponse\": \"availity:ClaimAttachmentResponse\",\n    \"DetailSearchRequest\": \"availity:DetailSearchRequest\",\n    \"ClaimStatusResponse\": \"availity:ClaimStatusResponse\",\n    \"SummarySearchRequest\": \"availity:SummarySearchRequest\",\n    \"AsyncJobResponse\": \"availity:AsyncJobResponse\",\n    \"SearchBy276Request\": \"availity:SearchBy276Request\",\n    \"ClaimStatusList\": \"availity:ClaimStatusList\",\n    \"ClaimAttachmentRequest\": \"availity:ClaimAttachmentRequest\",\n    \"payerId\": {\n      \"@id\": \"availity:payerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"availity:provider\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"npi\": {\n      \"@id\": \"availity:npi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxId\": {\n      \"@id\": \"availity:taxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriber\": {\n      \"@id\": \"availity:subscriber\",\n      \"@type\": \"@id\"\n    },\n    \"memberId\": {\n      \"@id\": \"availity:memberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"availity:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"availity:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"availity:dateOfBirth\",\n      \"@type\": \"xsd:date\"\n    },\n    \"claimNumber\": {\n      \"@id\": \"availity:claimNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fromDate\": {\n      \"@id\": \"availity:fromDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"toDate\": {\n      \"@id\": \"availity:toDate\",\n      \"@type\": \"xsd:date\"\
  \n    },\n    \"id\": {\n      \"@id\": \"availity:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"availity:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controlNumber\": {\n      \"@id\": \"availity:controlNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestType\": {\n      \"@id\": \"availity:requestType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerTaxId\": {\n      \"@id\": \"availity:providerTaxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"providerNpi\": {\n      \"@id\": \"availity:providerNpi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedDate\": {\n      \"@id\": \"availity:processedDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"traceIds\": {\n      \"@id\": \"availity:traceIds\",\n      \"@type\": \"@id\"\n    },\n    \"AVAILITYTraceId\": {\n      \"@id\": \"availity:AVAILITY_TRACE_ID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PAYERTraceId\": {\n      \"@id\": \"availity:PAYER_TRACE_ID\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"amounts\": {\n      \"@id\": \"availity:amounts\",\n      \"@type\": \"@id\"\n    },\n    \"billed\": {\n      \"@id\": \"availity:billed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"allowed\": {\n      \"@id\": \"availity:allowed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"paid\": {\n      \"@id\": \"availity:paid\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"patientResponsibility\": {\n      \"@id\": \"availity:patientResponsibility\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"completeCode\": {\n      \"@id\": \"availity:completeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"availity:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"code\": {\n      \"@id\": \"availity:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"availity:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkNumber\"\
  : {\n      \"@id\": \"availity:checkNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedStatus\": {\n      \"@id\": \"availity:requestedStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patientLastName\": {\n      \"@id\": \"availity:patientLastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patientFirstName\": {\n      \"@id\": \"availity:patientFirstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patientBirthDate\": {\n      \"@id\": \"availity:patientBirthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"providerLastName\": {\n      \"@id\": \"availity:providerLastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patientSameAsSubscriber\": {\n      \"@id\": \"availity:patientSameAsSubscriber\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"data\": {\n      \"@id\": \"availity:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"availity:total\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"offset\": {\n      \"@id\": \"availity:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attachmentType\": {\n      \"@id\": \"availity:attachmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attachments\": {\n      \"@id\": \"availity:attachments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"contentType\": {\n      \"@id\": \"availity:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"availity:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/availity/refs/heads/main/json-ld/availity-claim-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
