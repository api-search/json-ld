---
api_specs:
- filename: revert-unified-api-openapi.yml
  format: yaml
  label: Revert Unified API
  slug: revert-unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/revert/refs/heads/main/openapi/revert-unified-api-openapi.yml
class_count: 44
classes:
- id
- type
- Contact
- firstName
- lastName
- email
- phone
- company
- title
- Company
- name
- website
- industry
- numberOfEmployees
- Deal
- amount
- currency
- stage
- probability
- closeDate
- Lead
- source
- status
- Task
- subject
- description
- dueDate
- priority
- Event
- startDate
- endDate
- location
- Note
- content
- User
- role
- Connection
- tp_id
- t_id
- tp_account_url
- remoteId
- additional
- createdAt
- updatedAt
context_file: json-ld/revert-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/revert/refs/heads/main/json-ld/revert-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Revert from Revert.
layout: jsonld
name: Revert Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: revert
  uri: https://www.revert.dev/vocab/
properties: []
property_count: 0
provider_name: Revert
provider_slug: revert
slug: revert-context
source_filename: revert-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"revert\": \"https://www.revert.dev/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Contact\": \"schema:Person\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"company\": \"schema:worksFor\",\n    \"title\": \"schema:jobTitle\",\n\n    \"Company\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"website\": \"schema:url\",\n    \"industry\": \"schema:industry\",\n    \"numberOfEmployees\": \"schema:numberOfEmployees\",\n\n    \"Deal\": \"revert:Deal\",\n    \"amount\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"stage\": \"revert:stage\",\n    \"probability\": \"revert:probability\",\n    \"closeDate\": \"schema:endDate\",\n\n    \"Lead\": \"revert:Lead\",\n    \"source\": \"schema:sourceOrganization\",\n   \
  \ \"status\": \"schema:actionStatus\",\n\n    \"Task\": \"schema:Action\",\n    \"subject\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"dueDate\": \"schema:endDate\",\n    \"priority\": \"revert:priority\",\n\n    \"Event\": \"schema:Event\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"location\": \"schema:location\",\n\n    \"Note\": \"revert:Note\",\n    \"content\": \"schema:text\",\n\n    \"User\": \"schema:Person\",\n    \"role\": \"schema:roleName\",\n\n    \"Connection\": \"revert:Connection\",\n    \"tp_id\": \"revert:thirdPartyId\",\n    \"t_id\": \"revert:tenantId\",\n    \"tp_account_url\": \"revert:accountUrl\",\n\n    \"remoteId\": \"revert:remoteId\",\n    \"additional\": \"revert:additionalFields\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/revert/refs/heads/main/json-ld/revert-context.jsonld
tags:
- Integrations
- CRM
- Unified API
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
