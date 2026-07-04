# mos-docker-templates

Docker-App-Store-Templates (JSON-Format) für MOS, gepflegt von [anym001](https://github.com/anym001).

## Enthaltene Templates

| Template | Image | Beschreibung |
|---|---|---|
| [bitcoind](docker/bitcoind.json) | `ghcr.io/anym001/docker-bitcoind` | Voller Bitcoin-Core-Node |
| [electrs](docker/electrs.json) | `ghcr.io/anym001/docker-electrs` | Electrum-Server (Rust), Companion zu bitcoind |
| [healthlog](docker/healthlog.json) | `ghcr.io/anym001/healthlog` | Self-hosted Analyse-Engine für Apple-Health-Daten |
| [pocketlog](docker/pocketlog.json) | `ghcr.io/anym001/pocketlog` | Self-hosted Haushaltsbuch (PWA) |
| [pocketlog-importer](docker/pocketlog-importer.json) | `ghcr.io/anym001/pocketlog-importer` | Bank-CSV-Import-Companion für PocketLog |
| [portfolio-performance](docker/portfolio-performance.json) | `ghcr.io/ich777/portfolio-performance` | Portfolio-Tracking-Tool (Drittanbieter-Image) |
| [teddycloud](docker/teddycloud.json) | `ghcr.io/toniebox-reverse-engineering/teddycloud` | Selbst gehosteter Toniebox-Cloud-Ersatz (Drittanbieter-Image) |

## Lizenz / Haftung

Diese Templates werden ohne Gewähr bereitgestellt. Für die zugrundeliegenden Anwendungen gelten jeweils deren eigene Lizenzen.
