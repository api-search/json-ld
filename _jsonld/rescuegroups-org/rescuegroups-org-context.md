---
api_specs:
- filename: rescuegroups-org-openapi.yml
  format: yaml
  label: RescueGroups.org API
  slug: rescuegroups-org
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/openapi/rescuegroups-org-openapi.yml
class_count: 15
classes:
- sex
- sizeGroup
- isAdoptionPending
- isAltered
- pictureCount
- videoCount
- adoptedDate
- locationCitystate
- locationState
- breeds
- colors
- patterns
- species
- orgs
- pictures
context_file: json-ld/rescuegroups-org-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-ld/rescuegroups-org-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rescuegroups Org from RescueGroups.org.
layout: jsonld
name: Rescuegroups Org Context
namespaces:
- prefix: rg
  uri: https://api.rescuegroups.org/v5/vocab/
- prefix: Animal
  uri: https://schema.org/Animal
- prefix: Organization
  uri: https://schema.org/Organization
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: image
  uri: https://schema.org/image
- prefix: birthDate
  uri: https://schema.org/birthDate
- prefix: gender
  uri: https://schema.org/gender
- prefix: email
  uri: https://schema.org/email
- prefix: telephone
  uri: https://schema.org/telephone
- prefix: address
  uri: https://schema.org/PostalAddress
- prefix: streetAddress
  uri: https://schema.org/streetAddress
- prefix: addressLocality
  uri: https://schema.org/addressLocality
- prefix: addressRegion
  uri: https://schema.org/addressRegion
- prefix: postalCode
  uri: https://schema.org/postalCode
- prefix: addressCountry
  uri: https://schema.org/addressCountry
- prefix: sameAs
  uri: https://schema.org/sameAs
- prefix: id
  uri: https://schema.org/identifier
- prefix: ageGroup
  uri: https://schema.org/ageGroup
- prefix: specialNeedsDetails
  uri: https://schema.org/additionalProperty
- prefix: descriptionText
  uri: https://schema.org/description
- prefix: rescueId
  uri: https://schema.org/identifier
- prefix: serveAreas
  uri: https://schema.org/areaServed
- prefix: adoptionUrl
  uri: https://schema.org/url
- prefix: facebookUrl
  uri: https://schema.org/sameAs
properties: []
property_count: 0
provider_name: RescueGroups.org
provider_slug: rescuegroups-org
slug: rescuegroups-org-context
source_filename: rescuegroups-org-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rg\": \"https://api.rescuegroups.org/v5/vocab/\",\n    \"Animal\": \"https://schema.org/Animal\",\n    \"Organization\": \"https://schema.org/Organization\",\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\",\n    \"image\": \"https://schema.org/image\",\n    \"birthDate\": \"https://schema.org/birthDate\",\n    \"gender\": \"https://schema.org/gender\",\n    \"email\": \"https://schema.org/email\",\n    \"telephone\": \"https://schema.org/telephone\",\n    \"address\": \"https://schema.org/PostalAddress\",\n    \"streetAddress\": \"https://schema.org/streetAddress\",\n    \"addressLocality\": \"https://schema.org/addressLocality\",\n    \"addressRegion\": \"https://schema.org/addressRegion\",\n    \"postalCode\": \"https://schema.org/postalCode\",\n    \"addressCountry\": \"https://schema.org/addressCountry\",\n\
  \    \"sameAs\": \"https://schema.org/sameAs\",\n    \"id\": \"https://schema.org/identifier\",\n    \"sex\": \"rg:sex\",\n    \"ageGroup\": \"https://schema.org/ageGroup\",\n    \"sizeGroup\": \"rg:sizeGroup\",\n    \"isAdoptionPending\": \"rg:isAdoptionPending\",\n    \"isAltered\": \"rg:isAltered\",\n    \"pictureCount\": \"rg:pictureCount\",\n    \"videoCount\": \"rg:videoCount\",\n    \"adoptedDate\": \"rg:adoptedDate\",\n    \"specialNeedsDetails\": \"https://schema.org/additionalProperty\",\n    \"descriptionText\": \"https://schema.org/description\",\n    \"locationCitystate\": \"rg:locationCitystate\",\n    \"locationState\": \"rg:locationState\",\n    \"rescueId\": \"https://schema.org/identifier\",\n    \"serveAreas\": \"https://schema.org/areaServed\",\n    \"adoptionUrl\": \"https://schema.org/url\",\n    \"facebookUrl\": \"https://schema.org/sameAs\",\n    \"breeds\": \"rg:breeds\",\n    \"colors\": \"rg:colors\",\n    \"patterns\": \"rg:patterns\",\n    \"species\": \"rg:species\"\
  ,\n    \"orgs\": \"rg:organizations\",\n    \"pictures\": \"rg:pictures\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rescuegroups-org/refs/heads/main/json-ld/rescuegroups-org-context.jsonld
tags:
- Animals
- Pet Adoption
- Rescue
- Animal Welfare
- JSON-LD
- Linked Data
- Semantic Web
---
