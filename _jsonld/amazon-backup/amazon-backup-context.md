---
class_count: 0
classes: []
context_file: json-ld/amazon-backup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/json-ld/amazon-backup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Backup from Amazon Backup.
layout: jsonld
name: Amazon Backup Context
namespaces:
- prefix: backup
  uri: https://docs.aws.amazon.com/aws-backup/latest/devguide/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: BackupPlan
  type: ''
- container: ''
  name: BackupVault
  type: ''
- container: ''
  name: BackupJob
  type: ''
- container: ''
  name: RecoveryPoint
  type: ''
property_count: 4
provider_name: Amazon Backup
provider_slug: amazon-backup
slug: amazon-backup-context
source_filename: amazon-backup-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"backup\": \"https://docs.aws.amazon.com/aws-backup/latest/devguide/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"BackupPlan\": {\n      \"@id\": \"backup:BackupPlan\",\n      \"@context\": {\n        \"backupPlanName\": \"schema:name\",\n        \"backupPlanId\": \"backup:backupPlanId\",\n        \"backupPlanArn\": \"backup:backupPlanArn\",\n        \"rules\": {\n          \"@id\": \"backup:rules\",\n          \"@container\": \"@set\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BackupVault\": {\n      \"@id\": \"backup:BackupVault\",\n      \"@context\": {\n        \"backupVaultName\": \"schema:name\",\n        \"backupVaultArn\": \"backup:backupVaultArn\",\n        \"numberOfRecoveryPoints\": {\n    \
  \      \"@id\": \"backup:numberOfRecoveryPoints\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"BackupJob\": {\n      \"@id\": \"backup:BackupJob\",\n      \"@context\": {\n        \"backupJobId\": \"backup:backupJobId\",\n        \"state\": \"backup:state\",\n        \"resourceArn\": \"backup:resourceArn\",\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completionDate\": {\n          \"@id\": \"backup:completionDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"RecoveryPoint\": {\n      \"@id\": \"backup:RecoveryPoint\",\n      \"@context\": {\n        \"recoveryPointArn\": \"backup:recoveryPointArn\",\n        \"backupVaultName\": \"backup:backupVaultName\",\n        \"resourceArn\": \"backup:resourceArn\",\n        \"status\": \"backup:status\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-backup/refs/heads/main/json-ld/amazon-backup-context.jsonld
tags:
- AWS
- Backup
- Data Protection
- Disaster Recovery
- Storage
- Compliance
- Governance
- Business Continuity
- JSON-LD
- Linked Data
- Semantic Web
---
