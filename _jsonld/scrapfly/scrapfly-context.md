---
api_specs:
- filename: scrapfly-scrape-openapi.yml
  format: yaml
  label: Scrapfly Scrape API
  slug: scrape-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/openapi/scrapfly-scrape-openapi.yml
class_count: 0
classes: []
context_file: json-ld/scrapfly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-ld/scrapfly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Scrapfly from Scrapfly.
layout: jsonld
name: Scrapfly Context
namespaces:
- prefix: scrapfly
  uri: https://api-evangelist.github.io/scrapfly/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ScrapeRequest
  type: rdfs:Class
- container: ''
  name: ScrapeResult
  type: rdfs:Class
- container: ''
  name: Screenshot
  type: schema:ImageObject
- container: ''
  name: ExtractionResult
  type: rdfs:Class
- container: ''
  name: url
  type: anyURI
- container: ''
  name: content
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: statusCode
  type: integer
- container: ''
  name: renderJs
  type: boolean
- container: ''
  name: aspEnabled
  type: boolean
- container: ''
  name: proxyCountry
  type: string
- container: ''
  name: apiCost
  type: integer
- container: ''
  name: remainingCredits
  type: integer
- container: ''
  name: sessionName
  type: string
- container: ''
  name: correlationId
  type: string
property_count: 15
provider_name: Scrapfly
provider_slug: scrapfly
slug: scrapfly-context
source_filename: scrapfly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"scrapfly\": \"https://api-evangelist.github.io/scrapfly/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ScrapeRequest\": {\n      \"@id\": \"scrapfly:ScrapeRequest\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"A web scraping request submitted to the Scrapfly API\"\n    },\n    \"ScrapeResult\": {\n      \"@id\": \"scrapfly:ScrapeResult\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"The result of a web scraping request\"\n    },\n    \"Screenshot\": {\n      \"@id\": \"scrapfly:Screenshot\",\n      \"@type\": \"schema:ImageObject\",\n      \"rdfs:comment\": \"A screenshot image captured from a web page\"\n    },\n    \"ExtractionResult\": {\n      \"@id\": \"scrapfly:ExtractionResult\",\n      \"@type\": \"rdfs:Class\",\n      \"rdfs:comment\": \"Structured data extracted from scraped content via template or LLM\"\n    },\n\n    \"url\": {\n      \"\
  @id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"content\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"scrapfly:httpStatusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"renderJs\": {\n      \"@id\": \"scrapfly:renderJs\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"aspEnabled\": {\n      \"@id\": \"scrapfly:antiBotProtection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"proxyCountry\": {\n      \"@id\": \"scrapfly:proxyCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiCost\": {\n      \"@id\": \"scrapfly:creditCost\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remainingCredits\": {\n      \"@id\": \"scrapfly:remainingCredits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sessionName\": {\n      \"@id\": \"scrapfly:sessionName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"correlationId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-ld/scrapfly-context.jsonld
tags:
- AI
- Data Extraction
- Screenshots
- Web Scraping
- Proxies
- Browser Automation
- JSON-LD
- Linked Data
- Semantic Web
---
