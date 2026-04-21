---
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
