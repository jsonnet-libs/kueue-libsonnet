---
permalink: /0.15.3/kueue/v1beta2/resourceFlavor/
---

# kueue.v1beta2.resourceFlavor

"ResourceFlavor is the Schema for the resourceflavors API."

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
  * [`fn withNodeLabels(nodeLabels)`](#fn-specwithnodelabels)
  * [`fn withNodeLabelsMixin(nodeLabels)`](#fn-specwithnodelabelsmixin)
  * [`fn withNodeTaints(nodeTaints)`](#fn-specwithnodetaints)
  * [`fn withNodeTaintsMixin(nodeTaints)`](#fn-specwithnodetaintsmixin)
  * [`fn withTolerations(tolerations)`](#fn-specwithtolerations)
  * [`fn withTolerationsMixin(tolerations)`](#fn-specwithtolerationsmixin)
  * [`fn withTopologyName(topologyName)`](#fn-specwithtopologyname)
  * [`obj spec.nodeTaints`](#obj-specnodetaints)
    * [`fn withEffect(effect)`](#fn-specnodetaintswitheffect)
    * [`fn withKey(key)`](#fn-specnodetaintswithkey)
    * [`fn withTimeAdded(timeAdded)`](#fn-specnodetaintswithtimeadded)
    * [`fn withValue(value)`](#fn-specnodetaintswithvalue)
  * [`obj spec.tolerations`](#obj-spectolerations)
    * [`fn withEffect(effect)`](#fn-spectolerationswitheffect)
    * [`fn withKey(key)`](#fn-spectolerationswithkey)
    * [`fn withOperator(operator)`](#fn-spectolerationswithoperator)
    * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-spectolerationswithtolerationseconds)
    * [`fn withValue(value)`](#fn-spectolerationswithvalue)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of ResourceFlavor

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

"spec is the specification of the ResourceFlavor."

### fn spec.withNodeLabels

```ts
withNodeLabels(nodeLabels)
```

"nodeLabels are labels that associate the ResourceFlavor with Nodes that\nhave the same labels.\nWhen a Workload is admitted, its podsets can only get assigned\nResourceFlavors whose nodeLabels match the nodeSelector and nodeAffinity\nfields.\nOnce a ResourceFlavor is assigned to a podSet, the ResourceFlavor's\nnodeLabels should be injected into the pods of the Workload by the\ncontroller that integrates with the Workload object.\n\nnodeLabels can be up to 8 elements."

### fn spec.withNodeLabelsMixin

```ts
withNodeLabelsMixin(nodeLabels)
```

"nodeLabels are labels that associate the ResourceFlavor with Nodes that\nhave the same labels.\nWhen a Workload is admitted, its podsets can only get assigned\nResourceFlavors whose nodeLabels match the nodeSelector and nodeAffinity\nfields.\nOnce a ResourceFlavor is assigned to a podSet, the ResourceFlavor's\nnodeLabels should be injected into the pods of the Workload by the\ncontroller that integrates with the Workload object.\n\nnodeLabels can be up to 8 elements."

**Note:** This function appends passed data to existing values

### fn spec.withNodeTaints

```ts
withNodeTaints(nodeTaints)
```

"nodeTaints are taints that the nodes associated with this ResourceFlavor\nhave.\nWorkloads' podsets must have tolerations for these nodeTaints in order to\nget assigned this ResourceFlavor during admission.\nWhen this ResourceFlavor has also set the matching tolerations (in .spec.tolerations),\nthen the nodeTaints are not considered during admission.\nOnly the 'NoSchedule' and 'NoExecute' taint effects are evaluated,\nwhile 'PreferNoSchedule' is ignored.\n\nAn example of a nodeTaint is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\nnodeTaints can be up to 8 elements."

### fn spec.withNodeTaintsMixin

```ts
withNodeTaintsMixin(nodeTaints)
```

"nodeTaints are taints that the nodes associated with this ResourceFlavor\nhave.\nWorkloads' podsets must have tolerations for these nodeTaints in order to\nget assigned this ResourceFlavor during admission.\nWhen this ResourceFlavor has also set the matching tolerations (in .spec.tolerations),\nthen the nodeTaints are not considered during admission.\nOnly the 'NoSchedule' and 'NoExecute' taint effects are evaluated,\nwhile 'PreferNoSchedule' is ignored.\n\nAn example of a nodeTaint is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\nnodeTaints can be up to 8 elements."

**Note:** This function appends passed data to existing values

### fn spec.withTolerations

```ts
withTolerations(tolerations)
```

"tolerations are extra tolerations that will be added to the pods admitted in\nthe quota associated with this resource flavor.\n\nAn example of a toleration is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\ntolerations can be up to 8 elements."

### fn spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```

"tolerations are extra tolerations that will be added to the pods admitted in\nthe quota associated with this resource flavor.\n\nAn example of a toleration is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\ntolerations can be up to 8 elements."

**Note:** This function appends passed data to existing values

### fn spec.withTopologyName

```ts
withTopologyName(topologyName)
```

"topologyName indicates topology for the TAS ResourceFlavor.\nWhen specified, it enables scraping of the topology information from the\nnodes matching to the Resource Flavor node labels."

## obj spec.nodeTaints

"nodeTaints are taints that the nodes associated with this ResourceFlavor\nhave.\nWorkloads' podsets must have tolerations for these nodeTaints in order to\nget assigned this ResourceFlavor during admission.\nWhen this ResourceFlavor has also set the matching tolerations (in .spec.tolerations),\nthen the nodeTaints are not considered during admission.\nOnly the 'NoSchedule' and 'NoExecute' taint effects are evaluated,\nwhile 'PreferNoSchedule' is ignored.\n\nAn example of a nodeTaint is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\nnodeTaints can be up to 8 elements."

### fn spec.nodeTaints.withEffect

```ts
withEffect(effect)
```

"Required. The effect of the taint on pods\nthat do not tolerate the taint.\nValid effects are NoSchedule, PreferNoSchedule and NoExecute."

### fn spec.nodeTaints.withKey

```ts
withKey(key)
```

"Required. The taint key to be applied to a node."

### fn spec.nodeTaints.withTimeAdded

```ts
withTimeAdded(timeAdded)
```

"TimeAdded represents the time at which the taint was added."

### fn spec.nodeTaints.withValue

```ts
withValue(value)
```

"The taint value corresponding to the taint key."

## obj spec.tolerations

"tolerations are extra tolerations that will be added to the pods admitted in\nthe quota associated with this resource flavor.\n\nAn example of a toleration is\ncloud.provider.com/preemptible=\"true\":NoSchedule\n\ntolerations can be up to 8 elements."

### fn spec.tolerations.withEffect

```ts
withEffect(effect)
```

"Effect indicates the taint effect to match. Empty means match all taint effects.\nWhen specified, allowed values are NoSchedule, PreferNoSchedule and NoExecute."

### fn spec.tolerations.withKey

```ts
withKey(key)
```

"Key is the taint key that the toleration applies to. Empty means match all taint keys.\nIf the key is empty, operator must be Exists; this combination means to match all values and all keys."

### fn spec.tolerations.withOperator

```ts
withOperator(operator)
```

"Operator represents a key's relationship to the value.\nValid operators are Exists and Equal. Defaults to Equal.\nExists is equivalent to wildcard for value, so that a pod can\ntolerate all taints of a particular category."

### fn spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```

"TolerationSeconds represents the period of time the toleration (which must be\nof effect NoExecute, otherwise this field is ignored) tolerates the taint. By default,\nit is not set, which means tolerate the taint forever (do not evict). Zero and\nnegative values will be treated as 0 (evict immediately) by the system."

### fn spec.tolerations.withValue

```ts
withValue(value)
```

"Value is the taint value the toleration matches to.\nIf the operator is Exists, the value should be empty, otherwise just a regular string."