* You can setup your local cluster for dev with `minikube start`
* Then you can run can create deployments with e.g `kubectl create deployment hello-node --image=registry.k8s.io/e2e-test-images/agnhost:2.39 -- /agnhost netexec --http-port=8080`
* You can view and inspect resources with `kubctl get <resource>` e.g. `kubectl get deployment`
