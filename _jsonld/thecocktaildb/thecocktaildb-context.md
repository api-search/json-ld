---
api_specs:
- filename: thecocktaildb-openapi.yml
  format: yaml
  label: TheCocktailDB API
  slug: thecocktaildb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/openapi/thecocktaildb-openapi.yml
class_count: 4
classes:
- Drink
- ListResponse
- FilterResponse
- CocktailsResponse
context_file: json-ld/thecocktaildb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/json-ld/thecocktaildb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thecocktaildb from TheCocktailDB.
layout: jsonld
name: Thecocktaildb Context
namespaces:
- prefix: cocktaildb
  uri: https://www.thecocktaildb.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: idDrink
  type: string
- container: ''
  name: strDrink
  type: string
- container: ''
  name: strDrinkAlternate
  type: string
- container: ''
  name: strTags
  type: string
- container: ''
  name: strVideo
  type: string
- container: ''
  name: strCategory
  type: string
- container: ''
  name: strIBA
  type: string
- container: ''
  name: strAlcoholic
  type: string
- container: ''
  name: strGlass
  type: string
- container: ''
  name: strInstructions
  type: string
- container: ''
  name: strInstructionsES
  type: string
- container: ''
  name: strInstructionsDE
  type: string
- container: ''
  name: strInstructionsFR
  type: string
- container: ''
  name: strInstructionsIT
  type: string
- container: ''
  name: strDrinkThumb
  type: string
- container: ''
  name: strIngredient1
  type: string
- container: ''
  name: strIngredient2
  type: string
- container: ''
  name: strIngredient3
  type: string
- container: ''
  name: strMeasure1
  type: string
- container: ''
  name: strMeasure2
  type: string
- container: ''
  name: strMeasure3
  type: string
- container: ''
  name: strImageSource
  type: string
- container: ''
  name: strImageAttribution
  type: string
- container: ''
  name: strCreativeCommonsConfirmed
  type: string
- container: ''
  name: dateModified
  type: string
- container: set
  name: drinks
  type: string
property_count: 26
provider_name: TheCocktailDB
provider_slug: thecocktaildb
slug: thecocktaildb-context
source_filename: thecocktaildb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cocktaildb\": \"https://www.thecocktaildb.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Drink\": \"cocktaildb:Drink\",\n    \"ListResponse\": \"cocktaildb:ListResponse\",\n    \"FilterResponse\": \"cocktaildb:FilterResponse\",\n    \"CocktailsResponse\": \"cocktaildb:CocktailsResponse\",\n    \"idDrink\": {\n      \"@id\": \"cocktaildb:idDrink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strDrink\": {\n      \"@id\": \"cocktaildb:strDrink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strDrinkAlternate\": {\n      \"@id\": \"cocktaildb:strDrinkAlternate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strTags\": {\n      \"@id\": \"cocktaildb:strTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strVideo\": {\n      \"@id\": \"cocktaildb:strVideo\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"strCategory\": {\n      \"@id\": \"cocktaildb:strCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIBA\": {\n      \"@id\": \"cocktaildb:strIBA\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strAlcoholic\": {\n      \"@id\": \"cocktaildb:strAlcoholic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strGlass\": {\n      \"@id\": \"cocktaildb:strGlass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructions\": {\n      \"@id\": \"cocktaildb:strInstructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructionsES\": {\n      \"@id\": \"cocktaildb:strInstructionsES\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructionsDE\": {\n      \"@id\": \"cocktaildb:strInstructionsDE\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructionsFR\": {\n      \"@id\": \"cocktaildb:strInstructionsFR\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructionsIT\": {\n      \"@id\": \"cocktaildb:strInstructionsIT\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"strDrinkThumb\": {\n      \"@id\": \"cocktaildb:strDrinkThumb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient1\": {\n      \"@id\": \"cocktaildb:strIngredient1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient2\": {\n      \"@id\": \"cocktaildb:strIngredient2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient3\": {\n      \"@id\": \"cocktaildb:strIngredient3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure1\": {\n      \"@id\": \"cocktaildb:strMeasure1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure2\": {\n      \"@id\": \"cocktaildb:strMeasure2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure3\": {\n      \"@id\": \"cocktaildb:strMeasure3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strImageSource\": {\n      \"@id\": \"cocktaildb:strImageSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strImageAttribution\": {\n      \"@id\": \"cocktaildb:strImageAttribution\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"strCreativeCommonsConfirmed\": {\n      \"@id\": \"cocktaildb:strCreativeCommonsConfirmed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateModified\": {\n      \"@id\": \"cocktaildb:dateModified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"drinks\": {\n      \"@id\": \"cocktaildb:drinks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thecocktaildb/refs/heads/main/json-ld/thecocktaildb-context.jsonld
tags:
- Cocktails
- Drinks
- Recipes
- Food And Beverage
- JSON-LD
- Linked Data
- Semantic Web
---
