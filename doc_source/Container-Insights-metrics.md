# Metrics Collected by Container Insights<a name="Container-Insights-metrics"></a>


****  

|  | 
| --- |
| CloudWatch Container Insights isn't released yet\. It's in preview and is subject to change\. The preview is open to all AWS accounts\. You do not need to request access\. | 

The following table lists the metrics and dimensions that Container Insights collects\. These metrics are in the `ContainerInsights` namespace\. For more information, see [Metrics](cloudwatch_concepts.md#Metric)\.


| Metric Name | Dimensions | 
| --- | --- | 
|  `cluster_failed_node_count` |  ClusterName  | 
|  `cluster_node_count` |  ClusterName  | 
|  `namespace_number_of_running_pods` |  NameSpace, ClusterName ClusterName  | 
|  `node_cpu_limit` |  ClusterName  | 
|  `node_cpu_reserved_capacity` |  NodeName, ClusterName ClusterName  | 
|  `node_cpu_usage_total` |  ClusterName  | 
|  `node_cpu_utilization` |  NodeName, ClusterName ClusterName  | 
|  `node_filesystem_utilization` |  NodeName, ClusterName ClusterName  | 
|  `node_memory_limit` |  ClusterName  | 
|  `node_memory_reserved_capacity` |  NodeName, ClusterName ClusterName  | 
|  `node_memory_utilization` |  NodeName, ClusterName ClusterName  | 
|  `node_memory_working_set` |  ClusterName  | 
|  `node_network_total_bytes` |  NodeName, ClusterName ClusterName  | 
|  `node_number_of_running_containers` |  NodeName, ClusterName ClusterName  | 
|  `node_number_of_running_pods` |  NodeName, ClusterName ClusterName  | 
|  `pod_cpu_reserved_capacity` |  PodName, ClusterName ClusterName  | 
|  `pod_cpu_utilization` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `pod_cpu_utilization_over_pod_limit` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `pod_memory_reserved_capacity` |  PodName, ClusterName ClusterName  | 
|  `pod_memory_utilization` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `pod_memory_utilization_over_pod_limit` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `pod_network_rx_bytes` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `pod_network_tx_bytes` |  PodName, ClusterName Namespace, ClusterName Service, ClusterName ClusterName  | 
|  `service_number_of_running_pods` |  Service, ClusterName ClusterName  | 