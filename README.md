## Set kubectl namespace

```shell
kubectl config set-context --current --namespace=nocensurasuritaly-solitarygoat
```

## Create secrets

```shell
kubectl create secret generic database-secrets \
  --from-file=database-password=./database-password.txt
```
