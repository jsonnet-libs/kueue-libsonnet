---
permalink: /0.15.3/kueue/v1beta2/workload/
---

# kueue.v1beta2.workload

"Workload is the Schema for the workloads API"

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
  * [`fn withActive(active)`](#fn-specwithactive)
  * [`fn withMaximumExecutionTimeSeconds(maximumExecutionTimeSeconds)`](#fn-specwithmaximumexecutiontimeseconds)
  * [`fn withPodSets(podSets)`](#fn-specwithpodsets)
  * [`fn withPodSetsMixin(podSets)`](#fn-specwithpodsetsmixin)
  * [`fn withPriority(priority)`](#fn-specwithpriority)
  * [`fn withQueueName(queueName)`](#fn-specwithqueuename)
  * [`obj spec.podSets`](#obj-specpodsets)
    * [`fn withCount(count)`](#fn-specpodsetswithcount)
    * [`fn withMinCount(minCount)`](#fn-specpodsetswithmincount)
    * [`fn withName(name)`](#fn-specpodsetswithname)
    * [`obj spec.podSets.template`](#obj-specpodsetstemplate)
      * [`obj spec.podSets.template.metadata`](#obj-specpodsetstemplatemetadata)
        * [`fn withAnnotations(annotations)`](#fn-specpodsetstemplatemetadatawithannotations)
        * [`fn withAnnotationsMixin(annotations)`](#fn-specpodsetstemplatemetadatawithannotationsmixin)
        * [`fn withFinalizers(finalizers)`](#fn-specpodsetstemplatemetadatawithfinalizers)
        * [`fn withFinalizersMixin(finalizers)`](#fn-specpodsetstemplatemetadatawithfinalizersmixin)
        * [`fn withLabels(labels)`](#fn-specpodsetstemplatemetadatawithlabels)
        * [`fn withLabelsMixin(labels)`](#fn-specpodsetstemplatemetadatawithlabelsmixin)
        * [`fn withName(name)`](#fn-specpodsetstemplatemetadatawithname)
        * [`fn withNamespace(namespace)`](#fn-specpodsetstemplatemetadatawithnamespace)
      * [`obj spec.podSets.template.spec`](#obj-specpodsetstemplatespec)
        * [`fn withActiveDeadlineSeconds(activeDeadlineSeconds)`](#fn-specpodsetstemplatespecwithactivedeadlineseconds)
        * [`fn withAutomountServiceAccountToken(automountServiceAccountToken)`](#fn-specpodsetstemplatespecwithautomountserviceaccounttoken)
        * [`fn withContainers(containers)`](#fn-specpodsetstemplatespecwithcontainers)
        * [`fn withContainersMixin(containers)`](#fn-specpodsetstemplatespecwithcontainersmixin)
        * [`fn withDnsPolicy(dnsPolicy)`](#fn-specpodsetstemplatespecwithdnspolicy)
        * [`fn withEnableServiceLinks(enableServiceLinks)`](#fn-specpodsetstemplatespecwithenableservicelinks)
        * [`fn withEphemeralContainers(ephemeralContainers)`](#fn-specpodsetstemplatespecwithephemeralcontainers)
        * [`fn withEphemeralContainersMixin(ephemeralContainers)`](#fn-specpodsetstemplatespecwithephemeralcontainersmixin)
        * [`fn withHostAliases(hostAliases)`](#fn-specpodsetstemplatespecwithhostaliases)
        * [`fn withHostAliasesMixin(hostAliases)`](#fn-specpodsetstemplatespecwithhostaliasesmixin)
        * [`fn withHostIPC(hostIPC)`](#fn-specpodsetstemplatespecwithhostipc)
        * [`fn withHostNetwork(hostNetwork)`](#fn-specpodsetstemplatespecwithhostnetwork)
        * [`fn withHostPID(hostPID)`](#fn-specpodsetstemplatespecwithhostpid)
        * [`fn withHostUsers(hostUsers)`](#fn-specpodsetstemplatespecwithhostusers)
        * [`fn withHostname(hostname)`](#fn-specpodsetstemplatespecwithhostname)
        * [`fn withHostnameOverride(hostnameOverride)`](#fn-specpodsetstemplatespecwithhostnameoverride)
        * [`fn withImagePullSecrets(imagePullSecrets)`](#fn-specpodsetstemplatespecwithimagepullsecrets)
        * [`fn withImagePullSecretsMixin(imagePullSecrets)`](#fn-specpodsetstemplatespecwithimagepullsecretsmixin)
        * [`fn withInitContainers(initContainers)`](#fn-specpodsetstemplatespecwithinitcontainers)
        * [`fn withInitContainersMixin(initContainers)`](#fn-specpodsetstemplatespecwithinitcontainersmixin)
        * [`fn withNodeName(nodeName)`](#fn-specpodsetstemplatespecwithnodename)
        * [`fn withNodeSelector(nodeSelector)`](#fn-specpodsetstemplatespecwithnodeselector)
        * [`fn withNodeSelectorMixin(nodeSelector)`](#fn-specpodsetstemplatespecwithnodeselectormixin)
        * [`fn withOverhead(overhead)`](#fn-specpodsetstemplatespecwithoverhead)
        * [`fn withOverheadMixin(overhead)`](#fn-specpodsetstemplatespecwithoverheadmixin)
        * [`fn withPreemptionPolicy(preemptionPolicy)`](#fn-specpodsetstemplatespecwithpreemptionpolicy)
        * [`fn withPriority(priority)`](#fn-specpodsetstemplatespecwithpriority)
        * [`fn withPriorityClassName(priorityClassName)`](#fn-specpodsetstemplatespecwithpriorityclassname)
        * [`fn withReadinessGates(readinessGates)`](#fn-specpodsetstemplatespecwithreadinessgates)
        * [`fn withReadinessGatesMixin(readinessGates)`](#fn-specpodsetstemplatespecwithreadinessgatesmixin)
        * [`fn withResourceClaims(resourceClaims)`](#fn-specpodsetstemplatespecwithresourceclaims)
        * [`fn withResourceClaimsMixin(resourceClaims)`](#fn-specpodsetstemplatespecwithresourceclaimsmixin)
        * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespecwithrestartpolicy)
        * [`fn withRuntimeClassName(runtimeClassName)`](#fn-specpodsetstemplatespecwithruntimeclassname)
        * [`fn withSchedulerName(schedulerName)`](#fn-specpodsetstemplatespecwithschedulername)
        * [`fn withSchedulingGates(schedulingGates)`](#fn-specpodsetstemplatespecwithschedulinggates)
        * [`fn withSchedulingGatesMixin(schedulingGates)`](#fn-specpodsetstemplatespecwithschedulinggatesmixin)
        * [`fn withServiceAccount(serviceAccount)`](#fn-specpodsetstemplatespecwithserviceaccount)
        * [`fn withServiceAccountName(serviceAccountName)`](#fn-specpodsetstemplatespecwithserviceaccountname)
        * [`fn withSetHostnameAsFQDN(setHostnameAsFQDN)`](#fn-specpodsetstemplatespecwithsethostnameasfqdn)
        * [`fn withShareProcessNamespace(shareProcessNamespace)`](#fn-specpodsetstemplatespecwithshareprocessnamespace)
        * [`fn withSubdomain(subdomain)`](#fn-specpodsetstemplatespecwithsubdomain)
        * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecwithterminationgraceperiodseconds)
        * [`fn withTolerations(tolerations)`](#fn-specpodsetstemplatespecwithtolerations)
        * [`fn withTolerationsMixin(tolerations)`](#fn-specpodsetstemplatespecwithtolerationsmixin)
        * [`fn withTopologySpreadConstraints(topologySpreadConstraints)`](#fn-specpodsetstemplatespecwithtopologyspreadconstraints)
        * [`fn withTopologySpreadConstraintsMixin(topologySpreadConstraints)`](#fn-specpodsetstemplatespecwithtopologyspreadconstraintsmixin)
        * [`fn withVolumes(volumes)`](#fn-specpodsetstemplatespecwithvolumes)
        * [`fn withVolumesMixin(volumes)`](#fn-specpodsetstemplatespecwithvolumesmixin)
        * [`obj spec.podSets.template.spec.affinity`](#obj-specpodsetstemplatespecaffinity)
          * [`obj spec.podSets.template.spec.affinity.nodeAffinity`](#obj-specpodsetstemplatespecaffinitynodeaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitynodeaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference`](#obj-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreference)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchexpressionsmixin)
                * [`fn withMatchFields(matchFields)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfields)
                * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencewithmatchfieldsmixin)
                * [`obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions`](#obj-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchexpressionswithvaluesmixin)
                * [`obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields`](#obj-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfields)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinitypreferredduringschedulingignoredduringexecutionpreferencematchfieldswithvaluesmixin)
            * [`obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withNodeSelectorTerms(nodeSelectorTerms)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectorterms)
              * [`fn withNodeSelectorTermsMixin(nodeSelectorTerms)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionwithnodeselectortermsmixin)
              * [`obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms`](#obj-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectorterms)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchexpressionsmixin)
                * [`fn withMatchFields(matchFields)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfields)
                * [`fn withMatchFieldsMixin(matchFields)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermswithmatchfieldsmixin)
                * [`obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions`](#obj-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchexpressionswithvaluesmixin)
                * [`obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields`](#obj-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfields)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitynodeaffinityrequiredduringschedulingignoredduringexecutionnodeselectortermsmatchfieldswithvaluesmixin)
          * [`obj spec.podSets.template.spec.affinity.podAffinity`](#obj-specpodsetstemplatespecaffinitypodaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecution)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                * [`fn withNamespaces(namespaces)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                * [`fn withNamespacesMixin(namespaces)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                * [`fn withTopologyKey(topologyKey)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
            * [`obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
              * [`obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                * [`obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
          * [`obj spec.podSets.template.spec.affinity.podAntiAffinity`](#obj-specpodsetstemplatespecaffinitypodantiaffinity)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecution)
            * [`fn withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitywithpreferredduringschedulingignoredduringexecutionmixin)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecution)
            * [`fn withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitywithrequiredduringschedulingignoredduringexecutionmixin)
            * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecution)
              * [`fn withWeight(weight)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionwithweight)
              * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinityterm)
                * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeys)
                * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmatchlabelkeysmixin)
                * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeys)
                * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithmismatchlabelkeysmixin)
                * [`fn withNamespaces(namespaces)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespaces)
                * [`fn withNamespacesMixin(namespaces)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithnamespacesmixin)
                * [`fn withTopologyKey(topologyKey)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermwithtopologykey)
                * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermlabelselectormatchexpressionswithvaluesmixin)
                * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinitypreferredduringschedulingignoredduringexecutionpodaffinitytermnamespaceselectormatchexpressionswithvaluesmixin)
            * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution`](#obj-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecution)
              * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeys)
              * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmatchlabelkeysmixin)
              * [`fn withMismatchLabelKeys(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeys)
              * [`fn withMismatchLabelKeysMixin(mismatchLabelKeys)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithmismatchlabelkeysmixin)
              * [`fn withNamespaces(namespaces)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespaces)
              * [`fn withNamespacesMixin(namespaces)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithnamespacesmixin)
              * [`fn withTopologyKey(topologyKey)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionwithtopologykey)
              * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector`](#obj-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectorwithmatchlabelsmixin)
                * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionlabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector`](#obj-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselector)
                * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressions)
                * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchexpressionsmixin)
                * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabels)
                * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectorwithmatchlabelsmixin)
                * [`obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions`](#obj-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressions)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithkey)
                  * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithoperator)
                  * [`fn withValues(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvalues)
                  * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecaffinitypodantiaffinityrequiredduringschedulingignoredduringexecutionnamespaceselectormatchexpressionswithvaluesmixin)
        * [`obj spec.podSets.template.spec.containers`](#obj-specpodsetstemplatespeccontainers)
          * [`fn withArgs(args)`](#fn-specpodsetstemplatespeccontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specpodsetstemplatespeccontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specpodsetstemplatespeccontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specpodsetstemplatespeccontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specpodsetstemplatespeccontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specpodsetstemplatespeccontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specpodsetstemplatespeccontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodsetstemplatespeccontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainerswithname)
          * [`fn withPorts(ports)`](#fn-specpodsetstemplatespeccontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specpodsetstemplatespeccontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specpodsetstemplatespeccontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodsetstemplatespeccontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespeccontainerswithrestartpolicy)
          * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodsetstemplatespeccontainerswithrestartpolicyrules)
          * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodsetstemplatespeccontainerswithrestartpolicyrulesmixin)
          * [`fn withStdin(stdin)`](#fn-specpodsetstemplatespeccontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specpodsetstemplatespeccontainerswithstdinonce)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodsetstemplatespeccontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodsetstemplatespeccontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specpodsetstemplatespeccontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodsetstemplatespeccontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodsetstemplatespeccontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodsetstemplatespeccontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodsetstemplatespeccontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specpodsetstemplatespeccontainerswithworkingdir)
          * [`obj spec.podSets.template.spec.containers.env`](#obj-specpodsetstemplatespeccontainersenv)
            * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersenvwithname)
            * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainersenvwithvalue)
            * [`obj spec.podSets.template.spec.containers.env.valueFrom`](#obj-specpodsetstemplatespeccontainersenvvaluefrom)
              * [`obj spec.podSets.template.spec.containers.env.valueFrom.configMapKeyRef`](#obj-specpodsetstemplatespeccontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespeccontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespeccontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.podSets.template.spec.containers.env.valueFrom.fieldRef`](#obj-specpodsetstemplatespeccontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef`](#obj-specpodsetstemplatespeccontainersenvvaluefromfilekeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfilekeyrefwithkey)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfilekeyrefwithoptional)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfilekeyrefwithpath)
                * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespeccontainersenvvaluefromfilekeyrefwithvolumename)
              * [`obj spec.podSets.template.spec.containers.env.valueFrom.resourceFieldRef`](#obj-specpodsetstemplatespeccontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specpodsetstemplatespeccontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specpodsetstemplatespeccontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specpodsetstemplatespeccontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.podSets.template.spec.containers.env.valueFrom.secretKeyRef`](#obj-specpodsetstemplatespeccontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespeccontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespeccontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.podSets.template.spec.containers.envFrom`](#obj-specpodsetstemplatespeccontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specpodsetstemplatespeccontainersenvfromwithprefix)
            * [`obj spec.podSets.template.spec.containers.envFrom.configMapRef`](#obj-specpodsetstemplatespeccontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespeccontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.podSets.template.spec.containers.envFrom.secretRef`](#obj-specpodsetstemplatespeccontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespeccontainersenvfromsecretrefwithoptional)
          * [`obj spec.podSets.template.spec.containers.lifecycle`](#obj-specpodsetstemplatespeccontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specpodsetstemplatespeccontainerslifecyclewithstopsignal)
            * [`obj spec.podSets.template.spec.containers.lifecycle.postStart`](#obj-specpodsetstemplatespeccontainerslifecyclepoststart)
              * [`obj spec.podSets.template.spec.containers.lifecycle.postStart.exec`](#obj-specpodsetstemplatespeccontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.containers.lifecycle.postStart.httpGet`](#obj-specpodsetstemplatespeccontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodsetstemplatespeccontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.containers.lifecycle.postStart.sleep`](#obj-specpodsetstemplatespeccontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.podSets.template.spec.containers.lifecycle.postStart.tcpSocket`](#obj-specpodsetstemplatespeccontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.podSets.template.spec.containers.lifecycle.preStop`](#obj-specpodsetstemplatespeccontainerslifecycleprestop)
              * [`obj spec.podSets.template.spec.containers.lifecycle.preStop.exec`](#obj-specpodsetstemplatespeccontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.containers.lifecycle.preStop.httpGet`](#obj-specpodsetstemplatespeccontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodsetstemplatespeccontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.containers.lifecycle.preStop.sleep`](#obj-specpodsetstemplatespeccontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespeccontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.podSets.template.spec.containers.lifecycle.preStop.tcpSocket`](#obj-specpodsetstemplatespeccontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.podSets.template.spec.containers.livenessProbe`](#obj-specpodsetstemplatespeccontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespeccontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.containers.livenessProbe.exec`](#obj-specpodsetstemplatespeccontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.containers.livenessProbe.grpc`](#obj-specpodsetstemplatespeccontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespeccontainerslivenessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.containers.livenessProbe.httpGet`](#obj-specpodsetstemplatespeccontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.containers.livenessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespeccontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.containers.livenessProbe.tcpSocket`](#obj-specpodsetstemplatespeccontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainerslivenessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.containers.ports`](#obj-specpodsetstemplatespeccontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specpodsetstemplatespeccontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specpodsetstemplatespeccontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specpodsetstemplatespeccontainersportswithhostport)
            * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specpodsetstemplatespeccontainersportswithprotocol)
          * [`obj spec.podSets.template.spec.containers.readinessProbe`](#obj-specpodsetstemplatespeccontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespeccontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.containers.readinessProbe.exec`](#obj-specpodsetstemplatespeccontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.containers.readinessProbe.grpc`](#obj-specpodsetstemplatespeccontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespeccontainersreadinessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.containers.readinessProbe.httpGet`](#obj-specpodsetstemplatespeccontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.containers.readinessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespeccontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.containers.readinessProbe.tcpSocket`](#obj-specpodsetstemplatespeccontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersreadinessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.containers.resizePolicy`](#obj-specpodsetstemplatespeccontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specpodsetstemplatespeccontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespeccontainersresizepolicywithrestartpolicy)
          * [`obj spec.podSets.template.spec.containers.resources`](#obj-specpodsetstemplatespeccontainersresources)
            * [`fn withClaims(claims)`](#fn-specpodsetstemplatespeccontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specpodsetstemplatespeccontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specpodsetstemplatespeccontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specpodsetstemplatespeccontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specpodsetstemplatespeccontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specpodsetstemplatespeccontainersresourceswithrequestsmixin)
            * [`obj spec.podSets.template.spec.containers.resources.claims`](#obj-specpodsetstemplatespeccontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specpodsetstemplatespeccontainersresourcesclaimswithrequest)
          * [`obj spec.podSets.template.spec.containers.restartPolicyRules`](#obj-specpodsetstemplatespeccontainersrestartpolicyrules)
            * [`fn withAction(action)`](#fn-specpodsetstemplatespeccontainersrestartpolicyruleswithaction)
            * [`obj spec.podSets.template.spec.containers.restartPolicyRules.exitCodes`](#obj-specpodsetstemplatespeccontainersrestartpolicyrulesexitcodes)
              * [`fn withOperator(operator)`](#fn-specpodsetstemplatespeccontainersrestartpolicyrulesexitcodeswithoperator)
              * [`fn withValues(values)`](#fn-specpodsetstemplatespeccontainersrestartpolicyrulesexitcodeswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespeccontainersrestartpolicyrulesexitcodeswithvaluesmixin)
          * [`obj spec.podSets.template.spec.containers.securityContext`](#obj-specpodsetstemplatespeccontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwithrunasuser)
            * [`obj spec.podSets.template.spec.containers.securityContext.appArmorProfile`](#obj-specpodsetstemplatespeccontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespeccontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespeccontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.podSets.template.spec.containers.securityContext.capabilities`](#obj-specpodsetstemplatespeccontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specpodsetstemplatespeccontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specpodsetstemplatespeccontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specpodsetstemplatespeccontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specpodsetstemplatespeccontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.podSets.template.spec.containers.securityContext.seLinuxOptions`](#obj-specpodsetstemplatespeccontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specpodsetstemplatespeccontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specpodsetstemplatespeccontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specpodsetstemplatespeccontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specpodsetstemplatespeccontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.podSets.template.spec.containers.securityContext.seccompProfile`](#obj-specpodsetstemplatespeccontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespeccontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespeccontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.podSets.template.spec.containers.securityContext.windowsOptions`](#obj-specpodsetstemplatespeccontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodsetstemplatespeccontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.podSets.template.spec.containers.startupProbe`](#obj-specpodsetstemplatespeccontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespeccontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespeccontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespeccontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespeccontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespeccontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespeccontainersstartupprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.containers.startupProbe.exec`](#obj-specpodsetstemplatespeccontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespeccontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespeccontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.containers.startupProbe.grpc`](#obj-specpodsetstemplatespeccontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespeccontainersstartupprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.containers.startupProbe.httpGet`](#obj-specpodsetstemplatespeccontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.containers.startupProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespeccontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespeccontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.containers.startupProbe.tcpSocket`](#obj-specpodsetstemplatespeccontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespeccontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespeccontainersstartupprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.containers.volumeDevices`](#obj-specpodsetstemplatespeccontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specpodsetstemplatespeccontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersvolumedeviceswithname)
          * [`obj spec.podSets.template.spec.containers.volumeMounts`](#obj-specpodsetstemplatespeccontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specpodsetstemplatespeccontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specpodsetstemplatespeccontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specpodsetstemplatespeccontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespeccontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodsetstemplatespeccontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specpodsetstemplatespeccontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodsetstemplatespeccontainersvolumemountswithsubpathexpr)
        * [`obj spec.podSets.template.spec.dnsConfig`](#obj-specpodsetstemplatespecdnsconfig)
          * [`fn withNameservers(nameservers)`](#fn-specpodsetstemplatespecdnsconfigwithnameservers)
          * [`fn withNameserversMixin(nameservers)`](#fn-specpodsetstemplatespecdnsconfigwithnameserversmixin)
          * [`fn withOptions(options)`](#fn-specpodsetstemplatespecdnsconfigwithoptions)
          * [`fn withOptionsMixin(options)`](#fn-specpodsetstemplatespecdnsconfigwithoptionsmixin)
          * [`fn withSearches(searches)`](#fn-specpodsetstemplatespecdnsconfigwithsearches)
          * [`fn withSearchesMixin(searches)`](#fn-specpodsetstemplatespecdnsconfigwithsearchesmixin)
          * [`obj spec.podSets.template.spec.dnsConfig.options`](#obj-specpodsetstemplatespecdnsconfigoptions)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecdnsconfigoptionswithname)
            * [`fn withValue(value)`](#fn-specpodsetstemplatespecdnsconfigoptionswithvalue)
        * [`obj spec.podSets.template.spec.ephemeralContainers`](#obj-specpodsetstemplatespecephemeralcontainers)
          * [`fn withArgs(args)`](#fn-specpodsetstemplatespecephemeralcontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specpodsetstemplatespecephemeralcontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specpodsetstemplatespecephemeralcontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specpodsetstemplatespecephemeralcontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specpodsetstemplatespecephemeralcontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specpodsetstemplatespecephemeralcontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specpodsetstemplatespecephemeralcontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodsetstemplatespecephemeralcontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainerswithname)
          * [`fn withPorts(ports)`](#fn-specpodsetstemplatespecephemeralcontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specpodsetstemplatespecephemeralcontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specpodsetstemplatespecephemeralcontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodsetstemplatespecephemeralcontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespecephemeralcontainerswithrestartpolicy)
          * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodsetstemplatespecephemeralcontainerswithrestartpolicyrules)
          * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodsetstemplatespecephemeralcontainerswithrestartpolicyrulesmixin)
          * [`fn withStdin(stdin)`](#fn-specpodsetstemplatespecephemeralcontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specpodsetstemplatespecephemeralcontainerswithstdinonce)
          * [`fn withTargetContainerName(targetContainerName)`](#fn-specpodsetstemplatespecephemeralcontainerswithtargetcontainername)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodsetstemplatespecephemeralcontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodsetstemplatespecephemeralcontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specpodsetstemplatespecephemeralcontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodsetstemplatespecephemeralcontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodsetstemplatespecephemeralcontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodsetstemplatespecephemeralcontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodsetstemplatespecephemeralcontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specpodsetstemplatespecephemeralcontainerswithworkingdir)
          * [`obj spec.podSets.template.spec.ephemeralContainers.env`](#obj-specpodsetstemplatespecephemeralcontainersenv)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersenvwithname)
            * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainersenvwithvalue)
            * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefrom)
              * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fieldRef`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefromfilekeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfilekeyrefwithkey)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfilekeyrefwithoptional)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfilekeyrefwithpath)
                * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromfilekeyrefwithvolumename)
              * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef`](#obj-specpodsetstemplatespecephemeralcontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecephemeralcontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.podSets.template.spec.ephemeralContainers.envFrom`](#obj-specpodsetstemplatespecephemeralcontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specpodsetstemplatespecephemeralcontainersenvfromwithprefix)
            * [`obj spec.podSets.template.spec.ephemeralContainers.envFrom.configMapRef`](#obj-specpodsetstemplatespecephemeralcontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecephemeralcontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.podSets.template.spec.ephemeralContainers.envFrom.secretRef`](#obj-specpodsetstemplatespecephemeralcontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecephemeralcontainersenvfromsecretrefwithoptional)
          * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle`](#obj-specpodsetstemplatespecephemeralcontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclewithstopsignal)
            * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststart)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.exec`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.sleep`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket`](#obj-specpodsetstemplatespecephemeralcontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestop)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.exec`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.sleep`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket`](#obj-specpodsetstemplatespecephemeralcontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.exec`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.grpc`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.tcpSocket`](#obj-specpodsetstemplatespecephemeralcontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainerslivenessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.ephemeralContainers.ports`](#obj-specpodsetstemplatespecephemeralcontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specpodsetstemplatespecephemeralcontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specpodsetstemplatespecephemeralcontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specpodsetstemplatespecephemeralcontainersportswithhostport)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specpodsetstemplatespecephemeralcontainersportswithprotocol)
          * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.exec`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.grpc`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.tcpSocket`](#obj-specpodsetstemplatespecephemeralcontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersreadinessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.ephemeralContainers.resizePolicy`](#obj-specpodsetstemplatespecephemeralcontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specpodsetstemplatespecephemeralcontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespecephemeralcontainersresizepolicywithrestartpolicy)
          * [`obj spec.podSets.template.spec.ephemeralContainers.resources`](#obj-specpodsetstemplatespecephemeralcontainersresources)
            * [`fn withClaims(claims)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specpodsetstemplatespecephemeralcontainersresourceswithrequestsmixin)
            * [`obj spec.podSets.template.spec.ephemeralContainers.resources.claims`](#obj-specpodsetstemplatespecephemeralcontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specpodsetstemplatespecephemeralcontainersresourcesclaimswithrequest)
          * [`obj spec.podSets.template.spec.ephemeralContainers.restartPolicyRules`](#obj-specpodsetstemplatespecephemeralcontainersrestartpolicyrules)
            * [`fn withAction(action)`](#fn-specpodsetstemplatespecephemeralcontainersrestartpolicyruleswithaction)
            * [`obj spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.exitCodes`](#obj-specpodsetstemplatespecephemeralcontainersrestartpolicyrulesexitcodes)
              * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithoperator)
              * [`fn withValues(values)`](#fn-specpodsetstemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecephemeralcontainersrestartpolicyrulesexitcodeswithvaluesmixin)
          * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwithrunasuser)
            * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext.appArmorProfile`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext.seccompProfile`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions`](#obj-specpodsetstemplatespecephemeralcontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodsetstemplatespecephemeralcontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe.exec`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe.grpc`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.ephemeralContainers.startupProbe.tcpSocket`](#obj-specpodsetstemplatespecephemeralcontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecephemeralcontainersstartupprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.ephemeralContainers.volumeDevices`](#obj-specpodsetstemplatespecephemeralcontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specpodsetstemplatespecephemeralcontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersvolumedeviceswithname)
          * [`obj spec.podSets.template.spec.ephemeralContainers.volumeMounts`](#obj-specpodsetstemplatespecephemeralcontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodsetstemplatespecephemeralcontainersvolumemountswithsubpathexpr)
        * [`obj spec.podSets.template.spec.hostAliases`](#obj-specpodsetstemplatespechostaliases)
          * [`fn withHostnames(hostnames)`](#fn-specpodsetstemplatespechostaliaseswithhostnames)
          * [`fn withHostnamesMixin(hostnames)`](#fn-specpodsetstemplatespechostaliaseswithhostnamesmixin)
          * [`fn withIp(ip)`](#fn-specpodsetstemplatespechostaliaseswithip)
        * [`obj spec.podSets.template.spec.imagePullSecrets`](#obj-specpodsetstemplatespecimagepullsecrets)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecimagepullsecretswithname)
        * [`obj spec.podSets.template.spec.initContainers`](#obj-specpodsetstemplatespecinitcontainers)
          * [`fn withArgs(args)`](#fn-specpodsetstemplatespecinitcontainerswithargs)
          * [`fn withArgsMixin(args)`](#fn-specpodsetstemplatespecinitcontainerswithargsmixin)
          * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainerswithcommand)
          * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainerswithcommandmixin)
          * [`fn withEnv(env)`](#fn-specpodsetstemplatespecinitcontainerswithenv)
          * [`fn withEnvFrom(envFrom)`](#fn-specpodsetstemplatespecinitcontainerswithenvfrom)
          * [`fn withEnvFromMixin(envFrom)`](#fn-specpodsetstemplatespecinitcontainerswithenvfrommixin)
          * [`fn withEnvMixin(env)`](#fn-specpodsetstemplatespecinitcontainerswithenvmixin)
          * [`fn withImage(image)`](#fn-specpodsetstemplatespecinitcontainerswithimage)
          * [`fn withImagePullPolicy(imagePullPolicy)`](#fn-specpodsetstemplatespecinitcontainerswithimagepullpolicy)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainerswithname)
          * [`fn withPorts(ports)`](#fn-specpodsetstemplatespecinitcontainerswithports)
          * [`fn withPortsMixin(ports)`](#fn-specpodsetstemplatespecinitcontainerswithportsmixin)
          * [`fn withResizePolicy(resizePolicy)`](#fn-specpodsetstemplatespecinitcontainerswithresizepolicy)
          * [`fn withResizePolicyMixin(resizePolicy)`](#fn-specpodsetstemplatespecinitcontainerswithresizepolicymixin)
          * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespecinitcontainerswithrestartpolicy)
          * [`fn withRestartPolicyRules(restartPolicyRules)`](#fn-specpodsetstemplatespecinitcontainerswithrestartpolicyrules)
          * [`fn withRestartPolicyRulesMixin(restartPolicyRules)`](#fn-specpodsetstemplatespecinitcontainerswithrestartpolicyrulesmixin)
          * [`fn withStdin(stdin)`](#fn-specpodsetstemplatespecinitcontainerswithstdin)
          * [`fn withStdinOnce(stdinOnce)`](#fn-specpodsetstemplatespecinitcontainerswithstdinonce)
          * [`fn withTerminationMessagePath(terminationMessagePath)`](#fn-specpodsetstemplatespecinitcontainerswithterminationmessagepath)
          * [`fn withTerminationMessagePolicy(terminationMessagePolicy)`](#fn-specpodsetstemplatespecinitcontainerswithterminationmessagepolicy)
          * [`fn withTty(tty)`](#fn-specpodsetstemplatespecinitcontainerswithtty)
          * [`fn withVolumeDevices(volumeDevices)`](#fn-specpodsetstemplatespecinitcontainerswithvolumedevices)
          * [`fn withVolumeDevicesMixin(volumeDevices)`](#fn-specpodsetstemplatespecinitcontainerswithvolumedevicesmixin)
          * [`fn withVolumeMounts(volumeMounts)`](#fn-specpodsetstemplatespecinitcontainerswithvolumemounts)
          * [`fn withVolumeMountsMixin(volumeMounts)`](#fn-specpodsetstemplatespecinitcontainerswithvolumemountsmixin)
          * [`fn withWorkingDir(workingDir)`](#fn-specpodsetstemplatespecinitcontainerswithworkingdir)
          * [`obj spec.podSets.template.spec.initContainers.env`](#obj-specpodsetstemplatespecinitcontainersenv)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersenvwithname)
            * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainersenvwithvalue)
            * [`obj spec.podSets.template.spec.initContainers.env.valueFrom`](#obj-specpodsetstemplatespecinitcontainersenvvaluefrom)
              * [`obj spec.podSets.template.spec.initContainers.env.valueFrom.configMapKeyRef`](#obj-specpodsetstemplatespecinitcontainersenvvaluefromconfigmapkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromconfigmapkeyrefwithoptional)
              * [`obj spec.podSets.template.spec.initContainers.env.valueFrom.fieldRef`](#obj-specpodsetstemplatespecinitcontainersenvvaluefromfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfieldrefwithfieldpath)
              * [`obj spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef`](#obj-specpodsetstemplatespecinitcontainersenvvaluefromfilekeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfilekeyrefwithkey)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfilekeyrefwithoptional)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfilekeyrefwithpath)
                * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromfilekeyrefwithvolumename)
              * [`obj spec.podSets.template.spec.initContainers.env.valueFrom.resourceFieldRef`](#obj-specpodsetstemplatespecinitcontainersenvvaluefromresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromresourcefieldrefwithresource)
              * [`obj spec.podSets.template.spec.initContainers.env.valueFrom.secretKeyRef`](#obj-specpodsetstemplatespecinitcontainersenvvaluefromsecretkeyref)
                * [`fn withKey(key)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromsecretkeyrefwithkey)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromsecretkeyrefwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecinitcontainersenvvaluefromsecretkeyrefwithoptional)
          * [`obj spec.podSets.template.spec.initContainers.envFrom`](#obj-specpodsetstemplatespecinitcontainersenvfrom)
            * [`fn withPrefix(prefix)`](#fn-specpodsetstemplatespecinitcontainersenvfromwithprefix)
            * [`obj spec.podSets.template.spec.initContainers.envFrom.configMapRef`](#obj-specpodsetstemplatespecinitcontainersenvfromconfigmapref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersenvfromconfigmaprefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecinitcontainersenvfromconfigmaprefwithoptional)
            * [`obj spec.podSets.template.spec.initContainers.envFrom.secretRef`](#obj-specpodsetstemplatespecinitcontainersenvfromsecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersenvfromsecretrefwithname)
              * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecinitcontainersenvfromsecretrefwithoptional)
          * [`obj spec.podSets.template.spec.initContainers.lifecycle`](#obj-specpodsetstemplatespecinitcontainerslifecycle)
            * [`fn withStopSignal(stopSignal)`](#fn-specpodsetstemplatespecinitcontainerslifecyclewithstopsignal)
            * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststart)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart.exec`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststartexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststartexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststartexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgetwithscheme)
                * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarthttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart.sleep`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststartsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststartsleepwithseconds)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.postStart.tcpSocket`](#obj-specpodsetstemplatespecinitcontainerslifecyclepoststarttcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarttcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslifecyclepoststarttcpsocketwithport)
            * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestop)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop.exec`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestopexec)
                * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestopexecwithcommand)
                * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestopexecwithcommandmixin)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestophttpget)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithhost)
                * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithhttpheaders)
                * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithhttpheadersmixin)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithpath)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithport)
                * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgetwithscheme)
                * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestophttpgethttpheaders)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithname)
                  * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestophttpgethttpheaderswithvalue)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop.sleep`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestopsleep)
                * [`fn withSeconds(seconds)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestopsleepwithseconds)
              * [`obj spec.podSets.template.spec.initContainers.lifecycle.preStop.tcpSocket`](#obj-specpodsetstemplatespecinitcontainerslifecycleprestoptcpsocket)
                * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestoptcpsocketwithhost)
                * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslifecycleprestoptcpsocketwithport)
          * [`obj spec.podSets.template.spec.initContainers.livenessProbe`](#obj-specpodsetstemplatespecinitcontainerslivenessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.initContainers.livenessProbe.exec`](#obj-specpodsetstemplatespecinitcontainerslivenessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.initContainers.livenessProbe.grpc`](#obj-specpodsetstemplatespecinitcontainerslivenessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.initContainers.livenessProbe.httpGet`](#obj-specpodsetstemplatespecinitcontainerslivenessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.initContainers.livenessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecinitcontainerslivenessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.initContainers.livenessProbe.tcpSocket`](#obj-specpodsetstemplatespecinitcontainerslivenessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainerslivenessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.initContainers.ports`](#obj-specpodsetstemplatespecinitcontainersports)
            * [`fn withContainerPort(containerPort)`](#fn-specpodsetstemplatespecinitcontainersportswithcontainerport)
            * [`fn withHostIP(hostIP)`](#fn-specpodsetstemplatespecinitcontainersportswithhostip)
            * [`fn withHostPort(hostPort)`](#fn-specpodsetstemplatespecinitcontainersportswithhostport)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersportswithname)
            * [`fn withProtocol(protocol)`](#fn-specpodsetstemplatespecinitcontainersportswithprotocol)
          * [`obj spec.podSets.template.spec.initContainers.readinessProbe`](#obj-specpodsetstemplatespecinitcontainersreadinessprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.initContainers.readinessProbe.exec`](#obj-specpodsetstemplatespecinitcontainersreadinessprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.initContainers.readinessProbe.grpc`](#obj-specpodsetstemplatespecinitcontainersreadinessprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.initContainers.readinessProbe.httpGet`](#obj-specpodsetstemplatespecinitcontainersreadinessprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.initContainers.readinessProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecinitcontainersreadinessprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.initContainers.readinessProbe.tcpSocket`](#obj-specpodsetstemplatespecinitcontainersreadinessprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersreadinessprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.initContainers.resizePolicy`](#obj-specpodsetstemplatespecinitcontainersresizepolicy)
            * [`fn withResourceName(resourceName)`](#fn-specpodsetstemplatespecinitcontainersresizepolicywithresourcename)
            * [`fn withRestartPolicy(restartPolicy)`](#fn-specpodsetstemplatespecinitcontainersresizepolicywithrestartpolicy)
          * [`obj spec.podSets.template.spec.initContainers.resources`](#obj-specpodsetstemplatespecinitcontainersresources)
            * [`fn withClaims(claims)`](#fn-specpodsetstemplatespecinitcontainersresourceswithclaims)
            * [`fn withClaimsMixin(claims)`](#fn-specpodsetstemplatespecinitcontainersresourceswithclaimsmixin)
            * [`fn withLimits(limits)`](#fn-specpodsetstemplatespecinitcontainersresourceswithlimits)
            * [`fn withLimitsMixin(limits)`](#fn-specpodsetstemplatespecinitcontainersresourceswithlimitsmixin)
            * [`fn withRequests(requests)`](#fn-specpodsetstemplatespecinitcontainersresourceswithrequests)
            * [`fn withRequestsMixin(requests)`](#fn-specpodsetstemplatespecinitcontainersresourceswithrequestsmixin)
            * [`obj spec.podSets.template.spec.initContainers.resources.claims`](#obj-specpodsetstemplatespecinitcontainersresourcesclaims)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersresourcesclaimswithname)
              * [`fn withRequest(request)`](#fn-specpodsetstemplatespecinitcontainersresourcesclaimswithrequest)
          * [`obj spec.podSets.template.spec.initContainers.restartPolicyRules`](#obj-specpodsetstemplatespecinitcontainersrestartpolicyrules)
            * [`fn withAction(action)`](#fn-specpodsetstemplatespecinitcontainersrestartpolicyruleswithaction)
            * [`obj spec.podSets.template.spec.initContainers.restartPolicyRules.exitCodes`](#obj-specpodsetstemplatespecinitcontainersrestartpolicyrulesexitcodes)
              * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecinitcontainersrestartpolicyrulesexitcodeswithoperator)
              * [`fn withValues(values)`](#fn-specpodsetstemplatespecinitcontainersrestartpolicyrulesexitcodeswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecinitcontainersrestartpolicyrulesexitcodeswithvaluesmixin)
          * [`obj spec.podSets.template.spec.initContainers.securityContext`](#obj-specpodsetstemplatespecinitcontainerssecuritycontext)
            * [`fn withAllowPrivilegeEscalation(allowPrivilegeEscalation)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithallowprivilegeescalation)
            * [`fn withPrivileged(privileged)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithprivileged)
            * [`fn withProcMount(procMount)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithprocmount)
            * [`fn withReadOnlyRootFilesystem(readOnlyRootFilesystem)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithreadonlyrootfilesystem)
            * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithrunasgroup)
            * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithrunasnonroot)
            * [`fn withRunAsUser(runAsUser)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwithrunasuser)
            * [`obj spec.podSets.template.spec.initContainers.securityContext.appArmorProfile`](#obj-specpodsetstemplatespecinitcontainerssecuritycontextapparmorprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextapparmorprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextapparmorprofilewithtype)
            * [`obj spec.podSets.template.spec.initContainers.securityContext.capabilities`](#obj-specpodsetstemplatespecinitcontainerssecuritycontextcapabilities)
              * [`fn withAdd(add)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextcapabilitieswithadd)
              * [`fn withAddMixin(add)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextcapabilitieswithaddmixin)
              * [`fn withDrop(drop)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextcapabilitieswithdrop)
              * [`fn withDropMixin(drop)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextcapabilitieswithdropmixin)
            * [`obj spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions`](#obj-specpodsetstemplatespecinitcontainerssecuritycontextselinuxoptions)
              * [`fn withLevel(level)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextselinuxoptionswithlevel)
              * [`fn withRole(role)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextselinuxoptionswithrole)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextselinuxoptionswithtype)
              * [`fn withUser(user)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextselinuxoptionswithuser)
            * [`obj spec.podSets.template.spec.initContainers.securityContext.seccompProfile`](#obj-specpodsetstemplatespecinitcontainerssecuritycontextseccompprofile)
              * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextseccompprofilewithlocalhostprofile)
              * [`fn withType(type)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextseccompprofilewithtype)
            * [`obj spec.podSets.template.spec.initContainers.securityContext.windowsOptions`](#obj-specpodsetstemplatespecinitcontainerssecuritycontextwindowsoptions)
              * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspec)
              * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwindowsoptionswithgmsacredentialspecname)
              * [`fn withHostProcess(hostProcess)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwindowsoptionswithhostprocess)
              * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodsetstemplatespecinitcontainerssecuritycontextwindowsoptionswithrunasusername)
          * [`obj spec.podSets.template.spec.initContainers.startupProbe`](#obj-specpodsetstemplatespecinitcontainersstartupprobe)
            * [`fn withFailureThreshold(failureThreshold)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithfailurethreshold)
            * [`fn withInitialDelaySeconds(initialDelaySeconds)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithinitialdelayseconds)
            * [`fn withPeriodSeconds(periodSeconds)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithperiodseconds)
            * [`fn withSuccessThreshold(successThreshold)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithsuccessthreshold)
            * [`fn withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithterminationgraceperiodseconds)
            * [`fn withTimeoutSeconds(timeoutSeconds)`](#fn-specpodsetstemplatespecinitcontainersstartupprobewithtimeoutseconds)
            * [`obj spec.podSets.template.spec.initContainers.startupProbe.exec`](#obj-specpodsetstemplatespecinitcontainersstartupprobeexec)
              * [`fn withCommand(command)`](#fn-specpodsetstemplatespecinitcontainersstartupprobeexecwithcommand)
              * [`fn withCommandMixin(command)`](#fn-specpodsetstemplatespecinitcontainersstartupprobeexecwithcommandmixin)
            * [`obj spec.podSets.template.spec.initContainers.startupProbe.grpc`](#obj-specpodsetstemplatespecinitcontainersstartupprobegrpc)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersstartupprobegrpcwithport)
              * [`fn withService(service)`](#fn-specpodsetstemplatespecinitcontainersstartupprobegrpcwithservice)
            * [`obj spec.podSets.template.spec.initContainers.startupProbe.httpGet`](#obj-specpodsetstemplatespecinitcontainersstartupprobehttpget)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithhost)
              * [`fn withHttpHeaders(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithhttpheaders)
              * [`fn withHttpHeadersMixin(httpHeaders)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithhttpheadersmixin)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithpath)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithport)
              * [`fn withScheme(scheme)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgetwithscheme)
              * [`obj spec.podSets.template.spec.initContainers.startupProbe.httpGet.httpHeaders`](#obj-specpodsetstemplatespecinitcontainersstartupprobehttpgethttpheaders)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgethttpheaderswithname)
                * [`fn withValue(value)`](#fn-specpodsetstemplatespecinitcontainersstartupprobehttpgethttpheaderswithvalue)
            * [`obj spec.podSets.template.spec.initContainers.startupProbe.tcpSocket`](#obj-specpodsetstemplatespecinitcontainersstartupprobetcpsocket)
              * [`fn withHost(host)`](#fn-specpodsetstemplatespecinitcontainersstartupprobetcpsocketwithhost)
              * [`fn withPort(port)`](#fn-specpodsetstemplatespecinitcontainersstartupprobetcpsocketwithport)
          * [`obj spec.podSets.template.spec.initContainers.volumeDevices`](#obj-specpodsetstemplatespecinitcontainersvolumedevices)
            * [`fn withDevicePath(devicePath)`](#fn-specpodsetstemplatespecinitcontainersvolumedeviceswithdevicepath)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersvolumedeviceswithname)
          * [`obj spec.podSets.template.spec.initContainers.volumeMounts`](#obj-specpodsetstemplatespecinitcontainersvolumemounts)
            * [`fn withMountPath(mountPath)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithmountpath)
            * [`fn withMountPropagation(mountPropagation)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithmountpropagation)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithname)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithreadonly)
            * [`fn withRecursiveReadOnly(recursiveReadOnly)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithrecursivereadonly)
            * [`fn withSubPath(subPath)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithsubpath)
            * [`fn withSubPathExpr(subPathExpr)`](#fn-specpodsetstemplatespecinitcontainersvolumemountswithsubpathexpr)
        * [`obj spec.podSets.template.spec.os`](#obj-specpodsetstemplatespecos)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecoswithname)
        * [`obj spec.podSets.template.spec.readinessGates`](#obj-specpodsetstemplatespecreadinessgates)
          * [`fn withConditionType(conditionType)`](#fn-specpodsetstemplatespecreadinessgateswithconditiontype)
        * [`obj spec.podSets.template.spec.resourceClaims`](#obj-specpodsetstemplatespecresourceclaims)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecresourceclaimswithname)
          * [`fn withResourceClaimName(resourceClaimName)`](#fn-specpodsetstemplatespecresourceclaimswithresourceclaimname)
          * [`fn withResourceClaimTemplateName(resourceClaimTemplateName)`](#fn-specpodsetstemplatespecresourceclaimswithresourceclaimtemplatename)
        * [`obj spec.podSets.template.spec.resources`](#obj-specpodsetstemplatespecresources)
          * [`fn withClaims(claims)`](#fn-specpodsetstemplatespecresourceswithclaims)
          * [`fn withClaimsMixin(claims)`](#fn-specpodsetstemplatespecresourceswithclaimsmixin)
          * [`fn withLimits(limits)`](#fn-specpodsetstemplatespecresourceswithlimits)
          * [`fn withLimitsMixin(limits)`](#fn-specpodsetstemplatespecresourceswithlimitsmixin)
          * [`fn withRequests(requests)`](#fn-specpodsetstemplatespecresourceswithrequests)
          * [`fn withRequestsMixin(requests)`](#fn-specpodsetstemplatespecresourceswithrequestsmixin)
          * [`obj spec.podSets.template.spec.resources.claims`](#obj-specpodsetstemplatespecresourcesclaims)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecresourcesclaimswithname)
            * [`fn withRequest(request)`](#fn-specpodsetstemplatespecresourcesclaimswithrequest)
        * [`obj spec.podSets.template.spec.schedulingGates`](#obj-specpodsetstemplatespecschedulinggates)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecschedulinggateswithname)
        * [`obj spec.podSets.template.spec.securityContext`](#obj-specpodsetstemplatespecsecuritycontext)
          * [`fn withFsGroup(fsGroup)`](#fn-specpodsetstemplatespecsecuritycontextwithfsgroup)
          * [`fn withFsGroupChangePolicy(fsGroupChangePolicy)`](#fn-specpodsetstemplatespecsecuritycontextwithfsgroupchangepolicy)
          * [`fn withRunAsGroup(runAsGroup)`](#fn-specpodsetstemplatespecsecuritycontextwithrunasgroup)
          * [`fn withRunAsNonRoot(runAsNonRoot)`](#fn-specpodsetstemplatespecsecuritycontextwithrunasnonroot)
          * [`fn withRunAsUser(runAsUser)`](#fn-specpodsetstemplatespecsecuritycontextwithrunasuser)
          * [`fn withSeLinuxChangePolicy(seLinuxChangePolicy)`](#fn-specpodsetstemplatespecsecuritycontextwithselinuxchangepolicy)
          * [`fn withSupplementalGroups(supplementalGroups)`](#fn-specpodsetstemplatespecsecuritycontextwithsupplementalgroups)
          * [`fn withSupplementalGroupsMixin(supplementalGroups)`](#fn-specpodsetstemplatespecsecuritycontextwithsupplementalgroupsmixin)
          * [`fn withSupplementalGroupsPolicy(supplementalGroupsPolicy)`](#fn-specpodsetstemplatespecsecuritycontextwithsupplementalgroupspolicy)
          * [`fn withSysctls(sysctls)`](#fn-specpodsetstemplatespecsecuritycontextwithsysctls)
          * [`fn withSysctlsMixin(sysctls)`](#fn-specpodsetstemplatespecsecuritycontextwithsysctlsmixin)
          * [`obj spec.podSets.template.spec.securityContext.appArmorProfile`](#obj-specpodsetstemplatespecsecuritycontextapparmorprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecsecuritycontextapparmorprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodsetstemplatespecsecuritycontextapparmorprofilewithtype)
          * [`obj spec.podSets.template.spec.securityContext.seLinuxOptions`](#obj-specpodsetstemplatespecsecuritycontextselinuxoptions)
            * [`fn withLevel(level)`](#fn-specpodsetstemplatespecsecuritycontextselinuxoptionswithlevel)
            * [`fn withRole(role)`](#fn-specpodsetstemplatespecsecuritycontextselinuxoptionswithrole)
            * [`fn withType(type)`](#fn-specpodsetstemplatespecsecuritycontextselinuxoptionswithtype)
            * [`fn withUser(user)`](#fn-specpodsetstemplatespecsecuritycontextselinuxoptionswithuser)
          * [`obj spec.podSets.template.spec.securityContext.seccompProfile`](#obj-specpodsetstemplatespecsecuritycontextseccompprofile)
            * [`fn withLocalhostProfile(localhostProfile)`](#fn-specpodsetstemplatespecsecuritycontextseccompprofilewithlocalhostprofile)
            * [`fn withType(type)`](#fn-specpodsetstemplatespecsecuritycontextseccompprofilewithtype)
          * [`obj spec.podSets.template.spec.securityContext.sysctls`](#obj-specpodsetstemplatespecsecuritycontextsysctls)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecsecuritycontextsysctlswithname)
            * [`fn withValue(value)`](#fn-specpodsetstemplatespecsecuritycontextsysctlswithvalue)
          * [`obj spec.podSets.template.spec.securityContext.windowsOptions`](#obj-specpodsetstemplatespecsecuritycontextwindowsoptions)
            * [`fn withGmsaCredentialSpec(gmsaCredentialSpec)`](#fn-specpodsetstemplatespecsecuritycontextwindowsoptionswithgmsacredentialspec)
            * [`fn withGmsaCredentialSpecName(gmsaCredentialSpecName)`](#fn-specpodsetstemplatespecsecuritycontextwindowsoptionswithgmsacredentialspecname)
            * [`fn withHostProcess(hostProcess)`](#fn-specpodsetstemplatespecsecuritycontextwindowsoptionswithhostprocess)
            * [`fn withRunAsUserName(runAsUserName)`](#fn-specpodsetstemplatespecsecuritycontextwindowsoptionswithrunasusername)
        * [`obj spec.podSets.template.spec.tolerations`](#obj-specpodsetstemplatespectolerations)
          * [`fn withEffect(effect)`](#fn-specpodsetstemplatespectolerationswitheffect)
          * [`fn withKey(key)`](#fn-specpodsetstemplatespectolerationswithkey)
          * [`fn withOperator(operator)`](#fn-specpodsetstemplatespectolerationswithoperator)
          * [`fn withTolerationSeconds(tolerationSeconds)`](#fn-specpodsetstemplatespectolerationswithtolerationseconds)
          * [`fn withValue(value)`](#fn-specpodsetstemplatespectolerationswithvalue)
        * [`obj spec.podSets.template.spec.topologySpreadConstraints`](#obj-specpodsetstemplatespectopologyspreadconstraints)
          * [`fn withMatchLabelKeys(matchLabelKeys)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithmatchlabelkeys)
          * [`fn withMatchLabelKeysMixin(matchLabelKeys)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithmatchlabelkeysmixin)
          * [`fn withMaxSkew(maxSkew)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithmaxskew)
          * [`fn withMinDomains(minDomains)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithmindomains)
          * [`fn withNodeAffinityPolicy(nodeAffinityPolicy)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithnodeaffinitypolicy)
          * [`fn withNodeTaintsPolicy(nodeTaintsPolicy)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithnodetaintspolicy)
          * [`fn withTopologyKey(topologyKey)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithtopologykey)
          * [`fn withWhenUnsatisfiable(whenUnsatisfiable)`](#fn-specpodsetstemplatespectopologyspreadconstraintswithwhenunsatisfiable)
          * [`obj spec.podSets.template.spec.topologySpreadConstraints.labelSelector`](#obj-specpodsetstemplatespectopologyspreadconstraintslabelselector)
            * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectorwithmatchexpressions)
            * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectorwithmatchexpressionsmixin)
            * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectorwithmatchlabels)
            * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectorwithmatchlabelsmixin)
            * [`obj spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions`](#obj-specpodsetstemplatespectopologyspreadconstraintslabelselectormatchexpressions)
              * [`fn withKey(key)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectormatchexpressionswithkey)
              * [`fn withOperator(operator)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectormatchexpressionswithoperator)
              * [`fn withValues(values)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvalues)
              * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespectopologyspreadconstraintslabelselectormatchexpressionswithvaluesmixin)
        * [`obj spec.podSets.template.spec.volumes`](#obj-specpodsetstemplatespecvolumes)
          * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumeswithname)
          * [`obj spec.podSets.template.spec.volumes.awsElasticBlockStore`](#obj-specpodsetstemplatespecvolumesawselasticblockstore)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesawselasticblockstorewithfstype)
            * [`fn withPartition(partition)`](#fn-specpodsetstemplatespecvolumesawselasticblockstorewithpartition)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesawselasticblockstorewithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specpodsetstemplatespecvolumesawselasticblockstorewithvolumeid)
          * [`obj spec.podSets.template.spec.volumes.azureDisk`](#obj-specpodsetstemplatespecvolumesazuredisk)
            * [`fn withCachingMode(cachingMode)`](#fn-specpodsetstemplatespecvolumesazurediskwithcachingmode)
            * [`fn withDiskName(diskName)`](#fn-specpodsetstemplatespecvolumesazurediskwithdiskname)
            * [`fn withDiskURI(diskURI)`](#fn-specpodsetstemplatespecvolumesazurediskwithdiskuri)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesazurediskwithfstype)
            * [`fn withKind(kind)`](#fn-specpodsetstemplatespecvolumesazurediskwithkind)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesazurediskwithreadonly)
          * [`obj spec.podSets.template.spec.volumes.azureFile`](#obj-specpodsetstemplatespecvolumesazurefile)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesazurefilewithreadonly)
            * [`fn withSecretName(secretName)`](#fn-specpodsetstemplatespecvolumesazurefilewithsecretname)
            * [`fn withShareName(shareName)`](#fn-specpodsetstemplatespecvolumesazurefilewithsharename)
          * [`obj spec.podSets.template.spec.volumes.cephfs`](#obj-specpodsetstemplatespecvolumescephfs)
            * [`fn withMonitors(monitors)`](#fn-specpodsetstemplatespecvolumescephfswithmonitors)
            * [`fn withMonitorsMixin(monitors)`](#fn-specpodsetstemplatespecvolumescephfswithmonitorsmixin)
            * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumescephfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumescephfswithreadonly)
            * [`fn withSecretFile(secretFile)`](#fn-specpodsetstemplatespecvolumescephfswithsecretfile)
            * [`fn withUser(user)`](#fn-specpodsetstemplatespecvolumescephfswithuser)
            * [`obj spec.podSets.template.spec.volumes.cephfs.secretRef`](#obj-specpodsetstemplatespecvolumescephfssecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumescephfssecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.cinder`](#obj-specpodsetstemplatespecvolumescinder)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumescinderwithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumescinderwithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specpodsetstemplatespecvolumescinderwithvolumeid)
            * [`obj spec.podSets.template.spec.volumes.cinder.secretRef`](#obj-specpodsetstemplatespecvolumescindersecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumescindersecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.configMap`](#obj-specpodsetstemplatespecvolumesconfigmap)
            * [`fn withDefaultMode(defaultMode)`](#fn-specpodsetstemplatespecvolumesconfigmapwithdefaultmode)
            * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumesconfigmapwithitems)
            * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumesconfigmapwithitemsmixin)
            * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesconfigmapwithname)
            * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecvolumesconfigmapwithoptional)
            * [`obj spec.podSets.template.spec.volumes.configMap.items`](#obj-specpodsetstemplatespecvolumesconfigmapitems)
              * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumesconfigmapitemswithkey)
              * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumesconfigmapitemswithmode)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesconfigmapitemswithpath)
          * [`obj spec.podSets.template.spec.volumes.csi`](#obj-specpodsetstemplatespecvolumescsi)
            * [`fn withDriver(driver)`](#fn-specpodsetstemplatespecvolumescsiwithdriver)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumescsiwithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumescsiwithreadonly)
            * [`fn withVolumeAttributes(volumeAttributes)`](#fn-specpodsetstemplatespecvolumescsiwithvolumeattributes)
            * [`fn withVolumeAttributesMixin(volumeAttributes)`](#fn-specpodsetstemplatespecvolumescsiwithvolumeattributesmixin)
            * [`obj spec.podSets.template.spec.volumes.csi.nodePublishSecretRef`](#obj-specpodsetstemplatespecvolumescsinodepublishsecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumescsinodepublishsecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.downwardAPI`](#obj-specpodsetstemplatespecvolumesdownwardapi)
            * [`fn withDefaultMode(defaultMode)`](#fn-specpodsetstemplatespecvolumesdownwardapiwithdefaultmode)
            * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumesdownwardapiwithitems)
            * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumesdownwardapiwithitemsmixin)
            * [`obj spec.podSets.template.spec.volumes.downwardAPI.items`](#obj-specpodsetstemplatespecvolumesdownwardapiitems)
              * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemswithmode)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemswithpath)
              * [`obj spec.podSets.template.spec.volumes.downwardAPI.items.fieldRef`](#obj-specpodsetstemplatespecvolumesdownwardapiitemsfieldref)
                * [`fn withApiVersion(apiVersion)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemsfieldrefwithapiversion)
                * [`fn withFieldPath(fieldPath)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemsfieldrefwithfieldpath)
              * [`obj spec.podSets.template.spec.volumes.downwardAPI.items.resourceFieldRef`](#obj-specpodsetstemplatespecvolumesdownwardapiitemsresourcefieldref)
                * [`fn withContainerName(containerName)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemsresourcefieldrefwithcontainername)
                * [`fn withDivisor(divisor)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemsresourcefieldrefwithdivisor)
                * [`fn withResource(resource)`](#fn-specpodsetstemplatespecvolumesdownwardapiitemsresourcefieldrefwithresource)
          * [`obj spec.podSets.template.spec.volumes.emptyDir`](#obj-specpodsetstemplatespecvolumesemptydir)
            * [`fn withMedium(medium)`](#fn-specpodsetstemplatespecvolumesemptydirwithmedium)
            * [`fn withSizeLimit(sizeLimit)`](#fn-specpodsetstemplatespecvolumesemptydirwithsizelimit)
          * [`obj spec.podSets.template.spec.volumes.ephemeral`](#obj-specpodsetstemplatespecvolumesephemeral)
            * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplate)
              * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadata)
                * [`fn withAnnotations(annotations)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithannotations)
                * [`fn withAnnotationsMixin(annotations)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithannotationsmixin)
                * [`fn withFinalizers(finalizers)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithfinalizers)
                * [`fn withFinalizersMixin(finalizers)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithfinalizersmixin)
                * [`fn withLabels(labels)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithlabels)
                * [`fn withLabelsMixin(labels)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithlabelsmixin)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithname)
                * [`fn withNamespace(namespace)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatemetadatawithnamespace)
              * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespec)
                * [`fn withAccessModes(accessModes)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodes)
                * [`fn withAccessModesMixin(accessModes)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithaccessmodesmixin)
                * [`fn withStorageClassName(storageClassName)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithstorageclassname)
                * [`fn withVolumeAttributesClassName(volumeAttributesClassName)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumeattributesclassname)
                * [`fn withVolumeMode(volumeMode)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumemode)
                * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecwithvolumename)
                * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasource)
                  * [`fn withApiGroup(apiGroup)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithapigroup)
                  * [`fn withKind(kind)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithkind)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcewithname)
                * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourceref)
                  * [`fn withApiGroup(apiGroup)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithapigroup)
                  * [`fn withKind(kind)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithkind)
                  * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithname)
                  * [`fn withNamespace(namespace)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecdatasourcerefwithnamespace)
                * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecresources)
                  * [`fn withLimits(limits)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimits)
                  * [`fn withLimitsMixin(limits)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithlimitsmixin)
                  * [`fn withRequests(requests)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequests)
                  * [`fn withRequestsMixin(requests)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecresourceswithrequestsmixin)
                * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions`](#obj-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecvolumesephemeralvolumeclaimtemplatespecselectormatchexpressionswithvaluesmixin)
          * [`obj spec.podSets.template.spec.volumes.fc`](#obj-specpodsetstemplatespecvolumesfc)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesfcwithfstype)
            * [`fn withLun(lun)`](#fn-specpodsetstemplatespecvolumesfcwithlun)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesfcwithreadonly)
            * [`fn withTargetWWNs(targetWWNs)`](#fn-specpodsetstemplatespecvolumesfcwithtargetwwns)
            * [`fn withTargetWWNsMixin(targetWWNs)`](#fn-specpodsetstemplatespecvolumesfcwithtargetwwnsmixin)
            * [`fn withWwids(wwids)`](#fn-specpodsetstemplatespecvolumesfcwithwwids)
            * [`fn withWwidsMixin(wwids)`](#fn-specpodsetstemplatespecvolumesfcwithwwidsmixin)
          * [`obj spec.podSets.template.spec.volumes.flexVolume`](#obj-specpodsetstemplatespecvolumesflexvolume)
            * [`fn withDriver(driver)`](#fn-specpodsetstemplatespecvolumesflexvolumewithdriver)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesflexvolumewithfstype)
            * [`fn withOptions(options)`](#fn-specpodsetstemplatespecvolumesflexvolumewithoptions)
            * [`fn withOptionsMixin(options)`](#fn-specpodsetstemplatespecvolumesflexvolumewithoptionsmixin)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesflexvolumewithreadonly)
            * [`obj spec.podSets.template.spec.volumes.flexVolume.secretRef`](#obj-specpodsetstemplatespecvolumesflexvolumesecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesflexvolumesecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.flocker`](#obj-specpodsetstemplatespecvolumesflocker)
            * [`fn withDatasetName(datasetName)`](#fn-specpodsetstemplatespecvolumesflockerwithdatasetname)
            * [`fn withDatasetUUID(datasetUUID)`](#fn-specpodsetstemplatespecvolumesflockerwithdatasetuuid)
          * [`obj spec.podSets.template.spec.volumes.gcePersistentDisk`](#obj-specpodsetstemplatespecvolumesgcepersistentdisk)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesgcepersistentdiskwithfstype)
            * [`fn withPartition(partition)`](#fn-specpodsetstemplatespecvolumesgcepersistentdiskwithpartition)
            * [`fn withPdName(pdName)`](#fn-specpodsetstemplatespecvolumesgcepersistentdiskwithpdname)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesgcepersistentdiskwithreadonly)
          * [`obj spec.podSets.template.spec.volumes.gitRepo`](#obj-specpodsetstemplatespecvolumesgitrepo)
            * [`fn withDirectory(directory)`](#fn-specpodsetstemplatespecvolumesgitrepowithdirectory)
            * [`fn withRepository(repository)`](#fn-specpodsetstemplatespecvolumesgitrepowithrepository)
            * [`fn withRevision(revision)`](#fn-specpodsetstemplatespecvolumesgitrepowithrevision)
          * [`obj spec.podSets.template.spec.volumes.glusterfs`](#obj-specpodsetstemplatespecvolumesglusterfs)
            * [`fn withEndpoints(endpoints)`](#fn-specpodsetstemplatespecvolumesglusterfswithendpoints)
            * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesglusterfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesglusterfswithreadonly)
          * [`obj spec.podSets.template.spec.volumes.hostPath`](#obj-specpodsetstemplatespecvolumeshostpath)
            * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumeshostpathwithpath)
            * [`fn withType(type)`](#fn-specpodsetstemplatespecvolumeshostpathwithtype)
          * [`obj spec.podSets.template.spec.volumes.image`](#obj-specpodsetstemplatespecvolumesimage)
            * [`fn withPullPolicy(pullPolicy)`](#fn-specpodsetstemplatespecvolumesimagewithpullpolicy)
            * [`fn withReference(reference)`](#fn-specpodsetstemplatespecvolumesimagewithreference)
          * [`obj spec.podSets.template.spec.volumes.iscsi`](#obj-specpodsetstemplatespecvolumesiscsi)
            * [`fn withChapAuthDiscovery(chapAuthDiscovery)`](#fn-specpodsetstemplatespecvolumesiscsiwithchapauthdiscovery)
            * [`fn withChapAuthSession(chapAuthSession)`](#fn-specpodsetstemplatespecvolumesiscsiwithchapauthsession)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesiscsiwithfstype)
            * [`fn withInitiatorName(initiatorName)`](#fn-specpodsetstemplatespecvolumesiscsiwithinitiatorname)
            * [`fn withIqn(iqn)`](#fn-specpodsetstemplatespecvolumesiscsiwithiqn)
            * [`fn withIscsiInterface(iscsiInterface)`](#fn-specpodsetstemplatespecvolumesiscsiwithiscsiinterface)
            * [`fn withLun(lun)`](#fn-specpodsetstemplatespecvolumesiscsiwithlun)
            * [`fn withPortals(portals)`](#fn-specpodsetstemplatespecvolumesiscsiwithportals)
            * [`fn withPortalsMixin(portals)`](#fn-specpodsetstemplatespecvolumesiscsiwithportalsmixin)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesiscsiwithreadonly)
            * [`fn withTargetPortal(targetPortal)`](#fn-specpodsetstemplatespecvolumesiscsiwithtargetportal)
            * [`obj spec.podSets.template.spec.volumes.iscsi.secretRef`](#obj-specpodsetstemplatespecvolumesiscsisecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesiscsisecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.nfs`](#obj-specpodsetstemplatespecvolumesnfs)
            * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesnfswithpath)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesnfswithreadonly)
            * [`fn withServer(server)`](#fn-specpodsetstemplatespecvolumesnfswithserver)
          * [`obj spec.podSets.template.spec.volumes.persistentVolumeClaim`](#obj-specpodsetstemplatespecvolumespersistentvolumeclaim)
            * [`fn withClaimName(claimName)`](#fn-specpodsetstemplatespecvolumespersistentvolumeclaimwithclaimname)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumespersistentvolumeclaimwithreadonly)
          * [`obj spec.podSets.template.spec.volumes.photonPersistentDisk`](#obj-specpodsetstemplatespecvolumesphotonpersistentdisk)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesphotonpersistentdiskwithfstype)
            * [`fn withPdID(pdID)`](#fn-specpodsetstemplatespecvolumesphotonpersistentdiskwithpdid)
          * [`obj spec.podSets.template.spec.volumes.portworxVolume`](#obj-specpodsetstemplatespecvolumesportworxvolume)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesportworxvolumewithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesportworxvolumewithreadonly)
            * [`fn withVolumeID(volumeID)`](#fn-specpodsetstemplatespecvolumesportworxvolumewithvolumeid)
          * [`obj spec.podSets.template.spec.volumes.projected`](#obj-specpodsetstemplatespecvolumesprojected)
            * [`fn withDefaultMode(defaultMode)`](#fn-specpodsetstemplatespecvolumesprojectedwithdefaultmode)
            * [`fn withSources(sources)`](#fn-specpodsetstemplatespecvolumesprojectedwithsources)
            * [`fn withSourcesMixin(sources)`](#fn-specpodsetstemplatespecvolumesprojectedwithsourcesmixin)
            * [`obj spec.podSets.template.spec.volumes.projected.sources`](#obj-specpodsetstemplatespecvolumesprojectedsources)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle`](#obj-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundle)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlewithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlewithoptional)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlewithpath)
                * [`fn withSignerName(signerName)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlewithsignername)
                * [`obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector`](#obj-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselector)
                  * [`fn withMatchExpressions(matchExpressions)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressions)
                  * [`fn withMatchExpressionsMixin(matchExpressions)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchexpressionsmixin)
                  * [`fn withMatchLabels(matchLabels)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabels)
                  * [`fn withMatchLabelsMixin(matchLabels)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectorwithmatchlabelsmixin)
                  * [`obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions`](#obj-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressions)
                    * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithkey)
                    * [`fn withOperator(operator)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithoperator)
                    * [`fn withValues(values)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvalues)
                    * [`fn withValuesMixin(values)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesclustertrustbundlelabelselectormatchexpressionswithvaluesmixin)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.configMap`](#obj-specpodsetstemplatespecvolumesprojectedsourcesconfigmap)
                * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapwithitems)
                * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapwithitemsmixin)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapwithoptional)
                * [`obj spec.podSets.template.spec.volumes.projected.sources.configMap.items`](#obj-specpodsetstemplatespecvolumesprojectedsourcesconfigmapitems)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapitemswithkey)
                  * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapitemswithmode)
                  * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesconfigmapitemswithpath)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI`](#obj-specpodsetstemplatespecvolumesprojectedsourcesdownwardapi)
                * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiwithitems)
                * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiwithitemsmixin)
                * [`obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items`](#obj-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitems)
                  * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemswithmode)
                  * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemswithpath)
                  * [`obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef`](#obj-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsfieldref)
                    * [`fn withApiVersion(apiVersion)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithapiversion)
                    * [`fn withFieldPath(fieldPath)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsfieldrefwithfieldpath)
                  * [`obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef`](#obj-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldref)
                    * [`fn withContainerName(containerName)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithcontainername)
                    * [`fn withDivisor(divisor)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithdivisor)
                    * [`fn withResource(resource)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesdownwardapiitemsresourcefieldrefwithresource)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.podCertificate`](#obj-specpodsetstemplatespecvolumesprojectedsourcespodcertificate)
                * [`fn withCertificateChainPath(certificateChainPath)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithcertificatechainpath)
                * [`fn withCredentialBundlePath(credentialBundlePath)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithcredentialbundlepath)
                * [`fn withKeyPath(keyPath)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithkeypath)
                * [`fn withKeyType(keyType)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithkeytype)
                * [`fn withMaxExpirationSeconds(maxExpirationSeconds)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithmaxexpirationseconds)
                * [`fn withSignerName(signerName)`](#fn-specpodsetstemplatespecvolumesprojectedsourcespodcertificatewithsignername)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.secret`](#obj-specpodsetstemplatespecvolumesprojectedsourcessecret)
                * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretwithitems)
                * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretwithitemsmixin)
                * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretwithname)
                * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretwithoptional)
                * [`obj spec.podSets.template.spec.volumes.projected.sources.secret.items`](#obj-specpodsetstemplatespecvolumesprojectedsourcessecretitems)
                  * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretitemswithkey)
                  * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretitemswithmode)
                  * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesprojectedsourcessecretitemswithpath)
              * [`obj spec.podSets.template.spec.volumes.projected.sources.serviceAccountToken`](#obj-specpodsetstemplatespecvolumesprojectedsourcesserviceaccounttoken)
                * [`fn withAudience(audience)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesserviceaccounttokenwithaudience)
                * [`fn withExpirationSeconds(expirationSeconds)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesserviceaccounttokenwithexpirationseconds)
                * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumesprojectedsourcesserviceaccounttokenwithpath)
          * [`obj spec.podSets.template.spec.volumes.quobyte`](#obj-specpodsetstemplatespecvolumesquobyte)
            * [`fn withGroup(group)`](#fn-specpodsetstemplatespecvolumesquobytewithgroup)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesquobytewithreadonly)
            * [`fn withRegistry(registry)`](#fn-specpodsetstemplatespecvolumesquobytewithregistry)
            * [`fn withTenant(tenant)`](#fn-specpodsetstemplatespecvolumesquobytewithtenant)
            * [`fn withUser(user)`](#fn-specpodsetstemplatespecvolumesquobytewithuser)
            * [`fn withVolume(volume)`](#fn-specpodsetstemplatespecvolumesquobytewithvolume)
          * [`obj spec.podSets.template.spec.volumes.rbd`](#obj-specpodsetstemplatespecvolumesrbd)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesrbdwithfstype)
            * [`fn withImage(image)`](#fn-specpodsetstemplatespecvolumesrbdwithimage)
            * [`fn withKeyring(keyring)`](#fn-specpodsetstemplatespecvolumesrbdwithkeyring)
            * [`fn withMonitors(monitors)`](#fn-specpodsetstemplatespecvolumesrbdwithmonitors)
            * [`fn withMonitorsMixin(monitors)`](#fn-specpodsetstemplatespecvolumesrbdwithmonitorsmixin)
            * [`fn withPool(pool)`](#fn-specpodsetstemplatespecvolumesrbdwithpool)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesrbdwithreadonly)
            * [`fn withUser(user)`](#fn-specpodsetstemplatespecvolumesrbdwithuser)
            * [`obj spec.podSets.template.spec.volumes.rbd.secretRef`](#obj-specpodsetstemplatespecvolumesrbdsecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesrbdsecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.scaleIO`](#obj-specpodsetstemplatespecvolumesscaleio)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesscaleiowithfstype)
            * [`fn withGateway(gateway)`](#fn-specpodsetstemplatespecvolumesscaleiowithgateway)
            * [`fn withProtectionDomain(protectionDomain)`](#fn-specpodsetstemplatespecvolumesscaleiowithprotectiondomain)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesscaleiowithreadonly)
            * [`fn withSslEnabled(sslEnabled)`](#fn-specpodsetstemplatespecvolumesscaleiowithsslenabled)
            * [`fn withStorageMode(storageMode)`](#fn-specpodsetstemplatespecvolumesscaleiowithstoragemode)
            * [`fn withStoragePool(storagePool)`](#fn-specpodsetstemplatespecvolumesscaleiowithstoragepool)
            * [`fn withSystem(system)`](#fn-specpodsetstemplatespecvolumesscaleiowithsystem)
            * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespecvolumesscaleiowithvolumename)
            * [`obj spec.podSets.template.spec.volumes.scaleIO.secretRef`](#obj-specpodsetstemplatespecvolumesscaleiosecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesscaleiosecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.secret`](#obj-specpodsetstemplatespecvolumessecret)
            * [`fn withDefaultMode(defaultMode)`](#fn-specpodsetstemplatespecvolumessecretwithdefaultmode)
            * [`fn withItems(items)`](#fn-specpodsetstemplatespecvolumessecretwithitems)
            * [`fn withItemsMixin(items)`](#fn-specpodsetstemplatespecvolumessecretwithitemsmixin)
            * [`fn withOptional(optional)`](#fn-specpodsetstemplatespecvolumessecretwithoptional)
            * [`fn withSecretName(secretName)`](#fn-specpodsetstemplatespecvolumessecretwithsecretname)
            * [`obj spec.podSets.template.spec.volumes.secret.items`](#obj-specpodsetstemplatespecvolumessecretitems)
              * [`fn withKey(key)`](#fn-specpodsetstemplatespecvolumessecretitemswithkey)
              * [`fn withMode(mode)`](#fn-specpodsetstemplatespecvolumessecretitemswithmode)
              * [`fn withPath(path)`](#fn-specpodsetstemplatespecvolumessecretitemswithpath)
          * [`obj spec.podSets.template.spec.volumes.storageos`](#obj-specpodsetstemplatespecvolumesstorageos)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesstorageoswithfstype)
            * [`fn withReadOnly(readOnly)`](#fn-specpodsetstemplatespecvolumesstorageoswithreadonly)
            * [`fn withVolumeName(volumeName)`](#fn-specpodsetstemplatespecvolumesstorageoswithvolumename)
            * [`fn withVolumeNamespace(volumeNamespace)`](#fn-specpodsetstemplatespecvolumesstorageoswithvolumenamespace)
            * [`obj spec.podSets.template.spec.volumes.storageos.secretRef`](#obj-specpodsetstemplatespecvolumesstorageossecretref)
              * [`fn withName(name)`](#fn-specpodsetstemplatespecvolumesstorageossecretrefwithname)
          * [`obj spec.podSets.template.spec.volumes.vsphereVolume`](#obj-specpodsetstemplatespecvolumesvspherevolume)
            * [`fn withFsType(fsType)`](#fn-specpodsetstemplatespecvolumesvspherevolumewithfstype)
            * [`fn withStoragePolicyID(storagePolicyID)`](#fn-specpodsetstemplatespecvolumesvspherevolumewithstoragepolicyid)
            * [`fn withStoragePolicyName(storagePolicyName)`](#fn-specpodsetstemplatespecvolumesvspherevolumewithstoragepolicyname)
            * [`fn withVolumePath(volumePath)`](#fn-specpodsetstemplatespecvolumesvspherevolumewithvolumepath)
    * [`obj spec.podSets.topologyRequest`](#obj-specpodsetstopologyrequest)
      * [`fn withPodIndexLabel(podIndexLabel)`](#fn-specpodsetstopologyrequestwithpodindexlabel)
      * [`fn withPodSetGroupName(podSetGroupName)`](#fn-specpodsetstopologyrequestwithpodsetgroupname)
      * [`fn withPodSetSliceRequiredTopology(podSetSliceRequiredTopology)`](#fn-specpodsetstopologyrequestwithpodsetslicerequiredtopology)
      * [`fn withPodSetSliceSize(podSetSliceSize)`](#fn-specpodsetstopologyrequestwithpodsetslicesize)
      * [`fn withPreferred(preferred)`](#fn-specpodsetstopologyrequestwithpreferred)
      * [`fn withRequired(required)`](#fn-specpodsetstopologyrequestwithrequired)
      * [`fn withSubGroupCount(subGroupCount)`](#fn-specpodsetstopologyrequestwithsubgroupcount)
      * [`fn withSubGroupIndexLabel(subGroupIndexLabel)`](#fn-specpodsetstopologyrequestwithsubgroupindexlabel)
      * [`fn withUnconstrained(unconstrained)`](#fn-specpodsetstopologyrequestwithunconstrained)
  * [`obj spec.priorityClassRef`](#obj-specpriorityclassref)
    * [`fn withGroup(group)`](#fn-specpriorityclassrefwithgroup)
    * [`fn withKind(kind)`](#fn-specpriorityclassrefwithkind)
    * [`fn withName(name)`](#fn-specpriorityclassrefwithname)

## Fields

### fn new

```ts
new(name)
```

new returns an instance of Workload

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

"spec is the specification of the Workload."

### fn spec.withActive

```ts
withActive(active)
```

"active determines if a workload can be admitted into a queue.\nChanging active from true to false will evict any running workloads.\nPossible values are:\n\n  - false: indicates that a workload should never be admitted and evicts running workloads\n  - true: indicates that a workload can be evaluated for admission into it's respective queue.\n\nDefaults to true"

### fn spec.withMaximumExecutionTimeSeconds

```ts
withMaximumExecutionTimeSeconds(maximumExecutionTimeSeconds)
```

"maximumExecutionTimeSeconds if provided, determines the maximum time, in seconds,\nthe workload can be admitted before it's automatically deactivated.\n\nIf unspecified, no execution time limit is enforced on the Workload."

### fn spec.withPodSets

```ts
withPodSets(podSets)
```

"podSets is a list of sets of homogeneous pods, each described by a Pod spec\nand a count.\nThere must be at least one element and at most 8.\npodSets cannot be changed."

### fn spec.withPodSetsMixin

```ts
withPodSetsMixin(podSets)
```

"podSets is a list of sets of homogeneous pods, each described by a Pod spec\nand a count.\nThere must be at least one element and at most 8.\npodSets cannot be changed."

**Note:** This function appends passed data to existing values

### fn spec.withPriority

```ts
withPriority(priority)
```

"priority determines the order of access to the resources managed by the\nClusterQueue where the workload is queued.\nThe priority value is populated from the referenced PriorityClass (via priorityClassRef).\nThe higher the value, the higher the priority.\nIf priorityClassRef is specified, priority must not be null."

### fn spec.withQueueName

```ts
withQueueName(queueName)
```

"queueName is the name of the LocalQueue the Workload is associated with.\nqueueName cannot be changed while .status.admission is not null."

## obj spec.podSets

"podSets is a list of sets of homogeneous pods, each described by a Pod spec\nand a count.\nThere must be at least one element and at most 8.\npodSets cannot be changed."

### fn spec.podSets.withCount

```ts
withCount(count)
```

"count is the number of pods for the spec."

### fn spec.podSets.withMinCount

```ts
withMinCount(minCount)
```

"minCount is the minimum number of pods for the spec acceptable\nif the workload supports partial admission.\n\nIf not provided, partial admission for the current PodSet is not\nenabled.\n\nOnly one podSet within the workload can use this.\n\nThis is an alpha field and requires enabling PartialAdmission feature gate."

### fn spec.podSets.withName

```ts
withName(name)
```

"name is the PodSet name."

## obj spec.podSets.template

"template is the Pod template.\n\nThe only allowed fields in template.metadata are labels and annotations.\n\nIf requests are omitted for a container or initContainer,\nthey default to the limits if they are explicitly specified for the\ncontainer or initContainer.\n\nDuring admission, the rules in nodeSelector and\nnodeAffinity.requiredDuringSchedulingIgnoredDuringExecution that match\nthe keys in the nodeLabels from the ResourceFlavors considered for this\nWorkload are used to filter the ResourceFlavors that can be assigned to\nthis podSet."

## obj spec.podSets.template.metadata

"Standard object's metadata.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#metadata"

### fn spec.podSets.template.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.podSets.template.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.podSets.template.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.podSets.template.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.metadata.withName

```ts
withName(name)
```



### fn spec.podSets.template.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.podSets.template.spec

"Specification of the desired behavior of the pod.\nMore info: https://git.k8s.io/community/contributors/devel/sig-architecture/api-conventions.md#spec-and-status"

### fn spec.podSets.template.spec.withActiveDeadlineSeconds

```ts
withActiveDeadlineSeconds(activeDeadlineSeconds)
```

"Optional duration in seconds the pod may be active on the node relative to\nStartTime before the system will actively try to mark it failed and kill associated containers.\nValue must be a positive integer."

### fn spec.podSets.template.spec.withAutomountServiceAccountToken

```ts
withAutomountServiceAccountToken(automountServiceAccountToken)
```

"AutomountServiceAccountToken indicates whether a service account token should be automatically mounted."

### fn spec.podSets.template.spec.withContainers

```ts
withContainers(containers)
```

"List of containers belonging to the pod.\nContainers cannot currently be added or removed.\nThere must be at least one container in a Pod.\nCannot be updated."

### fn spec.podSets.template.spec.withContainersMixin

```ts
withContainersMixin(containers)
```

"List of containers belonging to the pod.\nContainers cannot currently be added or removed.\nThere must be at least one container in a Pod.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withDnsPolicy

```ts
withDnsPolicy(dnsPolicy)
```

"Set DNS policy for the pod.\nDefaults to \"ClusterFirst\".\nValid values are 'ClusterFirstWithHostNet', 'ClusterFirst', 'Default' or 'None'.\nDNS parameters given in DNSConfig will be merged with the policy selected with DNSPolicy.\nTo have DNS options set along with hostNetwork, you have to specify DNS policy\nexplicitly to 'ClusterFirstWithHostNet'."

### fn spec.podSets.template.spec.withEnableServiceLinks

```ts
withEnableServiceLinks(enableServiceLinks)
```

"EnableServiceLinks indicates whether information about services should be injected into pod's\nenvironment variables, matching the syntax of Docker links.\nOptional: Defaults to true."

### fn spec.podSets.template.spec.withEphemeralContainers

```ts
withEphemeralContainers(ephemeralContainers)
```

"List of ephemeral containers run in this pod. Ephemeral containers may be run in an existing\npod to perform user-initiated actions such as debugging. This list cannot be specified when\ncreating a pod, and it cannot be modified by updating the pod spec. In order to add an\nephemeral container to an existing pod, use the pod's ephemeralcontainers subresource."

### fn spec.podSets.template.spec.withEphemeralContainersMixin

```ts
withEphemeralContainersMixin(ephemeralContainers)
```

"List of ephemeral containers run in this pod. Ephemeral containers may be run in an existing\npod to perform user-initiated actions such as debugging. This list cannot be specified when\ncreating a pod, and it cannot be modified by updating the pod spec. In order to add an\nephemeral container to an existing pod, use the pod's ephemeralcontainers subresource."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withHostAliases

```ts
withHostAliases(hostAliases)
```

"HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts\nfile if specified."

### fn spec.podSets.template.spec.withHostAliasesMixin

```ts
withHostAliasesMixin(hostAliases)
```

"HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts\nfile if specified."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withHostIPC

```ts
withHostIPC(hostIPC)
```

"Use the host's ipc namespace.\nOptional: Default to false."

### fn spec.podSets.template.spec.withHostNetwork

```ts
withHostNetwork(hostNetwork)
```

"Host networking requested for this pod. Use the host's network namespace.\nWhen using HostNetwork you should specify ports so the scheduler is aware.\nWhen `hostNetwork` is true, specified `hostPort` fields in port definitions must match `containerPort`,\nand unspecified `hostPort` fields in port definitions are defaulted to match `containerPort`.\nDefault to false."

### fn spec.podSets.template.spec.withHostPID

```ts
withHostPID(hostPID)
```

"Use the host's pid namespace.\nOptional: Default to false."

### fn spec.podSets.template.spec.withHostUsers

```ts
withHostUsers(hostUsers)
```

"Use the host's user namespace.\nOptional: Default to true.\nIf set to true or not present, the pod will be run in the host user namespace, useful\nfor when the pod needs a feature only available to the host user namespace, such as\nloading a kernel module with CAP_SYS_MODULE.\nWhen set to false, a new userns is created for the pod. Setting false is useful for\nmitigating container breakout vulnerabilities even allowing users to run their\ncontainers as root without actually having root privileges on the host.\nThis field is alpha-level and is only honored by servers that enable the UserNamespacesSupport feature."

### fn spec.podSets.template.spec.withHostname

```ts
withHostname(hostname)
```

"Specifies the hostname of the Pod\nIf not specified, the pod's hostname will be set to a system-defined value."

### fn spec.podSets.template.spec.withHostnameOverride

```ts
withHostnameOverride(hostnameOverride)
```

"HostnameOverride specifies an explicit override for the pod's hostname as perceived by the pod.\nThis field only specifies the pod's hostname and does not affect its DNS records.\nWhen this field is set to a non-empty string:\n- It takes precedence over the values set in `hostname` and `subdomain`.\n- The Pod's hostname will be set to this value.\n- `setHostnameAsFQDN` must be nil or set to false.\n- `hostNetwork` must be set to false.\n\nThis field must be a valid DNS subdomain as defined in RFC 1123 and contain at most 64 characters.\nRequires the HostnameOverride feature gate to be enabled."

### fn spec.podSets.template.spec.withImagePullSecrets

```ts
withImagePullSecrets(imagePullSecrets)
```

"ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec.\nIf specified, these secrets will be passed to individual puller implementations for them to use.\nMore info: https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod"

### fn spec.podSets.template.spec.withImagePullSecretsMixin

```ts
withImagePullSecretsMixin(imagePullSecrets)
```

"ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec.\nIf specified, these secrets will be passed to individual puller implementations for them to use.\nMore info: https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withInitContainers

```ts
withInitContainers(initContainers)
```

"List of initialization containers belonging to the pod.\nInit containers are executed in order prior to containers being started. If any\ninit container fails, the pod is considered to have failed and is handled according\nto its restartPolicy. The name for an init container or normal container must be\nunique among all containers.\nInit containers may not have Lifecycle actions, Readiness probes, Liveness probes, or Startup probes.\nThe resourceRequirements of an init container are taken into account during scheduling\nby finding the highest request/limit for each resource type, and then using the max of\nthat value or the sum of the normal containers. Limits are applied to init containers\nin a similar fashion.\nInit containers cannot currently be added or removed.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/init-containers/"

### fn spec.podSets.template.spec.withInitContainersMixin

```ts
withInitContainersMixin(initContainers)
```

"List of initialization containers belonging to the pod.\nInit containers are executed in order prior to containers being started. If any\ninit container fails, the pod is considered to have failed and is handled according\nto its restartPolicy. The name for an init container or normal container must be\nunique among all containers.\nInit containers may not have Lifecycle actions, Readiness probes, Liveness probes, or Startup probes.\nThe resourceRequirements of an init container are taken into account during scheduling\nby finding the highest request/limit for each resource type, and then using the max of\nthat value or the sum of the normal containers. Limits are applied to init containers\nin a similar fashion.\nInit containers cannot currently be added or removed.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/init-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withNodeName

```ts
withNodeName(nodeName)
```

"NodeName indicates in which node this pod is scheduled.\nIf empty, this pod is a candidate for scheduling by the scheduler defined in schedulerName.\nOnce this field is set, the kubelet for this node becomes responsible for the lifecycle of this pod.\nThis field should not be used to express a desire for the pod to be scheduled on a specific node.\nhttps://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#nodename"

### fn spec.podSets.template.spec.withNodeSelector

```ts
withNodeSelector(nodeSelector)
```

"NodeSelector is a selector which must be true for the pod to fit on a node.\nSelector which must match a node's labels for the pod to be scheduled on that node.\nMore info: https://kubernetes.io/docs/concepts/configuration/assign-pod-node/"

### fn spec.podSets.template.spec.withNodeSelectorMixin

```ts
withNodeSelectorMixin(nodeSelector)
```

"NodeSelector is a selector which must be true for the pod to fit on a node.\nSelector which must match a node's labels for the pod to be scheduled on that node.\nMore info: https://kubernetes.io/docs/concepts/configuration/assign-pod-node/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withOverhead

```ts
withOverhead(overhead)
```

"Overhead represents the resource overhead associated with running a pod for a given RuntimeClass.\nThis field will be autopopulated at admission time by the RuntimeClass admission controller. If\nthe RuntimeClass admission controller is enabled, overhead must not be set in Pod create requests.\nThe RuntimeClass admission controller will reject Pod create requests which have the overhead already\nset. If RuntimeClass is configured and selected in the PodSpec, Overhead will be set to the value\ndefined in the corresponding RuntimeClass, otherwise it will remain unset and treated as zero.\nMore info: https://git.k8s.io/enhancements/keps/sig-node/688-pod-overhead/README.md"

### fn spec.podSets.template.spec.withOverheadMixin

```ts
withOverheadMixin(overhead)
```

"Overhead represents the resource overhead associated with running a pod for a given RuntimeClass.\nThis field will be autopopulated at admission time by the RuntimeClass admission controller. If\nthe RuntimeClass admission controller is enabled, overhead must not be set in Pod create requests.\nThe RuntimeClass admission controller will reject Pod create requests which have the overhead already\nset. If RuntimeClass is configured and selected in the PodSpec, Overhead will be set to the value\ndefined in the corresponding RuntimeClass, otherwise it will remain unset and treated as zero.\nMore info: https://git.k8s.io/enhancements/keps/sig-node/688-pod-overhead/README.md"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withPreemptionPolicy

```ts
withPreemptionPolicy(preemptionPolicy)
```

"PreemptionPolicy is the Policy for preempting pods with lower priority.\nOne of Never, PreemptLowerPriority.\nDefaults to PreemptLowerPriority if unset."

### fn spec.podSets.template.spec.withPriority

```ts
withPriority(priority)
```

"The priority value. Various system components use this field to find the\npriority of the pod. When Priority Admission Controller is enabled, it\nprevents users from setting this field. The admission controller populates\nthis field from PriorityClassName.\nThe higher the value, the higher the priority."

### fn spec.podSets.template.spec.withPriorityClassName

```ts
withPriorityClassName(priorityClassName)
```

"If specified, indicates the pod's priority. \"system-node-critical\" and\n\"system-cluster-critical\" are two special keywords which indicate the\nhighest priorities with the former being the highest priority. Any other\nname must be defined by creating a PriorityClass object with that name.\nIf not specified, the pod priority will be default or zero if there is no\ndefault."

### fn spec.podSets.template.spec.withReadinessGates

```ts
withReadinessGates(readinessGates)
```

"If specified, all readiness gates will be evaluated for pod readiness.\nA pod is ready when all its containers are ready AND\nall conditions specified in the readiness gates have status equal to \"True\"\nMore info: https://git.k8s.io/enhancements/keps/sig-network/580-pod-readiness-gates"

### fn spec.podSets.template.spec.withReadinessGatesMixin

```ts
withReadinessGatesMixin(readinessGates)
```

"If specified, all readiness gates will be evaluated for pod readiness.\nA pod is ready when all its containers are ready AND\nall conditions specified in the readiness gates have status equal to \"True\"\nMore info: https://git.k8s.io/enhancements/keps/sig-network/580-pod-readiness-gates"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withResourceClaims

```ts
withResourceClaims(resourceClaims)
```

"ResourceClaims defines which ResourceClaims must be allocated\nand reserved before the Pod is allowed to start. The resources\nwill be made available to those containers which consume them\nby name.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable."

### fn spec.podSets.template.spec.withResourceClaimsMixin

```ts
withResourceClaimsMixin(resourceClaims)
```

"ResourceClaims defines which ResourceClaims must be allocated\nand reserved before the Pod is allowed to start. The resources\nwill be made available to those containers which consume them\nby name.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"Restart policy for all containers within the pod.\nOne of Always, OnFailure, Never. In some contexts, only a subset of those values may be permitted.\nDefault to Always.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/#restart-policy"

### fn spec.podSets.template.spec.withRuntimeClassName

```ts
withRuntimeClassName(runtimeClassName)
```

"RuntimeClassName refers to a RuntimeClass object in the node.k8s.io group, which should be used\nto run this pod.  If no RuntimeClass resource matches the named class, the pod will not be run.\nIf unset or empty, the \"legacy\" RuntimeClass will be used, which is an implicit class with an\nempty definition that uses the default runtime handler.\nMore info: https://git.k8s.io/enhancements/keps/sig-node/585-runtime-class"

### fn spec.podSets.template.spec.withSchedulerName

```ts
withSchedulerName(schedulerName)
```

"If specified, the pod will be dispatched by specified scheduler.\nIf not specified, the pod will be dispatched by default scheduler."

### fn spec.podSets.template.spec.withSchedulingGates

```ts
withSchedulingGates(schedulingGates)
```

"SchedulingGates is an opaque list of values that if specified will block scheduling the pod.\nIf schedulingGates is not empty, the pod will stay in the SchedulingGated state and the\nscheduler will not attempt to schedule the pod.\n\nSchedulingGates can only be set at pod creation time, and be removed only afterwards."

### fn spec.podSets.template.spec.withSchedulingGatesMixin

```ts
withSchedulingGatesMixin(schedulingGates)
```

"SchedulingGates is an opaque list of values that if specified will block scheduling the pod.\nIf schedulingGates is not empty, the pod will stay in the SchedulingGated state and the\nscheduler will not attempt to schedule the pod.\n\nSchedulingGates can only be set at pod creation time, and be removed only afterwards."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withServiceAccount

```ts
withServiceAccount(serviceAccount)
```

"DeprecatedServiceAccount is a deprecated alias for ServiceAccountName.\nDeprecated: Use serviceAccountName instead."

### fn spec.podSets.template.spec.withServiceAccountName

```ts
withServiceAccountName(serviceAccountName)
```

"ServiceAccountName is the name of the ServiceAccount to use to run this pod.\nMore info: https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/"

### fn spec.podSets.template.spec.withSetHostnameAsFQDN

```ts
withSetHostnameAsFQDN(setHostnameAsFQDN)
```

"If true the pod's hostname will be configured as the pod's FQDN, rather than the leaf name (the default).\nIn Linux containers, this means setting the FQDN in the hostname field of the kernel (the nodename field of struct utsname).\nIn Windows containers, this means setting the registry value of hostname for the registry key HKEY_LOCAL_MACHINE\\\\SYSTEM\\\\CurrentControlSet\\\\Services\\\\Tcpip\\\\Parameters to FQDN.\nIf a pod does not have FQDN, this has no effect.\nDefault to false."

### fn spec.podSets.template.spec.withShareProcessNamespace

```ts
withShareProcessNamespace(shareProcessNamespace)
```

"Share a single process namespace between all of the containers in a pod.\nWhen this is set containers will be able to view and signal processes from other containers\nin the same pod, and the first process in each container will not be assigned PID 1.\nHostPID and ShareProcessNamespace cannot both be set.\nOptional: Default to false."

### fn spec.podSets.template.spec.withSubdomain

```ts
withSubdomain(subdomain)
```

"If specified, the fully qualified Pod hostname will be \"<hostname>.<subdomain>.<pod namespace>.svc.<cluster domain>\".\nIf not specified, the pod will not have a domainname at all."

### fn spec.podSets.template.spec.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully. May be decreased in delete request.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nIf this value is nil, the default grace period will be used instead.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nDefaults to 30 seconds."

### fn spec.podSets.template.spec.withTolerations

```ts
withTolerations(tolerations)
```

"If specified, the pod's tolerations."

### fn spec.podSets.template.spec.withTolerationsMixin

```ts
withTolerationsMixin(tolerations)
```

"If specified, the pod's tolerations."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withTopologySpreadConstraints

```ts
withTopologySpreadConstraints(topologySpreadConstraints)
```

"TopologySpreadConstraints describes how a group of pods ought to spread across topology\ndomains. Scheduler will schedule pods in a way which abides by the constraints.\nAll topologySpreadConstraints are ANDed."

### fn spec.podSets.template.spec.withTopologySpreadConstraintsMixin

```ts
withTopologySpreadConstraintsMixin(topologySpreadConstraints)
```

"TopologySpreadConstraints describes how a group of pods ought to spread across topology\ndomains. Scheduler will schedule pods in a way which abides by the constraints.\nAll topologySpreadConstraints are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.withVolumes

```ts
withVolumes(volumes)
```

"List of volumes that can be mounted by containers belonging to the pod.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes"

### fn spec.podSets.template.spec.withVolumesMixin

```ts
withVolumesMixin(volumes)
```

"List of volumes that can be mounted by containers belonging to the pod.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity

"If specified, the pod's scheduling constraints"

## obj spec.podSets.template.spec.affinity.nodeAffinity

"Describes node affinity scheduling rules for the pod."

### fn spec.podSets.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.nodeAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node matches the corresponding matchExpressions; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"Weight associated with matching the corresponding nodeSelectorTerm, in the range 1-100."

## obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference

"A node selector term, associated with the corresponding weight."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"A list of node selector requirements by node's labels."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"A list of node selector requirements by node's labels."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFields

```ts
withMatchFields(matchFields)
```

"A list of node selector requirements by node's fields."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```

"A list of node selector requirements by node's fields."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions

"A list of node selector requirements by node's labels."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields

"A list of node selector requirements by node's fields."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.podSets.template.spec.affinity.nodeAffinity.preferredDuringSchedulingIgnoredDuringExecution.preference.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to an update), the system\nmay or may not try to eventually evict the pod from its node."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTerms

```ts
withNodeSelectorTerms(nodeSelectorTerms)
```

"Required. A list of node selector terms. The terms are ORed."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNodeSelectorTermsMixin

```ts
withNodeSelectorTermsMixin(nodeSelectorTerms)
```

"Required. A list of node selector terms. The terms are ORed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms

"Required. A list of node selector terms. The terms are ORed."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"A list of node selector requirements by node's labels."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"A list of node selector requirements by node's labels."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFields

```ts
withMatchFields(matchFields)
```

"A list of node selector requirements by node's fields."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.withMatchFieldsMixin

```ts
withMatchFieldsMixin(matchFields)
```

"A list of node selector requirements by node's fields."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions

"A list of node selector requirements by node's labels."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields

"A list of node selector requirements by node's fields."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withKey

```ts
withKey(key)
```

"The label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withOperator

```ts
withOperator(operator)
```

"Represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists, DoesNotExist. Gt, and Lt."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValues

```ts
withValues(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

### fn spec.podSets.template.spec.affinity.nodeAffinity.requiredDuringSchedulingIgnoredDuringExecution.nodeSelectorTerms.matchFields.withValuesMixin

```ts
withValuesMixin(values)
```

"An array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. If the operator is Gt or Lt, the values\narray must have a single element, which will be interpreted as an integer.\nThis array is replaced during a strategic merge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity

"Describes pod affinity scheduling rules (e.g. co-locate this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.podSets.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.podAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.podSets.template.spec.affinity.podAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and adding\n\"weight\" to the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"weight associated with matching the corresponding podAffinityTerm,\nin the range 1-100."

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm

"Required. A pod affinity term, associated with the corresponding weight."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity

"Describes pod anti-affinity scheduling rules (e.g. avoid putting this pod in the same node, zone, etc. as some other pod(s))."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecution

```ts
withPreferredDuringSchedulingIgnoredDuringExecution(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and subtracting\n\"weight\" from the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.withPreferredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withPreferredDuringSchedulingIgnoredDuringExecutionMixin(preferredDuringSchedulingIgnoredDuringExecution)
```

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and subtracting\n\"weight\" from the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecution

```ts
withRequiredDuringSchedulingIgnoredDuringExecution(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.withRequiredDuringSchedulingIgnoredDuringExecutionMixin

```ts
withRequiredDuringSchedulingIgnoredDuringExecutionMixin(requiredDuringSchedulingIgnoredDuringExecution)
```

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution

"The scheduler will prefer to schedule pods to nodes that satisfy\nthe anti-affinity expressions specified by this field, but it may choose\na node that violates one or more of the expressions. The node that is\nmost preferred is the one with the greatest sum of weights, i.e.\nfor each node that meets all of the scheduling requirements (resource\nrequest, requiredDuringScheduling anti-affinity expressions, etc.),\ncompute a sum by iterating through the elements of this field and subtracting\n\"weight\" from the sum if the node has pods which matches the corresponding podAffinityTerm; the\nnode(s) with the highest sum are the most preferred."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.withWeight

```ts
withWeight(weight)
```

"weight associated with matching the corresponding podAffinityTerm,\nin the range 1-100."

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm

"Required. A pod affinity term, associated with the corresponding weight."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.preferredDuringSchedulingIgnoredDuringExecution.podAffinityTerm.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution

"If the anti-affinity requirements specified by this field are not met at\nscheduling time, the pod will not be scheduled onto the node.\nIf the anti-affinity requirements specified by this field cease to be met\nat some point during pod execution (e.g. due to a pod label update), the\nsystem may or may not try to eventually evict the pod from its node.\nWhen there are multiple elements, the lists of nodes corresponding to each\npodAffinityTerm are intersected, i.e. all terms must be satisfied."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key in (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both matchLabelKeys and labelSelector.\nAlso, matchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeys

```ts
withMismatchLabelKeys(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withMismatchLabelKeysMixin

```ts
withMismatchLabelKeysMixin(mismatchLabelKeys)
```

"MismatchLabelKeys is a set of pod label keys to select which pods will\nbe taken into consideration. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are merged with `labelSelector` as `key notin (value)`\nto select the group of existing pods which pods will be taken into consideration\nfor the incoming pod's pod (anti) affinity. Keys that don't exist in the incoming\npod labels will be ignored. The default value is empty.\nThe same key is forbidden to exist in both mismatchLabelKeys and labelSelector.\nAlso, mismatchLabelKeys cannot be set when labelSelector isn't set."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespaces

```ts
withNamespaces(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withNamespacesMixin

```ts
withNamespacesMixin(namespaces)
```

"namespaces specifies a static list of namespace names that the term applies to.\nThe term is applied to the union of the namespaces listed in this field\nand the ones selected by namespaceSelector.\nnull or empty namespaces list and null namespaceSelector means \"this pod's namespace\"."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"This pod should be co-located (affinity) or not co-located (anti-affinity) with the pods matching\nthe labelSelector in the specified namespaces, where co-located is defined as running on a node\nwhose value of the label with key topologyKey matches that of any node on which any of the\nselected pods is running.\nEmpty topologyKey is not allowed."

## obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector

"A label query over a set of resources, in this case pods.\nIf it's null, this PodAffinityTerm matches with no Pods."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector

"A label query over the set of namespaces that the term applies to.\nThe term is applied to the union of the namespaces selected by this field\nand the ones listed in the namespaces field.\nnull selector and null or empty namespaces list means \"this pod's namespace\".\nAn empty selector ({}) matches all namespaces."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.affinity.podAntiAffinity.requiredDuringSchedulingIgnoredDuringExecution.namespaceSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers

"List of containers belonging to the pod.\nContainers cannot currently be added or removed.\nThere must be at least one container in a Pod.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withArgs

```ts
withArgs(args)
```

"Arguments to the entrypoint.\nThe container image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.containers.withArgsMixin

```ts
withArgsMixin(args)
```

"Arguments to the entrypoint.\nThe container image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withCommand

```ts
withCommand(command)
```

"Entrypoint array. Not executed within a shell.\nThe container image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.containers.withCommandMixin

```ts
withCommandMixin(command)
```

"Entrypoint array. Not executed within a shell.\nThe container image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withEnv

```ts
withEnv(env)
```

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withEnvFrom

```ts
withEnvFrom(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withEnvMixin

```ts
withEnvMixin(env)
```

"List of environment variables to set in the container.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withImage

```ts
withImage(image)
```

"Container image name.\nMore info: https://kubernetes.io/docs/concepts/containers/images\nThis field is optional to allow higher level config management to default or override\ncontainer images in workload controllers like Deployments and StatefulSets."

### fn spec.podSets.template.spec.containers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```

"Image pull policy.\nOne of Always, Never, IfNotPresent.\nDefaults to Always if :latest tag is specified, or IfNotPresent otherwise.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/containers/images#updating-images"

### fn spec.podSets.template.spec.containers.withName

```ts
withName(name)
```

"Name of the container specified as a DNS_LABEL.\nEach container in a pod must have a unique name (DNS_LABEL).\nCannot be updated."

### fn spec.podSets.template.spec.containers.withPorts

```ts
withPorts(ports)
```

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withPortsMixin

```ts
withPortsMixin(ports)
```

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```

"Resources resize policy for the container."

### fn spec.podSets.template.spec.containers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```

"Resources resize policy for the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"RestartPolicy defines the restart behavior of individual containers in a pod.\nThis overrides the pod-level restart policy. When this field is not specified,\nthe restart behavior is defined by the Pod's restart policy and the container type.\nAdditionally, setting the RestartPolicy as \"Always\" for the init container will\nhave the following effect:\nthis init container will be continually restarted on\nexit until all regular containers have terminated. Once all regular\ncontainers have completed, all init containers with restartPolicy \"Always\"\nwill be shut down. This lifecycle differs from normal init containers and\nis often referred to as a \"sidecar\" container. Although this init\ncontainer still starts in the init container sequence, it does not wait\nfor the container to complete before proceeding to the next init\ncontainer. Instead, the next init container starts immediately after this\ninit container is started, or after any startupProbe has successfully\ncompleted."

### fn spec.podSets.template.spec.containers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

### fn spec.podSets.template.spec.containers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withStdin

```ts
withStdin(stdin)
```

"Whether this container should allocate a buffer for stdin in the container runtime. If this\nis not set, reads from stdin in the container will always result in EOF.\nDefault is false."

### fn spec.podSets.template.spec.containers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```

"Whether the container runtime should close the stdin channel after it has been opened by\na single attach. When stdin is true the stdin stream will remain open across multiple attach\nsessions. If stdinOnce is set to true, stdin is opened on container start, is empty until the\nfirst client attaches to stdin, and then remains open and accepts data until the client disconnects,\nat which time stdin is closed and remains closed until the container is restarted. If this\nflag is false, a container processes that reads from stdin will never receive an EOF.\nDefault is false"

### fn spec.podSets.template.spec.containers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```

"Optional: Path at which the file to which the container's termination message\nwill be written is mounted into the container's filesystem.\nMessage written is intended to be brief final status, such as an assertion failure message.\nWill be truncated by the node if greater than 4096 bytes. The total message length across\nall containers will be limited to 12kb.\nDefaults to /dev/termination-log.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```

"Indicate how the termination message should be populated. File will use the contents of\nterminationMessagePath to populate the container status message on both success and failure.\nFallbackToLogsOnError will use the last chunk of container log output if the termination\nmessage file is empty and the container exited with an error.\nThe log output is limited to 2048 bytes or 80 lines, whichever is smaller.\nDefaults to File.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withTty

```ts
withTty(tty)
```

"Whether this container should allocate a TTY for itself, also requires 'stdin' to be true.\nDefault is false."

### fn spec.podSets.template.spec.containers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.containers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

### fn spec.podSets.template.spec.containers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.withWorkingDir

```ts
withWorkingDir(workingDir)
```

"Container's working directory.\nIf not specified, the container runtime's default will be used, which\nmight be configured in the container image.\nCannot be updated."

## obj spec.podSets.template.spec.containers.env

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.containers.env.withName

```ts
withName(name)
```

"Name of the environment variable.\nMay consist of any printable ASCII characters except '='."

### fn spec.podSets.template.spec.containers.env.withValue

```ts
withValue(value)
```

"Variable references $(VAR_NAME) are expanded\nusing the previously defined environment variables in the container and\nany service environment variables. If a variable cannot be resolved,\nthe reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e.\n\"$$(VAR_NAME)\" will produce the string literal \"$(VAR_NAME)\".\nEscaped references will never be expanded, regardless of whether the variable\nexists or not.\nDefaults to \"\"."

## obj spec.podSets.template.spec.containers.env.valueFrom

"Source for the environment variable's value. Cannot be used if value is not empty."

## obj spec.podSets.template.spec.containers.env.valueFrom.configMapKeyRef

"Selects a key of a ConfigMap."

### fn spec.podSets.template.spec.containers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```

"The key to select."

### fn spec.podSets.template.spec.containers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.containers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap or its key must be defined"

## obj spec.podSets.template.spec.containers.env.valueFrom.fieldRef

"Selects a field of the pod: supports metadata.name, metadata.namespace, `metadata.labels['<KEY>']`, `metadata.annotations['<KEY>']`,\nspec.nodeName, spec.serviceAccountName, status.hostIP, status.podIP, status.podIPs."

### fn spec.podSets.template.spec.containers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"Version of the schema the FieldPath is written in terms of, defaults to \"v1\"."

### fn spec.podSets.template.spec.containers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"Path of the field to select in the specified API version."

## obj spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef

"FileKeyRef selects a key of the env file.\nRequires the EnvFiles feature gate to be enabled."

### fn spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```

"The key within the env file. An invalid key will prevent the pod from starting.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nDuring Alpha stage of the EnvFiles feature gate, the key size is limited to 128 characters."

### fn spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the file or its key must be defined. If the file or key\ndoes not exist, then the env var is not published.\nIf optional is set to true and the specified key does not exist,\nthe environment variable will not be set in the Pod's containers.\n\nIf optional is set to false and the specified key does not exist,\nan error will be returned during Pod creation."

### fn spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```

"The path within the volume from which to select the file.\nMust be relative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.containers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```

"The name of the volume mount containing the env file."

## obj spec.podSets.template.spec.containers.env.valueFrom.resourceFieldRef

"Selects a resource of the container: only resources limits and requests\n(limits.cpu, limits.memory, limits.ephemeral-storage, requests.cpu, requests.memory and requests.ephemeral-storage) are currently supported."

### fn spec.podSets.template.spec.containers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```

"Container name: required for volumes, optional for env vars"

### fn spec.podSets.template.spec.containers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```

"Specifies the output format of the exposed resources, defaults to \"1\

### fn spec.podSets.template.spec.containers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```

"Required: resource to select"

## obj spec.podSets.template.spec.containers.env.valueFrom.secretKeyRef

"Selects a key of a secret in the pod's namespace"

### fn spec.podSets.template.spec.containers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```

"The key of the secret to select from.  Must be a valid secret key."

### fn spec.podSets.template.spec.containers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.containers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret or its key must be defined"

## obj spec.podSets.template.spec.containers.envFrom

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.containers.envFrom.withPrefix

```ts
withPrefix(prefix)
```

"Optional text to prepend to the name of each environment variable.\nMay consist of any printable ASCII characters except '='."

## obj spec.podSets.template.spec.containers.envFrom.configMapRef

"The ConfigMap to select from"

### fn spec.podSets.template.spec.containers.envFrom.configMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.containers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap must be defined"

## obj spec.podSets.template.spec.containers.envFrom.secretRef

"The Secret to select from"

### fn spec.podSets.template.spec.containers.envFrom.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.containers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret must be defined"

## obj spec.podSets.template.spec.containers.lifecycle

"Actions that the management system should take in response to container lifecycle events.\nCannot be updated."

### fn spec.podSets.template.spec.containers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```

"StopSignal defines which signal will be sent to a container when it is being stopped.\nIf not specified, the default is defined by the container runtime in use.\nStopSignal can only be set for Pods with a non-empty .spec.os.name"

## obj spec.podSets.template.spec.containers.lifecycle.postStart

"PostStart is called immediately after a container is created. If the handler fails,\nthe container is terminated and restarted according to its restart policy.\nOther management of the container blocks until the hook completes.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.containers.lifecycle.postStart.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.lifecycle.postStart.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.containers.lifecycle.postStart.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.containers.lifecycle.postStart.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.containers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.containers.lifecycle.preStop

"PreStop is called immediately before a container is terminated due to an\nAPI request or management event such as liveness/startup probe failure,\npreemption, resource contention, etc. The handler is not called if the\ncontainer crashes or exits. The Pod's termination grace period countdown begins before the\nPreStop hook is executed. Regardless of the outcome of the handler, the\ncontainer will eventually terminate within the Pod's termination grace\nperiod (unless delayed by finalizers). Other management of the container blocks until the hook completes\nor until the termination grace period is reached.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.containers.lifecycle.preStop.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.lifecycle.preStop.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.containers.lifecycle.preStop.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.containers.lifecycle.preStop.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.containers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.containers.livenessProbe

"Periodic probe of container liveness.\nContainer will be restarted if the probe fails.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.containers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.containers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.containers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.containers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.containers.livenessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.containers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.containers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.livenessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.containers.livenessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.containers.livenessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.containers.livenessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.containers.livenessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.containers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.containers.livenessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.containers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.containers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.containers.ports

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

### fn spec.podSets.template.spec.containers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```

"Number of port to expose on the pod's IP address.\nThis must be a valid port number, 0 < x < 65536."

### fn spec.podSets.template.spec.containers.ports.withHostIP

```ts
withHostIP(hostIP)
```

"What host IP to bind the external port to."

### fn spec.podSets.template.spec.containers.ports.withHostPort

```ts
withHostPort(hostPort)
```

"Number of port to expose on the host.\nIf specified, this must be a valid port number, 0 < x < 65536.\nIf HostNetwork is specified, this must match ContainerPort.\nMost containers do not need this."

### fn spec.podSets.template.spec.containers.ports.withName

```ts
withName(name)
```

"If specified, this must be an IANA_SVC_NAME and unique within the pod. Each\nnamed port in a pod must have a unique name. Name for the port that can be\nreferred to by services."

### fn spec.podSets.template.spec.containers.ports.withProtocol

```ts
withProtocol(protocol)
```

"Protocol for port. Must be UDP, TCP, or SCTP.\nDefaults to \"TCP\"."

## obj spec.podSets.template.spec.containers.readinessProbe

"Periodic probe of container service readiness.\nContainer will be removed from service endpoints if the probe fails.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.containers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.containers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.containers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.containers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.containers.readinessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.containers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.containers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.readinessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.containers.readinessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.containers.readinessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.containers.readinessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.containers.readinessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.containers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.containers.readinessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.containers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.containers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.containers.resizePolicy

"Resources resize policy for the container."

### fn spec.podSets.template.spec.containers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```

"Name of the resource to which this resource resize policy applies.\nSupported values: cpu, memory."

### fn spec.podSets.template.spec.containers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"Restart policy to apply when specified resource is resized.\nIf not specified, it defaults to NotRequired."

## obj spec.podSets.template.spec.containers.resources

"Compute Resources required by this container.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.containers.resources.withClaims

```ts
withClaims(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.containers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.containers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.containers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.resources.claims

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.containers.resources.claims.withName

```ts
withName(name)
```

"Name must match the name of one entry in pod.spec.resourceClaims of\nthe Pod where this field is used. It makes that resource available\ninside a container."

### fn spec.podSets.template.spec.containers.resources.claims.withRequest

```ts
withRequest(request)
```

"Request is the name chosen for a request in the referenced claim.\nIf empty, everything from the claim is made available, otherwise\nonly the result of this request."

## obj spec.podSets.template.spec.containers.restartPolicyRules

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

### fn spec.podSets.template.spec.containers.restartPolicyRules.withAction

```ts
withAction(action)
```

"Specifies the action taken on a container exit if the requirements\nare satisfied. The only possible value is \"Restart\" to restart the\ncontainer."

## obj spec.podSets.template.spec.containers.restartPolicyRules.exitCodes

"Represents the exit codes to check on container exits."

### fn spec.podSets.template.spec.containers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```

"Represents the relationship between the container exit code(s) and the\nspecified values. Possible values are:\n- In: the requirement is satisfied if the container exit code is in the\n  set of specified values.\n- NotIn: the requirement is satisfied if the container exit code is\n  not in the set of specified values."

### fn spec.podSets.template.spec.containers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

### fn spec.podSets.template.spec.containers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.securityContext

"SecurityContext defines the security options the container should be run with.\nIf set, the fields of SecurityContext override the equivalent fields of PodSecurityContext.\nMore info: https://kubernetes.io/docs/tasks/configure-pod-container/security-context/"

### fn spec.podSets.template.spec.containers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```

"AllowPrivilegeEscalation controls whether a process can gain more\nprivileges than its parent process. This bool directly controls if\nthe no_new_privs flag will be set on the container process.\nAllowPrivilegeEscalation is true always when the container is:\n1) run as Privileged\n2) has CAP_SYS_ADMIN\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```

"Run container in privileged mode.\nProcesses in privileged containers are essentially equivalent to root on the host.\nDefaults to false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.withProcMount

```ts
withProcMount(procMount)
```

"procMount denotes the type of proc mount to use for the containers.\nThe default value is Default which uses the container runtime defaults for\nreadonly paths and masked paths.\nThis requires the ProcMountType feature flag to be enabled.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```

"Whether this container has a read-only root filesystem.\nDefault is false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```

"The GID to run the entrypoint of the container process.\nUses runtime default if unset.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```

"Indicates that the container must run as a non-root user.\nIf true, the Kubelet will validate the image at runtime to ensure that it\ndoes not run as UID 0 (root) and fail to start the container if it does.\nIf unset or false, no such validation will be performed.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

### fn spec.podSets.template.spec.containers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```

"The UID to run the entrypoint of the container process.\nDefaults to user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

## obj spec.podSets.template.spec.containers.securityContext.appArmorProfile

"appArmorProfile is the AppArmor options to use by this container. If set, this profile\noverrides the pod's appArmorProfile.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile loaded on the node that should be used.\nThe profile must be preconfigured on the node to work.\nMust match the loaded name of the profile.\nMust be set if and only if type is \"Localhost\"."

### fn spec.podSets.template.spec.containers.securityContext.appArmorProfile.withType

```ts
withType(type)
```

"type indicates which kind of AppArmor profile will be applied.\nValid options are:\n  Localhost - a profile pre-loaded on the node.\n  RuntimeDefault - the container runtime's default profile.\n  Unconfined - no AppArmor enforcement."

## obj spec.podSets.template.spec.containers.securityContext.capabilities

"The capabilities to add/drop when running containers.\nDefaults to the default set of capabilities granted by the container runtime.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```

"Added capabilities"

### fn spec.podSets.template.spec.containers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```

"Added capabilities"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```

"Removed capabilities"

### fn spec.podSets.template.spec.containers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```

"Removed capabilities"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.securityContext.seLinuxOptions

"The SELinux context to be applied to the container.\nIf unspecified, the container runtime will allocate a random SELinux context for each\ncontainer.  May also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```

"Level is SELinux level label that applies to the container."

### fn spec.podSets.template.spec.containers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```

"Role is a SELinux role label that applies to the container."

### fn spec.podSets.template.spec.containers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```

"Type is a SELinux type label that applies to the container."

### fn spec.podSets.template.spec.containers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```

"User is a SELinux user label that applies to the container."

## obj spec.podSets.template.spec.containers.securityContext.seccompProfile

"The seccomp options to use by this container. If seccomp options are\nprovided at both the pod & container level, the container options\noverride the pod options.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.containers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile defined in a file on the node should be used.\nThe profile must be preconfigured on the node to work.\nMust be a descending path, relative to the kubelet's configured seccomp profile location.\nMust be set if type is \"Localhost\". Must NOT be set for any other type."

### fn spec.podSets.template.spec.containers.securityContext.seccompProfile.withType

```ts
withType(type)
```

"type indicates which kind of seccomp profile will be applied.\nValid options are:\n\nLocalhost - a profile defined in a file on the node should be used.\nRuntimeDefault - the container runtime default profile should be used.\nUnconfined - no profile should be applied."

## obj spec.podSets.template.spec.containers.securityContext.windowsOptions

"The Windows specific settings applied to all containers.\nIf unspecified, the options from the PodSecurityContext will be used.\nIf set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is linux."

### fn spec.podSets.template.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```

"GMSACredentialSpec is where the GMSA admission webhook\n(https://github.com/kubernetes-sigs/windows-gmsa) inlines the contents of the\nGMSA credential spec named by the GMSACredentialSpecName field."

### fn spec.podSets.template.spec.containers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```

"GMSACredentialSpecName is the name of the GMSA credential spec to use."

### fn spec.podSets.template.spec.containers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```

"HostProcess determines if a container should be run as a 'Host Process' container.\nAll of a Pod's containers must have the same effective HostProcess value\n(it is not allowed to have a mix of HostProcess containers and non-HostProcess containers).\nIn addition, if HostProcess is true then HostNetwork must also be set to true."

### fn spec.podSets.template.spec.containers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```

"The UserName in Windows to run the entrypoint of the container process.\nDefaults to the user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext. If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

## obj spec.podSets.template.spec.containers.startupProbe

"StartupProbe indicates that the Pod has successfully initialized.\nIf specified, no other probes are executed until this completes successfully.\nIf this probe fails, the Pod will be restarted, just as if the livenessProbe failed.\nThis can be used to provide different probe parameters at the beginning of a Pod's lifecycle,\nwhen it might take a long time to load data or warm a cache, than during steady-state operation.\nThis cannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.containers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.containers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.containers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.containers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.containers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.containers.startupProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.containers.startupProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.containers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.containers.startupProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.containers.startupProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.containers.startupProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.containers.startupProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.containers.startupProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.containers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.containers.startupProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.containers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.containers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.containers.volumeDevices

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.containers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```

"devicePath is the path inside of the container that the device will be mapped to."

### fn spec.podSets.template.spec.containers.volumeDevices.withName

```ts
withName(name)
```

"name must match the name of a persistentVolumeClaim in the pod"

## obj spec.podSets.template.spec.containers.volumeMounts

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

### fn spec.podSets.template.spec.containers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```

"Path within the container at which the volume should be mounted.  Must\nnot contain ':'."

### fn spec.podSets.template.spec.containers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```

"mountPropagation determines how mounts are propagated from the host\nto container and the other way around.\nWhen not set, MountPropagationNone is used.\nThis field is beta in 1.10.\nWhen RecursiveReadOnly is set to IfPossible or to Enabled, MountPropagation must be None or unspecified\n(which defaults to None)."

### fn spec.podSets.template.spec.containers.volumeMounts.withName

```ts
withName(name)
```

"This must match the Name of a Volume."

### fn spec.podSets.template.spec.containers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```

"Mounted read-only if true, read-write otherwise (false or unspecified).\nDefaults to false."

### fn spec.podSets.template.spec.containers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```

"RecursiveReadOnly specifies whether read-only mounts should be handled\nrecursively.\n\nIf ReadOnly is false, this field has no meaning and must be unspecified.\n\nIf ReadOnly is true, and this field is set to Disabled, the mount is not made\nrecursively read-only.  If this field is set to IfPossible, the mount is made\nrecursively read-only, if it is supported by the container runtime.  If this\nfield is set to Enabled, the mount is made recursively read-only if it is\nsupported by the container runtime, otherwise the pod will not be started and\nan error will be generated to indicate the reason.\n\nIf this field is set to IfPossible or Enabled, MountPropagation must be set to\nNone (or be unspecified, which defaults to None).\n\nIf this field is not specified, it is treated as an equivalent of Disabled."

### fn spec.podSets.template.spec.containers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```

"Path within the volume from which the container's volume should be mounted.\nDefaults to \"\" (volume's root)."

### fn spec.podSets.template.spec.containers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```

"Expanded path within the volume from which the container's volume should be mounted.\nBehaves similarly to SubPath but environment variable references $(VAR_NAME) are expanded using the container's environment.\nDefaults to \"\" (volume's root).\nSubPathExpr and SubPath are mutually exclusive."

## obj spec.podSets.template.spec.dnsConfig

"Specifies the DNS parameters of a pod.\nParameters specified here will be merged to the generated DNS\nconfiguration based on DNSPolicy."

### fn spec.podSets.template.spec.dnsConfig.withNameservers

```ts
withNameservers(nameservers)
```

"A list of DNS name server IP addresses.\nThis will be appended to the base nameservers generated from DNSPolicy.\nDuplicated nameservers will be removed."

### fn spec.podSets.template.spec.dnsConfig.withNameserversMixin

```ts
withNameserversMixin(nameservers)
```

"A list of DNS name server IP addresses.\nThis will be appended to the base nameservers generated from DNSPolicy.\nDuplicated nameservers will be removed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.dnsConfig.withOptions

```ts
withOptions(options)
```

"A list of DNS resolver options.\nThis will be merged with the base options generated from DNSPolicy.\nDuplicated entries will be removed. Resolution options given in Options\nwill override those that appear in the base DNSPolicy."

### fn spec.podSets.template.spec.dnsConfig.withOptionsMixin

```ts
withOptionsMixin(options)
```

"A list of DNS resolver options.\nThis will be merged with the base options generated from DNSPolicy.\nDuplicated entries will be removed. Resolution options given in Options\nwill override those that appear in the base DNSPolicy."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.dnsConfig.withSearches

```ts
withSearches(searches)
```

"A list of DNS search domains for host-name lookup.\nThis will be appended to the base search paths generated from DNSPolicy.\nDuplicated search paths will be removed."

### fn spec.podSets.template.spec.dnsConfig.withSearchesMixin

```ts
withSearchesMixin(searches)
```

"A list of DNS search domains for host-name lookup.\nThis will be appended to the base search paths generated from DNSPolicy.\nDuplicated search paths will be removed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.dnsConfig.options

"A list of DNS resolver options.\nThis will be merged with the base options generated from DNSPolicy.\nDuplicated entries will be removed. Resolution options given in Options\nwill override those that appear in the base DNSPolicy."

### fn spec.podSets.template.spec.dnsConfig.options.withName

```ts
withName(name)
```

"Name is this DNS resolver option's name.\nRequired."

### fn spec.podSets.template.spec.dnsConfig.options.withValue

```ts
withValue(value)
```

"Value is this DNS resolver option's value."

## obj spec.podSets.template.spec.ephemeralContainers

"List of ephemeral containers run in this pod. Ephemeral containers may be run in an existing\npod to perform user-initiated actions such as debugging. This list cannot be specified when\ncreating a pod, and it cannot be modified by updating the pod spec. In order to add an\nephemeral container to an existing pod, use the pod's ephemeralcontainers subresource."

### fn spec.podSets.template.spec.ephemeralContainers.withArgs

```ts
withArgs(args)
```

"Arguments to the entrypoint.\nThe image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.ephemeralContainers.withArgsMixin

```ts
withArgsMixin(args)
```

"Arguments to the entrypoint.\nThe image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withCommand

```ts
withCommand(command)
```

"Entrypoint array. Not executed within a shell.\nThe image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.ephemeralContainers.withCommandMixin

```ts
withCommandMixin(command)
```

"Entrypoint array. Not executed within a shell.\nThe image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withEnv

```ts
withEnv(env)
```

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withEnvMixin

```ts
withEnvMixin(env)
```

"List of environment variables to set in the container.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withImage

```ts
withImage(image)
```

"Container image name.\nMore info: https://kubernetes.io/docs/concepts/containers/images"

### fn spec.podSets.template.spec.ephemeralContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```

"Image pull policy.\nOne of Always, Never, IfNotPresent.\nDefaults to Always if :latest tag is specified, or IfNotPresent otherwise.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/containers/images#updating-images"

### fn spec.podSets.template.spec.ephemeralContainers.withName

```ts
withName(name)
```

"Name of the ephemeral container specified as a DNS_LABEL.\nThis name must be unique among all containers, init containers and ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.withPorts

```ts
withPorts(ports)
```

"Ports are not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.withPortsMixin

```ts
withPortsMixin(ports)
```

"Ports are not allowed for ephemeral containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```

"Resources resize policy for the container."

### fn spec.podSets.template.spec.ephemeralContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```

"Resources resize policy for the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"Restart policy for the container to manage the restart behavior of each\ncontainer within a pod.\nYou cannot set this field on ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. You cannot set this field on\nephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. You cannot set this field on\nephemeral containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withStdin

```ts
withStdin(stdin)
```

"Whether this container should allocate a buffer for stdin in the container runtime. If this\nis not set, reads from stdin in the container will always result in EOF.\nDefault is false."

### fn spec.podSets.template.spec.ephemeralContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```

"Whether the container runtime should close the stdin channel after it has been opened by\na single attach. When stdin is true the stdin stream will remain open across multiple attach\nsessions. If stdinOnce is set to true, stdin is opened on container start, is empty until the\nfirst client attaches to stdin, and then remains open and accepts data until the client disconnects,\nat which time stdin is closed and remains closed until the container is restarted. If this\nflag is false, a container processes that reads from stdin will never receive an EOF.\nDefault is false"

### fn spec.podSets.template.spec.ephemeralContainers.withTargetContainerName

```ts
withTargetContainerName(targetContainerName)
```

"If set, the name of the container from PodSpec that this ephemeral container targets.\nThe ephemeral container will be run in the namespaces (IPC, PID, etc) of this container.\nIf not set then the ephemeral container uses the namespaces configured in the Pod spec.\n\nThe container runtime must implement support for this feature. If the runtime does not\nsupport namespace targeting then the result of setting this field is undefined."

### fn spec.podSets.template.spec.ephemeralContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```

"Optional: Path at which the file to which the container's termination message\nwill be written is mounted into the container's filesystem.\nMessage written is intended to be brief final status, such as an assertion failure message.\nWill be truncated by the node if greater than 4096 bytes. The total message length across\nall containers will be limited to 12kb.\nDefaults to /dev/termination-log.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```

"Indicate how the termination message should be populated. File will use the contents of\nterminationMessagePath to populate the container status message on both success and failure.\nFallbackToLogsOnError will use the last chunk of container log output if the termination\nmessage file is empty and the container exited with an error.\nThe log output is limited to 2048 bytes or 80 lines, whichever is smaller.\nDefaults to File.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.withTty

```ts
withTty(tty)
```

"Whether this container should allocate a TTY for itself, also requires 'stdin' to be true.\nDefault is false."

### fn spec.podSets.template.spec.ephemeralContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.ephemeralContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```

"Pod volumes to mount into the container's filesystem. Subpath mounts are not allowed for ephemeral containers.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```

"Pod volumes to mount into the container's filesystem. Subpath mounts are not allowed for ephemeral containers.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```

"Container's working directory.\nIf not specified, the container runtime's default will be used, which\nmight be configured in the container image.\nCannot be updated."

## obj spec.podSets.template.spec.ephemeralContainers.env

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.env.withName

```ts
withName(name)
```

"Name of the environment variable.\nMay consist of any printable ASCII characters except '='."

### fn spec.podSets.template.spec.ephemeralContainers.env.withValue

```ts
withValue(value)
```

"Variable references $(VAR_NAME) are expanded\nusing the previously defined environment variables in the container and\nany service environment variables. If a variable cannot be resolved,\nthe reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e.\n\"$$(VAR_NAME)\" will produce the string literal \"$(VAR_NAME)\".\nEscaped references will never be expanded, regardless of whether the variable\nexists or not.\nDefaults to \"\"."

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom

"Source for the environment variable's value. Cannot be used if value is not empty."

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef

"Selects a key of a ConfigMap."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```

"The key to select."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap or its key must be defined"

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fieldRef

"Selects a field of the pod: supports metadata.name, metadata.namespace, `metadata.labels['<KEY>']`, `metadata.annotations['<KEY>']`,\nspec.nodeName, spec.serviceAccountName, status.hostIP, status.podIP, status.podIPs."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"Version of the schema the FieldPath is written in terms of, defaults to \"v1\"."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"Path of the field to select in the specified API version."

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef

"FileKeyRef selects a key of the env file.\nRequires the EnvFiles feature gate to be enabled."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```

"The key within the env file. An invalid key will prevent the pod from starting.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nDuring Alpha stage of the EnvFiles feature gate, the key size is limited to 128 characters."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the file or its key must be defined. If the file or key\ndoes not exist, then the env var is not published.\nIf optional is set to true and the specified key does not exist,\nthe environment variable will not be set in the Pod's containers.\n\nIf optional is set to false and the specified key does not exist,\nan error will be returned during Pod creation."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```

"The path within the volume from which to select the file.\nMust be relative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```

"The name of the volume mount containing the env file."

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef

"Selects a resource of the container: only resources limits and requests\n(limits.cpu, limits.memory, limits.ephemeral-storage, requests.cpu, requests.memory and requests.ephemeral-storage) are currently supported."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```

"Container name: required for volumes, optional for env vars"

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```

"Specifies the output format of the exposed resources, defaults to \"1\

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```

"Required: resource to select"

## obj spec.podSets.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef

"Selects a key of a secret in the pod's namespace"

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```

"The key of the secret to select from.  Must be a valid secret key."

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.ephemeralContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret or its key must be defined"

## obj spec.podSets.template.spec.ephemeralContainers.envFrom

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```

"Optional text to prepend to the name of each environment variable.\nMay consist of any printable ASCII characters except '='."

## obj spec.podSets.template.spec.ephemeralContainers.envFrom.configMapRef

"The ConfigMap to select from"

### fn spec.podSets.template.spec.ephemeralContainers.envFrom.configMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.ephemeralContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap must be defined"

## obj spec.podSets.template.spec.ephemeralContainers.envFrom.secretRef

"The Secret to select from"

### fn spec.podSets.template.spec.ephemeralContainers.envFrom.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.ephemeralContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret must be defined"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle

"Lifecycle is not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```

"StopSignal defines which signal will be sent to a container when it is being stopped.\nIf not specified, the default is defined by the container runtime in use.\nStopSignal can only be set for Pods with a non-empty .spec.os.name"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart

"PostStart is called immediately after a container is created. If the handler fails,\nthe container is terminated and restarted according to its restart policy.\nOther management of the container blocks until the hook completes.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop

"PreStop is called immediately before a container is terminated due to an\nAPI request or management event such as liveness/startup probe failure,\npreemption, resource contention, etc. The handler is not called if the\ncontainer crashes or exits. The Pod's termination grace period countdown begins before the\nPreStop hook is executed. Regardless of the outcome of the handler, the\ncontainer will eventually terminate within the Pod's termination grace\nperiod (unless delayed by finalizers). Other management of the container blocks until the hook completes\nor until the termination grace period is reached.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.ephemeralContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe

"Probes are not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.ephemeralContainers.livenessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.ephemeralContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.ephemeralContainers.ports

"Ports are not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```

"Number of port to expose on the pod's IP address.\nThis must be a valid port number, 0 < x < 65536."

### fn spec.podSets.template.spec.ephemeralContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```

"What host IP to bind the external port to."

### fn spec.podSets.template.spec.ephemeralContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```

"Number of port to expose on the host.\nIf specified, this must be a valid port number, 0 < x < 65536.\nIf HostNetwork is specified, this must match ContainerPort.\nMost containers do not need this."

### fn spec.podSets.template.spec.ephemeralContainers.ports.withName

```ts
withName(name)
```

"If specified, this must be an IANA_SVC_NAME and unique within the pod. Each\nnamed port in a pod must have a unique name. Name for the port that can be\nreferred to by services."

### fn spec.podSets.template.spec.ephemeralContainers.ports.withProtocol

```ts
withProtocol(protocol)
```

"Protocol for port. Must be UDP, TCP, or SCTP.\nDefaults to \"TCP\"."

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe

"Probes are not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.ephemeralContainers.readinessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.ephemeralContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.ephemeralContainers.resizePolicy

"Resources resize policy for the container."

### fn spec.podSets.template.spec.ephemeralContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```

"Name of the resource to which this resource resize policy applies.\nSupported values: cpu, memory."

### fn spec.podSets.template.spec.ephemeralContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"Restart policy to apply when specified resource is resized.\nIf not specified, it defaults to NotRequired."

## obj spec.podSets.template.spec.ephemeralContainers.resources

"Resources are not allowed for ephemeral containers. Ephemeral containers use spare resources\nalready allocated to the pod."

### fn spec.podSets.template.spec.ephemeralContainers.resources.withClaims

```ts
withClaims(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.ephemeralContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.ephemeralContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.ephemeralContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.resources.claims

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.ephemeralContainers.resources.claims.withName

```ts
withName(name)
```

"Name must match the name of one entry in pod.spec.resourceClaims of\nthe Pod where this field is used. It makes that resource available\ninside a container."

### fn spec.podSets.template.spec.ephemeralContainers.resources.claims.withRequest

```ts
withRequest(request)
```

"Request is the name chosen for a request in the referenced claim.\nIf empty, everything from the claim is made available, otherwise\nonly the result of this request."

## obj spec.podSets.template.spec.ephemeralContainers.restartPolicyRules

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. You cannot set this field on\nephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.withAction

```ts
withAction(action)
```

"Specifies the action taken on a container exit if the requirements\nare satisfied. The only possible value is \"Restart\" to restart the\ncontainer."

## obj spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.exitCodes

"Represents the exit codes to check on container exits."

### fn spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```

"Represents the relationship between the container exit code(s) and the\nspecified values. Possible values are:\n- In: the requirement is satisfied if the container exit code is in the\n  set of specified values.\n- NotIn: the requirement is satisfied if the container exit code is\n  not in the set of specified values."

### fn spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

### fn spec.podSets.template.spec.ephemeralContainers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.securityContext

"Optional: SecurityContext defines the security options the ephemeral container should be run with.\nIf set, the fields of SecurityContext override the equivalent fields of PodSecurityContext."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```

"AllowPrivilegeEscalation controls whether a process can gain more\nprivileges than its parent process. This bool directly controls if\nthe no_new_privs flag will be set on the container process.\nAllowPrivilegeEscalation is true always when the container is:\n1) run as Privileged\n2) has CAP_SYS_ADMIN\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```

"Run container in privileged mode.\nProcesses in privileged containers are essentially equivalent to root on the host.\nDefaults to false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```

"procMount denotes the type of proc mount to use for the containers.\nThe default value is Default which uses the container runtime defaults for\nreadonly paths and masked paths.\nThis requires the ProcMountType feature flag to be enabled.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```

"Whether this container has a read-only root filesystem.\nDefault is false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```

"The GID to run the entrypoint of the container process.\nUses runtime default if unset.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```

"Indicates that the container must run as a non-root user.\nIf true, the Kubelet will validate the image at runtime to ensure that it\ndoes not run as UID 0 (root) and fail to start the container if it does.\nIf unset or false, no such validation will be performed.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```

"The UID to run the entrypoint of the container process.\nDefaults to user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

## obj spec.podSets.template.spec.ephemeralContainers.securityContext.appArmorProfile

"appArmorProfile is the AppArmor options to use by this container. If set, this profile\noverrides the pod's appArmorProfile.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile loaded on the node that should be used.\nThe profile must be preconfigured on the node to work.\nMust match the loaded name of the profile.\nMust be set if and only if type is \"Localhost\"."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```

"type indicates which kind of AppArmor profile will be applied.\nValid options are:\n  Localhost - a profile pre-loaded on the node.\n  RuntimeDefault - the container runtime's default profile.\n  Unconfined - no AppArmor enforcement."

## obj spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities

"The capabilities to add/drop when running containers.\nDefaults to the default set of capabilities granted by the container runtime.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```

"Added capabilities"

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```

"Added capabilities"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```

"Removed capabilities"

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```

"Removed capabilities"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions

"The SELinux context to be applied to the container.\nIf unspecified, the container runtime will allocate a random SELinux context for each\ncontainer.  May also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```

"Level is SELinux level label that applies to the container."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```

"Role is a SELinux role label that applies to the container."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```

"Type is a SELinux type label that applies to the container."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```

"User is a SELinux user label that applies to the container."

## obj spec.podSets.template.spec.ephemeralContainers.securityContext.seccompProfile

"The seccomp options to use by this container. If seccomp options are\nprovided at both the pod & container level, the container options\noverride the pod options.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile defined in a file on the node should be used.\nThe profile must be preconfigured on the node to work.\nMust be a descending path, relative to the kubelet's configured seccomp profile location.\nMust be set if type is \"Localhost\". Must NOT be set for any other type."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```

"type indicates which kind of seccomp profile will be applied.\nValid options are:\n\nLocalhost - a profile defined in a file on the node should be used.\nRuntimeDefault - the container runtime default profile should be used.\nUnconfined - no profile should be applied."

## obj spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions

"The Windows specific settings applied to all containers.\nIf unspecified, the options from the PodSecurityContext will be used.\nIf set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is linux."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```

"GMSACredentialSpec is where the GMSA admission webhook\n(https://github.com/kubernetes-sigs/windows-gmsa) inlines the contents of the\nGMSA credential spec named by the GMSACredentialSpecName field."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```

"GMSACredentialSpecName is the name of the GMSA credential spec to use."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```

"HostProcess determines if a container should be run as a 'Host Process' container.\nAll of a Pod's containers must have the same effective HostProcess value\n(it is not allowed to have a mix of HostProcess containers and non-HostProcess containers).\nIn addition, if HostProcess is true then HostNetwork must also be set to true."

### fn spec.podSets.template.spec.ephemeralContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```

"The UserName in Windows to run the entrypoint of the container process.\nDefaults to the user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext. If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe

"Probes are not allowed for ephemeral containers."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.ephemeralContainers.startupProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.ephemeralContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.ephemeralContainers.volumeDevices

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.ephemeralContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```

"devicePath is the path inside of the container that the device will be mapped to."

### fn spec.podSets.template.spec.ephemeralContainers.volumeDevices.withName

```ts
withName(name)
```

"name must match the name of a persistentVolumeClaim in the pod"

## obj spec.podSets.template.spec.ephemeralContainers.volumeMounts

"Pod volumes to mount into the container's filesystem. Subpath mounts are not allowed for ephemeral containers.\nCannot be updated."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```

"Path within the container at which the volume should be mounted.  Must\nnot contain ':'."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```

"mountPropagation determines how mounts are propagated from the host\nto container and the other way around.\nWhen not set, MountPropagationNone is used.\nThis field is beta in 1.10.\nWhen RecursiveReadOnly is set to IfPossible or to Enabled, MountPropagation must be None or unspecified\n(which defaults to None)."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withName

```ts
withName(name)
```

"This must match the Name of a Volume."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```

"Mounted read-only if true, read-write otherwise (false or unspecified).\nDefaults to false."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```

"RecursiveReadOnly specifies whether read-only mounts should be handled\nrecursively.\n\nIf ReadOnly is false, this field has no meaning and must be unspecified.\n\nIf ReadOnly is true, and this field is set to Disabled, the mount is not made\nrecursively read-only.  If this field is set to IfPossible, the mount is made\nrecursively read-only, if it is supported by the container runtime.  If this\nfield is set to Enabled, the mount is made recursively read-only if it is\nsupported by the container runtime, otherwise the pod will not be started and\nan error will be generated to indicate the reason.\n\nIf this field is set to IfPossible or Enabled, MountPropagation must be set to\nNone (or be unspecified, which defaults to None).\n\nIf this field is not specified, it is treated as an equivalent of Disabled."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```

"Path within the volume from which the container's volume should be mounted.\nDefaults to \"\" (volume's root)."

### fn spec.podSets.template.spec.ephemeralContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```

"Expanded path within the volume from which the container's volume should be mounted.\nBehaves similarly to SubPath but environment variable references $(VAR_NAME) are expanded using the container's environment.\nDefaults to \"\" (volume's root).\nSubPathExpr and SubPath are mutually exclusive."

## obj spec.podSets.template.spec.hostAliases

"HostAliases is an optional list of hosts and IPs that will be injected into the pod's hosts\nfile if specified."

### fn spec.podSets.template.spec.hostAliases.withHostnames

```ts
withHostnames(hostnames)
```

"Hostnames for the above IP address."

### fn spec.podSets.template.spec.hostAliases.withHostnamesMixin

```ts
withHostnamesMixin(hostnames)
```

"Hostnames for the above IP address."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.hostAliases.withIp

```ts
withIp(ip)
```

"IP address of the host file entry."

## obj spec.podSets.template.spec.imagePullSecrets

"ImagePullSecrets is an optional list of references to secrets in the same namespace to use for pulling any of the images used by this PodSpec.\nIf specified, these secrets will be passed to individual puller implementations for them to use.\nMore info: https://kubernetes.io/docs/concepts/containers/images#specifying-imagepullsecrets-on-a-pod"

### fn spec.podSets.template.spec.imagePullSecrets.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.initContainers

"List of initialization containers belonging to the pod.\nInit containers are executed in order prior to containers being started. If any\ninit container fails, the pod is considered to have failed and is handled according\nto its restartPolicy. The name for an init container or normal container must be\nunique among all containers.\nInit containers may not have Lifecycle actions, Readiness probes, Liveness probes, or Startup probes.\nThe resourceRequirements of an init container are taken into account during scheduling\nby finding the highest request/limit for each resource type, and then using the max of\nthat value or the sum of the normal containers. Limits are applied to init containers\nin a similar fashion.\nInit containers cannot currently be added or removed.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/init-containers/"

### fn spec.podSets.template.spec.initContainers.withArgs

```ts
withArgs(args)
```

"Arguments to the entrypoint.\nThe container image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.initContainers.withArgsMixin

```ts
withArgsMixin(args)
```

"Arguments to the entrypoint.\nThe container image's CMD is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withCommand

```ts
withCommand(command)
```

"Entrypoint array. Not executed within a shell.\nThe container image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

### fn spec.podSets.template.spec.initContainers.withCommandMixin

```ts
withCommandMixin(command)
```

"Entrypoint array. Not executed within a shell.\nThe container image's ENTRYPOINT is used if this is not provided.\nVariable references $(VAR_NAME) are expanded using the container's environment. If a variable\ncannot be resolved, the reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e. \"$$(VAR_NAME)\" will\nproduce the string literal \"$(VAR_NAME)\". Escaped references will never be expanded, regardless\nof whether the variable exists or not. Cannot be updated.\nMore info: https://kubernetes.io/docs/tasks/inject-data-application/define-command-argument-container/#running-a-command-in-a-shell"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withEnv

```ts
withEnv(env)
```

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withEnvFrom

```ts
withEnvFrom(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withEnvFromMixin

```ts
withEnvFromMixin(envFrom)
```

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withEnvMixin

```ts
withEnvMixin(env)
```

"List of environment variables to set in the container.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withImage

```ts
withImage(image)
```

"Container image name.\nMore info: https://kubernetes.io/docs/concepts/containers/images\nThis field is optional to allow higher level config management to default or override\ncontainer images in workload controllers like Deployments and StatefulSets."

### fn spec.podSets.template.spec.initContainers.withImagePullPolicy

```ts
withImagePullPolicy(imagePullPolicy)
```

"Image pull policy.\nOne of Always, Never, IfNotPresent.\nDefaults to Always if :latest tag is specified, or IfNotPresent otherwise.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/containers/images#updating-images"

### fn spec.podSets.template.spec.initContainers.withName

```ts
withName(name)
```

"Name of the container specified as a DNS_LABEL.\nEach container in a pod must have a unique name (DNS_LABEL).\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withPorts

```ts
withPorts(ports)
```

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withPortsMixin

```ts
withPortsMixin(ports)
```

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withResizePolicy

```ts
withResizePolicy(resizePolicy)
```

"Resources resize policy for the container."

### fn spec.podSets.template.spec.initContainers.withResizePolicyMixin

```ts
withResizePolicyMixin(resizePolicy)
```

"Resources resize policy for the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"RestartPolicy defines the restart behavior of individual containers in a pod.\nThis overrides the pod-level restart policy. When this field is not specified,\nthe restart behavior is defined by the Pod's restart policy and the container type.\nAdditionally, setting the RestartPolicy as \"Always\" for the init container will\nhave the following effect:\nthis init container will be continually restarted on\nexit until all regular containers have terminated. Once all regular\ncontainers have completed, all init containers with restartPolicy \"Always\"\nwill be shut down. This lifecycle differs from normal init containers and\nis often referred to as a \"sidecar\" container. Although this init\ncontainer still starts in the init container sequence, it does not wait\nfor the container to complete before proceeding to the next init\ncontainer. Instead, the next init container starts immediately after this\ninit container is started, or after any startupProbe has successfully\ncompleted."

### fn spec.podSets.template.spec.initContainers.withRestartPolicyRules

```ts
withRestartPolicyRules(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

### fn spec.podSets.template.spec.initContainers.withRestartPolicyRulesMixin

```ts
withRestartPolicyRulesMixin(restartPolicyRules)
```

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withStdin

```ts
withStdin(stdin)
```

"Whether this container should allocate a buffer for stdin in the container runtime. If this\nis not set, reads from stdin in the container will always result in EOF.\nDefault is false."

### fn spec.podSets.template.spec.initContainers.withStdinOnce

```ts
withStdinOnce(stdinOnce)
```

"Whether the container runtime should close the stdin channel after it has been opened by\na single attach. When stdin is true the stdin stream will remain open across multiple attach\nsessions. If stdinOnce is set to true, stdin is opened on container start, is empty until the\nfirst client attaches to stdin, and then remains open and accepts data until the client disconnects,\nat which time stdin is closed and remains closed until the container is restarted. If this\nflag is false, a container processes that reads from stdin will never receive an EOF.\nDefault is false"

### fn spec.podSets.template.spec.initContainers.withTerminationMessagePath

```ts
withTerminationMessagePath(terminationMessagePath)
```

"Optional: Path at which the file to which the container's termination message\nwill be written is mounted into the container's filesystem.\nMessage written is intended to be brief final status, such as an assertion failure message.\nWill be truncated by the node if greater than 4096 bytes. The total message length across\nall containers will be limited to 12kb.\nDefaults to /dev/termination-log.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withTerminationMessagePolicy

```ts
withTerminationMessagePolicy(terminationMessagePolicy)
```

"Indicate how the termination message should be populated. File will use the contents of\nterminationMessagePath to populate the container status message on both success and failure.\nFallbackToLogsOnError will use the last chunk of container log output if the termination\nmessage file is empty and the container exited with an error.\nThe log output is limited to 2048 bytes or 80 lines, whichever is smaller.\nDefaults to File.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withTty

```ts
withTty(tty)
```

"Whether this container should allocate a TTY for itself, also requires 'stdin' to be true.\nDefault is false."

### fn spec.podSets.template.spec.initContainers.withVolumeDevices

```ts
withVolumeDevices(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.initContainers.withVolumeDevicesMixin

```ts
withVolumeDevicesMixin(volumeDevices)
```

"volumeDevices is the list of block devices to be used by the container."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withVolumeMounts

```ts
withVolumeMounts(volumeMounts)
```

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.withVolumeMountsMixin

```ts
withVolumeMountsMixin(volumeMounts)
```

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.withWorkingDir

```ts
withWorkingDir(workingDir)
```

"Container's working directory.\nIf not specified, the container runtime's default will be used, which\nmight be configured in the container image.\nCannot be updated."

## obj spec.podSets.template.spec.initContainers.env

"List of environment variables to set in the container.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.env.withName

```ts
withName(name)
```

"Name of the environment variable.\nMay consist of any printable ASCII characters except '='."

### fn spec.podSets.template.spec.initContainers.env.withValue

```ts
withValue(value)
```

"Variable references $(VAR_NAME) are expanded\nusing the previously defined environment variables in the container and\nany service environment variables. If a variable cannot be resolved,\nthe reference in the input string will be unchanged. Double $$ are reduced\nto a single $, which allows for escaping the $(VAR_NAME) syntax: i.e.\n\"$$(VAR_NAME)\" will produce the string literal \"$(VAR_NAME)\".\nEscaped references will never be expanded, regardless of whether the variable\nexists or not.\nDefaults to \"\"."

## obj spec.podSets.template.spec.initContainers.env.valueFrom

"Source for the environment variable's value. Cannot be used if value is not empty."

## obj spec.podSets.template.spec.initContainers.env.valueFrom.configMapKeyRef

"Selects a key of a ConfigMap."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.configMapKeyRef.withKey

```ts
withKey(key)
```

"The key to select."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.configMapKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.initContainers.env.valueFrom.configMapKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap or its key must be defined"

## obj spec.podSets.template.spec.initContainers.env.valueFrom.fieldRef

"Selects a field of the pod: supports metadata.name, metadata.namespace, `metadata.labels['<KEY>']`, `metadata.annotations['<KEY>']`,\nspec.nodeName, spec.serviceAccountName, status.hostIP, status.podIP, status.podIPs."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"Version of the schema the FieldPath is written in terms of, defaults to \"v1\"."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"Path of the field to select in the specified API version."

## obj spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef

"FileKeyRef selects a key of the env file.\nRequires the EnvFiles feature gate to be enabled."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef.withKey

```ts
withKey(key)
```

"The key within the env file. An invalid key will prevent the pod from starting.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nDuring Alpha stage of the EnvFiles feature gate, the key size is limited to 128 characters."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the file or its key must be defined. If the file or key\ndoes not exist, then the env var is not published.\nIf optional is set to true and the specified key does not exist,\nthe environment variable will not be set in the Pod's containers.\n\nIf optional is set to false and the specified key does not exist,\nan error will be returned during Pod creation."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef.withPath

```ts
withPath(path)
```

"The path within the volume from which to select the file.\nMust be relative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.fileKeyRef.withVolumeName

```ts
withVolumeName(volumeName)
```

"The name of the volume mount containing the env file."

## obj spec.podSets.template.spec.initContainers.env.valueFrom.resourceFieldRef

"Selects a resource of the container: only resources limits and requests\n(limits.cpu, limits.memory, limits.ephemeral-storage, requests.cpu, requests.memory and requests.ephemeral-storage) are currently supported."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```

"Container name: required for volumes, optional for env vars"

### fn spec.podSets.template.spec.initContainers.env.valueFrom.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```

"Specifies the output format of the exposed resources, defaults to \"1\

### fn spec.podSets.template.spec.initContainers.env.valueFrom.resourceFieldRef.withResource

```ts
withResource(resource)
```

"Required: resource to select"

## obj spec.podSets.template.spec.initContainers.env.valueFrom.secretKeyRef

"Selects a key of a secret in the pod's namespace"

### fn spec.podSets.template.spec.initContainers.env.valueFrom.secretKeyRef.withKey

```ts
withKey(key)
```

"The key of the secret to select from.  Must be a valid secret key."

### fn spec.podSets.template.spec.initContainers.env.valueFrom.secretKeyRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.initContainers.env.valueFrom.secretKeyRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret or its key must be defined"

## obj spec.podSets.template.spec.initContainers.envFrom

"List of sources to populate environment variables in the container.\nThe keys defined within a source may consist of any printable ASCII characters except '='.\nWhen a key exists in multiple\nsources, the value associated with the last source will take precedence.\nValues defined by an Env with a duplicate key will take precedence.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.envFrom.withPrefix

```ts
withPrefix(prefix)
```

"Optional text to prepend to the name of each environment variable.\nMay consist of any printable ASCII characters except '='."

## obj spec.podSets.template.spec.initContainers.envFrom.configMapRef

"The ConfigMap to select from"

### fn spec.podSets.template.spec.initContainers.envFrom.configMapRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.initContainers.envFrom.configMapRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the ConfigMap must be defined"

## obj spec.podSets.template.spec.initContainers.envFrom.secretRef

"The Secret to select from"

### fn spec.podSets.template.spec.initContainers.envFrom.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.initContainers.envFrom.secretRef.withOptional

```ts
withOptional(optional)
```

"Specify whether the Secret must be defined"

## obj spec.podSets.template.spec.initContainers.lifecycle

"Actions that the management system should take in response to container lifecycle events.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.lifecycle.withStopSignal

```ts
withStopSignal(stopSignal)
```

"StopSignal defines which signal will be sent to a container when it is being stopped.\nIf not specified, the default is defined by the container runtime in use.\nStopSignal can only be set for Pods with a non-empty .spec.os.name"

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart

"PostStart is called immediately after a container is created. If the handler fails,\nthe container is terminated and restarted according to its restart policy.\nOther management of the container blocks until the hook completes.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.initContainers.lifecycle.postStart.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.initContainers.lifecycle.postStart.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop

"PreStop is called immediately before a container is terminated due to an\nAPI request or management event such as liveness/startup probe failure,\npreemption, resource contention, etc. The handler is not called if the\ncontainer crashes or exits. The Pod's termination grace period countdown begins before the\nPreStop hook is executed. Regardless of the outcome of the handler, the\ncontainer will eventually terminate within the Pod's termination grace\nperiod (unless delayed by finalizers). Other management of the container blocks until the hook completes\nor until the termination grace period is reached.\nMore info: https://kubernetes.io/docs/concepts/containers/container-lifecycle-hooks/#container-hooks"

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop.sleep

"Sleep represents a duration that the container should sleep."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.sleep.withSeconds

```ts
withSeconds(seconds)
```

"Seconds is the number of seconds to sleep."

## obj spec.podSets.template.spec.initContainers.lifecycle.preStop.tcpSocket

"Deprecated. TCPSocket is NOT supported as a LifecycleHandler and kept\nfor backward compatibility. There is no validation of this field and\nlifecycle hooks will fail at runtime when it is specified."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.initContainers.lifecycle.preStop.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.initContainers.livenessProbe

"Periodic probe of container liveness.\nContainer will be restarted if the probe fails.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.livenessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.livenessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.livenessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.livenessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.livenessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.initContainers.livenessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.initContainers.livenessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.initContainers.livenessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.initContainers.livenessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.livenessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.initContainers.livenessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.initContainers.livenessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.initContainers.livenessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.initContainers.livenessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.initContainers.livenessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.initContainers.livenessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.initContainers.livenessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.initContainers.livenessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.initContainers.ports

"List of ports to expose from the container. Not specifying a port here\nDOES NOT prevent that port from being exposed. Any port which is\nlistening on the default \"0.0.0.0\" address inside a container will be\naccessible from the network.\nModifying this array with strategic merge patch may corrupt the data.\nFor more information See https://github.com/kubernetes/kubernetes/issues/108255.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.ports.withContainerPort

```ts
withContainerPort(containerPort)
```

"Number of port to expose on the pod's IP address.\nThis must be a valid port number, 0 < x < 65536."

### fn spec.podSets.template.spec.initContainers.ports.withHostIP

```ts
withHostIP(hostIP)
```

"What host IP to bind the external port to."

### fn spec.podSets.template.spec.initContainers.ports.withHostPort

```ts
withHostPort(hostPort)
```

"Number of port to expose on the host.\nIf specified, this must be a valid port number, 0 < x < 65536.\nIf HostNetwork is specified, this must match ContainerPort.\nMost containers do not need this."

### fn spec.podSets.template.spec.initContainers.ports.withName

```ts
withName(name)
```

"If specified, this must be an IANA_SVC_NAME and unique within the pod. Each\nnamed port in a pod must have a unique name. Name for the port that can be\nreferred to by services."

### fn spec.podSets.template.spec.initContainers.ports.withProtocol

```ts
withProtocol(protocol)
```

"Protocol for port. Must be UDP, TCP, or SCTP.\nDefaults to \"TCP\"."

## obj spec.podSets.template.spec.initContainers.readinessProbe

"Periodic probe of container service readiness.\nContainer will be removed from service endpoints if the probe fails.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.readinessProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.readinessProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.readinessProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.readinessProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.readinessProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.initContainers.readinessProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.initContainers.readinessProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.initContainers.readinessProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.initContainers.readinessProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.readinessProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.initContainers.readinessProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.initContainers.readinessProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.initContainers.readinessProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.initContainers.readinessProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.initContainers.readinessProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.initContainers.readinessProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.initContainers.readinessProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.initContainers.readinessProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.initContainers.resizePolicy

"Resources resize policy for the container."

### fn spec.podSets.template.spec.initContainers.resizePolicy.withResourceName

```ts
withResourceName(resourceName)
```

"Name of the resource to which this resource resize policy applies.\nSupported values: cpu, memory."

### fn spec.podSets.template.spec.initContainers.resizePolicy.withRestartPolicy

```ts
withRestartPolicy(restartPolicy)
```

"Restart policy to apply when specified resource is resized.\nIf not specified, it defaults to NotRequired."

## obj spec.podSets.template.spec.initContainers.resources

"Compute Resources required by this container.\nCannot be updated.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.initContainers.resources.withClaims

```ts
withClaims(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.initContainers.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.initContainers.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.initContainers.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.resources.claims

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.initContainers.resources.claims.withName

```ts
withName(name)
```

"Name must match the name of one entry in pod.spec.resourceClaims of\nthe Pod where this field is used. It makes that resource available\ninside a container."

### fn spec.podSets.template.spec.initContainers.resources.claims.withRequest

```ts
withRequest(request)
```

"Request is the name chosen for a request in the referenced claim.\nIf empty, everything from the claim is made available, otherwise\nonly the result of this request."

## obj spec.podSets.template.spec.initContainers.restartPolicyRules

"Represents a list of rules to be checked to determine if the\ncontainer should be restarted on exit. The rules are evaluated in\norder. Once a rule matches a container exit condition, the remaining\nrules are ignored. If no rule matches the container exit condition,\nthe Container-level restart policy determines the whether the container\nis restarted or not. Constraints on the rules:\n- At most 20 rules are allowed.\n- Rules can have the same action.\n- Identical rules are not forbidden in validations.\nWhen rules are specified, container MUST set RestartPolicy explicitly\neven it if matches the Pod's RestartPolicy."

### fn spec.podSets.template.spec.initContainers.restartPolicyRules.withAction

```ts
withAction(action)
```

"Specifies the action taken on a container exit if the requirements\nare satisfied. The only possible value is \"Restart\" to restart the\ncontainer."

## obj spec.podSets.template.spec.initContainers.restartPolicyRules.exitCodes

"Represents the exit codes to check on container exits."

### fn spec.podSets.template.spec.initContainers.restartPolicyRules.exitCodes.withOperator

```ts
withOperator(operator)
```

"Represents the relationship between the container exit code(s) and the\nspecified values. Possible values are:\n- In: the requirement is satisfied if the container exit code is in the\n  set of specified values.\n- NotIn: the requirement is satisfied if the container exit code is\n  not in the set of specified values."

### fn spec.podSets.template.spec.initContainers.restartPolicyRules.exitCodes.withValues

```ts
withValues(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

### fn spec.podSets.template.spec.initContainers.restartPolicyRules.exitCodes.withValuesMixin

```ts
withValuesMixin(values)
```

"Specifies the set of values to check for container exit codes.\nAt most 255 elements are allowed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.securityContext

"SecurityContext defines the security options the container should be run with.\nIf set, the fields of SecurityContext override the equivalent fields of PodSecurityContext.\nMore info: https://kubernetes.io/docs/tasks/configure-pod-container/security-context/"

### fn spec.podSets.template.spec.initContainers.securityContext.withAllowPrivilegeEscalation

```ts
withAllowPrivilegeEscalation(allowPrivilegeEscalation)
```

"AllowPrivilegeEscalation controls whether a process can gain more\nprivileges than its parent process. This bool directly controls if\nthe no_new_privs flag will be set on the container process.\nAllowPrivilegeEscalation is true always when the container is:\n1) run as Privileged\n2) has CAP_SYS_ADMIN\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.withPrivileged

```ts
withPrivileged(privileged)
```

"Run container in privileged mode.\nProcesses in privileged containers are essentially equivalent to root on the host.\nDefaults to false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.withProcMount

```ts
withProcMount(procMount)
```

"procMount denotes the type of proc mount to use for the containers.\nThe default value is Default which uses the container runtime defaults for\nreadonly paths and masked paths.\nThis requires the ProcMountType feature flag to be enabled.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.withReadOnlyRootFilesystem

```ts
withReadOnlyRootFilesystem(readOnlyRootFilesystem)
```

"Whether this container has a read-only root filesystem.\nDefault is false.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```

"The GID to run the entrypoint of the container process.\nUses runtime default if unset.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```

"Indicates that the container must run as a non-root user.\nIf true, the Kubelet will validate the image at runtime to ensure that it\ndoes not run as UID 0 (root) and fail to start the container if it does.\nIf unset or false, no such validation will be performed.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

### fn spec.podSets.template.spec.initContainers.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```

"The UID to run the entrypoint of the container process.\nDefaults to user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

## obj spec.podSets.template.spec.initContainers.securityContext.appArmorProfile

"appArmorProfile is the AppArmor options to use by this container. If set, this profile\noverrides the pod's appArmorProfile.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile loaded on the node that should be used.\nThe profile must be preconfigured on the node to work.\nMust match the loaded name of the profile.\nMust be set if and only if type is \"Localhost\"."

### fn spec.podSets.template.spec.initContainers.securityContext.appArmorProfile.withType

```ts
withType(type)
```

"type indicates which kind of AppArmor profile will be applied.\nValid options are:\n  Localhost - a profile pre-loaded on the node.\n  RuntimeDefault - the container runtime's default profile.\n  Unconfined - no AppArmor enforcement."

## obj spec.podSets.template.spec.initContainers.securityContext.capabilities

"The capabilities to add/drop when running containers.\nDefaults to the default set of capabilities granted by the container runtime.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.capabilities.withAdd

```ts
withAdd(add)
```

"Added capabilities"

### fn spec.podSets.template.spec.initContainers.securityContext.capabilities.withAddMixin

```ts
withAddMixin(add)
```

"Added capabilities"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.securityContext.capabilities.withDrop

```ts
withDrop(drop)
```

"Removed capabilities"

### fn spec.podSets.template.spec.initContainers.securityContext.capabilities.withDropMixin

```ts
withDropMixin(drop)
```

"Removed capabilities"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions

"The SELinux context to be applied to the container.\nIf unspecified, the container runtime will allocate a random SELinux context for each\ncontainer.  May also be set in PodSecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```

"Level is SELinux level label that applies to the container."

### fn spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```

"Role is a SELinux role label that applies to the container."

### fn spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions.withType

```ts
withType(type)
```

"Type is a SELinux type label that applies to the container."

### fn spec.podSets.template.spec.initContainers.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```

"User is a SELinux user label that applies to the container."

## obj spec.podSets.template.spec.initContainers.securityContext.seccompProfile

"The seccomp options to use by this container. If seccomp options are\nprovided at both the pod & container level, the container options\noverride the pod options.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.initContainers.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile defined in a file on the node should be used.\nThe profile must be preconfigured on the node to work.\nMust be a descending path, relative to the kubelet's configured seccomp profile location.\nMust be set if type is \"Localhost\". Must NOT be set for any other type."

### fn spec.podSets.template.spec.initContainers.securityContext.seccompProfile.withType

```ts
withType(type)
```

"type indicates which kind of seccomp profile will be applied.\nValid options are:\n\nLocalhost - a profile defined in a file on the node should be used.\nRuntimeDefault - the container runtime default profile should be used.\nUnconfined - no profile should be applied."

## obj spec.podSets.template.spec.initContainers.securityContext.windowsOptions

"The Windows specific settings applied to all containers.\nIf unspecified, the options from the PodSecurityContext will be used.\nIf set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is linux."

### fn spec.podSets.template.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```

"GMSACredentialSpec is where the GMSA admission webhook\n(https://github.com/kubernetes-sigs/windows-gmsa) inlines the contents of the\nGMSA credential spec named by the GMSACredentialSpecName field."

### fn spec.podSets.template.spec.initContainers.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```

"GMSACredentialSpecName is the name of the GMSA credential spec to use."

### fn spec.podSets.template.spec.initContainers.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```

"HostProcess determines if a container should be run as a 'Host Process' container.\nAll of a Pod's containers must have the same effective HostProcess value\n(it is not allowed to have a mix of HostProcess containers and non-HostProcess containers).\nIn addition, if HostProcess is true then HostNetwork must also be set to true."

### fn spec.podSets.template.spec.initContainers.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```

"The UserName in Windows to run the entrypoint of the container process.\nDefaults to the user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext. If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

## obj spec.podSets.template.spec.initContainers.startupProbe

"StartupProbe indicates that the Pod has successfully initialized.\nIf specified, no other probes are executed until this completes successfully.\nIf this probe fails, the Pod will be restarted, just as if the livenessProbe failed.\nThis can be used to provide different probe parameters at the beginning of a Pod's lifecycle,\nwhen it might take a long time to load data or warm a cache, than during steady-state operation.\nThis cannot be updated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.startupProbe.withFailureThreshold

```ts
withFailureThreshold(failureThreshold)
```

"Minimum consecutive failures for the probe to be considered failed after having succeeded.\nDefaults to 3. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.startupProbe.withInitialDelaySeconds

```ts
withInitialDelaySeconds(initialDelaySeconds)
```

"Number of seconds after the container has started before liveness probes are initiated.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

### fn spec.podSets.template.spec.initContainers.startupProbe.withPeriodSeconds

```ts
withPeriodSeconds(periodSeconds)
```

"How often (in seconds) to perform the probe.\nDefault to 10 seconds. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.startupProbe.withSuccessThreshold

```ts
withSuccessThreshold(successThreshold)
```

"Minimum consecutive successes for the probe to be considered successful after having failed.\nDefaults to 1. Must be 1 for liveness and startup. Minimum value is 1."

### fn spec.podSets.template.spec.initContainers.startupProbe.withTerminationGracePeriodSeconds

```ts
withTerminationGracePeriodSeconds(terminationGracePeriodSeconds)
```

"Optional duration in seconds the pod needs to terminate gracefully upon probe failure.\nThe grace period is the duration in seconds after the processes running in the pod are sent\na termination signal and the time when the processes are forcibly halted with a kill signal.\nSet this value longer than the expected cleanup time for your process.\nIf this value is nil, the pod's terminationGracePeriodSeconds will be used. Otherwise, this\nvalue overrides the value provided by the pod spec.\nValue must be non-negative integer. The value zero indicates stop immediately via\nthe kill signal (no opportunity to shut down).\nThis is a beta field and requires enabling ProbeTerminationGracePeriod feature gate.\nMinimum value is 1. spec.terminationGracePeriodSeconds is used if unset."

### fn spec.podSets.template.spec.initContainers.startupProbe.withTimeoutSeconds

```ts
withTimeoutSeconds(timeoutSeconds)
```

"Number of seconds after which the probe times out.\nDefaults to 1 second. Minimum value is 1.\nMore info: https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle#container-probes"

## obj spec.podSets.template.spec.initContainers.startupProbe.exec

"Exec specifies a command to execute in the container."

### fn spec.podSets.template.spec.initContainers.startupProbe.exec.withCommand

```ts
withCommand(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

### fn spec.podSets.template.spec.initContainers.startupProbe.exec.withCommandMixin

```ts
withCommandMixin(command)
```

"Command is the command line to execute inside the container, the working directory for the\ncommand  is root ('/') in the container's filesystem. The command is simply exec'd, it is\nnot run inside a shell, so traditional shell instructions ('|', etc) won't work. To use\na shell, you need to explicitly call out to that shell.\nExit status of 0 is treated as live/healthy and non-zero is unhealthy."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.initContainers.startupProbe.grpc

"GRPC specifies a GRPC HealthCheckRequest."

### fn spec.podSets.template.spec.initContainers.startupProbe.grpc.withPort

```ts
withPort(port)
```

"Port number of the gRPC service. Number must be in the range 1 to 65535."

### fn spec.podSets.template.spec.initContainers.startupProbe.grpc.withService

```ts
withService(service)
```

"Service is the name of the service to place in the gRPC HealthCheckRequest\n(see https://github.com/grpc/grpc/blob/master/doc/health-checking.md).\n\nIf this is not specified, the default behavior is defined by gRPC."

## obj spec.podSets.template.spec.initContainers.startupProbe.httpGet

"HTTPGet specifies an HTTP GET request to perform."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withHost

```ts
withHost(host)
```

"Host name to connect to, defaults to the pod IP. You probably want to set\n\"Host\" in httpHeaders instead."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withHttpHeaders

```ts
withHttpHeaders(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withHttpHeadersMixin

```ts
withHttpHeadersMixin(httpHeaders)
```

"Custom headers to set in the request. HTTP allows repeated headers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withPath

```ts
withPath(path)
```

"Path to access on the HTTP server."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withPort

```ts
withPort(port)
```

"Name or number of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.withScheme

```ts
withScheme(scheme)
```

"Scheme to use for connecting to the host.\nDefaults to HTTP."

## obj spec.podSets.template.spec.initContainers.startupProbe.httpGet.httpHeaders

"Custom headers to set in the request. HTTP allows repeated headers."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.httpHeaders.withName

```ts
withName(name)
```

"The header field name.\nThis will be canonicalized upon output, so case-variant names will be understood as the same header."

### fn spec.podSets.template.spec.initContainers.startupProbe.httpGet.httpHeaders.withValue

```ts
withValue(value)
```

"The header field value"

## obj spec.podSets.template.spec.initContainers.startupProbe.tcpSocket

"TCPSocket specifies a connection to a TCP port."

### fn spec.podSets.template.spec.initContainers.startupProbe.tcpSocket.withHost

```ts
withHost(host)
```

"Optional: Host name to connect to, defaults to the pod IP."

### fn spec.podSets.template.spec.initContainers.startupProbe.tcpSocket.withPort

```ts
withPort(port)
```

"Number or name of the port to access on the container.\nNumber must be in the range 1 to 65535.\nName must be an IANA_SVC_NAME."

## obj spec.podSets.template.spec.initContainers.volumeDevices

"volumeDevices is the list of block devices to be used by the container."

### fn spec.podSets.template.spec.initContainers.volumeDevices.withDevicePath

```ts
withDevicePath(devicePath)
```

"devicePath is the path inside of the container that the device will be mapped to."

### fn spec.podSets.template.spec.initContainers.volumeDevices.withName

```ts
withName(name)
```

"name must match the name of a persistentVolumeClaim in the pod"

## obj spec.podSets.template.spec.initContainers.volumeMounts

"Pod volumes to mount into the container's filesystem.\nCannot be updated."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withMountPath

```ts
withMountPath(mountPath)
```

"Path within the container at which the volume should be mounted.  Must\nnot contain ':'."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withMountPropagation

```ts
withMountPropagation(mountPropagation)
```

"mountPropagation determines how mounts are propagated from the host\nto container and the other way around.\nWhen not set, MountPropagationNone is used.\nThis field is beta in 1.10.\nWhen RecursiveReadOnly is set to IfPossible or to Enabled, MountPropagation must be None or unspecified\n(which defaults to None)."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withName

```ts
withName(name)
```

"This must match the Name of a Volume."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withReadOnly

```ts
withReadOnly(readOnly)
```

"Mounted read-only if true, read-write otherwise (false or unspecified).\nDefaults to false."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withRecursiveReadOnly

```ts
withRecursiveReadOnly(recursiveReadOnly)
```

"RecursiveReadOnly specifies whether read-only mounts should be handled\nrecursively.\n\nIf ReadOnly is false, this field has no meaning and must be unspecified.\n\nIf ReadOnly is true, and this field is set to Disabled, the mount is not made\nrecursively read-only.  If this field is set to IfPossible, the mount is made\nrecursively read-only, if it is supported by the container runtime.  If this\nfield is set to Enabled, the mount is made recursively read-only if it is\nsupported by the container runtime, otherwise the pod will not be started and\nan error will be generated to indicate the reason.\n\nIf this field is set to IfPossible or Enabled, MountPropagation must be set to\nNone (or be unspecified, which defaults to None).\n\nIf this field is not specified, it is treated as an equivalent of Disabled."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withSubPath

```ts
withSubPath(subPath)
```

"Path within the volume from which the container's volume should be mounted.\nDefaults to \"\" (volume's root)."

### fn spec.podSets.template.spec.initContainers.volumeMounts.withSubPathExpr

```ts
withSubPathExpr(subPathExpr)
```

"Expanded path within the volume from which the container's volume should be mounted.\nBehaves similarly to SubPath but environment variable references $(VAR_NAME) are expanded using the container's environment.\nDefaults to \"\" (volume's root).\nSubPathExpr and SubPath are mutually exclusive."

## obj spec.podSets.template.spec.os

"Specifies the OS of the containers in the pod.\nSome pod and container fields are restricted if this is set.\n\nIf the OS field is set to linux, the following fields must be unset:\n-securityContext.windowsOptions\n\nIf the OS field is set to windows, following fields must be unset:\n- spec.hostPID\n- spec.hostIPC\n- spec.hostUsers\n- spec.resources\n- spec.securityContext.appArmorProfile\n- spec.securityContext.seLinuxOptions\n- spec.securityContext.seccompProfile\n- spec.securityContext.fsGroup\n- spec.securityContext.fsGroupChangePolicy\n- spec.securityContext.sysctls\n- spec.shareProcessNamespace\n- spec.securityContext.runAsUser\n- spec.securityContext.runAsGroup\n- spec.securityContext.supplementalGroups\n- spec.securityContext.supplementalGroupsPolicy\n- spec.containers[*].securityContext.appArmorProfile\n- spec.containers[*].securityContext.seLinuxOptions\n- spec.containers[*].securityContext.seccompProfile\n- spec.containers[*].securityContext.capabilities\n- spec.containers[*].securityContext.readOnlyRootFilesystem\n- spec.containers[*].securityContext.privileged\n- spec.containers[*].securityContext.allowPrivilegeEscalation\n- spec.containers[*].securityContext.procMount\n- spec.containers[*].securityContext.runAsUser\n- spec.containers[*].securityContext.runAsGroup"

### fn spec.podSets.template.spec.os.withName

```ts
withName(name)
```

"Name is the name of the operating system. The currently supported values are linux and windows.\nAdditional value may be defined in future and can be one of:\nhttps://github.com/opencontainers/runtime-spec/blob/master/config.md#platform-specific-configuration\nClients should expect to handle additional values and treat unrecognized values in this field as os: null"

## obj spec.podSets.template.spec.readinessGates

"If specified, all readiness gates will be evaluated for pod readiness.\nA pod is ready when all its containers are ready AND\nall conditions specified in the readiness gates have status equal to \"True\"\nMore info: https://git.k8s.io/enhancements/keps/sig-network/580-pod-readiness-gates"

### fn spec.podSets.template.spec.readinessGates.withConditionType

```ts
withConditionType(conditionType)
```

"ConditionType refers to a condition in the pod's condition list with matching type."

## obj spec.podSets.template.spec.resourceClaims

"ResourceClaims defines which ResourceClaims must be allocated\nand reserved before the Pod is allowed to start. The resources\nwill be made available to those containers which consume them\nby name.\n\nThis is an alpha field and requires enabling the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable."

### fn spec.podSets.template.spec.resourceClaims.withName

```ts
withName(name)
```

"Name uniquely identifies this resource claim inside the pod.\nThis must be a DNS_LABEL."

### fn spec.podSets.template.spec.resourceClaims.withResourceClaimName

```ts
withResourceClaimName(resourceClaimName)
```

"ResourceClaimName is the name of a ResourceClaim object in the same\nnamespace as this pod.\n\nExactly one of ResourceClaimName and ResourceClaimTemplateName must\nbe set."

### fn spec.podSets.template.spec.resourceClaims.withResourceClaimTemplateName

```ts
withResourceClaimTemplateName(resourceClaimTemplateName)
```

"ResourceClaimTemplateName is the name of a ResourceClaimTemplate\nobject in the same namespace as this pod.\n\nThe template will be used to create a new ResourceClaim, which will\nbe bound to this pod. When this pod is deleted, the ResourceClaim\nwill also be deleted. The pod name and resource name, along with a\ngenerated component, will be used to form a unique name for the\nResourceClaim, which will be recorded in pod.status.resourceClaimStatuses.\n\nThis field is immutable and no changes will be made to the\ncorresponding ResourceClaim by the control plane after creating the\nResourceClaim.\n\nExactly one of ResourceClaimName and ResourceClaimTemplateName must\nbe set."

## obj spec.podSets.template.spec.resources

"Resources is the total amount of CPU and Memory resources required by all\ncontainers in the pod. It supports specifying Requests and Limits for\n\"cpu\", \"memory\" and \"hugepages-\" resource names only. ResourceClaims are not supported.\n\nThis field enables fine-grained control over resource allocation for the\nentire pod, allowing resource sharing among containers in a pod.\n\nThis is an alpha field and requires enabling the PodLevelResources feature\ngate."

### fn spec.podSets.template.spec.resources.withClaims

```ts
withClaims(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.resources.withClaimsMixin

```ts
withClaimsMixin(claims)
```

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.resources.claims

"Claims lists the names of resources, defined in spec.resourceClaims,\nthat are used by this container.\n\nThis field depends on the\nDynamicResourceAllocation feature gate.\n\nThis field is immutable. It can only be set for containers."

### fn spec.podSets.template.spec.resources.claims.withName

```ts
withName(name)
```

"Name must match the name of one entry in pod.spec.resourceClaims of\nthe Pod where this field is used. It makes that resource available\ninside a container."

### fn spec.podSets.template.spec.resources.claims.withRequest

```ts
withRequest(request)
```

"Request is the name chosen for a request in the referenced claim.\nIf empty, everything from the claim is made available, otherwise\nonly the result of this request."

## obj spec.podSets.template.spec.schedulingGates

"SchedulingGates is an opaque list of values that if specified will block scheduling the pod.\nIf schedulingGates is not empty, the pod will stay in the SchedulingGated state and the\nscheduler will not attempt to schedule the pod.\n\nSchedulingGates can only be set at pod creation time, and be removed only afterwards."

### fn spec.podSets.template.spec.schedulingGates.withName

```ts
withName(name)
```

"Name of the scheduling gate.\nEach scheduling gate must have a unique name field."

## obj spec.podSets.template.spec.securityContext

"SecurityContext holds pod-level security attributes and common container settings.\nOptional: Defaults to empty.  See type description for default values of each field."

### fn spec.podSets.template.spec.securityContext.withFsGroup

```ts
withFsGroup(fsGroup)
```

"A special supplemental group that applies to all containers in a pod.\nSome volume types allow the Kubelet to change the ownership of that volume\nto be owned by the pod:\n\n1. The owning GID will be the FSGroup\n2. The setgid bit is set (new files created in the volume will be owned by FSGroup)\n3. The permission bits are OR'd with rw-rw----\n\nIf unset, the Kubelet will not modify the ownership and permissions of any volume.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withFsGroupChangePolicy

```ts
withFsGroupChangePolicy(fsGroupChangePolicy)
```

"fsGroupChangePolicy defines behavior of changing ownership and permission of the volume\nbefore being exposed inside Pod. This field will only apply to\nvolume types which support fsGroup based ownership(and permissions).\nIt will have no effect on ephemeral volume types such as: secret, configmaps\nand emptydir.\nValid values are \"OnRootMismatch\" and \"Always\". If not specified, \"Always\" is used.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withRunAsGroup

```ts
withRunAsGroup(runAsGroup)
```

"The GID to run the entrypoint of the container process.\nUses runtime default if unset.\nMay also be set in SecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence\nfor that container.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withRunAsNonRoot

```ts
withRunAsNonRoot(runAsNonRoot)
```

"Indicates that the container must run as a non-root user.\nIf true, the Kubelet will validate the image at runtime to ensure that it\ndoes not run as UID 0 (root) and fail to start the container if it does.\nIf unset or false, no such validation will be performed.\nMay also be set in SecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

### fn spec.podSets.template.spec.securityContext.withRunAsUser

```ts
withRunAsUser(runAsUser)
```

"The UID to run the entrypoint of the container process.\nDefaults to user specified in image metadata if unspecified.\nMay also be set in SecurityContext.  If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence\nfor that container.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withSeLinuxChangePolicy

```ts
withSeLinuxChangePolicy(seLinuxChangePolicy)
```

"seLinuxChangePolicy defines how the container's SELinux label is applied to all volumes used by the Pod.\nIt has no effect on nodes that do not support SELinux or to volumes does not support SELinux.\nValid values are \"MountOption\" and \"Recursive\".\n\n\"Recursive\" means relabeling of all files on all Pod volumes by the container runtime.\nThis may be slow for large volumes, but allows mixing privileged and unprivileged Pods sharing the same volume on the same node.\n\n\"MountOption\" mounts all eligible Pod volumes with `-o context` mount option.\nThis requires all Pods that share the same volume to use the same SELinux label.\nIt is not possible to share the same volume among privileged and unprivileged Pods.\nEligible volumes are in-tree FibreChannel and iSCSI volumes, and all CSI volumes\nwhose CSI driver announces SELinux support by setting spec.seLinuxMount: true in their\nCSIDriver instance. Other volumes are always re-labelled recursively.\n\"MountOption\" value is allowed only when SELinuxMount feature gate is enabled.\n\nIf not specified and SELinuxMount feature gate is enabled, \"MountOption\" is used.\nIf not specified and SELinuxMount feature gate is disabled, \"MountOption\" is used for ReadWriteOncePod volumes\nand \"Recursive\" for all other volumes.\n\nThis field affects only Pods that have SELinux label set, either in PodSecurityContext or in SecurityContext of all containers.\n\nAll Pods that use the same volume should use the same seLinuxChangePolicy, otherwise some pods can get stuck in ContainerCreating state.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withSupplementalGroups

```ts
withSupplementalGroups(supplementalGroups)
```

"A list of groups applied to the first process run in each container, in\naddition to the container's primary GID and fsGroup (if specified).  If\nthe SupplementalGroupsPolicy feature is enabled, the\nsupplementalGroupsPolicy field determines whether these are in addition\nto or instead of any group memberships defined in the container image.\nIf unspecified, no additional groups are added, though group memberships\ndefined in the container image may still be used, depending on the\nsupplementalGroupsPolicy field.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withSupplementalGroupsMixin

```ts
withSupplementalGroupsMixin(supplementalGroups)
```

"A list of groups applied to the first process run in each container, in\naddition to the container's primary GID and fsGroup (if specified).  If\nthe SupplementalGroupsPolicy feature is enabled, the\nsupplementalGroupsPolicy field determines whether these are in addition\nto or instead of any group memberships defined in the container image.\nIf unspecified, no additional groups are added, though group memberships\ndefined in the container image may still be used, depending on the\nsupplementalGroupsPolicy field.\nNote that this field cannot be set when spec.os.name is windows."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.securityContext.withSupplementalGroupsPolicy

```ts
withSupplementalGroupsPolicy(supplementalGroupsPolicy)
```

"Defines how supplemental groups of the first container processes are calculated.\nValid values are \"Merge\" and \"Strict\". If not specified, \"Merge\" is used.\n(Alpha) Using the field requires the SupplementalGroupsPolicy feature gate to be enabled\nand the container runtime must implement support for this feature.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withSysctls

```ts
withSysctls(sysctls)
```

"Sysctls hold a list of namespaced sysctls used for the pod. Pods with unsupported\nsysctls (by the container runtime) might fail to launch.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.withSysctlsMixin

```ts
withSysctlsMixin(sysctls)
```

"Sysctls hold a list of namespaced sysctls used for the pod. Pods with unsupported\nsysctls (by the container runtime) might fail to launch.\nNote that this field cannot be set when spec.os.name is windows."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.securityContext.appArmorProfile

"appArmorProfile is the AppArmor options to use by the containers in this pod.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.appArmorProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile loaded on the node that should be used.\nThe profile must be preconfigured on the node to work.\nMust match the loaded name of the profile.\nMust be set if and only if type is \"Localhost\"."

### fn spec.podSets.template.spec.securityContext.appArmorProfile.withType

```ts
withType(type)
```

"type indicates which kind of AppArmor profile will be applied.\nValid options are:\n  Localhost - a profile pre-loaded on the node.\n  RuntimeDefault - the container runtime's default profile.\n  Unconfined - no AppArmor enforcement."

## obj spec.podSets.template.spec.securityContext.seLinuxOptions

"The SELinux context to be applied to all containers.\nIf unspecified, the container runtime will allocate a random SELinux context for each\ncontainer.  May also be set in SecurityContext.  If set in\nboth SecurityContext and PodSecurityContext, the value specified in SecurityContext\ntakes precedence for that container.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.seLinuxOptions.withLevel

```ts
withLevel(level)
```

"Level is SELinux level label that applies to the container."

### fn spec.podSets.template.spec.securityContext.seLinuxOptions.withRole

```ts
withRole(role)
```

"Role is a SELinux role label that applies to the container."

### fn spec.podSets.template.spec.securityContext.seLinuxOptions.withType

```ts
withType(type)
```

"Type is a SELinux type label that applies to the container."

### fn spec.podSets.template.spec.securityContext.seLinuxOptions.withUser

```ts
withUser(user)
```

"User is a SELinux user label that applies to the container."

## obj spec.podSets.template.spec.securityContext.seccompProfile

"The seccomp options to use by the containers in this pod.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.seccompProfile.withLocalhostProfile

```ts
withLocalhostProfile(localhostProfile)
```

"localhostProfile indicates a profile defined in a file on the node should be used.\nThe profile must be preconfigured on the node to work.\nMust be a descending path, relative to the kubelet's configured seccomp profile location.\nMust be set if type is \"Localhost\". Must NOT be set for any other type."

### fn spec.podSets.template.spec.securityContext.seccompProfile.withType

```ts
withType(type)
```

"type indicates which kind of seccomp profile will be applied.\nValid options are:\n\nLocalhost - a profile defined in a file on the node should be used.\nRuntimeDefault - the container runtime default profile should be used.\nUnconfined - no profile should be applied."

## obj spec.podSets.template.spec.securityContext.sysctls

"Sysctls hold a list of namespaced sysctls used for the pod. Pods with unsupported\nsysctls (by the container runtime) might fail to launch.\nNote that this field cannot be set when spec.os.name is windows."

### fn spec.podSets.template.spec.securityContext.sysctls.withName

```ts
withName(name)
```

"Name of a property to set"

### fn spec.podSets.template.spec.securityContext.sysctls.withValue

```ts
withValue(value)
```

"Value of a property to set"

## obj spec.podSets.template.spec.securityContext.windowsOptions

"The Windows specific settings applied to all containers.\nIf unspecified, the options within a container's SecurityContext will be used.\nIf set in both SecurityContext and PodSecurityContext, the value specified in SecurityContext takes precedence.\nNote that this field cannot be set when spec.os.name is linux."

### fn spec.podSets.template.spec.securityContext.windowsOptions.withGmsaCredentialSpec

```ts
withGmsaCredentialSpec(gmsaCredentialSpec)
```

"GMSACredentialSpec is where the GMSA admission webhook\n(https://github.com/kubernetes-sigs/windows-gmsa) inlines the contents of the\nGMSA credential spec named by the GMSACredentialSpecName field."

### fn spec.podSets.template.spec.securityContext.windowsOptions.withGmsaCredentialSpecName

```ts
withGmsaCredentialSpecName(gmsaCredentialSpecName)
```

"GMSACredentialSpecName is the name of the GMSA credential spec to use."

### fn spec.podSets.template.spec.securityContext.windowsOptions.withHostProcess

```ts
withHostProcess(hostProcess)
```

"HostProcess determines if a container should be run as a 'Host Process' container.\nAll of a Pod's containers must have the same effective HostProcess value\n(it is not allowed to have a mix of HostProcess containers and non-HostProcess containers).\nIn addition, if HostProcess is true then HostNetwork must also be set to true."

### fn spec.podSets.template.spec.securityContext.windowsOptions.withRunAsUserName

```ts
withRunAsUserName(runAsUserName)
```

"The UserName in Windows to run the entrypoint of the container process.\nDefaults to the user specified in image metadata if unspecified.\nMay also be set in PodSecurityContext. If set in both SecurityContext and\nPodSecurityContext, the value specified in SecurityContext takes precedence."

## obj spec.podSets.template.spec.tolerations

"If specified, the pod's tolerations."

### fn spec.podSets.template.spec.tolerations.withEffect

```ts
withEffect(effect)
```

"Effect indicates the taint effect to match. Empty means match all taint effects.\nWhen specified, allowed values are NoSchedule, PreferNoSchedule and NoExecute."

### fn spec.podSets.template.spec.tolerations.withKey

```ts
withKey(key)
```

"Key is the taint key that the toleration applies to. Empty means match all taint keys.\nIf the key is empty, operator must be Exists; this combination means to match all values and all keys."

### fn spec.podSets.template.spec.tolerations.withOperator

```ts
withOperator(operator)
```

"Operator represents a key's relationship to the value.\nValid operators are Exists and Equal. Defaults to Equal.\nExists is equivalent to wildcard for value, so that a pod can\ntolerate all taints of a particular category."

### fn spec.podSets.template.spec.tolerations.withTolerationSeconds

```ts
withTolerationSeconds(tolerationSeconds)
```

"TolerationSeconds represents the period of time the toleration (which must be\nof effect NoExecute, otherwise this field is ignored) tolerates the taint. By default,\nit is not set, which means tolerate the taint forever (do not evict). Zero and\nnegative values will be treated as 0 (evict immediately) by the system."

### fn spec.podSets.template.spec.tolerations.withValue

```ts
withValue(value)
```

"Value is the taint value the toleration matches to.\nIf the operator is Exists, the value should be empty, otherwise just a regular string."

## obj spec.podSets.template.spec.topologySpreadConstraints

"TopologySpreadConstraints describes how a group of pods ought to spread across topology\ndomains. Scheduler will schedule pods in a way which abides by the constraints.\nAll topologySpreadConstraints are ANDed."

### fn spec.podSets.template.spec.topologySpreadConstraints.withMatchLabelKeys

```ts
withMatchLabelKeys(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select the pods over which\nspreading will be calculated. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are ANDed with labelSelector\nto select the group of existing pods over which spreading will be calculated\nfor the incoming pod. The same key is forbidden to exist in both MatchLabelKeys and LabelSelector.\nMatchLabelKeys cannot be set when LabelSelector isn't set.\nKeys that don't exist in the incoming pod labels will\nbe ignored. A null or empty list means only match against labelSelector.\n\nThis is a beta field and requires the MatchLabelKeysInPodTopologySpread feature gate to be enabled (enabled by default)."

### fn spec.podSets.template.spec.topologySpreadConstraints.withMatchLabelKeysMixin

```ts
withMatchLabelKeysMixin(matchLabelKeys)
```

"MatchLabelKeys is a set of pod label keys to select the pods over which\nspreading will be calculated. The keys are used to lookup values from the\nincoming pod labels, those key-value labels are ANDed with labelSelector\nto select the group of existing pods over which spreading will be calculated\nfor the incoming pod. The same key is forbidden to exist in both MatchLabelKeys and LabelSelector.\nMatchLabelKeys cannot be set when LabelSelector isn't set.\nKeys that don't exist in the incoming pod labels will\nbe ignored. A null or empty list means only match against labelSelector.\n\nThis is a beta field and requires the MatchLabelKeysInPodTopologySpread feature gate to be enabled (enabled by default)."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.topologySpreadConstraints.withMaxSkew

```ts
withMaxSkew(maxSkew)
```

"MaxSkew describes the degree to which pods may be unevenly distributed.\nWhen `whenUnsatisfiable=DoNotSchedule`, it is the maximum permitted difference\nbetween the number of matching pods in the target topology and the global minimum.\nThe global minimum is the minimum number of matching pods in an eligible domain\nor zero if the number of eligible domains is less than MinDomains.\nFor example, in a 3-zone cluster, MaxSkew is set to 1, and pods with the same\nlabelSelector spread as 2/2/1:\nIn this case, the global minimum is 1.\n| zone1 | zone2 | zone3 |\n|  P P  |  P P  |   P   |\n- if MaxSkew is 1, incoming pod can only be scheduled to zone3 to become 2/2/2;\nscheduling it onto zone1(zone2) would make the ActualSkew(3-1) on zone1(zone2)\nviolate MaxSkew(1).\n- if MaxSkew is 2, incoming pod can be scheduled onto any zone.\nWhen `whenUnsatisfiable=ScheduleAnyway`, it is used to give higher precedence\nto topologies that satisfy it.\nIt's a required field. Default value is 1 and 0 is not allowed."

### fn spec.podSets.template.spec.topologySpreadConstraints.withMinDomains

```ts
withMinDomains(minDomains)
```

"MinDomains indicates a minimum number of eligible domains.\nWhen the number of eligible domains with matching topology keys is less than minDomains,\nPod Topology Spread treats \"global minimum\" as 0, and then the calculation of Skew is performed.\nAnd when the number of eligible domains with matching topology keys equals or greater than minDomains,\nthis value has no effect on scheduling.\nAs a result, when the number of eligible domains is less than minDomains,\nscheduler won't schedule more than maxSkew Pods to those domains.\nIf value is nil, the constraint behaves as if MinDomains is equal to 1.\nValid values are integers greater than 0.\nWhen value is not nil, WhenUnsatisfiable must be DoNotSchedule.\n\nFor example, in a 3-zone cluster, MaxSkew is set to 2, MinDomains is set to 5 and pods with the same\nlabelSelector spread as 2/2/2:\n| zone1 | zone2 | zone3 |\n|  P P  |  P P  |  P P  |\nThe number of domains is less than 5(MinDomains), so \"global minimum\" is treated as 0.\nIn this situation, new pod with the same labelSelector cannot be scheduled,\nbecause computed skew will be 3(3 - 0) if new Pod is scheduled to any of the three zones,\nit will violate MaxSkew."

### fn spec.podSets.template.spec.topologySpreadConstraints.withNodeAffinityPolicy

```ts
withNodeAffinityPolicy(nodeAffinityPolicy)
```

"NodeAffinityPolicy indicates how we will treat Pod's nodeAffinity/nodeSelector\nwhen calculating pod topology spread skew. Options are:\n- Honor: only nodes matching nodeAffinity/nodeSelector are included in the calculations.\n- Ignore: nodeAffinity/nodeSelector are ignored. All nodes are included in the calculations.\n\nIf this value is nil, the behavior is equivalent to the Honor policy."

### fn spec.podSets.template.spec.topologySpreadConstraints.withNodeTaintsPolicy

```ts
withNodeTaintsPolicy(nodeTaintsPolicy)
```

"NodeTaintsPolicy indicates how we will treat node taints when calculating\npod topology spread skew. Options are:\n- Honor: nodes without taints, along with tainted nodes for which the incoming pod\nhas a toleration, are included.\n- Ignore: node taints are ignored. All nodes are included.\n\nIf this value is nil, the behavior is equivalent to the Ignore policy."

### fn spec.podSets.template.spec.topologySpreadConstraints.withTopologyKey

```ts
withTopologyKey(topologyKey)
```

"TopologyKey is the key of node labels. Nodes that have a label with this key\nand identical values are considered to be in the same topology.\nWe consider each <key, value> as a \"bucket\", and try to put balanced number\nof pods into each bucket.\nWe define a domain as a particular instance of a topology.\nAlso, we define an eligible domain as a domain whose nodes meet the requirements of\nnodeAffinityPolicy and nodeTaintsPolicy.\ne.g. If TopologyKey is \"kubernetes.io/hostname\", each Node is a domain of that topology.\nAnd, if TopologyKey is \"topology.kubernetes.io/zone\", each zone is a domain of that topology.\nIt's a required field."

### fn spec.podSets.template.spec.topologySpreadConstraints.withWhenUnsatisfiable

```ts
withWhenUnsatisfiable(whenUnsatisfiable)
```

"WhenUnsatisfiable indicates how to deal with a pod if it doesn't satisfy\nthe spread constraint.\n- DoNotSchedule (default) tells the scheduler not to schedule it.\n- ScheduleAnyway tells the scheduler to schedule the pod in any location,\n  but giving higher precedence to topologies that would help reduce the\n  skew.\nA constraint is considered \"Unsatisfiable\" for an incoming pod\nif and only if every possible node assignment for that pod would violate\n\"MaxSkew\" on some topology.\nFor example, in a 3-zone cluster, MaxSkew is set to 1, and pods with the same\nlabelSelector spread as 3/1/1:\n| zone1 | zone2 | zone3 |\n| P P P |   P   |   P   |\nIf WhenUnsatisfiable is set to DoNotSchedule, incoming pod can only be scheduled\nto zone2(zone3) to become 3/2/1(3/1/2) as ActualSkew(2-1) on zone2(zone3) satisfies\nMaxSkew(1). In other words, the cluster can still be imbalanced, but scheduler\nwon't make it *more* imbalanced.\nIt's a required field."

## obj spec.podSets.template.spec.topologySpreadConstraints.labelSelector

"LabelSelector is used to find matching pods.\nPods that match this label selector are counted to determine the number of pods\nin their corresponding topology domain."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.topologySpreadConstraints.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes

"List of volumes that can be mounted by containers belonging to the pod.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes"

### fn spec.podSets.template.spec.volumes.withName

```ts
withName(name)
```

"name of the volume.\nMust be a DNS_LABEL and unique within the pod.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.awsElasticBlockStore

"awsElasticBlockStore represents an AWS Disk resource that is attached to a\nkubelet's host machine and then exposed to the pod.\nDeprecated: AWSElasticBlockStore is deprecated. All operations for the in-tree\nawsElasticBlockStore type are redirected to the ebs.csi.aws.com CSI driver.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore"

### fn spec.podSets.template.spec.volumes.awsElasticBlockStore.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type of the volume that you want to mount.\nTip: Ensure that the filesystem type is supported by the host operating system.\nExamples: \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore"

### fn spec.podSets.template.spec.volumes.awsElasticBlockStore.withPartition

```ts
withPartition(partition)
```

"partition is the partition in the volume that you want to mount.\nIf omitted, the default is to mount by volume name.\nExamples: For volume /dev/sda1, you specify the partition as \"1\".\nSimilarly, the volume partition for /dev/sda is \"0\" (or you can leave the property empty)."

### fn spec.podSets.template.spec.volumes.awsElasticBlockStore.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly value true will force the readOnly setting in VolumeMounts.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore"

### fn spec.podSets.template.spec.volumes.awsElasticBlockStore.withVolumeID

```ts
withVolumeID(volumeID)
```

"volumeID is unique ID of the persistent disk resource in AWS (Amazon EBS volume).\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#awselasticblockstore"

## obj spec.podSets.template.spec.volumes.azureDisk

"azureDisk represents an Azure Data Disk mount on the host and bind mount to the pod.\nDeprecated: AzureDisk is deprecated. All operations for the in-tree azureDisk type\nare redirected to the disk.csi.azure.com CSI driver."

### fn spec.podSets.template.spec.volumes.azureDisk.withCachingMode

```ts
withCachingMode(cachingMode)
```

"cachingMode is the Host Caching mode: None, Read Only, Read Write."

### fn spec.podSets.template.spec.volumes.azureDisk.withDiskName

```ts
withDiskName(diskName)
```

"diskName is the Name of the data disk in the blob storage"

### fn spec.podSets.template.spec.volumes.azureDisk.withDiskURI

```ts
withDiskURI(diskURI)
```

"diskURI is the URI of data disk in the blob storage"

### fn spec.podSets.template.spec.volumes.azureDisk.withFsType

```ts
withFsType(fsType)
```

"fsType is Filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.azureDisk.withKind

```ts
withKind(kind)
```

"kind expected values are Shared: multiple blob disks per storage account  Dedicated: single blob disk per storage account  Managed: azure managed data disk (only in managed availability set). defaults to shared"

### fn spec.podSets.template.spec.volumes.azureDisk.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly Defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

## obj spec.podSets.template.spec.volumes.azureFile

"azureFile represents an Azure File Service mount on the host and bind mount to the pod.\nDeprecated: AzureFile is deprecated. All operations for the in-tree azureFile type\nare redirected to the file.csi.azure.com CSI driver."

### fn spec.podSets.template.spec.volumes.azureFile.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

### fn spec.podSets.template.spec.volumes.azureFile.withSecretName

```ts
withSecretName(secretName)
```

"secretName is the  name of secret that contains Azure Storage Account Name and Key"

### fn spec.podSets.template.spec.volumes.azureFile.withShareName

```ts
withShareName(shareName)
```

"shareName is the azure share Name"

## obj spec.podSets.template.spec.volumes.cephfs

"cephFS represents a Ceph FS mount on the host that shares a pod's lifetime.\nDeprecated: CephFS is deprecated and the in-tree cephfs type is no longer supported."

### fn spec.podSets.template.spec.volumes.cephfs.withMonitors

```ts
withMonitors(monitors)
```

"monitors is Required: Monitors is a collection of Ceph monitors\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.cephfs.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```

"monitors is Required: Monitors is a collection of Ceph monitors\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.cephfs.withPath

```ts
withPath(path)
```

"path is Optional: Used as the mounted root, rather than the full Ceph tree, default is /"

### fn spec.podSets.template.spec.volumes.cephfs.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly is Optional: Defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts.\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.cephfs.withSecretFile

```ts
withSecretFile(secretFile)
```

"secretFile is Optional: SecretFile is the path to key ring for User, default is /etc/ceph/user.secret\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.cephfs.withUser

```ts
withUser(user)
```

"user is optional: User is the rados user name, default is admin\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

## obj spec.podSets.template.spec.volumes.cephfs.secretRef

"secretRef is Optional: SecretRef is reference to the authentication secret for User, default is empty.\nMore info: https://examples.k8s.io/volumes/cephfs/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.cephfs.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.cinder

"cinder represents a cinder volume attached and mounted on kubelets host machine.\nDeprecated: Cinder is deprecated. All operations for the in-tree cinder type\nare redirected to the cinder.csi.openstack.org CSI driver.\nMore info: https://examples.k8s.io/mysql-cinder-pd/README.md"

### fn spec.podSets.template.spec.volumes.cinder.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nExamples: \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified.\nMore info: https://examples.k8s.io/mysql-cinder-pd/README.md"

### fn spec.podSets.template.spec.volumes.cinder.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts.\nMore info: https://examples.k8s.io/mysql-cinder-pd/README.md"

### fn spec.podSets.template.spec.volumes.cinder.withVolumeID

```ts
withVolumeID(volumeID)
```

"volumeID used to identify the volume in cinder.\nMore info: https://examples.k8s.io/mysql-cinder-pd/README.md"

## obj spec.podSets.template.spec.volumes.cinder.secretRef

"secretRef is optional: points to a secret object containing parameters used to connect\nto OpenStack."

### fn spec.podSets.template.spec.volumes.cinder.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.configMap

"configMap represents a configMap that should populate this volume"

### fn spec.podSets.template.spec.volumes.configMap.withDefaultMode

```ts
withDefaultMode(defaultMode)
```

"defaultMode is optional: mode bits used to set permissions on created files by default.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nDefaults to 0644.\nDirectories within the path are not affected by this setting.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.configMap.withItems

```ts
withItems(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.configMap.withItemsMixin

```ts
withItemsMixin(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.configMap.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.volumes.configMap.withOptional

```ts
withOptional(optional)
```

"optional specify whether the ConfigMap or its keys must be defined"

## obj spec.podSets.template.spec.volumes.configMap.items

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.configMap.items.withKey

```ts
withKey(key)
```

"key is the key to project."

### fn spec.podSets.template.spec.volumes.configMap.items.withMode

```ts
withMode(mode)
```

"mode is Optional: mode bits used to set permissions on this file.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.configMap.items.withPath

```ts
withPath(path)
```

"path is the relative path of the file to map the key to.\nMay not be an absolute path.\nMay not contain the path element '..'.\nMay not start with the string '..'."

## obj spec.podSets.template.spec.volumes.csi

"csi (Container Storage Interface) represents ephemeral storage that is handled by certain external CSI drivers."

### fn spec.podSets.template.spec.volumes.csi.withDriver

```ts
withDriver(driver)
```

"driver is the name of the CSI driver that handles this volume.\nConsult with your admin for the correct name as registered in the cluster."

### fn spec.podSets.template.spec.volumes.csi.withFsType

```ts
withFsType(fsType)
```

"fsType to mount. Ex. \"ext4\", \"xfs\", \"ntfs\".\nIf not provided, the empty value is passed to the associated CSI driver\nwhich will determine the default filesystem to apply."

### fn spec.podSets.template.spec.volumes.csi.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly specifies a read-only configuration for the volume.\nDefaults to false (read/write)."

### fn spec.podSets.template.spec.volumes.csi.withVolumeAttributes

```ts
withVolumeAttributes(volumeAttributes)
```

"volumeAttributes stores driver-specific properties that are passed to the CSI\ndriver. Consult your driver's documentation for supported values."

### fn spec.podSets.template.spec.volumes.csi.withVolumeAttributesMixin

```ts
withVolumeAttributesMixin(volumeAttributes)
```

"volumeAttributes stores driver-specific properties that are passed to the CSI\ndriver. Consult your driver's documentation for supported values."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.csi.nodePublishSecretRef

"nodePublishSecretRef is a reference to the secret object containing\nsensitive information to pass to the CSI driver to complete the CSI\nNodePublishVolume and NodeUnpublishVolume calls.\nThis field is optional, and  may be empty if no secret is required. If the\nsecret object contains more than one secret, all secret references are passed."

### fn spec.podSets.template.spec.volumes.csi.nodePublishSecretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.downwardAPI

"downwardAPI represents downward API about the pod that should populate this volume"

### fn spec.podSets.template.spec.volumes.downwardAPI.withDefaultMode

```ts
withDefaultMode(defaultMode)
```

"Optional: mode bits to use on created files by default. Must be a\nOptional: mode bits used to set permissions on created files by default.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nDefaults to 0644.\nDirectories within the path are not affected by this setting.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.downwardAPI.withItems

```ts
withItems(items)
```

"Items is a list of downward API volume file"

### fn spec.podSets.template.spec.volumes.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```

"Items is a list of downward API volume file"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.downwardAPI.items

"Items is a list of downward API volume file"

### fn spec.podSets.template.spec.volumes.downwardAPI.items.withMode

```ts
withMode(mode)
```

"Optional: mode bits used to set permissions on this file, must be an octal value\nbetween 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.downwardAPI.items.withPath

```ts
withPath(path)
```

"Required: Path is  the relative path name of the file to be created. Must not be absolute or contain the '..' path. Must be utf-8 encoded. The first item of the relative path must not start with '..'"

## obj spec.podSets.template.spec.volumes.downwardAPI.items.fieldRef

"Required: Selects a field of the pod: only annotations, labels, name, namespace and uid are supported."

### fn spec.podSets.template.spec.volumes.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"Version of the schema the FieldPath is written in terms of, defaults to \"v1\"."

### fn spec.podSets.template.spec.volumes.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"Path of the field to select in the specified API version."

## obj spec.podSets.template.spec.volumes.downwardAPI.items.resourceFieldRef

"Selects a resource of the container: only resources limits and requests\n(limits.cpu, limits.memory, requests.cpu and requests.memory) are currently supported."

### fn spec.podSets.template.spec.volumes.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```

"Container name: required for volumes, optional for env vars"

### fn spec.podSets.template.spec.volumes.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```

"Specifies the output format of the exposed resources, defaults to \"1\

### fn spec.podSets.template.spec.volumes.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```

"Required: resource to select"

## obj spec.podSets.template.spec.volumes.emptyDir

"emptyDir represents a temporary directory that shares a pod's lifetime.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#emptydir"

### fn spec.podSets.template.spec.volumes.emptyDir.withMedium

```ts
withMedium(medium)
```

"medium represents what type of storage medium should back this directory.\nThe default is \"\" which means to use the node's default medium.\nMust be an empty string (default) or Memory.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#emptydir"

### fn spec.podSets.template.spec.volumes.emptyDir.withSizeLimit

```ts
withSizeLimit(sizeLimit)
```

"sizeLimit is the total amount of local storage required for this EmptyDir volume.\nThe size limit is also applicable for memory medium.\nThe maximum usage on memory medium EmptyDir would be the minimum value between\nthe SizeLimit specified here and the sum of memory limits of all containers in a pod.\nThe default is nil which means that the limit is undefined.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#emptydir"

## obj spec.podSets.template.spec.volumes.ephemeral

"ephemeral represents a volume that is handled by a cluster storage driver.\nThe volume's lifecycle is tied to the pod that defines it - it will be created before the pod starts,\nand deleted when the pod is removed.\n\nUse this if:\na) the volume is only needed while the pod runs,\nb) features of normal volumes like restoring from snapshot or capacity\n   tracking are needed,\nc) the storage driver is specified through a storage class, and\nd) the storage driver supports dynamic volume provisioning through\n   a PersistentVolumeClaim (see EphemeralVolumeSource for more\n   information on the connection between this volume type\n   and PersistentVolumeClaim).\n\nUse PersistentVolumeClaim or one of the vendor-specific\nAPIs for volumes that persist for longer than the lifecycle\nof an individual pod.\n\nUse CSI for light-weight local ephemeral volumes if the CSI driver is meant to\nbe used that way - see the documentation of the driver for\nmore information.\n\nA pod can use both types of ephemeral volumes and\npersistent volumes at the same time."

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate

"Will be used to create a stand-alone PVC to provision the volume.\nThe pod in which this EphemeralVolumeSource is embedded will be the\nowner of the PVC, i.e. the PVC will be deleted together with the\npod.  The name of the PVC will be `<pod name>-<volume name>` where\n`<volume name>` is the name from the `PodSpec.Volumes` array\nentry. Pod validation will reject the pod if the concatenated name\nis not valid for a PVC (for example, too long).\n\nAn existing PVC with that name that is not owned by the pod\nwill *not* be used for the pod to avoid using an unrelated\nvolume by mistake. Starting the pod is then blocked until\nthe unrelated PVC is removed. If such a pre-created PVC is\nmeant to be used by the pod, the PVC has to updated with an\nowner reference to the pod once the pod exists. Normally\nthis should not be necessary, but it may be useful when\nmanually reconstructing a broken cluster.\n\nThis field is read-only and no changes will be made by Kubernetes\nto the PVC after it has been created.\n\nRequired, must not be nil."

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata

"May contain labels and annotations that will be copied into the PVC\nwhen creating it. No other fields are allowed and will be rejected during\nvalidation."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotations

```ts
withAnnotations(annotations)
```



### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withAnnotationsMixin

```ts
withAnnotationsMixin(annotations)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizers

```ts
withFinalizers(finalizers)
```



### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withFinalizersMixin

```ts
withFinalizersMixin(finalizers)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withLabels

```ts
withLabels(labels)
```



### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withLabelsMixin

```ts
withLabelsMixin(labels)
```



**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withName

```ts
withName(name)
```



### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.metadata.withNamespace

```ts
withNamespace(namespace)
```



## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec

"The specification for the PersistentVolumeClaim. The entire content is\ncopied unchanged into the PVC that gets created from this\ntemplate. The same fields as in a PersistentVolumeClaim\nare also valid here."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModes

```ts
withAccessModes(accessModes)
```

"accessModes contains the desired access modes the volume should have.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#access-modes-1"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withAccessModesMixin

```ts
withAccessModesMixin(accessModes)
```

"accessModes contains the desired access modes the volume should have.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#access-modes-1"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withStorageClassName

```ts
withStorageClassName(storageClassName)
```

"storageClassName is the name of the StorageClass required by the claim.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#class-1"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeAttributesClassName

```ts
withVolumeAttributesClassName(volumeAttributesClassName)
```

"volumeAttributesClassName may be used to set the VolumeAttributesClass used by this claim.\nIf specified, the CSI driver will create or update the volume with the attributes defined\nin the corresponding VolumeAttributesClass. This has a different purpose than storageClassName,\nit can be changed after the claim is created. An empty string or nil value indicates that no\nVolumeAttributesClass will be applied to the claim. If the claim enters an Infeasible error state,\nthis field can be reset to its previous value (including nil) to cancel the modification.\nIf the resource referred to by volumeAttributesClass does not exist, this PersistentVolumeClaim will be\nset to a Pending state, as reflected by the modifyVolumeStatus field, until such as a resource\nexists.\nMore info: https://kubernetes.io/docs/concepts/storage/volume-attributes-classes/"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeMode

```ts
withVolumeMode(volumeMode)
```

"volumeMode defines what type of volume is required by the claim.\nValue of Filesystem is implied when not included in claim spec."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.withVolumeName

```ts
withVolumeName(volumeName)
```

"volumeName is the binding reference to the PersistentVolume backing this claim."

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource

"dataSource field can be used to specify either:\n* An existing VolumeSnapshot object (snapshot.storage.k8s.io/VolumeSnapshot)\n* An existing PVC (PersistentVolumeClaim)\nIf the provisioner or an external controller can support the specified data source,\nit will create a new volume based on the contents of the specified data source.\nWhen the AnyVolumeDataSource feature gate is enabled, dataSource contents will be copied to dataSourceRef,\nand dataSourceRef contents will be copied to dataSource when dataSourceRef.namespace is not specified.\nIf the namespace is specified, then dataSourceRef will not be copied to dataSource."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withApiGroup

```ts
withApiGroup(apiGroup)
```

"APIGroup is the group for the resource being referenced.\nIf APIGroup is not specified, the specified Kind must be in the core API group.\nFor any other third-party types, APIGroup is required."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withKind

```ts
withKind(kind)
```

"Kind is the type of resource being referenced"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSource.withName

```ts
withName(name)
```

"Name is the name of resource being referenced"

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef

"dataSourceRef specifies the object from which to populate the volume with data, if a non-empty\nvolume is desired. This may be any object from a non-empty API group (non\ncore object) or a PersistentVolumeClaim object.\nWhen this field is specified, volume binding will only succeed if the type of\nthe specified object matches some installed volume populator or dynamic\nprovisioner.\nThis field will replace the functionality of the dataSource field and as such\nif both fields are non-empty, they must have the same value. For backwards\ncompatibility, when namespace isn't specified in dataSourceRef,\nboth fields (dataSource and dataSourceRef) will be set to the same\nvalue automatically if one of them is empty and the other is non-empty.\nWhen namespace is specified in dataSourceRef,\ndataSource isn't set to the same value and must be empty.\nThere are three important differences between dataSource and dataSourceRef:\n* While dataSource only allows two specific types of objects, dataSourceRef\n  allows any non-core object, as well as PersistentVolumeClaim objects.\n* While dataSource ignores disallowed values (dropping them), dataSourceRef\n  preserves all values, and generates an error if a disallowed value is\n  specified.\n* While dataSource only allows local objects, dataSourceRef allows objects\n  in any namespaces.\n(Beta) Using this field requires the AnyVolumeDataSource feature gate to be enabled.\n(Alpha) Using the namespace field of dataSourceRef requires the CrossNamespaceVolumeDataSource feature gate to be enabled."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withApiGroup

```ts
withApiGroup(apiGroup)
```

"APIGroup is the group for the resource being referenced.\nIf APIGroup is not specified, the specified Kind must be in the core API group.\nFor any other third-party types, APIGroup is required."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withKind

```ts
withKind(kind)
```

"Kind is the type of resource being referenced"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withName

```ts
withName(name)
```

"Name is the name of resource being referenced"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.dataSourceRef.withNamespace

```ts
withNamespace(namespace)
```

"Namespace is the namespace of resource being referenced\nNote that when a namespace is specified, a gateway.networking.k8s.io/ReferenceGrant object is required in the referent namespace to allow that namespace's owner to accept the reference. See the ReferenceGrant documentation for details.\n(Alpha) This field requires the CrossNamespaceVolumeDataSource feature gate to be enabled."

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources

"resources represents the minimum resources the volume should have.\nIf RecoverVolumeExpansionFailure feature is enabled users are allowed to specify resource requirements\nthat are lower than previous value but must still be higher than capacity recorded in the\nstatus field of the claim.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#resources"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimits

```ts
withLimits(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withLimitsMixin

```ts
withLimitsMixin(limits)
```

"Limits describes the maximum amount of compute resources allowed.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequests

```ts
withRequests(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.resources.withRequestsMixin

```ts
withRequestsMixin(requests)
```

"Requests describes the minimum amount of compute resources required.\nIf Requests is omitted for a container, it defaults to Limits if that is explicitly specified,\notherwise to an implementation-defined value. Requests cannot exceed Limits.\nMore info: https://kubernetes.io/docs/concepts/configuration/manage-resources-containers/"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector

"selector is a label query over volumes to consider for binding."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.volumes.ephemeral.volumeClaimTemplate.spec.selector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.fc

"fc represents a Fibre Channel resource that is attached to a kubelet's host machine and then exposed to the pod."

### fn spec.podSets.template.spec.volumes.fc.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.fc.withLun

```ts
withLun(lun)
```

"lun is Optional: FC target lun number"

### fn spec.podSets.template.spec.volumes.fc.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly is Optional: Defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

### fn spec.podSets.template.spec.volumes.fc.withTargetWWNs

```ts
withTargetWWNs(targetWWNs)
```

"targetWWNs is Optional: FC target worldwide names (WWNs)"

### fn spec.podSets.template.spec.volumes.fc.withTargetWWNsMixin

```ts
withTargetWWNsMixin(targetWWNs)
```

"targetWWNs is Optional: FC target worldwide names (WWNs)"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.fc.withWwids

```ts
withWwids(wwids)
```

"wwids Optional: FC volume world wide identifiers (wwids)\nEither wwids or combination of targetWWNs and lun must be set, but not both simultaneously."

### fn spec.podSets.template.spec.volumes.fc.withWwidsMixin

```ts
withWwidsMixin(wwids)
```

"wwids Optional: FC volume world wide identifiers (wwids)\nEither wwids or combination of targetWWNs and lun must be set, but not both simultaneously."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.flexVolume

"flexVolume represents a generic volume resource that is\nprovisioned/attached using an exec based plugin.\nDeprecated: FlexVolume is deprecated. Consider using a CSIDriver instead."

### fn spec.podSets.template.spec.volumes.flexVolume.withDriver

```ts
withDriver(driver)
```

"driver is the name of the driver to use for this volume."

### fn spec.podSets.template.spec.volumes.flexVolume.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". The default filesystem depends on FlexVolume script."

### fn spec.podSets.template.spec.volumes.flexVolume.withOptions

```ts
withOptions(options)
```

"options is Optional: this field holds extra command options if any."

### fn spec.podSets.template.spec.volumes.flexVolume.withOptionsMixin

```ts
withOptionsMixin(options)
```

"options is Optional: this field holds extra command options if any."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.flexVolume.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly is Optional: defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

## obj spec.podSets.template.spec.volumes.flexVolume.secretRef

"secretRef is Optional: secretRef is reference to the secret object containing\nsensitive information to pass to the plugin scripts. This may be\nempty if no secret object is specified. If the secret object\ncontains more than one secret, all secrets are passed to the plugin\nscripts."

### fn spec.podSets.template.spec.volumes.flexVolume.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.flocker

"flocker represents a Flocker volume attached to a kubelet's host machine. This depends on the Flocker control service being running.\nDeprecated: Flocker is deprecated and the in-tree flocker type is no longer supported."

### fn spec.podSets.template.spec.volumes.flocker.withDatasetName

```ts
withDatasetName(datasetName)
```

"datasetName is Name of the dataset stored as metadata -> name on the dataset for Flocker\nshould be considered as deprecated"

### fn spec.podSets.template.spec.volumes.flocker.withDatasetUUID

```ts
withDatasetUUID(datasetUUID)
```

"datasetUUID is the UUID of the dataset. This is unique identifier of a Flocker dataset"

## obj spec.podSets.template.spec.volumes.gcePersistentDisk

"gcePersistentDisk represents a GCE Disk resource that is attached to a\nkubelet's host machine and then exposed to the pod.\nDeprecated: GCEPersistentDisk is deprecated. All operations for the in-tree\ngcePersistentDisk type are redirected to the pd.csi.storage.gke.io CSI driver.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#gcepersistentdisk"

### fn spec.podSets.template.spec.volumes.gcePersistentDisk.withFsType

```ts
withFsType(fsType)
```

"fsType is filesystem type of the volume that you want to mount.\nTip: Ensure that the filesystem type is supported by the host operating system.\nExamples: \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#gcepersistentdisk"

### fn spec.podSets.template.spec.volumes.gcePersistentDisk.withPartition

```ts
withPartition(partition)
```

"partition is the partition in the volume that you want to mount.\nIf omitted, the default is to mount by volume name.\nExamples: For volume /dev/sda1, you specify the partition as \"1\".\nSimilarly, the volume partition for /dev/sda is \"0\" (or you can leave the property empty).\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#gcepersistentdisk"

### fn spec.podSets.template.spec.volumes.gcePersistentDisk.withPdName

```ts
withPdName(pdName)
```

"pdName is unique name of the PD resource in GCE. Used to identify the disk in GCE.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#gcepersistentdisk"

### fn spec.podSets.template.spec.volumes.gcePersistentDisk.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the ReadOnly setting in VolumeMounts.\nDefaults to false.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#gcepersistentdisk"

## obj spec.podSets.template.spec.volumes.gitRepo

"gitRepo represents a git repository at a particular revision.\nDeprecated: GitRepo is deprecated. To provision a container with a git repo, mount an\nEmptyDir into an InitContainer that clones the repo using git, then mount the EmptyDir\ninto the Pod's container."

### fn spec.podSets.template.spec.volumes.gitRepo.withDirectory

```ts
withDirectory(directory)
```

"directory is the target directory name.\nMust not contain or start with '..'.  If '.' is supplied, the volume directory will be the\ngit repository.  Otherwise, if specified, the volume will contain the git repository in\nthe subdirectory with the given name."

### fn spec.podSets.template.spec.volumes.gitRepo.withRepository

```ts
withRepository(repository)
```

"repository is the URL"

### fn spec.podSets.template.spec.volumes.gitRepo.withRevision

```ts
withRevision(revision)
```

"revision is the commit hash for the specified revision."

## obj spec.podSets.template.spec.volumes.glusterfs

"glusterfs represents a Glusterfs mount on the host that shares a pod's lifetime.\nDeprecated: Glusterfs is deprecated and the in-tree glusterfs type is no longer supported."

### fn spec.podSets.template.spec.volumes.glusterfs.withEndpoints

```ts
withEndpoints(endpoints)
```

"endpoints is the endpoint name that details Glusterfs topology."

### fn spec.podSets.template.spec.volumes.glusterfs.withPath

```ts
withPath(path)
```

"path is the Glusterfs volume path.\nMore info: https://examples.k8s.io/volumes/glusterfs/README.md#create-a-pod"

### fn spec.podSets.template.spec.volumes.glusterfs.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the Glusterfs volume to be mounted with read-only permissions.\nDefaults to false.\nMore info: https://examples.k8s.io/volumes/glusterfs/README.md#create-a-pod"

## obj spec.podSets.template.spec.volumes.hostPath

"hostPath represents a pre-existing file or directory on the host\nmachine that is directly exposed to the container. This is generally\nused for system agents or other privileged things that are allowed\nto see the host machine. Most containers will NOT need this.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#hostpath"

### fn spec.podSets.template.spec.volumes.hostPath.withPath

```ts
withPath(path)
```

"path of the directory on the host.\nIf the path is a symlink, it will follow the link to the real path.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#hostpath"

### fn spec.podSets.template.spec.volumes.hostPath.withType

```ts
withType(type)
```

"type for HostPath Volume\nDefaults to \"\"\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#hostpath"

## obj spec.podSets.template.spec.volumes.image

"image represents an OCI object (a container image or artifact) pulled and mounted on the kubelet's host machine.\nThe volume is resolved at pod startup depending on which PullPolicy value is provided:\n\n- Always: the kubelet always attempts to pull the reference. Container creation will fail If the pull fails.\n- Never: the kubelet never pulls the reference and only uses a local image or artifact. Container creation will fail if the reference isn't present.\n- IfNotPresent: the kubelet pulls if the reference isn't already present on disk. Container creation will fail if the reference isn't present and the pull fails.\n\nThe volume gets re-resolved if the pod gets deleted and recreated, which means that new remote content will become available on pod recreation.\nA failure to resolve or pull the image during pod startup will block containers from starting and may add significant latency. Failures will be retried using normal volume backoff and will be reported on the pod reason and message.\nThe types of objects that may be mounted by this volume are defined by the container runtime implementation on a host machine and at minimum must include all valid types supported by the container image field.\nThe OCI object gets mounted in a single directory (spec.containers[*].volumeMounts.mountPath) by merging the manifest layers in the same way as for container images.\nThe volume will be mounted read-only (ro) and non-executable files (noexec).\nSub path mounts for containers are not supported (spec.containers[*].volumeMounts.subpath) before 1.33.\nThe field spec.securityContext.fsGroupChangePolicy has no effect on this volume type."

### fn spec.podSets.template.spec.volumes.image.withPullPolicy

```ts
withPullPolicy(pullPolicy)
```

"Policy for pulling OCI objects. Possible values are:\nAlways: the kubelet always attempts to pull the reference. Container creation will fail If the pull fails.\nNever: the kubelet never pulls the reference and only uses a local image or artifact. Container creation will fail if the reference isn't present.\nIfNotPresent: the kubelet pulls if the reference isn't already present on disk. Container creation will fail if the reference isn't present and the pull fails.\nDefaults to Always if :latest tag is specified, or IfNotPresent otherwise."

### fn spec.podSets.template.spec.volumes.image.withReference

```ts
withReference(reference)
```

"Required: Image or artifact reference to be used.\nBehaves in the same way as pod.spec.containers[*].image.\nPull secrets will be assembled in the same way as for the container image by looking up node credentials, SA image pull secrets, and pod spec image pull secrets.\nMore info: https://kubernetes.io/docs/concepts/containers/images\nThis field is optional to allow higher level config management to default or override\ncontainer images in workload controllers like Deployments and StatefulSets."

## obj spec.podSets.template.spec.volumes.iscsi

"iscsi represents an ISCSI Disk resource that is attached to a\nkubelet's host machine and then exposed to the pod.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes/#iscsi"

### fn spec.podSets.template.spec.volumes.iscsi.withChapAuthDiscovery

```ts
withChapAuthDiscovery(chapAuthDiscovery)
```

"chapAuthDiscovery defines whether support iSCSI Discovery CHAP authentication"

### fn spec.podSets.template.spec.volumes.iscsi.withChapAuthSession

```ts
withChapAuthSession(chapAuthSession)
```

"chapAuthSession defines whether support iSCSI Session CHAP authentication"

### fn spec.podSets.template.spec.volumes.iscsi.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type of the volume that you want to mount.\nTip: Ensure that the filesystem type is supported by the host operating system.\nExamples: \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#iscsi"

### fn spec.podSets.template.spec.volumes.iscsi.withInitiatorName

```ts
withInitiatorName(initiatorName)
```

"initiatorName is the custom iSCSI Initiator Name.\nIf initiatorName is specified with iscsiInterface simultaneously, new iSCSI interface\n<target portal>:<volume name> will be created for the connection."

### fn spec.podSets.template.spec.volumes.iscsi.withIqn

```ts
withIqn(iqn)
```

"iqn is the target iSCSI Qualified Name."

### fn spec.podSets.template.spec.volumes.iscsi.withIscsiInterface

```ts
withIscsiInterface(iscsiInterface)
```

"iscsiInterface is the interface Name that uses an iSCSI transport.\nDefaults to 'default' (tcp)."

### fn spec.podSets.template.spec.volumes.iscsi.withLun

```ts
withLun(lun)
```

"lun represents iSCSI Target Lun number."

### fn spec.podSets.template.spec.volumes.iscsi.withPortals

```ts
withPortals(portals)
```

"portals is the iSCSI Target Portal List. The portal is either an IP or ip_addr:port if the port\nis other than default (typically TCP ports 860 and 3260)."

### fn spec.podSets.template.spec.volumes.iscsi.withPortalsMixin

```ts
withPortalsMixin(portals)
```

"portals is the iSCSI Target Portal List. The portal is either an IP or ip_addr:port if the port\nis other than default (typically TCP ports 860 and 3260)."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.iscsi.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the ReadOnly setting in VolumeMounts.\nDefaults to false."

### fn spec.podSets.template.spec.volumes.iscsi.withTargetPortal

```ts
withTargetPortal(targetPortal)
```

"targetPortal is iSCSI Target Portal. The Portal is either an IP or ip_addr:port if the port\nis other than default (typically TCP ports 860 and 3260)."

## obj spec.podSets.template.spec.volumes.iscsi.secretRef

"secretRef is the CHAP Secret for iSCSI target and initiator authentication"

### fn spec.podSets.template.spec.volumes.iscsi.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.nfs

"nfs represents an NFS mount on the host that shares a pod's lifetime\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#nfs"

### fn spec.podSets.template.spec.volumes.nfs.withPath

```ts
withPath(path)
```

"path that is exported by the NFS server.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#nfs"

### fn spec.podSets.template.spec.volumes.nfs.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the NFS export to be mounted with read-only permissions.\nDefaults to false.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#nfs"

### fn spec.podSets.template.spec.volumes.nfs.withServer

```ts
withServer(server)
```

"server is the hostname or IP address of the NFS server.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#nfs"

## obj spec.podSets.template.spec.volumes.persistentVolumeClaim

"persistentVolumeClaimVolumeSource represents a reference to a\nPersistentVolumeClaim in the same namespace.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#persistentvolumeclaims"

### fn spec.podSets.template.spec.volumes.persistentVolumeClaim.withClaimName

```ts
withClaimName(claimName)
```

"claimName is the name of a PersistentVolumeClaim in the same namespace as the pod using this volume.\nMore info: https://kubernetes.io/docs/concepts/storage/persistent-volumes#persistentvolumeclaims"

### fn spec.podSets.template.spec.volumes.persistentVolumeClaim.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly Will force the ReadOnly setting in VolumeMounts.\nDefault false."

## obj spec.podSets.template.spec.volumes.photonPersistentDisk

"photonPersistentDisk represents a PhotonController persistent disk attached and mounted on kubelets host machine.\nDeprecated: PhotonPersistentDisk is deprecated and the in-tree photonPersistentDisk type is no longer supported."

### fn spec.podSets.template.spec.volumes.photonPersistentDisk.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.photonPersistentDisk.withPdID

```ts
withPdID(pdID)
```

"pdID is the ID that identifies Photon Controller persistent disk"

## obj spec.podSets.template.spec.volumes.portworxVolume

"portworxVolume represents a portworx volume attached and mounted on kubelets host machine.\nDeprecated: PortworxVolume is deprecated. All operations for the in-tree portworxVolume type\nare redirected to the pxd.portworx.com CSI driver when the CSIMigrationPortworx feature-gate\nis on."

### fn spec.podSets.template.spec.volumes.portworxVolume.withFsType

```ts
withFsType(fsType)
```

"fSType represents the filesystem type to mount\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.portworxVolume.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

### fn spec.podSets.template.spec.volumes.portworxVolume.withVolumeID

```ts
withVolumeID(volumeID)
```

"volumeID uniquely identifies a Portworx volume"

## obj spec.podSets.template.spec.volumes.projected

"projected items for all in one resources secrets, configmaps, and downward API"

### fn spec.podSets.template.spec.volumes.projected.withDefaultMode

```ts
withDefaultMode(defaultMode)
```

"defaultMode are the mode bits used to set permissions on created files by default.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nDirectories within the path are not affected by this setting.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.projected.withSources

```ts
withSources(sources)
```

"sources is the list of volume projections. Each entry in this list\nhandles one source."

### fn spec.podSets.template.spec.volumes.projected.withSourcesMixin

```ts
withSourcesMixin(sources)
```

"sources is the list of volume projections. Each entry in this list\nhandles one source."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.projected.sources

"sources is the list of volume projections. Each entry in this list\nhandles one source."

## obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle

"ClusterTrustBundle allows a pod to access the `.spec.trustBundle` field\nof ClusterTrustBundle objects in an auto-updating file.\n\nAlpha, gated by the ClusterTrustBundleProjection feature gate.\n\nClusterTrustBundle objects can either be selected by name, or by the\ncombination of signer name and a label selector.\n\nKubelet performs aggressive normalization of the PEM contents written\ninto the pod filesystem.  Esoteric PEM features such as inter-block\ncomments and block headers are stripped.  Certificates are deduplicated.\nThe ordering of certificates within the file is arbitrary, and Kubelet\nmay change the order over time."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.withName

```ts
withName(name)
```

"Select a single ClusterTrustBundle by object name.  Mutually-exclusive\nwith signerName and labelSelector."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.withOptional

```ts
withOptional(optional)
```

"If true, don't block pod startup if the referenced ClusterTrustBundle(s)\naren't available.  If using name, then the named ClusterTrustBundle is\nallowed not to exist.  If using signerName, then the combination of\nsignerName and labelSelector is allowed to match zero\nClusterTrustBundles."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.withPath

```ts
withPath(path)
```

"Relative path from the volume root to write the bundle."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.withSignerName

```ts
withSignerName(signerName)
```

"Select all ClusterTrustBundles that match this signer name.\nMutually-exclusive with name.  The contents of all selected\nClusterTrustBundles will be unified and deduplicated."

## obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector

"Select all ClusterTrustBundles that match this label selector.  Only has\neffect if signerName is set.  Mutually-exclusive with name.  If unset,\ninterpreted as \"match nothing\".  If set but empty, interpreted as \"match\neverything\"."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressions

```ts
withMatchExpressions(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchExpressionsMixin

```ts
withMatchExpressionsMixin(matchExpressions)
```

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabels

```ts
withMatchLabels(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.withMatchLabelsMixin

```ts
withMatchLabelsMixin(matchLabels)
```

"matchLabels is a map of {key,value} pairs. A single {key,value} in the matchLabels\nmap is equivalent to an element of matchExpressions, whose key field is \"key\", the\noperator is \"In\", and the values array contains only \"value\". The requirements are ANDed."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions

"matchExpressions is a list of label selector requirements. The requirements are ANDed."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withKey

```ts
withKey(key)
```

"key is the label key that the selector applies to."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withOperator

```ts
withOperator(operator)
```

"operator represents a key's relationship to a set of values.\nValid operators are In, NotIn, Exists and DoesNotExist."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValues

```ts
withValues(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

### fn spec.podSets.template.spec.volumes.projected.sources.clusterTrustBundle.labelSelector.matchExpressions.withValuesMixin

```ts
withValuesMixin(values)
```

"values is an array of string values. If the operator is In or NotIn,\nthe values array must be non-empty. If the operator is Exists or DoesNotExist,\nthe values array must be empty. This array is replaced during a strategic\nmerge patch."

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.projected.sources.configMap

"configMap information about the configMap data to project"

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.withItems

```ts
withItems(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.withItemsMixin

```ts
withItemsMixin(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.withOptional

```ts
withOptional(optional)
```

"optional specify whether the ConfigMap or its keys must be defined"

## obj spec.podSets.template.spec.volumes.projected.sources.configMap.items

"items if unspecified, each key-value pair in the Data field of the referenced\nConfigMap will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the ConfigMap,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.items.withKey

```ts
withKey(key)
```

"key is the key to project."

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.items.withMode

```ts
withMode(mode)
```

"mode is Optional: mode bits used to set permissions on this file.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.projected.sources.configMap.items.withPath

```ts
withPath(path)
```

"path is the relative path of the file to map the key to.\nMay not be an absolute path.\nMay not contain the path element '..'.\nMay not start with the string '..'."

## obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI

"downwardAPI information about the downwardAPI data to project"

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.withItems

```ts
withItems(items)
```

"Items is a list of DownwardAPIVolume file"

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.withItemsMixin

```ts
withItemsMixin(items)
```

"Items is a list of DownwardAPIVolume file"

**Note:** This function appends passed data to existing values

## obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items

"Items is a list of DownwardAPIVolume file"

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.withMode

```ts
withMode(mode)
```

"Optional: mode bits used to set permissions on this file, must be an octal value\nbetween 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.withPath

```ts
withPath(path)
```

"Required: Path is  the relative path name of the file to be created. Must not be absolute or contain the '..' path. Must be utf-8 encoded. The first item of the relative path must not start with '..'"

## obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef

"Required: Selects a field of the pod: only annotations, labels, name, namespace and uid are supported."

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withApiVersion

```ts
withApiVersion(apiVersion)
```

"Version of the schema the FieldPath is written in terms of, defaults to \"v1\"."

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.fieldRef.withFieldPath

```ts
withFieldPath(fieldPath)
```

"Path of the field to select in the specified API version."

## obj spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef

"Selects a resource of the container: only resources limits and requests\n(limits.cpu, limits.memory, requests.cpu and requests.memory) are currently supported."

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withContainerName

```ts
withContainerName(containerName)
```

"Container name: required for volumes, optional for env vars"

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withDivisor

```ts
withDivisor(divisor)
```

"Specifies the output format of the exposed resources, defaults to \"1\

### fn spec.podSets.template.spec.volumes.projected.sources.downwardAPI.items.resourceFieldRef.withResource

```ts
withResource(resource)
```

"Required: resource to select"

## obj spec.podSets.template.spec.volumes.projected.sources.podCertificate

"Projects an auto-rotating credential bundle (private key and certificate\nchain) that the pod can use either as a TLS client or server.\n\nKubelet generates a private key and uses it to send a\nPodCertificateRequest to the named signer.  Once the signer approves the\nrequest and issues a certificate chain, Kubelet writes the key and\ncertificate chain to the pod filesystem.  The pod does not start until\ncertificates have been issued for each podCertificate projected volume\nsource in its spec.\n\nKubelet will begin trying to rotate the certificate at the time indicated\nby the signer using the PodCertificateRequest.Status.BeginRefreshAt\ntimestamp.\n\nKubelet can write a single file, indicated by the credentialBundlePath\nfield, or separate files, indicated by the keyPath and\ncertificateChainPath fields.\n\nThe credential bundle is a single file in PEM format.  The first PEM\nentry is the private key (in PKCS#8 format), and the remaining PEM\nentries are the certificate chain issued by the signer (typically,\nsigners will return their certificate chain in leaf-to-root order).\n\nPrefer using the credential bundle format, since your application code\ncan read it atomically.  If you use keyPath and certificateChainPath,\nyour application must make two separate file reads. If these coincide\nwith a certificate rotation, it is possible that the private key and leaf\ncertificate you read may not correspond to each other.  Your application\nwill need to check for this condition, and re-read until they are\nconsistent.\n\nThe named signer controls chooses the format of the certificate it\nissues; consult the signer implementation's documentation to learn how to\nuse the certificates it issues."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withCertificateChainPath

```ts
withCertificateChainPath(certificateChainPath)
```

"Write the certificate chain at this path in the projected volume.\n\nMost applications should use credentialBundlePath.  When using keyPath\nand certificateChainPath, your application needs to check that the key\nand leaf certificate are consistent, because it is possible to read the\nfiles mid-rotation."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withCredentialBundlePath

```ts
withCredentialBundlePath(credentialBundlePath)
```

"Write the credential bundle at this path in the projected volume.\n\nThe credential bundle is a single file that contains multiple PEM blocks.\nThe first PEM block is a PRIVATE KEY block, containing a PKCS#8 private\nkey.\n\nThe remaining blocks are CERTIFICATE blocks, containing the issued\ncertificate chain from the signer (leaf and any intermediates).\n\nUsing credentialBundlePath lets your Pod's application code make a single\natomic read that retrieves a consistent key and certificate chain.  If you\nproject them to separate files, your application code will need to\nadditionally check that the leaf certificate was issued to the key."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withKeyPath

```ts
withKeyPath(keyPath)
```

"Write the key at this path in the projected volume.\n\nMost applications should use credentialBundlePath.  When using keyPath\nand certificateChainPath, your application needs to check that the key\nand leaf certificate are consistent, because it is possible to read the\nfiles mid-rotation."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withKeyType

```ts
withKeyType(keyType)
```

"The type of keypair Kubelet will generate for the pod.\n\nValid values are \"RSA3072\", \"RSA4096\", \"ECDSAP256\", \"ECDSAP384\",\n\"ECDSAP521\", and \"ED25519\"."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withMaxExpirationSeconds

```ts
withMaxExpirationSeconds(maxExpirationSeconds)
```

"maxExpirationSeconds is the maximum lifetime permitted for the\ncertificate.\n\nKubelet copies this value verbatim into the PodCertificateRequests it\ngenerates for this projection.\n\nIf omitted, kube-apiserver will set it to 86400(24 hours). kube-apiserver\nwill reject values shorter than 3600 (1 hour).  The maximum allowable\nvalue is 7862400 (91 days).\n\nThe signer implementation is then free to issue a certificate with any\nlifetime *shorter* than MaxExpirationSeconds, but no shorter than 3600\nseconds (1 hour).  This constraint is enforced by kube-apiserver.\n`kubernetes.io` signers will never issue certificates with a lifetime\nlonger than 24 hours."

### fn spec.podSets.template.spec.volumes.projected.sources.podCertificate.withSignerName

```ts
withSignerName(signerName)
```

"Kubelet's generated CSRs will be addressed to this signer."

## obj spec.podSets.template.spec.volumes.projected.sources.secret

"secret information about the secret data to project"

### fn spec.podSets.template.spec.volumes.projected.sources.secret.withItems

```ts
withItems(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.projected.sources.secret.withItemsMixin

```ts
withItemsMixin(items)
```

"items if unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.projected.sources.secret.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

### fn spec.podSets.template.spec.volumes.projected.sources.secret.withOptional

```ts
withOptional(optional)
```

"optional field specify whether the Secret or its key must be defined"

## obj spec.podSets.template.spec.volumes.projected.sources.secret.items

"items if unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.projected.sources.secret.items.withKey

```ts
withKey(key)
```

"key is the key to project."

### fn spec.podSets.template.spec.volumes.projected.sources.secret.items.withMode

```ts
withMode(mode)
```

"mode is Optional: mode bits used to set permissions on this file.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.projected.sources.secret.items.withPath

```ts
withPath(path)
```

"path is the relative path of the file to map the key to.\nMay not be an absolute path.\nMay not contain the path element '..'.\nMay not start with the string '..'."

## obj spec.podSets.template.spec.volumes.projected.sources.serviceAccountToken

"serviceAccountToken is information about the serviceAccountToken data to project"

### fn spec.podSets.template.spec.volumes.projected.sources.serviceAccountToken.withAudience

```ts
withAudience(audience)
```

"audience is the intended audience of the token. A recipient of a token\nmust identify itself with an identifier specified in the audience of the\ntoken, and otherwise should reject the token. The audience defaults to the\nidentifier of the apiserver."

### fn spec.podSets.template.spec.volumes.projected.sources.serviceAccountToken.withExpirationSeconds

```ts
withExpirationSeconds(expirationSeconds)
```

"expirationSeconds is the requested duration of validity of the service\naccount token. As the token approaches expiration, the kubelet volume\nplugin will proactively rotate the service account token. The kubelet will\nstart trying to rotate the token if the token is older than 80 percent of\nits time to live or if the token is older than 24 hours.Defaults to 1 hour\nand must be at least 10 minutes."

### fn spec.podSets.template.spec.volumes.projected.sources.serviceAccountToken.withPath

```ts
withPath(path)
```

"path is the path relative to the mount point of the file to project the\ntoken into."

## obj spec.podSets.template.spec.volumes.quobyte

"quobyte represents a Quobyte mount on the host that shares a pod's lifetime.\nDeprecated: Quobyte is deprecated and the in-tree quobyte type is no longer supported."

### fn spec.podSets.template.spec.volumes.quobyte.withGroup

```ts
withGroup(group)
```

"group to map volume access to\nDefault is no group"

### fn spec.podSets.template.spec.volumes.quobyte.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the Quobyte volume to be mounted with read-only permissions.\nDefaults to false."

### fn spec.podSets.template.spec.volumes.quobyte.withRegistry

```ts
withRegistry(registry)
```

"registry represents a single or multiple Quobyte Registry services\nspecified as a string as host:port pair (multiple entries are separated with commas)\nwhich acts as the central registry for volumes"

### fn spec.podSets.template.spec.volumes.quobyte.withTenant

```ts
withTenant(tenant)
```

"tenant owning the given Quobyte volume in the Backend\nUsed with dynamically provisioned Quobyte volumes, value is set by the plugin"

### fn spec.podSets.template.spec.volumes.quobyte.withUser

```ts
withUser(user)
```

"user to map volume access to\nDefaults to serivceaccount user"

### fn spec.podSets.template.spec.volumes.quobyte.withVolume

```ts
withVolume(volume)
```

"volume is a string that references an already created Quobyte volume by name."

## obj spec.podSets.template.spec.volumes.rbd

"rbd represents a Rados Block Device mount on the host that shares a pod's lifetime.\nDeprecated: RBD is deprecated and the in-tree rbd type is no longer supported."

### fn spec.podSets.template.spec.volumes.rbd.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type of the volume that you want to mount.\nTip: Ensure that the filesystem type is supported by the host operating system.\nExamples: \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#rbd"

### fn spec.podSets.template.spec.volumes.rbd.withImage

```ts
withImage(image)
```

"image is the rados image name.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.withKeyring

```ts
withKeyring(keyring)
```

"keyring is the path to key ring for RBDUser.\nDefault is /etc/ceph/keyring.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.withMonitors

```ts
withMonitors(monitors)
```

"monitors is a collection of Ceph monitors.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.withMonitorsMixin

```ts
withMonitorsMixin(monitors)
```

"monitors is a collection of Ceph monitors.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.rbd.withPool

```ts
withPool(pool)
```

"pool is the rados pool name.\nDefault is rbd.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly here will force the ReadOnly setting in VolumeMounts.\nDefaults to false.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.withUser

```ts
withUser(user)
```

"user is the rados user name.\nDefault is admin.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

## obj spec.podSets.template.spec.volumes.rbd.secretRef

"secretRef is name of the authentication secret for RBDUser. If provided\noverrides keyring.\nDefault is nil.\nMore info: https://examples.k8s.io/volumes/rbd/README.md#how-to-use-it"

### fn spec.podSets.template.spec.volumes.rbd.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.scaleIO

"scaleIO represents a ScaleIO persistent volume attached and mounted on Kubernetes nodes.\nDeprecated: ScaleIO is deprecated and the in-tree scaleIO type is no longer supported."

### fn spec.podSets.template.spec.volumes.scaleIO.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\".\nDefault is \"xfs\"."

### fn spec.podSets.template.spec.volumes.scaleIO.withGateway

```ts
withGateway(gateway)
```

"gateway is the host address of the ScaleIO API Gateway."

### fn spec.podSets.template.spec.volumes.scaleIO.withProtectionDomain

```ts
withProtectionDomain(protectionDomain)
```

"protectionDomain is the name of the ScaleIO Protection Domain for the configured storage."

### fn spec.podSets.template.spec.volumes.scaleIO.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly Defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

### fn spec.podSets.template.spec.volumes.scaleIO.withSslEnabled

```ts
withSslEnabled(sslEnabled)
```

"sslEnabled Flag enable/disable SSL communication with Gateway, default false"

### fn spec.podSets.template.spec.volumes.scaleIO.withStorageMode

```ts
withStorageMode(storageMode)
```

"storageMode indicates whether the storage for a volume should be ThickProvisioned or ThinProvisioned.\nDefault is ThinProvisioned."

### fn spec.podSets.template.spec.volumes.scaleIO.withStoragePool

```ts
withStoragePool(storagePool)
```

"storagePool is the ScaleIO Storage Pool associated with the protection domain."

### fn spec.podSets.template.spec.volumes.scaleIO.withSystem

```ts
withSystem(system)
```

"system is the name of the storage system as configured in ScaleIO."

### fn spec.podSets.template.spec.volumes.scaleIO.withVolumeName

```ts
withVolumeName(volumeName)
```

"volumeName is the name of a volume already created in the ScaleIO system\nthat is associated with this volume source."

## obj spec.podSets.template.spec.volumes.scaleIO.secretRef

"secretRef references to the secret for ScaleIO user and other\nsensitive information. If this is not provided, Login operation will fail."

### fn spec.podSets.template.spec.volumes.scaleIO.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.secret

"secret represents a secret that should populate this volume.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#secret"

### fn spec.podSets.template.spec.volumes.secret.withDefaultMode

```ts
withDefaultMode(defaultMode)
```

"defaultMode is Optional: mode bits used to set permissions on created files by default.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values\nfor mode bits. Defaults to 0644.\nDirectories within the path are not affected by this setting.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.secret.withItems

```ts
withItems(items)
```

"items If unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.secret.withItemsMixin

```ts
withItemsMixin(items)
```

"items If unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

**Note:** This function appends passed data to existing values

### fn spec.podSets.template.spec.volumes.secret.withOptional

```ts
withOptional(optional)
```

"optional field specify whether the Secret or its keys must be defined"

### fn spec.podSets.template.spec.volumes.secret.withSecretName

```ts
withSecretName(secretName)
```

"secretName is the name of the secret in the pod's namespace to use.\nMore info: https://kubernetes.io/docs/concepts/storage/volumes#secret"

## obj spec.podSets.template.spec.volumes.secret.items

"items If unspecified, each key-value pair in the Data field of the referenced\nSecret will be projected into the volume as a file whose name is the\nkey and content is the value. If specified, the listed keys will be\nprojected into the specified paths, and unlisted keys will not be\npresent. If a key is specified which is not present in the Secret,\nthe volume setup will error unless it is marked optional. Paths must be\nrelative and may not contain the '..' path or start with '..'."

### fn spec.podSets.template.spec.volumes.secret.items.withKey

```ts
withKey(key)
```

"key is the key to project."

### fn spec.podSets.template.spec.volumes.secret.items.withMode

```ts
withMode(mode)
```

"mode is Optional: mode bits used to set permissions on this file.\nMust be an octal value between 0000 and 0777 or a decimal value between 0 and 511.\nYAML accepts both octal and decimal values, JSON requires decimal values for mode bits.\nIf not specified, the volume defaultMode will be used.\nThis might be in conflict with other options that affect the file\nmode, like fsGroup, and the result can be other mode bits set."

### fn spec.podSets.template.spec.volumes.secret.items.withPath

```ts
withPath(path)
```

"path is the relative path of the file to map the key to.\nMay not be an absolute path.\nMay not contain the path element '..'.\nMay not start with the string '..'."

## obj spec.podSets.template.spec.volumes.storageos

"storageOS represents a StorageOS volume attached and mounted on Kubernetes nodes.\nDeprecated: StorageOS is deprecated and the in-tree storageos type is no longer supported."

### fn spec.podSets.template.spec.volumes.storageos.withFsType

```ts
withFsType(fsType)
```

"fsType is the filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.storageos.withReadOnly

```ts
withReadOnly(readOnly)
```

"readOnly defaults to false (read/write). ReadOnly here will force\nthe ReadOnly setting in VolumeMounts."

### fn spec.podSets.template.spec.volumes.storageos.withVolumeName

```ts
withVolumeName(volumeName)
```

"volumeName is the human-readable name of the StorageOS volume.  Volume\nnames are only unique within a namespace."

### fn spec.podSets.template.spec.volumes.storageos.withVolumeNamespace

```ts
withVolumeNamespace(volumeNamespace)
```

"volumeNamespace specifies the scope of the volume within StorageOS.  If no\nnamespace is specified then the Pod's namespace will be used.  This allows the\nKubernetes name scoping to be mirrored within StorageOS for tighter integration.\nSet VolumeName to any name to override the default behaviour.\nSet to \"default\" if you are not using namespaces within StorageOS.\nNamespaces that do not pre-exist within StorageOS will be created."

## obj spec.podSets.template.spec.volumes.storageos.secretRef

"secretRef specifies the secret to use for obtaining the StorageOS API\ncredentials.  If not specified, default values will be attempted."

### fn spec.podSets.template.spec.volumes.storageos.secretRef.withName

```ts
withName(name)
```

"Name of the referent.\nThis field is effectively required, but due to backwards compatibility is\nallowed to be empty. Instances of this type with an empty value here are\nalmost certainly wrong.\nMore info: https://kubernetes.io/docs/concepts/overview/working-with-objects/names/#names"

## obj spec.podSets.template.spec.volumes.vsphereVolume

"vsphereVolume represents a vSphere volume attached and mounted on kubelets host machine.\nDeprecated: VsphereVolume is deprecated. All operations for the in-tree vsphereVolume type\nare redirected to the csi.vsphere.vmware.com CSI driver."

### fn spec.podSets.template.spec.volumes.vsphereVolume.withFsType

```ts
withFsType(fsType)
```

"fsType is filesystem type to mount.\nMust be a filesystem type supported by the host operating system.\nEx. \"ext4\", \"xfs\", \"ntfs\". Implicitly inferred to be \"ext4\" if unspecified."

### fn spec.podSets.template.spec.volumes.vsphereVolume.withStoragePolicyID

```ts
withStoragePolicyID(storagePolicyID)
```

"storagePolicyID is the storage Policy Based Management (SPBM) profile ID associated with the StoragePolicyName."

### fn spec.podSets.template.spec.volumes.vsphereVolume.withStoragePolicyName

```ts
withStoragePolicyName(storagePolicyName)
```

"storagePolicyName is the storage Policy Based Management (SPBM) profile name."

### fn spec.podSets.template.spec.volumes.vsphereVolume.withVolumePath

```ts
withVolumePath(volumePath)
```

"volumePath is the path that identifies vSphere volume vmdk"

## obj spec.podSets.topologyRequest

"topologyRequest defines the topology request for the PodSet."

### fn spec.podSets.topologyRequest.withPodIndexLabel

```ts
withPodIndexLabel(podIndexLabel)
```

"podIndexLabel indicates the name of the label indexing the pods.\nFor example, in the context of\n- kubernetes job this is: kubernetes.io/job-completion-index\n- JobSet: kubernetes.io/job-completion-index (inherited from Job)\n- Kubeflow: training.kubeflow.org/replica-index\n\tThis is limited to 317 characters."

### fn spec.podSets.topologyRequest.withPodSetGroupName

```ts
withPodSetGroupName(podSetGroupName)
```

"podSetGroupName indicates the name of the group of PodSets to which this PodSet belongs to.\nPodSets with the same `PodSetGroupName` should be assigned the same ResourceFlavor"

### fn spec.podSets.topologyRequest.withPodSetSliceRequiredTopology

```ts
withPodSetSliceRequiredTopology(podSetSliceRequiredTopology)
```

"podSetSliceRequiredTopology indicates the topology level required by the PodSet slice, as\nindicated by the `kueue.x-k8s.io/podset-slice-required-topology` annotation.\n\nThis is limited to 63"

### fn spec.podSets.topologyRequest.withPodSetSliceSize

```ts
withPodSetSliceSize(podSetSliceSize)
```

"podSetSliceSize indicates the size of a subgroup of pods in a PodSet for which\nKueue finds a requested topology domain on a level defined\nin `kueue.x-k8s.io/podset-slice-required-topology` annotation."

### fn spec.podSets.topologyRequest.withPreferred

```ts
withPreferred(preferred)
```

"preferred indicates the topology level preferred by the PodSet, as\nindicated by the `kueue.x-k8s.io/podset-preferred-topology` PodSet\nannotation.\nThis is limited to 63 characters."

### fn spec.podSets.topologyRequest.withRequired

```ts
withRequired(required)
```

"required indicates the topology level required by the PodSet, as\nindicated by the `kueue.x-k8s.io/podset-required-topology` PodSet\nannotation.\nThis is limited to 63 characters."

### fn spec.podSets.topologyRequest.withSubGroupCount

```ts
withSubGroupCount(subGroupCount)
```

"subGroupCount indicates the count of replicated Jobs (groups) within a PodSet.\nFor example, in the context of JobSet this value is read from jobset.sigs.k8s.io/replicatedjob-replicas."

### fn spec.podSets.topologyRequest.withSubGroupIndexLabel

```ts
withSubGroupIndexLabel(subGroupIndexLabel)
```

"subGroupIndexLabel indicates the name of the label indexing the instances of replicated Jobs (groups)\nwithin a PodSet. For example, in the context of JobSet this is jobset.sigs.k8s.io/job-index.\n\tThis is limited to 317 characters."

### fn spec.podSets.topologyRequest.withUnconstrained

```ts
withUnconstrained(unconstrained)
```

"unconstrained indicates that Kueue has the freedom to schedule the PodSet within\nthe entire available capacity, without constraints on the compactness of the placement.\nThis is indicated by the `kueue.x-k8s.io/podset-unconstrained-topology` PodSet annotation."

## obj spec.priorityClassRef

"priorityClassRef references a PriorityClass object that defines the workload's priority."

### fn spec.priorityClassRef.withGroup

```ts
withGroup(group)
```

"group is the API group of the PriorityClass object.\nUse \"kueue.x-k8s.io\" for WorkloadPriorityClass.\nUse \"scheduling.k8s.io\" for Pod PriorityClass."

### fn spec.priorityClassRef.withKind

```ts
withKind(kind)
```

"kind is the kind of the PriorityClass object."

### fn spec.priorityClassRef.withName

```ts
withName(name)
```

"name is the name of the PriorityClass the Workload is associated with.\nIf specified, indicates the workload's priority.\n\"system-node-critical\" and \"system-cluster-critical\" are two special\nkeywords which indicate the highest priorities with the former being\nthe highest priority. Any other name must be defined by creating a\nPriorityClass object with that name. If not specified, the workload\npriority will be default or zero if there is no default."