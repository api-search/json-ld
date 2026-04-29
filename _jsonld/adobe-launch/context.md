---
class_count: 67
classes:
- id
- type
- Company
- Property
- Rule
- RuleComponent
- DataElement
- Extension
- ExtensionPackage
- Library
- Build
- Environment
- Host
- Callback
- Secret
- AuditEvent
- attributes
- relationships
- links
- meta
- name
- description
- version
- enabled
- published
- dirty
- privacy
- ssl_enabled
- development
- rule_component_sequencing_enabled
- undefined_vars_return_empty
- delegate_descriptor_id
- settings
- default_value
- storage_duration
- force_lower_case
- clean_text
- order
- rule_order
- timeout
- delay_next
- negate
- display_name
- author
- availability
- discontinued
- state
- build_required
- status
- token
- error_message
- stage
- archive
- path
- library_name
- library_path
- type_of
- server
- port
- username
- encrypted_private_key
- skip_symlinks
- credentials
- revision_number
- org_id
- cjm_enabled
- edge_enabled
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Adobe Launch.
layout: jsonld
name: context Context
namespaces:
- prefix: adobe
  uri: https://ns.adobe.com/experience-platform/tags/
- prefix: jsonapi
  uri: https://jsonapi.org/format/#document-
- prefix: xdm
  uri: https://ns.adobe.com/xdm/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: platform
  type: string
- container: list
  name: domains
  type: ''
- container: ''
  name: exchange_url
  type: reference
- container: list
  name: subscriptions
  type: ''
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: deleted_at
  type: dateTime
- container: ''
  name: published_at
  type: dateTime
- container: ''
  name: property
  type: reference
- container: ''
  name: company
  type: reference
- container: ''
  name: extension
  type: reference
- container: ''
  name: extension_package
  type: reference
- container: set
  name: rule_components
  type: reference
- container: set
  name: data_elements
  type: reference
- container: set
  name: extensions
  type: reference
- container: set
  name: rules
  type: reference
- container: set
  name: libraries
  type: reference
- container: set
  name: builds
  type: reference
- container: set
  name: environments
  type: reference
- container: set
  name: hosts
  type: reference
- container: set
  name: callbacks
  type: reference
- container: set
  name: secrets
  type: reference
- container: set
  name: revisions
  type: reference
- container: ''
  name: origin
  type: reference
- container: ''
  name: environment
  type: reference
- container: ''
  name: host
  type: reference
- container: ''
  name: library
  type: reference
- container: ''
  name: self
  type: reference
- container: ''
  name: related
  type: reference
property_count: 30
provider_name: Adobe Launch
provider_slug: adobe-launch
slug: context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"adobe\": \"https://ns.adobe.com/experience-platform/tags/\",\n    \"jsonapi\": \"https://jsonapi.org/format/#document-\",\n    \"xdm\": \"https://ns.adobe.com/xdm/\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Company\": \"adobe:Company\",\n    \"Property\": \"adobe:Property\",\n    \"Rule\": \"adobe:Rule\",\n    \"RuleComponent\": \"adobe:RuleComponent\",\n    \"DataElement\": \"adobe:DataElement\",\n    \"Extension\": \"adobe:Extension\",\n    \"ExtensionPackage\": \"adobe:ExtensionPackage\",\n    \"Library\": \"adobe:Library\",\n    \"Build\": \"adobe:Build\",\n    \"Environment\": \"adobe:Environment\",\n    \"Host\": \"adobe:Host\",\n    \"Callback\": \"adobe:Callback\",\n    \"Secret\": \"adobe:Secret\",\n    \"AuditEvent\": \"adobe:AuditEvent\",\n\n    \"attributes\": \"adobe:attributes\",\n    \"relationships\": \"adobe:relationships\",\n    \"links\": \"adobe:links\",\n    \"meta\"\
  : \"adobe:meta\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"version\": \"schema:version\",\n    \"enabled\": \"adobe:enabled\",\n    \"published\": \"adobe:published\",\n    \"dirty\": \"adobe:dirty\",\n\n    \"platform\": {\n      \"@id\": \"adobe:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domains\": {\n      \"@id\": \"adobe:domains\",\n      \"@container\": \"@list\"\n    },\n    \"privacy\": \"adobe:privacy\",\n    \"ssl_enabled\": \"adobe:sslEnabled\",\n    \"development\": \"adobe:development\",\n    \"rule_component_sequencing_enabled\": \"adobe:ruleComponentSequencingEnabled\",\n    \"undefined_vars_return_empty\": \"adobe:undefinedVarsReturnEmpty\",\n\n    \"delegate_descriptor_id\": \"adobe:delegateDescriptorId\",\n    \"settings\": \"adobe:settings\",\n    \"default_value\": \"adobe:defaultValue\",\n    \"storage_duration\": \"adobe:storageDuration\"\
  ,\n    \"force_lower_case\": \"adobe:forceLowerCase\",\n    \"clean_text\": \"adobe:cleanText\",\n\n    \"order\": \"adobe:order\",\n    \"rule_order\": \"adobe:ruleOrder\",\n    \"timeout\": \"adobe:timeout\",\n    \"delay_next\": \"adobe:delayNext\",\n    \"negate\": \"adobe:negate\",\n\n    \"display_name\": \"adobe:displayName\",\n    \"author\": \"schema:author\",\n    \"availability\": \"adobe:availability\",\n    \"discontinued\": \"adobe:discontinued\",\n    \"exchange_url\": {\n      \"@id\": \"adobe:exchangeUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"state\": \"adobe:state\",\n    \"build_required\": \"adobe:buildRequired\",\n\n    \"status\": \"adobe:status\",\n    \"token\": \"adobe:token\",\n    \"error_message\": \"adobe:errorMessage\",\n\n    \"stage\": \"adobe:stage\",\n    \"archive\": \"adobe:archive\",\n    \"path\": \"adobe:path\",\n    \"library_name\": \"adobe:libraryName\",\n    \"library_path\": \"adobe:libraryPath\",\n\n    \"type_of\": \"adobe:typeOf\",\n\
  \    \"server\": \"adobe:server\",\n    \"port\": \"adobe:port\",\n    \"username\": \"adobe:username\",\n    \"encrypted_private_key\": \"adobe:encryptedPrivateKey\",\n    \"skip_symlinks\": \"adobe:skipSymlinks\",\n\n    \"subscriptions\": {\n      \"@id\": \"adobe:subscriptions\",\n      \"@container\": \"@list\"\n    },\n\n    \"credentials\": \"adobe:credentials\",\n\n    \"revision_number\": \"adobe:revisionNumber\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deleted_at\": {\n      \"@id\": \"adobe:dateDeleted\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"published_at\": {\n      \"@id\": \"adobe:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"org_id\": \"adobe:organizationId\",\n    \"cjm_enabled\": \"adobe:cjmEnabled\",\n    \"edge_enabled\": \"adobe:edgeEnabled\",\n\n    \"property\"\
  : {\n      \"@id\": \"adobe:property\",\n      \"@type\": \"@id\"\n    },\n    \"company\": {\n      \"@id\": \"adobe:company\",\n      \"@type\": \"@id\"\n    },\n    \"extension\": {\n      \"@id\": \"adobe:extension\",\n      \"@type\": \"@id\"\n    },\n    \"extension_package\": {\n      \"@id\": \"adobe:extensionPackage\",\n      \"@type\": \"@id\"\n    },\n    \"rule_components\": {\n      \"@id\": \"adobe:ruleComponents\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"data_elements\": {\n      \"@id\": \"adobe:dataElements\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"extensions\": {\n      \"@id\": \"adobe:extensions\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"rules\": {\n      \"@id\": \"adobe:rules\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"libraries\": {\n      \"@id\": \"adobe:libraries\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n\
  \    },\n    \"builds\": {\n      \"@id\": \"adobe:builds\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"environments\": {\n      \"@id\": \"adobe:environments\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"hosts\": {\n      \"@id\": \"adobe:hosts\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"callbacks\": {\n      \"@id\": \"adobe:callbacks\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"secrets\": {\n      \"@id\": \"adobe:secrets\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"revisions\": {\n      \"@id\": \"adobe:revisions\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"origin\": {\n      \"@id\": \"adobe:origin\",\n      \"@type\": \"@id\"\n    },\n    \"environment\": {\n      \"@id\": \"adobe:environment\",\n      \"@type\": \"@id\"\n    },\n    \"host\": {\n      \"@id\": \"adobe:host\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"library\": {\n      \"@id\": \"adobe:library\",\n      \"@type\": \"@id\"\n    },\n\n    \"self\": {\n      \"@id\": \"jsonapi:links-self\",\n      \"@type\": \"@id\"\n    },\n    \"related\": {\n      \"@id\": \"jsonapi:links-related\",\n      \"@type\": \"@id\"\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/json-ld/context.jsonld
tags:
- Data Collection
- Edge Network
- Event Forwarding
- Marketing Technology
- Tag Management
- JSON-LD
- Linked Data
- Semantic Web
---
