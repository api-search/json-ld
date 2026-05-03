---
api_specs:
- filename: vs-code-marketplace-gallery-api-openapi.yml
  format: yaml
  label: VS Code Marketplace Gallery API
  slug: vs-code-marketplace-gallery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/openapi/vs-code-marketplace-gallery-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/vs-code-marketplace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/json-ld/vs-code-marketplace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vs Code Marketplace from VS Code Marketplace.
layout: jsonld
name: Vs Code Marketplace Context
namespaces:
- prefix: vscode
  uri: https://marketplace.visualstudio.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: SoftwareApplication
  uri: https://schema.org/SoftwareApplication
- prefix: SoftwareSourceCode
  uri: https://schema.org/SoftwareSourceCode
- prefix: Person
  uri: https://schema.org/Person
- prefix: Organization
  uri: https://schema.org/Organization
- prefix: AggregateRating
  uri: https://schema.org/AggregateRating
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: datePublished
  uri: https://schema.org/datePublished
- prefix: dateModified
  uri: https://schema.org/dateModified
- prefix: keywords
  uri: https://schema.org/keywords
- prefix: applicationCategory
  uri: https://schema.org/applicationCategory
- prefix: aggregateRating
  uri: https://schema.org/aggregateRating
- prefix: ratingValue
  uri: https://schema.org/ratingValue
- prefix: ratingCount
  uri: https://schema.org/ratingCount
- prefix: author
  uri: https://schema.org/author
- prefix: downloadUrl
  uri: https://schema.org/downloadUrl
- prefix: softwareVersion
  uri: https://schema.org/softwareVersion
- prefix: operatingSystem
  uri: https://schema.org/operatingSystem
properties:
- container: ''
  name: vscode:extensionId
  type: string
- container: ''
  name: vscode:extensionName
  type: string
- container: ''
  name: vscode:publisherName
  type: string
- container: ''
  name: vscode:installCount
  type: integer
- container: ''
  name: vscode:version
  type: string
- container: ''
  name: vscode:vsixDownloadUrl
  type: reference
- container: ''
  name: vscode:filterType
  type: integer
- container: ''
  name: vscode:queryFlags
  type: integer
property_count: 8
provider_name: VS Code Marketplace
provider_slug: vs-code-marketplace
slug: vs-code-marketplace-context
source_filename: vs-code-marketplace-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vscode\": \"https://marketplace.visualstudio.com/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SoftwareApplication\": \"https://schema.org/SoftwareApplication\",\n    \"SoftwareSourceCode\": \"https://schema.org/SoftwareSourceCode\",\n    \"Person\": \"https://schema.org/Person\",\n    \"Organization\": \"https://schema.org/Organization\",\n    \"AggregateRating\": \"https://schema.org/AggregateRating\",\n\n    \"vscode:extensionId\": {\"@type\": \"xsd:string\"},\n    \"vscode:extensionName\": {\"@type\": \"xsd:string\"},\n    \"vscode:publisherName\": {\"@type\": \"xsd:string\"},\n    \"vscode:installCount\": {\"@type\": \"xsd:integer\"},\n    \"vscode:version\": {\"@type\": \"xsd:string\"},\n    \"vscode:vsixDownloadUrl\": {\"@type\": \"@id\"},\n    \"vscode:filterType\": {\"@type\": \"xsd:integer\"},\n    \"vscode:queryFlags\": {\"@type\": \"xsd:integer\"},\n\n    \"name\": \"https://schema.org/name\"\
  ,\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\",\n    \"datePublished\": \"https://schema.org/datePublished\",\n    \"dateModified\": \"https://schema.org/dateModified\",\n    \"keywords\": \"https://schema.org/keywords\",\n    \"applicationCategory\": \"https://schema.org/applicationCategory\",\n    \"aggregateRating\": \"https://schema.org/aggregateRating\",\n    \"ratingValue\": \"https://schema.org/ratingValue\",\n    \"ratingCount\": \"https://schema.org/ratingCount\",\n    \"author\": \"https://schema.org/author\",\n    \"downloadUrl\": \"https://schema.org/downloadUrl\",\n    \"softwareVersion\": \"https://schema.org/softwareVersion\",\n    \"operatingSystem\": \"https://schema.org/operatingSystem\"\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://marketplace.visualstudio.com/\",\n      \"@type\": \"Organization\",\n      \"name\": \"VS Code Marketplace\",\n      \"description\": \"Microsoft's official extension marketplace\
  \ for Visual Studio Code.\",\n      \"url\": \"https://marketplace.visualstudio.com/\",\n      \"parentOrganization\": {\n        \"@id\": \"https://www.microsoft.com/\",\n        \"name\": \"Microsoft\"\n      }\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vs-code-marketplace/refs/heads/main/json-ld/vs-code-marketplace-context.jsonld
tags:
- Developer Tools
- Extensions
- IDE
- Microsoft
- JSON-LD
- Linked Data
- Semantic Web
---
