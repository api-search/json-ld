---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google People API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-people/refs/heads/main/openapi/openapi.yml
class_count: 19
classes:
- Person
- name
- givenName
- familyName
- email
- telephone
- address
- PostalAddress
- streetAddress
- addressLocality
- addressRegion
- postalCode
- addressCountry
- worksFor
- jobTitle
- image
- birthDate
- url
- ContactPoint
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-people/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google People.
layout: jsonld
name: context Context
namespaces:
- prefix: people
  uri: https://people.googleapis.com/v1/
properties: []
property_count: 0
provider_name: Google People
provider_slug: google-people
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"people\": \"https://people.googleapis.com/v1/\",\n    \"Person\": \"schema:Person\",\n    \"name\": \"schema:name\",\n    \"givenName\": \"schema:givenName\",\n    \"familyName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"telephone\": \"schema:telephone\",\n    \"address\": \"schema:address\",\n    \"PostalAddress\": \"schema:PostalAddress\",\n    \"streetAddress\": \"schema:streetAddress\",\n    \"addressLocality\": \"schema:addressLocality\",\n    \"addressRegion\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"addressCountry\": \"schema:addressCountry\",\n    \"worksFor\": \"schema:worksFor\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"image\": \"schema:image\",\n    \"birthDate\": \"schema:birthDate\",\n    \"url\": \"schema:url\",\n    \"ContactPoint\": \"schema:ContactPoint\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-people/refs/heads/main/json-ld/context.jsonld
tags:
- Address Book
- Contacts
- Google
- People
- Profiles
- JSON-LD
- Linked Data
- Semantic Web
---
