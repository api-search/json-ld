---
api_specs:
- filename: qlik-sense-enterprise-repository-service-openapi.yml
  format: yaml
  label: Qlik Sense Repository Service
  slug: qlik-sense-repository-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-repository-service-openapi.yml
- filename: qlik-sense-enterprise-proxy-service-openapi.yml
  format: yaml
  label: Qlik Sense Proxy Service
  slug: qlik-sense-proxy-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-proxy-service-openapi.yml
- filename: qlik-sense-enterprise-about-service-openapi.yml
  format: yaml
  label: Qlik Sense About Service
  slug: qlik-sense-about-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-about-service-openapi.yml
- filename: qlik-sense-enterprise-data-connection-openapi.yml
  format: yaml
  label: Qlik Sense Data Connection
  slug: qlik-sense-data-connection
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-data-connection-openapi.yml
- filename: qlik-sense-enterprise-licenses-openapi.yml
  format: yaml
  label: Qlik Sense Licenses
  slug: qlik-sense-licenses
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-licenses-openapi.yml
- filename: qlik-sense-enterprise-odag-service-openapi.yml
  format: yaml
  label: Qlik Sense ODAG
  slug: qlik-sense-odag
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/openapi/qlik-sense-enterprise-odag-service-openapi.yml
class_count: 0
classes: []
context_file: json-ld/qlik-sense-enterprise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/json-ld/qlik-sense-enterprise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Qlik Sense Enterprise from Qlik Sense Enterprise.
layout: jsonld
name: Qlik Sense Enterprise Context
namespaces:
- prefix: qlik
  uri: https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: App
  type: ''
- container: ''
  name: Stream
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: DataConnection
  type: ''
- container: ''
  name: SecurityRule
  type: ''
- container: ''
  name: ReloadTask
  type: ''
- container: ''
  name: Session
  type: ''
- container: ''
  name: Extension
  type: ''
- container: ''
  name: License
  type: ''
- container: ''
  name: ServerNode
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: CustomProperty
  type: ''
property_count: 12
provider_name: Qlik Sense Enterprise
provider_slug: qlik-sense-enterprise
slug: qlik-sense-enterprise-context
source_filename: qlik-sense-enterprise-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"qlik\": \"https://help.qlik.com/en-US/sense-developer/November2025/Subsystems/RepositoryServiceAPI/Content/Sense_RepositoryServiceAPI/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"App\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"schema:Person\"\
  \n        },\n        \"published\": \"schema:isAccessibleForFree\",\n        \"publishTime\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"fileSize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"thumbnail\": \"schema:thumbnailUrl\",\n        \"stream\": \"schema:isPartOf\",\n        \"tags\": \"schema:keywords\",\n        \"savedInProductVersion\": \"schema:softwareVersion\"\n      }\n    },\n\n    \"Stream\": {\n      \"@id\": \"schema:Collection\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"schema:Person\"\
  \n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"userId\": \"schema:identifier\",\n        \"userDirectory\": \"schema:memberOf\",\n        \"roles\": \"schema:hasOccupation\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"inactive\": \"schema:accountablePerson\",\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"DataConnection\": {\n      \"@id\": \"dcat:DataService\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"type\": \"dcterms:type\",\n        \"connectionstring\": \"dcat:endpointURL\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"schema:Person\"\n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"SecurityRule\": {\n      \"@id\": \"schema:DigitalDocumentPermission\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"rule\": \"schema:description\",\n        \"resourceFilter\": \"schema:targetCollection\",\n        \"actions\": \"schema:permissionType\",\n        \"comment\": \"schema:description\",\n        \"disabled\": \"schema:expires\",\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n\
  \    },\n\n    \"ReloadTask\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"enabled\": \"schema:potentialAction\",\n        \"app\": {\n          \"@id\": \"schema:object\",\n          \"@type\": \"schema:SoftwareApplication\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"Session\": {\n      \"@id\": \"schema:InteractionCounter\",\n      \"@context\": {\n        \"sessionId\": \"@id\",\n        \"userId\": \"schema:identifier\",\n        \"userName\": \"schema:name\",\n        \"userDirectory\": \"schema:memberOf\",\n        \"sessionStart\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n     \
  \   },\n        \"lastActive\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Extension\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"owner\": {\n          \"@id\": \"schema:creator\",\n          \"@type\": \"schema:Person\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": \"schema:keywords\"\n      }\n    },\n\n    \"License\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"serial\": \"schema:serialNumber\",\n        \"key\": \"schema:identifier\",\n        \"isExpired\": \"schema:expires\",\n      \
  \  \"productLevel\": \"schema:version\"\n      }\n    },\n\n    \"ServerNode\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"hostName\": \"schema:url\",\n        \"isCentral\": \"schema:mainEntity\"\n      }\n    },\n\n    \"Tag\": {\n      \"@id\": \"schema:DefinedTerm\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\"\n      }\n    },\n\n    \"CustomProperty\": {\n      \"@id\": \"schema:PropertyValue\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:propertyID\",\n        \"choiceValues\": \"schema:value\",\n        \"objectTypes\": \"schema:additionalType\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/qlik-sense-enterprise/refs/heads/main/json-ld/qlik-sense-enterprise-context.jsonld
tags:
- Analytics
- Business Intelligence
- Data Visualization
- Enterprise
- REST API
- JSON-LD
- Linked Data
- Semantic Web
---
