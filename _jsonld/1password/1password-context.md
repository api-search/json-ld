---
class_count: 0
classes: []
context_file: json-ld/1password-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 1Password from 1Password.
layout: jsonld
name: 1Password Context
namespaces:
- prefix: onepassword
  uri: https://developer.1password.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Vault
  type: ''
- container: ''
  name: Item
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: Section
  type: ''
- container: ''
  name: SignInAttempt
  type: ''
- container: ''
  name: ItemUsage
  type: ''
- container: ''
  name: AuditEvent
  type: ''
- container: ''
  name: Account
  type: ''
property_count: 8
provider_name: 1Password
provider_slug: 1password
slug: 1password-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"onepassword\": \"https://developer.1password.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Vault\": {\n      \"@id\": \"onepassword:Vault\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"attributeVersion\": \"onepassword:attributeVersion\",\n        \"contentVersion\": \"onepassword:contentVersion\",\n        \"items\": \"onepassword:itemCount\",\n        \"type\": \"onepassword:vaultType\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Item\": {\n      \"@id\": \"onepassword:Item\"\
  ,\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"title\": \"schema:name\",\n        \"category\": \"onepassword:itemCategory\",\n        \"favorite\": \"onepassword:isFavorite\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"version\": \"schema:version\",\n        \"state\": \"onepassword:itemState\",\n        \"fields\": {\n          \"@id\": \"onepassword:hasField\",\n          \"@container\": \"@set\"\n        },\n        \"sections\": {\n          \"@id\": \"onepassword:hasSection\",\n          \"@container\": \"@set\"\n        },\n        \"urls\": {\n          \"@id\": \"schema:url\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastEditedBy\"\
  : \"onepassword:lastEditedBy\"\n      }\n    },\n\n    \"Field\": {\n      \"@id\": \"onepassword:Field\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"onepassword:fieldType\",\n        \"purpose\": \"onepassword:fieldPurpose\",\n        \"label\": \"schema:name\",\n        \"value\": \"schema:value\"\n      }\n    },\n\n    \"Section\": {\n      \"@id\": \"onepassword:Section\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"label\": \"schema:name\"\n      }\n    },\n\n    \"SignInAttempt\": {\n      \"@id\": \"onepassword:SignInAttempt\",\n      \"@context\": {\n        \"uuid\": \"schema:identifier\",\n        \"timestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"category\": \"onepassword:attemptCategory\",\n        \"type\": \"onepassword:attemptType\",\n        \"country\": \"schema:addressCountry\",\n        \"target_user\": \"onepassword:targetUser\"\
  ,\n        \"client\": \"onepassword:clientApplication\"\n      }\n    },\n\n    \"ItemUsage\": {\n      \"@id\": \"onepassword:ItemUsage\",\n      \"@context\": {\n        \"uuid\": \"schema:identifier\",\n        \"timestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"action\": \"schema:actionStatus\",\n        \"vault_uuid\": \"onepassword:vaultIdentifier\",\n        \"item_uuid\": \"onepassword:itemIdentifier\",\n        \"user\": \"schema:agent\"\n      }\n    },\n\n    \"AuditEvent\": {\n      \"@id\": \"onepassword:AuditEvent\",\n      \"@context\": {\n        \"uuid\": \"schema:identifier\",\n        \"timestamp\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"actor_uuid\": \"onepassword:actorIdentifier\",\n        \"action\": \"schema:actionStatus\",\n        \"object_type\": \"onepassword:objectType\",\n        \"object_uuid\": \"onepassword:objectIdentifier\"\
  \n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"onepassword:PartnerAccount\",\n      \"@context\": {\n        \"account_uid\": \"schema:identifier\",\n        \"account_type\": \"onepassword:accountType\",\n        \"domain\": {\n          \"@id\": \"schema:domainIncludes\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"onepassword:accountStatus\",\n        \"activation_token\": \"onepassword:activationToken\",\n        \"ends_at\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-context.jsonld
tags:
- Password Manager
- Passwords
- Security
- Secrets
- JSON-LD
- Linked Data
- Semantic Web
---
