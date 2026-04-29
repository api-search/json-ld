---
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
class_count: 161
classes:
- v1alpha1ResourceRef
- v1alpha1SCMProviderGeneratorFilter
- v1alpha1JWTTokens
- v1alpha1ApplicationSourceKustomize
- v1alpha1ApplicationSource
- v1alpha1GnuPGPublicKeyList
- v1alpha1SyncPolicy
- v1alpha1ConnectionState
- v1alpha1SecretRef
- v1alpha1ResourceActionParam
- v1alpha1ChartDetails
- v1alpha1ClusterResourceRestrictionItem
- v1alpha1Command
- v1alpha1KustomizeReplica
- v1alpha1ClusterGenerator
- v1alpha1ManagedNamespaceMetadata
- v1alpha1ApplicationSetApplicationStatus
- v1alpha1MergeGenerator
- v1alpha1ListGenerator
- v1alpha1PullRequestGeneratorGithub
- v1alpha1PullRequestGeneratorBitbucketServer
- v1alpha1Backoff
- v1alpha1AWSAuthConfig
- v1alpha1OrphanedResourceKey
- v1alpha1SCMProviderGeneratorGitlab
- v1alpha1ApplicationSetGenerator
- v1alpha1RevisionReference
- v1alpha1AppProjectStatus
- v1alpha1HostInfo
- v1alpha1ApplicationSourcePlugin
- v1alpha1ConfigManagementPlugin
- v1alpha1RepoCreds
- v1alpha1SCMProviderGenerator
- v1alpha1GitFileGeneratorItem
- v1alpha1ResourceNetworkingInfo
- v1alpha1SyncWindow
- v1alpha1SyncStrategyHook
- v1alpha1SyncOperation
- v1alpha1Info
- v1alpha1PullRequestGeneratorFilter
- v1alpha1Operation
- v1alpha1ConfigMapKeyRef
- v1alpha1ClusterInfo
- v1alpha1JsonnetVar
- v1alpha1ApplicationSetTree
- v1alpha1ApplicationSetRolloutStep
- v1alpha1ApplicationList
- v1alpha1BearerTokenBitbucket
- v1alpha1SyncOperationResult
- v1alpha1ApplicationSourceHelm
- v1alpha1GitGenerator
- v1alpha1RepositoryCertificate
- v1alpha1ApplicationSpec
- v1alpha1SCMProviderGeneratorAWSCodeCommit
- v1alpha1ResourceAction
- v1alpha1SCMProviderGeneratorAzureDevOps
- v1alpha1ApplicationSourceDirectory
- v1alpha1PullRequestGeneratorBitbucket
- v1alpha1SyncSource
- v1alpha1ResourceResult
- v1alpha1KustomizeVersion
- v1alpha1PluginGenerator
- v1alpha1SCMProviderGeneratorGithub
- v1alpha1RepositoryList
- v1alpha1Application
- v1alpha1RevisionMetadata
- v1alpha1SyncOperationResource
- v1alpha1ApplicationSetNestedGenerator
- v1alpha1SyncStrategyApply
- v1alpha1ApplicationSummary
- v1alpha1ApplicationCondition
- v1alpha1ResourceIgnoreDifferences
- v1alpha1ApplicationSet
- v1alpha1ApplicationSetSyncPolicy
- v1alpha1HydrateTo
- v1alpha1DuckTypeGenerator
- v1alpha1AppHealthStatus
- v1alpha1SourceHydratorStatus
- v1alpha1OCIMetadata
- v1alpha1RevisionHistory
- v1alpha1ClusterConfig
- v1alpha1ApplicationSetStatus
- v1alpha1ResourceDiff
- v1alpha1Repository
- v1alpha1ApplicationSourceJsonnet
- v1alpha1ProjectRole
- v1alpha1SourceHydrator
- v1alpha1HydrateOperation
- v1alpha1AppProject
- v1alpha1BasicAuthBitbucketServer
- v1alpha1ComparedTo
- v1alpha1PluginInput
- v1alpha1SyncStrategy
- v1alpha1GitDirectoryGeneratorItem
- v1alpha1SCMProviderGeneratorBitbucketServer
- v1alpha1SCMProviderGeneratorBitbucket
- v1alpha1ApplicationDestination
- v1alpha1GnuPGPublicKey
- v1alpha1PluginConfigMapRef
- v1alpha1ApplicationSetCondition
- v1alpha1BearerTokenBitbucketCloud
- v1alpha1SignatureKey
- v1alpha1ApplicationSourcePluginParameter
- v1alpha1KustomizeGvk
- v1alpha1HelmParameter
- v1alpha1DrySource
- v1alpha1PullRequestGeneratorAzureDevOps
- v1alpha1ApplicationSetWatchEvent
- v1alpha1PullRequestGenerator
- v1alpha1SyncStatus
- v1alpha1KustomizeSelector
- v1alpha1TagFilter
- v1alpha1KnownTypeField
- v1alpha1HelmFileParameter
- v1alpha1HostResourceInfo
- v1alpha1ResourceNode
- v1alpha1KustomizeResId
- v1alpha1JWTToken
- v1alpha1ExecProviderConfig
- v1alpha1RetryStrategy
- v1alpha1ApplicationSetTemplateMeta
- v1alpha1ApplicationDestinationServiceAccount
- v1alpha1OperationState
- v1alpha1HealthStatus
- v1alpha1InfoItem
- v1alpha1Cluster
- v1alpha1ApplicationTree
- v1alpha1SyncPolicyAutomated
- v1alpha1ApplicationSetList
- v1alpha1PullRequestGeneratorGitea
- v1alpha1AppProjectSpec
- v1alpha1ApplicationSetSpec
- v1alpha1RepoCredsList
- v1alpha1AppProjectList
- v1alpha1ResourceOverride
- v1alpha1ApplicationSetRolloutStrategy
- v1alpha1ApplicationWatchEvent
- v1alpha1ApplicationPreservedFields
- v1alpha1MatrixGenerator
- v1alpha1SCMProviderGeneratorGitea
- v1alpha1OperationInitiator
- v1alpha1SuccessfulHydrateOperation
- v1alpha1ApplicationStatus
- v1alpha1ApplicationSetTemplate
- v1alpha1ApplicationSetStrategy
- v1alpha1OrphanedResourcesMonitorSettings
- v1alpha1ApplicationMatchExpression
- v1alpha1KustomizeOptions
- v1alpha1KustomizePatch
- v1alpha1RepositoryCertificateList
- v1alpha1CommitMetadata
- v1alpha1ApplicationSetResourceIgnoreDifferences
- v1alpha1TLSClientConfig
- v1alpha1ClusterCacheInfo
- v1alpha1ClusterList
- v1alpha1PullRequestGeneratorGitLab
- v1alpha1OverrideIgnoreDiff
- name
- version
- description
- url
context_file: json-ld/argo-cd-v1alpha1-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-v1alpha1-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Argo Cd V1Alpha1 from Argo CD.
layout: jsonld
name: Argo Cd V1Alpha1 Context
namespaces:
- prefix: argocd
  uri: https://argoproj.github.io/schema/argo-cd/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: group
  type: string
- container: ''
  name: kind
  type: string
- container: ''
  name: namespace
  type: string
- container: ''
  name: uid
  type: string
- container: ''
  name: branchMatch
  type: string
- container: ''
  name: labelMatch
  type: string
- container: set
  name: pathsDoNotExist
  type: string
- container: set
  name: pathsExist
  type: string
- container: ''
  name: repositoryMatch
  type: string
- container: set
  name: items
  type: string
- container: set
  name: apiVersions
  type: string
- container: ''
  name: commonAnnotations
  type: reference
- container: ''
  name: commonAnnotationsEnvsubst
  type: boolean
- container: ''
  name: commonLabels
  type: reference
- container: set
  name: components
  type: string
- container: ''
  name: forceCommonAnnotations
  type: boolean
- container: ''
  name: forceCommonLabels
  type: boolean
- container: ''
  name: ignoreMissingComponents
  type: boolean
- container: set
  name: images
  type: string
- container: ''
  name: kubeVersion
  type: string
- container: ''
  name: labelIncludeTemplates
  type: boolean
- container: ''
  name: labelWithoutSelector
  type: boolean
- container: ''
  name: namePrefix
  type: string
- container: ''
  name: nameSuffix
  type: string
- container: set
  name: patches
  type: string
- container: set
  name: replicas
  type: string
- container: ''
  name: chart
  type: string
- container: ''
  name: directory
  type: string
- container: ''
  name: helm
  type: string
- container: ''
  name: kustomize
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: plugin
  type: string
- container: ''
  name: ref
  type: string
- container: ''
  name: repoURL
  type: string
- container: ''
  name: targetRevision
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: automated
  type: string
- container: ''
  name: managedNamespaceMetadata
  type: string
- container: ''
  name: retry
  type: string
- container: set
  name: syncOptions
  type: string
- container: ''
  name: attemptedAt
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: secretName
  type: string
- container: ''
  name: home
  type: string
- container: set
  name: maintainers
  type: string
- container: set
  name: args
  type: string
- container: set
  name: command
  type: string
- container: ''
  name: count
  type: string
- container: ''
  name: flatList
  type: boolean
- container: ''
  name: selector
  type: string
- container: ''
  name: template
  type: string
- container: ''
  name: values
  type: reference
- container: ''
  name: annotations
  type: reference
- container: ''
  name: labels
  type: reference
- container: ''
  name: application
  type: string
- container: ''
  name: lastTransitionTime
  type: string
- container: ''
  name: step
  type: string
- container: set
  name: targetrevisions
  type: string
- container: set
  name: generators
  type: string
- container: set
  name: mergeKeys
  type: string
- container: set
  name: elements
  type: string
- container: ''
  name: elementsYaml
  type: string
- container: ''
  name: api
  type: string
- container: ''
  name: appSecretName
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: repo
  type: string
- container: ''
  name: tokenRef
  type: string
- container: ''
  name: basicAuth
  type: string
- container: ''
  name: bearerToken
  type: string
- container: ''
  name: caRef
  type: string
- container: ''
  name: insecure
  type: boolean
- container: ''
  name: project
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: factor
  type: integer
- container: ''
  name: maxDuration
  type: string
- container: ''
  name: clusterName
  type: string
- container: ''
  name: profile
  type: string
- container: ''
  name: roleARN
  type: string
- container: ''
  name: allBranches
  type: boolean
- container: ''
  name: includeArchivedRepos
  type: boolean
- container: ''
  name: includeSharedProjects
  type: boolean
- container: ''
  name: includeSubgroups
  type: boolean
- container: ''
  name: topic
  type: string
- container: ''
  name: clusterDecisionResource
  type: string
- container: ''
  name: clusters
  type: string
- container: ''
  name: git
  type: string
- container: ''
  name: list
  type: string
- container: ''
  name: matrix
  type: string
- container: ''
  name: merge
  type: string
- container: ''
  name: pullRequest
  type: string
- container: ''
  name: scmProvider
  type: string
- container: ''
  name: commit
  type: string
- container: ''
  name: jwtTokensByRole
  type: reference
- container: set
  name: resourcesInfo
  type: string
- container: ''
  name: systemInfo
  type: string
- container: set
  name: env
  type: string
- container: set
  name: parameters
  type: string
- container: ''
  name: generate
  type: string
- container: ''
  name: init
  type: string
- container: ''
  name: lockRepo
  type: boolean
- container: ''
  name: azureActiveDirectoryEndpoint
  type: string
- container: ''
  name: azureServicePrincipalClientId
  type: string
- container: ''
  name: azureServicePrincipalClientSecret
  type: string
- container: ''
  name: azureServicePrincipalTenantId
  type: string
- container: ''
  name: enableOCI
  type: boolean
- container: ''
  name: forceHttpBasicAuth
  type: boolean
- container: ''
  name: gcpServiceAccountKey
  type: string
- container: ''
  name: githubAppEnterpriseBaseUrl
  type: string
- container: ''
  name: githubAppID
  type: integer
- container: ''
  name: githubAppInstallationID
  type: integer
- container: ''
  name: githubAppPrivateKey
  type: string
- container: ''
  name: insecureOCIForceHttp
  type: boolean
- container: ''
  name: noProxy
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: proxy
  type: string
- container: ''
  name: sshPrivateKey
  type: string
- container: ''
  name: tlsClientCertData
  type: string
- container: ''
  name: tlsClientCertKey
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: useAzureWorkloadIdentity
  type: boolean
- container: ''
  name: username
  type: string
- container: ''
  name: awsCodeCommit
  type: string
- container: ''
  name: azureDevOps
  type: string
- container: ''
  name: bitbucket
  type: string
- container: ''
  name: bitbucketServer
  type: string
- container: ''
  name: cloneProtocol
  type: string
- container: set
  name: filters
  type: string
- container: ''
  name: gitea
  type: string
- container: ''
  name: github
  type: string
- container: ''
  name: gitlab
  type: string
- container: ''
  name: requeueAfterSeconds
  type: integer
- container: ''
  name: exclude
  type: boolean
- container: set
  name: externalURLs
  type: string
- container: set
  name: ingress
  type: string
- container: ''
  name: targetLabels
  type: reference
- container: set
  name: targetRefs
  type: string
- container: ''
  name: andOperator
  type: boolean
- container: set
  name: applications
  type: string
- container: ''
  name: manualSync
  type: boolean
- container: set
  name: namespaces
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: syncOverrun
  type: boolean
- container: ''
  name: timeZone
  type: string
- container: ''
  name: syncStrategyApply
  type: string
- container: ''
  name: autoHealAttemptsCount
  type: integer
- container: ''
  name: dryRun
  type: boolean
- container: set
  name: manifests
  type: string
- container: ''
  name: prune
  type: boolean
- container: set
  name: resources
  type: string
- container: ''
  name: revision
  type: string
- container: set
  name: revisions
  type: string
- container: ''
  name: source
  type: string
- container: set
  name: sources
  type: string
- container: ''
  name: syncStrategy
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: targetBranchMatch
  type: string
- container: ''
  name: titleMatch
  type: string
- container: set
  name: info
  type: string
- container: ''
  name: initiatedBy
  type: string
- container: ''
  name: sync
  type: string
- container: ''
  name: configMapName
  type: string
- container: ''
  name: applicationsCount
  type: integer
- container: ''
  name: cacheInfo
  type: string
- container: ''
  name: connectionState
  type: string
- container: ''
  name: serverVersion
  type: string
- container: ''
  name: code
  type: boolean
- container: set
  name: nodes
  type: string
- container: set
  name: matchExpressions
  type: string
- container: ''
  name: maxUpdate
  type: string
- container: set
  name: fileParameters
  type: string
- container: ''
  name: ignoreMissingValueFiles
  type: boolean
- container: ''
  name: passCredentials
  type: boolean
- container: ''
  name: releaseName
  type: string
- container: ''
  name: skipCrds
  type: boolean
- container: ''
  name: skipSchemaValidation
  type: boolean
- container: ''
  name: skipTests
  type: boolean
- container: set
  name: valueFiles
  type: string
- container: ''
  name: valuesObject
  type: string
- container: set
  name: directories
  type: string
- container: set
  name: files
  type: string
- container: ''
  name: pathParamPrefix
  type: string
- container: ''
  name: certData
  type: string
- container: ''
  name: certInfo
  type: string
- container: ''
  name: certSubType
  type: string
- container: ''
  name: certType
  type: string
- container: ''
  name: serverName
  type: string
- container: ''
  name: destination
  type: string
- container: set
  name: ignoreDifferences
  type: string
- container: ''
  name: revisionHistoryLimit
  type: integer
- container: ''
  name: sourceHydrator
  type: string
- container: ''
  name: syncPolicy
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: role
  type: string
- container: set
  name: tagFilters
  type: string
- container: ''
  name: disabled
  type: boolean
- container: ''
  name: displayName
  type: string
- container: ''
  name: iconClass
  type: string
- container: set
  name: params
  type: string
- container: ''
  name: accessTokenRef
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: teamProject
  type: string
- container: ''
  name: include
  type: string
- container: ''
  name: jsonnet
  type: string
- container: ''
  name: recurse
  type: boolean
- container: ''
  name: targetBranch
  type: string
- container: ''
  name: hookPhase
  type: string
- container: ''
  name: hookType
  type: string
- container: ''
  name: syncPhase
  type: string
- container: ''
  name: buildOptions
  type: string
- container: ''
  name: configMapRef
  type: string
- container: ''
  name: input
  type: string
- container: ''
  name: excludeArchivedRepos
  type: boolean
- container: ''
  name: operation
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: date
  type: string
- container: set
  name: references
  type: string
- container: ''
  name: signatureInfo
  type: string
- container: set
  name: tags
  type: string
- container: ''
  name: force
  type: boolean
- container: set
  name: jqPathExpressions
  type: string
- container: set
  name: jsonPointers
  type: string
- container: set
  name: managedFieldsManagers
  type: string
- container: ''
  name: applicationsSync
  type: string
- container: ''
  name: preserveResourcesOnDeletion
  type: boolean
- container: ''
  name: labelSelector
  type: string
- container: ''
  name: currentOperation
  type: string
- container: ''
  name: lastSuccessfulOperation
  type: string
- container: ''
  name: authors
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: docsUrl
  type: string
- container: ''
  name: imageUrl
  type: string
- container: ''
  name: sourceUrl
  type: string
- container: ''
  name: deployStartedAt
  type: string
- container: ''
  name: deployedAt
  type: string
- container: ''
  name: id
  type: integer
- container: ''
  name: awsAuthConfig
  type: string
- container: ''
  name: disableCompression
  type: boolean
- container: ''
  name: execProviderConfig
  type: string
- container: ''
  name: proxyUrl
  type: string
- container: ''
  name: tlsClientConfig
  type: string
- container: set
  name: applicationStatus
  type: string
- container: set
  name: conditions
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: resourcesCount
  type: integer
- container: ''
  name: diff
  type: string
- container: ''
  name: hook
  type: boolean
- container: ''
  name: liveState
  type: string
- container: ''
  name: modified
  type: boolean
- container: ''
  name: normalizedLiveState
  type: string
- container: ''
  name: predictedLiveState
  type: string
- container: ''
  name: resourceVersion
  type: string
- container: ''
  name: targetState
  type: string
- container: ''
  name: depth
  type: integer
- container: ''
  name: enableLfs
  type: boolean
- container: ''
  name: inheritedCreds
  type: boolean
- container: ''
  name: insecureIgnoreHostKey
  type: boolean
- container: ''
  name: webhookManifestCacheWarmDisabled
  type: boolean
- container: set
  name: extVars
  type: string
- container: set
  name: libs
  type: string
- container: set
  name: tlas
  type: string
- container: set
  name: groups
  type: string
- container: set
  name: jwtTokens
  type: string
- container: set
  name: policies
  type: string
- container: ''
  name: drySource
  type: string
- container: ''
  name: hydrateTo
  type: string
- container: ''
  name: syncSource
  type: string
- container: ''
  name: drySHA
  type: string
- container: ''
  name: finishedAt
  type: string
- container: ''
  name: hydratedSHA
  type: string
- container: ''
  name: phase
  type: string
- container: ''
  name: startedAt
  type: string
- container: ''
  name: passwordRef
  type: string
- container: ''
  name: apply
  type: string
- container: ''
  name: appPasswordRef
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: server
  type: string
- container: ''
  name: fingerprint
  type: string
- container: ''
  name: keyData
  type: string
- container: ''
  name: keyID
  type: string
- container: ''
  name: subType
  type: string
- container: ''
  name: trust
  type: string
- container: ''
  name: reason
  type: string
- container: set
  name: array
  type: string
- container: ''
  name: map
  type: reference
- container: ''
  name: string
  type: string
- container: ''
  name: forceString
  type: boolean
- container: ''
  name: applicationSet
  type: string
- container: ''
  name: azuredevops
  type: string
- container: ''
  name: continueOnRepoNotFoundError
  type: boolean
- container: ''
  name: comparedTo
  type: string
- container: ''
  name: annotationSelector
  type: string
- container: ''
  name: resId
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: capacity
  type: integer
- container: ''
  name: requestedByApp
  type: integer
- container: ''
  name: requestedByNeighbors
  type: integer
- container: ''
  name: resourceName
  type: string
- container: ''
  name: networkingInfo
  type: string
- container: set
  name: parentRefs
  type: string
- container: ''
  name: gvk
  type: string
- container: ''
  name: exp
  type: integer
- container: ''
  name: iat
  type: integer
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: installHint
  type: string
- container: ''
  name: backoff
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: refresh
  type: boolean
- container: set
  name: finalizers
  type: string
- container: ''
  name: defaultServiceAccount
  type: string
- container: ''
  name: retryCount
  type: integer
- container: ''
  name: syncResult
  type: string
- container: ''
  name: clusterResources
  type: boolean
- container: ''
  name: config
  type: string
- container: ''
  name: refreshRequestedAt
  type: string
- container: ''
  name: shard
  type: integer
- container: set
  name: hosts
  type: string
- container: set
  name: orphanedNodes
  type: string
- container: ''
  name: shardsCount
  type: integer
- container: ''
  name: allowEmpty
  type: boolean
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: selfHeal
  type: boolean
- container: set
  name: clusterResourceBlacklist
  type: string
- container: set
  name: clusterResourceWhitelist
  type: string
- container: set
  name: destinationServiceAccounts
  type: string
- container: set
  name: destinations
  type: string
- container: set
  name: namespaceResourceBlacklist
  type: string
- container: set
  name: namespaceResourceWhitelist
  type: string
- container: ''
  name: orphanedResources
  type: string
- container: ''
  name: permitOnlyProjectScopedClusters
  type: boolean
- container: set
  name: roles
  type: string
- container: set
  name: signatureKeys
  type: string
- container: set
  name: sourceNamespaces
  type: string
- container: set
  name: sourceRepos
  type: string
- container: set
  name: syncWindows
  type: string
- container: ''
  name: applyNestedSelectors
  type: boolean
- container: ''
  name: goTemplate
  type: boolean
- container: set
  name: goTemplateOptions
  type: string
- container: set
  name: ignoreApplicationDifferences
  type: string
- container: ''
  name: preservedFields
  type: string
- container: ''
  name: strategy
  type: string
- container: ''
  name: templatePatch
  type: string
- container: ''
  name: actions
  type: string
- container: ''
  name: healthLua
  type: string
- container: ''
  name: ignoreResourceUpdates
  type: string
- container: set
  name: knownTypeFields
  type: string
- container: ''
  name: useOpenLibs
  type: boolean
- container: set
  name: steps
  type: string
- container: ''
  name: controllerNamespace
  type: string
- container: set
  name: history
  type: string
- container: ''
  name: observedAt
  type: string
- container: ''
  name: operationState
  type: string
- container: ''
  name: reconciledAt
  type: string
- container: ''
  name: resourceHealthSource
  type: string
- container: ''
  name: sourceType
  type: string
- container: set
  name: sourceTypes
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: deletionOrder
  type: string
- container: ''
  name: rollingSync
  type: string
- container: set
  name: ignore
  type: string
- container: ''
  name: warn
  type: boolean
- container: ''
  name: operator
  type: string
- container: ''
  name: binaryPath
  type: string
- container: set
  name: versions
  type: string
- container: ''
  name: options
  type: reference
- container: ''
  name: patch
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: body
  type: string
- container: ''
  name: repoUrl
  type: string
- container: ''
  name: sha
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: caData
  type: string
- container: ''
  name: apisCount
  type: integer
- container: ''
  name: lastCacheSyncTime
  type: string
- container: ''
  name: pullRequestState
  type: string
- container: set
  name: jSONPointers
  type: string
property_count: 378
provider_name: Argo CD
provider_slug: argo-cd
slug: argo-cd-v1alpha1-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"argocd\": \"https://argoproj.github.io/schema/argo-cd/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"v1alpha1ResourceRef\": \"argocd:v1alpha1ResourceRef\",\n    \"v1alpha1SCMProviderGeneratorFilter\": \"argocd:v1alpha1SCMProviderGeneratorFilter\",\n    \"v1alpha1JWTTokens\": \"argocd:v1alpha1JWTTokens\",\n    \"v1alpha1ApplicationSourceKustomize\": \"argocd:v1alpha1ApplicationSourceKustomize\",\n    \"v1alpha1ApplicationSource\": \"argocd:v1alpha1ApplicationSource\",\n    \"v1alpha1GnuPGPublicKeyList\": \"argocd:v1alpha1GnuPGPublicKeyList\",\n    \"v1alpha1SyncPolicy\": \"argocd:v1alpha1SyncPolicy\",\n    \"v1alpha1ConnectionState\": \"argocd:v1alpha1ConnectionState\",\n    \"v1alpha1SecretRef\": \"argocd:v1alpha1SecretRef\",\n    \"v1alpha1ResourceActionParam\": \"argocd:v1alpha1ResourceActionParam\",\n    \"v1alpha1ChartDetails\"\
  : \"argocd:v1alpha1ChartDetails\",\n    \"v1alpha1ClusterResourceRestrictionItem\": \"argocd:v1alpha1ClusterResourceRestrictionItem\",\n    \"v1alpha1Command\": \"argocd:v1alpha1Command\",\n    \"v1alpha1KustomizeReplica\": \"argocd:v1alpha1KustomizeReplica\",\n    \"v1alpha1ClusterGenerator\": \"argocd:v1alpha1ClusterGenerator\",\n    \"v1alpha1ManagedNamespaceMetadata\": \"argocd:v1alpha1ManagedNamespaceMetadata\",\n    \"v1alpha1ApplicationSetApplicationStatus\": \"argocd:v1alpha1ApplicationSetApplicationStatus\",\n    \"v1alpha1MergeGenerator\": \"argocd:v1alpha1MergeGenerator\",\n    \"v1alpha1ListGenerator\": \"argocd:v1alpha1ListGenerator\",\n    \"v1alpha1PullRequestGeneratorGithub\": \"argocd:v1alpha1PullRequestGeneratorGithub\",\n    \"v1alpha1PullRequestGeneratorBitbucketServer\": \"argocd:v1alpha1PullRequestGeneratorBitbucketServer\",\n    \"v1alpha1Backoff\": \"argocd:v1alpha1Backoff\",\n    \"v1alpha1AWSAuthConfig\": \"argocd:v1alpha1AWSAuthConfig\",\n    \"v1alpha1OrphanedResourceKey\"\
  : \"argocd:v1alpha1OrphanedResourceKey\",\n    \"v1alpha1SCMProviderGeneratorGitlab\": \"argocd:v1alpha1SCMProviderGeneratorGitlab\",\n    \"v1alpha1ApplicationSetGenerator\": \"argocd:v1alpha1ApplicationSetGenerator\",\n    \"v1alpha1RevisionReference\": \"argocd:v1alpha1RevisionReference\",\n    \"v1alpha1AppProjectStatus\": \"argocd:v1alpha1AppProjectStatus\",\n    \"v1alpha1HostInfo\": \"argocd:v1alpha1HostInfo\",\n    \"v1alpha1ApplicationSourcePlugin\": \"argocd:v1alpha1ApplicationSourcePlugin\",\n    \"v1alpha1ConfigManagementPlugin\": \"argocd:v1alpha1ConfigManagementPlugin\",\n    \"v1alpha1RepoCreds\": \"argocd:v1alpha1RepoCreds\",\n    \"v1alpha1SCMProviderGenerator\": \"argocd:v1alpha1SCMProviderGenerator\",\n    \"v1alpha1GitFileGeneratorItem\": \"argocd:v1alpha1GitFileGeneratorItem\",\n    \"v1alpha1ResourceNetworkingInfo\": \"argocd:v1alpha1ResourceNetworkingInfo\",\n    \"v1alpha1SyncWindow\": \"argocd:v1alpha1SyncWindow\",\n    \"v1alpha1SyncStrategyHook\": \"argocd:v1alpha1SyncStrategyHook\"\
  ,\n    \"v1alpha1SyncOperation\": \"argocd:v1alpha1SyncOperation\",\n    \"v1alpha1Info\": \"argocd:v1alpha1Info\",\n    \"v1alpha1PullRequestGeneratorFilter\": \"argocd:v1alpha1PullRequestGeneratorFilter\",\n    \"v1alpha1Operation\": \"argocd:v1alpha1Operation\",\n    \"v1alpha1ConfigMapKeyRef\": \"argocd:v1alpha1ConfigMapKeyRef\",\n    \"v1alpha1ClusterInfo\": \"argocd:v1alpha1ClusterInfo\",\n    \"v1alpha1JsonnetVar\": \"argocd:v1alpha1JsonnetVar\",\n    \"v1alpha1ApplicationSetTree\": \"argocd:v1alpha1ApplicationSetTree\",\n    \"v1alpha1ApplicationSetRolloutStep\": \"argocd:v1alpha1ApplicationSetRolloutStep\",\n    \"v1alpha1ApplicationList\": \"argocd:v1alpha1ApplicationList\",\n    \"v1alpha1BearerTokenBitbucket\": \"argocd:v1alpha1BearerTokenBitbucket\",\n    \"v1alpha1SyncOperationResult\": \"argocd:v1alpha1SyncOperationResult\",\n    \"v1alpha1ApplicationSourceHelm\": \"argocd:v1alpha1ApplicationSourceHelm\",\n    \"v1alpha1GitGenerator\": \"argocd:v1alpha1GitGenerator\",\n\
  \    \"v1alpha1RepositoryCertificate\": \"argocd:v1alpha1RepositoryCertificate\",\n    \"v1alpha1ApplicationSpec\": \"argocd:v1alpha1ApplicationSpec\",\n    \"v1alpha1SCMProviderGeneratorAWSCodeCommit\": \"argocd:v1alpha1SCMProviderGeneratorAWSCodeCommit\",\n    \"v1alpha1ResourceAction\": \"argocd:v1alpha1ResourceAction\",\n    \"v1alpha1SCMProviderGeneratorAzureDevOps\": \"argocd:v1alpha1SCMProviderGeneratorAzureDevOps\",\n    \"v1alpha1ApplicationSourceDirectory\": \"argocd:v1alpha1ApplicationSourceDirectory\",\n    \"v1alpha1PullRequestGeneratorBitbucket\": \"argocd:v1alpha1PullRequestGeneratorBitbucket\",\n    \"v1alpha1SyncSource\": \"argocd:v1alpha1SyncSource\",\n    \"v1alpha1ResourceResult\": \"argocd:v1alpha1ResourceResult\",\n    \"v1alpha1KustomizeVersion\": \"argocd:v1alpha1KustomizeVersion\",\n    \"v1alpha1PluginGenerator\": \"argocd:v1alpha1PluginGenerator\",\n    \"v1alpha1SCMProviderGeneratorGithub\": \"argocd:v1alpha1SCMProviderGeneratorGithub\",\n    \"v1alpha1RepositoryList\"\
  : \"argocd:v1alpha1RepositoryList\",\n    \"v1alpha1Application\": \"argocd:v1alpha1Application\",\n    \"v1alpha1RevisionMetadata\": \"argocd:v1alpha1RevisionMetadata\",\n    \"v1alpha1SyncOperationResource\": \"argocd:v1alpha1SyncOperationResource\",\n    \"v1alpha1ApplicationSetNestedGenerator\": \"argocd:v1alpha1ApplicationSetNestedGenerator\",\n    \"v1alpha1SyncStrategyApply\": \"argocd:v1alpha1SyncStrategyApply\",\n    \"v1alpha1ApplicationSummary\": \"argocd:v1alpha1ApplicationSummary\",\n    \"v1alpha1ApplicationCondition\": \"argocd:v1alpha1ApplicationCondition\",\n    \"v1alpha1ResourceIgnoreDifferences\": \"argocd:v1alpha1ResourceIgnoreDifferences\",\n    \"v1alpha1ApplicationSet\": \"argocd:v1alpha1ApplicationSet\",\n    \"v1alpha1ApplicationSetSyncPolicy\": \"argocd:v1alpha1ApplicationSetSyncPolicy\",\n    \"v1alpha1HydrateTo\": \"argocd:v1alpha1HydrateTo\",\n    \"v1alpha1DuckTypeGenerator\": \"argocd:v1alpha1DuckTypeGenerator\",\n    \"v1alpha1AppHealthStatus\": \"argocd:v1alpha1AppHealthStatus\"\
  ,\n    \"v1alpha1SourceHydratorStatus\": \"argocd:v1alpha1SourceHydratorStatus\",\n    \"v1alpha1OCIMetadata\": \"argocd:v1alpha1OCIMetadata\",\n    \"v1alpha1RevisionHistory\": \"argocd:v1alpha1RevisionHistory\",\n    \"v1alpha1ClusterConfig\": \"argocd:v1alpha1ClusterConfig\",\n    \"v1alpha1ApplicationSetStatus\": \"argocd:v1alpha1ApplicationSetStatus\",\n    \"v1alpha1ResourceDiff\": \"argocd:v1alpha1ResourceDiff\",\n    \"v1alpha1Repository\": \"argocd:v1alpha1Repository\",\n    \"v1alpha1ApplicationSourceJsonnet\": \"argocd:v1alpha1ApplicationSourceJsonnet\",\n    \"v1alpha1ProjectRole\": \"argocd:v1alpha1ProjectRole\",\n    \"v1alpha1SourceHydrator\": \"argocd:v1alpha1SourceHydrator\",\n    \"v1alpha1HydrateOperation\": \"argocd:v1alpha1HydrateOperation\",\n    \"v1alpha1AppProject\": \"argocd:v1alpha1AppProject\",\n    \"v1alpha1BasicAuthBitbucketServer\": \"argocd:v1alpha1BasicAuthBitbucketServer\",\n    \"v1alpha1ComparedTo\": \"argocd:v1alpha1ComparedTo\",\n    \"v1alpha1PluginInput\"\
  : \"argocd:v1alpha1PluginInput\",\n    \"v1alpha1SyncStrategy\": \"argocd:v1alpha1SyncStrategy\",\n    \"v1alpha1GitDirectoryGeneratorItem\": \"argocd:v1alpha1GitDirectoryGeneratorItem\",\n    \"v1alpha1SCMProviderGeneratorBitbucketServer\": \"argocd:v1alpha1SCMProviderGeneratorBitbucketServer\",\n    \"v1alpha1SCMProviderGeneratorBitbucket\": \"argocd:v1alpha1SCMProviderGeneratorBitbucket\",\n    \"v1alpha1ApplicationDestination\": \"argocd:v1alpha1ApplicationDestination\",\n    \"v1alpha1GnuPGPublicKey\": \"argocd:v1alpha1GnuPGPublicKey\",\n    \"v1alpha1PluginConfigMapRef\": \"argocd:v1alpha1PluginConfigMapRef\",\n    \"v1alpha1ApplicationSetCondition\": \"argocd:v1alpha1ApplicationSetCondition\",\n    \"v1alpha1BearerTokenBitbucketCloud\": \"argocd:v1alpha1BearerTokenBitbucketCloud\",\n    \"v1alpha1SignatureKey\": \"argocd:v1alpha1SignatureKey\",\n    \"v1alpha1ApplicationSourcePluginParameter\": \"argocd:v1alpha1ApplicationSourcePluginParameter\",\n    \"v1alpha1KustomizeGvk\": \"\
  argocd:v1alpha1KustomizeGvk\",\n    \"v1alpha1HelmParameter\": \"argocd:v1alpha1HelmParameter\",\n    \"v1alpha1DrySource\": \"argocd:v1alpha1DrySource\",\n    \"v1alpha1PullRequestGeneratorAzureDevOps\": \"argocd:v1alpha1PullRequestGeneratorAzureDevOps\",\n    \"v1alpha1ApplicationSetWatchEvent\": \"argocd:v1alpha1ApplicationSetWatchEvent\",\n    \"v1alpha1PullRequestGenerator\": \"argocd:v1alpha1PullRequestGenerator\",\n    \"v1alpha1SyncStatus\": \"argocd:v1alpha1SyncStatus\",\n    \"v1alpha1KustomizeSelector\": \"argocd:v1alpha1KustomizeSelector\",\n    \"v1alpha1TagFilter\": \"argocd:v1alpha1TagFilter\",\n    \"v1alpha1KnownTypeField\": \"argocd:v1alpha1KnownTypeField\",\n    \"v1alpha1HelmFileParameter\": \"argocd:v1alpha1HelmFileParameter\",\n    \"v1alpha1HostResourceInfo\": \"argocd:v1alpha1HostResourceInfo\",\n    \"v1alpha1ResourceNode\": \"argocd:v1alpha1ResourceNode\",\n    \"v1alpha1KustomizeResId\": \"argocd:v1alpha1KustomizeResId\",\n    \"v1alpha1JWTToken\": \"argocd:v1alpha1JWTToken\"\
  ,\n    \"v1alpha1ExecProviderConfig\": \"argocd:v1alpha1ExecProviderConfig\",\n    \"v1alpha1RetryStrategy\": \"argocd:v1alpha1RetryStrategy\",\n    \"v1alpha1ApplicationSetTemplateMeta\": \"argocd:v1alpha1ApplicationSetTemplateMeta\",\n    \"v1alpha1ApplicationDestinationServiceAccount\": \"argocd:v1alpha1ApplicationDestinationServiceAccount\",\n    \"v1alpha1OperationState\": \"argocd:v1alpha1OperationState\",\n    \"v1alpha1HealthStatus\": \"argocd:v1alpha1HealthStatus\",\n    \"v1alpha1InfoItem\": \"argocd:v1alpha1InfoItem\",\n    \"v1alpha1Cluster\": \"argocd:v1alpha1Cluster\",\n    \"v1alpha1ApplicationTree\": \"argocd:v1alpha1ApplicationTree\",\n    \"v1alpha1SyncPolicyAutomated\": \"argocd:v1alpha1SyncPolicyAutomated\",\n    \"v1alpha1ApplicationSetList\": \"argocd:v1alpha1ApplicationSetList\",\n    \"v1alpha1PullRequestGeneratorGitea\": \"argocd:v1alpha1PullRequestGeneratorGitea\",\n    \"v1alpha1AppProjectSpec\": \"argocd:v1alpha1AppProjectSpec\",\n    \"v1alpha1ApplicationSetSpec\"\
  : \"argocd:v1alpha1ApplicationSetSpec\",\n    \"v1alpha1RepoCredsList\": \"argocd:v1alpha1RepoCredsList\",\n    \"v1alpha1AppProjectList\": \"argocd:v1alpha1AppProjectList\",\n    \"v1alpha1ResourceOverride\": \"argocd:v1alpha1ResourceOverride\",\n    \"v1alpha1ApplicationSetRolloutStrategy\": \"argocd:v1alpha1ApplicationSetRolloutStrategy\",\n    \"v1alpha1ApplicationWatchEvent\": \"argocd:v1alpha1ApplicationWatchEvent\",\n    \"v1alpha1ApplicationPreservedFields\": \"argocd:v1alpha1ApplicationPreservedFields\",\n    \"v1alpha1MatrixGenerator\": \"argocd:v1alpha1MatrixGenerator\",\n    \"v1alpha1SCMProviderGeneratorGitea\": \"argocd:v1alpha1SCMProviderGeneratorGitea\",\n    \"v1alpha1OperationInitiator\": \"argocd:v1alpha1OperationInitiator\",\n    \"v1alpha1SuccessfulHydrateOperation\": \"argocd:v1alpha1SuccessfulHydrateOperation\",\n    \"v1alpha1ApplicationStatus\": \"argocd:v1alpha1ApplicationStatus\",\n    \"v1alpha1ApplicationSetTemplate\": \"argocd:v1alpha1ApplicationSetTemplate\"\
  ,\n    \"v1alpha1ApplicationSetStrategy\": \"argocd:v1alpha1ApplicationSetStrategy\",\n    \"v1alpha1OrphanedResourcesMonitorSettings\": \"argocd:v1alpha1OrphanedResourcesMonitorSettings\",\n    \"v1alpha1ApplicationMatchExpression\": \"argocd:v1alpha1ApplicationMatchExpression\",\n    \"v1alpha1KustomizeOptions\": \"argocd:v1alpha1KustomizeOptions\",\n    \"v1alpha1KustomizePatch\": \"argocd:v1alpha1KustomizePatch\",\n    \"v1alpha1RepositoryCertificateList\": \"argocd:v1alpha1RepositoryCertificateList\",\n    \"v1alpha1CommitMetadata\": \"argocd:v1alpha1CommitMetadata\",\n    \"v1alpha1ApplicationSetResourceIgnoreDifferences\": \"argocd:v1alpha1ApplicationSetResourceIgnoreDifferences\",\n    \"v1alpha1TLSClientConfig\": \"argocd:v1alpha1TLSClientConfig\",\n    \"v1alpha1ClusterCacheInfo\": \"argocd:v1alpha1ClusterCacheInfo\",\n    \"v1alpha1ClusterList\": \"argocd:v1alpha1ClusterList\",\n    \"v1alpha1PullRequestGeneratorGitLab\": \"argocd:v1alpha1PullRequestGeneratorGitLab\",\n    \"\
  v1alpha1OverrideIgnoreDiff\": \"argocd:v1alpha1OverrideIgnoreDiff\",\n    \"group\": {\n      \"@id\": \"argocd:group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kind\": {\n      \"@id\": \"argocd:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"namespace\": {\n      \"@id\": \"argocd:namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uid\": {\n      \"@id\": \"argocd:uid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"branchMatch\": {\n      \"@id\": \"argocd:branchMatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labelMatch\": {\n      \"@id\": \"argocd:labelMatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathsDoNotExist\": {\n      \"@id\": \"argocd:pathsDoNotExist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathsExist\": {\n      \"@id\": \"argocd:pathsExist\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"repositoryMatch\": {\n      \"@id\": \"argocd:repositoryMatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"argocd:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiVersions\": {\n      \"@id\": \"argocd:apiVersions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commonAnnotations\": {\n      \"@id\": \"argocd:commonAnnotations\",\n      \"@type\": \"@id\"\n    },\n    \"commonAnnotationsEnvsubst\": {\n      \"@id\": \"argocd:commonAnnotationsEnvsubst\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"commonLabels\": {\n      \"@id\": \"argocd:commonLabels\",\n      \"@type\": \"@id\"\n    },\n    \"components\": {\n      \"@id\": \"argocd:components\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forceCommonAnnotations\": {\n      \"@id\": \"argocd:forceCommonAnnotations\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"forceCommonLabels\"\
  : {\n      \"@id\": \"argocd:forceCommonLabels\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ignoreMissingComponents\": {\n      \"@id\": \"argocd:ignoreMissingComponents\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"images\": {\n      \"@id\": \"argocd:images\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kubeVersion\": {\n      \"@id\": \"argocd:kubeVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labelIncludeTemplates\": {\n      \"@id\": \"argocd:labelIncludeTemplates\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"labelWithoutSelector\": {\n      \"@id\": \"argocd:labelWithoutSelector\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"namePrefix\": {\n      \"@id\": \"argocd:namePrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameSuffix\": {\n      \"@id\": \"argocd:nameSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"patches\": {\n      \"@id\": \"argocd:patches\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"replicas\": {\n      \"@id\": \"argocd:replicas\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chart\": {\n      \"@id\": \"argocd:chart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directory\": {\n      \"@id\": \"argocd:directory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"helm\": {\n      \"@id\": \"argocd:helm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kustomize\": {\n      \"@id\": \"argocd:kustomize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"argocd:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"plugin\": {\n      \"@id\": \"argocd:plugin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ref\": {\n      \"@id\": \"argocd:ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repoURL\": {\n      \"@id\": \"argocd:repoURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetRevision\": {\n      \"@id\": \"argocd:targetRevision\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"argocd:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automated\": {\n      \"@id\": \"argocd:automated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managedNamespaceMetadata\": {\n      \"@id\": \"argocd:managedNamespaceMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retry\": {\n      \"@id\": \"argocd:retry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncOptions\": {\n      \"@id\": \"argocd:syncOptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attemptedAt\": {\n      \"@id\": \"argocd:attemptedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"argocd:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"argocd:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"argocd:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\"\
  : {\n      \"@id\": \"argocd:secretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"home\": {\n      \"@id\": \"argocd:home\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maintainers\": {\n      \"@id\": \"argocd:maintainers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"argocd:args\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"argocd:command\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"argocd:count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flatList\": {\n      \"@id\": \"argocd:flatList\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"selector\": {\n      \"@id\": \"argocd:selector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"template\": {\n      \"@id\": \"argocd:template\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"values\": {\n      \"@id\": \"argocd:values\",\n      \"@type\": \"@id\"\n    },\n    \"annotations\": {\n      \"@id\": \"argocd:annotations\",\n      \"@type\": \"@id\"\n    },\n    \"labels\": {\n      \"@id\": \"argocd:labels\",\n      \"@type\": \"@id\"\n    },\n    \"application\": {\n      \"@id\": \"argocd:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastTransitionTime\": {\n      \"@id\": \"argocd:lastTransitionTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"step\": {\n      \"@id\": \"argocd:step\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetrevisions\": {\n      \"@id\": \"argocd:targetrevisions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generators\": {\n      \"@id\": \"argocd:generators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mergeKeys\": {\n      \"@id\": \"argocd:mergeKeys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"elements\": {\n      \"@id\": \"argocd:elements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elementsYaml\": {\n      \"@id\": \"argocd:elementsYaml\",\n      \"@type\": \"xsd:string\"\n    },\n    \"api\": {\n      \"@id\": \"argocd:api\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appSecretName\": {\n      \"@id\": \"argocd:appSecretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"argocd:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repo\": {\n      \"@id\": \"argocd:repo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenRef\": {\n      \"@id\": \"argocd:tokenRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basicAuth\": {\n      \"@id\": \"argocd:basicAuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bearerToken\": {\n      \"@id\": \"argocd:bearerToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caRef\": {\n      \"@id\": \"argocd:caRef\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"insecure\": {\n      \"@id\": \"argocd:insecure\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"project\": {\n      \"@id\": \"argocd:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"argocd:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"factor\": {\n      \"@id\": \"argocd:factor\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxDuration\": {\n      \"@id\": \"argocd:maxDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterName\": {\n      \"@id\": \"argocd:clusterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"argocd:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleARN\": {\n      \"@id\": \"argocd:roleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allBranches\": {\n      \"@id\": \"argocd:allBranches\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeArchivedRepos\": {\n      \"@id\": \"argocd:includeArchivedRepos\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeSharedProjects\": {\n      \"@id\": \"argocd:includeSharedProjects\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"includeSubgroups\": {\n      \"@id\": \"argocd:includeSubgroups\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"topic\": {\n      \"@id\": \"argocd:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusterDecisionResource\": {\n      \"@id\": \"argocd:clusterDecisionResource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clusters\": {\n      \"@id\": \"argocd:clusters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"git\": {\n      \"@id\": \"argocd:git\",\n      \"@type\": \"xsd:string\"\n    },\n    \"list\": {\n      \"@id\": \"argocd:list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matrix\": {\n      \"@id\": \"argocd:matrix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merge\": {\n      \"@id\": \"argocd:merge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pullRequest\": {\n\
  \      \"@id\": \"argocd:pullRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scmProvider\": {\n      \"@id\": \"argocd:scmProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commit\": {\n      \"@id\": \"argocd:commit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jwtTokensByRole\": {\n      \"@id\": \"argocd:jwtTokensByRole\",\n      \"@type\": \"@id\"\n    },\n    \"resourcesInfo\": {\n      \"@id\": \"argocd:resourcesInfo\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemInfo\": {\n      \"@id\": \"argocd:systemInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"env\": {\n      \"@id\": \"argocd:env\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"argocd:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generate\": {\n      \"@id\": \"argocd:generate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"init\"\
  : {\n      \"@id\": \"argocd:init\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lockRepo\": {\n      \"@id\": \"argocd:lockRepo\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"azureActiveDirectoryEndpoint\": {\n      \"@id\": \"argocd:azureActiveDirectoryEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureServicePrincipalClientId\": {\n      \"@id\": \"argocd:azureServicePrincipalClientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureServicePrincipalClientSecret\": {\n      \"@id\": \"argocd:azureServicePrincipalClientSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureServicePrincipalTenantId\": {\n      \"@id\": \"argocd:azureServicePrincipalTenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableOCI\": {\n      \"@id\": \"argocd:enableOCI\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"forceHttpBasicAuth\": {\n      \"@id\": \"argocd:forceHttpBasicAuth\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"gcpServiceAccountKey\"\
  : {\n      \"@id\": \"argocd:gcpServiceAccountKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"githubAppEnterpriseBaseUrl\": {\n      \"@id\": \"argocd:githubAppEnterpriseBaseUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"githubAppID\": {\n      \"@id\": \"argocd:githubAppID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"githubAppInstallationID\": {\n      \"@id\": \"argocd:githubAppInstallationID\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"githubAppPrivateKey\": {\n      \"@id\": \"argocd:githubAppPrivateKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insecureOCIForceHttp\": {\n      \"@id\": \"argocd:insecureOCIForceHttp\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"noProxy\": {\n      \"@id\": \"argocd:noProxy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"argocd:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"proxy\": {\n      \"@id\": \"argocd:proxy\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"sshPrivateKey\": {\n      \"@id\": \"argocd:sshPrivateKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tlsClientCertData\": {\n      \"@id\": \"argocd:tlsClientCertData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tlsClientCertKey\": {\n      \"@id\": \"argocd:tlsClientCertKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"argocd:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"useAzureWorkloadIdentity\": {\n      \"@id\": \"argocd:useAzureWorkloadIdentity\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"username\": {\n      \"@id\": \"argocd:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsCodeCommit\": {\n      \"@id\": \"argocd:awsCodeCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureDevOps\": {\n      \"@id\": \"argocd:azureDevOps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bitbucket\": {\n      \"@id\": \"argocd:bitbucket\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"bitbucketServer\": {\n      \"@id\": \"argocd:bitbucketServer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloneProtocol\": {\n      \"@id\": \"argocd:cloneProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"argocd:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitea\": {\n      \"@id\": \"argocd:gitea\",\n      \"@type\": \"xsd:string\"\n    },\n    \"github\": {\n      \"@id\": \"argocd:github\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitlab\": {\n      \"@id\": \"argocd:gitlab\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requeueAfterSeconds\": {\n      \"@id\": \"argocd:requeueAfterSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exclude\": {\n      \"@id\": \"argocd:exclude\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"externalURLs\": {\n      \"@id\": \"argocd:externalURLs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"ingress\": {\n      \"@id\": \"argocd:ingress\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetLabels\": {\n      \"@id\": \"argocd:targetLabels\",\n      \"@type\": \"@id\"\n    },\n    \"targetRefs\": {\n      \"@id\": \"argocd:targetRefs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"andOperator\": {\n      \"@id\": \"argocd:andOperator\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applications\": {\n      \"@id\": \"argocd:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manualSync\": {\n      \"@id\": \"argocd:manualSync\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"namespaces\": {\n      \"@id\": \"argocd:namespaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"argocd:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncOverrun\": {\n      \"@id\": \"argocd:syncOverrun\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"timeZone\": {\n      \"@id\": \"argocd:timeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncStrategyApply\": {\n      \"@id\": \"argocd:syncStrategyApply\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoHealAttemptsCount\": {\n      \"@id\": \"argocd:autoHealAttemptsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dryRun\": {\n      \"@id\": \"argocd:dryRun\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"manifests\": {\n      \"@id\": \"argocd:manifests\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prune\": {\n      \"@id\": \"argocd:prune\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resources\": {\n      \"@id\": \"argocd:resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"argocd:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisions\": {\n      \"@id\": \"argocd:revisions\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"argocd:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"argocd:sources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncStrategy\": {\n      \"@id\": \"argocd:syncStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"argocd:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetBranchMatch\": {\n      \"@id\": \"argocd:targetBranchMatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"titleMatch\": {\n      \"@id\": \"argocd:titleMatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"info\": {\n      \"@id\": \"argocd:info\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initiatedBy\": {\n      \"@id\": \"argocd:initiatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sync\": {\n      \"@id\": \"argocd:sync\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"configMapName\": {\n      \"@id\": \"argocd:configMapName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationsCount\": {\n      \"@id\": \"argocd:applicationsCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cacheInfo\": {\n      \"@id\": \"argocd:cacheInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionState\": {\n      \"@id\": \"argocd:connectionState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverVersion\": {\n      \"@id\": \"argocd:serverVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"argocd:code\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nodes\": {\n      \"@id\": \"argocd:nodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchExpressions\": {\n      \"@id\": \"argocd:matchExpressions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxUpdate\": {\n      \"@id\": \"argocd:maxUpdate\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"fileParameters\": {\n      \"@id\": \"argocd:fileParameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ignoreMissingValueFiles\": {\n      \"@id\": \"argocd:ignoreMissingValueFiles\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"passCredentials\": {\n      \"@id\": \"argocd:passCredentials\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"releaseName\": {\n      \"@id\": \"argocd:releaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skipCrds\": {\n      \"@id\": \"argocd:skipCrds\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"skipSchemaValidation\": {\n      \"@id\": \"argocd:skipSchemaValidation\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"skipTests\": {\n      \"@id\": \"argocd:skipTests\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"valueFiles\": {\n      \"@id\": \"argocd:valueFiles\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"valuesObject\": {\n      \"@id\": \"argocd:valuesObject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directories\": {\n      \"@id\": \"argocd:directories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"files\": {\n      \"@id\": \"argocd:files\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pathParamPrefix\": {\n      \"@id\": \"argocd:pathParamPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certData\": {\n      \"@id\": \"argocd:certData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certInfo\": {\n      \"@id\": \"argocd:certInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certSubType\": {\n      \"@id\": \"argocd:certSubType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certType\": {\n      \"@id\": \"argocd:certType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverName\": {\n      \"@id\": \"argocd:serverName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\"\
  : {\n      \"@id\": \"argocd:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ignoreDifferences\": {\n      \"@id\": \"argocd:ignoreDifferences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionHistoryLimit\": {\n      \"@id\": \"argocd:revisionHistoryLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sourceHydrator\": {\n      \"@id\": \"argocd:sourceHydrator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncPolicy\": {\n      \"@id\": \"argocd:syncPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"argocd:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"argocd:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagFilters\": {\n      \"@id\": \"argocd:tagFilters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled\": {\n      \"@id\": \"argocd:disabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n   \
  \ \"displayName\": {\n      \"@id\": \"argocd:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iconClass\": {\n      \"@id\": \"argocd:iconClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"params\": {\n      \"@id\": \"argocd:params\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessTokenRef\": {\n      \"@id\": \"argocd:accessTokenRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\": {\n      \"@id\": \"argocd:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"teamProject\": {\n      \"@id\": \"argocd:teamProject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"include\": {\n      \"@id\": \"argocd:include\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonnet\": {\n      \"@id\": \"argocd:jsonnet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recurse\": {\n      \"@id\": \"argocd:recurse\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"targetBranch\": {\n      \"@id\": \"argocd:targetBranch\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"hookPhase\": {\n      \"@id\": \"argocd:hookPhase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hookType\": {\n      \"@id\": \"argocd:hookType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"syncPhase\": {\n      \"@id\": \"argocd:syncPhase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildOptions\": {\n      \"@id\": \"argocd:buildOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configMapRef\": {\n      \"@id\": \"argocd:configMapRef\",\n      \"@type\": \"xsd:string\"\n    },\n    \"input\": {\n      \"@id\": \"argocd:input\",\n      \"@type\": \"xsd:string\"\n    },\n    \"excludeArchivedRepos\": {\n      \"@id\": \"argocd:excludeArchivedRepos\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"operation\": {\n      \"@id\": \"argocd:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"argocd:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\"\
  : \"argocd:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"date\": {\n      \"@id\": \"argocd:date\",\n      \"@type\": \"xsd:string\"\n    },\n    \"references\": {\n      \"@id\": \"argocd:references\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signatureInfo\": {\n      \"@id\": \"argocd:signatureInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"argocd:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"force\": {\n      \"@id\": \"argocd:force\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"jqPathExpressions\": {\n      \"@id\": \"argocd:jqPathExpressions\",\n      \"@container\": \"@set\",\n    \n\n# --- truncated at 32 KB (46 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-v1alpha1-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/json-ld/argo-cd-v1alpha1-context.jsonld
tags:
- Continuous Delivery
- Containers
- Deployment
- GitOps
- Kubernetes
- CNCF
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
