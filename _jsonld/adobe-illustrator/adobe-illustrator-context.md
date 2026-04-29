---
api_specs:
- filename: adobe-illustrator-scripting-openapi-original.yml
  format: yaml
  label: Adobe Illustrator Scripting API
  slug: scripting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/openapi/adobe-illustrator-scripting-openapi-original.yml
class_count: 15
classes:
- Application
- Artboard
- ArtboardCreate
- Color
- Document
- DocumentCreate
- ExportOptions
- Layer
- LayerCreate
- PathItem
- PathItemCreate
- PathPoint
- Preferences
- TextFrame
- TextFrameCreate
context_file: json-ld/adobe-illustrator-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/json-ld/adobe-illustrator-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Illustrator from Adobe Illustrator.
layout: jsonld
name: Adobe Illustrator Context
namespaces:
- prefix: ai
  uri: https://developer.adobe.com/illustrator/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: activeDocument
  type: string
- container: ''
  name: activeLayer
  type: string
- container: set
  name: anchor
  type: string
- container: ''
  name: antiAliasing
  type: boolean
- container: ''
  name: area
  type: decimal
- container: ''
  name: artboardCount
  type: integer
- container: ''
  name: artboardLayout
  type: string
- container: ''
  name: artboardRange
  type: string
- container: set
  name: artboardRect
  type: string
- container: ''
  name: black
  type: decimal
- container: ''
  name: blendingMode
  type: string
- container: ''
  name: blue
  type: decimal
- container: ''
  name: buildNumber
  type: string
- container: ''
  name: characterAttributes
  type: string
- container: ''
  name: clipping
  type: boolean
- container: ''
  name: closed
  type: boolean
- container: ''
  name: color
  type: string
- container: ''
  name: colorType
  type: string
- container: ''
  name: contents
  type: string
- container: ''
  name: cornerRadius
  type: decimal
- container: ''
  name: cyan
  type: decimal
- container: ''
  name: dimPlacedImages
  type: boolean
- container: ''
  name: documentColorSpace
  type: string
- container: set
  name: documents
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: fillColor
  type: string
- container: ''
  name: filled
  type: boolean
- container: ''
  name: format
  type: string
- container: ''
  name: freeMemory
  type: integer
- container: ''
  name: fullName
  type: string
- container: ''
  name: generalPreferences
  type: reference
- container: ''
  name: gray
  type: decimal
- container: ''
  name: green
  type: decimal
- container: ''
  name: guides
  type: boolean
- container: ''
  name: hasSelectedArtwork
  type: boolean
- container: ''
  name: height
  type: decimal
- container: ''
  name: horizontalScale
  type: decimal
- container: ''
  name: id
  type: string
- container: ''
  name: index
  type: integer
- container: ''
  name: innerRadius
  type: decimal
- container: ''
  name: isClippingMask
  type: boolean
- container: ''
  name: kind
  type: string
- container: ''
  name: layer
  type: string
- container: ''
  name: layerCount
  type: integer
- container: set
  name: leftDirection
  type: string
- container: ''
  name: length
  type: decimal
- container: ''
  name: locale
  type: string
- container: ''
  name: locked
  type: boolean
- container: ''
  name: magenta
  type: decimal
- container: ''
  name: name
  type: string
- container: ''
  name: numArtboards
  type: integer
- container: ''
  name: opacity
  type: decimal
- container: ''
  name: orientation
  type: string
- container: ''
  name: paragraphAttributes
  type: string
- container: ''
  name: pathItemCount
  type: integer
- container: set
  name: pathPoints
  type: string
- container: ''
  name: pathType
  type: string
- container: ''
  name: pointType
  type: string
- container: ''
  name: points
  type: integer
- container: set
  name: position
  type: string
- container: ''
  name: preview
  type: boolean
- container: ''
  name: printable
  type: boolean
- container: ''
  name: rasterResolution
  type: string
- container: ''
  name: red
  type: decimal
- container: ''
  name: resolution
  type: decimal
- container: set
  name: rightDirection
  type: string
- container: set
  name: rulerOrigin
  type: string
- container: ''
  name: rulerPAR
  type: decimal
- container: ''
  name: rulerUnits
  type: string
- container: ''
  name: saved
  type: boolean
- container: ''
  name: scriptingVersion
  type: string
- container: ''
  name: showCenter
  type: boolean
- container: ''
  name: showCrossHairs
  type: boolean
- container: ''
  name: showSafeAreas
  type: boolean
- container: ''
  name: sides
  type: integer
- container: ''
  name: sliced
  type: boolean
- container: ''
  name: spotName
  type: string
- container: ''
  name: strokeCap
  type: string
- container: ''
  name: strokeColor
  type: string
- container: set
  name: strokeDashes
  type: string
- container: ''
  name: strokeJoin
  type: string
- container: ''
  name: strokeWidth
  type: decimal
- container: ''
  name: stroked
  type: boolean
- container: ''
  name: sublayerCount
  type: integer
- container: ''
  name: textFrameCount
  type: integer
- container: ''
  name: tint
  type: decimal
- container: ''
  name: transparency
  type: boolean
- container: ''
  name: typePreferences
  type: reference
- container: ''
  name: userInteractionLevel
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: verticalScale
  type: decimal
- container: ''
  name: visible
  type: boolean
- container: ''
  name: width
  type: decimal
- container: ''
  name: yellow
  type: decimal
property_count: 94
provider_name: Adobe Illustrator
provider_slug: adobe-illustrator
slug: adobe-illustrator-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ai\": \"https://developer.adobe.com/illustrator/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Application\": \"ai:Application\",\n    \"Artboard\": \"ai:Artboard\",\n    \"ArtboardCreate\": \"ai:ArtboardCreate\",\n    \"Color\": \"ai:Color\",\n    \"Document\": \"ai:Document\",\n    \"DocumentCreate\": \"ai:DocumentCreate\",\n    \"ExportOptions\": \"ai:ExportOptions\",\n    \"Layer\": \"ai:Layer\",\n    \"LayerCreate\": \"ai:LayerCreate\",\n    \"PathItem\": \"ai:PathItem\",\n    \"PathItemCreate\": \"ai:PathItemCreate\",\n    \"PathPoint\": \"ai:PathPoint\",\n    \"Preferences\": \"ai:Preferences\",\n    \"TextFrame\": \"ai:TextFrame\",\n    \"TextFrameCreate\": \"ai:TextFrameCreate\",\n    \"activeDocument\": {\n      \"@id\": \"ai:activeDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeLayer\": {\n      \"@id\": \"ai:activeLayer\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"anchor\": {\n      \"@id\": \"ai:anchor\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"antiAliasing\": {\n      \"@id\": \"ai:antiAliasing\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"area\": {\n      \"@id\": \"ai:area\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"artboardCount\": {\n      \"@id\": \"ai:artboardCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"artboardLayout\": {\n      \"@id\": \"ai:artboardLayout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artboardRange\": {\n      \"@id\": \"ai:artboardRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artboardRect\": {\n      \"@id\": \"ai:artboardRect\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"black\": {\n      \"@id\": \"ai:black\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"blendingMode\": {\n      \"@id\": \"ai:blendingMode\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"blue\": {\n      \"@id\": \"ai:blue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"buildNumber\": {\n      \"@id\": \"ai:buildNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characterAttributes\": {\n      \"@id\": \"ai:characterAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clipping\": {\n      \"@id\": \"ai:clipping\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"closed\": {\n      \"@id\": \"ai:closed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"color\": {\n      \"@id\": \"ai:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"colorType\": {\n      \"@id\": \"ai:colorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contents\": {\n      \"@id\": \"ai:contents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cornerRadius\": {\n      \"@id\": \"ai:cornerRadius\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cyan\": {\n      \"@id\": \"ai:cyan\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"dimPlacedImages\": {\n   \
  \   \"@id\": \"ai:dimPlacedImages\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"documentColorSpace\": {\n      \"@id\": \"ai:documentColorSpace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documents\": {\n      \"@id\": \"ai:documents\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"ai:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fillColor\": {\n      \"@id\": \"ai:fillColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filled\": {\n      \"@id\": \"ai:filled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"format\": {\n      \"@id\": \"ai:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeMemory\": {\n      \"@id\": \"ai:freeMemory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"fullName\": {\n      \"@id\": \"ai:fullName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generalPreferences\": {\n      \"@id\": \"ai:generalPreferences\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"gray\": {\n      \"@id\": \"ai:gray\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"green\": {\n      \"@id\": \"ai:green\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"guides\": {\n      \"@id\": \"ai:guides\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasSelectedArtwork\": {\n      \"@id\": \"ai:hasSelectedArtwork\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"height\": {\n      \"@id\": \"ai:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"horizontalScale\": {\n      \"@id\": \"ai:horizontalScale\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"id\": {\n      \"@id\": \"ai:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"ai:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"innerRadius\": {\n      \"@id\": \"ai:innerRadius\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"isClippingMask\": {\n      \"@id\": \"ai:isClippingMask\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"kind\": {\n      \"@id\"\
  : \"ai:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layer\": {\n      \"@id\": \"ai:layer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layerCount\": {\n      \"@id\": \"ai:layerCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"leftDirection\": {\n      \"@id\": \"ai:leftDirection\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"ai:length\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"locale\": {\n      \"@id\": \"ai:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locked\": {\n      \"@id\": \"ai:locked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"magenta\": {\n      \"@id\": \"ai:magenta\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": {\n      \"@id\": \"ai:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numArtboards\": {\n      \"@id\": \"ai:numArtboards\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"opacity\": {\n      \"@id\": \"ai:opacity\",\n   \
  \   \"@type\": \"xsd:decimal\"\n    },\n    \"orientation\": {\n      \"@id\": \"ai:orientation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paragraphAttributes\": {\n      \"@id\": \"ai:paragraphAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathItemCount\": {\n      \"@id\": \"ai:pathItemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pathPoints\": {\n      \"@id\": \"ai:pathPoints\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathType\": {\n      \"@id\": \"ai:pathType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointType\": {\n      \"@id\": \"ai:pointType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"points\": {\n      \"@id\": \"ai:points\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"position\": {\n      \"@id\": \"ai:position\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preview\": {\n      \"@id\": \"ai:preview\",\n      \"@type\": \"xsd:boolean\"\n    },\n\
  \    \"printable\": {\n      \"@id\": \"ai:printable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"rasterResolution\": {\n      \"@id\": \"ai:rasterResolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"red\": {\n      \"@id\": \"ai:red\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"resolution\": {\n      \"@id\": \"ai:resolution\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rightDirection\": {\n      \"@id\": \"ai:rightDirection\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rulerOrigin\": {\n      \"@id\": \"ai:rulerOrigin\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rulerPAR\": {\n      \"@id\": \"ai:rulerPAR\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"rulerUnits\": {\n      \"@id\": \"ai:rulerUnits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"saved\": {\n      \"@id\": \"ai:saved\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"scriptingVersion\": {\n      \"@id\": \"\
  ai:scriptingVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"showCenter\": {\n      \"@id\": \"ai:showCenter\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"showCrossHairs\": {\n      \"@id\": \"ai:showCrossHairs\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"showSafeAreas\": {\n      \"@id\": \"ai:showSafeAreas\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sides\": {\n      \"@id\": \"ai:sides\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sliced\": {\n      \"@id\": \"ai:sliced\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"spotName\": {\n      \"@id\": \"ai:spotName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strokeCap\": {\n      \"@id\": \"ai:strokeCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strokeColor\": {\n      \"@id\": \"ai:strokeColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strokeDashes\": {\n      \"@id\": \"ai:strokeDashes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strokeJoin\"\
  : {\n      \"@id\": \"ai:strokeJoin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strokeWidth\": {\n      \"@id\": \"ai:strokeWidth\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"stroked\": {\n      \"@id\": \"ai:stroked\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sublayerCount\": {\n      \"@id\": \"ai:sublayerCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"textFrameCount\": {\n      \"@id\": \"ai:textFrameCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tint\": {\n      \"@id\": \"ai:tint\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transparency\": {\n      \"@id\": \"ai:transparency\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"typePreferences\": {\n      \"@id\": \"ai:typePreferences\",\n      \"@type\": \"@id\"\n    },\n    \"userInteractionLevel\": {\n      \"@id\": \"ai:userInteractionLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"ai:version\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"verticalScale\": {\n      \"@id\": \"ai:verticalScale\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"visible\": {\n      \"@id\": \"ai:visible\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"width\": {\n      \"@id\": \"ai:width\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"yellow\": {\n      \"@id\": \"ai:yellow\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-illustrator/refs/heads/main/json-ld/adobe-illustrator-context.jsonld
tags:
- Creative Cloud
- Design
- Illustrator
- Vector Graphics
- JSON-LD
- Linked Data
- Semantic Web
---
