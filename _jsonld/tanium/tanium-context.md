---
api_specs:
- filename: tanium-platform-rest-api-openapi.yml
  format: yaml
  label: Tanium Platform REST API
  slug: platform-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-platform-rest-api-openapi.yml
- filename: tanium-threat-response-api-openapi.yml
  format: yaml
  label: Tanium Threat Response API
  slug: threat-response-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-threat-response-api-openapi.yml
- filename: tanium-connect-api-openapi.yml
  format: yaml
  label: Tanium Connect API
  slug: connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/openapi/tanium-connect-api-openapi.yml
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/tanium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/json-ld/tanium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tanium from Tanium.
layout: jsonld
name: Tanium Context
namespaces:
- prefix: tanium
  uri: https://developer.tanium.com/schema/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: stix
  uri: https://docs.oasis-open.org/cti/stix/v2.1/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Question
  type: ''
- container: ''
  name: SavedQuestion
  type: ''
- container: ''
  name: Sensor
  type: ''
- container: ''
  name: Package
  type: ''
- container: ''
  name: Action
  type: ''
- container: ''
  name: Alert
  type: ''
- container: ''
  name: IntelDocument
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Evidence
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: modTime
  type: dateTime
property_count: 13
provider_name: Tanium
provider_slug: tanium
slug: tanium-context
source_filename: tanium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tanium\": \"https://developer.tanium.com/schema/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"stix\": \"https://docs.oasis-open.org/cti/stix/v2.1/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Endpoint\": {\n      \"@id\": \"tanium:Endpoint\",\n      \"@context\": {\n        \"computerName\": \"schema:name\",\n        \"computerID\": \"schema:identifier\",\n        \"ipAddress\": \"schema:url\",\n        \"ipAddresses\": {\n          \"@id\": \"tanium:ipAddresses\",\n          \"@container\": \"@set\"\n        },\n        \"macAddress\": \"tanium:macAddress\",\n        \"operatingSystem\": \"schema:operatingSystem\",\n        \"osPlatform\": \"tanium:osPlatform\",\n        \"manufacturer\": \"schema:manufacturer\",\n        \"model\": \"schema:model\",\n        \"serialNumber\": \"schema:serialNumber\",\n        \"domainName\"\
  : \"tanium:domainName\",\n        \"lastRegistration\": {\n          \"@id\": \"tanium:lastRegistration\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"taniumClientVersion\": \"schema:softwareVersion\",\n        \"isVirtual\": \"tanium:isVirtual\",\n        \"chassisType\": \"tanium:chassisType\",\n        \"totalMemory\": \"tanium:totalMemory\",\n        \"diskSpace\": \"tanium:diskSpace\",\n        \"freeDiskSpace\": \"tanium:freeDiskSpace\",\n        \"installedApplications\": {\n          \"@id\": \"schema:softwareRequirements\",\n          \"@container\": \"@set\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Question\": {\n      \"@id\": \"tanium:Question\",\n      \"@context\": {\n        \"queryText\": \"schema:query\",\n        \"expiration\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"selects\": {\n\
  \          \"@id\": \"tanium:selects\",\n          \"@container\": \"@list\"\n        },\n        \"group\": \"tanium:targetGroup\",\n        \"savedQuestion\": \"tanium:savedQuestion\"\n      }\n    },\n\n    \"SavedQuestion\": {\n      \"@id\": \"tanium:SavedQuestion\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"queryText\": \"schema:query\",\n        \"issueSeconds\": \"tanium:issueSeconds\",\n        \"expireSeconds\": \"tanium:expireSeconds\",\n        \"modTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Sensor\": {\n      \"@id\": \"tanium:Sensor\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"hash\": \"tanium:sensorHash\",\n        \"maxAgeSeconds\": \"tanium:maxAgeSeconds\",\n        \"contentSet\": \"tanium:contentSet\",\n        \"queries\": {\n     \
  \     \"@id\": \"tanium:queries\",\n          \"@container\": \"@set\"\n        },\n        \"parameters\": {\n          \"@id\": \"tanium:parameters\",\n          \"@container\": \"@set\"\n        },\n        \"modTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"creationTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"tanium:Package\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"command\": \"tanium:command\",\n        \"commandTimeout\": \"tanium:commandTimeout\",\n        \"expireSeconds\": \"tanium:expireSeconds\",\n        \"contentSet\": \"tanium:contentSet\",\n        \"files\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        },\n        \"parameters\": {\n          \"@id\": \"tanium:parameters\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"modTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"creationTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Action\": {\n      \"@id\": \"tanium:Action\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"tanium:actionStatus\",\n        \"packageSpec\": \"tanium:packageSpec\",\n        \"actionGroup\": \"tanium:actionGroup\",\n        \"targetGroup\": \"tanium:targetGroup\",\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationTime\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"approvedFlag\": \"tanium:approvedFlag\"\n      }\n    },\n\n    \"Alert\": {\n      \"@id\": \"tanium:ThreatAlert\",\n      \"\
  @context\": {\n        \"priority\": \"tanium:alertPriority\",\n        \"severity\": \"tanium:alertSeverity\",\n        \"type\": \"dcterms:type\",\n        \"state\": \"tanium:alertState\",\n        \"computerName\": \"schema:name\",\n        \"computerIpAddress\": \"tanium:ipAddress\",\n        \"guid\": \"schema:identifier\",\n        \"intelDocId\": \"tanium:intelDocId\",\n        \"alertedAt\": {\n          \"@id\": \"tanium:alertedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"IntelDocument\": {\n      \"@id\": \"tanium:IntelDocument\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"dcterms:type\",\n        \"alertCount\": \"\
  tanium:alertCount\",\n        \"unresolvedAlertCount\": \"tanium:unresolvedAlertCount\",\n        \"labelIds\": {\n          \"@id\": \"tanium:labelIds\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"tanium:ConnectConnection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"enabled\": \"tanium:enabled\",\n        \"source\": \"tanium:dataSource\",\n        \"destination\": \"tanium:dataDestination\",\n        \"format\": \"tanium:outputFormat\",\n        \"schedule\": \"tanium:schedule\",\n        \"lastRunStatus\": \"tanium:lastRunStatus\",\n        \"lastRunTime\": {\n          \"@id\": \"tanium:lastRunTime\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Evidence\": {\n      \"@id\": \"tanium:Evidence\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"hostname\": \"tanium:hostname\",\n        \"evidenceType\": \"dcterms:type\",\n        \"summary\": \"schema:description\",\n        \"size\": \"schema:contentSize\",\n        \"username\": \"tanium:username\",\n        \"commandline\": \"tanium:commandline\",\n        \"timestamp\": {\n          \"@id\": \"tanium:eventTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"id\": \"schema:identifier\",\n\
  \    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tanium/refs/heads/main/json-ld/tanium-context.jsonld
tags:
- Compliance
- Endpoint Management
- Patch Management
- Security
- Threat Detection
- Unified Endpoint Management
- JSON-LD
- Linked Data
- Semantic Web
---
