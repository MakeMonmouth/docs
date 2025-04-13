# MMSVR01

| Hostname:         | mmsvr01.int.makemonmouth.co.uk |
|-------------------|--------------------------------|
| IP Address:       | 10.232.123.10 |
| Contact:          | `@proffalken` on Discord |
| Donated on:       | 2024-01-08 |
| Donated By:       | [Edinburgh Remakery](https://www.edinburghremakery.org.uk) |
| Manufacturer:     | Cisco |
| Model:            | UCS220 M4 |
| Operating System: | Ubuntu Linux |
| CPU:              | 2 x Intel(R) Xeon(R) CPU E5-2609 v3 @ 1.90GHz (12 cores total) |
| RAM:              | 48GB
| Disk:             | 2 x 512GB SSD |

## Services

| Service Name | SystemD Name | Purpose | Owner (Discord Name) | More information |
|--------------|--------------|---------|----------------------|------------------|
| Github Runner | actions.runner.MakeMonmouth.mmsvr01.service | Deploy software and containers locally | `@proffalken` | [Github Self-hosted Runners](https://docs.github.com/en/actions/hosting-your-own-runners) |
| Grafana Alloy | alloy.service | Observability | `@proffalken` | [Grafana Alloy](https://grafana.com/docs/alloy/latest/) |
| Docker | docker-io.service | Container Management | `@proffalken` | [Docker Documentation](https://docs.docker.com/) |
