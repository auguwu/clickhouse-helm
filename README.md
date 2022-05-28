# 🏚️ Helm Chart for ClickHouse
> *Production-ready Helm chart for deploying ClickHouse onto a Kubernetes cluster! ヽ(>∀<☆)ノ*

## Requirements
- **Kubernetes** >=1.22
- **Helm** 3

## Installation
All releases are deployed onto **charts.noelware.org**:

```shell
# 1. Index the repositories for my projects. Since the official instance uses
# chart-based repositories!
$ helm repo add noel https://charts.noelware.org/noel

# 2. Install ClickHouse
$ helm install clickhouse noel/clickhouse
```

And, you should be set!

## License
**clickhouse-helm** is released under the **MIT License** with love by Noel. :3
