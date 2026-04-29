---
api_specs:
- filename: gcp-cloud-storage-json-api-openapi.yml
  format: yaml
  label: Google Cloud Storage JSON API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/gcp-cloud-storage/refs/heads/main/openapi/gcp-cloud-storage-json-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/gcp-cloud-storage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/gcp-cloud-storage/refs/heads/main/json-ld/gcp-cloud-storage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Gcp Cloud Storage from Google Cloud Storage.
layout: jsonld
name: Gcp Cloud Storage Context
namespaces:
- prefix: gcs
  uri: https://cloud.google.com/storage/docs/json_api/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties:
- container: ''
  name: Bucket
  type: reference
- container: ''
  name: Object
  type: reference
- container: ''
  name: BucketAccessControl
  type: reference
- container: ''
  name: ObjectAccessControl
  type: reference
- container: ''
  name: Notification
  type: reference
- container: ''
  name: ServiceAccount
  type: reference
property_count: 6
provider_name: Google Cloud Storage
provider_slug: gcp-cloud-storage
slug: gcp-cloud-storage-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"gcs\": \"https://cloud.google.com/storage/docs/json_api/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n\n    \"Bucket\": {\n      \"@id\": \"gcs:buckets\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"projectNumber\": {\n          \"@id\": \"gcs:buckets/projectNumber\"\n        },\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"metageneration\": {\n          \"@id\": \"gcs:buckets/metageneration\"\n        },\n        \"location\": {\n          \"@id\": \"schema:locationCreated\"\n        },\n        \"locationType\": {\n          \"@id\": \"gcs:buckets/locationType\"\n        },\n        \"storageClass\": {\n          \"@id\": \"gcs:buckets/storageClass\"\n        },\n        \"etag\": {\n          \"@id\": \"gcs:buckets/etag\"\n        },\n        \"defaultEventBasedHold\": {\n          \"@id\": \"gcs:buckets/defaultEventBasedHold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"rpo\": {\n          \"@id\": \"gcs:buckets/rpo\"\n        },\n        \"acl\": {\n          \"@id\": \"gcs:buckets/acl\",\n          \"@container\": \"@set\"\n        },\n        \"defaultObjectAcl\": {\n          \"@id\": \"gcs:buckets/defaultObjectAcl\",\n          \"@container\": \"@set\"\n        },\n        \"iamConfiguration\": {\n          \"@id\": \"gcs:buckets/iamConfiguration\"\n    \
  \    },\n        \"encryption\": {\n          \"@id\": \"gcs:buckets/encryption\"\n        },\n        \"lifecycle\": {\n          \"@id\": \"gcs:buckets/lifecycle\"\n        },\n        \"logging\": {\n          \"@id\": \"gcs:buckets/logging\"\n        },\n        \"versioning\": {\n          \"@id\": \"gcs:buckets/versioning\"\n        },\n        \"website\": {\n          \"@id\": \"gcs:buckets/website\"\n        },\n        \"cors\": {\n          \"@id\": \"gcs:buckets/cors\",\n          \"@container\": \"@set\"\n        },\n        \"retentionPolicy\": {\n          \"@id\": \"gcs:buckets/retentionPolicy\"\n        },\n        \"softDeletePolicy\": {\n          \"@id\": \"gcs:buckets/softDeletePolicy\"\n        },\n        \"autoclass\": {\n          \"@id\": \"gcs:buckets/autoclass\"\n        },\n        \"hierarchicalNamespace\": {\n          \"@id\": \"gcs:buckets/hierarchicalNamespace\"\n        },\n        \"labels\": {\n          \"@id\": \"schema:keywords\"\n        },\n  \
  \      \"customPlacementConfig\": {\n          \"@id\": \"gcs:buckets/customPlacementConfig\"\n        },\n        \"satisfiesPZS\": {\n          \"@id\": \"gcs:buckets/satisfiesPZS\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Object\": {\n      \"@id\": \"gcs:objects\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"mediaLink\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"bucket\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n        \"generation\": {\n          \"@id\": \"schema:version\"\n        },\n        \"metageneration\": {\n          \"@id\": \"gcs:objects/metageneration\"\n        },\n        \"contentType\": {\n          \"\
  @id\": \"schema:encodingFormat\"\n        },\n        \"timeCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"timeDeleted\": {\n          \"@id\": \"gcs:objects/timeDeleted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"temporaryHold\": {\n          \"@id\": \"gcs:objects/temporaryHold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"eventBasedHold\": {\n          \"@id\": \"gcs:objects/eventBasedHold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"retentionExpirationTime\": {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"storageClass\": {\n          \"@id\": \"gcs:objects/storageClass\"\n        },\n        \"timeStorageClassUpdated\": {\n          \"@id\": \"gcs:objects/timeStorageClassUpdated\",\n  \
  \        \"@type\": \"xsd:dateTime\"\n        },\n        \"size\": {\n          \"@id\": \"schema:contentSize\"\n        },\n        \"md5Hash\": {\n          \"@id\": \"gcs:objects/md5Hash\"\n        },\n        \"crc32c\": {\n          \"@id\": \"gcs:objects/crc32c\"\n        },\n        \"etag\": {\n          \"@id\": \"gcs:objects/etag\"\n        },\n        \"componentCount\": {\n          \"@id\": \"gcs:objects/componentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"contentEncoding\": {\n          \"@id\": \"gcs:objects/contentEncoding\"\n        },\n        \"contentDisposition\": {\n          \"@id\": \"gcs:objects/contentDisposition\"\n        },\n        \"contentLanguage\": {\n          \"@id\": \"schema:inLanguage\"\n        },\n        \"cacheControl\": {\n          \"@id\": \"gcs:objects/cacheControl\"\n        },\n        \"metadata\": {\n          \"@id\": \"gcs:objects/metadata\"\n        },\n        \"acl\": {\n          \"@id\": \"gcs:objects/acl\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\"\n        },\n        \"customerEncryption\": {\n          \"@id\": \"gcs:objects/customerEncryption\"\n        },\n        \"kmsKeyName\": {\n          \"@id\": \"gcs:objects/kmsKeyName\"\n        },\n        \"customTime\": {\n          \"@id\": \"gcs:objects/customTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"softDeleteTime\": {\n          \"@id\": \"gcs:objects/softDeleteTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hardDeleteTime\": {\n          \"@id\": \"gcs:objects/hardDeleteTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BucketAccessControl\": {\n      \"@id\": \"gcs:bucketAccessControls\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"bucket\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n\
  \        \"entity\": {\n          \"@id\": \"gcs:bucketAccessControls/entity\"\n        },\n        \"role\": {\n          \"@id\": \"schema:roleName\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"domain\": {\n          \"@id\": \"gcs:bucketAccessControls/domain\"\n        },\n        \"entityId\": {\n          \"@id\": \"gcs:bucketAccessControls/entityId\"\n        },\n        \"projectTeam\": {\n          \"@id\": \"gcs:bucketAccessControls/projectTeam\"\n        }\n      }\n    },\n\n    \"ObjectAccessControl\": {\n      \"@id\": \"gcs:objectAccessControls\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"bucket\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n        \"object\": {\n          \"@id\": \"gcs:objectAccessControls/object\"\n        },\n        \"entity\": {\n          \"@id\": \"gcs:objectAccessControls/entity\"\n        },\n\
  \        \"role\": {\n          \"@id\": \"schema:roleName\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\"\n        },\n        \"domain\": {\n          \"@id\": \"gcs:objectAccessControls/domain\"\n        },\n        \"entityId\": {\n          \"@id\": \"gcs:objectAccessControls/entityId\"\n        },\n        \"projectTeam\": {\n          \"@id\": \"gcs:objectAccessControls/projectTeam\"\n        }\n      }\n    },\n\n    \"Notification\": {\n      \"@id\": \"gcs:notifications\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"topic\": {\n          \"@id\": \"gcs:notifications/topic\"\n        },\n        \"event_types\": {\n          \"@id\": \"gcs:notifications/event_types\",\n          \"@container\": \"@set\"\n        },\n        \"object_name_prefix\": {\n          \"@id\": \"gcs:notifications/object_name_prefix\"\n        },\n        \"payload_format\": {\n          \"\
  @id\": \"gcs:notifications/payload_format\"\n        },\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ServiceAccount\": {\n      \"@id\": \"gcs:serviceAccount\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"email_address\": {\n          \"@id\": \"schema:email\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/gcp-cloud-storage/refs/heads/main/json-ld/gcp-cloud-storage-context.jsonld
tags:
- Archival
- Backup
- Blob Storage
- Cloud Storage
- Data
- File Storage
- Google Cloud
- Object Storage
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
