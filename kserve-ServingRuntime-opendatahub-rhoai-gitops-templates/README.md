# Summary

[KServe](https://github.com/kserve/kserve) provides a Kubernetes Custom Resource Definition for serving predictive and generative machine learning (ML) models.


[Open Data Hub](https://opendatahub.io/) is the open source upstream to OpenShift AI that helps bring Kserve and other AI related tools into OpenShift / Kubernetes.

# Difference

The OpenShift `Template` with the API `template.openshift.io/v1` is used to deploy the `ServingRuntime` resource into Open Data Hub / RHOAI dashboard.

Deploying a `ServingRuntime` directly will not display in the dashboard.