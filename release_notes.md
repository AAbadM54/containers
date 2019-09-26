---

copyright:
  years: 2014, 2019
lastupdated: "2019-09-26"

keywords: kubernetes, iks, release notes

subcollection: containers

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:deprecated: .deprecated}
{:download: .download}
{:preview: .preview}


# Release notes
{: #iks-release}

Use the release notes to learn about the latest changes to the {{site.data.keyword.containerlong}} documentation that are grouped by month.
{:shortdesc}

The following icons are used to indicate if a release note applies only to a certain container platform. If no icon is used, the release note applies to both community Kubernetes and OpenShift clusters.<br>
<img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> Applies to only community Kubernetes clusters.<br>
<img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> Applies to only OpenShift clusters, which released as a beta on 5 June 2019.
{: note}

## September 2019
{: #sept19}

<table summary="The table shows release notes. Rows are to be read from the left to right, with the date in column one, the title of the feature in column two and a description in column three.">
<caption>Documentation updates in September 2019</caption>
<thead>
<th>Date</th>
<th>Description</th>
</thead>
<tbody>
<tr>
  <td>24 September 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.4.31](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the ALB [`nginx-ingress` image to build 566](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Managing cluster network traffic for VPC clusters</strong>: Includes the following new content:<ul>
    <li>[Opening required ports and IP addresses in your firewall for VPC clusters](/docs/containers?topic=containers-vpc-firewall)</li>
    <li>[Controlling traffic with VPC ACLs and network policies](/docs/containers?topic=containers-vpc-network-policy)</li>
    <li>[Setting up VPC VPN connectivity](/docs/containers?topic=containers-vpc-vpnaas)</li>
    <li>[Configuring CoreDNS for VPC clusters](/docs/containers?topic=containers-vpc_dns)</li></ul>
    <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Customizing PVC settings for VPC Block Storage</strong>: You can create a customized storage class or use a Kubernetes secret to create VPC Block Storage with your desired configuration. For more information, see [Customizing the default settings](/docs/containers?topic=containers-vpc-block#vpc-customize-default). </li></ul>
  </li>
  </ul></td>
</tr>
<tr>
  <td>19 September 2019</td>
  <td>Added [steps](/docs/containers?topic=containers-ingress-settings#default_server_cert) for ensuring that your custom certificate, instead of the default IBM-provided certificate, is sent by the Ingress ALB to legacy clients that do not support SNI.</td>
</tr>
<tr>
  <td>17 September 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Single zone location for OpenShift clusters</strong>: The following locations are now supported. For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).<ul>
    <li>Amsterdam, the Netherlands</li>
    <li>Hong Kong SAR of the PRC, China</li>
    <li>Mexico City, Mexico</li>
    <li>Milan, Italy</li>
    </ul></td>
</tr>
<tr>
  <td>16 September 2019</td>
  <td><ul><li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.4.23](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>{{site.data.keyword.at_full_notm}} events</strong>: Added information about [which {{site.data.keyword.at_short}} location your events are sent to](/docs/containers?topic=containers-at_events#at-ui) based on the {{site.data.keyword.containerlong_notm}} location where the cluster is located.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Melbourne, Australia `mel01` single zone location for OpenShift clusters</strong>: For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Worker node patch updates are available for Kubernetes [1.15.3_1517](/docs/containers?topic=containers-changelog#1153_1517_worker), [1.14.6_1533](/docs/containers?topic=containers-changelog#1146_1533_worker), [1.13.10_1536](/docs/containers?topic=containers-changelog#11310_1536_worker), and [1.12.10_1567](/docs/containers?topic=containers-changelog#11210_1567_worker).</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Master fix pack updates are available for OpenShift [3.11.141_1524](/docs/openshift?topic=openshift-openshift_changelog#311141_1524).</li></ul>
  </td>
</tr>
<tr>
  <td>13 September 2019</td>
  <td><ul>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Refreshed Red Hat OpenShift on IBM Cloud docs</strong>: Includes the following new content:<ul>
    <li>[Security information for OpenShift clusters](/docs/openshift?topic=openshift-security).
    <li>[Accessing clusters](/docs/openshift?topic=openshift-openshift_access_cluster).</li>
    <li>[App networking options](/docs/openshift?topic=openshift-openshift_routes) with comparisons of routes, NodePort, load balancers, and Ingress.</li>
    <li>[Common app modification scenarios](/docs/openshift?topic=openshift-openshift_apps#common-app-modification-scenarios) for moving apps from community Kubernetes to OpenShift.</li>
    <li>Updated [pricing FAQ](/docs/openshift?topic=openshift-faqs#openshift_charges) to explain the monthly license in more detail.</li>
    <li>[Resizing and externally exposing the internal registry](/docs/openshift?topic=openshift-openshift-images#openshift_internal_registry).</li>
    <li>[Tutorial overview](/docs/openshift?topic=openshift-tutorials-ov) with links to tutorials.</li>
    <li>[Using the internal registry in OpenShift](/docs/openshift?topic=openshift-openshift-images#openshift_internal_registry)</ul>
  </li>
    <li><strong>Entitled software</strong>: If you have licensed products from your [MyIBM.com ![External link icon](../icons/launch-glyph.svg "External link icon")](https://myibm.ibm.com) container software library, you can [set up your cluster to pull images from the entitled registry](/docs/containers?topic=containers-images#secret_entitled_software).</li>
  <li><strong>`script update` command</strong>: Added [steps for using the `script update` command](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli#script_update) to prepare your automation scripts for the release of version 1.0 of the {{site.data.keyword.containerlong_notm}} plug-in.</li>
  </ul></td>
</tr>
<tr>
  <td>12 September 2019</td>
  <td><ul>
  <li><strong>Ingress ALB changelog</strong>: Updated the ALB [`nginx-ingress` image to build 552](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><strong>Ingress annotations</strong>: Added the [`proxy-ssl-verify-depth` optional parameter to the `ssl-services` annotation](/docs/containers?topic=containers-ingress_annotation#ssl-services).</li></ul></td>
</tr>
<tr>
  <td>06 September 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Chennai, India `che01` single zone location for OpenShift clusters</strong>: For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</td>
</tr>
<tr>
  <td>05 September 2019</td>
  <td><strong>Ingress ALB changelog</strong>: Updated the ALB [`ingress-auth` image to build 340](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</td>
</tr>
<tr>
  <td>04 September 2019</td>
  <td><ul><li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.4.3](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>IAM whitelisting</strong>: If you use an IAM whitelist, you must [whitelist the CIDRs of the {{site.data.keyword.containerlong_notm}} control plane](/docs/containers?topic=containers-firewall#iam_whitelist) for the zones in the region where your cluster is located so that {{site.data.keyword.containerlong_notm}} can create Ingress ALBs and `LoadBalancers` in your cluster.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Montreal, Canada `mon01` single zone location for OpenShift clusters</strong>: For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</li></ul></td>
</tr>
<tr>
  <td>03 September 2019</td>
  <td><ul><li><strong>New! {{site.data.keyword.containerlong_notm}} plug-in version `0.4`</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for multiple changes in the [release of version 0.4.1](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>Version changelog</strong>: Worker node patch updates are available for Kubernetes [1.15.3_1516](/docs/containers?topic=containers-changelog#1153_1516_worker), [1.14.6_1532](/docs/containers?topic=containers-changelog#1146_1532_worker), [1.13.10_1535](/docs/containers?topic=containers-changelog#11310_1535_worker), [1.12.10_1566](/docs/containers?topic=containers-changelog#11210_1566_worker), and OpenShift [3.11.135_1523](/docs/openshift?topic=openshift-openshift_changelog#311135_1523_worker).</li></ul></td>
</tr>
</tbody></table>

<br />


## August 2019
{: #aug19}

<table summary="The table shows release notes. Rows are to be read from the left to right, with the date in column one, the title of the feature in column two and a description in column three.">
<caption>Documentation updates in August 2019</caption>
<thead>
<th>Date</th>
<th>Description</th>
</thead>
<tbody>
<tr>
  <td>30 August 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Paris, France `par01` single zone location for OpenShift clusters</strong>: For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</td>
</tr>
<tr>
  <td>29 August 2019</td>
  <td><strong>Forwarding Kubernetes API audit logs to {{site.data.keyword.la_full_notm}}</strong>: Added steps to [create an audit webhook in your cluster](/docs/containers?topic=containers-health#webhook_logdna) to collect Kubernetes API audit logs from your cluster and forward them to {{site.data.keyword.la_full_notm}}.</td>
</tr>
<tr>
  <td>28 August 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.3.112](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.15.3_1515](/docs/containers?topic=containers-changelog##1153_1515), [1.14.6_1531](/docs/containers?topic=containers-changelog#1146_1531), [1.13.10_1534](/docs/containers?topic=containers-changelog#11310_1534), and [1.12.10_1565](/docs/containers?topic=containers-changelog#11210_1565) master fix pack updates.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Changelog added for master fix pack [3.11.135_1522_openshift](/docs/openshift?topic=openshift-openshift_changelog#311135_1522).</li>
  </ul></td>
</tr>
<tr>
  <td>26 August 2019</td>
  <td><ul>
  <li><strong>Cluster autoscaler</strong>: With the latest version of the cluster autoscaler, you can [enable autoscaling for worker pools during the Helm chart installation](/docs/containers?topic=containers-ca#ca_helm) instead of modifying the config map after installation.</li>
    <li><strong>Ingress ALB changelog</strong>: Updated the ALB [`nginx-ingress` image to build 524 and `ingress-auth` image to build 337](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Seoul, Korea `seo01` single zone location for OpenShift clusters</strong>: For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</li></ul></td>
</tr>
<tr>
  <td>23 August 2019</td>
  <td><ul>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Single zone locations for OpenShift clusters</strong>: You can create OpenShift clusters in Toronto, Canada `tor01` and Singapore `sng01` single zone locations. For more locations, see [Single and multizone locations in Red Hat OpenShift on IBM Cloud](/docs/openshift?topic=openshift-regions-and-zones#zones).</li>
  <li><strong>App networking in VPC</strong>: Updated the [Planning in-cluster and external networking for apps](/docs/containers?topic=containers-cs_network_planning) topic with information for planning app networking in a VPC on Classic cluster.</li>
  <li><strong>Istio in VPC</strong>: Updated the [managed Istio add-on](/docs/containers?topic=containers-istio) topic with information for using Istio in a VPC on Classic cluster.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Remove bound services from cluster</strong>: Added instructions for how to remove an {{site.data.keyword.cloud_notm}} service that you added to a cluster by using service binding. For more information, see [Removing a service from a cluster](/docs/containers?topic=containers-service-binding#unbind-service).</li>
  </ul></td>
</tr>
<tr>
  <td>20 August 2019</td>
  <td><strong>Ingress ALB changelog</strong>: Updated the ALB [`nginx-ingress` image to build 519](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog) for a `custom-ports` bug fix.</td>
</tr>
<tr>
  <td>19 August 2019</td>
  <td><ul>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>New! Virtual Private Cloud</strong>: You can create standard Kubernetes clusters on classic infrastructure in the next generation of the {{site.data.keyword.cloud_notm}} platform, in your [Virtual Private Cloud](/docs/vpc-on-classic?topic=vpc-on-classic-about). VPC gives you the security of a private cloud environment with the dynamic scalability of a public cloud. Classic on VPC clusters are available for only standard, Kubernetes clusters and are not supported in free or OpenShift clusters.<br><br>
  With classic clusters in VPC, {{site.data.keyword.containerlong_notm}} introduces version 2 of the API, which supports multiple infrastructure providers for your clusters. Your cluster network setup also changes, from worker nodes that use public and private VLANs and the public service endpoint to worker nodes that are on a private subnet only and have the private service endpoint enabled. For more information, check out the following links:<ul>
    <li>[Overview of Classic and VPC infrastructure providers](/docs/containers?topic=containers-infrastructure_providers)</li>
    <li>[About the v2 API](/docs/containers?topic=containers-cs_api_install#api_about)</li>
    <li>[Comparison of Classic and VPC commands for the CLI](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli#cli_classic_vpc_about)</li>
    <li>[Understanding network basics of VPC clusters](/docs/containers?topic=containers-plan_clusters#vpc_basics)</li></ul>
    Ready to get started? Try out the [Creating a classic cluster in your VPC tutorial](/docs/containers?topic=containers-vpc_ks_tutorial).</li>
    <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Kubernetes 1.14</strong>: [Kubernetes 1.14](/docs/containers?topic=containers-cs_versions#version_types) is now the default version.</li>
</ul>
  </td>
</tr>
<tr>
  <td>17 August 2019</td>
  <td><ul>
  <li><strong>{{site.data.keyword.at_full}}</strong>: The [{{site.data.keyword.at_full_notm}} service](/docs/containers?topic=containers-at_events) is now supported for you to view, manage, and audit user-initiated activities in your clusters.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.15.2_1514](/docs/containers?topic=containers-changelog#1152_1514), [1.14.5_1530](/docs/containers?topic=containers-changelog#1145_1530), [1.13.9_1533](/docs/containers?topic=containers-changelog#1139_1533), and [1.12.10_1564](/docs/containers?topic=containers-changelog#11210_1564) master fix pack updates.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Changelog added for master fix pack [3.11.135_1521_openshift](/docs/openshift?topic=openshift-openshift_changelog#311135_1521_master).</li></ul></td>
</tr>
<tr>
  <td>15 August 2019</td>
  <td><ul>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>App deployments</strong>: Added steps for [copying deployments from one cluster to another](/docs/containers?topic=containers-app#copy_apps_cluster).</li>
  <li><strong>FAQs</strong>: Added an FAQ about [free clusters](/docs/containers?topic=containers-faqs#faq_free).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Istio</strong>: Added steps for [exposing Istio-managed apps with TLS termination](/docs/containers?topic=containers-istio#tls), [securing in-cluster traffic by enabling mTLS](/docs/containers?topic=containers-istio#mtls), and [Updating the Istio add-ons](/docs/containers?topic=containers-istio#istio_update).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Knative</strong>: Added instructions for how to [use volumes to access secrets and config maps](/docs/containers?topic=containers-serverless-apps-knative#knative-access-volume), [pull images from a private registry](/docs/containers?topic=containers-serverless-apps-knative#knative-private-registry), [scale apps based on CPU usage](/docs/containers?topic=containers-serverless-apps-knative#scale-cpu-vs-number-requests), [change the default container port](/docs/containers?topic=containers-serverless-apps-knative#knative-container-port), and [change the `scale-to-zero-grace-period`](/docs/containers?topic=containers-serverless-apps-knative#knative-idle-time).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.15.2_1513](/docs/containers?topic=containers-changelog#1152_1513), [1.14.5_1529](/docs/containers?topic=containers-changelog#1145_1529), [1.13.9_1532](/docs/containers?topic=containers-changelog#1139_1532), and [1.12.10_1563](/docs/containers?topic=containers-changelog#11210_1563) master fix pack updates.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Changelogs added for master fix pack [3.11.135_1520_openshift](/docs/openshift?topic=openshift-openshift_changelog#311135_1520_master).</li></ul></td>
</tr>
<tr>
  <td>12 August 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.3.103](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the ALB `ingress-auth` image to build 335 for [`musl libc` vulnerabilities](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li></ul></td>
</tr>
<tr>
  <td>05 August 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.3.99](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>New! `NodeLocal` DNS caching (beta)</strong>: For clusters that run Kubernetes 1.15 or later, you can set up improved cluster DNS performance with [`NodeLocal` DNS caching](/docs/containers?topic=containers-cluster_dns#dns_cache).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>New! Version 1.15</strong>: You can create community Kubernetes clusters that run version 1.15. To update from a previous version, review the [1.15 changes](/docs/containers?topic=containers-cs_versions#cs_v115).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Deprecated: Version 1.12</strong>: Kubernetes version 1.12 is deprecated. Review the [changes across versions](/docs/containers?topic=containers-cs_versions), and update to a more recent version.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.14.4_1527](/docs/containers?topic=containers-changelog#1144_1527_worker), [1.13.8_1530](/docs/containers?topic=containers-changelog#1138_1530_worker), and [1.12.10_1561](/docs/containers?topic=containers-changelog#11210_1561_worker) worker node patch updates.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Changelogs added for worker node patch [3.11.129_1518_openshift](/docs/openshift?topic=openshift-openshift_changelog#311129_1518_worker).</li></ul></td>
</tr>
<tr>
  <td>02 August 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: Changelogs added for [3.11.129_1517_openshift](/docs/openshift?topic=openshift-openshift_changelog#311129_1517).</td>
</tr>
<tr>
  <td>01 August 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Red Hat OpenShift on IBM Cloud</strong>: Red Hat OpenShift on IBM Cloud is generally available as of 1 August 2019 at 0:00 UTC. Any beta clusters expire within 30 days. You can [create a GA cluster](/docs/openshift?topic=openshift-openshift_tutorial) and then re-deploy any apps that you use in the beta clusters before the beta clusters are removed.<br><br>Because the {{site.data.keyword.containerlong_notm}} logic and underlying cloud infrastructure is the same, many topics are reused across the documentation for [community Kubernetes](/docs/containers?topic=containers-getting-started) and [OpenShift](/docs/openshift?topic=openshift-getting-started) clusters, such as this release notes topic.</td>
</tr>
</tbody></table>

## July 2019
{: #jul19}

<table summary="The table shows release notes. Rows are to be read from the left to right, with the date in column one, the title of the feature in column two and a description in column three.">
<caption>{{site.data.keyword.containerlong_notm}} documentation updates in July 2019</caption>
<thead>
<th>Date</th>
<th>Description</th>
</thead>
<tbody>
<tr>
  <td>30 July 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.3.95](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the ALB `nginx-ingress` image to build 515 for the [ALB pod readiness check](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><strong>Removing subnets from a cluster</strong>: Added steps for removing subnets [in an IBM Cloud infrastructure account](/docs/containers?topic=containers-subnets#remove-sl-subnets) or [in an on-premises network](/docs/containers?topic=containers-subnets#remove-user-subnets) from a cluster. </li>
  </ul></td>
</tr>
<tr>
  <td>26 July 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Red Hat OpenShift on IBM Cloud</strong>: Added [integrations](/docs/openshift?topic=openshift-openshift_integrations), [locations](/docs/openshift?topic=openshift-regions-and-zones), and [security context constraints](/docs/openshift?topic=openshift-openshift_scc) topics. Added the `basic-users` and `self-provisioning` cluster roles to the [IAM service role to RBAC sync](/docs/openshift?topic=openshift-access_reference#service) topic.</td>
</tr>
<tr>
  <td>23 July 2019</td>
  <td><strong>Fluentd changelog</strong>: Fixes [Alpine vulnerabilities](/docs/containers?topic=containers-cluster-add-ons-changelog#fluentd_changelog).</td>
</tr>
<tr>
  <td>22 July 2019</td>
  <td><ul>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version policy</strong>: Increased the [version deprecation](/docs/containers?topic=containers-cs_versions#version_types) period from 30 to 45 days.</li>
      <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.14.4_1526](/docs/containers?topic=containers-changelog#1144_1526_worker), [1.13.8_1529](/docs/containers?topic=containers-changelog#1138_1529_worker), and [1.12.10_1560](/docs/containers?topic=containers-changelog#11210_1560_worker) worker node patch updates.</li>
    <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelog</strong>: [Version 1.11](/docs/containers?topic=containers-changelog#111_changelog) is unsupported.</li></ul>
  </td>
</tr>
<tr>
  <td>19 July 2019</td>
  <td><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Red Hat OpenShift on IBM Cloud</strong>: Added the [Red Hat OpenShift on IBM Cloud documentation to a separate repository](/docs/openshift?topic=openshift-getting-started). Because the {{site.data.keyword.containerlong_notm}} logic and underlying cloud infrastructure is the same, many topics are reused across the documentation for community Kubernetes and OpenShift cluster documentation, such as this release notes topic.
  </td>
</tr>
<tr>
  <td>17 July 2019</td>
  <td><strong>Ingress ALB changelog</strong>: [Fixes `rbash` vulnerabilities](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).
  </td>
</tr>
<tr>
  <td>15 July 2019</td>
  <td><ul>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Cluster and worker node ID</strong>: The ID format for clusters and worker nodes is changed. Existing clusters and worker nodes keep their existing IDs. If you have automation that relies on the previous format, update it for new clusters.<ul>
  <li>**Cluster ID**: In the regex format `{a-v0-9}[7]{a-z0-9}[2]{a-v0-9}[11]`</li>
  <li>**Worker node ID**: In the format `kube-<cluster_ID>-<cluster_name_truncated>-<resource_group_truncated>-<worker_ID>`</li></ul></li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `nginx-ingress` image to build 497](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><strong>Troubleshooting clusters</strong>: Added [troubleshooting steps](/docs/containers?topic=containers-cs_troubleshoot_clusters#cs_totp) for when you cannot manage clusters and worker nodes because the time-based one-time passcode (TOTP) option is enabled for your account.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.14.4_1526](/docs/containers?topic=containers-changelog#1144_1526), [1.13.8_1529](/docs/containers?topic=containers-changelog#1138_1529), and [1.12.10_1560](/docs/containers?topic=containers-changelog#11210_1560) master fix pack updates.</li></ul>
  </td>
</tr>
<tr>
  <td>08 July 2019</td>
  <td><ul>
  <li><strong>App networking</strong>: You can now find information about app networking with NLBs and Ingress ALBs in the following pages:
    <ul><li>[Basic and DSR load balancing with network load balancers (NLB)](/docs/containers?topic=containers-cs_sitemap#sitemap-nlb)</li>
    <li>[HTTPS load balancing with Ingress application load balancers (ALB)](/docs/containers?topic=containers-cs_sitemap#sitemap-ingress)</li></ul>
  </li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.14.3_1525](/docs/containers?topic=containers-changelog#1143_1525), [1.13.7_1528](/docs/containers?topic=containers-changelog#1137_1528), [1.12.9_1559](/docs/containers?topic=containers-changelog#1129_1559), and [1.11.10_1564](/docs/containers?topic=containers-changelog#11110_1564) worker node patch updates.</li></ul>
  </td>
</tr>
<tr>
  <td>02 July 2019</td>
  <td><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of version 0.3.58](/docs/containers?topic=containers-cs_cli_changelog).</td>
</tr>
<tr>
  <td>01 July 2019</td>
  <td><ul>
  <li><strong>Infrastructure permissions</strong>: Updated the [classic infrastructure roles](/docs/containers?topic=containers-access_reference#infra) required for common use cases.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>OpenShift FAQs</strong>: Expanded the [FAQs](/docs/containers?topic=containers-faqs#container_platforms) to include information about OpenShift clusters.</li>
  <li><strong>Securing Istio-managed apps with {{site.data.keyword.appid_short_notm}}</strong>: Added information about the [App Identity and Access adapter](/docs/containers?topic=containers-istio#app-id).</li>
  <li><strong>strongSwan VPN service</strong>: If you install strongSwan in a multizone cluster and use the `enableSingleSourceIP=true` setting, you can now [set `local.subnet` to the `%zoneSubnet` variable and use the `local.zoneSubnet` to specify an IP address as a /32 subnet for each zone of the cluster](/docs/containers?topic=containers-vpn#strongswan_4).</li>
  </ul></td>
</tr>
</tbody></table>


## June 2019
{: #jun19}

<table summary="The table shows release notes. Rows are to be read from the left to right, with the date in column one, the title of the feature in column two and a description in column three.">
<caption>{{site.data.keyword.containerlong_notm}} documentation updates in June 2019</caption>
<thead>
<th>Date</th>
<th>Description</th>
</thead>
<tbody>
<tr>
  <td>24 June 2019</td>
  <td><ul>
  <li><strong>Calico network policies</strong>: Added a set of [public Calico policies](/docs/containers?topic=containers-network_policies#isolate_workers_public) and expanded the set of [private Calico policies](/docs/containers?topic=containers-network_policies#isolate_workers) to protect your cluster on public and private networks.</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `nginx-ingress` image to build 477](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Service limitations</strong>: Updated the [maximum number of pods per worker node limitation](/docs/containers?topic=containers-ibm-cloud-kubernetes-service-technology#tech_limits). For worker nodes that run Kubernetes 1.13.7_1527, 1.14.3_1524, or later and that have more than 11 CPU cores, the worker nodes can support 10 pods per core, up to a limit of 250 pods per worker node.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Added changelogs for [1.14.3_1524](/docs/containers?topic=containers-changelog#1143_1524), [1.13.7_1527](/docs/containers?topic=containers-changelog#1137_1527), [1.12.9_1558](/docs/containers?topic=containers-changelog#1129_1558), and [1.11.10_1563](/docs/containers?topic=containers-changelog#11110_1563) worker node patch updates.</li>
  </ul></td>
</tr>
<tr>
  <td>21 June 2019</td>
  <td><ul>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Accessing OpenShift clusters</strong>: Added steps for [automating access to an OpenShift cluster by using an OpenShift login token](/docs/openshift?topic=openshift-openshift-cli#openshift_cluster_login).</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Accessing the Kubernetes master through the private service endpoint</strong>: Added steps for [editing the local Kubernetes configuration file](/docs/containers?topic=containers-clusters#access_on_prem) when both the public and private service endpoints are enabled, but you want to access the Kubernetes master through the private service endpoint only.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>Troubleshooting OpenShift clusters</strong>: Added a [troubleshooting section](/docs/openshift?topic=openshift-openshift_troubleshoot) to the Creating a Red Hat OpenShift on IBM Cloud cluster tutorial.</li>
  </ul></td>
</tr>
<tr>
  <td>18 June 2019</td>
  <td><ul>
  <li><strong>CLI changelog</strong>: Updated the {{site.data.keyword.containerlong_notm}} CLI plug-in changelog page for the [release of versions 0.3.47 and 0.3.49](/docs/containers?topic=containers-cs_cli_changelog).</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `nginx-ingress` image to build 473 and `ingress-auth` image to build 331](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><strong>Managed add-on versions</strong>: Updated the version of the Istio managed add-on to 1.1.7 and the Knative managed add-on to 0.6.0.</li>
  <li><strong>Removing persistent storage</strong>: Updated the information for how you are billed when you [delete persistent storage](/docs/containers?topic=containers-cleanup).</li>
  <li><strong>Service bindings with private endpoint</strong>: [Added steps](/docs/containers?topic=containers-service-binding) for how to manually create service credentials with the private service endpoint when you bind the service to your cluster.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for [1.14.3_1523](/docs/containers?topic=containers-changelog#1143_1523), [1.13.7_1526](/docs/containers?topic=containers-changelog#1137_1526), [1.12.9_1557](/docs/containers?topic=containers-changelog#1129_1557), and [1.11.10_1562](/docs/containers?topic=containers-changelog#11110_1562) patch updates.</li>
  </ul></td>
</tr>
<tr>
  <td>14 June 2019</td>
  <td><ul>
  <li><strong>`kubectl` troubleshooting</strong>: Added a [troubleshooting topic](/docs/containers?topic=containers-cs_troubleshoot_clusters#kubectl_fails) for when you have a `kubectl` client version that is 2 or more versions apart from the server version or the OpenShift version of `kubectl`, which does not work with community Kubernetes clusters.</li>
  <li><strong>Tutorials landing page</strong>: Replaced the related links page with a new [tutorials landing page](/docs/containers?topic=containers-tutorials-ov) for all tutorials that are specific to {{site.data.keyword.containershort_notm}}.</li>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Tutorial to create a cluster and deploy an app</strong>: Combined the tutorials for creating clusters and deploying apps into one comprehensive [tutorial](/docs/containers?topic=containers-cs_cluster_tutorial).</li>
  <li><strong>Using existing subnets to create a cluster</strong>: To [reuse subnets from an unneeded cluster when you create a new cluster](/docs/containers?topic=containers-subnets#subnets_custom), the subnets must be user-managed subnets that you manually added from an on-premises network. All subnets that were automatically ordered during cluster creation are immediately deleted after you delete a cluster, and you cannot reuse these subnets to create a new cluster.</li>
  </ul></td>
</tr>
<tr>
  <td>12 June 2019</td>
  <td><strong>Aggregating cluster roles</strong>: Added steps for [extending users' existing permissions by aggregating cluster roles](/docs/containers?topic=containers-users#rbac_aggregate).</td>
</tr>
<tr>
  <td>07 June 2019</td>
  <td><ul>
  <li><strong>Access to the Kubernetes master through the private service endpoint</strong>: Added [steps](/docs/containers?topic=containers-clusters#access_on_prem) to expose the private service endpoint through a private load balancer. After you complete these steps, your authorized cluster users can access the Kubernetes master from a VPN or {{site.data.keyword.cloud_notm}} Direct Link connection.</li>
  <li><strong>{{site.data.keyword.BluDirectLink}}</strong>: Added {{site.data.keyword.cloud_notm}} Direct Link to the [VPN connectivity](/docs/containers?topic=containers-vpn) and [hybrid cloud](/docs/containers?topic=containers-hybrid_iks_icp) pages as a way to create a direct, private connection between your remote network environments and {{site.data.keyword.containerlong_notm}} without routing over the public internet.</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `ingress-auth` image to build 330](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>OpenShift beta</strong>: [Added a lesson](/docs/openshift?topic=openshift-openshift_tutorial#openshift_logdna_sysdig) about how to modify app deployments for privileged security context constraints for {{site.data.keyword.la_full_notm}} and {{site.data.keyword.mon_full_notm}} add-ons.</li>
  </ul></td>
</tr>
<tr>
  <td>06 June 2019</td>
  <td><ul>
  <li><strong>Fluentd changelog</strong>: Added a [Fluentd version changelog](/docs/containers?topic=containers-cluster-add-ons-changelog#fluentd_changelog).</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `nginx-ingress` image to build 470](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  </ul></td>
</tr>
<tr>
  <td>05 June 2019</td>
  <td><ul>
  <li><strong>CLI reference</strong>: Updated the [CLI reference page](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli) to reflect multiple changes for the [release of version 0.3.34](/docs/containers?topic=containers-cs_cli_changelog) of the {{site.data.keyword.containerlong_notm}} CLI plug-in.</li>
  <li><img src="images/logo_openshift.svg" alt="OpenShift icon" width="15" style="width:15px; border-style: none"/> <strong>New! Red Hat OpenShift on IBM Cloud clusters</strong>: With the Red Hat OpenShift on IBM Cloud beta, you can create {{site.data.keyword.containerlong_notm}} clusters with worker nodes that come installed with the OpenShift container orchestration platform software. You get all the advantages of managed {{site.data.keyword.containerlong_notm}} for your cluster infrastructure environment, along with the [OpenShift tooling and catalog ![External link icon](../icons/launch-glyph.svg "External link icon")](https://docs.openshift.com/container-platform/3.11/welcome/index.html) that runs on Red Hat Enterprise Linux for your app deployments. To get started, see [Tutorial: Creating a Red Hat OpenShift on IBM Cloud cluster](/docs/openshift?topic=openshift-openshift_tutorial).</li>
  </ul></td>
</tr>
<tr>
  <td>04 June 2019</td>
  <td><ul>
  <li><img src="images/logo_kubernetes.svg" alt="Kubernetes icon" width="15" style="width:15px; border-style: none"/> <strong>Version changelogs</strong>: Updated the changelogs for the [1.14.2_1521](/docs/containers?topic=containers-changelog#1142_1521), [1.13.6_1524](/docs/containers?topic=containers-changelog#1136_1524), [1.12.9_1555](/docs/containers?topic=containers-changelog#1129_1555), and [1.11.10_1561](/docs/containers?topic=containers-changelog#11110_1561) patch releases.</li></ul>
  </td>
</tr>
<tr>
  <td>03 June 2019</td>
  <td><ul>
  <li><strong>Bringing your own Ingress controller</strong>: Updated the [steps](/docs/containers?topic=containers-ingress-user_managed) to reflect changes to the default community controller and to require a health check for controller IP addresses in multizone clusters.</li>
  <li><strong>{{site.data.keyword.cos_full_notm}}</strong>: Updated the [steps](/docs/containers?topic=containers-object_storage#install_cos) to install the {{site.data.keyword.cos_full_notm}} plug-in with or without the Helm server, Tiller.</li>
  <li><strong>Ingress ALB changelog</strong>: Updated the [ALB `nginx-ingress` image to build 467](/docs/containers?topic=containers-cluster-add-ons-changelog#alb_changelog).</li>
  <li><strong>Kustomize</strong>: Added an example of [reusing Kubernetes configuration files across multiple environments with Kustomize](/docs/containers?topic=containers-app#kustomize).</li>
  <li><strong>Razee</strong>: Added [Razee ![External link icon](../icons/launch-glyph.svg "External link icon")](https://github.com/razee-io/Razee) to the supported integrations to visualize deployment information in the cluster and to automate the deployment of Kubernetes resources. </li></ul>
  </td>
</tr>
</tbody></table>


## May 2019
{: #may19}

<table summary="The table shows release notes. Rows are to be read from the left to right, with the date in column one, the title of the feature in column two and a description in column three.">
<caption>{{site.data.keyword.containerlong_notm}} documentation updates in May 2019</caption>
<thead>
<th>Date</th>
<th>Description</th>
</thead>
<tbody>
<tr>
  <td>30 May 2019</td>
  <td><ul>
  <li><strong>CLI reference</strong>: Updated the [CLI reference page](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli) to reflect multiple changes for the [release of version 0.3.33](/docs/containers?topic=containers-cs_cli_changelog) of the {{site.data.keyword.containerlong_notm}} CLI plug-in.</li>
  <li><strong>Troubleshooting storage</strong>: <ul>
  <li>Added a file and block storage troubleshooting topic for [PVC pending states](/docs/containers?topic=containers-cs_troubleshoot_storage#file_pvc_pending).</li>
  <li>Added a block storage troubleshooting topic for when [an app cannot access or write to PVC](/docs/containers?topic=containers-cs_troubleshoot_storage#block_app_failures).</li>
  </ul></li>
  </ul></td>
</tr>
<tr>
  <td>28 May 2019</td>
  <td><ul>
  <li><strong>Cluster add-ons changelog</strong>: Updated the [ALB `nginx-ingress` image to build 462](/docs/containers?topic=containers-cluster-add-ons-changelog).</li>
  <li><strong>Troubleshooting registry</strong>: Added a [troubleshooting topic](/docs/containers?topic=containers-cs_troubleshoot_clusters#ts_image_pull_create) for when your cluster cannot pull images from {{site.data.keyword.registryfull}} due to an error during cluster creation.
  </li>
  <li><strong>Troubleshooting storage</strong>: <ul>
  <li>Added a topic for [debugging persistent storage failures](/docs/containers?topic=containers-cs_troubleshoot_storage#debug_storage).</li>
  <li>Added a troubleshooting topic for [PVC creation failures due to missing permissions](/docs/containers?topic=containers-cs_troubleshoot_storage#missing_permissions).</li>
  </ul></li>
  </ul></td>
</tr>
<tr>
  <td>23 May 2019</td>
  <td><ul>
  <li><strong>CLI reference</strong>: Updated the [CLI reference page](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli) to reflect multiple changes for the [release of version 0.3.28](/docs/containers?topic=containers-cs_cli_changelog) of the {{site.data.keyword.containerlong_notm}} CLI plug-in.</li>
  <li><strong>Cluster add-ons changelog</strong>: Updated the [ALB `nginx-ingress` image to build 457](/docs/containers?topic=containers-cluster-add-ons-changelog).</li>
  <li><strong>Cluster and worker states</strong>: Updated the [Logging and monitoring page](/docs/containers?topic=containers-health#states) to add reference tables about cluster and worker node states.</li>
  <li><strong>Cluster planning and creation</strong>: You can now find information about cluster planning, creation, and removal and network planning in the following pages:
    <ul><li>[Planning your cluster network setup](/docs/containers?topic=containers-plan_clusters)</li>
    <li>[Planning your cluster for high availability](/docs/containers?topic=containers-ha_clusters)</li>
    <li>[Planning your worker node setup](/docs/containers?topic=containers-planning_worker_nodes)</li>
    <li>[Creating clusters](/docs/containers?topic=containers-clusters)</li>
    <li>[Adding worker nodes and zones to clusters](/docs/containers?topic=containers-add_workers)</li>
    <li>[Removing clusters](/docs/containers?topic=containers-remove)</li>
    <li>[Changing service endpoints or VLAN connections](/docs/containers?topic=containers-cs_network_cluster)</li></ul>
  </li>
  <li><strong>Cluster version updates</strong>: Updated the [unsupported versions policy](/docs/containers?topic=containers-cs_versions) to note that you cannot update clusters if the master version is three or more versions behind the oldest supported version. You can view if the cluster is **unsupported** by reviewing the **State** field when you list clusters.</li>
  <li><strong>Istio</strong>: Updated the [Istio page](/docs/containers?topic=containers-istio) to remove the limitation that Istio does not work in clusters that are connected to a private VLAN only. Added a step to the [Updating managed add-ons topic](/docs/containers?topic=containers-managed-addons#updating-managed-add-ons) to re-create Istio gateways that use TLS sections after the update of the Istio managed add-on is complete.</li>
  <li><strong>Popular topics</strong>: Replaced the popular topics with this release notes page for new features and updates that are specific to {{site.data.keyword.containershort_notm}}. For the latest information on {{site.data.keyword.cloud_notm}} products, check out the [Announcements](https://www.ibm.com/cloud/blog/announcements).</li>
  </ul></td>
</tr>
<tr>
  <td>20 May 2019</td>
  <td><ul>
  <li><strong>Version changelogs</strong>: Added [worker node fix pack changelogs](/docs/containers?topic=containers-changelog).</li>
  </ul></td>
</tr>
<tr>
  <td>16 May 2019</td>
  <td><ul>
  <li><strong>CLI reference</strong>: Updated the [CLI reference page](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli) to add COS endpoints for `logging collect` commands and to clarify that `cluster master refresh` restarts the Kubernetes master components.</li>
  <li><strong>Unsupported: Kubernetes version 1.10</strong>: [Kubernetes version 1.10](/docs/containers?topic=containers-cs_versions#cs_v114) is now unsupported.</li>
  </ul></td>
</tr>
<tr>
  <td>15 May 2019</td>
  <td><ul>
  <li><strong>Default Kubernetes version</strong>: The default Kubernetes version is now 1.13.6.</li>
  <li><strong>Service limits</strong>: Added a [service limitations topic](/docs/containers?topic=containers-ibm-cloud-kubernetes-service-technology#tech_limits).</li>
  </ul></td>
</tr>
<tr>
  <td>13 May 2019</td>
  <td><ul>
  <li><strong>Version changelogs</strong>: Added that new patch updates are available for [1.14.1_1518](/docs/containers?topic=containers-changelog#1141_1518), [1.13.6_1521](/docs/containers?topic=containers-changelog#1136_1521), [1.12.8_1552](/docs/containers?topic=containers-changelog#1128_1552), [1.11.10_1558](/docs/containers?topic=containers-changelog#11110_1558), and [1.10.13_1558](/docs/containers?topic=containers-changelog#11013_1558).</li>
  <li><strong>Worker node flavors</strong>: Removed all [virtual machine worker node flavors](/docs/containers?topic=containers-planning_worker_nodes#vm) that are 48 or more cores per [cloud status ![External link icon](../icons/launch-glyph.svg "External link icon")](https://cloud.ibm.com/status?component=containers-kubernetes&selected=status). You can still provision [bare metal worker nodes](/docs/containers?topic=containers-plan_clusters#bm) with 48 or more cores.</li></ul></td>
</tr>
<tr>
  <td>08 May 2019</td>
  <td><ul>
  <li><strong>API</strong>: Added a link to the [global API swagger docs ![External link icon](../icons/launch-glyph.svg "External link icon")](https://containers.cloud.ibm.com/global/swagger-global-api/#/).</li>
  <li><strong>Cloud Object Storage</strong>: [Added a troubleshooting guide for Cloud Object Storage](/docs/containers?topic=containers-cs_troubleshoot_storage#cos_pvc_pending) in your {{site.data.keyword.containerlong_notm}} clusters.</li>
  <li><strong>Kubernetes strategy</strong>: Added a topic about [What knowledge and technical skills are good to have before I move my apps to {{site.data.keyword.containerlong_notm}}?](/docs/containers?topic=containers-strategy#knowledge).</li>
  <li><strong>Kubernetes version 1.14</strong>: Added that the [Kubernetes 1.14 release](/docs/containers?topic=containers-cs_versions#cs_v114) is certified.</li>
  <li><strong>Reference topics</strong>: Updated information for various service binding, `logging`, and `nlb` operations in the [user access](/docs/containers?topic=containers-access_reference) and [CLI](/docs/containers?topic=containers-cli-plugin-kubernetes-service-cli) reference pages.</li></ul></td>
</tr>
<tr>
  <td>07 May 2019</td>
  <td><ul>
  <li><strong>Cluster DNS provider</strong>: [Explained the benefits of CoreDNS](/docs/containers?topic=containers-cluster_dns) now that clusters that run Kubernetes 1.14 and later support only CoreDNS.</li>
  <li><strong>Edge nodes</strong>: Added private load balancer support for [edge nodes](/docs/containers?topic=containers-edge).</li>
  <li><strong>Free clusters</strong>: Clarified where [free clusters](/docs/containers?topic=containers-regions-and-zones#regions_free) are supported.</li>
  <li><strong>New! Integrations</strong>: Added and restructure information about [{{site.data.keyword.cloud_notm}} services and third-party integrations](/docs/containers?topic=containers-ibm-3rd-party-integrations), [popular integrations](/docs/containers?topic=containers-supported_integrations), and [partnerships](/docs/containers?topic=containers-service-partners).</li>
  <li><strong>New! Kubernetes version 1.14</strong>: Create or update your clusters to [Kubernetes 1.14](/docs/containers?topic=containers-cs_versions#cs_v114).</li>
  <li><strong>Deprecated Kubernetes version 1.11</strong>: [Update](/docs/containers?topic=containers-update) any clusters that run [Kubernetes 1.11](/docs/containers?topic=containers-cs_versions#cs_v111) before they become unsupported.</li>
  <li><strong>Permissions</strong>: Added an FAQ, [What access policies do I give my cluster users?](/docs/containers?topic=containers-faqs#faq_access)</li>
  <li><strong>Worker pools</strong>: Added instructions for how to [apply labels to existing worker pools](/docs/containers?topic=containers-add_workers#worker_pool_labels).</li>
  <li><strong>Reference topics</strong>: To support new features such as Kubernetes 1.14, [changelog](/docs/containers?topic=containers-changelog#changelog) reference pages are updated.</li></ul></td>
</tr>
<tr>
  <td>01 May 2019</td>
  <td><strong>Assigning infrastructure access</strong>: Revised the [steps to assign IAM permissions for opening support cases](/docs/containers?topic=containers-users#infra_access).</td>
</tr>
</tbody></table>


