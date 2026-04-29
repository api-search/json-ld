---
api_specs:
- filename: apache-james-webadmin-rest-api.yaml
  format: yaml
  label: Apache James WebAdmin REST API
  slug: webadmin-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/openapi/apache-james-webadmin-rest-api.yaml
class_count: 9
classes:
- ComponentCheck
- DomainRequest
- MailRepository
- Task
- Quota
- UserRequest
- Mailbox
- User
- HealthCheckResult
context_file: json-ld/apache-james-webadmin-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/json-ld/apache-james-webadmin-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache James Webadmin Rest Api from Apache James.
layout: jsonld
name: Apache James Webadmin Rest Api Context
namespaces:
- prefix: james
  uri: https://apache-james.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: componentName
  type: string
- container: ''
  name: escapedComponentName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: cause
  type: string
- container: ''
  name: domain
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: taskId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: submitDate
  type: dateTime
- container: ''
  name: startedDate
  type: dateTime
- container: ''
  name: completedDate
  type: dateTime
- container: ''
  name: count
  type: integer
- container: ''
  name: size
  type: integer
- container: ''
  name: username
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: mailboxName
  type: string
- container: ''
  name: mailboxId
  type: string
- container: set
  name: checks
  type: string
property_count: 19
provider_name: Apache James
provider_slug: apache-james
slug: apache-james-webadmin-rest-api-context
source_filename: apache-james-webadmin-rest-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"james\": \"https://apache-james.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ComponentCheck\": \"james:ComponentCheck\",\n    \"DomainRequest\": \"james:DomainRequest\",\n    \"MailRepository\": \"james:MailRepository\",\n    \"Task\": \"james:Task\",\n    \"Quota\": \"james:Quota\",\n    \"UserRequest\": \"james:UserRequest\",\n    \"Mailbox\": \"james:Mailbox\",\n    \"User\": \"james:User\",\n    \"HealthCheckResult\": \"james:HealthCheckResult\",\n    \"componentName\": {\n      \"@id\": \"james:componentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"escapedComponentName\": {\n      \"@id\": \"james:escapedComponentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"james:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cause\": {\n      \"@id\"\
  : \"james:cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domain\": {\n      \"@id\": \"james:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"james:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"james:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"james:taskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"james:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submitDate\": {\n      \"@id\": \"james:submitDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedDate\": {\n      \"@id\": \"james:startedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedDate\": {\n      \"@id\": \"james:completedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"count\": {\n      \"@id\": \"james:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"size\": {\n      \"@id\": \"james:size\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"username\": {\n      \"@id\": \"james:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"james:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mailboxName\": {\n      \"@id\": \"james:mailboxName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mailboxId\": {\n      \"@id\": \"james:mailboxId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checks\": {\n      \"@id\": \"james:checks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-james/refs/heads/main/json-ld/apache-james-webadmin-rest-api-context.jsonld
tags:
- Email
- IMAP
- Java
- JMAP
- Mail Server
- Open Source
- SMTP
- JSON-LD
- Linked Data
- Semantic Web
---
