---
class_count: 18
classes:
- Activity
- Contact
- Task
- Tenant
- SearchResults
- User
- OfferingItem
- HardwareNode
- Agent
- Quota
- Report
- Client
- TokenResponse
- UsageItem
- AgentUpdateSettings
- AgentOS
- email
- name
context_file: json-ld/acronis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/json-ld/acronis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acronis from Acronis.
layout: jsonld
name: Acronis Context
namespaces:
- prefix: acronis
  uri: https://developer.acronis.com/schema/
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
  name: state
  type: string
- container: ''
  name: result_code
  type: string
- container: ''
  name: parent_activity_id
  type: string
- container: ''
  name: task_id
  type: string
- container: ''
  name: sustainable
  type: boolean
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: firstname
  type: string
- container: ''
  name: lastname
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: address1
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: uuid
  type: reference
- container: ''
  name: priority
  type: string
- container: ''
  name: policy_id
  type: reference
- container: ''
  name: resource_id
  type: reference
- container: ''
  name: executor_id
  type: string
- container: ''
  name: enqueuedAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: tenant_id
  type: reference
- container: ''
  name: kind
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: parent_id
  type: reference
- container: ''
  name: customer_type
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: version
  type: integer
- container: ''
  name: contact
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: login
  type: string
- container: ''
  name: application_id
  type: reference
- container: ''
  name: status
  type: integer
- container: ''
  name: quota
  type: string
- container: ''
  name: edition
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: last_seen
  type: dateTime
- container: ''
  name: registration_time
  type: dateTime
- container: ''
  name: value
  type: decimal
- container: ''
  name: overage
  type: decimal
- container: ''
  name: schedule
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: client_id
  type: string
- container: ''
  name: client_secret
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: access_token
  type: string
- container: ''
  name: token_type
  type: string
- container: ''
  name: expires_in
  type: integer
- container: ''
  name: refresh_token
  type: string
- container: ''
  name: scope
  type: string
- container: ''
  name: offering_item
  type: string
- container: ''
  name: update_channel
  type: string
- container: ''
  name: automatic
  type: boolean
- container: ''
  name: maintenance_window
  type: string
- container: ''
  name: family
  type: string
- container: ''
  name: arch
  type: string
property_count: 61
provider_name: Acronis
provider_slug: acronis
slug: acronis-context
source_filename: acronis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acronis\": \"https://developer.acronis.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Activity\": \"acronis:Activity\",\n    \"Contact\": \"acronis:Contact\",\n    \"Task\": \"acronis:Task\",\n    \"Tenant\": \"acronis:Tenant\",\n    \"SearchResults\": \"acronis:SearchResults\",\n    \"User\": \"acronis:User\",\n    \"OfferingItem\": \"acronis:OfferingItem\",\n    \"HardwareNode\": \"acronis:HardwareNode\",\n    \"Agent\": \"acronis:Agent\",\n    \"Quota\": \"acronis:Quota\",\n    \"Report\": \"acronis:Report\",\n    \"Client\": \"acronis:Client\",\n    \"TokenResponse\": \"acronis:TokenResponse\",\n    \"UsageItem\": \"acronis:UsageItem\",\n    \"AgentUpdateSettings\": \"acronis:AgentUpdateSettings\",\n    \"AgentOS\": \"acronis:AgentOS\",\n    \"id\": {\n      \"@id\": \"acronis:id\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"acronis:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"acronis:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"result_code\": {\n      \"@id\": \"acronis:result_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent_activity_id\": {\n      \"@id\": \"acronis:parent_activity_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"task_id\": {\n      \"@id\": \"acronis:task_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sustainable\": {\n      \"@id\": \"acronis:sustainable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdAt\": {\n      \"@id\": \"acronis:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"acronis:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"acronis:completedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firstname\": {\n      \"@id\": \"acronis:firstname\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"lastname\": {\n      \"@id\": \"acronis:lastname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"acronis:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address1\": {\n      \"@id\": \"acronis:address1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"acronis:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"acronis:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"acronis:uuid\",\n      \"@type\": \"@id\"\n    },\n    \"priority\": {\n      \"@id\": \"acronis:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy_id\": {\n      \"@id\": \"acronis:policy_id\",\n      \"@type\": \"@id\"\n    },\n    \"resource_id\": {\n      \"@id\": \"acronis:resource_id\",\n      \"@type\": \"@id\"\n    },\n    \"executor_id\": {\n      \"@id\": \"acronis:executor_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"enqueuedAt\": {\n      \"@id\": \"acronis:enqueuedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"acronis:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"tenant_id\": {\n      \"@id\": \"acronis:tenant_id\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"kind\": {\n      \"@id\": \"acronis:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"acronis:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"parent_id\": {\n      \"@id\": \"acronis:parent_id\",\n      \"@type\": \"@id\"\n    },\n    \"customer_type\": {\n      \"@id\": \"acronis:customer_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"acronis:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"acronis:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"version\"\
  : {\n      \"@id\": \"acronis:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contact\": {\n      \"@id\": \"acronis:contact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"acronis:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"acronis:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"login\": {\n      \"@id\": \"acronis:login\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application_id\": {\n      \"@id\": \"acronis:application_id\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"acronis:status\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"quota\": {\n      \"@id\": \"acronis:quota\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edition\": {\n      \"@id\": \"acronis:edition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"acronis:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"os\"\
  : {\n      \"@id\": \"acronis:os\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_seen\": {\n      \"@id\": \"acronis:last_seen\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"registration_time\": {\n      \"@id\": \"acronis:registration_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"value\": {\n      \"@id\": \"acronis:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"overage\": {\n      \"@id\": \"acronis:overage\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"schedule\": {\n      \"@id\": \"acronis:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"acronis:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_id\": {\n      \"@id\": \"acronis:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_secret\": {\n      \"@id\": \"acronis:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"acronis:data\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"access_token\": {\n      \"@id\": \"acronis:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token_type\": {\n      \"@id\": \"acronis:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expires_in\": {\n      \"@id\": \"acronis:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"refresh_token\": {\n      \"@id\": \"acronis:refresh_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scope\": {\n      \"@id\": \"acronis:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offering_item\": {\n      \"@id\": \"acronis:offering_item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"update_channel\": {\n      \"@id\": \"acronis:update_channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automatic\": {\n      \"@id\": \"acronis:automatic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maintenance_window\": {\n      \"@id\": \"acronis:maintenance_window\",\n      \"@type\": \"xsd:string\"\n    },\n    \"family\": {\n      \"\
  @id\": \"acronis:family\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arch\": {\n      \"@id\": \"acronis:arch\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acronis/refs/heads/main/json-ld/acronis-context.jsonld
tags:
- Cybersecurity
- Data Protection
- Endpoint Management
- JSON-LD
- Linked Data
- Semantic Web
---
