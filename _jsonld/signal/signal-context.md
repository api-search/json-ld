---
api_specs:
- filename: signal-server-openapi.yml
  format: yaml
  label: Signal Server
  slug: signal-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/openapi/signal-server-openapi.yml
class_count: 0
classes: []
context_file: json-ld/signal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/json-ld/signal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Signal from Signal.
layout: jsonld
name: Signal Context
namespaces:
- prefix: signal
  uri: https://signal.org/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: Account
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: IdentityKey
  type: ''
- container: ''
  name: PreKey
  type: ''
- container: ''
  name: SignedPreKey
  type: ''
- container: ''
  name: KyberPreKey
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: Profile
  type: ''
- container: ''
  name: Protocol
  type: ''
property_count: 10
provider_name: Signal
provider_slug: signal
slug: signal-context
source_filename: signal-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"signal\": \"https://signal.org/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"Account\": {\n      \"@id\": \"signal:Account\",\n      \"@context\": {\n        \"uuid\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pni\": {\n          \"@id\": \"signal:phoneNumberIdentity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"usernameHash\": {\n          \"@id\": \"signal:usernameHash\",\n          \"@type\": \"xsd:string\"\n        },\n        \"identityKey\": {\n          \"@id\": \"sec:publicKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"devices\": {\n          \"@id\"\
  : \"signal:devices\",\n          \"@container\": \"@set\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"signal:Device\",\n      \"@context\": {\n        \"deviceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastSeen\": {\n          \"@id\": \"signal:lastSeen\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"platform\": {\n          \"@id\": \"schema:operatingSystem\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Message\": {\n      \"@id\": \"signal:Message\",\n      \"@context\": {\n        \"type\": {\n          \"@id\"\
  : \"signal:envelopeType\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sender\": {\n          \"@id\": \"schema:sender\",\n          \"@type\": \"@id\"\n        },\n        \"recipient\": {\n          \"@id\": \"schema:recipient\",\n          \"@type\": \"@id\"\n        },\n        \"timestamp\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"serverTimestamp\": {\n          \"@id\": \"signal:serverTimestamp\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"content\": {\n          \"@id\": \"schema:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"urgent\": {\n          \"@id\": \"signal:urgent\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"IdentityKey\": {\n      \"@id\": \"signal:IdentityKey\",\n      \"@context\": {\n        \"publicKey\": {\n          \"@id\": \"sec:publicKeyBase64\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fingerprint\"\
  : {\n          \"@id\": \"signal:fingerprint\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"PreKey\": {\n      \"@id\": \"signal:PreKey\",\n      \"@context\": {\n        \"keyId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"publicKey\": {\n          \"@id\": \"sec:publicKeyBase64\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"SignedPreKey\": {\n      \"@id\": \"signal:SignedPreKey\",\n      \"@context\": {\n        \"keyId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"publicKey\": {\n          \"@id\": \"sec:publicKeyBase64\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signature\": {\n          \"@id\": \"sec:signature\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"KyberPreKey\": {\n      \"@id\": \"signal:KyberPreKey\",\n      \"@context\": {\n        \"\
  keyId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"publicKey\": {\n          \"@id\": \"sec:publicKeyBase64\",\n          \"@type\": \"xsd:string\"\n        },\n        \"signature\": {\n          \"@id\": \"sec:signature\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"signal:Group\",\n      \"@context\": {\n        \"groupId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatar\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"members\": {\n          \"@id\": \"schema:member\",\n          \"@container\": \"@set\"\n        },\n        \"revision\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\
  \n    \"Profile\": {\n      \"@id\": \"signal:Profile\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"about\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"avatar\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"paymentAddress\": {\n          \"@id\": \"signal:paymentAddress\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Protocol\": {\n      \"@id\": \"signal:Protocol\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"specificationUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"version\": {\n    \
  \      \"@id\": \"schema:version\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/signal/refs/heads/main/json-ld/signal-context.jsonld
tags:
- Encryption
- Messaging
- Security
- Cryptography
- Open Source
- Privacy
- JSON-LD
- Linked Data
- Semantic Web
---
