---
permalink: /0.15.3/kueue/v1beta2/provisioningRequestConfig/
---

# kueue.v1beta2.provisioningRequestConfig

"ProvisioningRequestConfig is the Schema for the provisioningrequestconfig API"

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
  * [`fn withManagedResources(managedResources)`](#fn-specwithmanagedresources)
  * [`fn withManagedResourcesMixin(managedResources)`](#fn-specwithmanagedresourcesmixin)
  * [`fn withParameters(parameters)`](#fn-specwithparameters)
  * [`fn withParametersMixin(parameters)`](#fn-specwithparametersmixin)
  * [`fn withPodSetMergePolicy(podSetMergePolicy)`](#fn-specwithpodsetmergepolicy)
  * [`fn withProvisioningClassName(provisioningClassName)`](#fn-specwithprovisioningclassname)
  * [`obj spec.podSetUpdates`](#obj-specpodsetupdates)
    * [`fn withNodeSelector(nodeSelector)`](#fn-specpodsetupdateswithnodeselector)
    * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specpodsetupdateswithnodeselectormixin)
    * [`obj spec.podSetUpdates.nodeSelector`](#obj-specpodsetupdatesnodeselector)
      * [`fn withKey(key)`](#fn-specpodsetupdatesnodeselectorwithkey)
      * [`fn withValueFromProvisioningClassDetail(valueFromProvisioningClassDetail)`](#fn-specpodsetupdatesnodeselectorwithvaluefromprovisioningclassdetail)
  * [`obj spec.retryStrategy`](#obj-specretrystrategy)
    * [`fn withBackoffBaseSeconds(backoffBaseSeconds)`](#fn-specretrystrategywithbackoffbaseseconds)
    * [`fn withBackoffLimitCount(backoffLimitCount)`](#fn-specretrystrategywithbackofflimitcount)
    * [`fn withBackoffMaxSeconds(backoffMaxSeconds)`](#fn-specretrystrategywithbackoffmaxseconds)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of ProvisioningRequestConfig

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

"spec is the specification of the ProvisioningRequestConfig."

### fn spec.withManagedResources

```ts
withManagedResources(managedResources)
```

"managedResources contains the list of resources managed by the autoscaling.\n\nIf empty, all resources are considered managed.\n\nIf not empty, the ProvisioningRequest will contain only the podsets that are\nrequesting at least one of them.\n\nIf none of the workloads podsets is requesting at least a managed resource,\nthe workload is considered ready."

### fn spec.withManagedResourcesMixin

```ts
withManagedResourcesMixin(managedResources)
```

"managedResources contains the list of resources managed by the autoscaling.\n\nIf empty, all resources are considered managed.\n\nIf not empty, the ProvisioningRequest will contain only the podsets that are\nrequesting at least one of them.\n\nIf none of the workloads podsets is requesting at least a managed resource,\nthe workload is considered ready."

**Note:** This function appends passed data to existing values

### fn spec.withParameters

```ts
withParameters(parameters)
```

"parameters contains all other parameters classes may require."

### fn spec.withParametersMixin

```ts
withParametersMixin(parameters)
```

"parameters contains all other parameters classes may require."

**Note:** This function appends passed data to existing values

### fn spec.withPodSetMergePolicy

```ts
withPodSetMergePolicy(podSetMergePolicy)
```

"podSetMergePolicy specifies the policy for merging PodSets before being passed\nto the cluster autoscaler."

### fn spec.withProvisioningClassName

```ts
withProvisioningClassName(provisioningClassName)
```

"provisioningClassName describes the different modes of provisioning the resources.\nCheck autoscaling.x-k8s.io ProvisioningRequestSpec.ProvisioningClassName for details."

## obj spec.podSetUpdates

"podSetUpdates specifies the update of the workload's PodSetUpdates which\nare used to target the provisioned nodes."

### fn spec.podSetUpdates.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```

"nodeSelector specifies the list of updates for the NodeSelector."

### fn spec.podSetUpdates.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```

"nodeSelector specifies the list of updates for the NodeSelector."

**Note:** This function appends passed data to existing values

## obj spec.podSetUpdates.nodeSelector

"nodeSelector specifies the list of updates for the NodeSelector."

### fn spec.podSetUpdates.nodeSelector.withKey

```ts
withKey(key)
```

"key specifies the key for the NodeSelector."

### fn spec.podSetUpdates.nodeSelector.withValueFromProvisioningClassDetail

```ts
withValueFromProvisioningClassDetail(valueFromProvisioningClassDetail)
```

"valueFromProvisioningClassDetail specifies the key of the\nProvisioningRequest.status.provisioningClassDetails from which the value\nis used for the update."

## obj spec.retryStrategy

"retryStrategy defines strategy for retrying ProvisioningRequest.\nIf null, then the default configuration is applied with the following parameter values:\nbackoffLimitCount:  3\nbackoffBaseSeconds: 60 - 1 min\nbackoffMaxSeconds:  1800 - 30 mins\n\nTo switch off retry mechanism\nset retryStrategy.backoffLimitCount to 0."

### fn spec.retryStrategy.withBackoffBaseSeconds

```ts
withBackoffBaseSeconds(backoffBaseSeconds)
```

"backoffBaseSeconds defines the base for the exponential backoff for\nre-queuing an evicted workload.\n\nDefaults to 60."

### fn spec.retryStrategy.withBackoffLimitCount

```ts
withBackoffLimitCount(backoffLimitCount)
```

"backoffLimitCount defines the maximum number of re-queuing retries.\nOnce the number is reached, the workload is deactivated (`.spec.activate`=`false`).\n\nEvery backoff duration is about \"b*2^(n-1)+Rand\" where:\n- \"b\" represents the base set by \"BackoffBaseSeconds\" parameter,\n- \"n\" represents the \"workloadStatus.requeueState.count\",\n- \"Rand\" represents the random jitter.\nDuring this time, the workload is taken as an inadmissible and\nother workloads will have a chance to be admitted.\nBy default, the consecutive requeue delays are around: (60s, 120s, 240s, ...).\n\nDefaults to 3."

### fn spec.retryStrategy.withBackoffMaxSeconds

```ts
withBackoffMaxSeconds(backoffMaxSeconds)
```

"backoffMaxSeconds defines the maximum backoff time to re-queue an evicted workload.\n\nDefaults to 1800."