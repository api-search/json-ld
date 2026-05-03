---
api_specs:
- filename: salesforcecom-rest-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/openapi/salesforcecom-rest-openapi.yml
class_count: 0
classes: []
context_file: json-ld/salesforcecom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/json-ld/salesforcecom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforcecom from Salesforce.
layout: jsonld
name: Salesforcecom Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sf
  uri: https://api-evangelist.github.io/salesforcecom/vocab#
properties:
- container: ''
  name: SObject
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Lead
  type: ''
- container: ''
  name: Opportunity
  type: ''
- container: ''
  name: Case
  type: ''
property_count: 6
provider_name: Salesforce
provider_slug: salesforcecom
slug: salesforcecom-context
source_filename: salesforcecom-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sf\": \"https://api-evangelist.github.io/salesforcecom/vocab#\",\n\n    \"SObject\": {\n      \"@id\": \"sf:SObject\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"Name\": \"schema:name\",\n        \"OwnerId\": \"sf:ownedBy\",\n        \"CreatedDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"IsDeleted\": \"sf:isDeleted\",\n        \"attributes\": \"sf:recordAttributes\"\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"Name\": \"schema:name\",\n        \"Phone\": \"schema:telephone\",\n        \"Website\": \"schema:url\",\n        \"\
  BillingCity\": \"schema:addressLocality\",\n        \"BillingState\": \"schema:addressRegion\",\n        \"BillingCountry\": \"schema:addressCountry\",\n        \"Industry\": \"schema:industry\",\n        \"NumberOfEmployees\": \"schema:numberOfEmployees\",\n        \"AnnualRevenue\": \"schema:value\",\n        \"Description\": \"schema:description\",\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    },\n\n    \"Contact\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"FirstName\": \"schema:givenName\",\n        \"LastName\": \"schema:familyName\",\n        \"Email\": \"schema:email\",\n        \"Phone\": \"schema:telephone\",\n        \"MobilePhone\": \"schema:telephone\",\n        \"Title\": \"schema:jobTitle\",\n        \"MailingCity\": \"schema:addressLocality\",\n        \"MailingState\": \"schema:addressRegion\",\n        \"MailingCountry\": \"schema:addressCountry\",\n        \"AccountId\": \"schema:worksFor\",\n        \"OwnerId\"\
  : \"sf:ownedBy\"\n      }\n    },\n\n    \"Lead\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"FirstName\": \"schema:givenName\",\n        \"LastName\": \"schema:familyName\",\n        \"Email\": \"schema:email\",\n        \"Phone\": \"schema:telephone\",\n        \"Company\": \"schema:worksFor\",\n        \"Title\": \"schema:jobTitle\",\n        \"Status\": \"sf:leadStatus\",\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"schema:Offer\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"Name\": \"schema:name\",\n        \"Amount\": \"schema:price\",\n        \"CloseDate\": {\n          \"@id\": \"schema:validThrough\",\n          \"@type\": \"xsd:date\"\n        },\n        \"StageName\": \"sf:opportunityStage\",\n        \"AccountId\": \"schema:offeredBy\",\n        \"OwnerId\": \"sf:ownedBy\",\n        \"Description\": \"schema:description\"\n      }\n    },\n\n    \"Case\"\
  : {\n      \"@id\": \"schema:ItemList\",\n      \"@context\": {\n        \"Id\": \"@id\",\n        \"Subject\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"Status\": \"sf:caseStatus\",\n        \"Priority\": \"sf:casePriority\",\n        \"AccountId\": \"schema:provider\",\n        \"ContactId\": \"schema:recipient\",\n        \"OwnerId\": \"sf:ownedBy\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/json-ld/salesforcecom-context.jsonld
tags:
- CRM
- Cloud
- Sales
- Marketing
- Automation
- AI
- JSON-LD
- Linked Data
- Semantic Web
---
