---
api_specs:
- filename: unified-to-accounting-openapi.yaml
  format: yaml
  label: Unified.to Accounting API
  slug: accounting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-accounting-openapi.yaml
- filename: unified-to-marketing-openapi.yaml
  format: yaml
  label: Unified.to Advertising API
  slug: ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-marketing-openapi.yaml
- filename: unified-to-hr-talent-openapi.yaml
  format: yaml
  label: Unified.to Assessment API
  slug: assessment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-hr-talent-openapi.yaml
- filename: unified-to-ats-openapi.yaml
  format: yaml
  label: Unified.to ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-ats-openapi.yaml
- filename: unified-to-productivity-openapi.yaml
  format: yaml
  label: Unified.to Calendar & Meetings API
  slug: calendar-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-productivity-openapi.yaml
- filename: unified-to-it-ops-openapi.yaml
  format: yaml
  label: Unified.to Call Center API
  slug: call-center-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-it-ops-openapi.yaml
- filename: unified-to-crm-openapi.yaml
  format: yaml
  label: Unified.to CRM API
  slug: crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-crm-openapi.yaml
- filename: unified-to-commerce-openapi.yaml
  format: yaml
  label: Unified.to E-Commerce API
  slug: ecommerce-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-commerce-openapi.yaml
- filename: unified-to-hris-openapi.yaml
  format: yaml
  label: Unified.to HR & Directory API
  slug: hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-hris-openapi.yaml
- filename: unified-to-productivity-openapi.yaml
  format: yaml
  label: Unified.to Messaging API
  slug: messaging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-productivity-openapi.yaml
- filename: unified-to-it-ops-openapi.yaml
  format: yaml
  label: Unified.to Payments API
  slug: payment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-it-ops-openapi.yaml
- filename: unified-to-it-ops-openapi.yaml
  format: yaml
  label: Unified.to Ticketing API
  slug: ticketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/openapi/unified-to-it-ops-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/unified-to-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/json-ld/unified-to-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unified To from Unified.to.
layout: jsonld
name: Unified To Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: unified
  uri: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/json-ld/unified-to-context.jsonld#
properties:
- container: ''
  name: Connection
  type: schema:SoftwareApplication
- container: ''
  name: Integration
  type: schema:SoftwareApplication
- container: ''
  name: CrmContact
  type: schema:Person
- container: ''
  name: CrmCompany
  type: schema:Organization
- container: ''
  name: CrmDeal
  type: schema:Offer
- container: ''
  name: HrisEmployee
  type: schema:Person
- container: ''
  name: AtsJob
  type: schema:JobPosting
- container: ''
  name: AtsCandidate
  type: schema:Person
- container: ''
  name: AccountingInvoice
  type: schema:Invoice
- container: ''
  name: TicketingTicket
  type: schema:SupportCase
- container: ''
  name: CommerceOrder
  type: schema:Order
- container: ''
  name: CommerceItem
  type: schema:Product
- container: ''
  name: CalendarEvent
  type: schema:Event
- container: ''
  name: MessagingMessage
  type: schema:Message
- container: ''
  name: PaymentPayment
  type: schema:PaymentStatusType
- container: ''
  name: connectionId
  type: string
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: integrationType
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: id
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
property_count: 25
provider_name: Unified.to
provider_slug: unified-to
slug: unified-to-context
source_filename: unified-to-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"unified\": \"https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/json-ld/unified-to-context.jsonld#\",\n\n    \"Connection\": {\n      \"@id\": \"unified:Connection\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Integration\": {\n      \"@id\": \"unified:Integration\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"CrmContact\": {\n      \"@id\": \"unified:CrmContact\",\n      \"@type\": \"schema:Person\"\n    },\n    \"CrmCompany\": {\n      \"@id\": \"unified:CrmCompany\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"CrmDeal\": {\n      \"@id\": \"unified:CrmDeal\",\n      \"@type\": \"schema:Offer\"\n    },\n    \"HrisEmployee\": {\n      \"@id\": \"unified:HrisEmployee\",\n      \"@type\": \"schema:Person\"\n    },\n    \"AtsJob\": {\n      \"@id\": \"unified:AtsJob\"\
  ,\n      \"@type\": \"schema:JobPosting\"\n    },\n    \"AtsCandidate\": {\n      \"@id\": \"unified:AtsCandidate\",\n      \"@type\": \"schema:Person\"\n    },\n    \"AccountingInvoice\": {\n      \"@id\": \"unified:AccountingInvoice\",\n      \"@type\": \"schema:Invoice\"\n    },\n    \"TicketingTicket\": {\n      \"@id\": \"unified:TicketingTicket\",\n      \"@type\": \"schema:SupportCase\"\n    },\n    \"CommerceOrder\": {\n      \"@id\": \"unified:CommerceOrder\",\n      \"@type\": \"schema:Order\"\n    },\n    \"CommerceItem\": {\n      \"@id\": \"unified:CommerceItem\",\n      \"@type\": \"schema:Product\"\n    },\n    \"CalendarEvent\": {\n      \"@id\": \"unified:CalendarEvent\",\n      \"@type\": \"schema:Event\"\n    },\n    \"MessagingMessage\": {\n      \"@id\": \"unified:MessagingMessage\",\n      \"@type\": \"schema:Message\"\n    },\n    \"PaymentPayment\": {\n      \"@id\": \"unified:PaymentPayment\",\n      \"@type\": \"schema:PaymentStatusType\"\n    },\n\n    \"connectionId\"\
  : {\n      \"@id\": \"unified:connectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"unified:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrationType\": {\n      \"@id\": \"unified:integrationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unified-to/refs/heads/main/json-ld/unified-to-context.jsonld
tags:
- Integrations
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
