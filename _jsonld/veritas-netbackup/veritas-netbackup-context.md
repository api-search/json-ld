---
class_count: 0
classes: []
context_file: json-ld/veritas-netbackup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/veritas-netbackup/refs/heads/main/json-ld/veritas-netbackup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Veritas Netbackup from Veritas NetBackup.
layout: jsonld
name: Veritas Netbackup Context
namespaces:
- prefix: nbu
  uri: https://sort.veritas.com/schemas/netbackup/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Job
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Client
  type: ''
- container: ''
  name: BackupImage
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: PolicyClient
  type: ''
- container: ''
  name: TryLog
  type: ''
- container: ''
  name: StorageUnit
  type: ''
property_count: 8
provider_name: Veritas NetBackup
provider_slug: veritas-netbackup
slug: veritas-netbackup-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nbu\": \"https://sort.veritas.com/schemas/netbackup/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Job\": {\n      \"@id\": \"nbu:Job\",\n      \"@context\": {\n        \"jobId\": \"nbu:jobId\",\n        \"parentJobId\": \"nbu:parentJobId\",\n        \"jobType\": \"nbu:jobType\",\n        \"state\": \"nbu:jobState\",\n        \"status\": \"nbu:statusCode\",\n        \"policyName\": \"nbu:policyName\",\n        \"policyType\": \"nbu:policyType\",\n        \"scheduleName\": \"nbu:scheduleName\",\n        \"scheduleType\": \"nbu:scheduleType\",\n        \"clientName\": \"nbu:clientName\",\n        \"mediaServer\": \"nbu:mediaServer\",\n        \"storageUnit\": \"nbu:storageUnit\",\n        \"startTime\": {\n          \"@id\": \"nbu:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n\
  \          \"@id\": \"nbu:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"elapsedTime\": \"nbu:elapsedTime\",\n        \"kilobytesTransferred\": \"nbu:kilobytesTransferred\",\n        \"filesTransferred\": \"nbu:filesTransferred\",\n        \"percentComplete\": \"nbu:percentComplete\",\n        \"currentOperation\": \"nbu:currentOperation\",\n        \"attempt\": \"nbu:attempt\",\n        \"restartable\": \"nbu:restartable\",\n        \"suspendable\": \"nbu:suspendable\",\n        \"resumable\": \"nbu:resumable\",\n        \"cancellable\": \"nbu:cancellable\",\n        \"backupId\": \"nbu:backupId\"\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"nbu:Policy\",\n      \"@context\": {\n        \"policyName\": \"nbu:policyName\",\n        \"policyType\": \"nbu:policyType\",\n        \"active\": \"nbu:active\",\n        \"effectiveDate\": {\n          \"@id\": \"nbu:effectiveDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"priority\": \"\
  nbu:priority\",\n        \"keyword\": \"nbu:keyword\",\n        \"dataClassification\": \"nbu:dataClassification\",\n        \"clients\": {\n          \"@id\": \"nbu:clients\",\n          \"@container\": \"@set\"\n        },\n        \"schedules\": {\n          \"@id\": \"nbu:schedules\",\n          \"@container\": \"@set\"\n        },\n        \"backupSelections\": {\n          \"@id\": \"nbu:backupSelections\",\n          \"@container\": \"@set\"\n        },\n        \"backupCopies\": {\n          \"@id\": \"nbu:backupCopies\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Client\": {\n      \"@id\": \"nbu:Client\",\n      \"@context\": {\n        \"hostName\": \"schema:name\",\n        \"hostType\": \"nbu:hostType\",\n        \"os\": \"nbu:operatingSystem\",\n        \"platform\": \"nbu:platform\",\n        \"version\": \"schema:softwareVersion\",\n        \"fingerprintSha256\": \"nbu:fingerprintSha256\",\n        \"trustLevel\": \"nbu:trustLevel\",\n    \
  \    \"communicationStatus\": \"nbu:communicationStatus\",\n        \"lastConnectedTime\": {\n          \"@id\": \"nbu:lastConnectedTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BackupImage\": {\n      \"@id\": \"nbu:BackupImage\",\n      \"@context\": {\n        \"backupId\": \"nbu:backupId\",\n        \"policyName\": \"nbu:policyName\",\n        \"policyType\": \"nbu:policyType\",\n        \"clientName\": \"nbu:clientName\",\n        \"scheduleName\": \"nbu:scheduleName\",\n        \"scheduleType\": \"nbu:scheduleType\",\n        \"backupTime\": {\n          \"@id\": \"nbu:backupTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationTime\": {\n          \"@id\": \"nbu:expirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"kilobytes\": \"nbu:kilobytes\",\n        \"numberOfFiles\": \"nbu:numberOfFiles\",\n        \"primaryCopy\": \"nbu:primaryCopy\",\n        \"copyCount\": \"nbu:copyCount\",\n   \
  \     \"mediaServer\": \"nbu:mediaServer\",\n        \"storageUnit\": \"nbu:storageUnit\",\n        \"mediaId\": \"nbu:mediaId\",\n        \"compressed\": \"nbu:compressed\",\n        \"encrypted\": \"nbu:encrypted\",\n        \"multiplexed\": \"nbu:multiplexed\",\n        \"retentionLevel\": \"nbu:retentionLevel\"\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"nbu:Schedule\",\n      \"@context\": {\n        \"scheduleName\": \"nbu:scheduleName\",\n        \"scheduleType\": \"nbu:scheduleType\",\n        \"frequency\": \"nbu:frequency\",\n        \"retentionPeriod\": \"nbu:retentionPeriod\",\n        \"storageUnit\": \"nbu:storageUnit\",\n        \"mediaMultiplexing\": \"nbu:mediaMultiplexing\",\n        \"syntheticBackup\": \"nbu:syntheticBackup\"\n      }\n    },\n\n    \"PolicyClient\": {\n      \"@id\": \"nbu:PolicyClient\",\n      \"@context\": {\n        \"clientName\": \"nbu:clientName\",\n        \"hardware\": \"nbu:hardware\",\n        \"operatingSystem\": \"nbu:operatingSystem\"\
  ,\n        \"priority\": \"nbu:clientPriority\"\n      }\n    },\n\n    \"TryLog\": {\n      \"@id\": \"nbu:TryLog\",\n      \"@context\": {\n        \"tryNumber\": \"nbu:tryNumber\",\n        \"pid\": \"nbu:processId\",\n        \"statusCode\": \"nbu:statusCode\",\n        \"statusMessage\": \"nbu:statusMessage\",\n        \"startTime\": {\n          \"@id\": \"nbu:tryStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"nbu:tryEndTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"mediaServer\": \"nbu:mediaServer\",\n        \"storageUnit\": \"nbu:storageUnit\",\n        \"kilobytesTransferred\": \"nbu:kilobytesTransferred\",\n        \"filesTransferred\": \"nbu:filesTransferred\"\n      }\n    },\n\n    \"StorageUnit\": {\n      \"@id\": \"nbu:StorageUnit\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"storageType\": \"nbu:storageType\",\n        \"mediaServer\": \"nbu:mediaServer\",\n\
  \        \"diskPool\": \"nbu:diskPool\",\n        \"maxConcurrentJobs\": \"nbu:maxConcurrentJobs\",\n        \"maxFragmentSize\": \"nbu:maxFragmentSize\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/veritas-netbackup/refs/heads/main/json-ld/veritas-netbackup-context.jsonld
tags:
- Backup
- Data Protection
- Disaster Recovery
- Enterprise
- Recovery
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
