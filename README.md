# pq-graph

Connecting the dots across your digital infrastructure.

pq-graph combines data from multiple discovery and scanning tools into a unified view of an organization's external infrastructure. It connects hosts, services, certificates, cryptographic configurations, and potential third-party providers to reveal relationships and dependencies that individual tools cannot show on their own.

Built to complement pq-map and pq-pulse, it helps organizations understand not only what is exposed, but also how their digital infrastructure is connected and who may be operating it.

## Usage

```sh
./pq-graph.sh [graph.json] [port]
```

- `graph.json` — path to the inventory file (default: `graph.json` in the working directory)
- `port` — HTTP port (default: `PORT` environment variable, else `8000`)
