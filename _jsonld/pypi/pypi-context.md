---
api_specs:
- filename: pypi-json-api-openapi.yml
  format: yaml
  label: PyPI JSON API
  slug: json
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-json-api-openapi.yml
- filename: pypi-index-api-openapi.yml
  format: yaml
  label: PyPI Index API
  slug: index
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-index-api-openapi.yml
- filename: pypi-integrity-api-openapi.yml
  format: yaml
  label: PyPI Integrity API
  slug: integrity
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-integrity-api-openapi.yml
- filename: pypi-upload-api-openapi.yml
  format: yaml
  label: PyPI Upload API
  slug: upload
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-upload-api-openapi.yml
- filename: pypi-stats-api-openapi.yml
  format: yaml
  label: PyPI Stats API
  slug: stats
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/openapi/pypi-stats-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/pypi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/json-ld/pypi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pypi from PyPI.
layout: jsonld
name: Pypi Context
namespaces:
- prefix: pypi
  uri: https://pypi.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: DistributionFile
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: Provenance
  type: ''
property_count: 5
provider_name: PyPI
provider_slug: pypi
slug: pypi-context
source_filename: pypi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pypi\": \"https://pypi.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n\n    \"Project\": {\n      \"@id\": \"pypi:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:softwareVersion\",\n        \"summary\": \"schema:description\",\n        \"description\": \"schema:text\",\n        \"author\": \"schema:author\",\n        \"authorEmail\": \"schema:email\",\n        \"maintainer\": \"schema:maintainer\",\n        \"maintainerEmail\": \"schema:email\",\n        \"license\": \"schema:license\",\n        \"licenseExpression\": {\n          \"@id\": \"spdx:licenseId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"keywords\": \"schema:keywords\",\n        \"classifiers\": {\n          \"@id\": \"pypi:classifier\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"homePage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"projectUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"requiresPython\": {\n          \"@id\": \"pypi:requiresPython\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requiresDist\": {\n          \"@id\": \"pypi:requiresDist\",\n          \"@container\": \"@set\"\n        },\n        \"projectUrls\": {\n          \"@id\": \"pypi:projectUrls\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"pypi:Release\",\n      \"@context\": {\n        \"version\": \"schema:softwareVersion\",\n        \"uploadTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"yanked\": {\n          \"@id\": \"pypi:yanked\",\n          \"@type\": \"xsd:boolean\"\n        },\n \
  \       \"yankedReason\": {\n          \"@id\": \"pypi:yankedReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"files\": {\n          \"@id\": \"pypi:hasFile\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DistributionFile\": {\n      \"@id\": \"pypi:DistributionFile\",\n      \"@context\": {\n        \"filename\": \"schema:name\",\n        \"url\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"packageType\": \"pypi:packageType\",\n        \"pythonVersion\": \"pypi:pythonVersion\",\n        \"md5Digest\": {\n          \"@id\": \"pypi:md5Digest\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sha256Digest\": {\n          \"@id\": \"pypi:sha256Digest\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blake2b256Digest\": {\n          \"@id\": \"pypi:blake2b256Digest\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"pypi:Vulnerability\",\n      \"@context\": {\n        \"id\": \"dcterms:identifier\",\n        \"summary\": \"schema:description\",\n        \"details\": \"schema:text\",\n        \"aliases\": {\n          \"@id\": \"schema:alternateName\",\n          \"@container\": \"@set\"\n        },\n        \"fixedIn\": {\n          \"@id\": \"pypi:fixedIn\",\n          \"@container\": \"@set\"\n        },\n        \"link\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Provenance\": {\n      \"@id\": \"pypi:Provenance\",\n      \"@context\": {\n        \"version\": \"schema:version\",\n        \"attestationBundles\": {\n          \"@id\": \"pypi:attestationBundle\",\n          \"@container\": \"@set\"\n        },\n        \"publisher\": \"pypi:publisher\",\n        \"publisherKind\": \"pypi:publisherKind\",\n        \"attestationType\"\
  : {\n          \"@id\": \"pypi:attestationType\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pypi/refs/heads/main/json-ld/pypi-context.jsonld
tags:
- Developer Tools
- Open Source
- Package Management
- Packages
- Python
- JSON-LD
- Linked Data
- Semantic Web
---
