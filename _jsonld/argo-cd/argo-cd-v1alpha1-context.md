---
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
