---
api_specs:
- filename: telefonica-number-verification-openapi.yml
  format: yaml
  label: Telefónica Number Verification API
  slug: number-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-number-verification-openapi.yml
- filename: telefonica-sim-swap-openapi.yml
  format: yaml
  label: Telefónica SIM Swap API
  slug: sim-swap-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-sim-swap-openapi.yml
- filename: telefonica-kyc-match-openapi.yml
  format: yaml
  label: Telefónica Know Your Customer Match API
  slug: kyc-match-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-kyc-match-openapi.yml
- filename: telefonica-location-verification-openapi.yml
  format: yaml
  label: Telefónica Location Verification API
  slug: location-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-location-verification-openapi.yml
- filename: telefonica-quality-on-demand-openapi.yml
  format: yaml
  label: Telefónica Quality on Demand API
  slug: quality-on-demand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-quality-on-demand-openapi.yml
- filename: telefonica-device-roaming-openapi.yml
  format: yaml
  label: Telefónica Device Roaming Status API
  slug: device-roaming-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/openapi/telefonica-device-roaming-openapi.yml
class_count: 38
classes:
- Device
- phoneNumber
- networkAccessIdentifier
- ipv4Address
- ipv6Address
- NumberVerificationRequest
- devicePhoneNumberVerified
- SimSwapCheckRequest
- swapped
- latestSimChange
- maxAge
- KycMatchRequest
- givenName
- familyName
- birthdate
- email
- address
- postalCode
- country
- LocationVerificationRequest
- verificationResult
- area
- areaType
- center
- latitude
- longitude
- radius
- QodSession
- sessionId
- qosProfile
- qosStatus
- startedAt
- expiresAt
- duration
- RoamingStatusResponse
- roaming
- countryCode
- countryName
context_file: json-ld/telefonica-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/json-ld/telefonica-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Telefonica from Telefónica.
layout: jsonld
name: Telefonica Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: camara
  uri: https://camaraproject.org/
- prefix: telefonica
  uri: https://opengateway.telefonica.com/
properties: []
property_count: 0
provider_name: Telefónica
provider_slug: telefonica
slug: telefonica-context
source_filename: telefonica-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"camara\": \"https://camaraproject.org/\",\n    \"telefonica\": \"https://opengateway.telefonica.com/\",\n\n    \"Device\": \"schema:Device\",\n    \"phoneNumber\": \"schema:telephone\",\n    \"networkAccessIdentifier\": \"camara:networkAccessIdentifier\",\n    \"ipv4Address\": \"schema:ipAddressFamily\",\n    \"ipv6Address\": \"schema:ipAddressFamily\",\n\n    \"NumberVerificationRequest\": \"camara:NumberVerificationRequest\",\n    \"devicePhoneNumberVerified\": \"camara:devicePhoneNumberVerified\",\n\n    \"SimSwapCheckRequest\": \"camara:SimSwapCheckRequest\",\n    \"swapped\": \"camara:swapped\",\n    \"latestSimChange\": \"schema:dateModified\",\n    \"maxAge\": \"camara:maxAge\",\n\n    \"KycMatchRequest\": \"schema:CheckAction\",\n    \"givenName\": \"schema:givenName\",\n    \"familyName\": \"schema:familyName\",\n    \"birthdate\": \"schema:birthDate\",\n    \"email\": \"\
  schema:email\",\n    \"address\": \"schema:address\",\n    \"postalCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\",\n\n    \"LocationVerificationRequest\": \"camara:LocationVerificationRequest\",\n    \"verificationResult\": \"camara:verificationResult\",\n    \"area\": \"schema:spatialCoverage\",\n    \"areaType\": \"camara:areaType\",\n    \"center\": \"schema:GeoCoordinates\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"radius\": \"schema:geoRadius\",\n\n    \"QodSession\": \"schema:Event\",\n    \"sessionId\": \"schema:identifier\",\n    \"qosProfile\": \"camara:qosProfile\",\n    \"qosStatus\": \"schema:status\",\n    \"startedAt\": \"schema:startDate\",\n    \"expiresAt\": \"schema:endDate\",\n    \"duration\": \"schema:duration\",\n\n    \"RoamingStatusResponse\": \"camara:RoamingStatusResponse\",\n    \"roaming\": \"camara:roaming\",\n    \"countryCode\": \"schema:addressCountry\",\n    \"countryName\": \"\
  schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/telefonica/refs/heads/main/json-ld/telefonica-context.jsonld
tags:
- Telecommunications
- Mobile Network
- CAMARA
- Open Gateway
- Authentication
- Fraud Prevention
- Location Services
- JSON-LD
- Linked Data
- Semantic Web
---
