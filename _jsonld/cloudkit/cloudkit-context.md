---
class_count: 0
classes: []
context_file: json-ld/cloudkit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloudkit/refs/heads/main/json-ld/cloudkit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloudkit from Apple CloudKit.
layout: jsonld
name: Cloudkit Context
namespaces:
- prefix: cloudkit
  uri: https://api.apple-cloudkit.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Container
  type: ''
- container: ''
  name: Database
  type: ''
- container: ''
  name: Zone
  type: ''
- container: ''
  name: Record
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Query
  type: ''
property_count: 8
provider_name: Apple CloudKit
provider_slug: cloudkit
slug: cloudkit-context
source_filename: cloudkit-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cloudkit\": \"https://api.apple-cloudkit.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Container\": {\n      \"@id\": \"cloudkit:Container\",\n      \"@context\": {\n        \"containerIdentifier\": \"cloudkit:container_identifier\",\n        \"environment\": \"cloudkit:environment\"\n      }\n    },\n\n    \"Database\": {\n      \"@id\": \"cloudkit:Database\",\n      \"@context\": {\n        \"databaseScope\": \"cloudkit:database_scope\"\n      }\n    },\n\n    \"Zone\": {\n      \"@id\": \"cloudkit:Zone\",\n      \"@context\": {\n        \"zoneID\": \"cloudkit:zone_id\",\n        \"ownerRecordName\": \"cloudkit:owner_record_name\",\n        \"atomic\": \"cloudkit:atomic\",\n        \"syncToken\": \"cloudkit:sync_token\"\n      }\n    },\n\n    \"Record\": {\n      \"@id\": \"cloudkit:Record\",\n      \"@context\"\
  : {\n        \"recordName\": \"cloudkit:record_name\",\n        \"recordType\": \"schema:additionalType\",\n        \"recordChangeTag\": \"cloudkit:record_change_tag\",\n        \"fields\": \"cloudkit:fields\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"cloudkit:Asset\",\n      \"@context\": {\n        \"fileChecksum\": \"cloudkit:file_checksum\",\n        \"size\": \"schema:contentSize\",\n        \"downloadURL\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"cloudkit:Subscription\",\n      \"@context\": {\n        \"subscriptionID\": \"cloudkit:subscription_id\",\n        \"subscriptionType\": \"cloudkit:subscription_type\",\n        \"filterBy\": \"\
  cloudkit:filter_by\",\n        \"fireOnce\": \"cloudkit:fire_once\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"cloudkit:User\",\n      \"@context\": {\n        \"userRecordName\": \"cloudkit:user_record_name\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"emailAddress\": \"schema:email\"\n      }\n    },\n\n    \"Query\": {\n      \"@id\": \"cloudkit:Query\",\n      \"@context\": {\n        \"recordType\": \"schema:additionalType\",\n        \"filterBy\": \"cloudkit:filter_by\",\n        \"sortBy\": \"cloudkit:sort_by\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloudkit/refs/heads/main/json-ld/cloudkit-context.jsonld
tags:
- Apple
- Cloud Storage
- CloudKit
- Database
- iCloud
- Mobile
- Sync
- Web Services
- JSON-LD
- Linked Data
- Semantic Web
---
