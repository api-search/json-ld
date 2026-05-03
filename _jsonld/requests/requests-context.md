---
class_count: 13
classes:
- headers
- params
- data
- json
- cookies
- auth
- verify
- proxies
- cert
- reason
- encoding
- text
- content
context_file: json-ld/requests-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-ld/requests-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Requests from Requests.
layout: jsonld
name: Requests Context
namespaces:
- prefix: req
  uri: https://schema.api-evangelist.com/requests/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: HTTPRequest
  type: reference
- container: ''
  name: HTTPResponse
  type: reference
- container: ''
  name: HTTPSession
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: timeout
  type: decimal
- container: ''
  name: allow_redirects
  type: boolean
- container: ''
  name: stream
  type: boolean
- container: ''
  name: status_code
  type: integer
- container: ''
  name: ok
  type: boolean
- container: ''
  name: elapsed
  type: decimal
- container: list
  name: history
  type: ''
property_count: 12
provider_name: Requests
provider_slug: requests
slug: requests-context
source_filename: requests-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"req\": \"https://schema.api-evangelist.com/requests/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"HTTPRequest\": {\n      \"@id\": \"hydra:Operation\",\n      \"@type\": \"@id\"\n    },\n    \"HTTPResponse\": {\n      \"@id\": \"req:Response\",\n      \"@type\": \"@id\"\n    },\n    \"HTTPSession\": {\n      \"@id\": \"req:Session\",\n      \"@type\": \"@id\"\n    },\n\n    \"method\": {\n      \"@id\": \"hydra:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"headers\": \"req:headers\",\n    \"params\": \"req:queryParams\",\n    \"data\": \"req:formData\",\n    \"json\": \"req:jsonBody\",\n    \"cookies\": \"req:cookies\",\n    \"auth\": \"req:auth\",\n    \"timeout\": {\n\
  \      \"@id\": \"req:timeout\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"allow_redirects\": {\n      \"@id\": \"req:allowRedirects\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"verify\": \"req:tlsVerify\",\n    \"stream\": {\n      \"@id\": \"req:stream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"proxies\": \"req:proxies\",\n    \"cert\": \"req:clientCert\",\n\n    \"status_code\": {\n      \"@id\": \"req:statusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ok\": {\n      \"@id\": \"req:isOk\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": \"req:reasonPhrase\",\n    \"encoding\": \"req:encoding\",\n    \"text\": \"req:textBody\",\n    \"content\": \"req:binaryContent\",\n    \"elapsed\": {\n      \"@id\": \"req:elapsed\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"history\": {\n      \"@id\": \"req:redirectHistory\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/requests/refs/heads/main/json-ld/requests-context.jsonld
tags:
- Clients
- HTTP Client
- HTTP Library
- Open Source
- Python
- Python Software Foundation
- JSON-LD
- Linked Data
- Semantic Web
---
