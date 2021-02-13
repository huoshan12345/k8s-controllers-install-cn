### cert-manager
- quay.io/jetstack/cert-manager-cainjector -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-cainjector
- quay.io/jetstack/cert-manager-controller -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-controller
- quay.io/jetstack/cert-manager-webhook -> quay.mirrors.ustc.edu.cn/jetstack/cert-manager-webhook

```
kubectl apply -f https://raw.githubusercontent.com/huoshan12345/k8s-controllers-install-cn/master/cert-manager/install.yaml
```
---

### cert-manager-tke 
适用于腾讯云
- quay.io/jetstack/cert-manager-cainjector -> quay.tencentcloudcr.com/jetstack/cert-manager-cainjector
- quay.io/jetstack/cert-manager-controller -> quay.tencentcloudcr.com/jetstack/cert-manager-controller
- quay.io/jetstack/cert-manager-webhook -> quay.tencentcloudcr.com/jetstack/cert-manager-webhook

```
kubectl apply -f https://raw.githubusercontent.com/huoshan12345/k8s-controllers-install-cn/master/cert-manager/install-tke.yaml
```