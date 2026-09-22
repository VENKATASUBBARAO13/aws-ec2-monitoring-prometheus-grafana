# Grafana dashboards

Create or import your dashboard in Grafana, export it as JSON, and save it in this directory.

Recommended panels:
- CPU utilization (Node Exporter / CloudWatch)
- Memory used and available
- Disk space usage
- Network receive/transmit
- Node Exporter target availability
- EC2 CloudWatch metrics

Before committing exported dashboard JSON, check that it contains no credentials, account-specific identifiers, or sensitive URLs.
