# Helm chart for mongo-express

## Usage

Run a kubernetes pod with mongo-express connected to a mongodb server:

```
helm install mongo-express --set adminUsername=root --set adminPassword=example --set server=my_mongodb_hostname
```
