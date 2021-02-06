# argo-cd install cn
### 替换了在国内拉取不下来的镜像
- ghcr.io/dexidp/dex -> dexidp/dex

```
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/huoshan12345/argo-cd-install-cn/master/stable/manifests/install.yaml
```