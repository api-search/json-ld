---
api_specs:
- filename: sharepoint-rest-openapi.json
  format: json
  label: SharePoint REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://example.com/sharepoint-rest-openapi.json
- filename: graph-sharepoint-openapi.json
  format: json
  label: Microsoft Graph API (SharePoint)
  slug: graph-api-sharepoint
  spec_type: OpenAPI
  url: https://example.com/graph-sharepoint-openapi.json
class_count: 11
classes:
- File
- FileCollection
- List
- ListCollection
- ListCreateRequest
- ListItem
- ListItemCollection
- ListItemCreateRequest
- SearchResult
- UserProfile
- Web
context_file: json-ld/sharepoint-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/json-ld/sharepoint-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sharepoint from Microsoft SharePoint.
layout: jsonld
name: Sharepoint Context
namespaces:
- prefix: sp
  uri: https://learn.microsoft.com/en-us/sharepoint/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AccountName
  type: string
- container: ''
  name: AllowContentTypes
  type: boolean
- container: ''
  name: AuthorId
  type: integer
- container: ''
  name: BaseTemplate
  type: integer
- container: ''
  name: CheckOutType
  type: integer
- container: ''
  name: ContentTypesEnabled
  type: boolean
- container: ''
  name: Created
  type: dateTime
- container: ''
  name: Department
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: EditorId
  type: integer
- container: ''
  name: Email
  type: string
- container: ''
  name: EnableVersioning
  type: boolean
- container: ''
  name: Hidden
  type: boolean
- container: ''
  name: Id
  type: string
- container: ''
  name: ItemCount
  type: integer
- container: ''
  name: Language
  type: integer
- container: ''
  name: LastItemModifiedDate
  type: dateTime
- container: ''
  name: Length
  type: integer
- container: ''
  name: MajorVersion
  type: integer
- container: ''
  name: MinorVersion
  type: integer
- container: ''
  name: Modified
  type: dateTime
- container: ''
  name: Name
  type: string
- container: ''
  name: PersonalUrl
  type: string
- container: ''
  name: PictureUrl
  type: string
- container: ''
  name: PrimaryQueryResult
  type: reference
- container: ''
  name: ServerRelativeUrl
  type: string
- container: ''
  name: TimeCreated
  type: dateTime
- container: ''
  name: TimeLastModified
  type: dateTime
- container: ''
  name: Title
  type: string
- container: ''
  name: UniqueId
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: WebTemplate
  type: string
- container: ''
  name: __metadata
  type: reference
- container: set
  name: value
  type: string
property_count: 35
provider_name: Microsoft SharePoint
provider_slug: sharepoint
slug: sharepoint-context
source_filename: sharepoint-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sp\": \"https://learn.microsoft.com/en-us/sharepoint/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"File\": \"sp:File\",\n    \"FileCollection\": \"sp:FileCollection\",\n    \"List\": \"sp:List\",\n    \"ListCollection\": \"sp:ListCollection\",\n    \"ListCreateRequest\": \"sp:ListCreateRequest\",\n    \"ListItem\": \"sp:ListItem\",\n    \"ListItemCollection\": \"sp:ListItemCollection\",\n    \"ListItemCreateRequest\": \"sp:ListItemCreateRequest\",\n    \"SearchResult\": \"sp:SearchResult\",\n    \"UserProfile\": \"sp:UserProfile\",\n    \"Web\": \"sp:Web\",\n    \"AccountName\": {\n      \"@id\": \"sp:AccountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowContentTypes\": {\n      \"@id\": \"sp:AllowContentTypes\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AuthorId\": {\n      \"@id\": \"sp:AuthorId\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"BaseTemplate\": {\n      \"@id\": \"sp:BaseTemplate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CheckOutType\": {\n      \"@id\": \"sp:CheckOutType\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ContentTypesEnabled\": {\n      \"@id\": \"sp:ContentTypesEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Created\": {\n      \"@id\": \"sp:Created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Department\": {\n      \"@id\": \"sp:Department\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"sp:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayName\": {\n      \"@id\": \"sp:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EditorId\": {\n      \"@id\": \"sp:EditorId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Email\": {\n      \"@id\": \"sp:Email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableVersioning\": {\n      \"@id\": \"sp:EnableVersioning\",\n      \"@type\"\
  : \"xsd:boolean\"\n    },\n    \"Hidden\": {\n      \"@id\": \"sp:Hidden\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Id\": {\n      \"@id\": \"sp:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemCount\": {\n      \"@id\": \"sp:ItemCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Language\": {\n      \"@id\": \"sp:Language\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LastItemModifiedDate\": {\n      \"@id\": \"sp:LastItemModifiedDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Length\": {\n      \"@id\": \"sp:Length\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MajorVersion\": {\n      \"@id\": \"sp:MajorVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MinorVersion\": {\n      \"@id\": \"sp:MinorVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Modified\": {\n      \"@id\": \"sp:Modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Name\": {\n      \"@id\": \"sp:Name\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"PersonalUrl\": {\n      \"@id\": \"sp:PersonalUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PictureUrl\": {\n      \"@id\": \"sp:PictureUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrimaryQueryResult\": {\n      \"@id\": \"sp:PrimaryQueryResult\",\n      \"@type\": \"@id\"\n    },\n    \"ServerRelativeUrl\": {\n      \"@id\": \"sp:ServerRelativeUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeCreated\": {\n      \"@id\": \"sp:TimeCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"TimeLastModified\": {\n      \"@id\": \"sp:TimeLastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Title\": {\n      \"@id\": \"sp:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UniqueId\": {\n      \"@id\": \"sp:UniqueId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"sp:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WebTemplate\": {\n      \"@id\": \"sp:WebTemplate\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"__metadata\": {\n      \"@id\": \"sp:__metadata\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"sp:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/json-ld/sharepoint-context.jsonld
tags:
- Collaboration
- Document Management
- Enterprise Content Management
- Intranet
- Microsoft
- JSON-LD
- Linked Data
- Semantic Web
---
