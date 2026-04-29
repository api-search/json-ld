---
api_specs:
- filename: copper-developer-api-openapi.yml
  format: yaml
  label: Copper Developer API
  slug: developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/openapi/copper-developer-api-openapi.yml
class_count: 44
classes:
- Person
- Company
- Lead
- Opportunity
- Project
- Task
- Activity
- Webhook
- id
- name
- first_name
- last_name
- prefix
- suffix
- title
- details
- emails
- email
- phone_numbers
- websites
- address
- street
- city
- state
- postal_code
- country
- company_name
- company_id
- tags
- monetary_value
- close_date
- win_probability
- status
- priority
- due_date
- completed_date
- date_created
- date_modified
- assignee_id
- pipeline_id
- pipeline_stage_id
- custom_fields
- source_id
- contact_type_id
context_file: json-ld/copper-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/json-ld/copper-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Copper from Copper.
layout: jsonld
name: Copper Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: copper
  uri: https://api.copper.com/vocab#
properties: []
property_count: 0
provider_name: Copper
provider_slug: copper
slug: copper-context
source_filename: copper-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://api.copper.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"copper\": \"https://api.copper.com/vocab#\",\n    \"Person\": \"schema:Person\",\n    \"Company\": \"schema:Organization\",\n    \"Lead\": \"copper:Lead\",\n    \"Opportunity\": \"copper:Opportunity\",\n    \"Project\": \"copper:Project\",\n    \"Task\": \"copper:Action\",\n    \"Activity\": \"copper:Activity\",\n    \"Webhook\": \"copper:Webhook\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"prefix\": \"schema:honorificPrefix\",\n    \"suffix\": \"schema:honorificSuffix\",\n    \"title\": \"schema:jobTitle\",\n    \"details\": \"schema:description\",\n    \"emails\": \"schema:email\",\n    \"email\": \"schema:email\",\n    \"phone_numbers\": \"schema:telephone\",\n    \"websites\": \"schema:url\",\n    \"address\": \"schema:address\",\n \
  \   \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"postal_code\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"company_name\": \"schema:worksFor\",\n    \"company_id\": \"copper:companyId\",\n    \"tags\": \"schema:keywords\",\n    \"monetary_value\": \"schema:price\",\n    \"close_date\": \"copper:closeDate\",\n    \"win_probability\": \"copper:winProbability\",\n    \"status\": \"copper:status\",\n    \"priority\": \"copper:priority\",\n    \"due_date\": \"schema:scheduledTime\",\n    \"completed_date\": \"copper:completedDate\",\n    \"date_created\": \"schema:dateCreated\",\n    \"date_modified\": \"schema:dateModified\",\n    \"assignee_id\": \"copper:assigneeId\",\n    \"pipeline_id\": \"copper:pipelineId\",\n    \"pipeline_stage_id\": \"copper:pipelineStageId\",\n    \"custom_fields\": \"copper:customFields\",\n    \"source_id\": \"copper:sourceId\",\n    \"contact_type_id\"\
  : \"copper:contactTypeId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/copper/refs/heads/main/json-ld/copper-context.jsonld
tags:
- Activities
- Companies
- Contact Relationship Management
- Contacts
- CRM
- Customer Relationship Management
- Google Workspace
- Leads
- Opportunities
- People
- Projects
- Sales
- Tasks
- JSON-LD
- Linked Data
- Semantic Web
---
