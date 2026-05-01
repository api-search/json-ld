---
api_specs:
- filename: fastly-services-openapi.yml
  format: yaml
  label: Fastly Services API
  slug: services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-services-openapi.yml
- filename: fastly-purging-openapi.yml
  format: yaml
  label: Fastly Purging API
  slug: purging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-purging-openapi.yml
- filename: fastly-logging-openapi.yml
  format: yaml
  label: Fastly Real-Time Logging API
  slug: logging-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-logging-openapi.yml
- filename: fastly-metrics-and-stats-openapi.yml
  format: yaml
  label: Fastly Metrics and Stats API
  slug: metrics-and-stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-metrics-and-stats-openapi.yml
- filename: fastly-tls-openapi.yml
  format: yaml
  label: Fastly TLS API
  slug: tls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-tls-openapi.yml
- filename: fastly-vcl-services-openapi.yml
  format: yaml
  label: Fastly VCL Services API
  slug: vcl-services-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-vcl-services-openapi.yml
- filename: fastly-account-openapi.yml
  format: yaml
  label: Fastly Account API
  slug: account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-account-openapi.yml
- filename: fastly-authentication-tokens-openapi.yml
  format: yaml
  label: Fastly Authentication Tokens API
  slug: authentication-tokens-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-authentication-tokens-openapi.yml
- filename: fastly-acls-openapi.yml
  format: yaml
  label: Fastly Access Control Lists API
  slug: acls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-acls-openapi.yml
- filename: fastly-dictionaries-openapi.yml
  format: yaml
  label: Fastly Edge Dictionaries API
  slug: dictionaries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-dictionaries-openapi.yml
- filename: fastly-compute-openapi.yml
  format: yaml
  label: Fastly Compute API
  slug: compute-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-compute-openapi.yml
- filename: fastly-waf-openapi.yml
  format: yaml
  label: Fastly Next-Gen WAF API
  slug: waf-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-waf-openapi.yml
- filename: fastly-domain-management-openapi.yml
  format: yaml
  label: Fastly Domain Management API
  slug: domain-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-domain-management-openapi.yml
- filename: fastly-products-openapi.yml
  format: yaml
  label: Fastly Products API
  slug: products-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/openapi/fastly-products-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fastly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/json-ld/fastly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fastly from fastly.
layout: jsonld
name: Fastly Context
namespaces:
- prefix: fastly
  uri: https://api.fastly.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Service
  type: ''
- container: ''
  name: ServiceVersion
  type: ''
- container: ''
  name: Backend
  type: ''
- container: ''
  name: Domain
  type: ''
- container: ''
  name: ACL
  type: ''
- container: ''
  name: ACLEntry
  type: ''
- container: ''
  name: Dictionary
  type: ''
- container: ''
  name: DictionaryItem
  type: ''
- container: ''
  name: TLSCertificate
  type: ''
- container: ''
  name: KVStore
  type: ''
- container: ''
  name: Token
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: User
  type: ''
property_count: 13
provider_name: fastly
provider_slug: fastly
slug: fastly-context
source_filename: fastly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fastly\": \"https://api.fastly.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Service\": {\n      \"@id\": \"fastly:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"serviceType\": \"fastly:serviceType\",\n        \"customerId\": \"fastly:customerId\",\n        \"activeVersion\": \"fastly:activeVersion\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"versions\": {\n          \"@id\": \"fastly:versions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ServiceVersion\": {\n      \"@id\": \"fastly:ServiceVersion\"\
  ,\n      \"@context\": {\n        \"number\": \"fastly:versionNumber\",\n        \"active\": \"fastly:active\",\n        \"locked\": \"fastly:locked\",\n        \"deployed\": \"fastly:deployed\",\n        \"comment\": \"schema:comment\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Backend\": {\n      \"@id\": \"fastly:Backend\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"address\": \"fastly:address\",\n        \"port\": \"fastly:port\",\n        \"useSSL\": \"fastly:useSSL\",\n        \"sslHostname\": \"fastly:sslHostname\",\n        \"shield\": \"fastly:shield\",\n        \"weight\": \"fastly:weight\",\n        \"connectTimeout\": \"fastly:connectTimeout\",\n        \"firstByteTimeout\": \"fastly:firstByteTimeout\",\n        \"betweenBytesTimeout\"\
  : \"fastly:betweenBytesTimeout\",\n        \"maxConn\": \"fastly:maxConn\",\n        \"healthcheck\": \"fastly:healthcheck\"\n      }\n    },\n\n    \"Domain\": {\n      \"@id\": \"fastly:Domain\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"comment\": \"schema:comment\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ACL\": {\n      \"@id\": \"fastly:ACL\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"entries\": {\n          \"@id\": \"fastly:entries\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        }\n      }\n    },\n\n    \"ACLEntry\": {\n      \"@id\": \"fastly:ACLEntry\",\n      \"@context\": {\n        \"ip\": \"fastly:ipAddress\",\n        \"subnet\": \"fastly:subnet\",\n        \"negated\": \"fastly:negated\",\n        \"comment\": \"schema:comment\"\n      }\n    },\n\n    \"Dictionary\": {\n      \"@id\": \"fastly:Dictionary\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"writeOnly\": \"fastly:writeOnly\",\n        \"items\": {\n          \"@id\": \"fastly:items\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DictionaryItem\": {\n      \"@id\": \"fastly:DictionaryItem\",\n      \"@context\": {\n        \"itemKey\": \"fastly:itemKey\",\n        \"itemValue\": \"fastly:itemValue\"\
  \n      }\n    },\n\n    \"TLSCertificate\": {\n      \"@id\": \"fastly:TLSCertificate\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"issuedTo\": \"fastly:issuedTo\",\n        \"issuer\": \"fastly:issuer\",\n        \"serialNumber\": \"fastly:serialNumber\",\n        \"signatureAlgorithm\": \"fastly:signatureAlgorithm\",\n        \"notBefore\": {\n          \"@id\": \"fastly:notBefore\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"notAfter\": {\n          \"@id\": \"fastly:notAfter\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"domains\": {\n          \"@id\": \"fastly:domains\",\n          \"@container\": \"@set\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"KVStore\": {\n      \"@id\": \"fastly:KVStore\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Token\": {\n      \"@id\": \"fastly:Token\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"scope\": \"fastly:scope\",\n        \"services\": {\n          \"@id\": \"fastly:services\",\n          \"@container\": \"@set\"\n        },\n        \"expiresAt\": {\n          \"@id\": \"fastly:expiresAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUsedAt\": {\n          \"@id\": \"fastly:lastUsedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"fastly:Customer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"pricingPlan\": \"fastly:pricingPlan\",\n  \
  \      \"ownerId\": \"fastly:ownerId\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"fastly:User\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"login\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": \"fastly:role\",\n        \"twoFactorAuthEnabled\": \"fastly:twoFactorAuthEnabled\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fastly/refs/heads/main/json-ld/fastly-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
