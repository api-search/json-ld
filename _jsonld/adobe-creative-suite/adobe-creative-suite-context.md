---
class_count: 56
classes:
- Adobe Creative Suite Image Job
- Adobe Firefly Generation Request and Response
- Adobe Stock File
- Asset
- AssetReference
- AssetUploadRequest
- AssetUploadResponse
- AsyncJobSubmitted
- AutoTagRequest
- Category
- CombinePDFRequest
- CompressPDFRequest
- CreatePDFRequest
- CutoutRequest
- DocumentGenerationRequest
- DocumentOperations
- DocumentOperationsRequest
- ErrorResponse
- ExportPDFRequest
- GenerateSimilarRequest
- GenerationStatus
- ImageExpandRequest
- ImageFillRequest
- ImageGenerateRequest
- ImageSize
- InputImageReference
- JobInput
- JobOutput
- JobStatus
- JobSubmitted
- Layer
- LayerManageRequest
- LicenseHistoryResult
- LicenseReference
- LicenseRequest
- LicenseResponse
- LicenseStatsResponse
- LinearizePDFRequest
- MaskRequest
- MemberProfile
- OCRRequest
- ObjectCompositeRequest
- OperationStatus
- OperationSubmitted
- OutputImage
- PageRange
- ProductCropRequest
- RenderOutput
- RenditionCreateRequest
- SearchResult
- StockFile
- StockFileResponse
- StraightenRequest
- StyleOptions
- TextEditRequest
- VideoGenerateRequest
context_file: json-ld/adobe-creative-suite-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/json-ld/adobe-creative-suite-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Creative Suite from Adobe Creative Suite.
layout: jsonld
name: Adobe Creative Suite Context
namespaces:
- prefix: adobe
  uri: https://developer.adobe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: _links
  type: reference
- container: ''
  name: asset
  type: string
- container: ''
  name: assetID
  type: string
- container: set
  name: assets
  type: string
- container: ''
  name: blendMode
  type: string
- container: ''
  name: bounds
  type: reference
- container: ''
  name: category
  type: reference
- container: set
  name: children
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: comp_url
  type: string
- container: ''
  name: compressionLevel
  type: string
- container: ''
  name: contentClass
  type: string
- container: ''
  name: content_id
  type: integer
- container: ''
  name: content_type
  type: string
- container: ''
  name: country_name
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: creator_id
  type: integer
- container: ''
  name: creator_name
  type: string
- container: ''
  name: details
  type: string
- container: ''
  name: documentLanguage
  type: string
- container: ''
  name: downloadUri
  type: string
- container: ''
  name: download_url
  type: string
- container: ''
  name: duration
  type: decimal
- container: ''
  name: end
  type: integer
- container: set
  name: errors
  type: string
- container: ''
  name: exportOCRLocale
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: flatten
  type: boolean
- container: ''
  name: generateReport
  type: boolean
- container: ''
  name: has_releases
  type: boolean
- container: ''
  name: height
  type: integer
- container: ''
  name: href
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: image
  type: string
- container: ''
  name: index
  type: integer
- container: ''
  name: input
  type: reference
- container: set
  name: inputs
  type: string
- container: ''
  name: is_editorial
  type: boolean
- container: ''
  name: is_licensed
  type: string
- container: ''
  name: jobID
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: jsonDataForMerge
  type: reference
- container: set
  name: keywords
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: locale
  type: string
- container: ''
  name: locked
  type: boolean
- container: ''
  name: mask
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: media_type_id
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: modified
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
  name: notTaggedAdds
  type: boolean
- container: ''
  name: numVariations
  type: integer
- container: ''
  name: ocrLang
  type: string
- container: ''
  name: opacity
  type: integer
- container: ''
  name: options
  type: string
- container: ''
  name: output
  type: reference
- container: ''
  name: outputFormat
  type: string
- container: set
  name: outputs
  type: string
- container: ''
  name: overwrite
  type: boolean
- container: ''
  name: placement
  type: reference
- container: ''
  name: premium_level_id
  type: integer
- container: set
  name: presets
  type: string
- container: ''
  name: prompt
  type: string
- container: ''
  name: purchase_details
  type: reference
- container: ''
  name: purchase_params
  type: reference
- container: ''
  name: referenceImage
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: resize
  type: reference
- container: ''
  name: seed
  type: integer
- container: set
  name: seeds
  type: string
- container: ''
  name: shiftHeadings
  type: boolean
- container: ''
  name: size
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: start
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: statusUrl
  type: string
- container: ''
  name: stock_user
  type: reference
- container: ''
  name: storage
  type: string
- container: ''
  name: strength
  type: integer
- container: ''
  name: style
  type: string
- container: ''
  name: targetFormat
  type: string
- container: ''
  name: thumbnail_1000_url
  type: string
- container: ''
  name: thumbnail_500_url
  type: string
- container: ''
  name: thumbnail_height
  type: integer
- container: ''
  name: thumbnail_url
  type: string
- container: ''
  name: thumbnail_width
  type: integer
- container: ''
  name: title
  type: string
- container: ''
  name: trim
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: uploadUri
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: vector_type
  type: string
- container: ''
  name: visible
  type: boolean
- container: ''
  name: width
  type: integer
property_count: 99
provider_name: Adobe Creative Suite
provider_slug: adobe-creative-suite
slug: adobe-creative-suite-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adobe\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Adobe Creative Suite Image Job\": \"adobe:Adobe Creative Suite Image Job\",\n    \"Adobe Firefly Generation Request and Response\": \"adobe:Adobe Firefly Generation Request and Response\",\n    \"Adobe Stock File\": \"adobe:Adobe Stock File\",\n    \"Asset\": \"adobe:Asset\",\n    \"AssetReference\": \"adobe:AssetReference\",\n    \"AssetUploadRequest\": \"adobe:AssetUploadRequest\",\n    \"AssetUploadResponse\": \"adobe:AssetUploadResponse\",\n    \"AsyncJobSubmitted\": \"adobe:AsyncJobSubmitted\",\n    \"AutoTagRequest\": \"adobe:AutoTagRequest\",\n    \"Category\": \"adobe:Category\",\n    \"CombinePDFRequest\": \"adobe:CombinePDFRequest\",\n    \"CompressPDFRequest\": \"adobe:CompressPDFRequest\",\n    \"CreatePDFRequest\": \"adobe:CreatePDFRequest\",\n    \"CutoutRequest\"\
  : \"adobe:CutoutRequest\",\n    \"DocumentGenerationRequest\": \"adobe:DocumentGenerationRequest\",\n    \"DocumentOperations\": \"adobe:DocumentOperations\",\n    \"DocumentOperationsRequest\": \"adobe:DocumentOperationsRequest\",\n    \"ErrorResponse\": \"adobe:ErrorResponse\",\n    \"ExportPDFRequest\": \"adobe:ExportPDFRequest\",\n    \"GenerateSimilarRequest\": \"adobe:GenerateSimilarRequest\",\n    \"GenerationStatus\": \"adobe:GenerationStatus\",\n    \"ImageExpandRequest\": \"adobe:ImageExpandRequest\",\n    \"ImageFillRequest\": \"adobe:ImageFillRequest\",\n    \"ImageGenerateRequest\": \"adobe:ImageGenerateRequest\",\n    \"ImageSize\": \"adobe:ImageSize\",\n    \"InputImageReference\": \"adobe:InputImageReference\",\n    \"JobInput\": \"adobe:JobInput\",\n    \"JobOutput\": \"adobe:JobOutput\",\n    \"JobStatus\": \"adobe:JobStatus\",\n    \"JobSubmitted\": \"adobe:JobSubmitted\",\n    \"Layer\": \"adobe:Layer\",\n    \"LayerManageRequest\": \"adobe:LayerManageRequest\",\n \
  \   \"LicenseHistoryResult\": \"adobe:LicenseHistoryResult\",\n    \"LicenseReference\": \"adobe:LicenseReference\",\n    \"LicenseRequest\": \"adobe:LicenseRequest\",\n    \"LicenseResponse\": \"adobe:LicenseResponse\",\n    \"LicenseStatsResponse\": \"adobe:LicenseStatsResponse\",\n    \"LinearizePDFRequest\": \"adobe:LinearizePDFRequest\",\n    \"MaskRequest\": \"adobe:MaskRequest\",\n    \"MemberProfile\": \"adobe:MemberProfile\",\n    \"OCRRequest\": \"adobe:OCRRequest\",\n    \"ObjectCompositeRequest\": \"adobe:ObjectCompositeRequest\",\n    \"OperationStatus\": \"adobe:OperationStatus\",\n    \"OperationSubmitted\": \"adobe:OperationSubmitted\",\n    \"OutputImage\": \"adobe:OutputImage\",\n    \"PageRange\": \"adobe:PageRange\",\n    \"ProductCropRequest\": \"adobe:ProductCropRequest\",\n    \"RenderOutput\": \"adobe:RenderOutput\",\n    \"RenditionCreateRequest\": \"adobe:RenditionCreateRequest\",\n    \"SearchResult\": \"adobe:SearchResult\",\n    \"StockFile\": \"adobe:StockFile\"\
  ,\n    \"StockFileResponse\": \"adobe:StockFileResponse\",\n    \"StraightenRequest\": \"adobe:StraightenRequest\",\n    \"StyleOptions\": \"adobe:StyleOptions\",\n    \"TextEditRequest\": \"adobe:TextEditRequest\",\n    \"VideoGenerateRequest\": \"adobe:VideoGenerateRequest\",\n    \"_links\": {\n      \"@id\": \"adobe:_links\",\n      \"@type\": \"@id\"\n    },\n    \"asset\": {\n      \"@id\": \"adobe:asset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetID\": {\n      \"@id\": \"adobe:assetID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assets\": {\n      \"@id\": \"adobe:assets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blendMode\": {\n      \"@id\": \"adobe:blendMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bounds\": {\n      \"@id\": \"adobe:bounds\",\n      \"@type\": \"@id\"\n    },\n    \"category\": {\n      \"@id\": \"adobe:category\",\n      \"@type\": \"@id\"\n    },\n    \"children\": {\n      \"@id\": \"adobe:children\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"adobe:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comp_url\": {\n      \"@id\": \"adobe:comp_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compressionLevel\": {\n      \"@id\": \"adobe:compressionLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentClass\": {\n      \"@id\": \"adobe:contentClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content_id\": {\n      \"@id\": \"adobe:content_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"content_type\": {\n      \"@id\": \"adobe:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country_name\": {\n      \"@id\": \"adobe:country_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"adobe:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator_id\": {\n      \"@id\": \"adobe:creator_id\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"creator_name\": {\n      \"@id\": \"adobe:creator_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"details\": {\n      \"@id\": \"adobe:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentLanguage\": {\n      \"@id\": \"adobe:documentLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUri\": {\n      \"@id\": \"adobe:downloadUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"download_url\": {\n      \"@id\": \"adobe:download_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"adobe:duration\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"end\": {\n      \"@id\": \"adobe:end\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errors\": {\n      \"@id\": \"adobe:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportOCRLocale\": {\n      \"@id\": \"adobe:exportOCRLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"adobe:files\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flatten\": {\n      \"@id\": \"adobe:flatten\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"generateReport\": {\n      \"@id\": \"adobe:generateReport\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"has_releases\": {\n      \"@id\": \"adobe:has_releases\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"height\": {\n      \"@id\": \"adobe:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"href\": {\n      \"@id\": \"adobe:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adobe:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"image\": {\n      \"@id\": \"adobe:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"adobe:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"input\": {\n      \"@id\": \"adobe:input\",\n      \"@type\": \"@id\"\n    },\n    \"inputs\": {\n      \"@id\": \"adobe:inputs\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_editorial\": {\n      \"@id\": \"adobe:is_editorial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_licensed\": {\n      \"@id\": \"adobe:is_licensed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobID\": {\n      \"@id\": \"adobe:jobID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"adobe:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonDataForMerge\": {\n      \"@id\": \"adobe:jsonDataForMerge\",\n      \"@type\": \"@id\"\n    },\n    \"keywords\": {\n      \"@id\": \"adobe:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"adobe:license\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"adobe:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": {\n      \"@id\": \"adobe:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locked\": {\n      \"@id\"\
  : \"adobe:locked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"mask\": {\n      \"@id\": \"adobe:mask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mediaType\": {\n      \"@id\": \"adobe:mediaType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media_type_id\": {\n      \"@id\": \"adobe:media_type_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"adobe:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modified\": {\n      \"@id\": \"adobe:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": {\n      \"@id\": \"adobe:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nb_results\": {\n      \"@id\": \"adobe:nb_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"negativePrompt\": {\n      \"@id\": \"adobe:negativePrompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notTaggedAdds\": {\n      \"@id\": \"adobe:notTaggedAdds\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"numVariations\": {\n   \
  \   \"@id\": \"adobe:numVariations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ocrLang\": {\n      \"@id\": \"adobe:ocrLang\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opacity\": {\n      \"@id\": \"adobe:opacity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"options\": {\n      \"@id\": \"adobe:options\",\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"adobe:output\",\n      \"@type\": \"@id\"\n    },\n    \"outputFormat\": {\n      \"@id\": \"adobe:outputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"adobe:outputs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overwrite\": {\n      \"@id\": \"adobe:overwrite\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"placement\": {\n      \"@id\": \"adobe:placement\",\n      \"@type\": \"@id\"\n    },\n    \"premium_level_id\": {\n      \"@id\": \"adobe:premium_level_id\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"presets\": {\n      \"@id\": \"adobe:presets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt\": {\n      \"@id\": \"adobe:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchase_details\": {\n      \"@id\": \"adobe:purchase_details\",\n      \"@type\": \"@id\"\n    },\n    \"purchase_params\": {\n      \"@id\": \"adobe:purchase_params\",\n      \"@type\": \"@id\"\n    },\n    \"referenceImage\": {\n      \"@id\": \"adobe:referenceImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"adobe:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resize\": {\n      \"@id\": \"adobe:resize\",\n      \"@type\": \"@id\"\n    },\n    \"seed\": {\n      \"@id\": \"adobe:seed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"seeds\": {\n      \"@id\": \"adobe:seeds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shiftHeadings\": {\n      \"@id\": \"adobe:shiftHeadings\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"size\": {\n      \"@id\": \"adobe:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"adobe:source\",\n      \"@type\": \"@id\"\n    },\n    \"start\": {\n      \"@id\": \"adobe:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"adobe:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusUrl\": {\n      \"@id\": \"adobe:statusUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stock_user\": {\n      \"@id\": \"adobe:stock_user\",\n      \"@type\": \"@id\"\n    },\n    \"storage\": {\n      \"@id\": \"adobe:storage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strength\": {\n      \"@id\": \"adobe:strength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"style\": {\n      \"@id\": \"adobe:style\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetFormat\": {\n      \"@id\": \"adobe:targetFormat\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"thumbnail_1000_url\": {\n      \"@id\": \"adobe:thumbnail_1000_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbnail_500_url\": {\n      \"@id\": \"adobe:thumbnail_500_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbnail_height\": {\n      \"@id\": \"adobe:thumbnail_height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"thumbnail_url\": {\n      \"@id\": \"adobe:thumbnail_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbnail_width\": {\n      \"@id\": \"adobe:thumbnail_width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": {\n      \"@id\": \"adobe:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trim\": {\n      \"@id\": \"adobe:trim\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"adobe:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadUri\": {\n      \"@id\": \"adobe:uploadUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adobe:value\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"vector_type\": {\n      \"@id\": \"adobe:vector_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visible\": {\n      \"@id\": \"adobe:visible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"width\": {\n      \"@id\": \"adobe:width\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/json-ld/adobe-creative-suite-context.jsonld
tags:
- Creative
- Design
- Graphics
- Photography
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
