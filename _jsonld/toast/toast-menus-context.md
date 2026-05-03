---
api_specs:
- filename: toast-orders-openapi.yaml
  format: yaml
  label: Toast Orders API
  slug: toast-orders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-orders-openapi.yaml
- filename: toast-menus-openapi.yaml
  format: yaml
  label: Toast Menus API
  slug: toast-menus
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-menus-openapi.yaml
- filename: toast-labor-openapi.yaml
  format: yaml
  label: Toast Labor API
  slug: toast-labor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-labor-openapi.yaml
- filename: toast-restaurants-openapi.yaml
  format: yaml
  label: Toast Restaurants API
  slug: toast-restaurants
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-restaurants-openapi.yaml
- filename: toast-stock-openapi.yaml
  format: yaml
  label: Toast Stock API
  slug: toast-stock
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-stock-openapi.yaml
- filename: toast-partners-openapi.yaml
  format: yaml
  label: Toast Partners API
  slug: toast-partners
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-partners-openapi.yaml
- filename: toast-authentication-openapi.yaml
  format: yaml
  label: Toast Authentication API
  slug: toast-authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/openapi/toast-authentication-openapi.yaml
class_count: 29
classes:
- Alcohol
- AllergenItem
- Availability
- CatalogProduct
- CatalogProductInfo
- CatalogProductOption
- CatalogProductOptionValue
- CatalogProductVariant
- CatalogProductVariantOption
- ContentAdvisories
- ItemTag
- Menu
- MenuGroup
- MenuItem
- Metadata
- ModifierGroup
- ModifierOption
- ModifierOptionTaxInfo
- Portion
- PreModifier
- PreModifierGroup
- PricingRules
- Restaurant
- SalesCategory
- Schedule
- SequencePrice
- SizeSequencePricingRule
- TimeRange
- TimeSpecificPrice
context_file: json-ld/toast-menus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-menus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toast Menus from Toast.
layout: jsonld
name: Toast Menus Context
namespaces:
- prefix: toast
  uri: https://developer.toasttab.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: alcohol
  type: string
- container: set
  name: allergens
  type: string
- container: ''
  name: allowsDuplicates
  type: boolean
- container: ''
  name: alwaysAvailable
  type: boolean
- container: ''
  name: availability
  type: reference
- container: set
  name: availableOptions
  type: string
- container: ''
  name: basePrice
  type: decimal
- container: ''
  name: calories
  type: integer
- container: ''
  name: catalogProductInfo
  type: string
- container: ''
  name: chargeAsExtra
  type: boolean
- container: ''
  name: code
  type: string
- container: ''
  name: containsAlcohol
  type: string
- container: ''
  name: contentAdvisories
  type: string
- container: set
  name: days
  type: string
- container: ''
  name: defaultOptionsChargePrice
  type: string
- container: ''
  name: defaultOptionsSubstitutionPricing
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: dimensionUnitOfMeasure
  type: string
- container: ''
  name: displayMode
  type: string
- container: set
  name: eligiblePaymentAssistancePrograms
  type: string
- container: ''
  name: end
  type: string
- container: ''
  name: fixedPrice
  type: decimal
- container: ''
  name: groupCode
  type: string
- container: ''
  name: groupGuid
  type: string
- container: ''
  name: guestCount
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: height
  type: string
- container: ''
  name: highResImage
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: images
  type: string
- container: ''
  name: isComboParent
  type: boolean
- container: ''
  name: isDefault
  type: boolean
- container: ''
  name: isDeferred
  type: boolean
- container: ''
  name: isDiscountable
  type: boolean
- container: ''
  name: isMultiSelect
  type: boolean
- container: set
  name: itemTags
  type: string
- container: ''
  name: kitchenName
  type: string
- container: ''
  name: lastUpdated
  type: string
- container: ''
  name: length
  type: string
- container: ''
  name: masterId
  type: string
- container: ''
  name: maxSelections
  type: integer
- container: set
  name: menuGroups
  type: string
- container: set
  name: menuItems
  type: string
- container: set
  name: menus
  type: string
- container: ''
  name: minSelections
  type: integer
- container: set
  name: modifierGroupReferences
  type: integer
- container: ''
  name: modifierOptionReferences
  type: string
- container: ''
  name: modifierOptionTaxInfo
  type: string
- container: ''
  name: multiLocationId
  type: string
- container: ''
  name: multiplicationFactor
  type: decimal
- container: ''
  name: name
  type: ''
- container: ''
  name: overrideItemTaxRates
  type: boolean
- container: ''
  name: plu
  type: string
- container: set
  name: portions
  type: string
- container: ''
  name: posButtonColorDark
  type: string
- container: ''
  name: posButtonColorLight
  type: string
- container: ''
  name: posName
  type: string
- container: ''
  name: preModifierGroupReference
  type: integer
- container: ''
  name: preModifierGroupReferences
  type: string
- container: set
  name: preModifiers
  type: string
- container: set
  name: prepStations
  type: string
- container: ''
  name: prepTime
  type: integer
- container: ''
  name: presenceType
  type: string
- container: ''
  name: price
  type: decimal
- container: ''
  name: priceScaleFactor
  type: decimal
- container: ''
  name: pricingRules
  type: reference
- container: ''
  name: pricingStrategy
  type: string
- container: ''
  name: product
  type: string
- container: ''
  name: productVariant
  type: string
- container: ''
  name: referenceId
  type: integer
- container: ''
  name: requiredMode
  type: string
- container: ''
  name: restaurantGuid
  type: string
- container: ''
  name: restaurantTimeZone
  type: string
- container: ''
  name: salesCategory
  type: string
- container: set
  name: schedule
  type: string
- container: set
  name: selectedOptions
  type: string
- container: ''
  name: sequence
  type: integer
- container: set
  name: sequencePrices
  type: string
- container: ''
  name: sizeGuid
  type: string
- container: ''
  name: sizeName
  type: string
- container: set
  name: sizeSequencePricingRules
  type: string
- container: ''
  name: sizeSpecificPricingGuid
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: sortOrder
  type: integer
- container: ''
  name: start
  type: string
- container: ''
  name: taxInclusion
  type: string
- container: set
  name: taxInfo
  type: string
- container: set
  name: taxRateGuids
  type: string
- container: set
  name: timeRanges
  type: string
- container: ''
  name: timeSpecificPrice
  type: decimal
- container: set
  name: timeSpecificPricingRules
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: unitOfMeasure
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: visibility
  type: string
- container: ''
  name: weight
  type: string
- container: ''
  name: weightUnitOfMeasure
  type: string
- container: ''
  name: width
  type: string
property_count: 100
provider_name: Toast
provider_slug: toast
slug: toast-menus-context
source_filename: toast-menus-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toast\": \"https://developer.toasttab.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Alcohol\": \"toast:Alcohol\",\n    \"AllergenItem\": \"toast:AllergenItem\",\n    \"Availability\": \"toast:Availability\",\n    \"CatalogProduct\": \"toast:CatalogProduct\",\n    \"CatalogProductInfo\": \"toast:CatalogProductInfo\",\n    \"CatalogProductOption\": \"toast:CatalogProductOption\",\n    \"CatalogProductOptionValue\": \"toast:CatalogProductOptionValue\",\n    \"CatalogProductVariant\": \"toast:CatalogProductVariant\",\n    \"CatalogProductVariantOption\": \"toast:CatalogProductVariantOption\",\n    \"ContentAdvisories\": \"toast:ContentAdvisories\",\n    \"ItemTag\": \"toast:ItemTag\",\n    \"Menu\": \"toast:Menu\",\n    \"MenuGroup\": \"toast:MenuGroup\",\n    \"MenuItem\": \"toast:MenuItem\",\n    \"Metadata\"\
  : \"toast:Metadata\",\n    \"ModifierGroup\": \"toast:ModifierGroup\",\n    \"ModifierOption\": \"toast:ModifierOption\",\n    \"ModifierOptionTaxInfo\": \"toast:ModifierOptionTaxInfo\",\n    \"Portion\": \"toast:Portion\",\n    \"PreModifier\": \"toast:PreModifier\",\n    \"PreModifierGroup\": \"toast:PreModifierGroup\",\n    \"PricingRules\": \"toast:PricingRules\",\n    \"Restaurant\": \"toast:Restaurant\",\n    \"SalesCategory\": \"toast:SalesCategory\",\n    \"Schedule\": \"toast:Schedule\",\n    \"SequencePrice\": \"toast:SequencePrice\",\n    \"SizeSequencePricingRule\": \"toast:SizeSequencePricingRule\",\n    \"TimeRange\": \"toast:TimeRange\",\n    \"TimeSpecificPrice\": \"toast:TimeSpecificPrice\",\n    \"alcohol\": {\n      \"@id\": \"toast:alcohol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allergens\": {\n      \"@id\": \"toast:allergens\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowsDuplicates\": {\n      \"@id\": \"toast:allowsDuplicates\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"alwaysAvailable\": {\n      \"@id\": \"toast:alwaysAvailable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"availability\": {\n      \"@id\": \"toast:availability\",\n      \"@type\": \"@id\"\n    },\n    \"availableOptions\": {\n      \"@id\": \"toast:availableOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basePrice\": {\n      \"@id\": \"toast:basePrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"calories\": {\n      \"@id\": \"toast:calories\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"catalogProductInfo\": {\n      \"@id\": \"toast:catalogProductInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chargeAsExtra\": {\n      \"@id\": \"toast:chargeAsExtra\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"code\": {\n      \"@id\": \"toast:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containsAlcohol\": {\n      \"@id\": \"toast:containsAlcohol\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"contentAdvisories\": {\n      \"@id\": \"toast:contentAdvisories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"days\": {\n      \"@id\": \"toast:days\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultOptionsChargePrice\": {\n      \"@id\": \"toast:defaultOptionsChargePrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultOptionsSubstitutionPricing\": {\n      \"@id\": \"toast:defaultOptionsSubstitutionPricing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dimensionUnitOfMeasure\": {\n      \"@id\": \"toast:dimensionUnitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayMode\": {\n      \"@id\": \"toast:displayMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eligiblePaymentAssistancePrograms\": {\n      \"@id\": \"toast:eligiblePaymentAssistancePrograms\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"toast:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixedPrice\": {\n      \"@id\": \"toast:fixedPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"groupCode\": {\n      \"@id\": \"toast:groupCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupGuid\": {\n      \"@id\": \"toast:groupGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guestCount\": {\n      \"@id\": \"toast:guestCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guid\": {\n      \"@id\": \"toast:guid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"height\": {\n      \"@id\": \"toast:height\",\n      \"@type\": \"xsd:string\"\n    },\n    \"highResImage\": {\n      \"@id\": \"toast:highResImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"toast:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"toast:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  images\": {\n      \"@id\": \"toast:images\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isComboParent\": {\n      \"@id\": \"toast:isComboParent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDefault\": {\n      \"@id\": \"toast:isDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDeferred\": {\n      \"@id\": \"toast:isDeferred\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDiscountable\": {\n      \"@id\": \"toast:isDiscountable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isMultiSelect\": {\n      \"@id\": \"toast:isMultiSelect\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"itemTags\": {\n      \"@id\": \"toast:itemTags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kitchenName\": {\n      \"@id\": \"toast:kitchenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"toast:lastUpdated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"toast:length\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"masterId\": {\n      \"@id\": \"toast:masterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxSelections\": {\n      \"@id\": \"toast:maxSelections\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"menuGroups\": {\n      \"@id\": \"toast:menuGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"menuItems\": {\n      \"@id\": \"toast:menuItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"menus\": {\n      \"@id\": \"toast:menus\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minSelections\": {\n      \"@id\": \"toast:minSelections\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modifierGroupReferences\": {\n      \"@id\": \"toast:modifierGroupReferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modifierOptionReferences\": {\n      \"@id\": \"toast:modifierOptionReferences\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"modifierOptionTaxInfo\": {\n      \"@id\": \"toast:modifierOptionTaxInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiLocationId\": {\n      \"@id\": \"toast:multiLocationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"multiplicationFactor\": {\n      \"@id\": \"toast:multiplicationFactor\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"overrideItemTaxRates\": {\n      \"@id\": \"toast:overrideItemTaxRates\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"plu\": {\n      \"@id\": \"toast:plu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portions\": {\n      \"@id\": \"toast:portions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"posButtonColorDark\": {\n      \"@id\": \"toast:posButtonColorDark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"posButtonColorLight\": {\n      \"@id\": \"toast:posButtonColorLight\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"posName\": {\n      \"@id\": \"toast:posName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preModifierGroupReference\": {\n      \"@id\": \"toast:preModifierGroupReference\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"preModifierGroupReferences\": {\n      \"@id\": \"toast:preModifierGroupReferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preModifiers\": {\n      \"@id\": \"toast:preModifiers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prepStations\": {\n      \"@id\": \"toast:prepStations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prepTime\": {\n      \"@id\": \"toast:prepTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"presenceType\": {\n      \"@id\": \"toast:presenceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"price\": {\n      \"@id\": \"toast:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"priceScaleFactor\"\
  : {\n      \"@id\": \"toast:priceScaleFactor\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"pricingRules\": {\n      \"@id\": \"toast:pricingRules\",\n      \"@type\": \"@id\"\n    },\n    \"pricingStrategy\": {\n      \"@id\": \"toast:pricingStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"product\": {\n      \"@id\": \"toast:product\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productVariant\": {\n      \"@id\": \"toast:productVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceId\": {\n      \"@id\": \"toast:referenceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"requiredMode\": {\n      \"@id\": \"toast:requiredMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restaurantGuid\": {\n      \"@id\": \"toast:restaurantGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restaurantTimeZone\": {\n      \"@id\": \"toast:restaurantTimeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"salesCategory\": {\n      \"@id\": \"toast:salesCategory\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"toast:schedule\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectedOptions\": {\n      \"@id\": \"toast:selectedOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sequence\": {\n      \"@id\": \"toast:sequence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sequencePrices\": {\n      \"@id\": \"toast:sequencePrices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeGuid\": {\n      \"@id\": \"toast:sizeGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeName\": {\n      \"@id\": \"toast:sizeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeSequencePricingRules\": {\n      \"@id\": \"toast:sizeSequencePricingRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeSpecificPricingGuid\": {\n      \"@id\": \"toast:sizeSpecificPricingGuid\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"toast:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortOrder\": {\n      \"@id\": \"toast:sortOrder\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"start\": {\n      \"@id\": \"toast:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxInclusion\": {\n      \"@id\": \"toast:taxInclusion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxInfo\": {\n      \"@id\": \"toast:taxInfo\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxRateGuids\": {\n      \"@id\": \"toast:taxRateGuids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeRanges\": {\n      \"@id\": \"toast:timeRanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSpecificPrice\": {\n      \"@id\": \"toast:timeSpecificPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"timeSpecificPricingRules\": {\n      \"@id\"\
  : \"toast:timeSpecificPricingRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"toast:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitOfMeasure\": {\n      \"@id\": \"toast:unitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"toast:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"toast:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"visibility\": {\n      \"@id\": \"toast:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"toast:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightUnitOfMeasure\": {\n      \"@id\": \"toast:weightUnitOfMeasure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"toast:width\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toast/refs/heads/main/json-ld/toast-menus-context.jsonld
tags:
- Food Service
- Point of Sale
- Restaurants
- Hospitality
- JSON-LD
- Linked Data
- Semantic Web
---
