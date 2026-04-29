---
class_count: 18
classes:
- Adobe CEP Extension Manifest
- Element
- ElementCreation
- ErrorResponse
- ExpandImageRequest
- FillImageRequest
- GenerateImagesRequest
- GenerateImagesResponse
- GenerateSimilarRequest
- ImageReference
- Library
- LicenseHistoryResponse
- LicenseInfoResponse
- LicenseResponse
- MemberProfile
- ObjectCompositeRequest
- SearchResponse
- StockAsset
context_file: json-ld/adobe-creative-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/json-ld/adobe-creative-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Creative Cloud from Adobe Creative Cloud.
layout: jsonld
name: Adobe Creative Cloud Context
namespaces:
- prefix: adobe
  uri: https://developer.adobe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ExtensionManifest
  type: reference
- container: ''
  name: available_entitlement
  type: reference
- container: ''
  name: category
  type: reference
- container: ''
  name: client_data
  type: reference
- container: ''
  name: comp_url
  type: reference
- container: ''
  name: contentClass
  type: string
- container: ''
  name: content_type
  type: string
- container: ''
  name: contents
  type: reference
- container: ''
  name: created_date
  type: dateTime
- container: ''
  name: creator_id
  type: integer
- container: ''
  name: creator_name
  type: string
- container: ''
  name: element_count
  type: integer
- container: ''
  name: error_code
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: height
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: is_licensed
  type: string
- container: set
  name: keywords
  type: string
- container: ''
  name: mask
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: modified_date
  type: dateTime
- container: ''
  name: name
  type: string
- container: ''
  name: nb_results
  type: integer
- container: ''
  name: negativePrompt
  type: string
- container: ''
  name: numVariations
  type: integer
- container: set
  name: outputs
  type: string
- container: ''
  name: owner
  type: reference
- container: ''
  name: placement
  type: reference
- container: ''
  name: premium_level_id
  type: integer
- container: ''
  name: prompt
  type: string
- container: set
  name: representations
  type: string
- container: set
  name: seeds
  type: string
- container: ''
  name: size
  type: reference
- container: ''
  name: source
  type: reference
- container: ''
  name: style
  type: reference
- container: ''
  name: thumbnail
  type: reference
- container: ''
  name: thumbnail_height
  type: integer
- container: ''
  name: thumbnail_url
  type: reference
- container: ''
  name: thumbnail_width
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: width
  type: integer
property_count: 43
provider_name: Adobe Creative Cloud
provider_slug: adobe-creative-cloud
slug: adobe-creative-cloud-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adobe\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Adobe CEP Extension Manifest\": \"adobe:Adobe CEP Extension Manifest\",\n    \"Element\": \"adobe:Element\",\n    \"ElementCreation\": \"adobe:ElementCreation\",\n    \"ErrorResponse\": \"adobe:ErrorResponse\",\n    \"ExpandImageRequest\": \"adobe:ExpandImageRequest\",\n    \"FillImageRequest\": \"adobe:FillImageRequest\",\n    \"GenerateImagesRequest\": \"adobe:GenerateImagesRequest\",\n    \"GenerateImagesResponse\": \"adobe:GenerateImagesResponse\",\n    \"GenerateSimilarRequest\": \"adobe:GenerateSimilarRequest\",\n    \"ImageReference\": \"adobe:ImageReference\",\n    \"Library\": \"adobe:Library\",\n    \"LicenseHistoryResponse\": \"adobe:LicenseHistoryResponse\",\n    \"LicenseInfoResponse\": \"adobe:LicenseInfoResponse\",\n    \"LicenseResponse\": \"adobe:LicenseResponse\"\
  ,\n    \"MemberProfile\": \"adobe:MemberProfile\",\n    \"ObjectCompositeRequest\": \"adobe:ObjectCompositeRequest\",\n    \"SearchResponse\": \"adobe:SearchResponse\",\n    \"StockAsset\": \"adobe:StockAsset\",\n    \"ExtensionManifest\": {\n      \"@id\": \"adobe:ExtensionManifest\",\n      \"@type\": \"@id\"\n    },\n    \"available_entitlement\": {\n      \"@id\": \"adobe:available_entitlement\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"adobe:category\",\n      \"@type\": \"@id\"\n    },\n    \"client_data\": {\n      \"@id\": \"adobe:client_data\",\n      \"@type\": \"@id\"\n    },\n    \"comp_url\": {\n      \"@id\": \"adobe:comp_url\",\n      \"@type\": \"@id\"\n    },\n    \"contentClass\": {\n      \"@id\": \"adobe:contentClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content_type\": {\n      \"@id\": \"adobe:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contents\": {\n      \"@id\": \"adobe:contents\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"created_date\": {\n      \"@id\": \"adobe:created_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator_id\": {\n      \"@id\": \"adobe:creator_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"creator_name\": {\n      \"@id\": \"adobe:creator_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"element_count\": {\n      \"@id\": \"adobe:element_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"error_code\": {\n      \"@id\": \"adobe:error_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"adobe:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"adobe:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"adobe:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"adobe:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_licensed\": {\n      \"@id\": \"adobe:is_licensed\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"adobe:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mask\": {\n      \"@id\": \"adobe:mask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"adobe:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified_date\": {\n      \"@id\": \"adobe:modified_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nb_results\": {\n      \"@id\": \"adobe:nb_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"negativePrompt\": {\n      \"@id\": \"adobe:negativePrompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numVariations\": {\n      \"@id\": \"adobe:numVariations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"outputs\": {\n      \"@id\": \"adobe:outputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"owner\": {\n      \"@id\": \"adobe:owner\",\n      \"@type\": \"@id\"\n    },\n    \"placement\": {\n      \"@id\": \"adobe:placement\",\n      \"@type\": \"@id\"\n    },\n    \"premium_level_id\": {\n      \"@id\": \"adobe:premium_level_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"prompt\": {\n      \"@id\": \"adobe:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"representations\": {\n      \"@id\": \"adobe:representations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seeds\": {\n      \"@id\": \"adobe:seeds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"adobe:size\",\n      \"@type\": \"@id\"\n    },\n    \"source\": {\n      \"@id\": \"adobe:source\",\n      \"@type\": \"@id\"\n    },\n    \"style\": {\n      \"@id\": \"adobe:style\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnail\": {\n      \"@id\": \"adobe:thumbnail\",\n      \"@type\": \"\
  @id\"\n    },\n    \"thumbnail_height\": {\n      \"@id\": \"adobe:thumbnail_height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"thumbnail_url\": {\n      \"@id\": \"adobe:thumbnail_url\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnail_width\": {\n      \"@id\": \"adobe:thumbnail_width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"adobe:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adobe:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"adobe:width\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-cloud/refs/heads/main/json-ld/adobe-creative-cloud-context.jsonld
tags:
- AI/ML
- Cloud
- Creative
- Design
- Documents
- Photography
- SaaS
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
