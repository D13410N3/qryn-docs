# About 


### Motivation

**qryn** _(formerly known as cLoki)_ is a project incubated at _qxip_ built by _ClickHouse users_ for _ClickHouse users_.

?> It's pronounced /ˈkwɪr..ɪŋ/ or _querying_

Started in 2018 as a _proof-of-concept_ artwork to display the vast capabilities of Clickhouse, it evolved through Covid times 2020-2022 into an fully featured stack for real-life workloads, leveraging the _lightness_ of NodeJS for its API and the _raw power_ of Clickhouse to perform heavy-duty tasks.

- 📦 A _high-performance_ version of qryn developed in go is separately available for [integrator licensing](mailto:info@qxip.net).

### Design

**qryn** implements a complete LogQL API buffered by a fast bulking **LRU** sitting on top of **ClickHouse** tables and relying on its *columnar search and insert performance alongside solid distribution and clustering capabilities* for stored data. qryn does not parse or index incoming logs, but rather groups log streams using the same label system as Prometheus and supports LogQL, PromQL and Tempo APIs for querying data back.

On top of this dataset, multiple ingestion APIs and query languages are implemented, such as _PromQL, Tempo, Influx, Elastic and others._

<p align="center">
  <img src="https://user-images.githubusercontent.com/1423657/54091852-5ce91000-4385-11e9-849d-998c1e5d3243.png" />
</p>

#### Contributors

qryn is made possible by its community of contributors and users - we love you all 🫀

<a href="https://github.com/lmangani/qryn/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=metrico/qryn" />
  <img src="https://contributors-img.web.app/image?repo=metrico/qryn" />
</a>

------

#### Disclaimers

©️ QXIP BV, released under the GNU Affero General Public License v3.0. See [LICENSE](LICENSE) for details.
<div style="font-size: 12px;">
- qryn is not affiliated or endorsed by Grafana Labs or ClickHouse Inc. All rights belong to their respective owners.<br>
- qryn is a 100% clear-room api implementation and does not fork, use or derivate from Grafana Loki code or concepts.<br>
- Grafana®, Loki™ and Tempo® are a Trademark of Raintank, Grafana Labs. <br>
- ClickHouse® is a trademark of ClickHouse Inc. <br>
- Prometheus is a trademark of The Linux Foundation.<br>
</div>
