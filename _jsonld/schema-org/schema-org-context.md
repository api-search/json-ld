---
class_count: 0
classes: []
context_file: json-ld/schema-org-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/schema-org/refs/heads/main/json-ld/schema-org-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Schema Org from Schema.org.
layout: jsonld
name: Schema Org Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties:
- container: ''
  name: Thing
  type: ''
- container: ''
  name: CreativeWork
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Person
  type: ''
- container: ''
  name: Place
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: WebAPI
  type: ''
property_count: 8
provider_name: Schema.org
provider_slug: schema-org
slug: schema-org-context
source_filename: schema-org-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n\n    \"Thing\": {\n      \"@id\": \"schema:Thing\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"image\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"identifier\": \"schema:identifier\",\n        \"sameAs\": {\n          \"@id\": \"schema:sameAs\",\n          \"@type\": \"@id\"\n        },\n        \"alternateName\": \"schema:alternateName\",\n        \"additionalType\": {\n          \"@id\": \"schema:additionalType\",\n          \"@type\": \"@id\"\n\
  \        }\n      }\n    },\n\n    \"CreativeWork\": {\n      \"@id\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"@id\"\n        },\n        \"datePublished\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"dateModified\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:date\"\n        },\n        \"headline\": \"schema:headline\",\n        \"text\": \"schema:text\",\n        \"keywords\": \"schema:keywords\",\n        \"license\": {\n          \"@id\": \"schema:license\",\n          \"@type\": \"@id\"\n        },\n        \"publisher\": {\n          \"@id\": \"schema:publisher\",\n          \"@type\": \"@id\"\n        },\n        \"inLanguage\": \"schema:inLanguage\",\n        \"version\": \"schema:version\"\
  \n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"legalName\": \"schema:legalName\",\n        \"email\": \"schema:email\",\n        \"telephone\": \"schema:telephone\",\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        },\n        \"member\": {\n          \"@id\": \"schema:member\",\n          \"@type\": \"@id\"\n        },\n        \"founder\": {\n          \"@id\": \"schema:founder\",\n          \"@type\": \"@id\"\n        },\n        \"foundingDate\": {\n          \"@id\": \"schema:foundingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"numberOfEmployees\": \"schema:numberOfEmployees\",\n        \"logo\": {\n          \"@id\": \"schema:logo\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Person\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"givenName\": \"schema:givenName\",\n        \"familyName\"\
  : \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"telephone\": \"schema:telephone\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"affiliation\": {\n          \"@id\": \"schema:affiliation\",\n          \"@type\": \"@id\"\n        },\n        \"birthDate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        },\n        \"worksFor\": {\n          \"@id\": \"schema:worksFor\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Place\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"@id\"\n        },\n        \"geo\": {\n          \"@id\": \"schema:geo\",\n          \"@type\": \"@id\"\n        },\n        \"latitude\": {\n          \"@id\": \"schema:latitude\",\n          \"@type\": \"xsd:float\"\n   \
  \     },\n        \"longitude\": {\n          \"@id\": \"schema:longitude\",\n          \"@type\": \"xsd:float\"\n        },\n        \"containedInPlace\": {\n          \"@id\": \"schema:containedInPlace\",\n          \"@type\": \"@id\"\n        },\n        \"hasMap\": {\n          \"@id\": \"schema:hasMap\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"brand\": {\n          \"@id\": \"schema:brand\",\n          \"@type\": \"@id\"\n        },\n        \"manufacturer\": {\n          \"@id\": \"schema:manufacturer\",\n          \"@type\": \"@id\"\n        },\n        \"model\": \"schema:model\",\n        \"sku\": \"schema:sku\",\n        \"gtin\": \"schema:gtin\",\n        \"category\": \"schema:category\",\n        \"color\": \"schema:color\",\n        \"material\": \"schema:material\",\n        \"offers\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"@id\"\n    \
  \    },\n        \"review\": {\n          \"@id\": \"schema:review\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Event\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"location\": {\n          \"@id\": \"schema:location\",\n          \"@type\": \"@id\"\n        },\n        \"organizer\": {\n          \"@id\": \"schema:organizer\",\n          \"@type\": \"@id\"\n        },\n        \"performer\": {\n          \"@id\": \"schema:performer\",\n          \"@type\": \"@id\"\n        },\n        \"eventStatus\": \"schema:eventStatus\",\n        \"eventAttendanceMode\": \"schema:eventAttendanceMode\",\n        \"offers\": {\n          \"@id\": \"schema:offers\",\n          \"@type\": \"@id\"\n        }\n      }\n   \
  \ },\n\n    \"WebAPI\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"documentation\": {\n          \"@id\": \"schema:documentation\",\n          \"@type\": \"@id\"\n        },\n        \"termsOfService\": {\n          \"@id\": \"schema:termsOfService\",\n          \"@type\": \"@id\"\n        },\n        \"provider\": {\n          \"@id\": \"schema:provider\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/schema-org/refs/heads/main/json-ld/schema-org-context.jsonld
tags:
- Schema.org
- Structured Data
- Linked Data
- JSON-LD
- Vocabulary
- SEO
- Web Standards
- RDF
- Ontology
- JSON-LD
- Linked Data
- Semantic Web
---
