# Catenary Helm Values and Charts

Values used by Catenary hosting. Should be adapted based on your settings.

## Helm
```bash
helm repo add cockroachdb https://charts.cockroachdb.com/
helm install catenary -f cockroach-values.yaml cockroachdb/cockroachdb
```

## Etcd
```bash
helm install catenary-etcd -f etcd-values.yaml oci://registry-1.docker.io/bitnamicharts/etcd
```