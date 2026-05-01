---
class_count: 0
classes: []
context_file: json-ld/denodo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/denodo/refs/heads/main/json-ld/denodo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Denodo from Denodo.
layout: jsonld
name: Denodo Context
namespaces:
- prefix: denodo
  uri: https://community.denodo.com/docs/
properties:
- container: ''
  name: VirtualView
  type: ''
- container: ''
  name: DataCatalogElement
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Environment
  type: ''
- container: ''
  name: ScheduledJob
  type: ''
- container: ''
  name: RESTEndpoint
  type: ''
property_count: 6
provider_name: Denodo
provider_slug: denodo
slug: denodo-context
source_filename: denodo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"denodo\": \"https://community.denodo.com/docs/\",\n    \"VirtualView\": {\n      \"@id\": \"denodo:vdp/administration/restful_architecture/restful_architecture\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"database\": \"https://schema.org/isPartOf\",\n        \"fields\": \"https://schema.org/variableMeasured\",\n        \"description\": \"https://schema.org/description\"\n      }\n    },\n    \"DataCatalogElement\": {\n      \"@id\": \"denodo:vdp/data_catalog/appendix/rest_api/rest_api\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"tags\": \"https://schema.org/keywords\",\n        \"category\": \"https://schema.org/category\",\n        \"owner\": \"https://schema.org/author\"\n      }\n    },\n    \"Cluster\": {\n      \"@id\": \"denodo:solution_manager/administration/appendix/rest_api/rest_api\"\
  ,\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"environment\": \"https://schema.org/applicationCategory\",\n        \"servers\": \"https://schema.org/serviceType\"\n      }\n    },\n    \"Environment\": {\n      \"@id\": \"denodo:solution_manager/administration/appendix/rest_api/rest_api\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"minUpdate\": \"https://schema.org/version\"\n      }\n    },\n    \"ScheduledJob\": {\n      \"@id\": \"denodo:scheduler/administration/scheduler_rest_web_service/scheduler_rest_web_service\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"project\": \"https://schema.org/isPartOf\",\n        \"schedule\": \"https://schema.org/scheduleTimezone\",\n        \"status\": \"https://schema.org/eventStatus\"\n      }\n    },\n    \"RESTEndpoint\": {\n      \"@id\": \"denodo:vdp/administration/restful_architecture/rest_web_service/rest_web_service\"\
  ,\n      \"@context\": {\n        \"path\": \"https://schema.org/url\",\n        \"view\": \"https://schema.org/about\",\n        \"format\": \"https://schema.org/encodingFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/denodo/refs/heads/main/json-ld/denodo-context.jsonld
tags:
- Data Catalog
- Data Fabric
- Data Mesh
- Data Virtualization
- GraphQL
- Logical Data Warehouse
- OData
- REST
- Scheduler
- Solution Manager
- JSON-LD
- Linked Data
- Semantic Web
---
