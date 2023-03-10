## Dashboard Image
<img src =./images/cadvisor.png width=50%/><br>
<img src =./images/node_exporter.png width=50%/><br>

This script will install the monitoring kit for grafana dashboard, it will include:

## Resources Monitoring
- Prometheus
- Node_Exporter
- Cadvisor

## Logging Monitoring
- Loki
- Promtail

## Docker Compose Version, Include
- Cadvisor
- Loki
- Prometheus
- Promtail

## Grafana Dashboard
- [Cadvisor Dashboard](https://grafana.com/grafana/dashboards/14282-cadvisor-exporter)
- [Node Exporter Dashboard](https://grafana.com/grafana/dashboards/1860-node-exporter-full)

### Installation Reference:
- https://computingforgeeks.com/how-to-install-prometheus-and-node-exporter-on-debian/
- https://citizix.com/how-to-setup-promtail-grafana-and-loki-for-free-log-management-in-debian-11/

## Server Environment
This has been tested in machine with spesification below:
```
PRETTY_NAME="Ubuntu 22.04 LTS"
NAME="Ubuntu"
VERSION_ID="22.04"
VERSION="22.04 LTS (Jammy Jellyfish)"
VERSION_CODENAME=jammy
ID=ubuntu
ID_LIKE=debian
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
UBUNTU_CODENAME=jammy

Linux 5.15.0-1028-aws #32-Ubuntu SMP Mon Jan 9 12:28:07 UTC 2023 x86_64 x86_64 x86_64 GNU/Linux

docker --version
Docker version 20.10.17, build 100c701

docker-compose --version
docker-compose version 1.29.2, build unknown
```

Note: 
That the monitoring kit maybe will not working properly in another operating system, and it will use the default configuration only, you can customize the configuration before start installing

Credits: M Taufiq Permana Sumarna - February 2023