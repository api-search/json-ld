---
api_specs:
- filename: google-docs-api-v1-openapi.yml
  format: yaml
  label: Google Docs API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-docs/refs/heads/main/openapi/google-docs-api-v1-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-docs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-docs/refs/heads/main/json-ld/google-docs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Docs from Google Docs.
layout: jsonld
name: Google Docs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gdocs
  uri: https://developers.google.com/docs/api/reference/rest/v1/documents#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Document
  type: ''
- container: ''
  name: Tab
  type: ''
- container: ''
  name: TabProperties
  type: ''
- container: ''
  name: DocumentTab
  type: ''
- container: ''
  name: Body
  type: ''
- container: ''
  name: StructuralElement
  type: ''
- container: ''
  name: Paragraph
  type: ''
- container: ''
  name: ParagraphElement
  type: ''
- container: ''
  name: TextRun
  type: ''
- container: ''
  name: TextStyle
  type: ''
- container: ''
  name: ParagraphStyle
  type: ''
- container: ''
  name: DocumentStyle
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: TableRow
  type: ''
- container: ''
  name: TableCell
  type: ''
- container: ''
  name: Header
  type: ''
- container: ''
  name: Footer
  type: ''
- container: ''
  name: Footnote
  type: ''
- container: ''
  name: InlineObject
  type: ''
- container: ''
  name: EmbeddedObject
  type: ''
- container: ''
  name: ImageProperties
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: PersonProperties
  type: ''
- container: ''
  name: RichLink
  type: ''
- container: ''
  name: RichLinkProperties
  type: ''
- container: ''
  name: Link
  type: ''
- container: ''
  name: Dimension
  type: ''
- container: ''
  name: Size
  type: ''
- container: ''
  name: OptionalColor
  type: ''
- container: ''
  name: Color
  type: ''
- container: ''
  name: RgbColor
  type: ''
- container: ''
  name: NamedRange
  type: ''
- container: ''
  name: Range
  type: ''
- container: ''
  name: List
  type: ''
- container: ''
  name: Bullet
  type: ''
- container: ''
  name: WeightedFontFamily
  type: ''
property_count: 36
provider_name: Google Docs
provider_slug: google-docs
slug: google-docs-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://developers.google.com/docs/api/reference/rest/v1/documents#\",\n    \"schema\": \"https://schema.org/\",\n    \"gdocs\": \"https://developers.google.com/docs/api/reference/rest/v1/documents#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Document\": {\n      \"@id\": \"gdocs:Document\",\n      \"@context\": {\n        \"documentId\": {\n          \"@id\": \"gdocs:Document.documentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tabs\": {\n          \"@id\": \"gdocs:Document.tabs\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"revisionId\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"suggestionsViewMode\": {\n          \"@id\": \"gdocs:Document.suggestionsViewMode\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"body\": {\n          \"@id\": \"gdocs:Document.body\",\n          \"@type\": \"@id\"\n        },\n        \"headers\": {\n          \"@id\": \"gdocs:Document.headers\",\n          \"@container\": \"@index\"\n        },\n        \"footers\": {\n          \"@id\": \"gdocs:Document.footers\",\n          \"@container\": \"@index\"\n        },\n        \"footnotes\": {\n          \"@id\": \"gdocs:Document.footnotes\",\n          \"@container\": \"@index\"\n        },\n        \"documentStyle\": {\n          \"@id\": \"gdocs:Document.documentStyle\",\n          \"@type\": \"@id\"\n        },\n        \"namedStyles\": {\n          \"@id\": \"gdocs:Document.namedStyles\",\n          \"@type\": \"@id\"\n        },\n        \"lists\": {\n          \"@id\": \"gdocs:Document.lists\",\n          \"@container\": \"@index\"\n        },\n        \"namedRanges\": {\n          \"@id\": \"gdocs:Document.namedRanges\",\n          \"@container\"\
  : \"@index\"\n        },\n        \"inlineObjects\": {\n          \"@id\": \"gdocs:Document.inlineObjects\",\n          \"@container\": \"@index\"\n        },\n        \"positionedObjects\": {\n          \"@id\": \"gdocs:Document.positionedObjects\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"Tab\": {\n      \"@id\": \"gdocs:Tab\",\n      \"@context\": {\n        \"tabProperties\": {\n          \"@id\": \"gdocs:Tab.tabProperties\",\n          \"@type\": \"@id\"\n        },\n        \"childTabs\": {\n          \"@id\": \"gdocs:Tab.childTabs\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"documentTab\": {\n          \"@id\": \"gdocs:Tab.documentTab\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TabProperties\": {\n      \"@id\": \"gdocs:TabProperties\",\n      \"@context\": {\n        \"tabId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentTabId\": {\n          \"@id\": \"gdocs:TabProperties.parentTabId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"index\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"DocumentTab\": {\n      \"@id\": \"gdocs:DocumentTab\",\n      \"@context\": {\n        \"body\": {\n          \"@id\": \"gdocs:DocumentTab.body\",\n          \"@type\": \"@id\"\n        },\n        \"headers\": {\n          \"@id\": \"gdocs:DocumentTab.headers\",\n          \"@container\": \"@index\"\n        },\n        \"footers\": {\n          \"@id\": \"gdocs:DocumentTab.footers\",\n          \"@container\": \"@index\"\n        },\n        \"footnotes\": {\n          \"@id\": \"gdocs:DocumentTab.footnotes\",\n          \"@container\": \"@index\"\n        },\n        \"documentStyle\": {\n          \"@id\": \"\
  gdocs:DocumentTab.documentStyle\",\n          \"@type\": \"@id\"\n        },\n        \"namedStyles\": {\n          \"@id\": \"gdocs:DocumentTab.namedStyles\",\n          \"@type\": \"@id\"\n        },\n        \"lists\": {\n          \"@id\": \"gdocs:DocumentTab.lists\",\n          \"@container\": \"@index\"\n        },\n        \"namedRanges\": {\n          \"@id\": \"gdocs:DocumentTab.namedRanges\",\n          \"@container\": \"@index\"\n        },\n        \"inlineObjects\": {\n          \"@id\": \"gdocs:DocumentTab.inlineObjects\",\n          \"@container\": \"@index\"\n        },\n        \"positionedObjects\": {\n          \"@id\": \"gdocs:DocumentTab.positionedObjects\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"Body\": {\n      \"@id\": \"gdocs:Body\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"gdocs:Body.content\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"\
  StructuralElement\": {\n      \"@id\": \"gdocs:StructuralElement\",\n      \"@context\": {\n        \"startIndex\": {\n          \"@id\": \"gdocs:StructuralElement.startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gdocs:StructuralElement.endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"paragraph\": {\n          \"@id\": \"gdocs:StructuralElement.paragraph\",\n          \"@type\": \"@id\"\n        },\n        \"sectionBreak\": {\n          \"@id\": \"gdocs:StructuralElement.sectionBreak\",\n          \"@type\": \"@id\"\n        },\n        \"table\": {\n          \"@id\": \"gdocs:StructuralElement.table\",\n          \"@type\": \"@id\"\n        },\n        \"tableOfContents\": {\n          \"@id\": \"gdocs:StructuralElement.tableOfContents\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Paragraph\": {\n      \"@id\": \"gdocs:Paragraph\",\n      \"@context\": {\n        \"elements\"\
  : {\n          \"@id\": \"gdocs:Paragraph.elements\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"paragraphStyle\": {\n          \"@id\": \"gdocs:Paragraph.paragraphStyle\",\n          \"@type\": \"@id\"\n        },\n        \"bullet\": {\n          \"@id\": \"gdocs:Paragraph.bullet\",\n          \"@type\": \"@id\"\n        },\n        \"positionedObjectIds\": {\n          \"@id\": \"gdocs:Paragraph.positionedObjectIds\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"ParagraphElement\": {\n      \"@id\": \"gdocs:ParagraphElement\",\n      \"@context\": {\n        \"startIndex\": {\n          \"@id\": \"gdocs:ParagraphElement.startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gdocs:ParagraphElement.endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"textRun\": {\n          \"@id\": \"gdocs:ParagraphElement.textRun\",\n          \"@type\"\
  : \"@id\"\n        },\n        \"autoText\": {\n          \"@id\": \"gdocs:ParagraphElement.autoText\",\n          \"@type\": \"@id\"\n        },\n        \"pageBreak\": {\n          \"@id\": \"gdocs:ParagraphElement.pageBreak\",\n          \"@type\": \"@id\"\n        },\n        \"columnBreak\": {\n          \"@id\": \"gdocs:ParagraphElement.columnBreak\",\n          \"@type\": \"@id\"\n        },\n        \"footnoteReference\": {\n          \"@id\": \"gdocs:ParagraphElement.footnoteReference\",\n          \"@type\": \"@id\"\n        },\n        \"horizontalRule\": {\n          \"@id\": \"gdocs:ParagraphElement.horizontalRule\",\n          \"@type\": \"@id\"\n        },\n        \"equation\": {\n          \"@id\": \"gdocs:ParagraphElement.equation\",\n          \"@type\": \"@id\"\n        },\n        \"inlineObjectElement\": {\n          \"@id\": \"gdocs:ParagraphElement.inlineObjectElement\",\n          \"@type\": \"@id\"\n        },\n        \"person\": {\n          \"@id\": \"gdocs:ParagraphElement.person\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"richLink\": {\n          \"@id\": \"gdocs:ParagraphElement.richLink\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TextRun\": {\n      \"@id\": \"gdocs:TextRun\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"textStyle\": {\n          \"@id\": \"gdocs:TextRun.textStyle\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TextStyle\": {\n      \"@id\": \"gdocs:TextStyle\",\n      \"@context\": {\n        \"bold\": {\n          \"@id\": \"gdocs:TextStyle.bold\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"italic\": {\n          \"@id\": \"gdocs:TextStyle.italic\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"underline\": {\n          \"@id\": \"gdocs:TextStyle.underline\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"strikethrough\": {\n          \"\
  @id\": \"gdocs:TextStyle.strikethrough\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"smallCaps\": {\n          \"@id\": \"gdocs:TextStyle.smallCaps\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"backgroundColor\": {\n          \"@id\": \"gdocs:TextStyle.backgroundColor\",\n          \"@type\": \"@id\"\n        },\n        \"foregroundColor\": {\n          \"@id\": \"gdocs:TextStyle.foregroundColor\",\n          \"@type\": \"@id\"\n        },\n        \"fontSize\": {\n          \"@id\": \"gdocs:TextStyle.fontSize\",\n          \"@type\": \"@id\"\n        },\n        \"weightedFontFamily\": {\n          \"@id\": \"gdocs:TextStyle.weightedFontFamily\",\n          \"@type\": \"@id\"\n        },\n        \"baselineOffset\": {\n          \"@id\": \"gdocs:TextStyle.baselineOffset\",\n          \"@type\": \"xsd:string\"\n        },\n        \"link\": {\n          \"@id\": \"gdocs:TextStyle.link\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n\
  \    \"ParagraphStyle\": {\n      \"@id\": \"gdocs:ParagraphStyle\",\n      \"@context\": {\n        \"headingId\": {\n          \"@id\": \"gdocs:ParagraphStyle.headingId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"namedStyleType\": {\n          \"@id\": \"gdocs:ParagraphStyle.namedStyleType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alignment\": {\n          \"@id\": \"gdocs:ParagraphStyle.alignment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lineSpacing\": {\n          \"@id\": \"gdocs:ParagraphStyle.lineSpacing\",\n          \"@type\": \"xsd:float\"\n        },\n        \"direction\": {\n          \"@id\": \"gdocs:ParagraphStyle.direction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spaceAbove\": {\n          \"@id\": \"gdocs:ParagraphStyle.spaceAbove\",\n          \"@type\": \"@id\"\n        },\n        \"spaceBelow\": {\n          \"@id\": \"gdocs:ParagraphStyle.spaceBelow\",\n          \"@type\": \"@id\"\n\
  \        },\n        \"indentFirstLine\": {\n          \"@id\": \"gdocs:ParagraphStyle.indentFirstLine\",\n          \"@type\": \"@id\"\n        },\n        \"indentStart\": {\n          \"@id\": \"gdocs:ParagraphStyle.indentStart\",\n          \"@type\": \"@id\"\n        },\n        \"indentEnd\": {\n          \"@id\": \"gdocs:ParagraphStyle.indentEnd\",\n          \"@type\": \"@id\"\n        },\n        \"keepLinesTogether\": {\n          \"@id\": \"gdocs:ParagraphStyle.keepLinesTogether\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"keepWithNext\": {\n          \"@id\": \"gdocs:ParagraphStyle.keepWithNext\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"avoidWidowAndOrphan\": {\n          \"@id\": \"gdocs:ParagraphStyle.avoidWidowAndOrphan\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"pageBreakBefore\": {\n          \"@id\": \"gdocs:ParagraphStyle.pageBreakBefore\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n\
  \    \"DocumentStyle\": {\n      \"@id\": \"gdocs:DocumentStyle\",\n      \"@context\": {\n        \"background\": {\n          \"@id\": \"gdocs:DocumentStyle.background\",\n          \"@type\": \"@id\"\n        },\n        \"defaultHeaderId\": {\n          \"@id\": \"gdocs:DocumentStyle.defaultHeaderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"defaultFooterId\": {\n          \"@id\": \"gdocs:DocumentStyle.defaultFooterId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"useFirstPageHeaderFooter\": {\n          \"@id\": \"gdocs:DocumentStyle.useFirstPageHeaderFooter\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"useEvenPageHeaderFooter\": {\n          \"@id\": \"gdocs:DocumentStyle.useEvenPageHeaderFooter\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"pageNumberStart\": {\n          \"@id\": \"gdocs:DocumentStyle.pageNumberStart\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"marginTop\": {\n          \"\
  @id\": \"gdocs:DocumentStyle.marginTop\",\n          \"@type\": \"@id\"\n        },\n        \"marginBottom\": {\n          \"@id\": \"gdocs:DocumentStyle.marginBottom\",\n          \"@type\": \"@id\"\n        },\n        \"marginRight\": {\n          \"@id\": \"gdocs:DocumentStyle.marginRight\",\n          \"@type\": \"@id\"\n        },\n        \"marginLeft\": {\n          \"@id\": \"gdocs:DocumentStyle.marginLeft\",\n          \"@type\": \"@id\"\n        },\n        \"pageSize\": {\n          \"@id\": \"gdocs:DocumentStyle.pageSize\",\n          \"@type\": \"@id\"\n        },\n        \"flipPageOrientation\": {\n          \"@id\": \"gdocs:DocumentStyle.flipPageOrientation\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Table\": {\n      \"@id\": \"gdocs:Table\",\n      \"@context\": {\n        \"rows\": {\n          \"@id\": \"gdocs:Table.rows\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"columns\": {\n          \"@id\": \"gdocs:Table.columns\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"tableRows\": {\n          \"@id\": \"gdocs:Table.tableRows\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"tableStyle\": {\n          \"@id\": \"gdocs:Table.tableStyle\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TableRow\": {\n      \"@id\": \"gdocs:TableRow\",\n      \"@context\": {\n        \"startIndex\": {\n          \"@id\": \"gdocs:TableRow.startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gdocs:TableRow.endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tableCells\": {\n          \"@id\": \"gdocs:TableRow.tableCells\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"tableRowStyle\": {\n          \"@id\": \"gdocs:TableRow.tableRowStyle\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TableCell\": {\n  \
  \    \"@id\": \"gdocs:TableCell\",\n      \"@context\": {\n        \"startIndex\": {\n          \"@id\": \"gdocs:TableCell.startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gdocs:TableCell.endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"content\": {\n          \"@id\": \"gdocs:TableCell.content\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        },\n        \"tableCellStyle\": {\n          \"@id\": \"gdocs:TableCell.tableCellStyle\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Header\": {\n      \"@id\": \"gdocs:Header\",\n      \"@context\": {\n        \"headerId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"gdocs:Header.content\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Footer\": {\n      \"\
  @id\": \"gdocs:Footer\",\n      \"@context\": {\n        \"footerId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"gdocs:Footer.content\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Footnote\": {\n      \"@id\": \"gdocs:Footnote\",\n      \"@context\": {\n        \"footnoteId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content\": {\n          \"@id\": \"gdocs:Footnote.content\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"InlineObject\": {\n      \"@id\": \"gdocs:InlineObject\",\n      \"@context\": {\n        \"objectId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inlineObjectProperties\": {\n          \"@id\": \"gdocs:InlineObject.inlineObjectProperties\"\
  ,\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"EmbeddedObject\": {\n      \"@id\": \"gdocs:EmbeddedObject\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"gdocs:EmbeddedObject.size\",\n          \"@type\": \"@id\"\n        },\n        \"imageProperties\": {\n          \"@id\": \"gdocs:EmbeddedObject.imageProperties\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ImageProperties\": {\n      \"@id\": \"gdocs:ImageProperties\",\n      \"@context\": {\n        \"contentUri\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"sourceUri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"brightness\":\
  \ {\n          \"@id\": \"gdocs:ImageProperties.brightness\",\n          \"@type\": \"xsd:float\"\n        },\n        \"contrast\": {\n          \"@id\": \"gdocs:ImageProperties.contrast\",\n          \"@type\": \"xsd:float\"\n        },\n        \"transparency\": {\n          \"@id\": \"gdocs:ImageProperties.transparency\",\n          \"@type\": \"xsd:float\"\n        },\n        \"angle\": {\n          \"@id\": \"gdocs:ImageProperties.angle\",\n          \"@type\": \"xsd:float\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"personId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"personProperties\": {\n          \"@id\": \"gdocs:Person.personProperties\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PersonProperties\": {\n      \"@id\": \"gdocs:PersonProperties\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"RichLink\": {\n      \"@id\": \"gdocs:RichLink\",\n      \"@context\": {\n        \"richLinkId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"richLinkProperties\": {\n          \"@id\": \"gdocs:RichLink.richLinkProperties\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"RichLinkProperties\": {\n      \"@id\": \"gdocs:RichLinkProperties\",\n      \"@context\": {\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"mimeType\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Link\": {\n\
  \      \"@id\": \"gdocs:Link\",\n      \"@context\": {\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"xsd:anyURI\"\n        },\n        \"bookmarkId\": {\n          \"@id\": \"gdocs:Link.bookmarkId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"headingId\": {\n          \"@id\": \"gdocs:Link.headingId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tabId\": {\n          \"@id\": \"gdocs:Link.tabId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Dimension\": {\n      \"@id\": \"gdocs:Dimension\",\n      \"@context\": {\n        \"magnitude\": {\n          \"@id\": \"schema:value\",\n          \"@type\": \"xsd:float\"\n        },\n        \"unit\": {\n          \"@id\": \"schema:unitCode\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Size\": {\n      \"@id\": \"gdocs:Size\",\n      \"@context\": {\n        \"height\": {\n          \"@id\": \"schema:height\",\n      \
  \    \"@type\": \"@id\"\n        },\n        \"width\": {\n          \"@id\": \"schema:width\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"OptionalColor\": {\n      \"@id\": \"gdocs:OptionalColor\",\n      \"@context\": {\n        \"color\": {\n          \"@id\": \"gdocs:OptionalColor.color\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Color\": {\n      \"@id\": \"gdocs:Color\",\n      \"@context\": {\n        \"rgbColor\": {\n          \"@id\": \"gdocs:Color.rgbColor\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"RgbColor\": {\n      \"@id\": \"gdocs:RgbColor\",\n      \"@context\": {\n        \"red\": {\n          \"@id\": \"gdocs:RgbColor.red\",\n          \"@type\": \"xsd:float\"\n        },\n        \"green\": {\n          \"@id\": \"gdocs:RgbColor.green\",\n          \"@type\": \"xsd:float\"\n        },\n        \"blue\": {\n          \"@id\": \"gdocs:RgbColor.blue\",\n          \"@type\": \"xsd:float\"\n    \
  \    }\n      }\n    },\n\n    \"NamedRange\": {\n      \"@id\": \"gdocs:NamedRange\",\n      \"@context\": {\n        \"namedRangeId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ranges\": {\n          \"@id\": \"gdocs:NamedRange.ranges\",\n          \"@type\": \"@id\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Range\": {\n      \"@id\": \"gdocs:Range\",\n      \"@context\": {\n        \"segmentId\": {\n          \"@id\": \"gdocs:Range.segmentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startIndex\": {\n          \"@id\": \"gdocs:Range.startIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endIndex\": {\n          \"@id\": \"gdocs:Range.endIndex\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tabId\": {\n          \"@id\": \"gdocs:Range.tabId\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"List\": {\n      \"@id\": \"gdocs:List\",\n      \"@context\": {\n        \"listProperties\": {\n          \"@id\": \"gdocs:List.listProperties\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Bullet\": {\n      \"@id\": \"gdocs:Bullet\",\n      \"@context\": {\n        \"listId\": {\n          \"@id\": \"gdocs:Bullet.listId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nestingLevel\": {\n          \"@id\": \"gdocs:Bullet.nestingLevel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"textStyle\": {\n          \"@id\": \"gdocs:Bullet.textStyle\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"WeightedFontFamily\": {\n      \"@id\": \"gdocs:WeightedFontFamily\",\n      \"@context\": {\n        \"fontFamily\": {\n          \"@id\": \"gdocs:WeightedFontFamily.fontFamily\",\n          \"@type\": \"xsd:string\"\n        },\n        \"weight\": {\n\
  \          \"@id\": \"gdocs:WeightedFontFamily.weight\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-docs/refs/heads/main/json-ld/google-docs-context.jsonld
tags:
- Collaboration
- Documents
- Google Workspace
- Productivity
- Word Processing
- JSON-LD
- Linked Data
- Semantic Web
---
