# cert-manager
- quay.io/jetstack/cert-manager-cainjector:v1.2.0 -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-cainjector:v1.2.0
- quay.io/jetstack/cert-manager-controller:v1.2.0 -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-controller:v1.2.0
- quay.io/jetstack/cert-manager-webhook:v1.2.0 -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-webhook:v1.2.0

```
kubectl apply -n argocd -f https://raw.githubusercontent.com/huoshan12345/k8s-controllers-install-cn/master/cert-manager/install.yaml
```