---
permalink: /0.14.3/kueue/v1beta1/cohort/
---

# kueue.v1beta1.cohort

"Cohort defines the Cohorts API.\n\nHierarchical Cohorts (any Cohort which has a parent) are compatible\nwith Fair Sharing as of v0.11. Using these features together in\nV0.9 and V0.10 is unsupported, and results in undefined behavior."

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
  * [`fn withParentName(parentName)`](#fn-specwithparentname)
  * [`fn withResourceGroups(resourceGroups)`](#fn-specwithresourcegroups)
  * [`fn withResourceGroupsMixin(resourceGroups)`](#fn-specwithresourcegroupsmixin)
  * [`obj spec.fairSharing`](#obj-specfairsharing)
    * [`fn withWeight(weight)`](#fn-specfairsharingwithweight)
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

new returns an instance of Cohort

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

"spec is the specification of the Cohort."

### fn spec.withParentName

```ts
withParentName(parentName)
```

"parentName references the name of the Cohort's parent, if\nany. It satisfies one of three cases:\n1) Unset. This Cohort is the root of its Cohort tree.\n2) References a non-existent Cohort. We use default Cohort (no borrowing/lending limits).\n3) References an existent Cohort.\n\nIf a cycle is created, we disable all members of the\nCohort, including ClusterQueues, until the cycle is\nremoved.  We prevent further admission while the cycle\nexists."

### fn spec.withResourceGroups

```ts
withResourceGroups(resourceGroups)
```

"resourceGroups describes groupings of Resources and\nFlavors.  Each ResourceGroup defines a list of Resources\nand a list of Flavors which provide quotas for these\nResources. Each Resource and each Flavor may only form part\nof one ResourceGroup.  There may be up to 16 ResourceGroups\nwithin a Cohort.\n\nPlease note that nominalQuota defined at the Cohort level\nrepresents additional resources on top of those defined by\nClusterQueues within the Cohort. The Cohort's nominalQuota\nmay be thought of as a shared pool for the ClusterQueues\nwithin it. Additionally, this quota may also be lent out to\nparent Cohort(s), subject to LendingLimit.\n\nBorrowingLimit limits how much members of this Cohort\nsubtree can borrow from the parent subtree.\n\nLendingLimit limits how much members of this Cohort subtree\ncan lend to the parent subtree.\n\nBorrowing and Lending limits must only be set when the\nCohort has a parent.  Otherwise, the Cohort create/update\nwill be rejected by the webhook."

### fn spec.withResourceGroupsMixin

```ts
withResourceGroupsMixin(resourceGroups)
```

"resourceGroups describes groupings of Resources and\nFlavors.  Each ResourceGroup defines a list of Resources\nand a list of Flavors which provide quotas for these\nResources. Each Resource and each Flavor may only form part\nof one ResourceGroup.  There may be up to 16 ResourceGroups\nwithin a Cohort.\n\nPlease note that nominalQuota defined at the Cohort level\nrepresents additional resources on top of those defined by\nClusterQueues within the Cohort. The Cohort's nominalQuota\nmay be thought of as a shared pool for the ClusterQueues\nwithin it. Additionally, this quota may also be lent out to\nparent Cohort(s), subject to LendingLimit.\n\nBorrowingLimit limits how much members of this Cohort\nsubtree can borrow from the parent subtree.\n\nLendingLimit limits how much members of this Cohort subtree\ncan lend to the parent subtree.\n\nBorrowing and Lending limits must only be set when the\nCohort has a parent.  Otherwise, the Cohort create/update\nwill be rejected by the webhook."

**Note:** This function appends passed data to existing values

## obj spec.fairSharing

"fairSharing defines the properties of the Cohort when\nparticipating in FairSharing. The values are only relevant\nif FairSharing is enabled in the Kueue configuration."

### fn spec.fairSharing.withWeight

```ts
withWeight(weight)
```

"weight gives a comparative advantage to this ClusterQueue\nor Cohort when competing for unused resources in the\nCohort.  The share is based on the dominant resource usage\nabove nominal quotas for each resource, divided by the\nweight.  Admission prioritizes scheduling workloads from\nClusterQueues and Cohorts with the lowest share and\npreempting workloads from the ClusterQueues and Cohorts\nwith the highest share.  A zero weight implies infinite\nshare value, meaning that this Node will always be at\ndisadvantage against other ClusterQueues and Cohorts.\nWhen not 0, Weight must be greater than 10^-9."

## obj spec.resourceGroups

"resourceGroups describes groupings of Resources and\nFlavors.  Each ResourceGroup defines a list of Resources\nand a list of Flavors which provide quotas for these\nResources. Each Resource and each Flavor may only form part\nof one ResourceGroup.  There may be up to 16 ResourceGroups\nwithin a Cohort.\n\nPlease note that nominalQuota defined at the Cohort level\nrepresents additional resources on top of those defined by\nClusterQueues within the Cohort. The Cohort's nominalQuota\nmay be thought of as a shared pool for the ClusterQueues\nwithin it. Additionally, this quota may also be lent out to\nparent Cohort(s), subject to LendingLimit.\n\nBorrowingLimit limits how much members of this Cohort\nsubtree can borrow from the parent subtree.\n\nLendingLimit limits how much members of this Cohort subtree\ncan lend to the parent subtree.\n\nBorrowing and Lending limits must only be set when the\nCohort has a parent.  Otherwise, the Cohort create/update\nwill be rejected by the webhook."

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