# k8s_Voting_App
Project to deploy an application on kubernetes.

Commands to run:

> kubectl get pods
> kubectl get svc
> ls
> kubectl create -f voting-app-pod.yaml
> kubectl create -f voting-app-service.yaml
> kubectl get pods,svc
> minicube service voting-service --url

you can hit the url in your local browser.

> kubectl create -f redis-pod.yaml
> kubectl create -f redis-service.yaml
> kubectl create -f postgres-pod.yaml
> kubectl create -f postgres-service.yaml
> kubectl create -f worker-pod.yaml
> kubectl create -f result-app-pod.yaml
> kubectl create -f result-app-service.yaml

generate the url for results app
minicube service result-service --url
