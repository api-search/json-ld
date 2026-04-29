---
api_specs:
- filename: servicenow-table-api-openapi.yml
  format: yaml
  label: ServiceNow Table API
  slug: servicenow-table-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-table-api-openapi.yml
- filename: servicenow-aggregate-api-openapi.yml
  format: yaml
  label: ServiceNow Aggregate API
  slug: servicenow-aggregate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-aggregate-api-openapi.yml
- filename: servicenow-attachment-api-openapi.yml
  format: yaml
  label: ServiceNow Attachment API
  slug: servicenow-attachment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-attachment-api-openapi.yml
- filename: servicenow-import-set-api-openapi.yml
  format: yaml
  label: ServiceNow Import Set API
  slug: servicenow-import-set-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-import-set-api-openapi.yml
- filename: servicenow-change-management-api-openapi.yml
  format: yaml
  label: ServiceNow Change Management API
  slug: servicenow-change-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-change-management-api-openapi.yml
- filename: servicenow-service-catalog-api-openapi.yml
  format: yaml
  label: ServiceNow Service Catalog API
  slug: servicenow-service-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-service-catalog-api-openapi.yml
- filename: servicenow-cmdb-instance-api-openapi.yml
  format: yaml
  label: ServiceNow CMDB Instance API
  slug: servicenow-cmdb-instance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-cmdb-instance-api-openapi.yml
- filename: contact-api-openapi.yaml
  format: yaml
  label: ServiceNow Contact API
  slug: servicenow-contact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/contact-api-openapi.yaml
- filename: trouble-ticket-openapi.yaml
  format: yaml
  label: ServiceNow Trouble Ticket Open API
  slug: servicenow-trouble-ticket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/trouble-ticket-openapi.yaml
- filename: servicenow-events-asyncapi.yml
  format: yaml
  label: ServiceNow Event Management Topic Open API
  slug: servicenow-event-management-topic-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/asyncapi/servicenow-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/trouble-ticket-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/trouble-ticket-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trouble Ticket from ServiceNow.
layout: jsonld
name: Trouble Ticket Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: TroubleTicket
  type: ''
- container: ''
  name: TroubleTicketCreate
  type: ''
- container: ''
  name: TroubleTicketUpdate
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: ChannelInput
  type: ''
- container: ''
  name: Note
  type: ''
- container: ''
  name: NoteInput
  type: ''
- container: ''
  name: RelatedEntity
  type: ''
- container: ''
  name: RelatedEntityInput
  type: ''
- container: ''
  name: RelatedParty
  type: ''
- container: ''
  name: RelatedPartyInput
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 12
provider_name: ServiceNow
provider_slug: servicenow
slug: trouble-ticket-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"TroubleTicket\": {\n      \"@id\": \"ns:TroubleTicket\",\n      \"@context\": {\n        \"@type\": {\n          \"@id\": \"ns:@type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"href\": {\n          \"@id\": \"ns:href\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationDate\": {\n          \"@id\": \"ns:creationDate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastUpdate\": {\n          \"@id\": \"ns:lastUpdate\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"severity\": {\n          \"@id\": \"ns:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticketType\": {\n          \"@id\": \"ns:ticketType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channel\": {\n          \"@id\": \"ns:channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"note\": \"ns:note\",\n        \"relatedEntity\": \"ns:relatedEntity\",\n        \"relatedParty\": \"ns:relatedParty\"\n      }\n    },\n    \"TroubleTicketCreate\": {\n      \"@id\": \"ns:TroubleTicketCreate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"ns:severity\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ticketType\": {\n          \"@id\": \"ns:ticketType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"channel\": {\n          \"@id\": \"ns:channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"note\": \"ns:note\",\n        \"relatedEntity\": \"ns:relatedEntity\",\n        \"relatedParty\": \"ns:relatedParty\"\n      }\n    },\n    \"TroubleTicketUpdate\": {\n      \"@id\": \"ns:TroubleTicketUpdate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"ns:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\":\
  \ \"xsd:string\"\n        },\n        \"channel\": {\n          \"@id\": \"ns:channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"note\": \"ns:note\",\n        \"relatedEntity\": \"ns:relatedEntity\",\n        \"relatedParty\": \"ns:relatedParty\"\n      }\n    },\n    \"Channel\": {\n      \"@id\": \"ns:Channel\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ChannelInput\": {\n      \"@id\": \"ns:ChannelInput\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Note\": {\n      \"@id\": \"ns:Note\",\n      \"@context\": {\n        \"@type\": {\n          \"@id\": \"ns:@type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"text\": {\n          \"@id\": \"ns:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"date\": {\n          \"@id\":\
  \ \"ns:date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"ns:author\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"NoteInput\": {\n      \"@id\": \"ns:NoteInput\",\n      \"@context\": {\n        \"text\": {\n          \"@id\": \"ns:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"@type\": {\n          \"@id\": \"ns:@type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RelatedEntity\": {\n      \"@id\": \"ns:RelatedEntity\",\n      \"@context\": {\n        \"@type\": {\n          \"@id\": \"ns:@type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"href\": {\n          \"@id\": \"ns:href\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\"\
  : {\n          \"@id\": \"ns:role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"@referredType\": {\n          \"@id\": \"ns:@referredType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RelatedEntityInput\": {\n      \"@id\": \"ns:RelatedEntityInput\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"@referredType\": {\n          \"@id\": \"ns:@referredType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RelatedParty\": {\n      \"@id\": \"ns:RelatedParty\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"@referredType\": {\n          \"@id\": \"ns:@referredType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"RelatedPartyInput\"\
  : {\n      \"@id\": \"ns:RelatedPartyInput\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"@referredType\": {\n          \"@id\": \"ns:@referredType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/trouble-ticket-context.jsonld
tags:
- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- IT Service Management
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
