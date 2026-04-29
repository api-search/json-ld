---
class_count: 2
classes:
- Profile
- name
context_file: json-ld/adyen-management-profile-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-profile-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Profile from Adyen.
layout: jsonld
name: Adyen Management Profile Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: authType
  type: string
- container: ''
  name: autoWifi
  type: boolean
- container: ''
  name: bssType
  type: string
- container: ''
  name: channel
  type: integer
- container: ''
  name: defaultProfile
  type: boolean
- container: ''
  name: eap
  type: string
- container: ''
  name: eapCaCert
  type: string
- container: ''
  name: eapClientCert
  type: string
- container: ''
  name: eapClientKey
  type: string
- container: ''
  name: eapClientPwd
  type: string
- container: ''
  name: eapIdentity
  type: string
- container: ''
  name: eapIntermediateCert
  type: string
- container: ''
  name: eapPwd
  type: string
- container: ''
  name: hiddenSsid
  type: boolean
- container: ''
  name: psk
  type: string
- container: ''
  name: ssid
  type: string
- container: ''
  name: wsec
  type: string
property_count: 17
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-profile-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Profile\": \"adyen:Profile\",\n    \"authType\": {\n      \"@id\": \"adyen:authType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoWifi\": {\n      \"@id\": \"adyen:autoWifi\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"bssType\": {\n      \"@id\": \"adyen:bssType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"adyen:channel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultProfile\": {\n      \"@id\": \"adyen:defaultProfile\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"eap\": {\n      \"@id\": \"adyen:eap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapCaCert\": {\n      \"@id\": \"adyen:eapCaCert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapClientCert\"\
  : {\n      \"@id\": \"adyen:eapClientCert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapClientKey\": {\n      \"@id\": \"adyen:eapClientKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapClientPwd\": {\n      \"@id\": \"adyen:eapClientPwd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapIdentity\": {\n      \"@id\": \"adyen:eapIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapIntermediateCert\": {\n      \"@id\": \"adyen:eapIntermediateCert\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eapPwd\": {\n      \"@id\": \"adyen:eapPwd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hiddenSsid\": {\n      \"@id\": \"adyen:hiddenSsid\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": \"schema:name\",\n    \"psk\": {\n      \"@id\": \"adyen:psk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssid\": {\n      \"@id\": \"adyen:ssid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wsec\": {\n      \"@id\": \"adyen:wsec\",\n      \"@type\": \"xsd:string\"\
  \n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-profile-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
