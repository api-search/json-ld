---
class_count: 3
classes:
- EvidenceItem
- Dispute
- EvidenceRequest
context_file: json-ld/affirm-disputes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-disputes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Affirm Disputes from affirm.
layout: jsonld
name: Affirm Disputes Context
namespaces:
- prefix: affirm
  uri: https://affirm.com/schema/
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
  name: type
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: transactionId
  type: string
- container: ''
  name: chargeId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: reasonCode
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: evidenceDueBy
  type: dateTime
- container: ''
  name: closedAt
  type: dateTime
- container: ''
  name: outcome
  type: string
- container: set
  name: evidence
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: explanation
  type: string
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: shippingCarrier
  type: string
- container: ''
  name: customerCommunication
  type: string
- container: ''
  name: refundPolicyDisclosure
  type: string
property_count: 21
provider_name: affirm
provider_slug: affirm
slug: affirm-disputes-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"affirm\": \"https://affirm.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EvidenceItem\": \"affirm:EvidenceItem\",\n    \"id\": {\n      \"@id\": \"affirm:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"affirm:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"affirm:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"affirm:submitted_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Dispute\": \"affirm:Dispute\",\n    \"transactionId\": {\n      \"@id\": \"affirm:transaction_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargeId\": {\n      \"@id\": \"affirm:charge_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"affirm:status\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"reasonCode\": {\n      \"@id\": \"affirm:reason_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"affirm:amount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currency\": {\n      \"@id\": \"affirm:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"affirm:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"evidenceDueBy\": {\n      \"@id\": \"affirm:evidence_due_by\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"closedAt\": {\n      \"@id\": \"affirm:closed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"outcome\": {\n      \"@id\": \"affirm:outcome\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evidence\": {\n      \"@id\": \"affirm:evidence\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EvidenceRequest\": \"affirm:EvidenceRequest\",\n    \"files\": {\n      \"@id\": \"affirm:files\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"explanation\": {\n      \"@id\": \"affirm:explanation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trackingNumber\": {\n      \"@id\": \"affirm:tracking_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shippingCarrier\": {\n      \"@id\": \"affirm:shipping_carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerCommunication\": {\n      \"@id\": \"affirm:customer_communication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"refundPolicyDisclosure\": {\n      \"@id\": \"affirm:refund_policy_disclosure\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/json-ld/affirm-disputes-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
