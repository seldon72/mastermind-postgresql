# mastermind-postgresql
## mastermind-postgresql
### mastermind-postgresql

    $ kubectl create -f postgres-configmap.yaml 

    $ kubectl create -f postgres-storage.yaml

    $ kubectl create -f postgres-deployment.yaml

    $ kubectl create -f postgres-service.yaml

    $ kubectl get svc postgres


$ kubectl delete service postgres 
$ kubectl delete deployment postgres
$ kubectl delete configmap postgres-config
$ kubectl delete persistentvolumeclaim postgres-pv-claim
$ kubectl delete persistentvolume postgres-pv-volume