---
api_specs:
- filename: frostbyte-ip-geolocation-openapi.yml
  format: yaml
  label: Frostbyte IP Geolocation API
  slug: ip-geolocation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-ip-geolocation-openapi.yml
- filename: frostbyte-crypto-prices-openapi.yml
  format: yaml
  label: Frostbyte Crypto Prices API
  slug: crypto-prices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-crypto-prices-openapi.yml
- filename: frostbyte-screenshot-openapi.yml
  format: yaml
  label: Frostbyte Screenshot API
  slug: screenshot
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-screenshot-openapi.yml
- filename: frostbyte-dns-lookup-openapi.yml
  format: yaml
  label: Frostbyte DNS Lookup API
  slug: dns-lookup
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-dns-lookup-openapi.yml
- filename: frostbyte-web-scraper-openapi.yml
  format: yaml
  label: Frostbyte Web Scraper API
  slug: web-scraper
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-web-scraper-openapi.yml
- filename: frostbyte-code-execution-openapi.yml
  format: yaml
  label: Frostbyte Code Execution API
  slug: code-execution
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-code-execution-openapi.yml
- filename: frostbyte-agent-gateway-openapi.yml
  format: yaml
  label: Frostbyte Agent Gateway (Full API)
  slug: agent-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/openapi/frostbyte-agent-gateway-openapi.yml
class_count: 0
classes: []
context_file: json-ld/frostbyte-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/json-ld/frostbyte-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Frostbyte from Frostbyte.
layout: jsonld
name: Frostbyte Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fb
  uri: https://api-catalog-three.vercel.app/vocab#
properties:
- container: ''
  name: Frostbyte
  type: ''
- container: ''
  name: FrostbyteAPI
  type: ''
- container: ''
  name: FrostbyteCredit
  type: ''
- container: ''
  name: FrostbyteKey
  type: ''
- container: ''
  name: FrostbyteService
  type: ''
- container: ''
  name: credits
  type: schema:Integer
- container: ''
  name: expires_at
  type: schema:DateTime
- container: ''
  name: ip
  type: ''
- container: ''
  name: country_code
  type: ''
- container: ''
  name: city
  type: ''
- container: ''
  name: latitude
  type: schema:Number
- container: ''
  name: longitude
  type: schema:Number
- container: ''
  name: timezone
  type: ''
- container: ''
  name: symbol
  type: ''
- container: ''
  name: price
  type: schema:Number
- container: ''
  name: change_24h
  type: schema:Number
- container: ''
  name: volume_24h
  type: schema:Number
- container: ''
  name: source
  type: ''
property_count: 18
provider_name: Frostbyte
provider_slug: frostbyte
slug: frostbyte-context
source_filename: frostbyte-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fb\": \"https://api-catalog-three.vercel.app/vocab#\",\n    \"Frostbyte\":         { \"@id\": \"schema:Organization\" },\n    \"FrostbyteAPI\":      { \"@id\": \"schema:WebAPI\" },\n    \"FrostbyteCredit\":   { \"@id\": \"fb:Credit\" },\n    \"FrostbyteKey\":      { \"@id\": \"fb:APIKey\" },\n    \"FrostbyteService\":  { \"@id\": \"fb:Service\" },\n    \"credits\":           { \"@id\": \"fb:credits\", \"@type\": \"schema:Integer\" },\n    \"expires_at\":        { \"@id\": \"fb:expiresAt\", \"@type\": \"schema:DateTime\" },\n    \"ip\":                { \"@id\": \"fb:ip\" },\n    \"country_code\":      { \"@id\": \"schema:addressCountry\" },\n    \"city\":              { \"@id\": \"schema:addressLocality\" },\n    \"latitude\":          { \"@id\": \"schema:latitude\", \"@type\": \"schema:Number\" },\n    \"longitude\":         { \"@id\": \"schema:longitude\", \"@type\": \"schema:Number\"\
  \ },\n    \"timezone\":          { \"@id\": \"fb:timezone\" },\n    \"symbol\":            { \"@id\": \"fb:symbol\" },\n    \"price\":             { \"@id\": \"schema:price\", \"@type\": \"schema:Number\" },\n    \"change_24h\":        { \"@id\": \"fb:change24h\", \"@type\": \"schema:Number\" },\n    \"volume_24h\":        { \"@id\": \"fb:volume24h\", \"@type\": \"schema:Number\" },\n    \"source\":            { \"@id\": \"schema:provider\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/frostbyte/refs/heads/main/json-ld/frostbyte-context.jsonld
tags:
- Developer Tools
- Utility APIs
- Geolocation
- Cryptocurrency
- Screenshots
- DNS
- Scraping
- AI Agents
- JSON-LD
- Linked Data
- Semantic Web
---
