# Rolling-Updates-Configs
Config files for rolling updates in Kubernetes cluster

Commands to test rolling updates
* `kubectl set image deployment/deployment-definition front-end=darwin/rss-php-nginx:v1 --record`

* `kubectl create -f deployment-definition.yml`

* `kubectl get deployments`
* `kubectl apply -f deployment-definition.yml`
