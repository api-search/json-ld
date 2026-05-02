---
api_specs:
- filename: looker-studio-api-openapi.yml
  format: yaml
  label: Looker Studio API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-api-openapi.yml
- filename: looker-studio-linking-api-openapi.yml
  format: yaml
  label: Looker Studio Linking API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-linking-api-openapi.yml
- filename: looker-studio-embedding-api-openapi.yml
  format: yaml
  label: Looker Studio Embedding API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-embedding-api-openapi.yml
- filename: looker-studio-community-connector-api-openapi.yml
  format: yaml
  label: Looker Studio Community Connector API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-community-connector-api-openapi.yml
- filename: looker-studio-community-visualization-api-openapi.yml
  format: yaml
  label: Looker Studio Community Visualization API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/openapi/looker-studio-community-visualization-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/looker-studio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/json-ld/looker-studio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Looker Studio from Looker Studio.
layout: jsonld
name: Looker Studio Context
namespaces:
- prefix: ls
  uri: https://developers.google.com/looker-studio/ns#
- prefix: goog
  uri: https://cloud.google.com/ns#
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: vcard
  uri: http://www.w3.org/2006/vcard/ns#
- prefix: prov
  uri: http://www.w3.org/ns/prov#
properties:
- container: ''
  name: Asset
  type: schema:CreativeWork
- container: ''
  name: Report
  type: schema:Report
- container: ''
  name: DataSource
  type: dcat:Dataset
- container: ''
  name: Connector
  type: schema:SoftwareApplication
- container: ''
  name: Visualization
  type: schema:SoftwareApplication
- container: ''
  name: Permissions
  type: schema:DigitalDocumentPermission
- container: ''
  name: Member
  type: schema:Person
- container: ''
  name: name
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: owner
  type: reference
- container: ''
  name: creator
  type: reference
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
- container: ''
  name: lastViewByMeTime
  type: dateTime
- container: ''
  name: updateByMeTime
  type: dateTime
- container: ''
  name: trashed
  type: boolean
- container: ''
  name: assetType
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: connectorType
  type: string
- container: ''
  name: authType
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: conceptType
  type: string
- container: ''
  name: semanticType
  type: string
- container: list
  name: fields
  type: ''
- container: list
  name: pages
  type: ''
- container: list
  name: dataSources
  type: ''
- container: list
  name: components
  type: ''
- container: list
  name: configParams
  type: ''
- container: ''
  name: logoUrl
  type: reference
- container: ''
  name: organization
  type: string
- container: ''
  name: company
  type: string
- container: ''
  name: companyUrl
  type: reference
- container: ''
  name: supportUrl
  type: reference
- container: ''
  name: reportId
  type: string
- container: ''
  name: pageId
  type: string
- container: ''
  name: embedUrl
  type: reference
- container: ''
  name: email
  type: string
- container: ''
  name: url
  type: reference
property_count: 40
provider_name: Looker Studio
provider_slug: looker-studio
slug: looker-studio-context
source_filename: looker-studio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ls\": \"https://developers.google.com/looker-studio/ns#\",\n    \"goog\": \"https://cloud.google.com/ns#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"vcard\": \"http://www.w3.org/2006/vcard/ns#\",\n    \"prov\": \"http://www.w3.org/ns/prov#\",\n\n    \"Asset\": {\n      \"@id\": \"ls:Asset\",\n      \"@type\": \"schema:CreativeWork\"\n    },\n    \"Report\": {\n      \"@id\": \"ls:Report\",\n      \"@type\": \"schema:Report\"\n    },\n    \"DataSource\": {\n      \"@id\": \"ls:DataSource\",\n      \"@type\": \"dcat:Dataset\"\n    },\n    \"Connector\": {\n      \"@id\": \"ls:Connector\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Visualization\": {\n      \"@id\": \"ls:Visualization\",\n      \"@type\": \"schema:SoftwareApplication\"\n \
  \   },\n    \"Permissions\": {\n      \"@id\": \"ls:Permissions\",\n      \"@type\": \"schema:DigitalDocumentPermission\"\n    },\n    \"Member\": {\n      \"@id\": \"ls:Member\",\n      \"@type\": \"schema:Person\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"schema:accountablePerson\",\n      \"@type\": \"@id\"\n    },\n    \"creator\": {\n      \"@id\": \"schema:creator\",\n      \"@type\": \"@id\"\n    },\n    \"createTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastViewByMeTime\": {\n      \"@id\": \"ls:lastViewByMeTime\",\n      \"@type\"\
  : \"xsd:dateTime\"\n    },\n    \"updateByMeTime\": {\n      \"@id\": \"ls:updateByMeTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"trashed\": {\n      \"@id\": \"ls:trashed\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"assetType\": {\n      \"@id\": \"ls:assetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"schema:roleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"ls:etag\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"connectorType\": {\n      \"@id\": \"ls:connectorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authType\": {\n      \"@id\": \"ls:authType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"ls:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conceptType\": {\n      \"@id\": \"ls:conceptType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"semanticType\": {\n      \"@id\": \"ls:semanticType\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"fields\": {\n      \"@id\": \"ls:fields\",\n      \"@container\": \"@list\"\n    },\n\n    \"pages\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@list\"\n    },\n    \"dataSources\": {\n      \"@id\": \"ls:dataSources\",\n      \"@container\": \"@list\"\n    },\n    \"components\": {\n      \"@id\": \"schema:hasPart\",\n      \"@container\": \"@list\"\n    },\n    \"configParams\": {\n      \"@id\": \"ls:configParams\",\n      \"@container\": \"@list\"\n    },\n\n    \"logoUrl\": {\n      \"@id\": \"schema:logo\",\n      \"@type\": \"@id\"\n    },\n    \"organization\": {\n      \"@id\": \"schema:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"company\": {\n      \"@id\": \"schema:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"supportUrl\": {\n      \"@id\": \"schema:mainEntityOfPage\",\n      \"@type\": \"@id\"\n    },\n\n    \"reportId\"\
  : {\n      \"@id\": \"ls:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageId\": {\n      \"@id\": \"ls:pageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"embedUrl\": {\n      \"@id\": \"schema:embedUrl\",\n      \"@type\": \"@id\"\n    },\n\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/looker-studio/refs/heads/main/json-ld/looker-studio-context.jsonld
tags:
- Analytics
- Business Intelligence
- Dashboards
- Data Visualization
- Google
- Reports
- JSON-LD
- Linked Data
- Semantic Web
---
