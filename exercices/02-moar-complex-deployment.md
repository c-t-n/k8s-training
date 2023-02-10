# Your first deployment

## Exercice

Create a manifest file that ensure the following:

- We want a Postgresql database in our cluster.
- Our postgres must run with the latest alpine version 
- We want a 5Gib mounted volume a the right place to persist data
- We want the following configuration

```
Username: fortytwo
Password: @ndTh4nks4TheF1sh!
Initial database: intra_v4_production
```


Your manifest file can be pushed to your cluster by doing:

```
$> kubectl apply -f <your-manifest-file>.yaml
```