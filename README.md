#### create secret with base64

- go to cmd
- echo -n 'username' | base64
- echo -n 'password' | base64

### run app

- before run application need to run secret file
- kubectl apply -f monogo-secret.yaml
- kubectl get secret
- kubectl apply -f monogo.yaml
- kubectl get all
- kubectl get service
- kubectl describe service serviceName
- kubectl get all | grep mongodb
- create for configmap file
- apply this for set config
- kubectl apply -f mongo-configmap.yaml
- apply this for run contianer
- kubectl apply -f monogo-express.yaml
- kubectl get pod
- if all is okey then try to run as external ip
- minikube service mongo-express-service

- chenge the active namespace with:
- kubectl config set-context --currnt --namespace=my-namespace
- need to install kubectx
- suto apt-get install kubectx
-
