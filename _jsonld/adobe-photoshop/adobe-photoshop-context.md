---
class_count: 16
classes:
- ActionJSONRequest
- Adobe Photoshop UXP Plugin Manifest
- ArtboardCreateRequest
- DepthBlurRequest
- DocumentCreateRequest
- DocumentManifestRequest
- DocumentOperationsRequest
- FillMaskedAreasRequest
- PhotoshopActionsRequest
- ProductCropRequest
- RemoveBackgroundRequest
- RenditionCreateRequest
- SmartObjectRequest
- StorageInput
- StorageOutput
- TextEditRequest
context_file: json-ld/adobe-photoshop-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-photoshop/refs/heads/main/json-ld/adobe-photoshop-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Photoshop from Adobe Photoshop.
layout: jsonld
name: Adobe Photoshop Context
namespaces:
- prefix: ps
  uri: https://developer.adobe.com/photoshop/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: addon
  type: reference
- container: ''
  name: author
  type: string
- container: ''
  name: backgroundColor
  type: reference
- container: ''
  name: colorDecontamination
  type: integer
- container: ''
  name: description
  type: string
- container: set
  name: entrypoints
  type: string
- container: ''
  name: host
  type: reference
- container: ''
  name: href
  type: string
- container: set
  name: icons
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: reference
- container: set
  name: inputs
  type: string
- container: set
  name: keywords
  type: string
- container: ''
  name: main
  type: string
- container: ''
  name: manifestVersion
  type: integer
- container: set
  name: masks
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: output
  type: reference
- container: set
  name: outputs
  type: string
- container: ''
  name: overwrite
  type: boolean
- container: ''
  name: requiredPermissions
  type: reference
- container: ''
  name: storage
  type: string
- container: ''
  name: trim
  type: boolean
- container: ''
  name: type
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: width
  type: integer
property_count: 28
provider_name: Adobe Photoshop
provider_slug: adobe-photoshop
slug: adobe-photoshop-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ps\": \"https://developer.adobe.com/photoshop/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ActionJSONRequest\": \"ps:ActionJSONRequest\",\n    \"Adobe Photoshop UXP Plugin Manifest\": \"ps:Adobe Photoshop UXP Plugin Manifest\",\n    \"ArtboardCreateRequest\": \"ps:ArtboardCreateRequest\",\n    \"DepthBlurRequest\": \"ps:DepthBlurRequest\",\n    \"DocumentCreateRequest\": \"ps:DocumentCreateRequest\",\n    \"DocumentManifestRequest\": \"ps:DocumentManifestRequest\",\n    \"DocumentOperationsRequest\": \"ps:DocumentOperationsRequest\",\n    \"FillMaskedAreasRequest\": \"ps:FillMaskedAreasRequest\",\n    \"PhotoshopActionsRequest\": \"ps:PhotoshopActionsRequest\",\n    \"ProductCropRequest\": \"ps:ProductCropRequest\",\n    \"RemoveBackgroundRequest\": \"ps:RemoveBackgroundRequest\",\n    \"RenditionCreateRequest\": \"ps:RenditionCreateRequest\",\n    \"SmartObjectRequest\"\
  : \"ps:SmartObjectRequest\",\n    \"StorageInput\": \"ps:StorageInput\",\n    \"StorageOutput\": \"ps:StorageOutput\",\n    \"TextEditRequest\": \"ps:TextEditRequest\",\n    \"addon\": {\n      \"@id\": \"ps:addon\",\n      \"@type\": \"@id\"\n    },\n    \"author\": {\n      \"@id\": \"ps:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"backgroundColor\": {\n      \"@id\": \"ps:backgroundColor\",\n      \"@type\": \"@id\"\n    },\n    \"colorDecontamination\": {\n      \"@id\": \"ps:colorDecontamination\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"ps:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entrypoints\": {\n      \"@id\": \"ps:entrypoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"host\": {\n      \"@id\": \"ps:host\",\n      \"@type\": \"@id\"\n    },\n    \"href\": {\n      \"@id\": \"ps:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icons\": {\n      \"@id\":\
  \ \"ps:icons\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"ps:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"ps:image\",\n      \"@type\": \"@id\"\n    },\n    \"inputs\": {\n      \"@id\": \"ps:inputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"ps:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"main\": {\n      \"@id\": \"ps:main\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestVersion\": {\n      \"@id\": \"ps:manifestVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"masks\": {\n      \"@id\": \"ps:masks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"ps:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"ps:name\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"options\": {\n      \"@id\": \"ps:options\",\n      \"@type\": \"@id\"\n    },\n    \"output\": {\n      \"@id\": \"ps:output\",\n      \"@type\": \"@id\"\n    },\n    \"outputs\": {\n      \"@id\": \"ps:outputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overwrite\": {\n      \"@id\": \"ps:overwrite\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requiredPermissions\": {\n      \"@id\": \"ps:requiredPermissions\",\n      \"@type\": \"@id\"\n    },\n    \"storage\": {\n      \"@id\": \"ps:storage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trim\": {\n      \"@id\": \"ps:trim\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"type\": {\n      \"@id\": \"ps:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"ps:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"ps:width\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-photoshop/refs/heads/main/json-ld/adobe-photoshop-context.jsonld
tags:
- AI/ML
- Creative Cloud
- Image Editing
- Photoshop
- Plugins
- REST API
- Scripting
- JSON-LD
- Linked Data
- Semantic Web
---
