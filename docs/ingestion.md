# 🔻 Data Ingestion

Ingesting data with **qryn** is easy and painless. _Choose a supported integration and start shipping._

<!-- tabs:start -->

#### ** Logs **

Get started using the [Log Ingestion](logs/ingestion.md) section

[![image](https://user-images.githubusercontent.com/1423657/185749193-faa91e58-4283-479a-8196-bae5212ae141.png ':size=100')](logs/ingestion#popular)
[![image](https://user-images.githubusercontent.com/1423657/184496222-ca95d80c-906f-4c77-a963-86f0b27a56b0.png ':size=100')](logs/ingestion#grafana)
[![image](https://user-images.githubusercontent.com/1423657/184496304-4f35a365-efdc-4dca-9771-6b7b1deb9ae3.png ':size=100')](logs/ingestion#elastic)
[![image](https://user-images.githubusercontent.com/1423657/184496174-aca323dd-f40e-489a-a584-fa7348c0eab0.png ':size=100')](logs/ingestion#influx)
[![image](https://avatars.githubusercontent.com/u/54801242?s=200&v=4 ':size=100')](logs/ingestion#clickhouse)


#### ** Metrics **

Get started using the [Metrics Ingestion](metrics/ingestion.md) section

[![image](https://user-images.githubusercontent.com/1423657/184496222-ca95d80c-906f-4c77-a963-86f0b27a56b0.png ':size=100')](metrics/ingestion#logql)
[![image](https://user-images.githubusercontent.com/1423657/184496973-9f46e551-872d-4a25-877c-51a2e5f53e84.png ':size=100')](metrics/ingestion#prometheus)
[![image](https://user-images.githubusercontent.com/1423657/184496174-aca323dd-f40e-489a-a584-fa7348c0eab0.png ':size=100')](metrics/ingestion#influx)
[![image](https://avatars.githubusercontent.com/u/54801242?s=200&v=4 ':size=100')](metrics/ingestion#clickhouse)

#### ** Telemetry **

Get started using the [Telemetry Ingestion](telemetry/ingestion.md) section

[![image](https://user-images.githubusercontent.com/1423657/184496222-ca95d80c-906f-4c77-a963-86f0b27a56b0.png ':size=100')](telemetry/ingestion#grafana)
[![image](https://user-images.githubusercontent.com/1423657/184494381-15d20f5d-3d52-411b-9064-dfd2ccea7c1c.png ':size=100')](telemetry/ingestion#zipkin)
[![image](https://user-images.githubusercontent.com/1423657/184494438-17d7ceb0-a62a-4819-9b1c-43d7f0baf802.png ':size=100')](telemetry/ingestion#zipkin)
[![image](https://avatars.githubusercontent.com/u/54801242?s=200&v=4 ':size=100')](telemetry/ingestion#clickhouse)

#### ** Custom **

Missing an ingestion API? Open a [feature request](https://github.com/metrico/qryn/issues) or a PR with your work.

![image](https://user-images.githubusercontent.com/1423657/184502410-eacd247e-e046-4cdb-9e0c-39411e02d734.png ':size=100')

<!-- tabs:end -->

?> **qryn** APIs are compatible with [many observability ingestion formats](support.md)

| Client  | Logs  | Metrics | Traces  |
|---|:-:|:-:|:-:|
| [Grafana Agent](https://grafana.com/docs/grafana-cloud/data-configuration/logs/collect-logs-with-agent/)  | 🟢 | 🟢 | 🟢 |
| [OpenTelemetry](https://github.com/metrico/otel-collector)  | 🟢 | 🟢 | 🟢 |
| [Vector/Datadog](https://vector.dev/docs/reference/configuration/sinks/loki/)  | 🟢 | 🟢 |   |
| [Telegraf/Influx](https://docs.influxdata.com/telegraf/v1.21/introduction/getting-started/)  | 🟢 | 🟢 |   |
| [Logstash/Elastic](https://grafana.com/docs/loki/latest/clients/logstash/)  | 🟢 | 🟢 |   |
| [paStash](https://github.com/sipcapture/paStash/wiki/Example:-Loki)  | 🟢 | 🟢 |   |
| [Promtail](https://grafana.com/docs/grafana-cloud/data-configuration/logs/collect-logs-with-promtail/)  | 🟢 |   |   |
| [Promtail Lambda](https://grafana.com/docs/loki/latest/clients/lambda-promtail/) | 🟢 |   |   |
| [Fluentd](https://grafana.com/docs/loki/latest/clients/fluentd/)  | 🟢 |   |   |
| [Docker](https://grafana.com/docs/loki/latest/clients/docker-driver/)  | 🟢 |   |   |
| [Cloudflare Logpush](https://github.com/metrico/cloudflare-worker-logpush-loki) | 🟢  |   |   |
| [Curl](https://github.com/metrico/qryn/wiki/HTTP-API#api-examples) | 🟢 | 🟢 | 🟢 |

<img src="https://user-images.githubusercontent.com/1423657/184487816-fcc86e34-0395-4927-8ceb-33c2ad3e63d4.gif" width=600 />
