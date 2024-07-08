# service-mesh-gateways

This chart deploys OpenShift Service Mesh Ingress & Egress Gateways on
a given namespace, using [OpenShift Service Mesh Gateway Injection](https://docs.openshift.com/container-platform/4.14/service_mesh/v2x/ossm-traffic-manage.html#ossm-deploying-automatic-gateway-injection_traffic-management) capabilities.

It deploys the Deployment object along with other required
objects such as Service, RBAC, HPA, Network Policy or PDB.