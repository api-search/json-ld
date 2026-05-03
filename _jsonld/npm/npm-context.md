---
api_specs:
- filename: npm-registry-api-openapi.yml
  format: yaml
  label: npm Registry API
  slug: registry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-registry-api-openapi.yml
- filename: npm-public-api-openapi.yml
  format: yaml
  label: npm Public API
  slug: public
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-public-api-openapi.yml
- filename: npm-hooks-api-openapi.yml
  format: yaml
  label: npm Hooks API
  slug: hooks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/openapi/npm-hooks-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/npm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/json-ld/npm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Npm from npm.
layout: jsonld
name: Npm Context
namespaces:
- prefix: npm
  uri: https://registry.npmjs.org/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: spdx
  uri: http://spdx.org/licenses/
properties:
- container: ''
  name: Package
  type: ''
- container: ''
  name: PackageVersion
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Distribution
  type: ''
- container: ''
  name: HookSubscription
  type: ''
- container: ''
  name: AccessToken
  type: ''
- container: ''
  name: TrustedPublisher
  type: ''
property_count: 8
provider_name: npm
provider_slug: npm
slug: npm-context
source_filename: npm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"npm\": \"https://registry.npmjs.org/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"spdx\": \"http://spdx.org/licenses/\",\n\n    \"Package\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:version\",\n        \"keywords\": \"schema:keywords\",\n        \"homepage\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"author\": \"schema:author\",\n        \"maintainers\": {\n          \"@id\": \"schema:maintainer\",\n          \"@container\": \"@set\"\n        },\n        \"repository\": {\n          \"@id\": \"schema:codeRepository\",\n\
  \          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dependencies\": {\n          \"@id\": \"schema:softwareRequirements\",\n          \"@container\": \"@set\"\n        },\n        \"devDependencies\": {\n          \"@id\": \"npm:devDependencies\",\n          \"@container\": \"@set\"\n        },\n        \"peerDependencies\": {\n          \"@id\": \"npm:peerDependencies\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PackageVersion\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"description\": \"schema:description\",\n        \"main\": \"npm:main\",\n        \"tarball\": {\n          \"@id\": \"schema:downloadUrl\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"shasum\": \"npm:shasum\",\n        \"integrity\": \"npm:integrity\",\n        \"fileCount\": \"npm:fileCount\",\n        \"unpackedSize\": {\n          \"@id\": \"schema:fileSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"deprecated\": \"npm:deprecated\",\n        \"publishedAt\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"scope\": \"npm:scope\",\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\
  \n        }\n      }\n    },\n\n    \"Distribution\": {\n      \"@id\": \"schema:DataDownload\",\n      \"@context\": {\n        \"tarball\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"shasum\": \"npm:shasum\",\n        \"integrity\": \"npm:integrity\",\n        \"fileCount\": \"npm:fileCount\",\n        \"unpackedSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"HookSubscription\": {\n      \"@id\": \"npm:HookSubscription\",\n      \"@context\": {\n        \"type\": \"npm:hookType\",\n        \"name\": \"npm:watchedEntity\",\n        \"endpoint\": {\n          \"@id\": \"npm:endpoint\",\n          \"@type\": \"@id\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n      \
  \  }\n      }\n    },\n\n    \"AccessToken\": {\n      \"@id\": \"npm:AccessToken\",\n      \"@context\": {\n        \"key\": \"npm:tokenKey\",\n        \"readonly\": \"npm:readonly\",\n        \"automation\": \"npm:automation\",\n        \"cidr_whitelist\": {\n          \"@id\": \"npm:cidrWhitelist\",\n          \"@container\": \"@set\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TrustedPublisher\": {\n      \"@id\": \"npm:TrustedPublisher\",\n      \"@context\": {\n        \"provider\": \"npm:ciProvider\",\n        \"repository_owner\": \"npm:repositoryOwner\",\n        \"repository\": \"npm:repository\",\n        \"workflow_filename\": \"npm:workflowFilename\",\n        \"environment\": \"npm:deploymentEnvironment\",\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/npm/refs/heads/main/json-ld/npm-context.jsonld
tags:
- Packages
- JavaScript
- Node.js
- Package Management
- Registry
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
