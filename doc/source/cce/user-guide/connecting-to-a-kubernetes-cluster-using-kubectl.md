# Connecting to a Kubernetes Cluster Using kubectl<a name="cce_01_0107"></a>

To access a Kubernetes cluster from a client, you can use the Kubernetes command-line tool \(kubectl\).

This section takes VM clusters as an example. The operations for bare metal clusters are the same.

## Preparation<a name="section3271162319436"></a>

CCE allows you to access a cluster through a VPC network or a public network.

-   Intra-VPC access: You need to apply for an ECS on the  **ECS**  console and ensure that the ECS is in the same VPC as the current cluster.
-   Public network access: You need to prepare an ECS that can connect to a public network.

## Procedure<a name="section37321625113110"></a>

1.  Log in to the CCE console. In the navigation pane, choose  **Resource Management**  \>  **Clusters**, and click  **Kubectl**  under the cluster to be connected.
2.  Follow on-screen prompts to connect to the cluster.

    **Figure  1**  Connecting to a Kubernetes cluster using kubectl<a name="fig984735623518"></a>  
    ![](figures/connecting-to-a-kubernetes-cluster-using-kubectl.png "connecting-to-a-kubernetes-cluster-using-kubectl")


## Related Operations<a name="section422912118536"></a>

After connecting to the cluster, you can use Kubernetes to manage workloads. For details, see  [kubectl Usage Guide](kubectl-usage-guide.md).

