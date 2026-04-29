---
class_count: 0
classes: []
context_file: json-ld/chef-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/json-ld/chef-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Chef from Chef.
layout: jsonld
name: Chef Context
namespaces:
- prefix: chef
  uri: https://docs.chef.io/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Node
  type: ''
- container: ''
  name: Cookbook
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: ComplianceProfile
  type: ''
- container: ''
  name: ScanReport
  type: ''
- container: ''
  name: HabitatPackage
  type: ''
property_count: 7
provider_name: Chef
provider_slug: chef
slug: chef-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"chef\": \"https://docs.chef.io/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Node\": {\n      \"@id\": \"chef:Node\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"chef_environment\": \"chef:chefEnvironment\",\n        \"run_list\": \"chef:runList\",\n        \"automatic\": \"chef:automaticAttributes\",\n        \"default\": \"chef:defaultAttributes\",\n        \"override\": \"chef:overrideAttributes\"\n      }\n    },\n\n    \"Cookbook\": {\n      \"@id\": \"chef:Cookbook\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"chef:Role\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"description\": \"schema:description\",\n        \"run_list\": \"chef:runList\",\n        \"default_attributes\": \"chef:defaultAttributes\",\n        \"override_attributes\": \"chef:overrideAttributes\"\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"chef:Environment\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"cookbook_versions\": \"chef:cookbookVersions\"\n      }\n    },\n\n    \"ComplianceProfile\": {\n      \"@id\": \"chef:ComplianceProfile\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"title\": \"schema:headline\",\n        \"version\": \"schema:version\",\n        \"summary\": \"schema:description\"\n      }\n    },\n\n    \"ScanReport\": {\n      \"@id\": \"chef:ScanReport\",\n      \"@context\": {\n        \"id\": \"chef:reportId\",\n        \"nodeId\": \"chef:nodeId\",\n        \"endTime\": {\n          \"@id\": \"chef:endTime\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        },\n        \"status\": \"chef:status\"\n      }\n    },\n\n    \"HabitatPackage\": {\n      \"@id\": \"chef:HabitatPackage\",\n      \"@context\": {\n        \"origin\": \"chef:origin\",\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"release\": \"chef:release\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/json-ld/chef-context.jsonld
tags:
- Application Delivery
- Automation
- Compliance
- Configuration Management
- DevOps
- DevSecOps
- Habitat
- Infrastructure as Code
- InSpec
- JSON-LD
- Linked Data
- Semantic Web
---
