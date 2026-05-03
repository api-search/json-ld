---
api_specs:
- filename: web-of-science-starter-openapi.yml
  format: yaml
  label: Web of Science Starter API
  slug: web-of-science-starter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/openapi/web-of-science-starter-openapi.yml
- filename: web-of-science-expanded-openapi.yml
  format: yaml
  label: Web of Science API Expanded
  slug: web-of-science-expanded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/openapi/web-of-science-expanded-openapi.yml
class_count: 0
classes: []
context_file: json-ld/web-of-science-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/json-ld/web-of-science-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Web Of Science from Web of Science APIs.
layout: jsonld
name: Web Of Science Context
namespaces:
- prefix: wos
  uri: https://clarivate.com/webofsciencegroup/solutions/web-of-science/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: DocumentSource
  type: reference
- container: ''
  name: sourceTitle
  type: string
- container: ''
  name: publishYear
  type: integer
- container: ''
  name: publishMonth
  type: string
- container: ''
  name: volume
  type: string
- container: ''
  name: issue
  type: string
- container: ''
  name: pages
  type: ''
- container: ''
  name: articleNumber
  type: string
- container: ''
  name: supplement
  type: string
- container: ''
  name: ErrorResponse
  type: reference
- container: ''
  name: code
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: StaticData
  type: reference
- container: ''
  name: summary
  type: ''
- container: ''
  name: fullrecord_metadata
  type: ''
- container: ''
  name: Journal
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: issn
  type: string
- container: ''
  name: eissn
  type: string
- container: ''
  name: publisher
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: openAccess
  type: ''
- container: ''
  name: categories
  type: ''
- container: ''
  name: jcrProfile
  type: anyURI
- container: ''
  name: links
  type: ''
- container: ''
  name: PubInfo
  type: reference
- container: ''
  name: pubtype
  type: string
- container: ''
  name: pubyear
  type: string
- container: ''
  name: sortdate
  type: string
- container: ''
  name: vol
  type: string
- container: ''
  name: DocumentPages
  type: reference
- container: ''
  name: range
  type: string
- container: ''
  name: begin
  type: string
- container: ''
  name: end
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: CategoryCount
  type: reference
- container: ''
  name: CategoryContext
  type: reference
- container: ''
  name: Document
  type: reference
- container: ''
  name: uid
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: types
  type: ''
- container: ''
  name: sourceTypes
  type: ''
- container: ''
  name: source
  type: ''
- container: ''
  name: names
  type: ''
- container: ''
  name: citations
  type: ''
- container: ''
  name: identifiers
  type: ''
- container: ''
  name: keywords
  type: ''
- container: ''
  name: TimeSpan
  type: reference
- container: ''
  name: WosRecord
  type: reference
- container: ''
  name: UID
  type: string
- container: ''
  name: static_data
  type: ''
- container: ''
  name: dynamic_data
  type: ''
- container: ''
  name: CitationReport
  type: reference
- container: ''
  name: timesCited
  type: integer
- container: ''
  name: averagePerItem
  type: float
- container: ''
  name: hIndex
  type: integer
- container: ''
  name: citingArticlesLinks
  type: anyURI
- container: ''
  name: yearPublished
  type: ''
- container: ''
  name: citationsByYear
  type: ''
- container: ''
  name: QueryResult
  type: reference
- container: ''
  name: queryId
  type: integer
- container: ''
  name: recordsFound
  type: integer
- container: ''
  name: recordsSearched
  type: integer
- container: ''
  name: RecordIdsResponse
  type: reference
- container: ''
  name: queryResult
  type: ''
- container: ''
  name: ids
  type: ''
- container: ''
  name: DocumentIdentifiers
  type: reference
- container: ''
  name: doi
  type: string
- container: ''
  name: pmid
  type: string
- container: ''
  name: DynamicData
  type: reference
- container: ''
  name: citation_related
  type: ''
- container: ''
  name: CitationCount
  type: reference
- container: ''
  name: db
  type: string
- container: ''
  name: RecordSummary
  type: reference
- container: ''
  name: doctypes
  type: ''
- container: ''
  name: titles
  type: ''
- container: ''
  name: pub_info
  type: ''
- container: ''
  name: DocumentKeywords
  type: reference
- container: ''
  name: authorKeywords
  type: ''
- container: ''
  name: keywordsPlus
  type: ''
- container: ''
  name: SearchResponse
  type: reference
- container: ''
  name: records
  type: ''
- container: ''
  name: DocumentNames
  type: reference
- container: ''
  name: authors
  type: ''
- container: ''
  name: SearchRequest
  type: reference
- container: ''
  name: databaseId
  type: string
- container: ''
  name: usrQuery
  type: string
- container: ''
  name: firstRecord
  type: integer
- container: ''
  name: editions
  type: ''
- container: ''
  name: publishTimeSpan
  type: ''
- container: ''
  name: sortField
  type: string
- container: ''
  name: Records
  type: reference
- container: ''
  name: JournalsSearchResponse
  type: reference
- container: ''
  name: total
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: limit
  type: integer
- container: ''
  name: hits
  type: ''
- container: ''
  name: DocumentsSearchResponse
  type: reference
- container: ''
  name: YearCount
  type: reference
- container: ''
  name: year
  type: integer
- container: ''
  name: Author
  type: reference
- container: ''
  name: displayName
  type: string
- container: ''
  name: wosStandard
  type: string
- container: ''
  name: researcherId
  type: string
- container: ''
  name: FullRecordMetadata
  type: reference
- container: ''
  name: languages
  type: ''
- container: ''
  name: addresses
  type: ''
- container: ''
  name: fund_ack
  type: ''
- container: ''
  name: DocumentLinks
  type: reference
- container: ''
  name: record
  type: anyURI
- container: ''
  name: references
  type: anyURI
- container: ''
  name: related
  type: anyURI
property_count: 113
provider_name: Web of Science APIs
provider_slug: web-of-science-apis
slug: web-of-science-context
source_filename: web-of-science-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"wos\": \"https://clarivate.com/webofsciencegroup/solutions/web-of-science/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DocumentSource\": {\n      \"@id\": \"wos:DocumentSource\",\n      \"@type\": \"@id\"\n    },\n    \"sourceTitle\": {\n      \"@id\": \"wos:sourceTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishYear\": {\n      \"@id\": \"wos:publishYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishMonth\": {\n      \"@id\": \"wos:publishMonth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volume\": {\n      \"@id\": \"wos:volume\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issue\": {\n      \"@id\": \"wos:issue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pages\": {\n      \"@id\": \"wos:pages\"\n    },\n    \"articleNumber\": {\n      \"@id\": \"wos:articleNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supplement\": {\n      \"\
  @id\": \"wos:supplement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"wos:ErrorResponse\",\n      \"@type\": \"@id\"\n    },\n    \"code\": {\n      \"@id\": \"wos:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"wos:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StaticData\": {\n      \"@id\": \"wos:StaticData\",\n      \"@type\": \"@id\"\n    },\n    \"summary\": {\n      \"@id\": \"wos:summary\"\n    },\n    \"fullrecord_metadata\": {\n      \"@id\": \"wos:fullrecord_metadata\"\n    },\n    \"Journal\": {\n      \"@id\": \"wos:Journal\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"wos:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"wos:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issn\": {\n      \"@id\": \"wos:issn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eissn\": {\n      \"@id\": \"wos:eissn\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\": \"wos:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"wos:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openAccess\": {\n      \"@id\": \"wos:openAccess\"\n    },\n    \"categories\": {\n      \"@id\": \"wos:categories\"\n    },\n    \"jcrProfile\": {\n      \"@id\": \"wos:jcrProfile\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"links\": {\n      \"@id\": \"wos:links\"\n    },\n    \"PubInfo\": {\n      \"@id\": \"wos:PubInfo\",\n      \"@type\": \"@id\"\n    },\n    \"pubtype\": {\n      \"@id\": \"wos:pubtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pubyear\": {\n      \"@id\": \"wos:pubyear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortdate\": {\n      \"@id\": \"wos:sortdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vol\": {\n      \"@id\": \"wos:vol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DocumentPages\": {\n      \"@id\"\
  : \"wos:DocumentPages\",\n      \"@type\": \"@id\"\n    },\n    \"range\": {\n      \"@id\": \"wos:range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"begin\": {\n      \"@id\": \"wos:begin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"wos:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"wos:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CategoryCount\": {\n      \"@id\": \"wos:CategoryCount\",\n      \"@type\": \"@id\"\n    },\n    \"CategoryContext\": {\n      \"@id\": \"wos:CategoryContext\",\n      \"@type\": \"@id\"\n    },\n    \"Document\": {\n      \"@id\": \"wos:Document\",\n      \"@type\": \"@id\"\n    },\n    \"uid\": {\n      \"@id\": \"wos:uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"wos:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"types\": {\n      \"@id\": \"wos:types\"\n    },\n    \"sourceTypes\": {\n      \"@id\": \"wos:sourceTypes\"\n\
  \    },\n    \"source\": {\n      \"@id\": \"wos:source\"\n    },\n    \"names\": {\n      \"@id\": \"wos:names\"\n    },\n    \"citations\": {\n      \"@id\": \"wos:citations\"\n    },\n    \"identifiers\": {\n      \"@id\": \"wos:identifiers\"\n    },\n    \"keywords\": {\n      \"@id\": \"wos:keywords\"\n    },\n    \"TimeSpan\": {\n      \"@id\": \"wos:TimeSpan\",\n      \"@type\": \"@id\"\n    },\n    \"WosRecord\": {\n      \"@id\": \"wos:WosRecord\",\n      \"@type\": \"@id\"\n    },\n    \"UID\": {\n      \"@id\": \"wos:UID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"static_data\": {\n      \"@id\": \"wos:static_data\"\n    },\n    \"dynamic_data\": {\n      \"@id\": \"wos:dynamic_data\"\n    },\n    \"CitationReport\": {\n      \"@id\": \"wos:CitationReport\",\n      \"@type\": \"@id\"\n    },\n    \"timesCited\": {\n      \"@id\": \"wos:timesCited\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"averagePerItem\": {\n      \"@id\": \"wos:averagePerItem\",\n      \"@type\"\
  : \"xsd:float\"\n    },\n    \"hIndex\": {\n      \"@id\": \"wos:hIndex\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"citingArticlesLinks\": {\n      \"@id\": \"wos:citingArticlesLinks\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"yearPublished\": {\n      \"@id\": \"wos:yearPublished\"\n    },\n    \"citationsByYear\": {\n      \"@id\": \"wos:citationsByYear\"\n    },\n    \"QueryResult\": {\n      \"@id\": \"wos:QueryResult\",\n      \"@type\": \"@id\"\n    },\n    \"queryId\": {\n      \"@id\": \"wos:queryId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recordsFound\": {\n      \"@id\": \"wos:recordsFound\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recordsSearched\": {\n      \"@id\": \"wos:recordsSearched\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"RecordIdsResponse\": {\n      \"@id\": \"wos:RecordIdsResponse\",\n      \"@type\": \"@id\"\n    },\n    \"queryResult\": {\n      \"@id\": \"wos:queryResult\"\n    },\n    \"ids\": {\n      \"@id\": \"wos:ids\"\
  \n    },\n    \"DocumentIdentifiers\": {\n      \"@id\": \"wos:DocumentIdentifiers\",\n      \"@type\": \"@id\"\n    },\n    \"doi\": {\n      \"@id\": \"wos:doi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pmid\": {\n      \"@id\": \"wos:pmid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DynamicData\": {\n      \"@id\": \"wos:DynamicData\",\n      \"@type\": \"@id\"\n    },\n    \"citation_related\": {\n      \"@id\": \"wos:citation_related\"\n    },\n    \"CitationCount\": {\n      \"@id\": \"wos:CitationCount\",\n      \"@type\": \"@id\"\n    },\n    \"db\": {\n      \"@id\": \"wos:db\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecordSummary\": {\n      \"@id\": \"wos:RecordSummary\",\n      \"@type\": \"@id\"\n    },\n    \"doctypes\": {\n      \"@id\": \"wos:doctypes\"\n    },\n    \"titles\": {\n      \"@id\": \"wos:titles\"\n    },\n    \"pub_info\": {\n      \"@id\": \"wos:pub_info\"\n    },\n    \"DocumentKeywords\": {\n      \"@id\": \"wos:DocumentKeywords\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"authorKeywords\": {\n      \"@id\": \"wos:authorKeywords\"\n    },\n    \"keywordsPlus\": {\n      \"@id\": \"wos:keywordsPlus\"\n    },\n    \"SearchResponse\": {\n      \"@id\": \"wos:SearchResponse\",\n      \"@type\": \"@id\"\n    },\n    \"records\": {\n      \"@id\": \"wos:records\"\n    },\n    \"DocumentNames\": {\n      \"@id\": \"wos:DocumentNames\",\n      \"@type\": \"@id\"\n    },\n    \"authors\": {\n      \"@id\": \"wos:authors\"\n    },\n    \"SearchRequest\": {\n      \"@id\": \"wos:SearchRequest\",\n      \"@type\": \"@id\"\n    },\n    \"databaseId\": {\n      \"@id\": \"wos:databaseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usrQuery\": {\n      \"@id\": \"wos:usrQuery\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstRecord\": {\n      \"@id\": \"wos:firstRecord\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"editions\": {\n      \"@id\": \"wos:editions\"\n    },\n    \"publishTimeSpan\": {\n      \"@id\"\
  : \"wos:publishTimeSpan\"\n    },\n    \"sortField\": {\n      \"@id\": \"wos:sortField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Records\": {\n      \"@id\": \"wos:Records\",\n      \"@type\": \"@id\"\n    },\n    \"JournalsSearchResponse\": {\n      \"@id\": \"wos:JournalsSearchResponse\",\n      \"@type\": \"@id\"\n    },\n    \"total\": {\n      \"@id\": \"wos:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"wos:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"wos:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hits\": {\n      \"@id\": \"wos:hits\"\n    },\n    \"DocumentsSearchResponse\": {\n      \"@id\": \"wos:DocumentsSearchResponse\",\n      \"@type\": \"@id\"\n    },\n    \"YearCount\": {\n      \"@id\": \"wos:YearCount\",\n      \"@type\": \"@id\"\n    },\n    \"year\": {\n      \"@id\": \"wos:year\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Author\": {\n      \"@id\": \"wos:Author\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"displayName\": {\n      \"@id\": \"wos:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wosStandard\": {\n      \"@id\": \"wos:wosStandard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"researcherId\": {\n      \"@id\": \"wos:researcherId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullRecordMetadata\": {\n      \"@id\": \"wos:FullRecordMetadata\",\n      \"@type\": \"@id\"\n    },\n    \"languages\": {\n      \"@id\": \"wos:languages\"\n    },\n    \"addresses\": {\n      \"@id\": \"wos:addresses\"\n    },\n    \"fund_ack\": {\n      \"@id\": \"wos:fund_ack\"\n    },\n    \"DocumentLinks\": {\n      \"@id\": \"wos:DocumentLinks\",\n      \"@type\": \"@id\"\n    },\n    \"record\": {\n      \"@id\": \"wos:record\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"references\": {\n      \"@id\": \"wos:references\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"related\": {\n      \"@id\": \"wos:related\",\n      \"@type\"\
  : \"xsd:anyURI\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/json-ld/web-of-science-context.jsonld
tags:
- Research
- Academic
- Bibliometrics
- Citations
- Science
- Scholarly
- JSON-LD
- Linked Data
- Semantic Web
---
