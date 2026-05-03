---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 2
classes:
- PaginatedResponse
- PartnerAccessExternalRep
context_file: json-ld/toast-partners-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-partners-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Partners from Toast.
layout: jsonld
name: Toast Partners Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdByEmailAddress
  type: string
- container: ''
  name: createdDate
  type: integer
- container: ''
  name: currentPageNum
  type: integer
- container: ''
  name: currentPageToken
  type: string
- container: ''
  name: deleted
  type: boolean
- container: ''
  name: externalGroupRef
  type: string
- container: ''
  name: externalRestaurantRef
  type: string
- container: ''
  name: isoCreatedDate
  type: string
- container: ''
  name: isoModifiedDate
  type: string
- container: ''
  name: lastPageNum
  type: integer
- container: ''
  name: locationName
  type: string
- container: ''
  name: managementGroupGuid
  type: string
- container: ''
  name: modifiedDate
  type: integer
- container: ''
  name: nextPageNum
  type: integer
- container: ''
  name: nextPageToken
  type: string
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: previousPageNum
  type: integer
- container: ''
  name: restaurantGuid
  type: string
- container: ''
  name: restaurantName
  type: string
- container: set
  name: results
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: totalResultCount
  type: integer
property_count: 22
provider_name: Toast
provider_slug: toast
slug: toast-partners-context
source_filename: toast-partners-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaginatedResponse\": \"toast:PaginatedResponse\",\n    \"PartnerAccessExternalRep\": \"toast:PartnerAccessExternalRep\",\n    \"createdByEmailAddress\": {\n      \"@id\": \"toast:createdByEmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdDate\": {\n      \"@id\": \"toast:createdDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentPageNum\": {\n      \"@id\": \"toast:currentPageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentPageToken\": {\n      \"@id\": \"toast:currentPageToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleted\": {\n      \"@id\": \"toast:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"externalGroupRef\": {\n      \"@id\": \"toast:externalGroupRef\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"externalRestaurantRef\": {\n      \"@id\": \"toast:externalRestaurantRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isoCreatedDate\": {\n      \"@id\": \"toast:isoCreatedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isoModifiedDate\": {\n      \"@id\": \"toast:isoModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastPageNum\": {\n      \"@id\": \"toast:lastPageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"locationName\": {\n      \"@id\": \"toast:locationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managementGroupGuid\": {\n      \"@id\": \"toast:managementGroupGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiedDate\": {\n      \"@id\": \"toast:modifiedDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nextPageNum\": {\n      \"@id\": \"toast:nextPageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"nextPageToken\": {\n      \"@id\": \"toast:nextPageToken\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"pageSize\": {\n      \"@id\": \"toast:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"previousPageNum\": {\n      \"@id\": \"toast:previousPageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"restaurantGuid\": {\n      \"@id\": \"toast:restaurantGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restaurantName\": {\n      \"@id\": \"toast:restaurantName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"toast:results\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"toast:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalResultCount\": {\n      \"@id\": \"toast:totalResultCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-partners-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
