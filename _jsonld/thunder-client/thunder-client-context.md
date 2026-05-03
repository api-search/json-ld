---
class_count: 14
classes:
- name
- description
- url
- version
- created
- modified
- dateExported
- SoftwareApplication
- programmingLanguage
- softwareVersion
- downloadUrl
- codeRepository
- applicationCategory
- operatingSystem
context_file: json-ld/thunder-client-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-ld/thunder-client-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thunder Client from Thunder Client.
layout: jsonld
name: Thunder Client Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: tc
  uri: https://www.thunderclient.com/vocab#
properties:
- container: ''
  name: ThunderCollection
  type: ''
- container: ''
  name: ThunderRequest
  type: ''
- container: ''
  name: ThunderFolder
  type: ''
- container: ''
  name: ThunderEnvironment
  type: ''
- container: ''
  name: TestAssertion
  type: ''
- container: ''
  name: method
  type: ''
- container: list
  name: headers
  type: ''
- container: list
  name: params
  type: ''
- container: ''
  name: body
  type: reference
- container: ''
  name: auth
  type: reference
- container: list
  name: tests
  type: ''
- container: list
  name: preScripts
  type: ''
- container: list
  name: postScripts
  type: ''
- container: list
  name: requests
  type: ''
- container: list
  name: folders
  type: ''
- container: list
  name: data
  type: ''
- container: ''
  name: assertionType
  type: ''
- container: ''
  name: assertionAction
  type: ''
- container: ''
  name: assertionValue
  type: ''
- container: ''
  name: fieldPath
  type: ''
- container: ''
  name: isSecret
  type: boolean
- container: ''
  name: isDisabled
  type: boolean
- container: ''
  name: sortNum
  type: decimal
- container: ''
  name: collectionId
  type: reference
- container: ''
  name: folderId
  type: reference
- container: ''
  name: authType
  type: ''
- container: ''
  name: bodyType
  type: ''
property_count: 27
provider_name: Thunder Client
provider_slug: thunder-client
slug: thunder-client-context
source_filename: thunder-client-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://www.thunderclient.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"tc\": \"https://www.thunderclient.com/vocab#\",\n\n    \"ThunderCollection\": {\n      \"@id\": \"tc:ThunderCollection\",\n      \"rdfs:comment\": \"A Thunder Client collection grouping related API requests\"\n    },\n    \"ThunderRequest\": {\n      \"@id\": \"tc:ThunderRequest\",\n      \"rdfs:comment\": \"A single HTTP or GraphQL API request definition\"\n    },\n    \"ThunderFolder\": {\n      \"@id\": \"tc:ThunderFolder\",\n      \"rdfs:comment\": \"A folder organizing requests within a collection\"\n    },\n    \"ThunderEnvironment\": {\n      \"@id\": \"tc:ThunderEnvironment\",\n      \"rdfs:comment\": \"A set of key-value variables for request parameterization\"\n    },\n    \"TestAssertion\": {\n      \"@id\": \"tc:TestAssertion\"\
  ,\n      \"rdfs:comment\": \"A scriptless test assertion on an API response\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\",\n    \"dateExported\": \"schema:datePublished\",\n\n    \"method\": {\n      \"@id\": \"tc:httpMethod\",\n      \"rdfs:comment\": \"HTTP method (GET, POST, PUT, PATCH, DELETE, etc.)\"\n    },\n    \"headers\": {\n      \"@id\": \"tc:hasHeaders\",\n      \"@container\": \"@list\"\n    },\n    \"params\": {\n      \"@id\": \"tc:hasQueryParams\",\n      \"@container\": \"@list\"\n    },\n    \"body\": {\n      \"@id\": \"tc:hasBody\",\n      \"@type\": \"@id\"\n    },\n    \"auth\": {\n      \"@id\": \"tc:hasAuth\",\n      \"@type\": \"@id\"\n    },\n    \"tests\": {\n      \"@id\": \"tc:hasTests\",\n      \"@container\": \"@list\"\n    },\n    \"preScripts\": {\n      \"@id\"\
  : \"tc:hasPreScripts\",\n      \"@container\": \"@list\"\n    },\n    \"postScripts\": {\n      \"@id\": \"tc:hasPostScripts\",\n      \"@container\": \"@list\"\n    },\n    \"requests\": {\n      \"@id\": \"tc:hasRequests\",\n      \"@container\": \"@list\"\n    },\n    \"folders\": {\n      \"@id\": \"tc:hasFolders\",\n      \"@container\": \"@list\"\n    },\n    \"data\": {\n      \"@id\": \"tc:hasVariables\",\n      \"@container\": \"@list\"\n    },\n\n    \"assertionType\": {\n      \"@id\": \"tc:assertionType\",\n      \"rdfs:comment\": \"Assertion target: status | json | header | text | ms | size\"\n    },\n    \"assertionAction\": {\n      \"@id\": \"tc:assertionAction\",\n      \"rdfs:comment\": \"Comparison operator for an assertion\"\n    },\n    \"assertionValue\": {\n      \"@id\": \"tc:assertionValue\"\n    },\n    \"fieldPath\": {\n      \"@id\": \"tc:fieldPath\",\n      \"rdfs:comment\": \"JSON path or header name for assertion targeting\"\n    },\n    \"isSecret\": {\n\
  \      \"@id\": \"tc:isSecret\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDisabled\": {\n      \"@id\": \"tc:isDisabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"sortNum\": {\n      \"@id\": \"tc:sortOrder\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"collectionId\": {\n      \"@id\": \"tc:belongsToCollection\",\n      \"@type\": \"@id\"\n    },\n    \"folderId\": {\n      \"@id\": \"tc:belongsToFolder\",\n      \"@type\": \"@id\"\n    },\n\n    \"authType\": {\n      \"@id\": \"tc:authType\",\n      \"rdfs:comment\": \"Authentication type: none | basic | bearer | oauth2 | apikey\"\n    },\n    \"bodyType\": {\n      \"@id\": \"tc:bodyType\",\n      \"rdfs:comment\": \"Body content type: json | text | xml | formdata | graphql | binary | none\"\n    },\n\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"softwareVersion\": \"schema:softwareVersion\",\n    \"downloadUrl\": \"schema:downloadUrl\"\
  ,\n    \"codeRepository\": \"schema:codeRepository\",\n    \"applicationCategory\": \"schema:applicationCategory\",\n    \"operatingSystem\": \"schema:operatingSystem\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thunder-client/refs/heads/main/json-ld/thunder-client-context.jsonld
tags:
- API Client
- API Testing
- CI/CD
- CLI
- Collections
- GraphQL
- REST Client
- VS Code
- JSON-LD
- Linked Data
- Semantic Web
---
