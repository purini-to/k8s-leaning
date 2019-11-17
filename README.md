# k8s-leaning

## Metrics Server Install

```bash
kubectl apply -f metrics-server
```

## Kubernates Dashboard Install

```bash
kubectl apply -f kubernetes-dashboard
```

You can access Dashboard using the kubectl command-line tool by running the following command:

```bash
kubectl proxy
```

Kubectl will make Dashboard available at http://localhost:8001/api/v1/namespaces/kubernetes-dashboard/services/https:kubernetes-dashboard:/proxy/.
