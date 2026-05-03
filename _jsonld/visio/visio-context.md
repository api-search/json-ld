---
api_specs:
- filename: visio-javascript-openapi.yml
  format: yaml
  label: Visio JavaScript API
  slug: visio-javascript-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/openapi/visio-javascript-openapi.yml
class_count: 35
classes:
- Document
- Page
- Shape
- ShapeDataItem
- Hyperlink
- Comment
- Application
- BoundingBox
- PageView
- ShapeView
- Highlight
- id
- name
- description
- text
- author
- date
- address
- label
- value
- zoom
- showToolbars
- isBackground
- index
- select
- color
- width
- height
- x
- y
- subAddress
- extraInfo
- format
- formattedValue
- tooltip
context_file: json-ld/visio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/json-ld/visio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Visio from Microsoft Visio API.
layout: jsonld
name: Visio Context
namespaces:
- prefix: visio
  uri: https://learn.microsoft.com/en-us/javascript/api/visio/visio.
- prefix: ms
  uri: https://learn.microsoft.com/en-us/graph/
properties:
- container: ''
  name: pages
  type: visio:pagecollection
- container: ''
  name: shapes
  type: visio:shapecollection
- container: ''
  name: shapeDataItems
  type: visio:shapedataitemcollection
- container: ''
  name: hyperlinks
  type: visio:hyperlinkcollection
- container: ''
  name: comments
  type: visio:commentcollection
- container: ''
  name: boundingBox
  type: visio:boundingbox
- container: ''
  name: view
  type: ''
- container: ''
  name: highlight
  type: visio:highlight
property_count: 8
provider_name: Microsoft Visio API
provider_slug: visio
slug: visio-context
source_filename: visio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"visio\": \"https://learn.microsoft.com/en-us/javascript/api/visio/visio.\",\n    \"ms\": \"https://learn.microsoft.com/en-us/graph/\",\n\n    \"Document\": \"visio:document\",\n    \"Page\": \"visio:page\",\n    \"Shape\": \"visio:shape\",\n    \"ShapeDataItem\": \"visio:shapedataitem\",\n    \"Hyperlink\": \"visio:hyperlink\",\n    \"Comment\": \"visio:comment\",\n    \"Application\": \"visio:application\",\n    \"BoundingBox\": \"visio:boundingbox\",\n    \"PageView\": \"visio:pageview\",\n    \"ShapeView\": \"visio:shapeview\",\n    \"Highlight\": \"visio:highlight\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"text\": \"schema:text\",\n    \"author\": \"schema:author\",\n    \"date\": \"schema:dateCreated\",\n    \"address\": \"schema:url\",\n    \"label\": \"schema:name\",\n    \"value\": \"schema:value\",\n\n    \"pages\": {\n      \"\
  @id\": \"visio:document.pages\",\n      \"@type\": \"visio:pagecollection\"\n    },\n    \"shapes\": {\n      \"@id\": \"visio:page.shapes\",\n      \"@type\": \"visio:shapecollection\"\n    },\n    \"shapeDataItems\": {\n      \"@id\": \"visio:shape.shapedataitems\",\n      \"@type\": \"visio:shapedataitemcollection\"\n    },\n    \"hyperlinks\": {\n      \"@id\": \"visio:shape.hyperlinks\",\n      \"@type\": \"visio:hyperlinkcollection\"\n    },\n    \"comments\": {\n      \"@id\": \"visio:shape.comments\",\n      \"@type\": \"visio:commentcollection\"\n    },\n    \"boundingBox\": {\n      \"@id\": \"visio:shape.boundingbox\",\n      \"@type\": \"visio:boundingbox\"\n    },\n    \"view\": {\n      \"@id\": \"visio:view\"\n    },\n    \"highlight\": {\n      \"@id\": \"visio:shapeview.highlight\",\n      \"@type\": \"visio:highlight\"\n    },\n    \"zoom\": \"visio:pageview.zoom\",\n    \"showToolbars\": \"visio:application.showtoolbars\",\n    \"isBackground\": \"visio:page.isbackground\"\
  ,\n    \"index\": \"visio:page.index\",\n    \"select\": \"visio:shape.select\",\n    \"color\": \"schema:color\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"x\": \"visio:boundingbox.x\",\n    \"y\": \"visio:boundingbox.y\",\n    \"subAddress\": \"visio:hyperlink.subaddress\",\n    \"extraInfo\": \"visio:hyperlink.extrainfo\",\n    \"format\": \"visio:shapedataitem.format\",\n    \"formattedValue\": \"visio:shapedataitem.formattedvalue\",\n    \"tooltip\": \"visio:shapeview.tooltip\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/visio/refs/heads/main/json-ld/visio-context.jsonld
tags:
- Business Process
- Collaboration
- Diagrams
- Enterprise
- Flowcharts
- Microsoft 365
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
