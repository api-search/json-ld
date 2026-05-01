---
api_specs:
- filename: contacts.yml
  format: yaml
  label: Google People API v1
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-contacts/refs/heads/main/openapi/contacts.yml
class_count: 21
classes:
- Person
- ContactGroup
- resourceName
- displayName
- givenName
- familyName
- middleName
- emailAddresses
- phoneNumbers
- addresses
- streetAddress
- city
- region
- postalCode
- country
- organizations
- title
- department
- birthdays
- photos
- biographies
context_file: json-ld/contacts.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-contacts/refs/heads/main/json-ld/contacts.jsonld
description: JSON-LD context defining the semantic vocabulary for Contacts from Google People API.
layout: jsonld
name: Contacts Context
namespaces:
- prefix: gpeople
  uri: https://people.googleapis.com/v1/
properties:
- container: ''
  name: urls
  type: reference
property_count: 1
provider_name: Google People API
provider_slug: google-contacts
slug: contacts
source_filename: contacts.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gpeople\": \"https://people.googleapis.com/v1/\",\n    \"Person\": \"schema:Person\",\n    \"ContactGroup\": \"schema:ItemList\",\n    \"resourceName\": \"schema:identifier\",\n    \"displayName\": \"schema:name\",\n    \"givenName\": \"schema:givenName\",\n    \"familyName\": \"schema:familyName\",\n    \"middleName\": \"schema:additionalName\",\n    \"emailAddresses\": \"schema:email\",\n    \"phoneNumbers\": \"schema:telephone\",\n    \"addresses\": \"schema:address\",\n    \"streetAddress\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"region\": \"schema:addressRegion\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n    \"organizations\": \"schema:worksFor\",\n    \"title\": \"schema:jobTitle\",\n    \"department\": \"schema:department\",\n    \"birthdays\": \"schema:birthDate\",\n    \"photos\": \"schema:image\",\n    \"biographies\"\
  : \"schema:description\",\n    \"urls\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-contacts/refs/heads/main/json-ld/contacts.jsonld
tags:
- Address Book
- Contacts
- Directory
- Google
- People
- Profiles
- JSON-LD
- Linked Data
- Semantic Web
---
