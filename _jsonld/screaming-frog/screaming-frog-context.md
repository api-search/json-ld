---
class_count: 20
classes:
- url
- status_code
- status
- title
- title_length
- meta_description
- meta_description_length
- h1
- word_count
- content_type
- size
- indexability
- canonical_url
- redirect_url
- inlinks
- outlinks
- crawl_depth
- response_time
- CrawlResult
- SEOAudit
context_file: json-ld/screaming-frog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/json-ld/screaming-frog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Screaming Frog from Screaming Frog.
layout: jsonld
name: Screaming Frog Context
namespaces:
- prefix: seo
  uri: https://raw.githubusercontent.com/api-evangelist/screaming-frog/main/vocabulary/
properties: []
property_count: 0
provider_name: Screaming Frog
provider_slug: screaming-frog
slug: screaming-frog-context
source_filename: screaming-frog-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"seo\": \"https://raw.githubusercontent.com/api-evangelist/screaming-frog/main/vocabulary/\",\n    \"url\": \"url\",\n    \"status_code\": \"seo:statusCode\",\n    \"status\": \"seo:httpStatus\",\n    \"title\": \"name\",\n    \"title_length\": \"seo:titleLength\",\n    \"meta_description\": \"description\",\n    \"meta_description_length\": \"seo:descriptionLength\",\n    \"h1\": \"headline\",\n    \"word_count\": \"wordCount\",\n    \"content_type\": \"encodingFormat\",\n    \"size\": \"contentSize\",\n    \"indexability\": \"seo:indexability\",\n    \"canonical_url\": \"sameAs\",\n    \"redirect_url\": \"seo:redirectUrl\",\n    \"inlinks\": \"seo:inlinks\",\n    \"outlinks\": \"seo:outlinks\",\n    \"crawl_depth\": \"seo:crawlDepth\",\n    \"response_time\": \"seo:responseTime\",\n    \"CrawlResult\": \"WebPage\",\n    \"SEOAudit\": \"Report\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/json-ld/screaming-frog-context.jsonld
tags:
- SEO
- Search Engine Optimization
- Website Crawler
- Technical Audit
- Marketing
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
