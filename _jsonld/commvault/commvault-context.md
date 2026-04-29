---
api_specs:
- filename: commvault-rest-openapi.yml
  format: yaml
  label: Commvault REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-rest-openapi.yml
- filename: commvault-command-center-openapi.yml
  format: yaml
  label: Commvault Command Center API
  slug: command-center-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-command-center-openapi.yml
- filename: commvault-automation-openapi.yml
  format: yaml
  label: Commvault Automation API
  slug: automation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-automation-openapi.yml
class_count: 0
classes: []
context_file: json-ld/commvault-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/json-ld/commvault-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Commvault from Commvault.
layout: jsonld
name: Commvault Context
namespaces:
- prefix: commvault
  uri: https://api.commvault.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Client
  type: ''
- container: ''
  name: BackupJob
  type: ''
- container: ''
  name: Subclient
  type: ''
- container: ''
  name: StoragePolicy
  type: ''
- container: ''
  name: Plan
  type: ''
- container: ''
  name: VirtualMachine
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: StoragePool
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: User
  type: ''
property_count: 10
provider_name: Commvault
provider_slug: commvault
slug: commvault-context
source_filename: commvault-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"commvault\": \"https://api.commvault.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Client\": {\n      \"@id\": \"commvault:Client\",\n      \"@context\": {\n        \"clientName\": \"schema:name\",\n        \"hostName\": \"commvault:hostName\",\n        \"displayName\": \"schema:alternateName\",\n        \"osType\": \"commvault:osType\",\n        \"clientType\": \"commvault:clientType\",\n        \"enableBackup\": {\n          \"@id\": \"commvault:enableBackup\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enableRestore\": {\n          \"@id\": \"commvault:enableRestore\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"BackupJob\": {\n      \"@id\": \"commvault:BackupJob\",\n      \"@context\": {\n        \"jobType\": \"commvault:jobType\",\n        \"status\"\
  : \"commvault:jobStatus\",\n        \"backupLevel\": \"commvault:backupLevel\",\n        \"percentComplete\": {\n          \"@id\": \"commvault:percentComplete\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sizeOfBackupBytes\": {\n          \"@id\": \"commvault:sizeOfBackup\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Subclient\": {\n      \"@id\": \"commvault:Subclient\",\n      \"@context\": {\n        \"subclientName\": \"schema:name\",\n        \"clientName\": \"commvault:clientName\",\n        \"appName\": \"commvault:appName\",\n        \"storagePolicyName\": \"commvault:storagePolicyName\"\n      }\n    },\n\n    \"StoragePolicy\": {\n      \"@id\": \"commvault:StoragePolicy\",\n      \"@context\":\
  \ {\n        \"storagePolicyName\": \"schema:name\",\n        \"retainBackupDataForDays\": {\n          \"@id\": \"commvault:retainBackupDataForDays\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"retainBackupDataForCycles\": {\n          \"@id\": \"commvault:retainBackupDataForCycles\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Plan\": {\n      \"@id\": \"commvault:Plan\",\n      \"@context\": {\n        \"planName\": \"schema:name\",\n        \"rpoInMinutes\": {\n          \"@id\": \"commvault:rpoInMinutes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"retainBackupDataForDays\": {\n          \"@id\": \"commvault:retainBackupDataForDays\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"VirtualMachine\": {\n      \"@id\": \"commvault:VirtualMachine\",\n      \"@context\": {\n        \"vmName\": \"schema:name\",\n        \"vmUUID\": \"schema:identifier\",\n        \"vmStatus\": \"commvault:vmStatus\"\
  ,\n        \"lastBackupTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"vmSize\": {\n          \"@id\": \"commvault:vmSize\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"commvault:Workflow\",\n      \"@context\": {\n        \"workflowName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": {\n          \"@id\": \"commvault:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"workflowType\": \"commvault:workflowType\"\n      }\n    },\n\n    \"StoragePool\": {\n      \"@id\": \"commvault:StoragePool\",\n      \"@context\": {\n        \"storagePoolName\": \"schema:name\",\n        \"storageType\": \"commvault:storageType\",\n        \"totalCapacityGB\": {\n          \"@id\": \"commvault:totalCapacityGB\",\n          \"@type\": \"xsd:float\"\n        },\n        \"usedCapacityGB\": {\n          \"@id\": \"\
  commvault:usedCapacityGB\",\n          \"@type\": \"xsd:float\"\n        },\n        \"freeCapacityGB\": {\n          \"@id\": \"commvault:freeCapacityGB\",\n          \"@type\": \"xsd:float\"\n        }\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"commvault:Alert\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"severity\": \"commvault:severity\",\n        \"alertType\": {\n          \"@id\": \"commvault:alertType\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"commvault:User\",\n      \"@context\": {\n        \"userName\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"description\": \"schema:description\",\n        \"enabled\": {\n          \"@id\": \"commvault:enabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/json-ld/commvault-context.jsonld
tags:
- Backup
- Cloud Storage
- Cyber Recovery
- Data Management
- Data Protection
- Disaster Recovery
- Enterprise Software
- JSON-LD
- Linked Data
- Semantic Web
---
