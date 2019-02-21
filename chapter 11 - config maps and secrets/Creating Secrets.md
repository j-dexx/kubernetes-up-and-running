Creating secrets

    kubectl create secret generic kuard-tls --from-file=kuard.crt --from-file=kuard.key
    kubectl create secret docker-registry my-image-pull-secret --docker-username=username --docker-password=password --docker-email=email-address

Can also use `from-literal=key=value`

Get secrets (includes raw data)

    kubectl get secret kuard-tls -o yaml
