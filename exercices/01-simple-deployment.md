# Your first deployment

## Exercice

Create the required manifests file that ensure the following:

- You have to deploy the image `nginx:1.23-alpine` on your cluster
- Your deployment ensure the presence of 3 replicas on your cluster
- A service will ensure the fact that your nginx pods can be reached in your cluster with the address `nginx.dummyapp`

```
A service can be reached with the address "<service-name>.<namespace>"
```

Your manifest files can be pushed to your cluster by doing:

```
$> kubectl apply -f <your-manifest-file>.yaml
```