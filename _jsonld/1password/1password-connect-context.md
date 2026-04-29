---
class_count: 15
classes:
- APIRequest
- Field
- File
- FullItem
- GeneratorRecipe
- Item
- SectionRef
- Section
- ServerHealth
- Url
- VaultRef
- Vault
- description
- name
- version
context_file: json-ld/1password-connect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-connect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for 1Password Connect from 1Password.
layout: jsonld
name: 1Password Connect Context
namespaces:
- prefix: onepassword
  uri: https://1password.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: account
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actor
  type: reference
- container: ''
  name: attributeVersion
  type: integer
- container: ''
  name: category
  type: string
- container: set
  name: characterSets
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: contentVersion
  type: integer
- container: ''
  name: contentPath
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: set
  name: dependencies
  type: reference
- container: ''
  name: entropy
  type: decimal
- container: ''
  name: excludeCharacters
  type: string
- container: ''
  name: favorite
  type: boolean
- container: ''
  name: generate
  type: boolean
- container: ''
  name: href
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: item
  type: reference
- container: ''
  name: itemVersion
  type: integer
- container: ''
  name: items
  type: integer
- container: ''
  name: jti
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: lastEditedBy
  type: string
- container: ''
  name: length
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: primary
  type: boolean
- container: ''
  name: purpose
  type: string
- container: ''
  name: recipe
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: requestIp
  type: string
- container: ''
  name: resource
  type: reference
- container: ''
  name: result
  type: string
- container: ''
  name: section
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: set
  name: urls
  type: string
- container: ''
  name: userAgent
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: vault
  type: string
property_count: 46
provider_name: 1Password
provider_slug: 1password
slug: 1password-connect-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"onepassword\": \"https://1password.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"APIRequest\": \"onepassword:APIRequest\",\n    \"Field\": \"onepassword:Field\",\n    \"File\": \"onepassword:File\",\n    \"FullItem\": \"onepassword:FullItem\",\n    \"GeneratorRecipe\": \"onepassword:GeneratorRecipe\",\n    \"Item\": \"onepassword:Item\",\n    \"SectionRef\": \"onepassword:SectionRef\",\n    \"Section\": \"onepassword:Section\",\n    \"ServerHealth\": \"onepassword:ServerHealth\",\n    \"Url\": \"onepassword:Url\",\n    \"VaultRef\": \"onepassword:VaultRef\",\n    \"Vault\": \"onepassword:Vault\",\n    \"account\": {\n      \"@id\": \"onepassword:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"onepassword:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actor\"\
  : {\n      \"@id\": \"onepassword:actor\",\n      \"@type\": \"@id\"\n    },\n    \"attributeVersion\": {\n      \"@id\": \"onepassword:attributeVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"onepassword:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characterSets\": {\n      \"@id\": \"onepassword:characterSets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"onepassword:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentVersion\": {\n      \"@id\": \"onepassword:contentVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"contentPath\": {\n      \"@id\": \"onepassword:content_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"onepassword:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"dependencies\": {\n      \"@id\": \"onepassword:dependencies\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"@id\"\n    },\n    \"description\": \"schema:description\",\n    \"entropy\": {\n      \"@id\": \"onepassword:entropy\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"excludeCharacters\": {\n      \"@id\": \"onepassword:excludeCharacters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"favorite\": {\n      \"@id\": \"onepassword:favorite\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"generate\": {\n      \"@id\": \"onepassword:generate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"href\": {\n      \"@id\": \"onepassword:href\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"onepassword:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"item\": {\n      \"@id\": \"onepassword:item\",\n      \"@type\": \"@id\"\n    },\n    \"itemVersion\": {\n      \"@id\": \"onepassword:itemVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"onepassword:items\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"jti\":\
  \ {\n      \"@id\": \"onepassword:jti\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"onepassword:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEditedBy\": {\n      \"@id\": \"onepassword:lastEditedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"onepassword:length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"onepassword:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"primary\": {\n      \"@id\": \"onepassword:primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"purpose\": {\n      \"@id\": \"onepassword:purpose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipe\": {\n      \"@id\": \"onepassword:recipe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"onepassword:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestIp\": {\n      \"@id\": \"onepassword:requestIp\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"onepassword:resource\",\n      \"@type\": \"@id\"\n    },\n    \"result\": {\n      \"@id\": \"onepassword:result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"section\": {\n      \"@id\": \"onepassword:section\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"onepassword:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"onepassword:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"onepassword:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"onepassword:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"onepassword:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"onepassword:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"title\": {\n    \
  \  \"@id\": \"onepassword:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"onepassword:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"onepassword:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"urls\": {\n      \"@id\": \"onepassword:urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAgent\": {\n      \"@id\": \"onepassword:userAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"onepassword:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vault\": {\n      \"@id\": \"onepassword:vault\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/1password/refs/heads/main/json-ld/1password-connect-context.jsonld
tags:
- Password Manager
- Passwords
- Security
- Secrets
- JSON-LD
- Linked Data
- Semantic Web
---
