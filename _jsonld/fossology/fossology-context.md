---
class_count: 11
classes:
- Upload
- License
- Job
- shortName
- fullName
- text
- url
- uploaddate
- uploadname
- filesize
- hash
context_file: json-ld/fossology-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fossology/refs/heads/main/json-ld/fossology-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fossology from FOSSology.
layout: jsonld
name: Fossology Context
namespaces:
- prefix: spdx
  uri: http://spdx.org/rdf/terms#
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: FOSSology
provider_slug: fossology
slug: fossology-context
source_filename: fossology-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://raw.githubusercontent.com/api-evangelist/fossology/refs/heads/main/vocabulary/fossology-vocabulary.yml#\",\n    \"spdx\": \"http://spdx.org/rdf/terms#\",\n    \"schema\": \"https://schema.org/\",\n    \"Upload\": \"FOSSologyUpload\",\n    \"License\": \"spdx:License\",\n    \"Job\": \"FOSSologyJob\",\n    \"shortName\": \"spdx:licenseId\",\n    \"fullName\": \"spdx:name\",\n    \"text\": \"spdx:licenseText\",\n    \"url\": \"schema:url\",\n    \"uploaddate\": \"schema:dateCreated\",\n    \"uploadname\": \"schema:name\",\n    \"filesize\": \"schema:contentSize\",\n    \"hash\": \"spdx:checksum\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fossology/refs/heads/main/json-ld/fossology-context.jsonld
tags:
- Compliance
- Licensing
- Linux Foundation
- Scanning
- SPDX
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
