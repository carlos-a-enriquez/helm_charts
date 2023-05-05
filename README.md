# helm_charts

## Modified Liqo Helm Chart

- [Original repository](https://github.com/liqotech/liqo)
- [Forked repository](https://github.com/carlos-a-enriquez/liqo)


## How to install this forked Liqo Helm chart

```bash
#Add repo to local
helm repo add liqo-fork https://carlos-a-enriquez.github.io/helm_charts/
helm repo update

#Installation
helm install liqo-fork liqo-fork/liqo \
--namespace liqo \
--values values.yaml \
--create-namespace 
```
