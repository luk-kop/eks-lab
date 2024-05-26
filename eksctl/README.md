# eksctl

## Documentation
- The `ClusterConfig` file schema - [eksctl docks](https://eksctl.io/usage/schema/)
- The `ClusterConfig` file examples - [eksctl GitHub](https://github.com/eksctl-io/eksctl/tree/main/examples)
- The `eksctl` EKS Add-Ons - [eksctl docks](https://eksctl.io/usage/addons/)

Command examples:
- Check `eksctl` version:
```bash
eksctl version
```
- Create EKS cluster from file:
```bash
eksctl create cluster -f cluster-config.yaml
```
- Delete EKS cluster:
```bash
eksctl delete cluster -f cluster-config.yaml
```
- Listing EKS clusters:
```bash
eksctl get cluster
```

- Get the raw JSON schema
```bash
eksctl utils schema
```
