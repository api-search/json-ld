---
api_specs:
- filename: openapi.json
  format: json
  label: Microsoft Access Database Engine API
  slug: ''
  spec_type: OpenAPI
  url: https://example.com/openapi.json
class_count: 0
classes: []
context_file: json-ld/microsoft-access-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-access/refs/heads/main/json-ld/microsoft-access-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Access from Microsoft Access.
layout: jsonld
name: Microsoft Access Context
namespaces:
- prefix: access
  uri: https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties:
- container: ''
  name: Database
  type: reference
- container: ''
  name: TableDef
  type: reference
- container: ''
  name: Field
  type: reference
- container: ''
  name: Index
  type: reference
- container: ''
  name: QueryDef
  type: reference
- container: ''
  name: Relation
  type: reference
- container: ''
  name: Recordset
  type: reference
- container: ''
  name: Container
  type: reference
- container: ''
  name: Document
  type: reference
property_count: 9
provider_name: Microsoft Access
provider_slug: microsoft-access
slug: microsoft-access-context
source_filename: microsoft-access-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"access\": \"https://learn.microsoft.com/en-us/office/client-developer/access/desktop-database-reference/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n\n    \"Database\": {\n      \"@id\": \"access:database-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"version\": {\n          \"@id\": \"schema:softwareVersion\"\n        },\n        \"collatingOrder\": {\n          \"@id\": \"access:database-collatingorder-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"connect\": {\n          \"@id\": \"access:database-connect-property-dao\"\n        },\n        \"queryTimeout\": {\n          \"@id\": \"access:database-querytimeout-property-dao\",\n \
  \         \"@type\": \"xsd:integer\"\n        },\n        \"recordsAffected\": {\n          \"@id\": \"access:database-recordsaffected-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updatable\": {\n          \"@id\": \"access:database-updatable-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"transactions\": {\n          \"@id\": \"access:database-transactions-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"designMasterID\": {\n          \"@id\": \"access:database-designmasterid-property-dao\"\n        },\n        \"replicaID\": {\n          \"@id\": \"access:database-replicaid-property-dao\"\n        },\n        \"tableDefs\": {\n          \"@id\": \"access:database-tabledefs-property-dao\",\n          \"@container\": \"@set\"\n        },\n        \"queryDefs\": {\n          \"@id\": \"access:database-querydefs-property-dao\",\n          \"@container\": \"@set\"\n        },\n        \"relations\": {\n\
  \          \"@id\": \"access:database-relations-property-dao\",\n          \"@container\": \"@set\"\n        },\n        \"containers\": {\n          \"@id\": \"access:database-containers-property-dao\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TableDef\": {\n      \"@id\": \"access:tabledef-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"attributes\": {\n          \"@id\": \"access:tabledef-attributes-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"connect\": {\n          \"@id\": \"access:tabledef-connect-property-dao\"\n        },\n        \"sourceTableName\": {\n          \"@id\": \"access:tabledef-sourcetablename-property-dao\"\
  \n        },\n        \"recordCount\": {\n          \"@id\": \"access:tabledef-recordcount-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"updatable\": {\n          \"@id\": \"access:tabledef-updatable-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"validationRule\": {\n          \"@id\": \"access:tabledef-validationrule-property-dao\"\n        },\n        \"validationText\": {\n          \"@id\": \"access:tabledef-validationtext-property-dao\"\n        },\n        \"conflictTable\": {\n          \"@id\": \"access:tabledef-conflicttable-property-dao\"\n        },\n        \"replicaFilter\": {\n          \"@id\": \"access:tabledef-replicafilter-property-dao\"\n        },\n        \"fields\": {\n          \"@id\": \"access:tabledef-fields-property-dao\",\n          \"@container\": \"@set\"\n        },\n        \"indexes\": {\n          \"@id\": \"access:tabledef-indexes-property-dao\",\n          \"@container\": \"@set\"\n       \
  \ }\n      }\n    },\n\n    \"Field\": {\n      \"@id\": \"access:field-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"type\": {\n          \"@id\": \"access:field-type-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"size\": {\n          \"@id\": \"access:field-size-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": {\n          \"@id\": \"access:field-attributes-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ordinalPosition\": {\n          \"@id\": \"access:field-ordinalposition-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"required\": {\n          \"@id\": \"access:field-required-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"allowZeroLength\": {\n          \"@id\": \"access:field-allowzerolength-property-dao\",\n          \"@type\"\
  : \"xsd:boolean\"\n        },\n        \"defaultValue\": {\n          \"@id\": \"access:field-defaultvalue-property-dao\"\n        },\n        \"validationRule\": {\n          \"@id\": \"access:field-validationrule-property-dao\"\n        },\n        \"validationText\": {\n          \"@id\": \"access:field-validationtext-property-dao\"\n        },\n        \"validateOnSet\": {\n          \"@id\": \"access:field-validateonset-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"collatingOrder\": {\n          \"@id\": \"access:field-collatingorder-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"foreignName\": {\n          \"@id\": \"access:field-foreignname-property-dao\"\n        },\n        \"sourceField\": {\n          \"@id\": \"access:field-sourcefield-property-dao\"\n        },\n        \"sourceTable\": {\n          \"@id\": \"access:field-sourcetable-property-dao\"\n        },\n        \"dataUpdatable\": {\n          \"@id\": \"\
  access:field-dataupdatable-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"expression\": {\n          \"@id\": \"schema:mathExpression\"\n        }\n      }\n    },\n\n    \"Index\": {\n      \"@id\": \"access:index-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"primary\": {\n          \"@id\": \"access:index-primary-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"unique\": {\n          \"@id\": \"access:index-unique-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"required\": {\n          \"@id\": \"access:index-required-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"ignoreNulls\": {\n          \"@id\": \"access:index-ignorenulls-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"foreign\": {\n          \"@id\": \"access:index-foreign-property-dao\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"clustered\": {\n          \"@id\": \"access:index-clustered-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"distinctCount\": {\n          \"@id\": \"access:index-distinctcount-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"fields\": {\n          \"@id\": \"access:index-fields-property-dao\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"QueryDef\": {\n      \"@id\": \"access:querydef-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sql\": {\n          \"@id\": \"access:querydef-sql-property-dao\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n  \
  \      \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatable\": {\n          \"@id\": \"access:querydef-updatable-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"connect\": {\n          \"@id\": \"access:querydef-connect-property-dao\"\n        },\n        \"returnsRecords\": {\n          \"@id\": \"access:querydef-returnsrecords-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Relation\": {\n      \"@id\": \"access:relation-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"table\": {\n          \"@id\": \"access:relation-table-property-dao\"\n        },\n        \"foreignTable\": {\n          \"@id\": \"access:relation-foreigntable-property-dao\"\n        },\n        \"attributes\": {\n          \"@id\": \"access:relation-attributes-property-dao\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"fields\": {\n          \"@id\": \"access:relation-fields-property-dao\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Recordset\": {\n      \"@id\": \"access:recordset-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"recordCount\": {\n          \"@id\": \"access:recordset-recordcount-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bof\": {\n          \"@id\": \"access:recordset-bof-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"eof\": {\n          \"@id\": \"access:recordset-eof-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"updatable\": {\n          \"@id\": \"access:recordset-updatable-property-dao\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"bookmarkable\": {\n          \"@id\": \"access:recordset-bookmarkable-property-dao\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"fields\": {\n          \"@id\": \"access:recordset-fields-property-dao\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Container\": {\n      \"@id\": \"access:container-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\"\n        },\n        \"permissions\": {\n          \"@id\": \"access:container-permissions-property-dao\",\n          \"@type\": \"xsd:integer\"\n        },\n\
  \        \"documents\": {\n          \"@id\": \"access:container-documents-property-dao\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Document\": {\n      \"@id\": \"access:document-object-dao\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdated\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-access/refs/heads/main/json-ld/microsoft-access-context.jsonld
tags:
- Access Database
- Database
- Desktop Database
- Microsoft
- Relational Database
- JSON-LD
- Linked Data
- Semantic Web
---
