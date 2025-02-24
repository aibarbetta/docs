Supported Environments
======================

Kubecost requires a Kubernetes cluster to be deployed. 

## Supported Kubernetes versions

* Kubecost runs in any Kubernetes v1.8 (Aug 2017) or greater environment.
* Kubernetes 1.25 is officially supported as of v1.99.0

## Supported cluster types

* Managed Kubernetes clusters (e.g. EKS, GKE, AKS) *most common*
* Kubernetes distributions (e.g. OpenShift, DigitalOcean, Rancher, Tanzu)
* Bootstrapped Kubernetes cluster
* On-prem and air-gapped using custom [pricing sheets](https://docs.kubecost.com/install-and-configure/install/provider-installations/air-gapped#how-do-i-configure-prices-for-my-on-premise-assets)

## Supported Cloud Providers

* AWS (Amazon Web Services)
  * All regions supported, as shown in [opencost/pkg/cloud/awsprovider.go](https://github.com/opencost/opencost/blob/0c2f063052723a65ca62a4c75be23392806b6fac/pkg/cloud/awsprovider.go#L111)
  * x86, ARM
* GCP (Google Cloud Platform)
  * All regions supported, as shown in [opencost/pkg/cloud/gcpprovider.go](https://github.com/opencost/opencost/blob/0c2f063052723a65ca62a4c75be23392806b6fac/pkg/cloud/gcpprovider.go#L41)
  * x86
* Azure (Microsoft)
  * All regions supported, as shown in [opencost/pkg/cloud/azureprovider.go](https://github.com/opencost/opencost/blob/0c2f063052723a65ca62a4c75be23392806b6fac/pkg/cloud/azureprovider.go#L82)
  * x86

**This list is certainly not exhaustive!** This is simply a list of observations as to where our users run Kubecost based on their questions/feedback. Please [contact us](https://docs.kubecost.com/other-resources/contactus) with any questions!
