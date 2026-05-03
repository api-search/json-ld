---
api_specs:
- filename: nuget-server-api-openapi.yml
  format: yaml
  label: NuGet Server API
  slug: nuget-server-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-server-api-openapi.yml
- filename: nuget-catalog-api-openapi.yml
  format: yaml
  label: NuGet Catalog API
  slug: nuget-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-catalog-api-openapi.yml
- filename: nuget-search-api-openapi.yml
  format: yaml
  label: NuGet Search API
  slug: nuget-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-search-api-openapi.yml
- filename: nuget-package-metadata-api-openapi.yml
  format: yaml
  label: NuGet Package Metadata API
  slug: nuget-package-metadata-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-package-metadata-api-openapi.yml
- filename: nuget-package-content-api-openapi.yml
  format: yaml
  label: NuGet Package Content API
  slug: nuget-package-content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/openapi/nuget-package-content-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/nuget-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/json-ld/nuget-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nuget from NuGet.
layout: jsonld
name: Nuget Context
namespaces:
- prefix: nuget
  uri: https://schema.nuget.org/schema#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: catalog
  uri: https://schema.nuget.org/catalog#
properties:
- container: ''
  name: Package
  type: ''
- container: ''
  name: PackageVersion
  type: ''
- container: ''
  name: DependencyGroup
  type: ''
- container: ''
  name: PackageDependency
  type: ''
- container: ''
  name: PackageType
  type: ''
- container: ''
  name: Deprecation
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: CatalogEvent
  type: ''
property_count: 8
provider_name: NuGet
provider_slug: nuget
slug: nuget-context
source_filename: nuget-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nuget\": \"https://schema.nuget.org/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"catalog\": \"https://schema.nuget.org/catalog#\",\n\n    \"Package\": {\n      \"@id\": \"nuget:Package\",\n      \"@context\": {\n        \"id\": \"nuget:id\",\n        \"version\": \"nuget:version\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"summary\": \"schema:abstract\",\n        \"authors\": \"schema:author\",\n        \"owners\": \"nuget:owners\",\n        \"tags\": \"schema:keywords\",\n        \"language\": \"schema:inLanguage\",\n        \"iconUrl\": {\n          \"@id\": \"schema:thumbnailUrl\",\n          \"@type\": \"@id\"\n        },\n        \"licenseUrl\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"licenseExpression\"\
  : \"nuget:licenseExpression\",\n        \"projectUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"readmeUrl\": {\n          \"@id\": \"nuget:readmeUrl\",\n          \"@type\": \"@id\"\n        },\n        \"registration\": {\n          \"@id\": \"nuget:registration\",\n          \"@type\": \"@id\"\n        },\n        \"packageContent\": {\n          \"@id\": \"nuget:packageContent\",\n          \"@type\": \"@id\"\n        },\n        \"listed\": \"nuget:listed\",\n        \"verified\": \"nuget:verified\",\n        \"published\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"totalDownloads\": \"nuget:totalDownloads\",\n        \"requireLicenseAcceptance\": \"nuget:requireLicenseAcceptance\",\n        \"minClientVersion\": \"nuget:minClientVersion\",\n        \"\
  isPrerelease\": \"nuget:isPrerelease\",\n        \"packageHash\": \"nuget:packageHash\",\n        \"packageHashAlgorithm\": \"nuget:packageHashAlgorithm\",\n        \"packageSize\": \"nuget:packageSize\",\n        \"versions\": {\n          \"@id\": \"nuget:versions\",\n          \"@container\": \"@set\"\n        },\n        \"dependencyGroups\": {\n          \"@id\": \"nuget:dependencyGroups\",\n          \"@container\": \"@set\"\n        },\n        \"packageTypes\": {\n          \"@id\": \"nuget:packageTypes\",\n          \"@container\": \"@set\"\n        },\n        \"deprecation\": \"nuget:deprecation\",\n        \"vulnerabilities\": {\n          \"@id\": \"nuget:vulnerabilities\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PackageVersion\": {\n      \"@id\": \"nuget:PackageVersion\",\n      \"@context\": {\n        \"version\": \"nuget:version\",\n        \"downloads\": \"nuget:downloads\"\n      }\n    },\n\n    \"DependencyGroup\": {\n      \"@id\"\
  : \"nuget:DependencyGroup\",\n      \"@context\": {\n        \"targetFramework\": \"nuget:targetFramework\",\n        \"dependencies\": {\n          \"@id\": \"nuget:dependencies\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"PackageDependency\": {\n      \"@id\": \"nuget:PackageDependency\",\n      \"@context\": {\n        \"id\": \"nuget:id\",\n        \"range\": \"nuget:range\",\n        \"registration\": {\n          \"@id\": \"nuget:registration\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PackageType\": {\n      \"@id\": \"nuget:PackageType\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"nuget:version\"\n      }\n    },\n\n    \"Deprecation\": {\n      \"@id\": \"nuget:Deprecation\",\n      \"@context\": {\n        \"reasons\": \"nuget:reasons\",\n        \"message\": \"nuget:message\",\n        \"alternatePackage\": \"nuget:alternatePackage\"\n      }\n    },\n\n    \"Vulnerability\": {\n\
  \      \"@id\": \"nuget:Vulnerability\",\n      \"@context\": {\n        \"advisoryUrl\": {\n          \"@id\": \"nuget:advisoryUrl\",\n          \"@type\": \"@id\"\n        },\n        \"severity\": \"nuget:severity\"\n      }\n    },\n\n    \"CatalogEvent\": {\n      \"@id\": \"catalog:CatalogEvent\",\n      \"@context\": {\n        \"commitId\": \"catalog:commitId\",\n        \"commitTimeStamp\": {\n          \"@id\": \"catalog:commitTimeStamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"id\": \"nuget:id\",\n        \"version\": \"nuget:version\",\n        \"published\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nuget/refs/heads/main/json-ld/nuget-context.jsonld
tags:
- Package Management
- .NET
- Packages
- Dependencies
- Software Distribution
- Registry
- JSON-LD
- Linked Data
- Semantic Web
---
