---
api_specs:
- filename: themealdb-openapi.yml
  format: yaml
  label: TheMealDB API
  slug: themealdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/openapi/themealdb-openapi.yml
class_count: 6
classes:
- FilterResponse
- CategoriesResponse
- MealsResponse
- Category
- ListResponse
- Meal
context_file: json-ld/themealdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/json-ld/themealdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Themealdb from TheMealDB.
layout: jsonld
name: Themealdb Context
namespaces:
- prefix: mealdb
  uri: https://www.themealdb.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: meals
  type: string
- container: ''
  name: strMeal
  type: string
- container: ''
  name: strMealThumb
  type: string
- container: ''
  name: idMeal
  type: string
- container: set
  name: categories
  type: string
- container: ''
  name: idCategory
  type: string
- container: ''
  name: strCategory
  type: string
- container: ''
  name: strCategoryThumb
  type: string
- container: ''
  name: strCategoryDescription
  type: string
- container: ''
  name: strArea
  type: string
- container: ''
  name: strInstructions
  type: string
- container: ''
  name: strTags
  type: string
- container: ''
  name: strYoutube
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
  name: strSource
  type: string
- container: ''
  name: dateModified
  type: string
property_count: 21
provider_name: TheMealDB
provider_slug: themealdb
slug: themealdb-context
source_filename: themealdb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mealdb\": \"https://www.themealdb.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"FilterResponse\": \"mealdb:FilterResponse\",\n    \"CategoriesResponse\": \"mealdb:CategoriesResponse\",\n    \"MealsResponse\": \"mealdb:MealsResponse\",\n    \"Category\": \"mealdb:Category\",\n    \"ListResponse\": \"mealdb:ListResponse\",\n    \"Meal\": \"mealdb:Meal\",\n    \"meals\": {\n      \"@id\": \"mealdb:meals\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeal\": {\n      \"@id\": \"mealdb:strMeal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMealThumb\": {\n      \"@id\": \"mealdb:strMealThumb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idMeal\": {\n      \"@id\": \"mealdb:idMeal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categories\": {\n      \"@id\"\
  : \"mealdb:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idCategory\": {\n      \"@id\": \"mealdb:idCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strCategory\": {\n      \"@id\": \"mealdb:strCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strCategoryThumb\": {\n      \"@id\": \"mealdb:strCategoryThumb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strCategoryDescription\": {\n      \"@id\": \"mealdb:strCategoryDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strArea\": {\n      \"@id\": \"mealdb:strArea\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strInstructions\": {\n      \"@id\": \"mealdb:strInstructions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strTags\": {\n      \"@id\": \"mealdb:strTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strYoutube\": {\n      \"@id\": \"mealdb:strYoutube\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient1\": {\n      \"@id\"\
  : \"mealdb:strIngredient1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient2\": {\n      \"@id\": \"mealdb:strIngredient2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strIngredient3\": {\n      \"@id\": \"mealdb:strIngredient3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure1\": {\n      \"@id\": \"mealdb:strMeasure1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure2\": {\n      \"@id\": \"mealdb:strMeasure2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strMeasure3\": {\n      \"@id\": \"mealdb:strMeasure3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"strSource\": {\n      \"@id\": \"mealdb:strSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateModified\": {\n      \"@id\": \"mealdb:dateModified\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/themealdb/refs/heads/main/json-ld/themealdb-context.jsonld
tags:
- Recipes
- Meals
- Food
- Cooking
- JSON-LD
- Linked Data
- Semantic Web
---
