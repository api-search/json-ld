---
api_specs:
- filename: basecamp-api-openapi.yml
  format: yaml
  label: Basecamp API
  slug: basecamp-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/openapi/basecamp-api-openapi.yml
- filename: basecamp-webhooks-asyncapi.yml
  format: yaml
  label: Basecamp Webhooks
  slug: basecamp-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/asyncapi/basecamp-webhooks-asyncapi.yml
- filename: basecamp-oauth-openapi.yml
  format: yaml
  label: Basecamp OAuth
  slug: basecamp-oauth
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/openapi/basecamp-oauth-openapi.yml
class_count: 0
classes: []
context_file: json-ld/basecamp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/json-ld/basecamp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Basecamp from Basecamp.
layout: jsonld
name: Basecamp Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bcapi
  uri: https://api-evangelist.github.io/basecamp/vocab#
properties:
- container: ''
  name: Error
  type: ''
- container: ''
  name: error
  type: string
- container: ''
  name: BucketRef
  type: ''
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: url
  type: string
- container: ''
  name: app_url
  type: string
- container: ''
  name: PersonRef
  type: ''
- container: ''
  name: attachable_sgid
  type: string
- container: ''
  name: email_address
  type: string
- container: ''
  name: personable_type
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: bio
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: created_at
  type: string
- container: ''
  name: updated_at
  type: string
- container: ''
  name: admin
  type: boolean
- container: ''
  name: owner
  type: boolean
- container: ''
  name: client
  type: boolean
- container: ''
  name: employee
  type: boolean
- container: ''
  name: time_zone
  type: string
- container: ''
  name: avatar_url
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: Person
  type: ''
- container: ''
  name: DockItem
  type: ''
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: position
  type: integer
- container: ''
  name: Project
  type: ''
- container: ''
  name: status
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: purpose
  type: string
- container: ''
  name: clients_enabled
  type: boolean
- container: ''
  name: timesheet_enabled
  type: boolean
- container: ''
  name: color
  type: string
- container: ''
  name: bookmark_url
  type: string
- container: ''
  name: dock
  type: string
- container: ''
  name: ProjectCreateRequest
  type: ''
- container: ''
  name: ProjectUpdateRequest
  type: ''
- container: ''
  name: schedule_attributes
  type: string
- container: ''
  name: admissions
  type: string
- container: ''
  name: ProjectAccessRequest
  type: ''
- container: ''
  name: grant
  type: string
- container: ''
  name: revoke
  type: string
- container: ''
  name: create
  type: string
- container: ''
  name: ProfileUpdateRequest
  type: ''
- container: ''
  name: time_zone_name
  type: string
- container: ''
  name: Template
  type: ''
- container: ''
  name: TemplateCreateRequest
  type: ''
- container: ''
  name: ProjectConstructionRequest
  type: ''
- container: ''
  name: project
  type: string
- container: ''
  name: ProjectConstruction
  type: ''
- container: ''
  name: Recording
  type: ''
- container: ''
  name: visible_to_clients
  type: boolean
- container: ''
  name: inherits_status
  type: boolean
- container: ''
  name: bucket
  type: string
- container: ''
  name: creator
  type: string
- container: ''
  name: Message
  type: ''
- container: ''
  name: MessageCreateRequest
  type: ''
- container: ''
  name: subject
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: category_id
  type: integer
- container: ''
  name: subscriptions
  type: string
- container: ''
  name: MessageUpdateRequest
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: CommentCreateRequest
  type: ''
- container: ''
  name: TodoList
  type: ''
- container: ''
  name: TodoListCreateRequest
  type: ''
- container: ''
  name: Todo
  type: ''
- container: ''
  name: TodoCreateRequest
  type: ''
- container: ''
  name: assignee_ids
  type: string
- container: ''
  name: completion_subscriber_ids
  type: string
- container: ''
  name: notify
  type: boolean
- container: ''
  name: due_on
  type: string
- container: ''
  name: starts_on
  type: string
- container: ''
  name: PositionRequest
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: ScheduleUpdateRequest
  type: ''
- container: ''
  name: include_due_assignments
  type: boolean
- container: ''
  name: ScheduleEntry
  type: ''
- container: ''
  name: RecurrenceSchedule
  type: ''
- container: ''
  name: frequency
  type: string
- container: ''
  name: days
  type: string
- container: ''
  name: hour
  type: integer
- container: ''
  name: minute
  type: integer
- container: ''
  name: week_instance
  type: integer
- container: ''
  name: start_date
  type: string
- container: ''
  name: end_date
  type: string
- container: ''
  name: ScheduleEntryCreateRequest
  type: ''
- container: ''
  name: summary
  type: string
- container: ''
  name: starts_at
  type: string
- container: ''
  name: ends_at
  type: string
- container: ''
  name: participant_ids
  type: string
- container: ''
  name: all_day
  type: boolean
- container: ''
  name: Document
  type: ''
- container: ''
  name: DocumentCreateRequest
  type: ''
- container: ''
  name: Upload
  type: ''
- container: ''
  name: UploadCreateRequest
  type: ''
- container: ''
  name: base_name
  type: string
- container: ''
  name: UploadUpdateRequest
  type: ''
- container: ''
  name: Campfire
  type: ''
- container: ''
  name: CampfireLine
  type: ''
- container: ''
  name: parent
  type: string
- container: ''
  name: boosts_count
  type: integer
- container: ''
  name: CampfireLineCreateRequest
  type: ''
- container: ''
  name: CardTable
  type: ''
- container: ''
  name: CardColumn
  type: ''
- container: ''
  name: cards_count
  type: integer
- container: ''
  name: cards_url
  type: string
- container: ''
  name: CardMoveRequest
  type: ''
- container: ''
  name: source_id
  type: integer
- container: ''
  name: target_id
  type: integer
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: active
  type: boolean
- container: ''
  name: payload_url
  type: string
- container: ''
  name: types
  type: string
- container: ''
  name: WebhookCreateRequest
  type: ''
- container: ''
  name: WebhookUpdateRequest
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: subscribed
  type: boolean
- container: ''
  name: count
  type: integer
- container: ''
  name: subscribers
  type: string
- container: ''
  name: SubscriptionUpdateRequest
  type: ''
- container: ''
  name: unsubscriptions
  type: string
property_count: 124
provider_name: Basecamp
provider_slug: basecamp
slug: basecamp-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"bcapi\": \"https://api-evangelist.github.io/basecamp/vocab#\",\n    \"Error\": {\n      \"@id\": \"bcapi:Error\"\n    },\n    \"error\": {\n      \"@id\": \"bcapi:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketRef\": {\n      \"@id\": \"bcapi:BucketRef\"\n    },\n    \"id\": {\n      \"@id\": \"bcapi:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"bcapi:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"bcapi:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"bcapi:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"app_url\": {\n      \"@id\": \"bcapi:app_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PersonRef\": {\n      \"@id\": \"bcapi:PersonRef\"\n    },\n    \"attachable_sgid\": {\n      \"@id\": \"\
  bcapi:attachable_sgid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email_address\": {\n      \"@id\": \"bcapi:email_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"personable_type\": {\n      \"@id\": \"bcapi:personable_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"bcapi:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bio\": {\n      \"@id\": \"bcapi:bio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"bcapi:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created_at\": {\n      \"@id\": \"bcapi:created_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated_at\": {\n      \"@id\": \"bcapi:updated_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admin\": {\n      \"@id\": \"bcapi:admin\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"owner\": {\n      \"@id\": \"bcapi:owner\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"client\": {\n      \"@id\": \"bcapi:client\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"employee\": {\n      \"@id\": \"bcapi:employee\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"time_zone\": {\n      \"@id\": \"bcapi:time_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avatar_url\": {\n      \"@id\": \"bcapi:avatar_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"bcapi:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Person\": {\n      \"@id\": \"bcapi:Person\"\n    },\n    \"DockItem\": {\n      \"@id\": \"bcapi:DockItem\"\n    },\n    \"enabled\": {\n      \"@id\": \"bcapi:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"position\": {\n      \"@id\": \"bcapi:position\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Project\": {\n      \"@id\": \"bcapi:Project\"\n    },\n    \"status\": {\n      \"@id\": \"bcapi:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"bcapi:description\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"purpose\": {\n      \"@id\": \"bcapi:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clients_enabled\": {\n      \"@id\": \"bcapi:clients_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timesheet_enabled\": {\n      \"@id\": \"bcapi:timesheet_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"color\": {\n      \"@id\": \"bcapi:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bookmark_url\": {\n      \"@id\": \"bcapi:bookmark_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dock\": {\n      \"@id\": \"bcapi:dock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProjectCreateRequest\": {\n      \"@id\": \"bcapi:ProjectCreateRequest\"\n    },\n    \"ProjectUpdateRequest\": {\n      \"@id\": \"bcapi:ProjectUpdateRequest\"\n    },\n    \"schedule_attributes\": {\n      \"@id\": \"bcapi:schedule_attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"admissions\": {\n      \"@id\": \"bcapi:admissions\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"ProjectAccessRequest\": {\n      \"@id\": \"bcapi:ProjectAccessRequest\"\n    },\n    \"grant\": {\n      \"@id\": \"bcapi:grant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revoke\": {\n      \"@id\": \"bcapi:revoke\",\n      \"@type\": \"xsd:string\"\n    },\n    \"create\": {\n      \"@id\": \"bcapi:create\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileUpdateRequest\": {\n      \"@id\": \"bcapi:ProfileUpdateRequest\"\n    },\n    \"time_zone_name\": {\n      \"@id\": \"bcapi:time_zone_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Template\": {\n      \"@id\": \"bcapi:Template\"\n    },\n    \"TemplateCreateRequest\": {\n      \"@id\": \"bcapi:TemplateCreateRequest\"\n    },\n    \"ProjectConstructionRequest\": {\n      \"@id\": \"bcapi:ProjectConstructionRequest\"\n    },\n    \"project\": {\n      \"@id\": \"bcapi:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProjectConstruction\": {\n      \"@id\": \"bcapi:ProjectConstruction\"\
  \n    },\n    \"Recording\": {\n      \"@id\": \"bcapi:Recording\"\n    },\n    \"visible_to_clients\": {\n      \"@id\": \"bcapi:visible_to_clients\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"inherits_status\": {\n      \"@id\": \"bcapi:inherits_status\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"bucket\": {\n      \"@id\": \"bcapi:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creator\": {\n      \"@id\": \"bcapi:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": {\n      \"@id\": \"bcapi:Message\"\n    },\n    \"MessageCreateRequest\": {\n      \"@id\": \"bcapi:MessageCreateRequest\"\n    },\n    \"subject\": {\n      \"@id\": \"bcapi:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"bcapi:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category_id\": {\n      \"@id\": \"bcapi:category_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subscriptions\": {\n      \"@id\": \"bcapi:subscriptions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageUpdateRequest\": {\n      \"@id\": \"bcapi:MessageUpdateRequest\"\n    },\n    \"Comment\": {\n      \"@id\": \"bcapi:Comment\"\n    },\n    \"CommentCreateRequest\": {\n      \"@id\": \"bcapi:CommentCreateRequest\"\n    },\n    \"TodoList\": {\n      \"@id\": \"bcapi:TodoList\"\n    },\n    \"TodoListCreateRequest\": {\n      \"@id\": \"bcapi:TodoListCreateRequest\"\n    },\n    \"Todo\": {\n      \"@id\": \"bcapi:Todo\"\n    },\n    \"TodoCreateRequest\": {\n      \"@id\": \"bcapi:TodoCreateRequest\"\n    },\n    \"assignee_ids\": {\n      \"@id\": \"bcapi:assignee_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completion_subscriber_ids\": {\n      \"@id\": \"bcapi:completion_subscriber_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notify\": {\n      \"@id\": \"bcapi:notify\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"due_on\": {\n      \"@id\": \"bcapi:due_on\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"starts_on\": {\n      \"@id\": \"bcapi:starts_on\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PositionRequest\": {\n      \"@id\": \"bcapi:PositionRequest\"\n    },\n    \"Schedule\": {\n      \"@id\": \"bcapi:Schedule\"\n    },\n    \"ScheduleUpdateRequest\": {\n      \"@id\": \"bcapi:ScheduleUpdateRequest\"\n    },\n    \"include_due_assignments\": {\n      \"@id\": \"bcapi:include_due_assignments\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ScheduleEntry\": {\n      \"@id\": \"bcapi:ScheduleEntry\"\n    },\n    \"RecurrenceSchedule\": {\n      \"@id\": \"bcapi:RecurrenceSchedule\"\n    },\n    \"frequency\": {\n      \"@id\": \"bcapi:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"days\": {\n      \"@id\": \"bcapi:days\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hour\": {\n      \"@id\": \"bcapi:hour\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"minute\": {\n      \"@id\": \"bcapi:minute\",\n      \"@type\": \"xsd:integer\"\n    },\n   \
  \ \"week_instance\": {\n      \"@id\": \"bcapi:week_instance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start_date\": {\n      \"@id\": \"bcapi:start_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end_date\": {\n      \"@id\": \"bcapi:end_date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleEntryCreateRequest\": {\n      \"@id\": \"bcapi:ScheduleEntryCreateRequest\"\n    },\n    \"summary\": {\n      \"@id\": \"bcapi:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"starts_at\": {\n      \"@id\": \"bcapi:starts_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ends_at\": {\n      \"@id\": \"bcapi:ends_at\",\n      \"@type\": \"xsd:string\"\n    },\n    \"participant_ids\": {\n      \"@id\": \"bcapi:participant_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"all_day\": {\n      \"@id\": \"bcapi:all_day\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Document\": {\n      \"@id\": \"bcapi:Document\"\n    },\n    \"DocumentCreateRequest\"\
  : {\n      \"@id\": \"bcapi:DocumentCreateRequest\"\n    },\n    \"Upload\": {\n      \"@id\": \"bcapi:Upload\"\n    },\n    \"UploadCreateRequest\": {\n      \"@id\": \"bcapi:UploadCreateRequest\"\n    },\n    \"base_name\": {\n      \"@id\": \"bcapi:base_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UploadUpdateRequest\": {\n      \"@id\": \"bcapi:UploadUpdateRequest\"\n    },\n    \"Campfire\": {\n      \"@id\": \"bcapi:Campfire\"\n    },\n    \"CampfireLine\": {\n      \"@id\": \"bcapi:CampfireLine\"\n    },\n    \"parent\": {\n      \"@id\": \"bcapi:parent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"boosts_count\": {\n      \"@id\": \"bcapi:boosts_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CampfireLineCreateRequest\": {\n      \"@id\": \"bcapi:CampfireLineCreateRequest\"\n    },\n    \"CardTable\": {\n      \"@id\": \"bcapi:CardTable\"\n    },\n    \"CardColumn\": {\n      \"@id\": \"bcapi:CardColumn\"\n    },\n    \"cards_count\": {\n      \"@id\"\
  : \"bcapi:cards_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cards_url\": {\n      \"@id\": \"bcapi:cards_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardMoveRequest\": {\n      \"@id\": \"bcapi:CardMoveRequest\"\n    },\n    \"source_id\": {\n      \"@id\": \"bcapi:source_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"target_id\": {\n      \"@id\": \"bcapi:target_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Webhook\": {\n      \"@id\": \"bcapi:Webhook\"\n    },\n    \"active\": {\n      \"@id\": \"bcapi:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"payload_url\": {\n      \"@id\": \"bcapi:payload_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"types\": {\n      \"@id\": \"bcapi:types\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WebhookCreateRequest\": {\n      \"@id\": \"bcapi:WebhookCreateRequest\"\n    },\n    \"WebhookUpdateRequest\": {\n      \"@id\": \"bcapi:WebhookUpdateRequest\"\n    },\n    \"Subscription\": {\n\
  \      \"@id\": \"bcapi:Subscription\"\n    },\n    \"subscribed\": {\n      \"@id\": \"bcapi:subscribed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"count\": {\n      \"@id\": \"bcapi:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"subscribers\": {\n      \"@id\": \"bcapi:subscribers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionUpdateRequest\": {\n      \"@id\": \"bcapi:SubscriptionUpdateRequest\"\n    },\n    \"unsubscriptions\": {\n      \"@id\": \"bcapi:unsubscriptions\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/basecamp/refs/heads/main/json-ld/basecamp-context.jsonld
tags:
- Collaboration
- Project Management
- REST
- SaaS
- Team Communication
- JSON-LD
- Linked Data
- Semantic Web
---
