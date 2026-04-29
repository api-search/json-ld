---
class_count: 9
classes:
- targetId
- targetName
- targetType
- hostName
- lifecycleStatus
- availabilityStatus
- severity
- priority
- status
context_file: json-ld/oracle-enterprise-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/json-ld/oracle-enterprise-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Enterprise Manager from Oracle Enterprise Manager.
layout: jsonld
name: Oracle Enterprise Manager Context
namespaces:
- prefix: oem
  uri: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Target
  type: ''
- container: ''
  name: Incident
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: Blackout
  type: ''
- container: ''
  name: BlackoutSchedule
  type: ''
- container: ''
  name: MetricGroup
  type: ''
- container: ''
  name: MetricColumn
  type: ''
- container: ''
  name: MetricDataPoint
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: GlobalTargetProperty
  type: ''
- container: ''
  name: canonicalLink
  type: reference
- container: ''
  name: timeCreated
  type: dateTime
- container: ''
  name: timeUpdated
  type: dateTime
property_count: 13
provider_name: Oracle Enterprise Manager
provider_slug: oracle-enterprise-manager
slug: oracle-enterprise-manager-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"oem\": \"https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Target\": {\n      \"@id\": \"oem:Target\",\n      \"@context\": {\n        \"targetId\": \"oem:targetId\",\n        \"targetName\": \"schema:name\",\n        \"targetType\": \"oem:targetType\",\n        \"targetDisplayType\": \"oem:targetDisplayType\",\n        \"hostName\": \"oem:hostName\",\n        \"lifecycleStatus\": \"oem:lifecycleStatus\",\n        \"availabilityStatus\": \"oem:availabilityStatus\",\n        \"agentUrl\": {\n          \"@id\": \"oem:agentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"oracleHome\": \"oem:oracleHome\",\n        \"machineName\": \"oem:machineName\",\n        \"installLocation\": \"oem:installLocation\"\
  ,\n        \"timezone\": \"oem:timezone\",\n        \"owner\": \"oem:owner\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"properties\": \"oem:properties\",\n        \"associations\": {\n          \"@id\": \"oem:associations\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Incident\": {\n      \"@id\": \"oem:Incident\",\n      \"@context\": {\n        \"incidentId\": \"oem:incidentId\",\n        \"summary\": \"schema:description\",\n        \"severity\": \"oem:severity\",\n        \"priority\": \"oem:priority\",\n        \"status\": \"oem:status\",\n        \"category\": \"oem:category\",\n        \"targetName\": \"oem:targetName\",\n        \"targetType\": \"oem:targetType\",\n        \"escalationLevel\": \"oem:escalationLevel\",\n        \"owner\": \"oem:owner\"\
  ,\n        \"acknowledgedBy\": \"oem:acknowledgedBy\",\n        \"resolutionState\": \"oem:resolutionState\",\n        \"ruleSetName\": \"oem:ruleSetName\",\n        \"timeRaised\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeResolved\": {\n          \"@id\": \"oem:timeResolved\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"eventCount\": \"oem:eventCount\"\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"oem:Event\",\n      \"@context\": {\n        \"eventId\": \"oem:eventId\",\n        \"eventType\": \"oem:eventType\",\n        \"severity\": \"oem:severity\",\n        \"message\": \"schema:description\",\n        \"targetName\": \"oem:targetName\",\n        \"targetType\": \"oem:targetType\",\n        \"metricGroupName\": \"oem:metricGroupName\",\n        \"metricColumnName\": \"\
  oem:metricColumnName\",\n        \"metricValue\": \"oem:metricValue\",\n        \"timeRaised\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeResolved\": {\n          \"@id\": \"oem:timeResolved\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Blackout\": {\n      \"@id\": \"oem:Blackout\",\n      \"@context\": {\n        \"blackoutId\": \"oem:blackoutId\",\n        \"blackoutName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"oem:status\",\n        \"reason\": \"oem:reason\",\n        \"createdBy\": \"dcterms:creator\",\n        \"schedule\": \"oem:schedule\",\n        \"targets\": {\n          \"@id\": \"oem:targets\",\n          \"@container\": \"@set\"\n        },\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeUpdated\": {\n          \"@id\": \"dcterms:modified\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BlackoutSchedule\": {\n      \"@id\": \"oem:BlackoutSchedule\",\n      \"@context\": {\n        \"startTime\": {\n          \"@id\": \"oem:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"oem:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"duration\": \"oem:duration\",\n        \"timezone\": \"oem:timezone\",\n        \"frequency\": \"oem:frequency\",\n        \"repeatInterval\": \"oem:repeatInterval\",\n        \"daysOfWeek\": {\n          \"@id\": \"oem:daysOfWeek\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"MetricGroup\": {\n      \"@id\": \"oem:MetricGroup\",\n      \"@context\": {\n        \"metricGroupName\": \"oem:metricGroupName\",\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"collectionFrequency\": \"oem:collectionFrequency\",\n\
  \        \"metricColumns\": {\n          \"@id\": \"oem:metricColumns\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MetricColumn\": {\n      \"@id\": \"oem:MetricColumn\",\n      \"@context\": {\n        \"columnName\": \"oem:columnName\",\n        \"displayName\": \"schema:name\",\n        \"columnType\": \"oem:columnType\",\n        \"isKey\": \"oem:isKey\",\n        \"unit\": \"oem:unit\"\n      }\n    },\n\n    \"MetricDataPoint\": {\n      \"@id\": \"oem:MetricDataPoint\",\n      \"@context\": {\n        \"metricColumn\": \"oem:metricColumn\",\n        \"value\": \"schema:value\",\n        \"key\": \"oem:key\",\n        \"collectionTime\": {\n          \"@id\": \"oem:collectionTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Annotation\": {\n      \"@id\": \"oem:Annotation\",\n      \"@context\": {\n        \"annotationId\": \"oem:annotationId\",\n        \"summary\": \"schema:name\",\n        \"details\": \"schema:description\"\
  ,\n        \"author\": \"dcterms:creator\",\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"GlobalTargetProperty\": {\n      \"@id\": \"oem:GlobalTargetProperty\",\n      \"@context\": {\n        \"globalTargetPropertyId\": \"oem:globalTargetPropertyId\",\n        \"propertyName\": \"schema:name\",\n        \"propertyDisplayName\": \"oem:propertyDisplayName\",\n        \"description\": \"schema:description\",\n        \"propertyType\": \"oem:propertyType\",\n        \"hasValidValues\": \"oem:hasValidValues\"\n      }\n    },\n\n    \"targetId\": \"oem:targetId\",\n    \"targetName\": \"schema:name\",\n    \"targetType\": \"oem:targetType\",\n    \"hostName\": \"oem:hostName\",\n    \"lifecycleStatus\": \"oem:lifecycleStatus\",\n    \"availabilityStatus\": \"oem:availabilityStatus\",\n    \"severity\": \"oem:severity\",\n    \"priority\": \"oem:priority\",\n    \"status\": \"oem:status\",\n\
  \    \"canonicalLink\": {\n      \"@id\": \"oem:canonicalLink\",\n      \"@type\": \"@id\"\n    },\n    \"timeCreated\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"timeUpdated\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/json-ld/oracle-enterprise-manager-context.jsonld
tags:
- Cloud Management
- Database Management
- Enterprise Management
- Infrastructure Management
- Monitoring
- Oracle
- JSON-LD
- Linked Data
- Semantic Web
---
