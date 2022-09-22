```
kubectl create -n istio-system secret tls gateway-cert-aws-elb-dns --key=private.key --cert=certificate.crt
```

```
kubectl create -n istio-system secret tls gateway-cert-sni-dns --key=private.key --cert=certificate.crt
```