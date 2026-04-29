---
class_count: 71
classes:
- url-protection-category
- hostname-coverage-match-target-get-200
- header-logging-put
- custom-rules
- reputation-profile
- attack-payload-logging-put
- url-protection-bypass-request-header-condition
- url-protection-policies
- malware-policy
- hostnames
- prefetch-request-put
- version-notes-get-200
- reputation-profiles
- url-protection-policy
- attack-payload-logging-get-200
- prefetch-request-get-200
- validation
- config-get
- version-notes-put
- request-header-condition-2
- overlap-config
- waf-config-version
- rate-policy-evaluation-put
- validations
- siem-settings
- hostname-object
- custom-deny
- match-targets
- evasive-path-match-get-200
- malware-policies
- config-clone-post
- header-logging-get-200
- siem-version
- request-body
- problem-details
- pii-learning
- configs-get
- hostname-coverage-match-target
- custom-rule
- effectiveTimePeriod
- rate-policy
- cookie-settings
- match-target
- host-info-in-config
- bypass-network-lists-get
- logging-option
- evasive-path-match-put
- header-logging-put-200
- evasive-path-match-put-200
- match-targets-sequence
- hostname-coverage-overlapping-get-200
- attack-payload-logging
- waf-config-versions
- rate-policies
- custom-denies
- logging-header-setting
- url-protection-policy-hostpath
- siem-versions
- pragma-header
- bypass-network-lists-put
- security-controls
- config-rename
- malware-policies-content-types
- tls-fingerprint-condition
- version-notes-put-200
- url-protection-client-list-category
- prefetch-request-put-200
- client-reputation-condition
- config-post
- attack-payload-logging-put-200
- url-protection-bypass-client-list-condition
context_file: json-ld/akamai-api-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/json-ld/akamai-api-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Akamai Api Security from Akamai API Security.
layout: jsonld
name: Akamai Api Security Context
namespaces:
- prefix: akamai
  uri: https://developer.akamai.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: matchTargets
  type: reference
- container: set
  name: apiTargets
  type: reference
- container: set
  name: websiteTargets
  type: reference
- container: ''
  name: allowSampling
  type: boolean
- container: ''
  name: cookies
  type: reference
- container: set
  name: values
  type: string
- container: ''
  name: customHeaders
  type: reference
- container: ''
  name: standardHeaders
  type: reference
- container: set
  name: customRules
  type: reference
- container: ''
  name: condition
  type: reference
- container: set
  name: atomicConditions
  type: reference
- container: ''
  name: positiveMatch
  type: boolean
- container: ''
  name: context
  type: string
- container: ''
  name: contextReadable
  type: string
- container: ''
  name: description
  type: ''
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: ''
- container: ''
  name: sharedIpHandling
  type: string
- container: ''
  name: threshold
  type: decimal
- container: ''
  name: requestBody
  type: reference
- container: ''
  name: responseBody
  type: reference
- container: ''
  name: className
  type: string
- container: ''
  name: nameWildcard
  type: boolean
- container: set
  name: value
  type: string
- container: ''
  name: valueCase
  type: boolean
- container: ''
  name: valueWildcard
  type: boolean
- container: set
  name: urlProtectionPolicies
  type: reference
- container: ''
  name: allowListId
  type: string
- container: ''
  name: blockListId
  type: string
- container: set
  name: contentTypes
  type: reference
- container: ''
  name: logFilename
  type: boolean
- container: set
  name: paths
  type: string
- container: ''
  name: allExtensions
  type: boolean
- container: ''
  name: enableAppLayer
  type: boolean
- container: ''
  name: enableRateControls
  type: boolean
- container: set
  name: extensions
  type: string
- container: ''
  name: notes
  type: string
- container: set
  name: reputationProfiles
  type: reference
- container: set
  name: apiDefinitions
  type: reference
- container: ''
  name: bypassCondition
  type: reference
- container: set
  name: categories
  type: string
- container: ''
  name: configId
  type: integer
- container: ''
  name: configVersion
  type: integer
- container: ''
  name: createDate
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: set
  name: hostnamePaths
  type: reference
- container: ''
  name: intelligentLoadShedding
  type: boolean
- container: ''
  name: policyId
  type: integer
- container: ''
  name: protectionType
  type: string
- container: ''
  name: rateThreshold
  type: integer
- container: ''
  name: sheddingThresholdHitsPerSec
  type: integer
- container: ''
  name: updateDate
  type: dateTime
- container: ''
  name: updatedBy
  type: string
- container: ''
  name: used
  type: boolean
- container: ''
  name: detail
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: jsonReference
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: latestVersion
  type: integer
- container: set
  name: productionHostnames
  type: string
- container: ''
  name: productionVersion
  type: integer
- container: ''
  name: stagingVersion
  type: integer
- container: ''
  name: configName
  type: string
- container: ''
  name: contractId
  type: string
- container: ''
  name: contractName
  type: string
- container: ''
  name: basedOn
  type: integer
- container: ''
  name: production
  type: reference
- container: ''
  name: action
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: staging
  type: reference
- container: ''
  name: version
  type: ''
- container: ''
  name: versionNotes
  type: string
- container: set
  name: errors
  type: reference
- container: set
  name: notices
  type: reference
- container: set
  name: warnings
  type: reference
- container: ''
  name: enableForAllPolicies
  type: boolean
- container: ''
  name: enableSiem
  type: boolean
- container: ''
  name: enabledBotmanSiemEvents
  type: boolean
- container: set
  name: exceptions
  type: reference
- container: set
  name: firewallPolicyIds
  type: string
- container: ''
  name: siemDefinitionId
  type: integer
- container: ''
  name: activeInProduction
  type: boolean
- container: ''
  name: activeInStaging
  type: boolean
- container: ''
  name: arlInclusion
  type: boolean
- container: ''
  name: configIdInProduction
  type: integer
- container: ''
  name: configNameInProduction
  type: string
- container: ''
  name: hostname
  type: string
- container: set
  name: parameters
  type: reference
- container: ''
  name: enablePathMatch
  type: boolean
- container: set
  name: malwarePolicies
  type: reference
- container: ''
  name: createFromVersion
  type: integer
- container: ''
  name: ruleUpdate
  type: boolean
- container: ''
  name: requestBodyInspectionLimitInKB
  type: string
- container: ''
  name: fieldErrors
  type: reference
- container: ''
  name: instance
  type: string
- container: ''
  name: enablePiiLearning
  type: boolean
- container: set
  name: configurations
  type: reference
- container: set
  name: apis
  type: reference
- container: set
  name: bypassNetworkLists
  type: reference
- container: ''
  name: defaultFile
  type: string
- container: ''
  name: effectiveSecurityControls
  type: reference
- container: ''
  name: applyApiConstraints
  type: boolean
- container: ''
  name: applyApplicationLayerControls
  type: boolean
- container: ''
  name: applyBotmanControls
  type: boolean
- container: ''
  name: applyNetworkLayerControls
  type: boolean
- container: ''
  name: applyRateControls
  type: boolean
- container: ''
  name: applyReputationControls
  type: boolean
- container: ''
  name: applySlowPostControls
  type: boolean
- container: set
  name: fileExtensions
  type: string
- container: set
  name: filePaths
  type: string
- container: ''
  name: isNegativeFileExtensionMatch
  type: boolean
- container: ''
  name: isNegativePathMatch
  type: boolean
- container: ''
  name: securityPolicy
  type: reference
- container: ''
  name: sequence
  type: integer
- container: ''
  name: targetId
  type: integer
- container: set
  name: conditions
  type: reference
- container: ''
  name: endDate
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: inspectRequest
  type: boolean
- container: ''
  name: inspectResponse
  type: boolean
- container: set
  name: loggingOptions
  type: reference
- container: ''
  name: metadata
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: ruleActivated
  type: boolean
- container: ''
  name: samplingRate
  type: integer
- container: ''
  name: stagingOnly
  type: boolean
- container: ''
  name: structured
  type: boolean
- container: set
  name: tag
  type: string
- container: set
  name: additionalMatchOptions
  type: reference
- container: set
  name: apiSelectors
  type: reference
- container: ''
  name: averageThreshold
  type: integer
- container: set
  name: bodyParameters
  type: reference
- container: ''
  name: burstThreshold
  type: integer
- container: ''
  name: burstWindow
  type: integer
- container: ''
  name: clientIdentifier
  type: string
- container: ''
  name: counterType
  type: string
- container: ''
  name: evaluation
  type: reference
- container: ''
  name: evaluationId
  type: integer
- container: ''
  name: evaluationStatus
  type: string
- container: ''
  name: hosts
  type: reference
- container: ''
  name: matchType
  type: string
- container: ''
  name: path
  type: reference
- container: ''
  name: pathMatchType
  type: string
- container: ''
  name: pathUriPositiveMatch
  type: boolean
- container: set
  name: queryParameters
  type: reference
- container: ''
  name: requestType
  type: string
- container: ''
  name: sameActionOnIpv6
  type: boolean
- container: ''
  name: useXForwardForHeaders
  type: boolean
- container: ''
  name: cookieDomain
  type: string
- container: ''
  name: useAllSecureTraffic
  type: boolean
- container: set
  name: availableSet
  type: reference
- container: set
  name: errorSet
  type: reference
- container: ''
  name: protectARLInclusionHost
  type: boolean
- container: set
  name: selectedSet
  type: reference
- container: set
  name: networkLists
  type: reference
- container: set
  name: targetSequence
  type: reference
- container: set
  name: overLappingList
  type: reference
- container: ''
  name: lastCreatedVersion
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: productionActiveVersion
  type: integer
- container: ''
  name: productionExpediteRequestId
  type: integer
- container: ''
  name: stagingActiveVersion
  type: integer
- container: ''
  name: stagingExpediteRequestId
  type: integer
- container: ''
  name: totalSize
  type: integer
- container: set
  name: versionList
  type: reference
- container: set
  name: ratePolicies
  type: reference
- container: set
  name: hostnameList
  type: reference
- container: ''
  name: mode
  type: string
- container: set
  name: siemDefinitions
  type: reference
- container: ''
  name: conditionOperator
  type: string
- container: set
  name: excludeCondition
  type: reference
- container: set
  name: malwareContentTypes
  type: string
- container: set
  name: listIds
  type: string
- container: ''
  name: createFrom
  type: reference
- container: ''
  name: groupId
  type: integer
- container: ''
  name: checkIps
  type: string
property_count: 180
provider_name: Akamai API Security
provider_slug: akamai-api-security
slug: akamai-api-security-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"akamai\": \"https://developer.akamai.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"url-protection-category\": \"akamai:url-protection-category\",\n    \"type\": {\n      \"@id\": \"akamai:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname-coverage-match-target-get-200\": \"akamai:hostname-coverage-match-target-get-200\",\n    \"matchTargets\": {\n      \"@id\": \"akamai:matchTargets\",\n      \"@type\": \"@id\"\n    },\n    \"apiTargets\": {\n      \"@id\": \"akamai:apiTargets\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"websiteTargets\": {\n      \"@id\": \"akamai:websiteTargets\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"header-logging-put\": \"akamai:header-logging-put\",\n    \"allowSampling\": {\n      \"@id\": \"akamai:allowSampling\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cookies\": {\n      \"@id\": \"akamai:cookies\",\n      \"@type\": \"@id\"\n    },\n    \"values\": {\n      \"@id\": \"akamai:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customHeaders\": {\n      \"@id\": \"akamai:customHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"standardHeaders\": {\n      \"@id\": \"akamai:standardHeaders\",\n      \"@type\": \"@id\"\n    },\n    \"custom-rules\": \"akamai:custom-rules\",\n    \"customRules\": {\n      \"@id\": \"akamai:customRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"reputation-profile\": \"akamai:reputation-profile\",\n    \"condition\": {\n      \"@id\": \"akamai:condition\",\n      \"@type\": \"@id\"\n    },\n    \"atomicConditions\": {\n      \"@id\": \"akamai:atomicConditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"positiveMatch\": {\n      \"@id\": \"akamai:positiveMatch\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"context\": {\n      \"@id\": \"akamai:context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contextReadable\": {\n      \"@id\": \"akamai:contextReadable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"enabled\": {\n      \"@id\": \"akamai:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"akamai:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"sharedIpHandling\": {\n      \"@id\": \"akamai:sharedIpHandling\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threshold\": {\n      \"@id\": \"akamai:threshold\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"attack-payload-logging-put\": \"akamai:attack-payload-logging-put\",\n    \"requestBody\": {\n      \"@id\": \"akamai:requestBody\",\n      \"@type\": \"@id\"\n    },\n    \"responseBody\": {\n      \"@id\":\
  \ \"akamai:responseBody\",\n      \"@type\": \"@id\"\n    },\n    \"url-protection-bypass-request-header-condition\": \"akamai:url-protection-bypass-request-header-condition\",\n    \"className\": {\n      \"@id\": \"akamai:className\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameWildcard\": {\n      \"@id\": \"akamai:nameWildcard\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"value\": {\n      \"@id\": \"akamai:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueCase\": {\n      \"@id\": \"akamai:valueCase\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"valueWildcard\": {\n      \"@id\": \"akamai:valueWildcard\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"url-protection-policies\": \"akamai:url-protection-policies\",\n    \"urlProtectionPolicies\": {\n      \"@id\": \"akamai:urlProtectionPolicies\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"malware-policy\": \"akamai:malware-policy\",\n \
  \   \"allowListId\": {\n      \"@id\": \"akamai:allowListId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockListId\": {\n      \"@id\": \"akamai:blockListId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentTypes\": {\n      \"@id\": \"akamai:contentTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hostnames\": \"akamai:hostnames\",\n    \"logFilename\": {\n      \"@id\": \"akamai:logFilename\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paths\": {\n      \"@id\": \"akamai:paths\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefetch-request-put\": \"akamai:prefetch-request-put\",\n    \"allExtensions\": {\n      \"@id\": \"akamai:allExtensions\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableAppLayer\": {\n      \"@id\": \"akamai:enableAppLayer\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableRateControls\": {\n      \"@id\": \"akamai:enableRateControls\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"extensions\": {\n      \"@id\": \"akamai:extensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version-notes-get-200\": \"akamai:version-notes-get-200\",\n    \"notes\": {\n      \"@id\": \"akamai:notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reputation-profiles\": \"akamai:reputation-profiles\",\n    \"reputationProfiles\": {\n      \"@id\": \"akamai:reputationProfiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"url-protection-policy\": \"akamai:url-protection-policy\",\n    \"apiDefinitions\": {\n      \"@id\": \"akamai:apiDefinitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"bypassCondition\": {\n      \"@id\": \"akamai:bypassCondition\",\n      \"@type\": \"@id\"\n    },\n    \"categories\": {\n      \"@id\": \"akamai:categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configId\": {\n      \"\
  @id\": \"akamai:configId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configVersion\": {\n      \"@id\": \"akamai:configVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createDate\": {\n      \"@id\": \"akamai:createDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"akamai:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostnamePaths\": {\n      \"@id\": \"akamai:hostnamePaths\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"intelligentLoadShedding\": {\n      \"@id\": \"akamai:intelligentLoadShedding\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"policyId\": {\n      \"@id\": \"akamai:policyId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"protectionType\": {\n      \"@id\": \"akamai:protectionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateThreshold\": {\n      \"@id\": \"akamai:rateThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sheddingThresholdHitsPerSec\"\
  : {\n      \"@id\": \"akamai:sheddingThresholdHitsPerSec\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"updateDate\": {\n      \"@id\": \"akamai:updateDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedBy\": {\n      \"@id\": \"akamai:updatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"used\": {\n      \"@id\": \"akamai:used\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"attack-payload-logging-get-200\": \"akamai:attack-payload-logging-get-200\",\n    \"prefetch-request-get-200\": \"akamai:prefetch-request-get-200\",\n    \"validation\": \"akamai:validation\",\n    \"detail\": {\n      \"@id\": \"akamai:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"akamai:fieldName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonReference\": {\n      \"@id\": \"akamai:jsonReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"akamai:title\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"config-get\": \"akamai:config-get\",\n    \"latestVersion\": {\n      \"@id\": \"akamai:latestVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"productionHostnames\": {\n      \"@id\": \"akamai:productionHostnames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productionVersion\": {\n      \"@id\": \"akamai:productionVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stagingVersion\": {\n      \"@id\": \"akamai:stagingVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"version-notes-put\": \"akamai:version-notes-put\",\n    \"request-header-condition-2\": \"akamai:request-header-condition-2\",\n    \"overlap-config\": \"akamai:overlap-config\",\n    \"configName\": {\n      \"@id\": \"akamai:configName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contractId\": {\n      \"@id\": \"akamai:contractId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contractName\": {\n      \"@id\": \"akamai:contractName\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"waf-config-version\": \"akamai:waf-config-version\",\n    \"basedOn\": {\n      \"@id\": \"akamai:basedOn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"production\": {\n      \"@id\": \"akamai:production\",\n      \"@type\": \"@id\"\n    },\n    \"action\": {\n      \"@id\": \"akamai:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"akamai:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"akamai:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"staging\": {\n      \"@id\": \"akamai:staging\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"versionNotes\": {\n      \"@id\": \"akamai:versionNotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rate-policy-evaluation-put\": \"akamai:rate-policy-evaluation-put\",\n    \"validations\": \"akamai:validations\",\n    \"errors\": {\n      \"@id\": \"akamai:errors\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"notices\": {\n      \"@id\": \"akamai:notices\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"warnings\": {\n      \"@id\": \"akamai:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"siem-settings\": \"akamai:siem-settings\",\n    \"enableForAllPolicies\": {\n      \"@id\": \"akamai:enableForAllPolicies\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableSiem\": {\n      \"@id\": \"akamai:enableSiem\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabledBotmanSiemEvents\": {\n      \"@id\": \"akamai:enabledBotmanSiemEvents\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"exceptions\": {\n      \"@id\": \"akamai:exceptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"firewallPolicyIds\": {\n      \"@id\": \"akamai:firewallPolicyIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"siemDefinitionId\": {\n      \"@id\": \"akamai:siemDefinitionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hostname-object\": \"akamai:hostname-object\",\n    \"activeInProduction\": {\n      \"@id\": \"akamai:activeInProduction\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"activeInStaging\": {\n      \"@id\": \"akamai:activeInStaging\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"arlInclusion\": {\n      \"@id\": \"akamai:arlInclusion\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"configIdInProduction\": {\n      \"@id\": \"akamai:configIdInProduction\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configNameInProduction\": {\n      \"@id\": \"akamai:configNameInProduction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostname\": {\n      \"@id\": \"akamai:hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"custom-deny\": \"akamai:custom-deny\",\n    \"parameters\": {\n      \"@id\": \"akamai:parameters\",\n      \"@container\": \"\
  @set\",\n      \"@type\": \"@id\"\n    },\n    \"match-targets\": \"akamai:match-targets\",\n    \"evasive-path-match-get-200\": \"akamai:evasive-path-match-get-200\",\n    \"enablePathMatch\": {\n      \"@id\": \"akamai:enablePathMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"malware-policies\": \"akamai:malware-policies\",\n    \"malwarePolicies\": {\n      \"@id\": \"akamai:malwarePolicies\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"config-clone-post\": \"akamai:config-clone-post\",\n    \"createFromVersion\": {\n      \"@id\": \"akamai:createFromVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ruleUpdate\": {\n      \"@id\": \"akamai:ruleUpdate\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"header-logging-get-200\": \"akamai:header-logging-get-200\",\n    \"siem-version\": \"akamai:siem-version\",\n    \"request-body\": \"akamai:request-body\",\n    \"requestBodyInspectionLimitInKB\": {\n      \"@id\": \"akamai:requestBodyInspectionLimitInKB\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"problem-details\": \"akamai:problem-details\",\n    \"fieldErrors\": {\n      \"@id\": \"akamai:fieldErrors\",\n      \"@type\": \"@id\"\n    },\n    \"instance\": {\n      \"@id\": \"akamai:instance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pii-learning\": \"akamai:pii-learning\",\n    \"enablePiiLearning\": {\n      \"@id\": \"akamai:enablePiiLearning\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"configs-get\": \"akamai:configs-get\",\n    \"configurations\": {\n      \"@id\": \"akamai:configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hostname-coverage-match-target\": \"akamai:hostname-coverage-match-target\",\n    \"apis\": {\n      \"@id\": \"akamai:apis\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"bypassNetworkLists\": {\n      \"@id\": \"akamai:bypassNetworkLists\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"defaultFile\"\
  : {\n      \"@id\": \"akamai:defaultFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveSecurityControls\": {\n      \"@id\": \"akamai:effectiveSecurityControls\",\n      \"@type\": \"@id\"\n    },\n    \"applyApiConstraints\": {\n      \"@id\": \"akamai:applyApiConstraints\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applyApplicationLayerControls\": {\n      \"@id\": \"akamai:applyApplicationLayerControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applyBotmanControls\": {\n      \"@id\": \"akamai:applyBotmanControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applyNetworkLayerControls\": {\n      \"@id\": \"akamai:applyNetworkLayerControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applyRateControls\": {\n      \"@id\": \"akamai:applyRateControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applyReputationControls\": {\n      \"@id\": \"akamai:applyReputationControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applySlowPostControls\"\
  : {\n      \"@id\": \"akamai:applySlowPostControls\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fileExtensions\": {\n      \"@id\": \"akamai:fileExtensions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePaths\": {\n      \"@id\": \"akamai:filePaths\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isNegativeFileExtensionMatch\": {\n      \"@id\": \"akamai:isNegativeFileExtensionMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isNegativePathMatch\": {\n      \"@id\": \"akamai:isNegativePathMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"securityPolicy\": {\n      \"@id\": \"akamai:securityPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"sequence\": {\n      \"@id\": \"akamai:sequence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"targetId\": {\n      \"@id\": \"akamai:targetId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"custom-rule\": \"akamai:custom-rule\",\n    \"conditions\"\
  : {\n      \"@id\": \"akamai:conditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"effectiveTimePeriod\": \"akamai:effectiveTimePeriod\",\n    \"endDate\": {\n      \"@id\": \"akamai:endDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"akamai:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"inspectRequest\": {\n      \"@id\": \"akamai:inspectRequest\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"inspectResponse\": {\n      \"@id\": \"akamai:inspectResponse\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"loggingOptions\": {\n      \"@id\": \"akamai:loggingOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"metadata\": {\n      \"@id\": \"akamai:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"akamai:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleActivated\": {\n      \"@id\": \"akamai:ruleActivated\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"samplingRate\": {\n      \"@id\": \"akamai:samplingRate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stagingOnly\": {\n      \"@id\": \"akamai:stagingOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"structured\": {\n      \"@id\": \"akamai:structured\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"tag\": {\n      \"@id\": \"akamai:tag\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rate-policy\": \"akamai:rate-policy\",\n    \"additionalMatchOptions\": {\n      \"@id\": \"akamai:additionalMatchOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"apiSelectors\": {\n      \"@id\": \"akamai:apiSelectors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"averageThreshold\": {\n      \"@id\": \"akamai:averageThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bodyParameters\": {\n      \"@id\": \"akamai:bodyParameters\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"burstThreshold\": {\n      \"@id\": \"akamai:burstThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"burstWindow\": {\n      \"@id\": \"akamai:burstWindow\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clientIdentifier\": {\n      \"@id\": \"akamai:clientIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"counterType\": {\n      \"@id\": \"akamai:counterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluation\": {\n      \"@id\": \"akamai:evaluation\",\n      \"@type\": \"@id\"\n    },\n    \"evaluationId\": {\n      \"@id\": \"akamai:evaluationId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"evaluationStatus\": {\n      \"@id\": \"akamai:evaluationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hosts\": {\n      \"@id\": \"akamai:hosts\",\n      \"@type\": \"@id\"\n    },\n    \"matchType\": {\n      \"@id\": \"akamai:matchType\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"path\": {\n      \"@id\": \"akamai:path\",\n      \"@type\": \"@id\"\n    },\n    \"pathMatchType\": {\n      \"@id\": \"akamai:pathMatchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathUriPositiveMatch\": {\n      \"@id\": \"akamai:pathUriPositiveMatch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"queryParameters\": {\n      \"@id\": \"akamai:queryParameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"requestType\": {\n      \"@id\": \"akamai:requestType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sameActionOnIpv6\": {\n      \"@id\": \"akamai:sameActionOnIpv6\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"useXForwardForHeaders\": {\n      \"@id\": \"akamai:useXForwardForHeaders\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"cookie-settings\": \"akamai:cookie-settings\",\n    \"cookieDomain\": {\n      \"@id\": \"akamai:cookieDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useAllSecureTraffic\"\
  : {\n      \"@id\": \"akamai:useAllSecureTraffic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"match-target\": \"akamai:match-target\",\n    \"host-info-in-config\": \"akamai:host-info-in-config\",\n    \"availableSet\": {\n      \"@id\": \"akamai:availableSet\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"errorSet\": {\n      \"@id\": \"akamai:errorSet\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"protectARLInclusionHost\": {\n      \"@id\": \"akamai:protectARLInclusionHost\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"selectedSet\": {\n      \"@id\": \"akamai:selectedSet\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"bypass-network-lists-get\": \"akamai:bypass-network-lists-get\",\n    \"networkLists\": {\n      \"@id\": \"akamai:networkLists\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"logging-option\": \"akamai:logging-option\",\n    \"evasive-path-match-put\"\
  : \"akamai:evasive-path-match-put\",\n    \"header-logging-put-200\": \"akamai:header-logging-put-200\",\n    \"evasive-path-match-put-200\": \"akamai:evasive-path-match-put-200\",\n    \"match-targets-sequence\": \"akamai:match-targets-sequence\",\n    \"targetSequence\": {\n      \"@id\": \"akamai:targetSequence\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hostname-coverage-overlapping-get-200\": \"akamai:hostname-coverage-overlapping-get-200\",\n    \"overLappingList\": {\n      \"@id\": \"akamai:overLappingList\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"attack-payload-logging\": \"akamai:attack-payload-logging\",\n    \"waf-config-versions\": \"akamai:waf-config-versions\",\n    \"lastCreatedVersion\": {\n      \"@id\": \"akamai:lastCreatedVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"akamai:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\"\
  : \"akamai:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"productionActiveVersion\": {\n      \"@id\": \"akamai:productionActiveVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"productionExpediteRequestId\": {\n      \"@id\": \"akamai:productionExpediteRequestId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stagingActiveVersion\": {\n      \"@id\": \"akamai:stagingActiveVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stagingExpediteRequestId\": {\n      \"@id\": \"akamai:stagingExpediteRequestId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalSize\": {\n      \"@id\": \"akamai:totalSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"versionList\": {\n      \"@id\": \"akamai:versionList\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"rate-policies\": \"akamai:rate-policies\",\n    \"ratePolicies\": {\n      \"@id\": \"akamai:ratePolicies\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n \
  \   },\n    \"hostnameList\": {\n      \"@id\": \"akamai:hostnameList\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"mode\": {\n      \"@id\": \"akamai:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"custom-denies\": \"akamai:custom-denies\",\n    \"logging-header-setting\": \"akamai:logging-header-setting\",\n    \"url-protection-policy-hostpath\": \"akamai:url-protection-policy-hostpath\",\n    \"siem-versions\": \"akamai:siem-versions\",\n    \"siemDefinitions\": {\n      \"@id\": \"akamai:siemDefinitions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"pragma-header\": \"akamai:pragma-header\",\n    \"conditionOperator\": {\n      \"@id\": \"akamai:conditionOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"excludeCondition\": {\n      \"@id\": \"akamai:excludeCondition\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"bypass-network-lists-put\": \"akamai:bypass-network-lists-put\"\
  ,\n    \"security-controls\": \"akamai:security-controls\",\n    \"config-rename\": \"akamai:config-rename\",\n    \"malware-policies-content-types\": \"akamai:malware-policies-content-types\",\n    \"malwareContentTypes\": {\n      \"@id\": \"akamai:malwareContentTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tls-fingerprint-condition\": \"akamai:tls-fingerprint-condition\",\n    \"version-notes-put-200\": \"akamai:version-notes-put-200\",\n    \"url-protection-client-list-category\": \"akamai:url-protection-client-list-category\",\n    \"listIds\": {\n      \"@id\": \"akamai:listIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefetch-request-put-200\": \"akamai:prefetch-request-put-200\",\n    \"client-reputation-condition\": \"akamai:client-reputation-condition\",\n    \"config-post\": \"akamai:config-post\",\n    \"createFrom\": {\n      \"@id\": \"akamai:createFrom\",\n      \"@type\": \"@id\"\n  \
  \  },\n    \"groupId\": {\n      \"@id\": \"akamai:groupId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attack-payload-logging-put-200\": \"akamai:attack-payload-logging-put-200\",\n    \"url-protection-bypass-client-list-condition\": \"akamai:url-protection-bypass-client-list-condition\",\n    \"checkIps\": {\n      \"@id\": \"akamai:checkIps\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/json-ld/akamai-api-security-context.jsonld
tags:
- API Discovery
- API Security
- Cloud Security
- Posture Management
- Runtime Protection
- Threat Protection
- JSON-LD
- Linked Data
- Semantic Web
---
