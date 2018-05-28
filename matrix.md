## The Matrix

| WORKLOADS | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| Container | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| CronJob | batch/v1beta1 | batch/v1beta1 | batch/v1beta1 | batch/v2alpha1 | batch/v2alpha1 | v2alpha1 |
| DaemonSet | apps/v1 | apps/v1 | apps/v1beta2 | extensions/v1beta1 | extensions/v1beta1 | v1beta1 |
| Deployment | apps/v1 | apps/v1 | apps/v1beta2 | apps/v1beta1 | apps/v1beta1 | v1beta1 |
| Job | batch/v1 | batch/v1 | batch/v1 | batch/v1 | batch/v1 | v1 |
| Pod | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| ReplicaSet | apps/v1 | apps/v1 | apps/v1beta2 | extensions/v1beta1 | extensions/v1beta1 | v1beta1 |
| ReplicationController | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| StatefulSet | apps/v1 | apps/v1 | apps/v1beta2 | apps/v1beta1 | apps/v1beta1 | v1beta1 |

| DISCOVERY & LOAD BALANCING | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| Endpoints | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| Ingress | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | v1beta1 |
| Service | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |

| CONFIG & STORAGE | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| ConfigMap | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| Secret | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| PersistentVolumeClaim | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| StorageClass | storage.k8s.io/v1 | storage/v1 | storage/v1 | storage/v1 | storage/v1 | v1beta1 |
| Volume | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| VolumeAttachment | storage.k8s.io/v1beta1 | storage/v1alpha1 |  |  |  |  |

| METADATA | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| ControllerRevision | apps/v1 | apps/v1 | apps/v1beta2 | apps/v1beta1 |  |  |
| CustomResourceDefinition | apiextensions.k8s.io/v1beta1 | apiextensions/v1beta1 | apiextensions/v1beta1 |  |  |  |
| Event | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| LimitRange | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| ExternalAdmissionHookConfiguration |  |  | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 |  |  |
| HorizontalPodAutoscaler | autoscaling/v1 | autoscaling/v1 | autoscaling/v1 | autoscaling/v1 | autoscaling/v1 | v1 |
| InitializerConfiguration | admissionregistration.k8s.io/v1alpha1 | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 |  |  |
| MutatingWebhookConfiguration | admissionregistration.k8s.io/v1beta1 | admissionregistration/v1beta1 |  |  |  |  |
| ValidatingWebhookConfiguration | admissionregistration.k8s.io/v1beta1 | admissionregistration/v1beta1 |  |  |  |  |
| PodTemplate | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| PodDisruptionBudget | policy/v1beta1 | policy/v1beta1 | policy/v1beta1 | policy/v1beta1 | policy/v1beta1 | v1beta1 |
| PriorityClass | scheduling.k8s.io/v1alpha1 | scheduling/v1alpha1 | scheduling/v1alpha1 |  |  |  |
| ThirdPartyResource |  |  |  | extensions/v1beta1 | extensions/v1beta1 | v1beta1 |
| PodPreset | settings.k8s.io/v1alpha1 | settings/v1alpha1 | settings/v1alpha1 | settings/v1alpha1 | settings/v1alpha1 |  |
| PodSecurityPolicy | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |

| CLUSTER | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| APIService | apiregistration.k8s.io/v1 | apiregistration/v1beta1 | apiregistration/v1beta1 | apiregistration/v1beta1 |  |  |
| Binding | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| CertificateSigningRequest | certificates.k8s.io/v1beta1 | certificates/v1beta1 | certificates/v1beta1 | certificates/v1beta1 | certificates/v1beta1 | v1alpha1 |
| ClusterRole | rbac.authorization.k8s.io/v1 | rbac/v1 | rbac/v1 | rbac/v1beta1 | rbac/v1beta1 | v1alpha1 |
| ClusterRoleBinding | rbac.authorization.k8s.io/v1 | rbac/v1 | rbac/v1 | rbac/v1beta1 | rbac/v1beta1 | v1alpha1 |
| ComponentStatus | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| LocalSubjectAccessReview | authorization.k8s.io/v1 | authorization/v1 | authorization/v1 | authorization/v1 | authorization/v1 | v1beta1 |
| Namespace | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| Node | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| PersistentVolume | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| ResourceQuota | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| Role | rbac.authorization.k8s.io/v1 | rbac/v1 | rbac/v1 | rbac/v1beta1 | rbac/v1beta1 | v1alpha1 |
| RoleBinding | rbac.authorization.k8s.io/v1 | rbac/v1 | rbac/v1 | rbac/v1beta1 | rbac/v1beta1 | v1alpha1 |
| SelfSubjectAccessReview | authorization.k8s.io/v1 | authorization/v1 | authorization/v1 | authorization/v1 | authorization/v1 | v1beta1 |
| SelfSubjectRulesReview | authorization.k8s.io/v1 | authorization/v1 | authorization/v1 |  |  |  |
| ServiceAccount | core/v1 | core/v1 | core/v1 | core/v1 | core/v1 | v1 |
| SubjectAccessReview | authorization.k8s.io/v1 | authorization/v1 | authorization/v1 | authorization/v1 | authorization/v1 | v1beta1 |
| TokenReview | authentication.k8s.io/v1 | authentication/v1 | authentication/v1 | authentication/v1 | authentication/v1 | v1beta1 |
| NetworkPolicy | networking.k8s.io/v1 | networking/v1 | networking/v1 | networking/v1 | extensions/v1beta1 | v1beta1 |

## The Compatible Matrix

| API OVERVIEW | 1.10 | 1.9 | 1.8 | 1.7 | 1.6 | 1.5 |
| -- | -- | -- | -- | -- | -- | -- |
| **OLD API VERSIONS** |  |  |  |  |  |  |
| APIService | apiregistration.k8s.io/v1beta1 |  |  |  |  |  |
| APIServiceCondition | apiregistration.k8s.io/v1beta1 |  |  |  |  |  |
| AggregationRule | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 |  |  |  |  |
| AggregationRule | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 |  |  |  |  |
| AllowedFlexVolume | policy/v1beta1 |  |  |  |  |  |
| AllowedHostPath | policy/v1beta1 |  |  |  |  |  |
| ClusterRole | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| ClusterRole | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| ClusterRoleBinding | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| ClusterRoleBinding | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| ControllerRevision | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| ControllerRevision | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| CronJob | batch/v2alpha1 | batch/v2alpha1 | batch/v2alpha1 |  |  |  |
| CrossVersionObjectReference | autoscaling/v2beta1 | autoscaling/v2beta1 | autoscaling/v2beta1 | autoscaling/v2alpha1 | autoscaling/v2alpha1 |  |
| DaemonSet | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| DaemonSet | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| DaemonSetCondition | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| DaemonSetCondition | extensions/v1beta1 | extensions/v1beta1 |  |  |  |  |
| DaemonSetUpdateStrategy | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| DaemonSetUpdateStrategy | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| Deployment | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| Deployment | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| Deployment | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |
| DeploymentCondition | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| DeploymentCondition | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| DeploymentCondition | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |
| Event | events.k8s.io/v1beta1 | events/v1beta1 |  |  |  |  |
| EventSeries | events.k8s.io/v1beta1 | events/v1beta1 |  |  |  |  |
| FSGroupStrategyOptions | policy/v1beta1 |  |  |  |  |  |
| HorizontalPodAutoscaler | autoscaling/v2beta1 | autoscaling/v2beta1 | autoscaling/v2beta1 | autoscaling/v2alpha1 | autoscaling/v2alpha1 |  |
| HostPortRange | policy/v1beta1 |  |  |  |  |  |
| IDRange | policy/v1beta1 |  |  |  |  |  |
| IPBlock | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| Initializer | admissionregistration.k8s.io/v1alpha1 | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 |  |  |
| JobTemplateSpec | batch/v2alpha1 | batch/v2alpha1 | batch/v2alpha1 |  |  |  |
| LocalSubjectAccessReview | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |
| NetworkPolicy | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |
| NetworkPolicyEgressRule | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| NetworkPolicyIngressRule | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |
| NetworkPolicyPeer | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |
| NetworkPolicyPort | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |
| NonResourceAttributes | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |
| NonResourceRule | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |  |  |
| PodSecurityPolicy | policy/v1beta1 |  |  |  |  |  |
| PolicyRule | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| PolicyRule | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| ReplicaSet | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| ReplicaSet | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| ReplicaSetCondition | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| ReplicaSetCondition | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |  |  |
| ResourceAttributes | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |
| ResourceRule | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |  |  |
| Role | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| Role | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| RoleBinding | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| RoleBinding | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| RoleRef | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| RoleRef | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| RollbackConfig | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 |  |
| RollingUpdateStatefulSetStrategy | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| RollingUpdateStatefulSetStrategy | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| RunAsUserStrategyOptions | policy/v1beta1 |  |  |  |  |  |
| SELinuxStrategyOptions | policy/v1beta1 |  |  |  |  |  |
| Scale | apps/v1beta2 | apps/v1beta2 | apps/v1beta2 |  |  |  |
| Scale | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 | extensions/v1beta1 |  |
| Scale | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | extensions/v1beta1 | apps/v1beta1 |  |
| SelfSubjectAccessReview | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |
| SelfSubjectRulesReview | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |  |  |
| ServiceReference | admissionregistration.k8s.io/v1beta1 |  |  |  |  |  |
| ServiceReference | apiregistration.k8s.io/v1beta1 | apiregistration/v1beta1 | admissionregistration/v1alpha1 | admissionregistration/v1alpha1 |  |  |
| StatefulSet | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| StatefulSet | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| StatefulSetCondition | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| StatefulSetCondition | apps/v1beta1 | apps/v1beta1 |  |  |  |  |
| StatefulSetUpdateStrategy | apps/v1beta2 | apps/v1beta2 |  |  |  |  |
| StatefulSetUpdateStrategy | apps/v1beta1 | apps/v1beta1 | apps/v1beta1 |  |  |  |
| StorageClass | storage.k8s.io/v1beta1 | storage/v1beta1 | storage/v1beta1 | storage/v1beta1 | storage/v1beta1 |  |
| Subject | rbac.authorization.k8s.io/v1beta1 | rbac/v1beta1 | rbac/v1beta1 |  |  |  |
| Subject | rbac.authorization.k8s.io/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 | rbac/v1alpha1 |  |
| SubjectAccessReview | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |
| SubjectRulesReviewStatus | authorization.k8s.io/v1beta1 | authorization/v1beta1 | authorization/v1beta1 |  |  |  |
| SupplementalGroupsStrategyOptions | policy/v1beta1 |  |  |  |  |  |
| TokenReview | authentication.k8s.io/v1beta1 | authentication/v1beta1 | authentication/v1beta1 | authentication/v1beta1 | authentication/v1beta1 |  |
| UserInfo | authentication.k8s.io/v1beta1 | authentication/v1beta1 | authentication/v1beta1 | authentication/v1beta1 | authentication/v1beta1 |  |
| VolumeAttachment | storage.k8s.io/v1alpha1 |  |  |  |  |  |
| VolumeAttachmentSource | storage.k8s.io/v1alpha1 |  |  |  |  |  |
| VolumeError | storage.k8s.io/v1alpha1 |  |  |  |  |  |


