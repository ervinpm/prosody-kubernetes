# Prosody (XMPP) Kubernetes configuration

## How to use

1. Update the values with your domain (i.e. example.com)

2. This configuration assumes that dynamic nfs subdirectory is already in place

```sh
$ kubectl apply -f pvc.yaml
```

3. This configuration assumes that cert manager is already installed

```sh
$ kubectl apply -f certificate.yaml
```

4. Apply deployment

```sh
$ kubectl apply -f deployment.yaml
```

5. Apply service

```sh
$ kubectl apply -f service.yaml
```
