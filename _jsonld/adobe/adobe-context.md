---
api_specs:
- filename: adobe-pdf-services-api-openapi.yml
  format: yaml
  label: Adobe PDF Services API
  slug: adobe-pdf-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/openapi/adobe-pdf-services-api-openapi.yml
class_count: 45
classes:
- id
- type
- PDFJob
- Asset
- InputAsset
- OutputAsset
- PageRange
- PDFProperties
- PageProperties
- PasswordProtection
- Permissions
- ExtractOptions
- JobError
- CreatePDFOperation
- ExportPDFOperation
- CombinePDFOperation
- SplitPDFOperation
- OCROperation
- CompressPDFOperation
- ProtectPDFOperation
- RemoveProtectionOperation
- LinearizePDFOperation
- ExtractPDFOperation
- AutoTagOperation
- DocumentGenerationOperation
- status
- error
- metadata
- userPassword
- ownerPassword
- password
- permissions
- jsonDataForMerge
- fragments
- title
- description
- author
- creator
- producer
- code
- message
- passwordProtection
- splitOptions
- basePagesRange
- assetPagesRange
context_file: json-ld/adobe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/json-ld/adobe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe from Adobe.
layout: jsonld
name: Adobe Context
namespaces:
- prefix: adobe
  uri: https://ns.adobe.com/pdf-services/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: assetID
  type: string
- container: ''
  name: uploadUri
  type: reference
- container: ''
  name: downloadUri
  type: reference
- container: ''
  name: asset
  type: reference
- container: ''
  name: mediaType
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: list
  name: pageRanges
  type: ''
- container: list
  name: pagesOrder
  type: ''
- container: list
  name: pageActions
  type: ''
- container: ''
  name: rotation
  type: integer
- container: list
  name: assets
  type: ''
- container: list
  name: assetsToInsert
  type: ''
- container: list
  name: assetsToReplace
  type: ''
- container: ''
  name: baseAssetID
  type: string
- container: ''
  name: insertAt
  type: integer
- container: ''
  name: targetFormat
  type: string
- container: ''
  name: documentLanguage
  type: string
- container: ''
  name: ocrLanguage
  type: string
- container: ''
  name: ocrType
  type: string
- container: ''
  name: compressionLevel
  type: string
- container: ''
  name: outputFormat
  type: string
- container: ''
  name: encryptionAlgorithm
  type: string
- container: ''
  name: printQuality
  type: string
- container: ''
  name: editContent
  type: boolean
- container: ''
  name: copyContent
  type: boolean
- container: ''
  name: editAnnotations
  type: boolean
- container: ''
  name: fillForms
  type: boolean
- container: ''
  name: assembleDocument
  type: boolean
- container: list
  name: elementsToExtract
  type: ''
- container: list
  name: elementsToExtractRenditions
  type: ''
- container: ''
  name: tableOutputFormat
  type: string
- container: ''
  name: getStylingInfo
  type: boolean
- container: ''
  name: addCharInfo
  type: boolean
- container: ''
  name: generateReport
  type: boolean
- container: ''
  name: shiftHeadings
  type: boolean
- container: ''
  name: includePageLevelProperties
  type: boolean
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: pdfVersion
  type: string
- container: ''
  name: isEncrypted
  type: boolean
- container: ''
  name: isLinearized
  type: boolean
- container: ''
  name: hasFormFields
  type: boolean
- container: ''
  name: isTagged
  type: boolean
- container: ''
  name: pageNumber
  type: integer
- container: ''
  name: width
  type: decimal
- container: ''
  name: height
  type: decimal
- container: list
  name: pages
  type: ''
- container: ''
  name: createdDate
  type: dateTime
- container: ''
  name: modifiedDate
  type: dateTime
- container: ''
  name: fileCount
  type: integer
property_count: 51
provider_name: Adobe
provider_slug: adobe
slug: adobe-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"adobe\": \"https://ns.adobe.com/pdf-services/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"PDFJob\": \"adobe:PDFJob\",\n    \"Asset\": \"adobe:Asset\",\n    \"InputAsset\": \"adobe:InputAsset\",\n    \"OutputAsset\": \"adobe:OutputAsset\",\n    \"PageRange\": \"adobe:PageRange\",\n    \"PDFProperties\": \"adobe:PDFProperties\",\n    \"PageProperties\": \"adobe:PageProperties\",\n    \"PasswordProtection\": \"adobe:PasswordProtection\",\n    \"Permissions\": \"adobe:Permissions\",\n    \"ExtractOptions\": \"adobe:ExtractOptions\",\n    \"JobError\": \"adobe:JobError\",\n\n    \"CreatePDFOperation\": \"adobe:CreatePDFOperation\",\n    \"ExportPDFOperation\": \"adobe:ExportPDFOperation\",\n    \"CombinePDFOperation\": \"adobe:CombinePDFOperation\",\n\
  \    \"SplitPDFOperation\": \"adobe:SplitPDFOperation\",\n    \"OCROperation\": \"adobe:OCROperation\",\n    \"CompressPDFOperation\": \"adobe:CompressPDFOperation\",\n    \"ProtectPDFOperation\": \"adobe:ProtectPDFOperation\",\n    \"RemoveProtectionOperation\": \"adobe:RemoveProtectionOperation\",\n    \"LinearizePDFOperation\": \"adobe:LinearizePDFOperation\",\n    \"ExtractPDFOperation\": \"adobe:ExtractPDFOperation\",\n    \"AutoTagOperation\": \"adobe:AutoTagOperation\",\n    \"DocumentGenerationOperation\": \"adobe:DocumentGenerationOperation\",\n\n    \"assetID\": {\n      \"@id\": \"adobe:assetID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadUri\": {\n      \"@id\": \"adobe:uploadUri\",\n      \"@type\": \"@id\"\n    },\n    \"downloadUri\": {\n      \"@id\": \"adobe:downloadUri\",\n      \"@type\": \"@id\"\n    },\n\n    \"status\": \"adobe:status\",\n    \"asset\": {\n      \"@id\": \"adobe:asset\",\n      \"@type\": \"@id\"\n    },\n    \"error\": \"adobe:error\"\
  ,\n\n    \"mediaType\": {\n      \"@id\": \"adobe:mediaType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"adobe:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"metadata\": \"adobe:metadata\",\n\n    \"start\": {\n      \"@id\": \"adobe:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"end\": {\n      \"@id\": \"adobe:end\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageRanges\": {\n      \"@id\": \"adobe:pageRanges\",\n      \"@container\": \"@list\"\n    },\n    \"pagesOrder\": {\n      \"@id\": \"adobe:pagesOrder\",\n      \"@container\": \"@list\"\n    },\n    \"pageActions\": {\n      \"@id\": \"adobe:pageActions\",\n      \"@container\": \"@list\"\n    },\n    \"rotation\": {\n      \"@id\": \"adobe:rotation\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"assets\": {\n      \"@id\": \"adobe:assets\",\n      \"@container\": \"@list\"\n    },\n    \"assetsToInsert\": {\n      \"@id\": \"adobe:assetsToInsert\",\n      \"\
  @container\": \"@list\"\n    },\n    \"assetsToReplace\": {\n      \"@id\": \"adobe:assetsToReplace\",\n      \"@container\": \"@list\"\n    },\n    \"baseAssetID\": {\n      \"@id\": \"adobe:baseAssetID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insertAt\": {\n      \"@id\": \"adobe:insertAt\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"targetFormat\": {\n      \"@id\": \"adobe:targetFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentLanguage\": {\n      \"@id\": \"adobe:documentLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ocrLanguage\": {\n      \"@id\": \"adobe:ocrLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ocrType\": {\n      \"@id\": \"adobe:ocrType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compressionLevel\": {\n      \"@id\": \"adobe:compressionLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"adobe:outputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"userPassword\"\
  : \"adobe:userPassword\",\n    \"ownerPassword\": \"adobe:ownerPassword\",\n    \"encryptionAlgorithm\": {\n      \"@id\": \"adobe:encryptionAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": \"adobe:password\",\n    \"permissions\": \"adobe:permissions\",\n    \"printQuality\": {\n      \"@id\": \"adobe:printQuality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"editContent\": {\n      \"@id\": \"adobe:editContent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"copyContent\": {\n      \"@id\": \"adobe:copyContent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"editAnnotations\": {\n      \"@id\": \"adobe:editAnnotations\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fillForms\": {\n      \"@id\": \"adobe:fillForms\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"assembleDocument\": {\n      \"@id\": \"adobe:assembleDocument\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"elementsToExtract\": {\n      \"@id\": \"adobe:elementsToExtract\"\
  ,\n      \"@container\": \"@list\"\n    },\n    \"elementsToExtractRenditions\": {\n      \"@id\": \"adobe:elementsToExtractRenditions\",\n      \"@container\": \"@list\"\n    },\n    \"tableOutputFormat\": {\n      \"@id\": \"adobe:tableOutputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"getStylingInfo\": {\n      \"@id\": \"adobe:getStylingInfo\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"addCharInfo\": {\n      \"@id\": \"adobe:addCharInfo\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"generateReport\": {\n      \"@id\": \"adobe:generateReport\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shiftHeadings\": {\n      \"@id\": \"adobe:shiftHeadings\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"jsonDataForMerge\": \"adobe:jsonDataForMerge\",\n    \"fragments\": \"adobe:fragments\",\n\n    \"includePageLevelProperties\": {\n      \"@id\": \"adobe:includePageLevelProperties\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pageCount\": {\n      \"\
  @id\": \"adobe:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pdfVersion\": {\n      \"@id\": \"adobe:pdfVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isEncrypted\": {\n      \"@id\": \"adobe:isEncrypted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isLinearized\": {\n      \"@id\": \"adobe:isLinearized\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasFormFields\": {\n      \"@id\": \"adobe:hasFormFields\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isTagged\": {\n      \"@id\": \"adobe:isTagged\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pageNumber\": {\n      \"@id\": \"adobe:pageNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"width\": {\n      \"@id\": \"adobe:width\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"height\": {\n      \"@id\": \"adobe:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pages\": {\n      \"@id\": \"adobe:pages\",\n      \"@container\": \"@list\"\n    },\n\n    \"title\": \"dcterms:title\"\
  ,\n    \"description\": \"dcterms:description\",\n    \"author\": \"dcterms:creator\",\n    \"creator\": \"adobe:creator\",\n    \"producer\": \"adobe:producer\",\n    \"createdDate\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"code\": \"adobe:errorCode\",\n    \"message\": \"adobe:errorMessage\",\n\n    \"passwordProtection\": \"adobe:passwordProtection\",\n    \"splitOptions\": \"adobe:splitOptions\",\n    \"fileCount\": {\n      \"@id\": \"adobe:fileCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"basePagesRange\": \"adobe:basePagesRange\",\n    \"assetPagesRange\": \"adobe:assetPagesRange\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe/refs/heads/main/json-ld/adobe-context.jsonld
tags:
- Analytics
- Creative Cloud
- Digital Asset Management
- Document Services
- E-Commerce
- E-Signatures
- Experience Cloud
- Generative AI
- Marketing
- PDF
- Work Management
- JSON-LD
- Linked Data
- Semantic Web
---
