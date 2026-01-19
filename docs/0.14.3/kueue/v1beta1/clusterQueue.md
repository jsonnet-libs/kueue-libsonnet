---
permalink: /0.14.3/kueue/v1beta1/clusterQueue/
---

# kueue.v1beta1.clusterQueue

"ClusterQueue is the Schema for the clusterQueue API."

## Index

* [`fn new(name)`](#fn-new)
* [`obj metadata`](#obj-metadata)
  * [`fn withAnnotations(annotations)`](#fn-metadatawithannotations)
  * [`fn withAnnotationsMixin(annotations)`](#fn-metadatawithannotationsmixin)
  * [`fn withClusterName(clusterName)`](#fn-metadatawithclustername)
  * [`fn withCreationTimestamp(creationTimestamp)`](#fn-metadatawithcreationtimestamp)
  * [`fn withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)`](#fn-metadatawithdeletiongraceperiodseconds)
  * [`fn withDeletionTimestamp(deletionTimestamp)`](#fn-metadatawithdeletiontimestamp)
  * [`fn withFinalizers(finalizers)`](#fn-metadatawithfinalizers)
  * [`fn withFinalizersMixin(finalizers)`](#fn-metadatawithfinalizersmixin)
  * [`fn withGenerateName(generateName)`](#fn-metadatawithgeneratename)
  * [`fn withGeneration(generation)`](#fn-metadatawithgeneration)
  * [`fn withLabels(labels)`](#fn-metadatawithlabels)
  * [`fn withLabelsMixin(labels)`](#fn-metadatawithlabelsmixin)
  * [`fn withName(name)`](#fn-metadatawithname)
  * [`fn withNamespace(namespace)`](#fn-metadatawithnamespace)
  * [`fn withOwnerReferences(ownerReferences)`](#fn-metadatawithownerreferences)
  * [`fn withOwnerReferencesMixin(ownerReferences)`](#fn-metadatawithownerreferencesmixin)
  * [`fn withResourceVersion(resourceVersion)`](#fn-metadatawithresourceversion)
  * [`fn withSelfLink(selfLink)`](#fn-metadatawithselflink)
  * [`fn withUid(uid)`](#fn-metadatawithuid)
* [`obj spec`](#obj-spec)
  * [`fn withAdmissionChecks(admissionChecks)`](#fn-specwithadmissionchecks)
  * [`fn withAdmissionChecksMixin(admissionChecks)`](#fn-specwithadmissionchecksmixin)
  * [`fn withCohort(cohort)`](#fn-specwithcohort)
  * [`fn withQueueingStrategy(queueingStrategy)`](#fn-specwithqueueingstrategy)
  * [`fn withResourceGroups(resourceGroups)`](#fn-specwithresourcegroups)
  * [`fn withResourceGroupsMixin(resourceGroups)`](#fn-specwithresourcegroupsmixin)
  * [`fn withStopPolicy(stopPolicy)`](#fn-specwithstoppolicy)
  * [`obj spec.admissionChecksStrategy`](#obj-specadmissionchecksstrategy)
    * [`fn withAdmissionChecks(admissionChecks)`](#fn-specadmissionchecksstrategywithadmissionchecks)
    * [`fn withAdmissionChecksMixin(admissionChecks)`](#fn-specadmissionchecksstrategywithadmissionchecksmixin)
    * [`obj spec.admissionChecksStrategy.admissionChecks`](#obj-specadmissionchecksstrategyadmissionchecks)
      * [`fn withName(name)`](#fn-specadmissionchecksstrategyadmissioncheckswithname)
      * [`fn withOnFlavors(onFlavors)`](#fn-specadmissionchecksstrategyadmissioncheckswithonflavors)
      * [`fn withOnFlavorsMixin(onFlavors)`](#fn-specadmissionchecksstrategyadmissioncheckswithonflavorsmixin)
  * [`obj spec.admissionScope`](#obj-specadmissionscope)
    * [`fn withAdmissionMode(admissionMode)`](#fn-specadmissionscopewithadmissionmode)
  * [`obj spec.fairSharing`](#obj-specfairsharing)
    * [`fn withWeight(weight)`](#fn-specfairsharingwithweight)
  * [`obj spec.flavorFungibility`](#obj-specflavorfungibility)
    * [`fn withWhenCanBorrow(whenCanBorrow)`](#fn-specflavorfungibilitywithwhencanborrow)
    * [`fn withWhenCanPreempt(whenCanPreempt)`](#fn-specflavorfungibilitywithwhencanpreempt)
  * [`obj spec.namespaceSelector`](#obj-specnamespaceselector)
    * [`fn withMatchExpressions(matchExpressions)`](#fn-specnamespaceselectorwithmatchexpressions)
    * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specnamespaceselectorwithmatchexpressionsmixin)
    * [`fn withMatchLabels(matchLabels)`](#fn-specnamespaceselectorwithmatchlabels)
    * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specnamespaceselectorwithmatchlabelsmixin)
    * [`obj spec.namespaceSelector.matchExpressions`](#obj-specnamespaceselectormatchexpressions)
      * [`fn withKey(key)`](#fn-specnamespaceselectormatchexpressionswithkey)
      * [`fn withOperator(operator)`](#fn-specnamespaceselectormatchexpressionswithoperator)
      * [`fn withValues(values)`](#fn-specnamespaceselectormatchexpressionswithvalues)
      * [`fn withValuesMixin(values)`](#fn-specnamespaceselectormatchexpressionswithvaluesmixin)
  * [`obj spec.preemption`](#obj-specpreemption)
    * [`fn withReclaimWithinCohort(reclaimWithinCohort)`](#fn-specpreemptionwithreclaimwithincohort)
    * [`fn withWithinClusterQueue(withinClusterQueue)`](#fn-specpreemptionwithwithinclusterqueue)
    * [`obj spec.preemption.borrowWithinCohort`](#obj-specpreemptionborrowwithincohort)
      * [`fn withMaxPriorityThreshold(maxPriorityThreshold)`](#fn-specpreemptionborrowwithincohortwithmaxprioritythreshold)
      * [`fn withPolicy(policy)`](#fn-specpreemptionborrowwithincohortwithpolicy)
  * [`obj spec.resourceGroups`](#obj-specresourcegroups)
    * [`fn withCoveredResources(coveredResources)`](#fn-specresourcegroupswithcoveredresources)
    * [`fn withCoveredResourcesMixin(coveredResources)`](#fn-specresourcegroupswithcoveredresourcesmixin)
    * [`fn withFlavors(flavors)`](#fn-specresourcegroupswithflavors)
    * [`fn withFlavorsMixin(flavors)`](#fn-specresourcegroupswithflavorsmixin)
    * [`obj spec.resourceGroups.flavors`](#obj-specresourcegroupsflavors)
      * [`fn withName(name)`](#fn-specresourcegroupsflavorswithname)
      * [`fn withResources(resources)`](#fn-specresourcegroupsflavorswithresources)
      * [`fn withResourcesMixin(resources)`](#fn-specresourcegroupsflavorswithresourcesmixin)
      * [`obj spec.resourceGroups.flavors.resources`](#obj-specresourcegroupsflavorsresources)
        * [`fn withBorrowingLimit(borrowingLimit)`](#fn-specresourcegroupsflavorsresourceswithborrowinglimit)
        * [`fn withLendingLimit(lendingLimit)`](#fn-specresourcegroupsflavorsresourceswithlendinglimit)
        * [`fn withName(name)`](#fn-specresourcegroupsflavorsresourceswithname)
        * [`fn withNominalQuota(nominalQuota)`](#fn-specresourcegroupsflavorsresourceswithnominalquota)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of ClusterQueue

## obj metadata

"ObjectMeta is metadata that all persisted resources must have, which includes all objects users must create."

### fn metadata.withAnnotations

```ts
withAnnotations(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

### fn metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```

"Annotations is an unstructured key value map stored with a resource that may be set by external tools to store and retrieve arbitrary metadata. They are not queryable and should be preserved when modifying objects. More info: http://kubernetes.io/docs/user-guide/annotations"

**Note:** This function appends passed data to existing values

### fn metadata.withClusterName

```ts
withClusterName(clusterName)
```

"The name of the cluster which the object belongs to. This is used to distinguish resources with same name and namespace in different clusters. This field is not set anywhere right now and apiserver is going to ignore it if set in create or update request."

### fn metadata.withCreationTimestamp

```ts
withCreationTimestamp(creationTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withDeletionGracePeriodSeconds

```ts
withDeletionGracePeriodSeconds(deletionGracePeriodSeconds)
```

"Number of seconds allowed for this object to gracefully terminate before it will be removed from the system. Only set when deletionTimestamp is also set. May only be shortened. Read-only."

### fn metadata.withDeletionTimestamp

```ts
withDeletionTimestamp(deletionTimestamp)
```

"Time is a wrapper around time.Time which supports correct marshaling to YAML and JSON.  Wrappers are provided for many of the factory methods that the time package offers."

### fn metadata.withFinalizers

```ts
withFinalizers(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

### fn metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```

"Must be empty before the object is deleted from the registry. Each entry is an identifier for the responsible component that will remove the entry from the list. If the deletionTimestamp of the object is non-nil, entries in this list can only be removed. Finalizers may be processed and removed in any order.  Order is NOT enforced because it introduces significant risk of stuck finalizers. finalizers is a shared field, any actor with permission can reorder it. If the finalizer list is processed in order, then this can lead to a situation in which the component responsible for the first finalizer in the list is waiting for a signal (field value, external system, or other) produced by a component responsible for a finalizer later in the list, resulting in a deadlock. Without enforced ordering finalizers are free to order amongst themselves and are not vulnerable to ordering changes in the list."

**Note:** This function appends passed data to existing values

### fn metadata.withGenerateName

```ts
withGenerateName(generateName)
```

"GenerateName is an optional prefix, used by the server, to generate a unique name ONLY IF the Name field has not been provided. If this field is used, the name returned to the client will be different than the name passed. This value will also be combined with a unique suffix. The provided value has the same validation rules as the Name field, and may be truncated by the length of the suffix required to make the value unique on the server.\n\nIf this field is specified and the generated name exists, the server will NOT return a 409 - instead, it will either return 201 Created or 500 with Reason ServerTimeout indicating a unique name could not be found in the time allotted, and the client should retry (optionally after the time indicated in the Retry-After header).\n\nApplied only if Name is not specified. More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#idempotency"

### fn metadata.withGeneration

```ts
withGeneration(generation)
```

"A sequence number representing a specific generation of the desired state. Populated by the system. Read-only."

### fn metadata.withLabels

```ts
withLabels(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

### fn metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```

"Map of string keys and values that can be used to organize and categorize (scope and select) objects. May match selectors of replication controllers and services. More info: http://kubernetes.io/docs/user-guide/labels"

**Note:** This function appends passed data to existing values

### fn metadata.withName

```ts
withName(name)
```

"Name must be unique within a namespace. Is required when creating resources, although some resources may allow a client to request the generation of an appropriate name automatically. Name is primarily intended for creation idempotence and configuration definition. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/identifiers#names"

### fn metadata.withNamespace

```ts
withNamespace(namespace)
```

"Namespace defines the space within which each name must be unique. An empty namespace is equivalent to the \"default\" namespace, but \"default\" is the canonical representation. Not all objects are required to be scoped to a namespace - the value of this field for those objects will be empty.\n\nMust be a DNS_LABEL. Cannot be updated. More info: http://kubernetes.io/docs/user-guide/namespaces"

### fn metadata.withOwnerReferences

```ts
withOwnerReferences(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

### fn metadata.withOwnerReferencesMixin

```ts
withOwnerReferencesMixin(ownerReferences)
```

"List of objects depended by this object. If ALL objects in the list have been deleted, this object will be garbage collected. If this object is managed by a controller, then an entry in this list will point to this controller, with the controller field set to true. There cannot be more than one managing controller."

**Note:** This function appends passed data to existing values

### fn metadata.withResourceVersion

```ts
withResourceVersion(resourceVersion)
```

"An opaque value that represents the internal version of this object that can be used by clients to determine when objects have changed. May be used for optimistic concurrency, change detection, and the watch operation on a resource or set of resources. Clients must treat these values as opaque and passed unmodified back to the server. They may only be valid for a particular resource or set of resources.\n\nPopulated by the system. Read-only. Value must be treated as opaque by clients and . More info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#concurrency-control-and-consistency"

### fn metadata.withSelfLink

```ts
withSelfLink(selfLink)
```

"SelfLink is a URL representing this object. Populated by the system. Read-only.\n\nDEPRECATED Kubernetes will stop propagating this field in 1.20 release and the field is planned to be removed in 1.21 release."

### fn metadata.withUid

```ts
withUid(uid)
```

"UID is the unique in time and space value for this object. It is typically generated by the server on successful creation of a resource and is not allowed to change on PUT operations.\n\nPopulated by the system. Read-only. More info: http://kubernetes.io/docs/user-guide/identifiers#uids"

## obj spec

"spec is the specification of the ClusterQueue."

### fn spec.withAdmissionChecks

```ts
withAdmissionChecks(admissionChecks)
```

"admissionChecks lists the AdmissionChecks required by this ClusterQueue.\nCannot be used along with AdmissionCheckStrategy."

### fn spec.withAdmissionChecksMixin

```ts
withAdmissionChecksMixin(admissionChecks)
```

"admissionChecks lists the AdmissionChecks required by this ClusterQueue.\nCannot be used along with AdmissionCheckStrategy."

**Note:** This function appends passed data to existing values

### fn spec.withCohort

```ts
withCohort(cohort)
```

"cohort that this ClusterQueue belongs to. CQs that belong to the\nsame cohort can borrow unused resources from each other.\n\nA CQ can be a member of a single borrowing cohort. A workload submitted\nto a queue referencing this CQ can borrow quota from any CQ in the cohort.\nOnly quota for the [resource, flavor] pairs listed in the CQ can be\nborrowed.\nIf empty, this ClusterQueue cannot borrow from any other ClusterQueue and\nvice versa.\n\nA cohort is a name that links CQs together, but it doesn't reference any\nobject."

### fn spec.withQueueingStrategy

```ts
withQueueingStrategy(queueingStrategy)
```

"queueingStrategy indicates the queueing strategy of the workloads\nacross the queues in this ClusterQueue.\nCurrent Supported Strategies:\n\n- StrictFIFO: workloads are ordered strictly by creation time.\nOlder workloads that can't be admitted will block admitting newer\nworkloads even if they fit available quota.\n- BestEffortFIFO: workloads are ordered by creation time,\nhowever older workloads that can't be admitted will not block\nadmitting newer workloads that fit existing quota."

### fn spec.withResourceGroups

```ts
withResourceGroups(resourceGroups)
```

"resourceGroups describes groups of resources.\nEach resource group defines the list of resources and a list of flavors\nthat provide quotas for these resources.\nEach resource and each flavor can only form part of one resource group.\nresourceGroups can be up to 16, with a max of 256 total flavors across all groups."

### fn spec.withResourceGroupsMixin

```ts
withResourceGroupsMixin(resourceGroups)
```

"resourceGroups describes groups of resources.\nEach resource group defines the list of resources and a list of flavors\nthat provide quotas for these resources.\nEach resource and each flavor can only form part of one resource group.\nresourceGroups can be up to 16, with a max of 256 total flavors across all groups."

**Note:** This function appends passed data to existing values

### fn spec.withStopPolicy

```ts
withStopPolicy(stopPolicy)
```

"stopPolicy - if set to a value different from None, the ClusterQueue is considered Inactive, no new reservation being\nmade.\n\nDepending on its value, its associated workloads will:\n\n- None - Workloads are admitted\n- HoldAndDrain - Admitted workloads are evicted and Reserving workloads will cancel the reservation.\n- Hold - Admitted workloads will run to completion and Reserving workloads will cancel the reservation."

## obj spec.admissionChecksStrategy

"admissionChecksStrategy defines a list of strategies to determine which ResourceFlavors require AdmissionChecks.\nThis property cannot be used in conjunction with the 'admissionChecks' property."

### fn spec.admissionChecksStrategy.withAdmissionChecks

```ts
withAdmissionChecks(admissionChecks)
```

"admissionChecks is a list of strategies for AdmissionChecks"

### fn spec.admissionChecksStrategy.withAdmissionChecksMixin

```ts
withAdmissionChecksMixin(admissionChecks)
```

"admissionChecks is a list of strategies for AdmissionChecks"

**Note:** This function appends passed data to existing values

## obj spec.admissionChecksStrategy.admissionChecks

"admissionChecks is a list of strategies for AdmissionChecks"

### fn spec.admissionChecksStrategy.admissionChecks.withName

```ts
withName(name)
```

"name is an AdmissionCheck's name."

### fn spec.admissionChecksStrategy.admissionChecks.withOnFlavors

```ts
withOnFlavors(onFlavors)
```

"onFlavors is a list of ResourceFlavors' names that this AdmissionCheck should run for.\nIf empty, the AdmissionCheck will run for all workloads submitted to the ClusterQueue."

### fn spec.admissionChecksStrategy.admissionChecks.withOnFlavorsMixin

```ts
withOnFlavorsMixin(onFlavors)
```

"onFlavors is a list of ResourceFlavors' names that this AdmissionCheck should run for.\nIf empty, the AdmissionCheck will run for all workloads submitted to the ClusterQueue."

**Note:** This function appends passed data to existing values

## obj spec.admissionScope

"admissionScope indicates whether ClusterQueue uses the Admission Fair Sharing"

### fn spec.admissionScope.withAdmissionMode

```ts
withAdmissionMode(admissionMode)
```

"admissionMode indicates which mode for AdmissionFairSharing should be used\nin the AdmissionScope. Possible values are:\n- UsageBasedAdmissionFairSharing\n- NoAdmissionFairSharing"

## obj spec.fairSharing

"fairSharing defines the properties of the ClusterQueue when\nparticipating in FairSharing.  The values are only relevant\nif FairSharing is enabled in the Kueue configuration."

### fn spec.fairSharing.withWeight

```ts
withWeight(weight)
```

"weight gives a comparative advantage to this ClusterQueue\nor Cohort when competing for unused resources in the\nCohort.  The share is based on the dominant resource usage\nabove nominal quotas for each resource, divided by the\nweight.  Admission prioritizes scheduling workloads from\nClusterQueues and Cohorts with the lowest share and\npreempting workloads from the ClusterQueues and Cohorts\nwith the highest share.  A zero weight implies infinite\nshare value, meaning that this Node will always be at\ndisadvantage against other ClusterQueues and Cohorts.\nWhen not 0, Weight must be greater than 10^-9."

## obj spec.flavorFungibility

"flavorFungibility defines whether a workload should try the next flavor\nbefore borrowing or preempting in the flavor being evaluated."

### fn spec.flavorFungibility.withWhenCanBorrow

```ts
withWhenCanBorrow(whenCanBorrow)
```

"whenCanBorrow determines whether a workload should try the next flavor\nbefore borrowing in current flavor. The possible values are:\n\n- `Borrow` (default): allocate in current flavor if borrowing\n  is possible.\n- `TryNextFlavor`: try next flavor even if the current\n  flavor has enough resources to borrow."

### fn spec.flavorFungibility.withWhenCanPreempt

```ts
withWhenCanPreempt(whenCanPreempt)
```

"whenCanPreempt determines whether a workload should try the next flavor\nbefore borrowing in current flavor. The possible values are:\n\n- `Preempt`: allocate in current flavor if it's possible to preempt some workloads.\n- `TryNextFlavor` (default): try next flavor even if there are enough\n  candidates for preemption in the current flavor."

## obj spec.namespaceSelector

"namespaceSelector defines which namespaces are allowed to submit workloads to\nthis clusterQueue. Beyond this basic support for policy, a policy agent like\nGatekeeper should be used to enforce more advanced policies.\nDefaults to null which is a nothing selector (no namespaces eligible).\nIf set to an empty selector `{}`, then all namespaces are eligible."

### fn spec.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.preemption

"preemption defines the preemption policies."

### fn spec.preemption.withReclaimWithinCohort

```ts
withReclaimWithinCohort(reclaimWithinCohort)
```

"reclaimWithinCohort determines whether a pending Workload can preempt\nWorkloads from other ClusterQueues in the cohort that are using more than\ntheir nominal quota. The possible values are:\n\n- `Never` (default): do not preempt Workloads in the cohort.\n- `LowerPriority`: **Classic Preemption** if the pending Workload\n  fits within the nominal quota of its ClusterQueue, only preempt\n  Workloads in the cohort that have lower priority than the pending\n  Workload. **Fair Sharing** only preempt Workloads in the cohort that\n  have lower priority than the pending Workload and that satisfy the\n  Fair Sharing preemptionStategies.\n- `Any`: **Classic Preemption** if the pending Workload fits within\n   the nominal quota of its ClusterQueue, preempt any Workload in the\n   cohort, irrespective of priority. **Fair Sharing** preempt Workloads\n   in the cohort that satisfy the Fair Sharing preemptionStrategies."

### fn spec.preemption.withWithinClusterQueue

```ts
withWithinClusterQueue(withinClusterQueue)
```

"withinClusterQueue determines whether a pending Workload that doesn't fit\nwithin the nominal quota for its ClusterQueue, can preempt active Workloads in\nthe ClusterQueue. The possible values are:\n\n- `Never` (default): do not preempt Workloads in the ClusterQueue.\n- `LowerPriority`: only preempt Workloads in the ClusterQueue that have\n  lower priority than the pending Workload.\n- `LowerOrNewerEqualPriority`: only preempt Workloads in the ClusterQueue that\n  either have a lower priority than the pending workload or equal priority\n  and are newer than the pending workload."

## obj spec.preemption.borrowWithinCohort

"borrowWithinCohort determines whether a pending Workload can preempt\nWorkloads from other ClusterQueues in the cohort if the workload requires borrowing.\nMay only be configured with Classical Preemption, and __not__ with Fair Sharing."

### fn spec.preemption.borrowWithinCohort.withMaxPriorityThreshold

```ts
withMaxPriorityThreshold(maxPriorityThreshold)
```

"maxPriorityThreshold allows to restrict the set of workloads which\nmight be preempted by a borrowing workload, to only workloads with\npriority less than or equal to the specified threshold priority.\nWhen the threshold is not specified, then any workload satisfying the\npolicy can be preempted by the borrowing workload."

### fn spec.preemption.borrowWithinCohort.withPolicy

```ts
withPolicy(policy)
```

"policy determines the policy for preemption to reclaim quota within cohort while borrowing.\nPossible values are:\n- `Never` (default): do not allow for preemption, in other\n   ClusterQueues within the cohort, for a borrowing workload.\n- `LowerPriority`: allow preemption, in other ClusterQueues\n   within the cohort, for a borrowing workload, but only if\n   the preempted workloads are of lower priority."

## obj spec.resourceGroups

"resourceGroups describes groups of resources.\nEach resource group defines the list of resources and a list of flavors\nthat provide quotas for these resources.\nEach resource and each flavor can only form part of one resource group.\nresourceGroups can be up to 16, with a max of 256 total flavors across all groups."

### fn spec.resourceGroups.withCoveredResources

```ts
withCoveredResources(coveredResources)
```

"coveredResources is the list of resources covered by the flavors in this\ngroup.\nExamples: cpu, memory, vendor.com/gpu.\nThe list cannot be empty and it can contain up to 64 resources. With a total\nof up to 256 covered resources across all resource groups in the ClusterQueue."

### fn spec.resourceGroups.withCoveredResourcesMixin

```ts
withCoveredResourcesMixin(coveredResources)
```

"coveredResources is the list of resources covered by the flavors in this\ngroup.\nExamples: cpu, memory, vendor.com/gpu.\nThe list cannot be empty and it can contain up to 64 resources. With a total\nof up to 256 covered resources across all resource groups in the ClusterQueue."

**Note:** This function appends passed data to existing values

### fn spec.resourceGroups.withFlavors

```ts
withFlavors(flavors)
```

"flavors is the list of flavors that provide the resources of this group.\nTypically, different flavors represent different hardware models\n(e.g., gpu models, cpu architectures) or pricing models (on-demand vs spot\ncpus).\nEach flavor MUST list all the resources listed for this group in the same\norder as the .resources field.\nThe list cannot be empty and it can contain up to 64 flavors, with a max of\n256 total flavors across all resource groups in the ClusterQueue."

### fn spec.resourceGroups.withFlavorsMixin

```ts
withFlavorsMixin(flavors)
```

"flavors is the list of flavors that provide the resources of this group.\nTypically, different flavors represent different hardware models\n(e.g., gpu models, cpu architectures) or pricing models (on-demand vs spot\ncpus).\nEach flavor MUST list all the resources listed for this group in the same\norder as the .resources field.\nThe list cannot be empty and it can contain up to 64 flavors, with a max of\n256 total flavors across all resource groups in the ClusterQueue."

**Note:** This function appends passed data to existing values

## obj spec.resourceGroups.flavors

"flavors is the list of flavors that provide the resources of this group.\nTypically, different flavors represent different hardware models\n(e.g., gpu models, cpu architectures) or pricing models (on-demand vs spot\ncpus).\nEach flavor MUST list all the resources listed for this group in the same\norder as the .resources field.\nThe list cannot be empty and it can contain up to 64 flavors, with a max of\n256 total flavors across all resource groups in the ClusterQueue."

### fn spec.resourceGroups.flavors.withName

```ts
withName(name)
```

"name of this flavor. The name should match the .metadata.name of a\nResourceFlavor. If a matching ResourceFlavor does not exist, the\nClusterQueue will have an Active condition set to False."

### fn spec.resourceGroups.flavors.withResources

```ts
withResources(resources)
```

"resources is the list of quotas for this flavor per resource.\nThere could be up to 64 resources."

### fn spec.resourceGroups.flavors.withResourcesMixin

```ts
withResourcesMixin(resources)
```

"resources is the list of quotas for this flavor per resource.\nThere could be up to 64 resources."

**Note:** This function appends passed data to existing values

## obj spec.resourceGroups.flavors.resources

"resources is the list of quotas for this flavor per resource.\nThere could be up to 64 resources."

### fn spec.resourceGroups.flavors.resources.withBorrowingLimit

```ts
withBorrowingLimit(borrowingLimit)
```

"borrowingLimit is the maximum amount of quota for the [flavor, resource]\ncombination that this ClusterQueue is allowed to borrow from the unused\nquota of other ClusterQueues in the same cohort.\nIn total, at a given time, Workloads in a ClusterQueue can consume a\nquantity of quota equal to nominalQuota+borrowingLimit, assuming the other\nClusterQueues in the cohort have enough unused quota.\nIf null, it means that there is no borrowing limit.\nIf not null, it must be non-negative.\nborrowingLimit must be null if spec.cohort is empty."

### fn spec.resourceGroups.flavors.resources.withLendingLimit

```ts
withLendingLimit(lendingLimit)
```

"lendingLimit is the maximum amount of unused quota for the [flavor, resource]\ncombination that this ClusterQueue can lend to other ClusterQueues in the same cohort.\nIn total, at a given time, ClusterQueue reserves for its exclusive use\na quantity of quota equals to nominalQuota - lendingLimit.\nIf null, it means that there is no lending limit, meaning that\nall the nominalQuota can be borrowed by other clusterQueues in the cohort.\nIf not null, it must be non-negative.\nlendingLimit must be null if spec.cohort is empty.\nThis field is in beta stage and is enabled by default."

### fn spec.resourceGroups.flavors.resources.withName

```ts
withName(name)
```

"name of this resource."

### fn spec.resourceGroups.flavors.resources.withNominalQuota

```ts
withNominalQuota(nominalQuota)
```

"nominalQuota is the quantity of this resource that is available for\nWorkloads admitted by this ClusterQueue at a point in time.\nThe nominalQuota must be non-negative.\nnominalQuota should represent the resources in the cluster available for\nrunning jobs (after discounting resources consumed by system components\nand pods not managed by kueue). In an autoscaled cluster, nominalQuota\nshould account for resources that can be provided by a component such as\nKubernetes cluster-autoscaler.\n\nIf the ClusterQueue belongs to a cohort, the sum of the quotas for each\n(flavor, resource) combination defines the maximum quantity that can be\nallocated by a ClusterQueue in the cohort."