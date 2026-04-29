---
api_specs:
- filename: ariba-guided-buying-catalog-shop-api.yaml
  format: yaml
  label: Ariba Guided Buying - Public Catalogs Shop API
  slug: ariba-guided-buying-catalog-shop-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/openapi/ariba-guided-buying-catalog-shop-api.yaml
- filename: ariba-guided-buying-asset-management-api.yaml
  format: yaml
  label: Ariba Guided Buying - Asset Management API
  slug: ariba-guided-buying-asset-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/openapi/ariba-guided-buying-asset-management-api.yaml
class_count: 7
classes:
- ItemsResponse
- CatalogItem
- ShopResponse
- Facet
- name
- FacetValue
- AutoCompleteResponse
context_file: json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ariba Guided Buying Catalog Shop Api from Ariba Guided Buying.
layout: jsonld
name: Ariba Guided Buying Catalog Shop Api Context
namespaces:
- prefix: ariba
  uri: https://openapi.ariba.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: items
  type: string
- container: ''
  name: extProductId
  type: string
- container: ''
  name: leadTime
  type: integer
- container: ''
  name: manufactCode
  type: string
- container: ''
  name: manufactName
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: vendor
  type: string
- container: ''
  name: vendorName
  type: string
- container: ''
  name: vendorPartId
  type: string
- container: ''
  name: shopID
  type: string
- container: set
  name: facets
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: count
  type: integer
- container: set
  name: suggestions
  type: string
property_count: 15
provider_name: Ariba Guided Buying
provider_slug: ariba-guided-buying
slug: ariba-guided-buying-catalog-shop-api-context
source_filename: ariba-guided-buying-catalog-shop-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ariba\": \"https://openapi.ariba.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ItemsResponse\": \"ariba:ItemsResponse\",\n    \"items\": {\n      \"@id\": \"ariba:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogItem\": \"ariba:CatalogItem\",\n    \"extProductId\": {\n      \"@id\": \"ariba:extProductId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leadTime\": {\n      \"@id\": \"ariba:leadTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"manufactCode\": {\n      \"@id\": \"ariba:manufactCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufactName\": {\n      \"@id\": \"ariba:manufactName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"ariba:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vendor\"\
  : {\n      \"@id\": \"ariba:vendor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorName\": {\n      \"@id\": \"ariba:vendorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorPartId\": {\n      \"@id\": \"ariba:vendorPartId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShopResponse\": \"ariba:ShopResponse\",\n    \"shopID\": {\n      \"@id\": \"ariba:shopID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facets\": {\n      \"@id\": \"ariba:facets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Facet\": \"ariba:Facet\",\n    \"name\": \"schema:name\",\n    \"values\": {\n      \"@id\": \"ariba:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FacetValue\": \"ariba:FacetValue\",\n    \"label\": {\n      \"@id\": \"ariba:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"ariba:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"AutoCompleteResponse\"\
  : \"ariba:AutoCompleteResponse\",\n    \"suggestions\": {\n      \"@id\": \"ariba:suggestions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ariba-guided-buying/refs/heads/main/json-ld/ariba-guided-buying-catalog-shop-api-context.jsonld
tags:
- B2B
- Catalog
- ERP
- Procurement
- Requisitions
- SAP
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
