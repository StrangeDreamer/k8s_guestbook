# k8s_guestbook
## A tutorial of k8s
### This startup id based on [io.k8s](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/)
1. **change file location to this repository like:**
```
$ kubectl apply -f https://k8s.io/examples/application/guestbook/redis-master-deployment.yaml
```
```
$ cd k8s_guestbook
$ sudo kubectl apply -f redis-master-deployment.yaml
```
2. change `--external-ip` in file frontend-service.yaml to your own VM public IP
