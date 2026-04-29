---
class_count: 17
classes:
- Error
- Ux Message
- User
- Application
- Subscription
- Ide
- Environment
- Agreement
- Ssh Key
- Organization
- Team
- Invite
- Notification
- url
- name
- email
- description
context_file: json-ld/acquia-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/json-ld/acquia-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Acquia from Acquia.
layout: jsonld
name: Acquia Context
namespaces:
- prefix: acquia
  uri: https://acquia.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: uuid
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: flags
  type: string
- container: ''
  name: weight
  type: integer
- container: ''
  name: start_at
  type: dateTime
- container: ''
  name: expire_at
  type: dateTime
- container: ''
  name: _links
  type: string
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: last_login_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: mail
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: job_title
  type: string
- container: ''
  name: job_function
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: picture_url
  type: reference
- container: set
  name: features
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: hosting
  type: string
- container: ''
  name: subscription
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: _embedded
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: applications_total
  type: integer
- container: ''
  name: applications_used
  type: integer
- container: ''
  name: label
  type: string
- container: ''
  name: application
  type: string
- container: set
  name: domains
  type: string
- container: ''
  name: active_domain
  type: string
- container: ''
  name: default_domain
  type: string
- container: ''
  name: image_url
  type: reference
- container: ''
  name: ssh_url
  type: string
- container: set
  name: ips
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: balancer
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: vcs
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: artifact
  type: string
- container: ''
  name: document_uuid
  type: string
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: actioned_by
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: public_key
  type: string
- container: ''
  name: fingerprint
  type: string
- container: ''
  name: subscriptions_total
  type: integer
- container: ''
  name: admins_total
  type: integer
- container: ''
  name: users_total
  type: integer
- container: ''
  name: teams_total
  type: integer
- container: ''
  name: roles_total
  type: integer
- container: ''
  name: owner
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: team
  type: string
- container: set
  name: applications
  type: string
- container: set
  name: roles
  type: string
- container: ''
  name: progress
  type: integer
- container: ''
  name: user
  type: string
- container: ''
  name: started_at
  type: dateTime
- container: ''
  name: completed_at
  type: dateTime
- container: ''
  name: labels
  type: string
property_count: 73
provider_name: Acquia
provider_slug: acquia
slug: acquia-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"acquia\": \"https://acquia.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Error\": \"acquia:Error\",\n    \"Ux Message\": \"acquia:UxMessage\",\n    \"User\": \"acquia:User\",\n    \"Application\": \"acquia:Application\",\n    \"Subscription\": \"acquia:Subscription\",\n    \"Ide\": \"acquia:Ide\",\n    \"Environment\": \"acquia:Environment\",\n    \"Agreement\": \"acquia:Agreement\",\n    \"Ssh Key\": \"acquia:SshKey\",\n    \"Organization\": \"acquia:Organization\",\n    \"Team\": \"acquia:Team\",\n    \"Invite\": \"acquia:Invite\",\n    \"Notification\": \"acquia:Notification\",\n    \"error\": {\n      \"@id\": \"acquia:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"acquia:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"acquia:id\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"uuid\": {\n      \"@id\": \"acquia:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"acquia:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"body\": {\n      \"@id\": \"acquia:body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"filters\": {\n      \"@id\": \"acquia:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flags\": {\n      \"@id\": \"acquia:flags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"acquia:weight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start_at\": {\n      \"@id\": \"acquia:start_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expire_at\": {\n      \"@id\": \"acquia:expire_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"_links\": {\n      \"@id\": \"acquia:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"first_name\": {\n      \"@id\"\
  : \"acquia:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_name\": {\n      \"@id\": \"acquia:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_login_at\": {\n      \"@id\": \"acquia:last_login_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_at\": {\n      \"@id\": \"acquia:created_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"mail\": {\n      \"@id\": \"acquia:mail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phone\": {\n      \"@id\": \"acquia:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job_title\": {\n      \"@id\": \"acquia:job_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job_function\": {\n      \"@id\": \"acquia:job_function\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"acquia:company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"acquia:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\"\
  : \"acquia:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"acquia:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"picture_url\": {\n      \"@id\": \"acquia:picture_url\",\n      \"@type\": \"@id\"\n    },\n    \"features\": {\n      \"@id\": \"acquia:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"acquia:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hosting\": {\n      \"@id\": \"acquia:hosting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscription\": {\n      \"@id\": \"acquia:subscription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"acquia:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"acquia:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"acquia:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"_embedded\"\
  : {\n      \"@id\": \"acquia:_embedded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"acquia:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications_total\": {\n      \"@id\": \"acquia:applications_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"applications_used\": {\n      \"@id\": \"acquia:applications_used\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"label\": {\n      \"@id\": \"acquia:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"acquia:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"acquia:domains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"active_domain\": {\n      \"@id\": \"acquia:active_domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default_domain\": {\n      \"@id\": \"acquia:default_domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image_url\": {\n      \"@id\"\
  : \"acquia:image_url\",\n      \"@type\": \"@id\"\n    },\n    \"ssh_url\": {\n      \"@id\": \"acquia:ssh_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ips\": {\n      \"@id\": \"acquia:ips\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"acquia:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balancer\": {\n      \"@id\": \"acquia:balancer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"acquia:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"acquia:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vcs\": {\n      \"@id\": \"acquia:vcs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"acquia:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artifact\": {\n      \"@id\": \"acquia:artifact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document_uuid\": {\n      \"@id\":\
  \ \"acquia:document_uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updated_at\": {\n      \"@id\": \"acquia:updated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"actioned_by\": {\n      \"@id\": \"acquia:actioned_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"acquia:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"public_key\": {\n      \"@id\": \"acquia:public_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fingerprint\": {\n      \"@id\": \"acquia:fingerprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptions_total\": {\n      \"@id\": \"acquia:subscriptions_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"admins_total\": {\n      \"@id\": \"acquia:admins_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"users_total\": {\n      \"@id\": \"acquia:users_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"teams_total\": {\n      \"@id\": \"acquia:teams_total\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"roles_total\": {\n      \"@id\": \"acquia:roles_total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"owner\": {\n      \"@id\": \"acquia:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"token\": {\n      \"@id\": \"acquia:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"acquia:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"team\": {\n      \"@id\": \"acquia:team\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications\": {\n      \"@id\": \"acquia:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roles\": {\n      \"@id\": \"acquia:roles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progress\": {\n      \"@id\": \"acquia:progress\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"user\": {\n      \"@id\": \"acquia:user\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"description\": \"schema:description\",\n    \"started_at\": {\n      \"@id\": \"acquia:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completed_at\": {\n      \"@id\": \"acquia:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"labels\": {\n      \"@id\": \"acquia:labels\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/json-ld/acquia-context.jsonld
tags:
- Content
- Experience
- JSON-LD
- Linked Data
- Semantic Web
---
