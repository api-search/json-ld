---
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
