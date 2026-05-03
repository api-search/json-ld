---
class_count: 34
classes:
- APIDocumentationPlatform
- APIRegistry
- APIClient
- SDKGenerator
- OpenAPIDocument
- SpectralRuleset
- APICollection
- MockServer
- name
- description
- url
- documentation
- version
- license
- provider
- dateCreated
- dateModified
- SoftwareApplication
- SoftwareSourceCode
- WebAPI
- baseUrl
- apiType
- tags
- openAPIVersion
- supportedLanguages
- frameworkIntegrations
- themeSupport
- gitSyncEnabled
- offlineFirst
- registryNamespace
- sdkLanguage
- mockServerPort
- spectralRuleCount
- customDomainEnabled
context_file: json-ld/scalar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scalar/refs/heads/main/json-ld/scalar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scalar from Scalar.
layout: jsonld
name: Scalar Context
namespaces:
- prefix: api
  uri: https://api-evangelist.com/vocabulary/
- prefix: scalar
  uri: https://api-evangelist.com/vocabulary/scalar/
properties:
- container: ''
  name: Organization
  type: reference
property_count: 1
provider_name: Scalar
provider_slug: scalar
slug: scalar-context
source_filename: scalar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"api\": \"https://api-evangelist.com/vocabulary/\",\n    \"scalar\": \"https://api-evangelist.com/vocabulary/scalar/\",\n\n    \"APIDocumentationPlatform\": \"scalar:APIDocumentationPlatform\",\n    \"APIRegistry\": \"scalar:APIRegistry\",\n    \"APIClient\": \"scalar:APIClient\",\n    \"SDKGenerator\": \"scalar:SDKGenerator\",\n    \"OpenAPIDocument\": \"scalar:OpenAPIDocument\",\n    \"SpectralRuleset\": \"scalar:SpectralRuleset\",\n    \"APICollection\": \"scalar:APICollection\",\n    \"MockServer\": \"scalar:MockServer\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"documentation\": \"schema:documentation\",\n    \"version\": \"schema:version\",\n    \"license\": \"schema:license\",\n    \"provider\": \"schema:provider\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\"\
  ,\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"WebAPI\": \"schema:WebAPI\",\n\n    \"baseUrl\": \"api:baseUrl\",\n    \"apiType\": \"api:apiType\",\n    \"tags\": \"api:tags\",\n\n    \"openAPIVersion\": \"scalar:openAPIVersion\",\n    \"supportedLanguages\": \"scalar:supportedLanguages\",\n    \"frameworkIntegrations\": \"scalar:frameworkIntegrations\",\n    \"themeSupport\": \"scalar:themeSupport\",\n    \"gitSyncEnabled\": \"scalar:gitSyncEnabled\",\n    \"offlineFirst\": \"scalar:offlineFirst\",\n    \"registryNamespace\": \"scalar:registryNamespace\",\n    \"sdkLanguage\": \"scalar:sdkLanguage\",\n    \"mockServerPort\": \"scalar:mockServerPort\",\n    \"spectralRuleCount\": \"scalar:spectralRuleCount\",\n    \"customDomainEnabled\": \"scalar:customDomainEnabled\",\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scalar/refs/heads/main/json-ld/scalar-context.jsonld
tags:
- API Client
- API Documentation
- API References
- Code Generation
- Developer Tools
- OpenAPI
- Registry
- SDKs
- Swagger
- JSON-LD
- Linked Data
- Semantic Web
---
