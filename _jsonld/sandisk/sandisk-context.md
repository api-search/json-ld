---
class_count: 4
classes:
- SanDisk
- StorageDevice
- SDK
- DeveloperPortal
context_file: json-ld/sandisk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sandisk/refs/heads/main/json-ld/sandisk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sandisk from SanDisk.
layout: jsonld
name: Sandisk Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sandisk
  uri: https://api-evangelist.github.io/sandisk/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: iXpand
  type: schema:Product
- container: ''
  name: iXpandSDK
  type: schema:SoftwareApplication
- container: ''
  name: HQMESDK
  type: schema:SoftwareApplication
- container: ''
  name: FileSystemAPI
  type: schema:WebAPI
- container: ''
  name: SystemAPI
  type: schema:WebAPI
- container: ''
  name: productPlanId
  type: string
- container: ''
  name: storageCapacity
  type: string
- container: ''
  name: interfaceType
  type: string
property_count: 8
provider_name: SanDisk
provider_slug: sandisk
slug: sandisk-context
source_filename: sandisk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sandisk\": \"https://api-evangelist.github.io/sandisk/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SanDisk\": \"schema:Brand\",\n    \"StorageDevice\": \"schema:Product\",\n    \"SDK\": \"schema:SoftwareApplication\",\n    \"DeveloperPortal\": \"schema:WebSite\",\n\n    \"iXpand\": {\n      \"@id\": \"sandisk:iXpand\",\n      \"@type\": \"schema:Product\",\n      \"schema:brand\": { \"@id\": \"sandisk:SanDisk\" },\n      \"schema:description\": \"SanDisk Flash Drives for iOS devices via Lightning connector\"\n    },\n\n    \"iXpandSDK\": {\n      \"@id\": \"sandisk:iXpandSDK\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:applicationCategory\": \"DeveloperApplication\",\n      \"schema:operatingSystem\": \"iOS\",\n      \"schema:description\": \"iOS SDK for integrating iXpand Flash Drive access into third-party apps\"\n    },\n\n    \"\
  HQMESDK\": {\n      \"@id\": \"sandisk:HQMESDK\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:applicationCategory\": \"DeveloperApplication\",\n      \"schema:operatingSystem\": \"Android\",\n      \"schema:description\": \"Android SDK based on IEEE P2200/D2 for media storage and retrieval\"\n    },\n\n    \"FileSystemAPI\": {\n      \"@id\": \"sandisk:FileSystemAPI\",\n      \"@type\": \"schema:WebAPI\",\n      \"schema:description\": \"APIs for reading, writing, and managing files on iXpand storage\"\n    },\n\n    \"SystemAPI\": {\n      \"@id\": \"sandisk:SystemAPI\",\n      \"@type\": \"schema:WebAPI\",\n      \"schema:description\": \"Administrative APIs for iXpand device metadata and configuration\"\n    },\n\n    \"productPlanId\": {\n      \"@id\": \"sandisk:productPlanId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"storageCapacity\": {\n      \"@id\": \"schema:storageSize\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"interfaceType\": {\n \
  \     \"@id\": \"schema:additionalProperty\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sandisk/refs/heads/main/json-ld/sandisk-context.jsonld
tags:
- Flash Memory
- Storage
- SDK
- Mobile
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
