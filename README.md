# Helm

## Resources

- [Helm Documentation](https://helm.sh/docs/)

## Notes

```
brew install go
brew install helm
brew install kind
brew install kubectl
brew install minikube
```

```
minikube start
```

```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install bitnami/postgresql --generate-name  
```

- A `Chart` is a Helm package. It contains all of the resource definitions necessary to run an application, tool, or service inside of a Kubernetes cluster.
- A `Repository` is the place where charts can be collected and shared.
- A `Release` is an instance of a chart running in a Kubernetes cluster.
- Helm installs `charts` into Kubernetes, creating a new `release` for each installation. And to find new charts, you can search Helm chart `repositories`.