---
api_specs:
- filename: grafana-api.yml
  format: yaml
  label: Grafana HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/openapi/grafana-api.yml
class_count: 0
classes: []
context_file: json-ld/grafana-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/json-ld/grafana-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Grafana from Grafana.
layout: jsonld
name: Grafana Context
namespaces:
- prefix: grafana
  uri: https://grafana.com/docs/grafana/latest/developers/http_api/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
- prefix: sioc
  uri: http://rdfs.org/sioc/ns#
- prefix: ssn
  uri: http://www.w3.org/ns/ssn/
- prefix: sosa
  uri: http://www.w3.org/ns/sosa/
- prefix: qudt
  uri: http://qudt.org/schema/qudt/
properties:
- container: ''
  name: Dashboard
  type: ''
- container: ''
  name: Panel
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: AlertRule
  type: ''
- container: ''
  name: ContactPoint
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Organization
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Annotation
  type: ''
- container: ''
  name: Query
  type: ''
- container: ''
  name: Observation
  type: ''
property_count: 12
provider_name: Grafana
provider_slug: grafana
slug: grafana-context
source_filename: grafana-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"grafana\": \"https://grafana.com/docs/grafana/latest/developers/http_api/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n    \"sioc\": \"http://rdfs.org/sioc/ns#\",\n    \"ssn\": \"http://www.w3.org/ns/ssn/\",\n    \"sosa\": \"http://www.w3.org/ns/sosa/\",\n    \"qudt\": \"http://qudt.org/schema/qudt/\",\n\n    \"Dashboard\": {\n      \"@id\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"uid\": \"dcterms:identifier\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"tags\": \"schema:keywords\",\n        \"version\": \"schema:version\",\n        \"created\": \"dcterms:created\",\n        \"updated\": \"dcterms:modified\",\n        \"createdBy\": \"dcterms:creator\",\n        \"updatedBy\": \"schema:editor\",\n        \"panels\": \"schema:hasPart\",\n\
  \        \"url\": \"schema:url\",\n        \"editable\": \"schema:isAccessibleForFree\",\n        \"folder\": \"schema:isPartOf\",\n        \"time\": {\n          \"@id\": \"schema:temporalCoverage\"\n        },\n        \"annotations\": \"schema:comment\",\n        \"links\": \"schema:relatedLink\",\n        \"templating\": \"schema:variableMeasured\"\n      }\n    },\n\n    \"Panel\": {\n      \"@id\": \"schema:DataVisualization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"type\": \"schema:additionalType\",\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"datasource\": \"schema:provider\",\n        \"targets\": \"schema:query\",\n        \"gridPos\": \"schema:spatialCoverage\",\n        \"fieldConfig\": \"schema:measurementTechnique\",\n        \"options\": \"schema:additionalProperty\",\n        \"transformations\": \"schema:algorithm\",\n        \"transparent\": \"schema:cssSelector\",\n        \"repeat\"\
  : \"schema:repeatCount\",\n        \"links\": \"schema:relatedLink\",\n        \"thresholds\": \"schema:valueReference\"\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"uid\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:additionalType\",\n        \"url\": \"schema:contentUrl\",\n        \"access\": \"schema:accessMode\",\n        \"database\": \"schema:dataset\",\n        \"isDefault\": \"schema:isDefaultAction\",\n        \"basicAuth\": \"schema:authenticator\",\n        \"jsonData\": \"schema:additionalProperty\",\n        \"readOnly\": \"schema:readonlyValue\",\n        \"version\": \"schema:version\",\n        \"user\": \"schema:accountId\"\n      }\n    },\n\n    \"AlertRule\": {\n      \"@id\": \"schema:MonitorAction\",\n      \"@context\": {\n        \"uid\": \"dcterms:identifier\",\n        \"title\": \"schema:name\",\n        \"condition\": \"schema:actionStatus\",\n  \
  \      \"folderUID\": \"schema:isPartOf\",\n        \"ruleGroup\": \"schema:category\",\n        \"for\": \"schema:duration\",\n        \"annotations\": \"schema:comment\",\n        \"labels\": \"schema:keywords\",\n        \"noDataState\": \"schema:defaultValue\",\n        \"data\": \"schema:query\",\n        \"isPaused\": \"schema:potentialAction\"\n      }\n    },\n\n    \"ContactPoint\": {\n      \"@id\": \"schema:ContactPoint\",\n      \"@context\": {\n        \"uid\": \"dcterms:identifier\",\n        \"name\": \"schema:name\",\n        \"type\": \"schema:contactType\",\n        \"settings\": \"schema:additionalProperty\",\n        \"disableResolveMessage\": \"schema:actionOption\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"foaf:Person\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"login\": \"schema:alternateName\",\n        \"isGrafanaAdmin\": \"schema:hasCredential\"\
  ,\n        \"isDisabled\": \"schema:actionStatus\",\n        \"avatarUrl\": \"schema:image\",\n        \"createdAt\": \"dcterms:created\",\n        \"updatedAt\": \"dcterms:modified\",\n        \"orgId\": \"schema:memberOf\",\n        \"authLabels\": \"schema:identifier\"\n      }\n    },\n\n    \"Organization\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"users\": \"schema:member\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"schema:Team\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"email\": \"schema:email\",\n        \"avatarUrl\": \"schema:image\",\n        \"memberCount\": \"schema:numberOfEmployees\",\n        \"members\": \"schema:member\",\n        \"created\": \"dcterms:created\",\n        \"updated\": \"dcterms:modified\"\n      }\n    },\n\n    \"Folder\"\
  : {\n      \"@id\": \"schema:Collection\",\n      \"@context\": {\n        \"uid\": \"dcterms:identifier\",\n        \"title\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"parentUid\": \"schema:isPartOf\",\n        \"created\": \"dcterms:created\",\n        \"updated\": \"dcterms:modified\",\n        \"createdBy\": \"dcterms:creator\",\n        \"updatedBy\": \"schema:editor\"\n      }\n    },\n\n    \"Annotation\": {\n      \"@id\": \"schema:Comment\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"text\": \"schema:text\",\n        \"time\": \"schema:startDate\",\n        \"timeEnd\": \"schema:endDate\",\n        \"tags\": \"schema:keywords\",\n        \"dashboardId\": \"schema:isPartOf\",\n        \"panelId\": \"schema:about\",\n        \"created\": \"dcterms:created\",\n        \"updated\": \"dcterms:modified\"\n      }\n    },\n\n    \"Query\": {\n      \"@id\": \"schema:SearchAction\",\n      \"@context\": {\n        \"refId\": \"schema:identifier\"\
  ,\n        \"expr\": \"schema:query\",\n        \"format\": \"schema:encodingFormat\",\n        \"interval\": \"schema:repeatFrequency\",\n        \"legendFormat\": \"schema:alternateName\"\n      }\n    },\n\n    \"Observation\": {\n      \"@id\": \"sosa:Observation\",\n      \"@context\": {\n        \"value\": \"sosa:hasSimpleResult\",\n        \"timestamp\": \"sosa:resultTime\",\n        \"metric\": \"sosa:observedProperty\",\n        \"unit\": \"qudt:unit\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/grafana/refs/heads/main/json-ld/grafana-context.jsonld
tags:
- Alerting
- Analytics
- Dashboards
- Logs
- Metrics
- Monitoring
- Observability
- Traces
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
