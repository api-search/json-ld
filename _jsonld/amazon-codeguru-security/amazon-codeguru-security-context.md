---
api_specs:
- filename: amazon-codeguru-security-openapi-original.yaml
  format: yaml
  label: Amazon CodeGuru Security API
  slug: amazon-codeguru-security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-security/refs/heads/main/openapi/amazon-codeguru-security-openapi-original.yaml
class_count: 49
classes:
- BatchGetFindingsResponse
- FindingIdentifier
- CreateScanResponse
- CreateUploadUrlResponse
- GetAccountConfigurationResponse
- GetFindingsResponse
- GetMetricsSummaryResponse
- GetScanResponse
- ListFindingsMetricsResponse
- ListScansResponse
- ListTagsForResourceResponse
- TagResourceResponse
- UntagResourceResponse
- UpdateAccountConfigurationResponse
- FindingMetricsValuePerSeverity
- AccountFindingsMetric
- BatchGetFindingsError
- BatchGetFindingsRequest
- CategoryWithFindingNum
- CodeLine
- ResourceId
- TagMap
- CreateScanRequest
- CreateUploadUrlRequest
- RequestHeaderMap
- EncryptionConfig
- FilePath
- Remediation
- Resource
- Vulnerability
- Finding
- GetAccountConfigurationRequest
- GetFindingsRequest
- GetMetricsSummaryRequest
- MetricsSummary
- GetScanRequest
- ListFindingsMetricsRequest
- ListScansRequest
- ListTagsForResourceRequest
- Recommendation
- ScanNameWithFindingNum
- ScanSummary
- SuggestedFix
- TagResourceRequest
- UntagResourceRequest
- UpdateAccountConfigurationRequest
- name
- description
- url
context_file: json-ld/amazon-codeguru-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-security/refs/heads/main/json-ld/amazon-codeguru-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codeguru Security from Amazon CodeGuru Security.
layout: jsonld
name: Amazon Codeguru Security Context
namespaces:
- prefix: amazon-code-guru-security
  uri: https://amazon-code-guru-security.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: failedFindings
  type: string
- container: ''
  name: findings
  type: string
- container: ''
  name: findingId
  type: string
- container: ''
  name: scanName
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: runId
  type: string
- container: ''
  name: scanNameArn
  type: string
- container: ''
  name: scanState
  type: string
- container: ''
  name: codeArtifactId
  type: string
- container: ''
  name: requestHeaders
  type: string
- container: ''
  name: s3Url
  type: string
- container: ''
  name: encryptionConfig
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: metricsSummary
  type: string
- container: ''
  name: analysisType
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: numberOfRevisions
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: findingsMetrics
  type: string
- container: ''
  name: summaries
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: critical
  type: string
- container: ''
  name: high
  type: string
- container: ''
  name: info
  type: string
- container: ''
  name: low
  type: string
- container: ''
  name: medium
  type: string
- container: ''
  name: closedFindings
  type: string
- container: ''
  name: date
  type: string
- container: ''
  name: meanTimeToClose
  type: string
- container: ''
  name: newFindings
  type: string
- container: ''
  name: openFindings
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: findingIdentifiers
  type: string
- container: ''
  name: categoryName
  type: string
- container: ''
  name: findingNumber
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: number
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: scanType
  type: string
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: codeSnippet
  type: string
- container: ''
  name: endLine
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: startLine
  type: string
- container: ''
  name: recommendation
  type: string
- container: ''
  name: suggestedFixes
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: subResourceId
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: itemCount
  type: string
- container: ''
  name: referenceUrls
  type: string
- container: ''
  name: relatedVulnerabilities
  type: string
- container: ''
  name: detectorId
  type: string
- container: ''
  name: detectorName
  type: string
- container: ''
  name: detectorTags
  type: string
- container: ''
  name: generatorId
  type: string
- container: ''
  name: remediation
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: vulnerability
  type: string
- container: ''
  name: categoriesWithMostFindings
  type: string
- container: ''
  name: scansWithMostOpenCriticalFindings
  type: string
- container: ''
  name: scansWithMostOpenFindings
  type: string
- container: ''
  name: text
  type: string
- container: ''
  name: code
  type: string
property_count: 70
provider_name: Amazon CodeGuru Security
provider_slug: amazon-codeguru-security
slug: amazon-codeguru-security-context
source_filename: amazon-codeguru-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-guru-security\": \"https://amazon-code-guru-security.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchGetFindingsResponse\": \"amazon-code-guru-security:BatchGetFindingsResponse\",\n    \"FindingIdentifier\": \"amazon-code-guru-security:FindingIdentifier\",\n    \"CreateScanResponse\": \"amazon-code-guru-security:CreateScanResponse\",\n    \"CreateUploadUrlResponse\": \"amazon-code-guru-security:CreateUploadUrlResponse\",\n    \"GetAccountConfigurationResponse\": \"amazon-code-guru-security:GetAccountConfigurationResponse\",\n    \"GetFindingsResponse\": \"amazon-code-guru-security:GetFindingsResponse\",\n    \"GetMetricsSummaryResponse\": \"amazon-code-guru-security:GetMetricsSummaryResponse\",\n    \"GetScanResponse\": \"amazon-code-guru-security:GetScanResponse\",\n    \"ListFindingsMetricsResponse\"\
  : \"amazon-code-guru-security:ListFindingsMetricsResponse\",\n    \"ListScansResponse\": \"amazon-code-guru-security:ListScansResponse\",\n    \"ListTagsForResourceResponse\": \"amazon-code-guru-security:ListTagsForResourceResponse\",\n    \"TagResourceResponse\": \"amazon-code-guru-security:TagResourceResponse\",\n    \"UntagResourceResponse\": \"amazon-code-guru-security:UntagResourceResponse\",\n    \"UpdateAccountConfigurationResponse\": \"amazon-code-guru-security:UpdateAccountConfigurationResponse\",\n    \"FindingMetricsValuePerSeverity\": \"amazon-code-guru-security:FindingMetricsValuePerSeverity\",\n    \"AccountFindingsMetric\": \"amazon-code-guru-security:AccountFindingsMetric\",\n    \"BatchGetFindingsError\": \"amazon-code-guru-security:BatchGetFindingsError\",\n    \"BatchGetFindingsRequest\": \"amazon-code-guru-security:BatchGetFindingsRequest\",\n    \"CategoryWithFindingNum\": \"amazon-code-guru-security:CategoryWithFindingNum\",\n    \"CodeLine\": \"amazon-code-guru-security:CodeLine\"\
  ,\n    \"ResourceId\": \"amazon-code-guru-security:ResourceId\",\n    \"TagMap\": \"amazon-code-guru-security:TagMap\",\n    \"CreateScanRequest\": \"amazon-code-guru-security:CreateScanRequest\",\n    \"CreateUploadUrlRequest\": \"amazon-code-guru-security:CreateUploadUrlRequest\",\n    \"RequestHeaderMap\": \"amazon-code-guru-security:RequestHeaderMap\",\n    \"EncryptionConfig\": \"amazon-code-guru-security:EncryptionConfig\",\n    \"FilePath\": \"amazon-code-guru-security:FilePath\",\n    \"Remediation\": \"amazon-code-guru-security:Remediation\",\n    \"Resource\": \"amazon-code-guru-security:Resource\",\n    \"Vulnerability\": \"amazon-code-guru-security:Vulnerability\",\n    \"Finding\": \"amazon-code-guru-security:Finding\",\n    \"GetAccountConfigurationRequest\": \"amazon-code-guru-security:GetAccountConfigurationRequest\",\n    \"GetFindingsRequest\": \"amazon-code-guru-security:GetFindingsRequest\",\n    \"GetMetricsSummaryRequest\": \"amazon-code-guru-security:GetMetricsSummaryRequest\"\
  ,\n    \"MetricsSummary\": \"amazon-code-guru-security:MetricsSummary\",\n    \"GetScanRequest\": \"amazon-code-guru-security:GetScanRequest\",\n    \"ListFindingsMetricsRequest\": \"amazon-code-guru-security:ListFindingsMetricsRequest\",\n    \"ListScansRequest\": \"amazon-code-guru-security:ListScansRequest\",\n    \"ListTagsForResourceRequest\": \"amazon-code-guru-security:ListTagsForResourceRequest\",\n    \"Recommendation\": \"amazon-code-guru-security:Recommendation\",\n    \"ScanNameWithFindingNum\": \"amazon-code-guru-security:ScanNameWithFindingNum\",\n    \"ScanSummary\": \"amazon-code-guru-security:ScanSummary\",\n    \"SuggestedFix\": \"amazon-code-guru-security:SuggestedFix\",\n    \"TagResourceRequest\": \"amazon-code-guru-security:TagResourceRequest\",\n    \"UntagResourceRequest\": \"amazon-code-guru-security:UntagResourceRequest\",\n    \"UpdateAccountConfigurationRequest\": \"amazon-code-guru-security:UpdateAccountConfigurationRequest\",\n    \"failedFindings\": {\n \
  \     \"@id\": \"amazon-code-guru-security:failedFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"amazon-code-guru-security:findings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingId\": {\n      \"@id\": \"amazon-code-guru-security:findingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanName\": {\n      \"@id\": \"amazon-code-guru-security:scanName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"amazon-code-guru-security:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runId\": {\n      \"@id\": \"amazon-code-guru-security:runId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanNameArn\": {\n      \"@id\": \"amazon-code-guru-security:scanNameArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanState\": {\n      \"@id\": \"amazon-code-guru-security:scanState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeArtifactId\": {\n      \"@id\": \"amazon-code-guru-security:codeArtifactId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"requestHeaders\": {\n      \"@id\": \"amazon-code-guru-security:requestHeaders\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Url\": {\n      \"@id\": \"amazon-code-guru-security:s3Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionConfig\": {\n      \"@id\": \"amazon-code-guru-security:encryptionConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-guru-security:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricsSummary\": {\n      \"@id\": \"amazon-code-guru-security:metricsSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analysisType\": {\n      \"@id\": \"amazon-code-guru-security:analysisType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amazon-code-guru-security:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfRevisions\": {\n      \"@id\": \"amazon-code-guru-security:numberOfRevisions\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"amazon-code-guru-security:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingsMetrics\": {\n      \"@id\": \"amazon-code-guru-security:findingsMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summaries\": {\n      \"@id\": \"amazon-code-guru-security:summaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amazon-code-guru-security:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"amazon-code-guru-security:critical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"high\": {\n      \"@id\": \"amazon-code-guru-security:high\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"amazon-code-guru-security:info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"low\": {\n      \"@id\": \"amazon-code-guru-security:low\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medium\": {\n      \"\
  @id\": \"amazon-code-guru-security:medium\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closedFindings\": {\n      \"@id\": \"amazon-code-guru-security:closedFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"amazon-code-guru-security:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meanTimeToClose\": {\n      \"@id\": \"amazon-code-guru-security:meanTimeToClose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newFindings\": {\n      \"@id\": \"amazon-code-guru-security:newFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openFindings\": {\n      \"@id\": \"amazon-code-guru-security:openFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amazon-code-guru-security:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amazon-code-guru-security:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingIdentifiers\": {\n      \"@id\": \"amazon-code-guru-security:findingIdentifiers\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryName\": {\n      \"@id\": \"amazon-code-guru-security:categoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingNumber\": {\n      \"@id\": \"amazon-code-guru-security:findingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"amazon-code-guru-security:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"number\": {\n      \"@id\": \"amazon-code-guru-security:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amazon-code-guru-security:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanType\": {\n      \"@id\": \"amazon-code-guru-security:scanType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"amazon-code-guru-security:kmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeSnippet\": {\n      \"@id\": \"amazon-code-guru-security:codeSnippet\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"endLine\": {\n      \"@id\": \"amazon-code-guru-security:endLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"path\": {\n      \"@id\": \"amazon-code-guru-security:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startLine\": {\n      \"@id\": \"amazon-code-guru-security:startLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendation\": {\n      \"@id\": \"amazon-code-guru-security:recommendation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedFixes\": {\n      \"@id\": \"amazon-code-guru-security:suggestedFixes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amazon-code-guru-security:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subResourceId\": {\n      \"@id\": \"amazon-code-guru-security:subResourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"amazon-code-guru-security:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"itemCount\": {\n      \"@id\": \"amazon-code-guru-security:itemCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceUrls\": {\n      \"@id\": \"amazon-code-guru-security:referenceUrls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedVulnerabilities\": {\n      \"@id\": \"amazon-code-guru-security:relatedVulnerabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"detectorId\": {\n      \"@id\": \"amazon-code-guru-security:detectorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorName\": {\n      \"@id\": \"amazon-code-guru-security:detectorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorTags\": {\n      \"@id\": \"amazon-code-guru-security:detectorTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatorId\": {\n      \"@id\": \"amazon-code-guru-security:generatorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"amazon-code-guru-security:remediation\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"amazon-code-guru-security:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"amazon-code-guru-security:ruleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"amazon-code-guru-security:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amazon-code-guru-security:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"amazon-code-guru-security:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amazon-code-guru-security:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerability\": {\n      \"@id\": \"amazon-code-guru-security:vulnerability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoriesWithMostFindings\": {\n      \"@id\": \"amazon-code-guru-security:categoriesWithMostFindings\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"scansWithMostOpenCriticalFindings\": {\n      \"@id\": \"amazon-code-guru-security:scansWithMostOpenCriticalFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scansWithMostOpenFindings\": {\n      \"@id\": \"amazon-code-guru-security:scansWithMostOpenFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"amazon-code-guru-security:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"code\": {\n      \"@id\": \"amazon-code-guru-security:code\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-security/refs/heads/main/json-ld/amazon-codeguru-security-context.jsonld
tags:
- Amazon
- Security
- SAST
- Code Analysis
- DevSecOps
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
