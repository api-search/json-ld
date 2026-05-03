---
api_specs:
- filename: zesty-auth-api-openapi.yml
  format: yaml
  label: Zesty Auth API
  slug: auth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-auth-api-openapi.yml
- filename: zesty-accounts-api-openapi.yml
  format: yaml
  label: Zesty Accounts API
  slug: accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-accounts-api-openapi.yml
- filename: zesty-instances-api-openapi.yml
  format: yaml
  label: Zesty Instances API
  slug: instances-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-instances-api-openapi.yml
- filename: zesty-media-api-openapi.yml
  format: yaml
  label: Zesty Media API
  slug: media-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-media-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/zesty-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/json-ld/zesty-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zesty from Zesty.
layout: jsonld
name: Zesty Context
namespaces:
- prefix: zesty
  uri: https://docs.zesty.io/docs/
properties:
- container: ''
  name: Instance
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: ContentModel
  type: ''
- container: ''
  name: ContentItem
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: MediaBin
  type: ''
- container: ''
  name: MediaGroup
  type: ''
- container: ''
  name: MediaFile
  type: ''
property_count: 11
provider_name: Zesty
provider_slug: zesty
slug: zesty-context
source_filename: zesty-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"zesty\": \"https://docs.zesty.io/docs/\",\n    \"Instance\": {\n      \"@id\": \"zesty:instances-api\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"ecoZUID\": {\n          \"@id\": \"zesty:accounts\",\n          \"@type\": \"@id\"\n        },\n        \"domain\": \"https://schema.org/url\",\n        \"blueprint\": \"https://schema.org/additionalType\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"zesty:accounts\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"firstName\": \"https://schema.org/givenName\",\n        \"lastName\": \"https://schema.org/familyName\",\n        \"email\": \"https://schema.org/email\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\
  ,\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Role\": {\n      \"@id\": \"zesty:accounts\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"instanceZUID\": {\n          \"@id\": \"zesty:instances-api\",\n          \"@type\": \"@id\"\n        },\n        \"systemRole\": \"https://schema.org/additionalType\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Team\": {\n      \"@id\": \"zesty:accounts\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"Token\": {\n      \"@id\": \"zesty:accounts\"\
  ,\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"roleZUID\": {\n          \"@id\": \"zesty:accounts\",\n          \"@type\": \"@id\"\n        },\n        \"token\": \"https://schema.org/accessCode\",\n        \"createdAt\": \"https://schema.org/dateCreated\"\n      }\n    },\n    \"ContentModel\": {\n      \"@id\": \"zesty:instances-api\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"label\": \"https://schema.org/alternateName\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"description\": \"https://schema.org/description\",\n        \"parentZUID\": {\n          \"@id\": \"zesty:instances-api\",\n          \"@type\": \"@id\"\n        },\n        \"listed\": \"https://schema.org/position\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\
  \n      }\n    },\n    \"ContentItem\": {\n      \"@id\": \"zesty:instances-api\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"modelZUID\": {\n          \"@id\": \"zesty:instances-api\",\n          \"@type\": \"@id\"\n        },\n        \"data\": \"https://schema.org/mainEntity\",\n        \"web\": \"https://schema.org/WebPage\",\n        \"meta\": \"https://schema.org/additionalProperty\",\n        \"publishing\": \"https://schema.org/publishingPrinciples\"\n      }\n    },\n    \"Field\": {\n      \"@id\": \"zesty:instances-api\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"contentModelZUID\": {\n          \"@id\": \"zesty:instances-api\",\n          \"@type\": \"@id\"\n        },\n        \"name\": \"https://schema.org/name\",\n        \"label\": \"https://schema.org/alternateName\",\n        \"description\": \"https://schema.org/description\",\n        \"datatype\": \"https://schema.org/additionalType\"\
  ,\n        \"required\": \"https://schema.org/valueRequired\",\n        \"sort\": \"https://schema.org/position\",\n        \"settings\": \"https://schema.org/additionalProperty\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"MediaBin\": {\n      \"@id\": \"zesty:media\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"MediaGroup\": {\n      \"@id\": \"zesty:media\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"binZUID\": {\n          \"@id\": \"zesty:media\",\n          \"@type\": \"@id\"\n        },\n        \"groupZUID\": {\n          \"@id\": \"zesty:media\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    },\n    \"MediaFile\": {\n      \"@id\": \"zesty:media\",\n      \"@context\": {\n        \"ZUID\": \"https://schema.org/identifier\",\n        \"binZUID\": {\n          \"@id\": \"zesty:media\",\n          \"@type\": \"@id\"\n        },\n        \"groupZUID\": {\n          \"@id\": \"zesty:media\",\n          \"@type\": \"@id\"\n        },\n        \"fileName\": \"https://schema.org/name\",\n        \"title\": \"https://schema.org/headline\",\n        \"url\": \"https://schema.org/contentUrl\",\n        \"type\": \"https://schema.org/encodingFormat\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"updatedAt\": \"https://schema.org/dateModified\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/json-ld/zesty-context.jsonld
tags:
- CMS
- Composable
- Content Management
- Headless CMS
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
