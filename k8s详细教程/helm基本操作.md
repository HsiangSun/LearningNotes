# Helm常用操作
---
## Helm 查看资源
```shell
helm list -n <namespace>
```
## Helm 删除资源
```shell
helm uninstall <release> -n <namespace>
```

## Helm 查看资源状态
```shell
helm status <release> -n <namespace>
```

## Helm 回滚某个版本
```shell
helm rollback <release>  <version>
```

## Helm 更新
```shell
helm upgrade --install --namespace <namespace> <release> -f ./values-prod.yaml .
```



