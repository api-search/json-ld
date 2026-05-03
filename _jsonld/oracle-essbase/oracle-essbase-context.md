---
api_specs:
- filename: oracle-essbase-rest-api-openapi.yml
  format: yaml
  label: Oracle Essbase REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/openapi/oracle-essbase-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-essbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/json-ld/oracle-essbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Essbase from Oracle Essbase.
layout: jsonld
name: Oracle Essbase Context
namespaces:
- prefix: essbase
  uri: https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/ns#
- prefix: olap
  uri: http://purl.org/linked-data/cube#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Dimension
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: Script
  type: ''
- container: ''
  name: Filter
  type: ''
- container: ''
  name: Connection
  type: ''
- container: ''
  name: Variable
  type: ''
- container: ''
  name: FileItem
  type: ''
- container: ''
  name: Lock
  type: ''
property_count: 13
provider_name: Oracle Essbase
provider_slug: oracle-essbase
slug: oracle-essbase-context
source_filename: oracle-essbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"essbase\": \"https://docs.oracle.com/en/database/other-databases/essbase/21/essrt/ns#\",\n    \"olap\": \"http://purl.org/linked-data/cube#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n\n    \"Application\": {\n      \"@id\": \"essbase:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"owner\": \"schema:creator\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"modifiedBy\": \"schema:editor\",\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\"\
  : \"xsd:long\"\n        },\n        \"status\": \"schema:status\",\n        \"type\": \"essbase:storageType\",\n        \"encrypted\": \"essbase:encrypted\",\n        \"connectedUsersCount\": \"essbase:connectedUsersCount\"\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"essbase:Database\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"application\": {\n          \"@id\": \"essbase:belongsToApplication\",\n          \"@type\": \"@id\"\n        },\n        \"owner\": \"schema:creator\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        },\n        \"modifiedBy\": \"schema:editor\",\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        },\n        \"status\": \"schema:status\",\n        \"type\": \"essbase:storageType\"\n      }\n    },\n\n    \"Dimension\": {\n      \"@id\": \"essbase:Dimension\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"essbase:dimensionType\",\n        \"storageType\": \"essbase:storageCategory\",\n        \"tag\": \"essbase:dimensionTag\",\n        \"memberCount\": \"essbase:memberCount\"\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"essbase:Job\",\n      \"@context\": {\n        \"job_ID\": \"schema:identifier\",\n        \"appName\": \"essbase:applicationName\",\n        \"dbName\": \"essbase:databaseName\",\n        \"jobType\": \"schema:additionalType\",\n        \"jobfileName\": \"essbase:scriptFileName\",\n        \"userName\": \"schema:creator\",\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:long\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:long\"\n        },\n        \"statusCode\": \"essbase:statusCode\",\n        \"statusMessage\": \"essbase:statusMessage\"\n      }\n    },\n\n    \"User\": {\n\
  \      \"@id\": \"essbase:User\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"role\": \"schema:roleName\",\n        \"groups\": \"schema:memberOf\"\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"essbase:Group\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"role\": \"schema:roleName\",\n        \"members\": \"schema:member\"\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"essbase:Session\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"sessionId\": \"essbase:sessionIdentifier\",\n        \"loginTimeInSeconds\": \"essbase:loginDuration\",\n        \"application\": \"essbase:activeApplication\",\n        \"database\": \"essbase:activeDatabase\",\n        \"connectionSource\": \"essbase:connectionSource\",\n        \"request\"\
  : \"essbase:activeRequestType\",\n        \"requestState\": \"essbase:requestState\"\n      }\n    },\n\n    \"Script\": {\n      \"@id\": \"essbase:Script\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"content\": \"schema:text\",\n        \"modifiedBy\": \"schema:editor\",\n        \"modifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"Filter\": {\n      \"@id\": \"essbase:SecurityFilter\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"rows\": \"essbase:filterRows\"\n      }\n    },\n\n    \"Connection\": {\n      \"@id\": \"essbase:Connection\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"essbase:connectionType\",\n        \"host\": \"essbase:databaseHost\",\n        \"port\": \"essbase:databasePort\",\n        \"serviceName\"\
  : \"essbase:serviceName\",\n        \"user\": \"essbase:databaseUser\"\n      }\n    },\n\n    \"Variable\": {\n      \"@id\": \"essbase:SubstitutionVariable\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"value\": \"schema:value\"\n      }\n    },\n\n    \"FileItem\": {\n      \"@id\": \"essbase:FileItem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"fullPath\": \"essbase:filePath\",\n        \"type\": \"essbase:fileType\"\n      }\n    },\n\n    \"Lock\": {\n      \"@id\": \"essbase:Lock\",\n      \"@context\": {\n        \"lockId\": \"schema:identifier\",\n        \"userId\": \"essbase:lockOwner\",\n        \"objectName\": \"essbase:lockedObject\",\n        \"lockType\": \"essbase:lockType\",\n        \"lockTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-essbase/refs/heads/main/json-ld/oracle-essbase-context.jsonld
tags:
- Analytics
- Budgeting
- Business Intelligence
- Financial Consolidation
- Multi-Dimensional Database
- OLAP
- Planning
- JSON-LD
- Linked Data
- Semantic Web
---
