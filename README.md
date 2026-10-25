# Node-RED Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Node-RED cookbook** for flow-based automation for geospatial and IoT triggers. Patterns are drawn from the ZQM fleet's Node-RED 5.0.9 installs (Node-1 on port 1980, Node-3 on port 1880). It is intended for Engineers who wire sensors, APIs, and databases together as flows. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Node-RED patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Engineers who wire sensors, APIs, and databases together as flows.

## Prerequisites

- Node-RED 5.0.9
- A browser for the flow editor
- Postgres or MQTT for the integration passes

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-flow` | A first flow: inject, function, and debug nodes |
| 02 | `02-http-mqtt` | HTTP endpoints and MQTT subscriptions in flows |
| 03 | `03-postgres-flow` | Reading and writing Postgres from a flow |
| 04 | `04-credentialsecret` | Setting a custom credentialSecret before storing credentials in flows |

## Repository layout

```text
nodered-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [mosquitto-cookbook](https://github.com/ZQM-Computing/mosquitto-cookbook) — MQTT broker setup, listeners, and pub/sub patterns
- [prefect-cookbook](https://github.com/ZQM-Computing/prefect-cookbook) — Workflow orchestration, schedules, and deployments
- [postgis-cookbook](https://github.com/ZQM-Computing/postgis-cookbook) — Spatial indexing, joins & KNN, SRID management, vector tiles
