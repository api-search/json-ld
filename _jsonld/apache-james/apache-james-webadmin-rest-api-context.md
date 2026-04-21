---
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
