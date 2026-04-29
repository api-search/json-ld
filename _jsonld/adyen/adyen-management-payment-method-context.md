---
class_count: 3
classes:
- PaymentMethodResponse
- PaymentMethod
- PaymentMethodSetupInfo
context_file: json-ld/adyen-management-payment-method-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-payment-method-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Payment Method from Adyen.
layout: jsonld
name: Adyen Management Payment Method Context
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
  name: Links
  type: string
- container: set
  name: data
  type: string
- container: ''
  name: itemsTotal
  type: integer
- container: ''
  name: pagesTotal
  type: integer
- container: set
  name: typesWithErrors
  type: string
- container: ''
  name: afterpayTouch
  type: string
- container: ''
  name: allowed
  type: boolean
- container: ''
  name: applePay
  type: string
- container: ''
  name: bcmc
  type: string
- container: ''
  name: businessLineId
  type: string
- container: ''
  name: cartesBancaires
  type: string
- container: ''
  name: clearpay
  type: string
- container: set
  name: countries
  type: string
- container: ''
  name: cup
  type: string
- container: set
  name: currencies
  type: string
- container: set
  name: customRoutingFlags
  type: string
- container: ''
  name: diners
  type: string
- container: ''
  name: discover
  type: string
- container: ''
  name: eftposAustralia
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: giroPay
  type: string
- container: ''
  name: girocard
  type: string
- container: ''
  name: googlePay
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ideal
  type: string
- container: ''
  name: interacCard
  type: string
- container: ''
  name: jcb
  type: string
- container: ''
  name: klarna
  type: string
- container: ''
  name: maestro
  type: string
- container: ''
  name: mc
  type: string
- container: ''
  name: mealVoucherFr
  type: string
- container: ''
  name: paypal
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: shopperInteraction
  type: string
- container: ''
  name: sofort
  type: string
- container: set
  name: storeIds
  type: string
- container: ''
  name: swish
  type: string
- container: ''
  name: twint
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: verificationStatus
  type: string
- container: ''
  name: vipps
  type: string
- container: ''
  name: visa
  type: string
property_count: 42
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-payment-method-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentMethodResponse\": \"adyen:PaymentMethodResponse\",\n    \"PaymentMethod\": \"adyen:PaymentMethod\",\n    \"PaymentMethodSetupInfo\": \"adyen:PaymentMethodSetupInfo\",\n    \"Links\": {\n      \"@id\": \"adyen:_links\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemsTotal\": {\n      \"@id\": \"adyen:itemsTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pagesTotal\": {\n      \"@id\": \"adyen:pagesTotal\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"typesWithErrors\": {\n      \"@id\": \"adyen:typesWithErrors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"afterpayTouch\": {\n      \"@id\": \"adyen:afterpayTouch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed\": {\n      \"@id\": \"adyen:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applePay\": {\n      \"@id\": \"adyen:applePay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bcmc\": {\n      \"@id\": \"adyen:bcmc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"businessLineId\": {\n      \"@id\": \"adyen:businessLineId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cartesBancaires\": {\n      \"@id\": \"adyen:cartesBancaires\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clearpay\": {\n      \"@id\": \"adyen:clearpay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countries\": {\n      \"@id\": \"adyen:countries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cup\": {\n      \"@id\": \"adyen:cup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencies\": {\n      \"@id\": \"adyen:currencies\",\n   \
  \   \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customRoutingFlags\": {\n      \"@id\": \"adyen:customRoutingFlags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diners\": {\n      \"@id\": \"adyen:diners\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discover\": {\n      \"@id\": \"adyen:discover\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eftposAustralia\": {\n      \"@id\": \"adyen:eftpos_australia\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"giroPay\": {\n      \"@id\": \"adyen:giroPay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"girocard\": {\n      \"@id\": \"adyen:girocard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"googlePay\": {\n      \"@id\": \"adyen:googlePay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"ideal\": {\n      \"@id\": \"adyen:ideal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interacCard\": {\n      \"@id\": \"adyen:interac_card\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jcb\": {\n      \"@id\": \"adyen:jcb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"klarna\": {\n      \"@id\": \"adyen:klarna\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maestro\": {\n      \"@id\": \"adyen:maestro\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mc\": {\n      \"@id\": \"adyen:mc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mealVoucherFr\": {\n      \"@id\": \"adyen:mealVoucher_FR\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paypal\": {\n      \"@id\": \"adyen:paypal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInteraction\": {\n      \"@id\": \"adyen:shopperInteraction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sofort\"\
  : {\n      \"@id\": \"adyen:sofort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storeIds\": {\n      \"@id\": \"adyen:storeIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"swish\": {\n      \"@id\": \"adyen:swish\",\n      \"@type\": \"xsd:string\"\n    },\n    \"twint\": {\n      \"@id\": \"adyen:twint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"verificationStatus\": {\n      \"@id\": \"adyen:verificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vipps\": {\n      \"@id\": \"adyen:vipps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visa\": {\n      \"@id\": \"adyen:visa\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-payment-method-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
