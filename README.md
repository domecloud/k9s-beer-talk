# k9s-beer-talk
Kubeernetes Beer Talk Demo by [DomeCloud](https://dome.cloud)

Video on Facebook [LiveTube / Live! Kubeernetes
](https://www.facebook.com/livetubethailand/videos/2061413037459464/)

---
## NFS Dynamic Provisioning

Create ClusterRole and ClusterRoleBinding

```
kubectl apply -f ClusterRole.yaml
```

Create ServiceAccount

```
kubectl apply -f ServiceAccount.yaml
```

Deploy NFS Provisioner

```
kubectl apply -f Deployment.yaml
```

Create StorageClass

```
kubectl apply -f StorageClass.yaml
```

Claim Volume

```
kubectl apply -f Claim.yaml
```

---

## MySQL Cluster

```
kubectl apply -f galera-cluster.yaml
```

## WordPress on K8S

```
kubectl apply -f WordPress.yaml
```

## Monitoring K8S

Monitoring Kubernetes clusters on AWS, GCP and Azure using Prometheus Operator and Grafana [camilb/prometheus-kubernetes](https://github.com/camilb/prometheus-kubernetes)

```
git clone https://github.com/camilb/prometheus-kubernetes.git
cd prometheus-kubernetes
./deploy
```

## Alerting

Demo
