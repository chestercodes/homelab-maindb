# homelab-maindb

Helm charts for deploying a postgres instance with optional exporter.

## interesting features

- different values files for different environments and cluster types
- kubernetes job that runs after sync and runs scripts to setup database
- sync job to tell workflow reporter that sync has passed or failed
- dashboard deployed as config map with grafana