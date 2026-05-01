---
api_specs:
- filename: Welcome.html
  format: yaml
  label: Amazon QuickSight API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.aws.amazon.com/quicksight/latest/APIReference/Welcome.html
class_count: 0
classes: []
context_file: json-ld/amazon-quicksight-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Quicksight from Amazon QuickSight.
layout: jsonld
name: Amazon Quicksight Context
namespaces:
- prefix: quicksight
  uri: https://docs.aws.amazon.com/quicksight/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Dashboard
  type: ''
- container: ''
  name: DataSet
  type: ''
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: Analysis
  type: ''
- container: ''
  name: DashboardVersion
  type: ''
property_count: 5
provider_name: Amazon QuickSight
provider_slug: amazon-quicksight
slug: amazon-quicksight-context
source_filename: amazon-quicksight-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"quicksight\": \"https://docs.aws.amazon.com/quicksight/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Dashboard\": {\n      \"@id\": \"quicksight:API_DescribeDashboard\",\n      \"@context\": {\n        \"DashboardId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"quicksight:dashboardArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Version\": {\n          \"@id\": \"quicksight:dashboardVersion\",\n          \"@type\": \"quicksight:DashboardVersion\"\n        },\n        \"CreatedTime\": {\n          \"@id\": \"schema:dateCreated\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastPublishedTime\": {\n          \"@id\": \"quicksight:lastPublishedTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DataSet\": {\n      \"@id\": \"quicksight:API_DescribeDataSet\",\n      \"@context\": {\n        \"DataSetId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"quicksight:dataSetArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\
  \n        },\n        \"ImportMode\": {\n          \"@id\": \"quicksight:importMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ConsumedSpiceCapacityInBytes\": {\n          \"@id\": \"quicksight:consumedSpiceCapacity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"PhysicalTableMap\": {\n          \"@id\": \"quicksight:physicalTableMap\",\n          \"@container\": \"@index\"\n        },\n        \"LogicalTableMap\": {\n          \"@id\": \"quicksight:logicalTableMap\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"DataSource\": {\n      \"@id\": \"quicksight:API_DescribeDataSource\",\n      \"@context\": {\n        \"DataSourceId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"quicksight:dataSourceArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"Type\": {\n          \"@id\": \"quicksight:dataSourceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"quicksight:dataSourceStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Analysis\": {\n      \"@id\": \"quicksight:API_DescribeAnalysis\",\n      \"@context\": {\n        \"AnalysisId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"quicksight:analysisArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\"\
  : {\n          \"@id\": \"quicksight:analysisStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastUpdatedTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DashboardVersion\": {\n      \"@id\": \"quicksight:DashboardVersion\",\n      \"@context\": {\n        \"VersionNumber\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"Status\": {\n          \"@id\": \"quicksight:versionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Arn\": {\n          \"@id\": \"quicksight:versionArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"SourceEntityArn\": {\n          \"@id\": \"quicksight:sourceEntityArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n     \
  \     \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreatedTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"DataSetArns\": {\n          \"@id\": \"quicksight:dataSetArns\",\n          \"@container\": \"@list\"\n        },\n        \"Sheets\": {\n          \"@id\": \"quicksight:sheets\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-quicksight/refs/heads/main/json-ld/amazon-quicksight-context.jsonld
tags:
- Analytics
- BI
- Business Intelligence
- Dashboards
- Machine Learning
- Reporting
- Visualization
- JSON-LD
- Linked Data
- Semantic Web
---
