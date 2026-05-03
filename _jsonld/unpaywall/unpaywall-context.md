---
api_specs:
- filename: unpaywall-openapi.yml
  format: yaml
  label: Unpaywall API
  slug: unpaywall
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/openapi/unpaywall-openapi.yml
class_count: 8
classes:
- ScholarlyArticle
- Journal
- OALocation
- Author
- title
- publisher
- given
- family
context_file: json-ld/unpaywall-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-ld/unpaywall-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unpaywall from Unpaywall.
layout: jsonld
name: Unpaywall Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bibo
  uri: http://purl.org/ontology/bibo/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: unpaywall
  uri: https://unpaywall.org/ontology#
- prefix: fabio
  uri: http://purl.org/spar/fabio/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: doi
  type: string
- container: ''
  name: doi_url
  type: anyURI
- container: ''
  name: genre
  type: string
- container: ''
  name: is_paratext
  type: boolean
- container: ''
  name: published_date
  type: string
- container: ''
  name: year
  type: integer
- container: ''
  name: journal_name
  type: string
- container: ''
  name: journal_issns
  type: string
- container: ''
  name: journal_issn_l
  type: string
- container: ''
  name: journal_is_oa
  type: boolean
- container: ''
  name: journal_is_in_doaj
  type: boolean
- container: ''
  name: is_oa
  type: boolean
- container: ''
  name: oa_status
  type: string
- container: ''
  name: has_repository_copy
  type: boolean
- container: ''
  name: best_oa_location
  type: unpaywall:OALocation
- container: ''
  name: first_oa_location
  type: unpaywall:OALocation
- container: set
  name: oa_locations
  type: ''
- container: set
  name: oa_locations_embargoed
  type: ''
- container: ''
  name: url
  type: anyURI
- container: ''
  name: url_for_pdf
  type: anyURI
- container: ''
  name: url_for_landing_page
  type: anyURI
- container: ''
  name: host_type
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: license
  type: string
- container: ''
  name: oa_date
  type: string
- container: ''
  name: is_best
  type: boolean
- container: ''
  name: endpoint_id
  type: string
- container: ''
  name: pmh_id
  type: string
- container: ''
  name: repository_institution
  type: string
- container: ''
  name: evidence
  type: string
- container: ''
  name: data_standard
  type: integer
- container: ''
  name: updated
  type: dateTime
- container: set
  name: z_authors
  type: ''
- container: ''
  name: ORCID
  type: anyURI
- container: set
  name: affiliation
  type: ''
- container: ''
  name: score
  type: float
- container: ''
  name: snippet
  type: string
property_count: 37
provider_name: Unpaywall
provider_slug: unpaywall
slug: unpaywall-context
source_filename: unpaywall-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"bibo\": \"http://purl.org/ontology/bibo/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"unpaywall\": \"https://unpaywall.org/ontology#\",\n    \"fabio\": \"http://purl.org/spar/fabio/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ScholarlyArticle\": \"schema:ScholarlyArticle\",\n    \"Journal\": \"bibo:Journal\",\n    \"OALocation\": \"unpaywall:OALocation\",\n    \"Author\": \"schema:Person\",\n\n    \"doi\": {\n      \"@id\": \"bibo:doi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"doi_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"title\": \"dcterms:title\",\n    \"genre\": {\n      \"@id\": \"dcterms:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_paratext\": {\n      \"@id\": \"unpaywall:isParatext\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"published_date\": {\n      \"@id\": \"dcterms:date\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publisher\": \"dcterms:publisher\",\n    \"journal_name\": {\n      \"@id\": \"schema:isPartOf\",\n      \"@type\": \"xsd:string\"\n    },\n    \"journal_issns\": {\n      \"@id\": \"bibo:issn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"journal_issn_l\": {\n      \"@id\": \"bibo:issn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"journal_is_oa\": {\n      \"@id\": \"unpaywall:journalIsOA\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"journal_is_in_doaj\": {\n      \"@id\": \"unpaywall:inDOAJ\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_oa\": {\n      \"@id\": \"unpaywall:isOpenAccess\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"oa_status\": {\n      \"@id\": \"unpaywall:oaStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"has_repository_copy\": {\n      \"@id\": \"unpaywall:hasRepositoryCopy\",\n \
  \     \"@type\": \"xsd:boolean\"\n    },\n    \"best_oa_location\": {\n      \"@id\": \"unpaywall:bestOALocation\",\n      \"@type\": \"unpaywall:OALocation\"\n    },\n    \"first_oa_location\": {\n      \"@id\": \"unpaywall:firstOALocation\",\n      \"@type\": \"unpaywall:OALocation\"\n    },\n    \"oa_locations\": {\n      \"@id\": \"unpaywall:oaLocations\",\n      \"@container\": \"@set\"\n    },\n    \"oa_locations_embargoed\": {\n      \"@id\": \"unpaywall:oaLocationsEmbargoed\",\n      \"@container\": \"@set\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"url_for_pdf\": {\n      \"@id\": \"fabio:hasManifestation\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"url_for_landing_page\": {\n      \"@id\": \"schema:mainEntityOfPage\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"host_type\": {\n      \"@id\": \"unpaywall:hostType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"unpaywall:version\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"license\": {\n      \"@id\": \"dcterms:license\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oa_date\": {\n      \"@id\": \"unpaywall:oaDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_best\": {\n      \"@id\": \"unpaywall:isBest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endpoint_id\": {\n      \"@id\": \"unpaywall:endpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pmh_id\": {\n      \"@id\": \"unpaywall:pmhId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository_institution\": {\n      \"@id\": \"schema:sourceOrganization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evidence\": {\n      \"@id\": \"unpaywall:evidence\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data_standard\": {\n      \"@id\": \"unpaywall:dataStandard\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updated\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"z_authors\"\
  : {\n      \"@id\": \"dcterms:creator\",\n      \"@container\": \"@set\"\n    },\n    \"given\": \"schema:givenName\",\n    \"family\": \"schema:familyName\",\n    \"ORCID\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"affiliation\": {\n      \"@id\": \"schema:affiliation\",\n      \"@container\": \"@set\"\n    },\n    \"score\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:float\"\n    },\n    \"snippet\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-ld/unpaywall-context.jsonld
tags:
- Open Access
- Scholarly Articles
- Research
- Academic
- Libraries
- DOI
- Science
- JSON-LD
- Linked Data
- Semantic Web
---
