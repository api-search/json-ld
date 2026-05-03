---
api_specs:
- filename: soax-web-data-api-openapi.yml
  format: yaml
  label: SOAX Web Data API
  slug: soax-web-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/openapi/soax-web-data-api-openapi.yml
- filename: soax-proxy-management-api-openapi.yml
  format: yaml
  label: SOAX Proxy Management API
  slug: soax-proxy-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/openapi/soax-proxy-management-api-openapi.yml
class_count: 39
classes:
- ProxyRequest
- ProxyPool
- ResidentialProxy
- MobileProxy
- DatacenterProxy
- ScrapeRequest
- SerpRequest
- EcommerceRequest
- GeoTarget
- IpSlot
- WebContent
- SearchResult
- ProductData
- url
- country
- city
- region
- isp
- carrier
- proxyType
- stickySession
- sessionId
- ipAddress
- slot
- apiKey
- packageKey
- htmlBody
- screenshot
- xhrResponse
- markdown
- searchQuery
- searchEngine
- organicResults
- featuredSnippet
- price
- priceCurrency
- stockStatus
- productRating
- reviewCount
context_file: json-ld/soax-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/json-ld/soax-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Soax from SOAX.
layout: jsonld
name: Soax Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: soax
  uri: https://soax.com/ontology/
properties: []
property_count: 0
provider_name: SOAX
provider_slug: soax
slug: soax-context
source_filename: soax-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"soax\": \"https://soax.com/ontology/\",\n\n    \"ProxyRequest\": \"soax:ProxyRequest\",\n    \"ProxyPool\": \"soax:ProxyPool\",\n    \"ResidentialProxy\": \"soax:ResidentialProxy\",\n    \"MobileProxy\": \"soax:MobileProxy\",\n    \"DatacenterProxy\": \"soax:DatacenterProxy\",\n    \"ScrapeRequest\": \"soax:ScrapeRequest\",\n    \"SerpRequest\": \"soax:SerpRequest\",\n    \"EcommerceRequest\": \"soax:EcommerceRequest\",\n    \"GeoTarget\": \"soax:GeoTarget\",\n    \"IpSlot\": \"soax:IpSlot\",\n    \"WebContent\": \"soax:WebContent\",\n    \"SearchResult\": \"soax:SearchResult\",\n    \"ProductData\": \"soax:ProductData\",\n\n    \"url\": \"schema:url\",\n    \"country\": \"schema:addressCountry\",\n    \"city\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"isp\": \"soax:internetServiceProvider\",\n    \"carrier\": \"soax:mobileCarrier\",\n    \"proxyType\"\
  : \"soax:proxyType\",\n    \"stickySession\": \"soax:stickySession\",\n    \"sessionId\": \"schema:identifier\",\n    \"ipAddress\": \"schema:ipAddressFromHeaders\",\n    \"slot\": \"soax:slot\",\n    \"apiKey\": \"schema:accessCode\",\n    \"packageKey\": \"soax:packageKey\",\n\n    \"htmlBody\": \"schema:text\",\n    \"screenshot\": \"schema:image\",\n    \"xhrResponse\": \"soax:xhrResponse\",\n    \"markdown\": \"soax:markdownContent\",\n\n    \"searchQuery\": \"schema:query\",\n    \"searchEngine\": \"soax:searchEngine\",\n    \"organicResults\": \"soax:organicResults\",\n    \"featuredSnippet\": \"soax:featuredSnippet\",\n\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"stockStatus\": \"schema:availability\",\n    \"productRating\": \"schema:ratingValue\",\n    \"reviewCount\": \"schema:reviewCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/json-ld/soax-context.jsonld
tags:
- Proxy
- Web Scraping
- Residential Proxies
- Mobile Proxies
- Datacenter Proxies
- Data Extraction
- Anti-Bot Bypass
- JSON-LD
- Linked Data
- Semantic Web
---
