# nginx-ingress-sample
Repo for playing around with Nginx ingress controller and the new VirtualServer and VirtualServerRoutes resources

* httpbin.yaml - A Sample httpbin deployment with a service exposing the pod pon port 8000
* selfsigned-certificate.yaml - self signed certificate resource for cert-manager
* selfsigned-cluster-issuer.yaml - a clusteriwde self signed cert issues
* selfsigned-issuer.yaml - a namespace wide self-signed cert issuer
* virtualserver-simple.yaml - a simple virtual server with routes directly in the VirtualServer resource object
* virtualserver-w-vsroutes.yaml - a virtualserver which forwards traffic to virtualserverroute for more complex routing.
* vsroutes.yaml - the virtualserverroutes resources to be used along with the virtualserver-w-routes yaml sample 
