---
api_specs:
- filename: google-tag-manager-api-v2-openapi.yml
  format: yaml
  label: Google Tag Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-tag-manager/refs/heads/main/openapi/google-tag-manager-api-v2-openapi.yml
class_count: 8
classes:
- gtmAccount
- gtmContainer
- gtmWorkspace
- gtmTag
- gtmTrigger
- gtmVariable
- gtmVersion
- gtmParameter
context_file: json-ld/google-tag-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-tag-manager/refs/heads/main/json-ld/google-tag-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Tag Manager from Google Tag Manager.
layout: jsonld
name: Google Tag Manager Context
namespaces:
- prefix: gtm
  uri: https://developers.google.com/tag-platform/tag-manager/api/reference/rest/v2/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Container
  type: ''
- container: ''
  name: Workspace
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: Trigger
  type: ''
- container: ''
  name: Variable
  type: ''
- container: ''
  name: ContainerVersion
  type: ''
- container: ''
  name: Parameter
  type: ''
property_count: 8
provider_name: Google Tag Manager
provider_slug: google-tag-manager
slug: google-tag-manager-context
source_filename: google-tag-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gtm\": \"https://developers.google.com/tag-platform/tag-manager/api/reference/rest/v2/\",\n    \"gtmAccount\": \"gtm:accounts#Account\",\n    \"gtmContainer\": \"gtm:accounts.containers#Container\",\n    \"gtmWorkspace\": \"gtm:accounts.containers.workspaces#Workspace\",\n    \"gtmTag\": \"gtm:accounts.containers.workspaces.tags#Tag\",\n    \"gtmTrigger\": \"gtm:accounts.containers.workspaces.triggers#Trigger\",\n    \"gtmVariable\": \"gtm:accounts.containers.workspaces.variables#Variable\",\n    \"gtmVersion\": \"gtm:accounts.containers.versions#ContainerVersion\",\n    \"gtmParameter\": \"gtm:Parameter\",\n    \"Account\": {\n      \"@id\": \"gtmAccount\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts#Account.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts#Account.accountId\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"shareData\": {\n          \"@id\": \"gtm:accounts#Account.shareData\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts#Account.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"features\": {\n          \"@id\": \"gtm:accounts#Account.features\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Container\": {\n      \"@id\": \"gtmContainer\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers#Container.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts.containers#Container.accountId\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers#Container.containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domainName\": {\n          \"@id\": \"gtm:accounts.containers#Container.domainName\",\n          \"@container\": \"@list\"\n        },\n        \"publicId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagIds\": {\n          \"@id\": \"gtm:accounts.containers#Container.tagIds\",\n          \"@container\": \"@list\"\n        },\n        \"notes\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usageContext\": {\n          \"@id\": \"gtm:accounts.containers#Container.usageContext\",\n          \"@container\": \"@list\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers#Container.fingerprint\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"taggingServerUrls\": {\n          \"@id\": \"gtm:accounts.containers#Container.taggingServerUrls\",\n          \"@container\": \"@list\"\n        },\n        \"features\": {\n          \"@id\": \"gtm:accounts.containers#Container.features\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Workspace\": {\n      \"@id\": \"gtmWorkspace\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers.workspaces#Workspace.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces#Workspace.accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces#Workspace.containerId\",\n          \"@type\": \"xsd:string\"\n  \
  \      },\n        \"workspaceId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces#Workspace.workspaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers.workspaces#Workspace.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Tag\": {\n      \"@id\": \"gtmTag\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.accountId\",\n  \
  \        \"@type\": \"xsd:string\"\n        },\n        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workspaceId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.workspaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"liveOnly\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.liveOnly\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"notes\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n  \
  \      \"scheduleStartMs\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.scheduleStartMs\",\n          \"@type\": \"xsd:long\"\n        },\n        \"scheduleEndMs\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.scheduleEndMs\",\n          \"@type\": \"xsd:long\"\n        },\n        \"parameter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.parameter\",\n          \"@container\": \"@list\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firingTriggerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.firingTriggerId\",\n          \"@container\": \"@list\"\n        },\n        \"blockingTriggerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.blockingTriggerId\",\n          \"@container\": \"@list\"\n        },\n        \"parentFolderId\": {\n\
  \          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.parentFolderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagFiringOption\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.tagFiringOption\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"paused\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.paused\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"consentSettings\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.tags#Tag.consentSettings\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Trigger\": {\n      \"@id\": \"gtmTrigger\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\"\
  : \"gtm:accounts.containers.workspaces.triggers#Trigger.accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workspaceId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.workspaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"triggerId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customEventFilter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.customEventFilter\",\n          \"@container\": \"@list\"\n     \
  \   },\n        \"filter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.filter\",\n          \"@container\": \"@list\"\n        },\n        \"autoEventFilter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.autoEventFilter\",\n          \"@container\": \"@list\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentFolderId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.parentFolderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"notes\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.triggers#Trigger.parameter\"\
  ,\n          \"@container\": \"@list\"\n        }\n      }\n    },\n    \"Variable\": {\n      \"@id\": \"gtmVariable\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workspaceId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.workspaceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"variableId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"notes\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scheduleStartMs\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.scheduleStartMs\",\n          \"@type\": \"xsd:long\"\n        },\n        \"scheduleEndMs\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.scheduleEndMs\",\n          \"@type\": \"xsd:long\"\n        },\n        \"parameter\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.parameter\",\n          \"@container\": \"@list\"\n        },\n        \"enablingTriggerId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.enablingTriggerId\",\n          \"@container\": \"@list\"\n        },\n        \"disablingTriggerId\"\
  : {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.disablingTriggerId\",\n          \"@container\": \"@list\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentFolderId\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.parentFolderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"formatValue\": {\n          \"@id\": \"gtm:accounts.containers.workspaces.variables#Variable.formatValue\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"ContainerVersion\": {\n      \"@id\": \"gtmVersion\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"gtm:accounts.containers.versions#ContainerVersion.path\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"accountId\": {\n          \"@id\": \"gtm:accounts.containers.versions#ContainerVersion.accountId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"containerId\": {\n          \"@id\": \"gtm:accounts.containers.versions#ContainerVersion.containerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"containerVersionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fingerprint\": {\n          \"@id\": \"gtm:accounts.containers.versions#ContainerVersion.fingerprint\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tagManagerUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"deleted\": {\n          \"\
  @id\": \"gtm:accounts.containers.versions#ContainerVersion.deleted\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"Parameter\": {\n      \"@id\": \"gtmParameter\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"gtm:Parameter.type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"key\": {\n          \"@id\": \"gtm:Parameter.key\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"gtm:Parameter.value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"list\": {\n          \"@id\": \"gtm:Parameter.list\",\n          \"@container\": \"@list\"\n        },\n        \"map\": {\n          \"@id\": \"gtm:Parameter.map\",\n          \"@container\": \"@list\"\n        },\n        \"isWeakReference\": {\n          \"@id\": \"gtm:Parameter.isWeakReference\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\"\
  : \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-tag-manager/refs/heads/main/json-ld/google-tag-manager-context.jsonld
tags:
- Analytics
- Conversion Tracking
- Marketing
- Tag Management
- Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
