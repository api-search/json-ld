---
api_specs:
- filename: api-snap-openapi.yml
  format: yaml
  label: QR Code API
  slug: qr
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Screenshot API
  slug: screenshot
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Image Resize API
  slug: resize
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: PDF API
  slug: pdf
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Markdown API
  slug: markdown
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: URL Metadata API
  slug: meta
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Hash API
  slug: hash
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: JWT Decode API
  slug: jwt-decode
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Base64 API
  slug: base64
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: UUID API
  slug: uuid
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Color API
  slug: color
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Lorem Ipsum API
  slug: lorem
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
- filename: api-snap-openapi.yml
  format: yaml
  label: Placeholder Image API
  slug: placeholder
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/openapi/api-snap-openapi.yml
class_count: 22
classes:
- ApiSnap
- name
- description
- url
- provider
- termsOfService
- documentation
- endpointURL
- endpointDescription
- version
- Hash
- Identifier
- UrlMetadata
- title
- image
- siteName
- author
- type
- Base64Result
- JwtDecoded
- ColorConversion
- LoremText
context_file: json-ld/api-snap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/json-ld/api-snap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Api Snap from API Snap.
layout: jsonld
name: Api Snap Context
namespaces:
- prefix: snap
  uri: https://api-snap.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: hash
  type: ''
- container: ''
  name: algorithm
  type: ''
- container: ''
  name: encoding
  type: ''
- container: ''
  name: id
  type: ''
- container: set
  name: ids
  type: ''
- container: ''
  name: format
  type: ''
- container: ''
  name: count
  type: integer
- container: ''
  name: prefix
  type: ''
- container: ''
  name: favicon
  type: ''
- container: ''
  name: themeColor
  type: ''
- container: ''
  name: published
  type: dateTime
- container: ''
  name: input
  type: ''
- container: ''
  name: result
  type: ''
- container: ''
  name: action
  type: ''
- container: ''
  name: urlSafe
  type: boolean
- container: ''
  name: header
  type: ''
- container: ''
  name: payload
  type: ''
- container: ''
  name: expired
  type: boolean
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: issuedAt
  type: dateTime
- container: ''
  name: hex
  type: ''
- container: ''
  name: rgb
  type: ''
- container: ''
  name: rgbString
  type: ''
- container: ''
  name: hsl
  type: ''
- container: ''
  name: hslString
  type: ''
- container: ''
  name: rgba
  type: ''
- container: ''
  name: brightness
  type: integer
- container: ''
  name: isDark
  type: boolean
- container: ''
  name: text
  type: ''
- container: list
  name: paragraphs
  type: ''
property_count: 30
provider_name: API Snap
provider_slug: api-snap
slug: api-snap-context
source_filename: api-snap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"snap\": \"https://api-snap.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiSnap\": \"snap:ApiSnap\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"termsOfService\": \"schema:termsOfService\",\n    \"documentation\": \"schema:documentation\",\n    \"endpointURL\": \"schema:endpointURL\",\n    \"endpointDescription\": \"schema:endpointDescription\",\n    \"version\": \"schema:version\",\n    \"Hash\": \"snap:Hash\",\n    \"hash\": {\"@id\": \"snap:hash\"},\n    \"algorithm\": {\"@id\": \"snap:algorithm\"},\n    \"encoding\": {\"@id\": \"snap:encoding\"},\n    \"Identifier\": \"snap:Identifier\",\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"ids\": {\"@id\": \"snap:ids\", \"@container\": \"@set\"\
  },\n    \"format\": {\"@id\": \"snap:format\"},\n    \"count\": {\"@id\": \"snap:count\", \"@type\": \"xsd:integer\"},\n    \"prefix\": {\"@id\": \"snap:prefix\"},\n    \"UrlMetadata\": \"snap:UrlMetadata\",\n    \"title\": \"schema:headline\",\n    \"image\": \"schema:image\",\n    \"siteName\": \"schema:publisher\",\n    \"favicon\": {\"@id\": \"snap:favicon\"},\n    \"themeColor\": {\"@id\": \"snap:themeColor\"},\n    \"author\": \"schema:author\",\n    \"published\": {\"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\"},\n    \"type\": \"schema:additionalType\",\n    \"Base64Result\": \"snap:Base64Result\",\n    \"input\": {\"@id\": \"snap:input\"},\n    \"result\": {\"@id\": \"snap:result\"},\n    \"action\": {\"@id\": \"snap:action\"},\n    \"urlSafe\": {\"@id\": \"snap:urlSafe\", \"@type\": \"xsd:boolean\"},\n    \"JwtDecoded\": \"snap:JwtDecoded\",\n    \"header\": {\"@id\": \"snap:jwtHeader\"},\n    \"payload\": {\"@id\": \"snap:jwtPayload\"},\n    \"expired\": {\"\
  @id\": \"snap:expired\", \"@type\": \"xsd:boolean\"},\n    \"expiresAt\": {\"@id\": \"snap:expiresAt\", \"@type\": \"xsd:dateTime\"},\n    \"issuedAt\": {\"@id\": \"snap:issuedAt\", \"@type\": \"xsd:dateTime\"},\n    \"ColorConversion\": \"snap:ColorConversion\",\n    \"hex\": {\"@id\": \"snap:hex\"},\n    \"rgb\": {\"@id\": \"snap:rgb\"},\n    \"rgbString\": {\"@id\": \"snap:rgbString\"},\n    \"hsl\": {\"@id\": \"snap:hsl\"},\n    \"hslString\": {\"@id\": \"snap:hslString\"},\n    \"rgba\": {\"@id\": \"snap:rgba\"},\n    \"brightness\": {\"@id\": \"snap:brightness\", \"@type\": \"xsd:integer\"},\n    \"isDark\": {\"@id\": \"snap:isDark\", \"@type\": \"xsd:boolean\"},\n    \"LoremText\": \"snap:LoremText\",\n    \"text\": {\"@id\": \"schema:text\"},\n    \"paragraphs\": {\"@id\": \"snap:paragraphs\", \"@container\": \"@list\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/api-snap/refs/heads/main/json-ld/api-snap-context.jsonld
tags:
- API Utilities
- Developer Tools
- QR Codes
- Screenshots
- Image Processing
- PDF Generation
- Markdown
- URL Metadata
- Hashing
- JWT
- Base64
- UUID
- Color Conversion
- Lorem Ipsum
- Placeholder Images
- JSON-LD
- Linked Data
- Semantic Web
---
