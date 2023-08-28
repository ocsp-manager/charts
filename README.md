# ocsp-manager charts

Chart to install `ocsp-manager`

```
helm repo add ocsp-manager https://ocsp-manager.github.io/charts/
helm repo update

helm upgrade --install --create-namespace -n ocsp-manager --values=values-production.yaml ocsp-manager ocsp-manager/ocsp-manager
helm -n ocsp-manager uninstall ocsp-manager
```
