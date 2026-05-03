---
api_specs:
- filename: rubygems-gems-api-openapi.yml
  format: yaml
  label: RubyGems Gems API
  slug: gems-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-gems-api-openapi.yml
- filename: rubygems-api-v2-openapi.yml
  format: yaml
  label: RubyGems API V2
  slug: api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-api-v2-openapi.yml
- filename: rubygems-downloads-api-openapi.yml
  format: yaml
  label: RubyGems Downloads API
  slug: downloads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-downloads-api-openapi.yml
- filename: rubygems-search-api-openapi.yml
  format: yaml
  label: RubyGems Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-search-api-openapi.yml
- filename: rubygems-activity-api-openapi.yml
  format: yaml
  label: RubyGems Activity API
  slug: activity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-activity-api-openapi.yml
- filename: rubygems-webhooks-api-openapi.yml
  format: yaml
  label: RubyGems Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/openapi/rubygems-webhooks-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/rubygems-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/json-ld/rubygems-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rubygems from RubyGems.
layout: jsonld
name: Rubygems Context
namespaces:
- prefix: rubygems
  uri: https://rubygems.org/ns/
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
  name: Gem
  type: ''
- container: ''
  name: GemVersion
  type: ''
- container: ''
  name: Dependency
  type: ''
- container: ''
  name: Owner
  type: ''
- container: ''
  name: Webhook
  type: ''
property_count: 5
provider_name: RubyGems
provider_slug: rubygems
slug: rubygems-context
source_filename: rubygems-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rubygems\": \"https://rubygems.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"spdx\": \"http://spdx.org/licenses/\",\n\n    \"Gem\": {\n      \"@id\": \"rubygems:Gem\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"version\": \"schema:softwareVersion\",\n        \"authors\": \"schema:author\",\n        \"info\": \"schema:description\",\n        \"platform\": \"schema:operatingSystem\",\n        \"downloads\": {\n          \"@id\": \"rubygems:downloadCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"version_downloads\": {\n          \"@id\": \"rubygems:versionDownloadCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"version_created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"licenses\": {\n          \"@id\": \"schema:license\",\n          \"@container\": \"@set\"\n        },\n        \"homepage_uri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"project_uri\": {\n          \"@id\": \"rubygems:projectUrl\",\n          \"@type\": \"@id\"\n        },\n        \"gem_uri\": {\n          \"@id\": \"schema:downloadUrl\",\n          \"@type\": \"@id\"\n        },\n        \"documentation_uri\": {\n          \"@id\": \"rubygems:documentationUrl\",\n          \"@type\": \"@id\"\n        },\n        \"source_code_uri\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"bug_tracker_uri\": {\n          \"@id\": \"rubygems:bugTrackerUrl\",\n          \"@type\": \"@id\"\n        },\n        \"changelog_uri\": {\n          \"@id\": \"rubygems:changelogUrl\",\n          \"@type\": \"@id\"\n        },\n        \"wiki_uri\": {\n        \
  \  \"@id\": \"rubygems:wikiUrl\",\n          \"@type\": \"@id\"\n        },\n        \"mailing_list_uri\": {\n          \"@id\": \"rubygems:mailingListUrl\",\n          \"@type\": \"@id\"\n        },\n        \"funding_uri\": {\n          \"@id\": \"schema:funding\",\n          \"@type\": \"@id\"\n        },\n        \"sha\": \"rubygems:sha256\",\n        \"yanked\": {\n          \"@id\": \"rubygems:yanked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dependencies\": \"rubygems:dependencies\"\n      }\n    },\n\n    \"GemVersion\": {\n      \"@id\": \"rubygems:GemVersion\",\n      \"@context\": {\n        \"number\": \"schema:softwareVersion\",\n        \"summary\": \"schema:abstract\",\n        \"description\": \"schema:description\",\n        \"authors\": \"schema:author\",\n        \"platform\": \"schema:operatingSystem\",\n        \"built_at\": {\n          \"@id\": \"rubygems:builtAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created_at\": {\n\
  \          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"downloads_count\": {\n          \"@id\": \"rubygems:downloadCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"prerelease\": {\n          \"@id\": \"rubygems:prerelease\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ruby_version\": {\n          \"@id\": \"rubygems:rubyVersionRequirement\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rubygems_version\": {\n          \"@id\": \"rubygems:rubygemsVersionRequirement\",\n          \"@type\": \"xsd:string\"\n        },\n        \"licenses\": {\n          \"@id\": \"schema:license\",\n          \"@container\": \"@set\"\n        },\n        \"sha\": \"rubygems:sha256\"\n      }\n    },\n\n    \"Dependency\": {\n      \"@id\": \"rubygems:Dependency\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"requirements\": \"rubygems:versionRequirement\"\n      }\n    },\n\n    \"\
  Owner\": {\n      \"@id\": \"rubygems:Owner\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"handle\": \"schema:alternateName\",\n        \"email\": \"schema:email\"\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"rubygems:Webhook\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"failure_count\": {\n          \"@id\": \"rubygems:failureCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rubygems/refs/heads/main/json-ld/rubygems-context.jsonld
tags:
- Ruby
- Package Manager
- Open Source
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
