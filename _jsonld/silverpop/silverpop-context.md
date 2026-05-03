---
api_specs:
- filename: silverpop-openapi.yml
  format: yaml
  label: Silverpop Engage XML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/silverpop/refs/heads/main/openapi/silverpop-openapi.yml
class_count: 25
classes:
- Contact
- Database
- Campaign
- Program
- EngagementEvent
- id
- email
- first_name
- last_name
- opt_in_status
- custom_fields
- name
- subject
- status
- database_id
- from_name
- from_email
- sent_count
- delivered_count
- open_count
- click_count
- unsubscribe_count
- bounce_count
- open_rate
- click_rate
context_file: json-ld/silverpop-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/silverpop/refs/heads/main/json-ld/silverpop-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Silverpop from Silverpop.
layout: jsonld
name: Silverpop Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: silverpop
  uri: https://developer.goacoustic.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
- container: ''
  name: scheduled_date
  type: dateTime
- container: ''
  name: sent_date
  type: dateTime
property_count: 4
provider_name: Silverpop
provider_slug: silverpop
slug: silverpop-context
source_filename: silverpop-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"silverpop\": \"https://developer.goacoustic.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Contact\": \"schema:Person\",\n    \"Database\": \"schema:ItemList\",\n    \"Campaign\": \"schema:EmailMessage\",\n    \"Program\": \"silverpop:AutomationProgram\",\n    \"EngagementEvent\": \"schema:InteractionCounter\",\n\n    \"id\": \"@id\",\n    \"email\": \"schema:email\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"opt_in_status\": \"silverpop:optInStatus\",\n    \"custom_fields\": \"silverpop:customFields\",\n    \"created\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"modified\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"name\": \"schema:name\",\n    \"subject\": \"schema:about\",\n    \"status\": \"schema:status\",\n    \"database_id\": \"silverpop:databaseReference\"\
  ,\n    \"from_name\": \"schema:senderName\",\n    \"from_email\": \"schema:senderEmail\",\n    \"scheduled_date\": {\"@id\": \"silverpop:scheduledDate\", \"@type\": \"xsd:dateTime\"},\n    \"sent_date\": {\"@id\": \"silverpop:sentDate\", \"@type\": \"xsd:dateTime\"},\n\n    \"sent_count\": \"silverpop:sentCount\",\n    \"delivered_count\": \"silverpop:deliveredCount\",\n    \"open_count\": \"silverpop:openCount\",\n    \"click_count\": \"silverpop:clickCount\",\n    \"unsubscribe_count\": \"silverpop:unsubscribeCount\",\n    \"bounce_count\": \"silverpop:bounceCount\",\n    \"open_rate\": \"silverpop:openRate\",\n    \"click_rate\": \"silverpop:clickRate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/silverpop/refs/heads/main/json-ld/silverpop-context.jsonld
tags:
- Email Marketing
- Marketing Automation
- Campaign Management
- Digital Marketing
- JSON-LD
- Linked Data
- Semantic Web
---
