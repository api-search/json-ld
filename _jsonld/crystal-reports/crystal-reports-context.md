---
class_count: 22
classes:
- DataSource
- Error
- FileFormatVersion
- Formula
- GrandTotalCollection
- GroupCondition
- InfostoreEntry
- InfostoreEntryList
- InstanceForm
- LogonRequest
- LogonResponse
- ODataFieldValue
- ODataRowCollection
- ODataServiceDocument
- ReportInstance
- ReportParameter
- ReportStructure
- ReportSummary
- RunningTotal
- Subreport
- SummaryField
- UsedField
context_file: json-ld/crystal-reports-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/json-ld/crystal-reports-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Crystal Reports from Crystal Reports.
layout: jsonld
name: Crystal Reports Context
namespaces:
- prefix: cr
  uri: https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ConnectionInfo
  type: string
- container: set
  name: EntitySets
  type: string
- container: ''
  name: SuppressData
  type: boolean
- container: ''
  name: __count
  type: string
- container: ''
  name: __next
  type: string
- container: ''
  name: auth
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: comments
  type: string
- container: ''
  name: cuid
  type: string
- container: ''
  name: databaseName
  type: string
- container: set
  name: datasources
  type: string
- container: ''
  name: default_value
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: direction
  type: string
- container: ''
  name: edit_uri
  type: string
- container: set
  name: entries
  type: string
- container: ''
  name: error_code
  type: integer
- container: ''
  name: export_uri
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: file_format_version
  type: string
- container: set
  name: formulas
  type: string
- container: set
  name: groupconditions
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: keywords
  type: string
- container: ''
  name: last_data_refresh_date
  type: dateTime
- container: ''
  name: logonToken
  type: string
- container: ''
  name: major_version
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: minor_version
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: operation
  type: string
- container: set
  name: parameters
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: prompt
  type: string
- container: ''
  name: report_name
  type: string
- container: ''
  name: report_title
  type: string
- container: ''
  name: required
  type: boolean
- container: ''
  name: reset_condition
  type: string
- container: ''
  name: resource
  type: string
- container: set
  name: runningtotals
  type: string
- container: ''
  name: serverName
  type: string
- container: ''
  name: service_uri
  type: string
- container: ''
  name: subject
  type: string
- container: set
  name: subreports
  type: string
- container: set
  name: summary
  type: string
- container: ''
  name: table
  type: string
- container: set
  name: tables
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: uri
  type: string
- container: set
  name: usedfields
  type: string
- container: ''
  name: userName
  type: string
- container: set
  name: value
  type: string
property_count: 54
provider_name: Crystal Reports
provider_slug: crystal-reports
slug: crystal-reports-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cr\": \"https://help.sap.com/docs/SAP_CRYSTAL_REPORTS/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConnectionInfo\": {\n      \"@id\": \"cr:ConnectionInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataSource\": \"cr:DataSource\",\n    \"Error\": \"cr:Error\",\n    \"FileFormatVersion\": \"cr:FileFormatVersion\",\n    \"Formula\": \"cr:Formula\",\n    \"GrandTotalCollection\": \"cr:GrandTotalCollection\",\n    \"GroupCondition\": \"cr:GroupCondition\",\n    \"InfostoreEntry\": \"cr:InfostoreEntry\",\n    \"InfostoreEntryList\": \"cr:InfostoreEntryList\",\n    \"InstanceForm\": \"cr:InstanceForm\",\n    \"LogonRequest\": \"cr:LogonRequest\",\n    \"LogonResponse\": \"cr:LogonResponse\",\n    \"ODataFieldValue\": \"cr:ODataFieldValue\",\n    \"ODataRowCollection\": \"cr:ODataRowCollection\",\n    \"ODataServiceDocument\": \"cr:ODataServiceDocument\"\
  ,\n    \"ReportInstance\": \"cr:ReportInstance\",\n    \"ReportParameter\": \"cr:ReportParameter\",\n    \"ReportStructure\": \"cr:ReportStructure\",\n    \"ReportSummary\": \"cr:ReportSummary\",\n    \"RunningTotal\": \"cr:RunningTotal\",\n    \"Subreport\": \"cr:Subreport\",\n    \"SummaryField\": \"cr:SummaryField\",\n    \"UsedField\": \"cr:UsedField\",\n    \"EntitySets\": {\n      \"@id\": \"cr:EntitySets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SuppressData\": {\n      \"@id\": \"cr:SuppressData\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"__count\": {\n      \"@id\": \"cr:__count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"__next\": {\n      \"@id\": \"cr:__next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"auth\": {\n      \"@id\": \"cr:auth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"cr:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comments\": {\n      \"@id\": \"cr:comments\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"cuid\": {\n      \"@id\": \"cr:cuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseName\": {\n      \"@id\": \"cr:databaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datasources\": {\n      \"@id\": \"cr:datasources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"default_value\": {\n      \"@id\": \"cr:default_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"cr:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"direction\": {\n      \"@id\": \"cr:direction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edit_uri\": {\n      \"@id\": \"cr:edit_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"cr:entries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error_code\": {\n      \"@id\": \"cr:error_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"export_uri\"\
  : {\n      \"@id\": \"cr:export_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"cr:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"cr:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file_format_version\": {\n      \"@id\": \"cr:file_format_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formulas\": {\n      \"@id\": \"cr:formulas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupconditions\": {\n      \"@id\": \"cr:groupconditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"cr:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"keywords\": {\n      \"@id\": \"cr:keywords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"last_data_refresh_date\": {\n      \"@id\": \"cr:last_data_refresh_date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logonToken\": {\n      \"@id\": \"cr:logonToken\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"major_version\": {\n      \"@id\": \"cr:major_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"cr:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minor_version\": {\n      \"@id\": \"cr:minor_version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"cr:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"cr:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"cr:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"cr:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt\": {\n      \"@id\": \"cr:prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"report_name\": {\n      \"@id\": \"cr:report_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"report_title\": {\n      \"@id\": \"cr:report_title\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"cr:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reset_condition\": {\n      \"@id\": \"cr:reset_condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"cr:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runningtotals\": {\n      \"@id\": \"cr:runningtotals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverName\": {\n      \"@id\": \"cr:serverName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service_uri\": {\n      \"@id\": \"cr:service_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"cr:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subreports\": {\n      \"@id\": \"cr:subreports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"cr:summary\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"table\": {\n      \"@id\": \"cr:table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tables\": {\n      \"@id\": \"cr:tables\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"cr:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"cr:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"cr:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usedfields\": {\n      \"@id\": \"cr:usedfields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"cr:userName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"cr:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/crystal-reports/refs/heads/main/json-ld/crystal-reports-context.jsonld
tags:
- Business Intelligence
- Crystal Reports
- Data Analytics
- Enterprise Software
- Reporting
- SAP
- JSON-LD
- Linked Data
- Semantic Web
---
