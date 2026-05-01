---
api_specs:
- filename: drupal-rest-api-openapi.yml
  format: yaml
  label: Drupal REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/openapi/drupal-rest-api-openapi.yml
- filename: drupal-jsonapi-openapi.yml
  format: yaml
  label: Drupal JSON:API
  slug: jsonapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/openapi/drupal-jsonapi-openapi.yml
class_count: 0
classes: []
context_file: json-ld/drupal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/json-ld/drupal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Drupal from drupal.
layout: jsonld
name: Drupal Context
namespaces:
- prefix: drupal
  uri: https://www.drupal.org/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: hydra
  uri: http://www.w3.org/ns/hydra/core#
properties:
- container: ''
  name: Node
  type: ''
- container: ''
  name: ContentType
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: TaxonomyTerm
  type: ''
- container: ''
  name: TaxonomyVocabulary
  type: ''
- container: ''
  name: File
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: JsonApiResource
  type: ''
property_count: 8
provider_name: drupal
provider_slug: drupal
slug: drupal-context
source_filename: drupal-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"drupal\": \"https://www.drupal.org/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"hydra\": \"http://www.w3.org/ns/hydra/core#\",\n\n    \"Node\": {\n      \"@id\": \"drupal:Node\",\n      \"@context\": {\n        \"nid\": {\n          \"@id\": \"drupal:nid\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vid\": {\n          \"@id\": \"drupal:revisionId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"langcode\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"drupal:contentType\",\n          \"@type\": \"@id\"\n        },\n   \
  \     \"title\": \"schema:name\",\n        \"status\": {\n          \"@id\": \"schema:creativeWorkStatus\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"promote\": {\n          \"@id\": \"drupal:promoted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"sticky\": {\n          \"@id\": \"drupal:sticky\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"changed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"uid\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"body\": {\n          \"@id\": \"schema:text\"\n        },\n        \"path\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"field_tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n       \
  \ },\n        \"field_image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ContentType\": {\n      \"@id\": \"drupal:ContentType\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"drupal:machineNameId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"help\": {\n          \"@id\": \"drupal:helpText\",\n          \"@type\": \"xsd:string\"\n        },\n        \"new_revision\": {\n          \"@id\": \"drupal:revisionsEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"preview_mode\": {\n          \"@id\": \"drupal:previewMode\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"display_submitted\": {\n          \"@id\": \"drupal:displaySubmitted\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"drupal:User\",\n      \"@context\"\
  : {\n        \"uid\": {\n          \"@id\": \"drupal:userId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"mail\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:accountablePerson\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"changed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"access\": {\n          \"@id\": \"drupal:lastAccess\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"login\": {\n          \"@id\": \"drupal:lastLogin\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"roles\": {\n          \"@id\"\
  : \"schema:hasCredential\",\n          \"@container\": \"@set\"\n        },\n        \"timezone\": {\n          \"@id\": \"drupal:timezone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"langcode\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"TaxonomyTerm\": {\n      \"@id\": \"drupal:TaxonomyTerm\",\n      \"@context\": {\n        \"tid\": {\n          \"@id\": \"drupal:termId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vid\": {\n          \"@id\": \"drupal:vocabulary\",\n          \"@type\": \"@id\"\n        },\n        \"langcode\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"weight\": {\n          \"@id\": \"drupal:sortWeight\"\
  ,\n          \"@type\": \"xsd:integer\"\n        },\n        \"parent\": {\n          \"@id\": \"skos:broader\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"changed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"path\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TaxonomyVocabulary\": {\n      \"@id\": \"drupal:TaxonomyVocabulary\",\n      \"@context\": {\n        \"vid\": {\n          \"@id\": \"drupal:vocabularyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"hierarchy\": {\n          \"@id\": \"drupal:hierarchyType\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"File\": {\n\
  \      \"@id\": \"drupal:File\",\n      \"@context\": {\n        \"fid\": {\n          \"@id\": \"drupal:fileId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"langcode\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uid\": {\n          \"@id\": \"dcterms:creator\",\n          \"@type\": \"@id\"\n        },\n        \"filename\": \"schema:name\",\n        \"uri\": {\n          \"@id\": \"schema:contentUrl\",\n          \"@type\": \"@id\"\n        },\n        \"filemime\": {\n          \"@id\": \"schema:encodingFormat\",\n          \"@type\": \"xsd:string\"\n        },\n        \"filesize\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"drupal:fileStatus\",\n          \"@type\": \"xsd:boolean\"\n        },\n\
  \        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"changed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"drupal:Comment\",\n      \"@context\": {\n        \"cid\": {\n          \"@id\": \"drupal:commentId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"uuid\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"langcode\": {\n          \"@id\": \"dcterms:language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comment_type\": {\n          \"@id\": \"drupal:commentType\",\n          \"@type\": \"@id\"\n        },\n        \"subject\": \"schema:name\",\n        \"uid\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"entity_id\": {\n          \"@id\": \"schema:about\",\n       \
  \   \"@type\": \"@id\"\n        },\n        \"entity_type\": {\n          \"@id\": \"drupal:parentEntityType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"field_name\": {\n          \"@id\": \"drupal:commentField\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"schema:creativeWorkStatus\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"created\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"changed\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"comment_body\": {\n          \"@id\": \"schema:text\"\n        },\n        \"pid\": {\n          \"@id\": \"schema:parentItem\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"JsonApiResource\": {\n      \"@id\": \"drupal:JsonApiResource\",\n      \"@context\": {\n        \"type\": {\n          \"@id\": \"drupal:resourceType\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"dcterms:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attributes\": {\n          \"@id\": \"drupal:resourceAttributes\"\n        },\n        \"relationships\": {\n          \"@id\": \"drupal:resourceRelationships\"\n        },\n        \"links\": {\n          \"@id\": \"hydra:links\"\n        },\n        \"included\": {\n          \"@id\": \"drupal:includedResources\",\n          \"@container\": \"@set\"\n        },\n        \"meta\": {\n          \"@id\": \"drupal:responseMeta\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/drupal/refs/heads/main/json-ld/drupal-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
