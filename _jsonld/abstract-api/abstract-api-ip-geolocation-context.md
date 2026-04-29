---
class_count: 5
classes:
- CurrencyInfo
- FlagInfo
- IPGeolocationResponse
- SecurityInfo
- TimezoneInfo
context_file: json-ld/abstract-api-ip-geolocation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-ip-geolocation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Abstract Api Ip Geolocation from Abstract API.
layout: jsonld
name: Abstract Api Ip Geolocation Context
namespaces:
- prefix: abstract
  uri: https://abstractapi.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: currencyName
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: emoji
  type: string
- container: ''
  name: unicode
  type: string
- container: ''
  name: png
  type: reference
- container: ''
  name: svg
  type: reference
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: cityGeonameId
  type: integer
- container: ''
  name: region
  type: string
- container: ''
  name: regionIsoCode
  type: string
- container: ''
  name: regionGeonameId
  type: integer
- container: ''
  name: postalCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: countryGeonameId
  type: integer
- container: ''
  name: countryIsEu
  type: boolean
- container: ''
  name: continent
  type: string
- container: ''
  name: continentCode
  type: string
- container: ''
  name: continentGeonameId
  type: integer
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: security
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: flag
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: isVpn
  type: boolean
- container: ''
  name: name
  type: ''
- container: ''
  name: abbreviation
  type: string
- container: ''
  name: gmtOffset
  type: integer
- container: ''
  name: currentTime
  type: string
- container: ''
  name: isDst
  type: boolean
property_count: 32
provider_name: Abstract API
provider_slug: abstract-api
slug: abstract-api-ip-geolocation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abstract\": \"https://abstractapi.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CurrencyInfo\": \"abstract:CurrencyInfo\",\n    \"FlagInfo\": \"abstract:FlagInfo\",\n    \"IPGeolocationResponse\": \"abstract:IPGeolocationResponse\",\n    \"SecurityInfo\": \"abstract:SecurityInfo\",\n    \"TimezoneInfo\": \"abstract:TimezoneInfo\",\n    \"currencyName\": {\n      \"@id\": \"abstract:currency_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"abstract:currency_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emoji\": {\n      \"@id\": \"abstract:emoji\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unicode\": {\n      \"@id\": \"abstract:unicode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"png\": {\n      \"@id\": \"abstract:png\",\n      \"@type\": \"\
  @id\"\n    },\n    \"svg\": {\n      \"@id\": \"abstract:svg\",\n      \"@type\": \"@id\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"abstract:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"abstract:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityGeonameId\": {\n      \"@id\": \"abstract:city_geoname_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"region\": {\n      \"@id\": \"abstract:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionIsoCode\": {\n      \"@id\": \"abstract:region_iso_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionGeonameId\": {\n      \"@id\": \"abstract:region_geoname_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"postalCode\": {\n      \"@id\": \"abstract:postal_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"abstract:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"abstract:country_code\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"countryGeonameId\": {\n      \"@id\": \"abstract:country_geoname_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countryIsEu\": {\n      \"@id\": \"abstract:country_is_eu\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"continent\": {\n      \"@id\": \"abstract:continent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"continentCode\": {\n      \"@id\": \"abstract:continent_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"continentGeonameId\": {\n      \"@id\": \"abstract:continent_geoname_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"longitude\": {\n      \"@id\": \"abstract:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"latitude\": {\n      \"@id\": \"abstract:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"security\": {\n      \"@id\": \"abstract:security\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"abstract:timezone\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"flag\": {\n      \"@id\": \"abstract:flag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"abstract:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isVpn\": {\n      \"@id\": \"abstract:is_vpn\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"abbreviation\": {\n      \"@id\": \"abstract:abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gmtOffset\": {\n      \"@id\": \"abstract:gmt_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentTime\": {\n      \"@id\": \"abstract:current_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDst\": {\n      \"@id\": \"abstract:is_dst\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/abstract-api/refs/heads/main/json-ld/abstract-api-ip-geolocation-context.jsonld
tags:
- Avatars
- Company Enrichment
- Contacts
- Currencies
- Email Validation
- Exchange Rates
- IBAN Validation
- Image Processing
- IP Geolocation
- IP Intelligence
- Phone Validation
- Public Holidays
- Screenshots
- Timezones
- VAT Validation
- Web Scraping
- JSON-LD
- Linked Data
- Semantic Web
---
