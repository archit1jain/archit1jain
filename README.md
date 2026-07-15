<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&pause=1000&color=00FF88&center=true&vCenter=true&width=900&lines=%24+ssh+archit%40github;%24+Loading+Distributed+Systems...;%24+Go+%E2%80%A2+Java+%E2%80%A2+Kafka+%E2%80%A2+Redis;%24+Building+Backend+Infrastructure..." alt="Typing SVG" />
</p>

```console
╭──────────────────────────────────────────────────────────────────────────╮
│ ● ● ●                                          ssh archit@github          │
├──────────────────────────────────────────────────────────────────────────┤
│ Last login: Wed Jul 15 22:31:07 2026 from 10.0.0.14                       │
│                                                                            │
│ Welcome to ArchitOS 3.2 LTS (GNU/Linux 6.9.0-backend x86_64)               │
│                                                                            │
│  * Documentation:  https://github.com/archit                             │
│  * Uptime:         6 years, 3 months, 14 days                            │
│                                                                            │
│ System load:  0.42     Processes:       118                              │
│ Usage of /:   71.2%    Users logged in:  1                               │
│                                                                            │
╰──────────────────────────────────────────────────────────────────────────╯
```

<br>

```bash
archit@github:~$ whoami
```

```
Backend Engineer.
Building distributed systems that stay up when everything else falls over.
Fluent in Go and Java. Comfortable at 2am reading a stack trace from a
service that's been running fine for two years.

Interested in: system design, database internals, consensus algorithms,
and teaching machines to page other machines instead of me.
```

<br>

```bash
archit@github:~$ uname -a
```

```
ArchitOS 3.2.0-backend #1 SMP PREEMPT Go/Java x86_64
Kernel: distributed-systems-6.9
Arch: latency-sensitive
Build flags: -O2 -Wall -Wobservability
```

<br>

## `$ tree /skills`

```text
/skills
├── backend/
│   ├── Go
│   ├── Java
│   ├── gRPC
│   ├── REST APIs
│   ├── Concurrency & Goroutines
│   └── Service Design
│
├── messaging/
│   ├── Kafka
│   ├── RabbitMQ
│   ├── NATS
│   └── Redis Streams
│
├── databases/
│   ├── PostgreSQL
│   ├── MySQL
│   ├── Redis
│   ├── Cassandra
│   └── DynamoDB
│
├── observability/
│   ├── Prometheus
│   ├── Grafana
│   └── OpenTelemetry
│
├── networking/
│   ├── TCP/IP
│   ├── BGP
│   ├── OSPF
│   ├── VXLAN
│   └── IPsec
│
├── ai-infra/
│   ├── Agentic Systems
│   ├── LLM Infrastructure
│   ├── RAG Pipelines
│   └── MCP
│
└── tooling/
    ├── Docker
    ├── Kubernetes (light use)
    ├── Git
    └── Linux
```

<br>

## `$ cat /etc/philosophy`

```text
1. Measure before you optimize.
2. Optimize before you scale.
3. A system you can't observe is a system you don't control.
4. Simple and boring beats clever and fragile.
5. Every queue has a consumer. Every consumer can fall behind.
6. Automate the repetitive. Document the irreversible.
```

<br>

## `$ ps aux`

```text
USER      PID  %CPU  %MEM  COMMAND
archit      1   2.1   1.4  /sbin/api-gateway
archit    102   6.7   3.2  grpc-server --workers=16
archit    118   4.3   2.8  kafka-consumer --group=events
archit    134   1.9   0.9  redis-cache --mode=cluster
archit    151   3.4   1.7  scheduler --cron
archit    177   5.0   4.1  raft-node --peer-count=5
archit    203   2.6   1.1  ai-agent --model=mcp-orchestrator
archit    229   0.4   0.3  log-shipper
```

<br>

## `$ netstat -tulpn`

```text
Proto  Local Address     State    PID/Program
tcp    0.0.0.0:8080      LISTEN   102/grpc-server
tcp    0.0.0.0:50051     LISTEN   102/grpc-server
tcp    0.0.0.0:9092      LISTEN   118/kafka
tcp    0.0.0.0:6379      LISTEN   134/redis
tcp    0.0.0.0:5432      LISTEN   -/postgres
tcp    0.0.0.0:5672      LISTEN   -/rabbitmq
tcp    0.0.0.0:9090      LISTEN   -/prometheus
```

<br>

## `$ systemctl status current-project`

```text
● ai-infra-platform.service - Multi-Agent Infrastructure & Digital Twin
   Loaded: loaded (/etc/systemd/system/ai-infra-platform.service)
   Active: active (running) since 2026-01-08

   Building an AI-powered network digital twin backed by an event-driven
   pipeline: Kafka for ingestion, Go services for orchestration, Redis
   for hot-path state, and an agentic layer coordinating diagnostics.

   Main PID: 203 (ai-agent)
      Tasks: 12
     Memory: 340.2M
        CPU: 6.734s
```

<br>

## `$ git log --oneline --graph`

```text
* 9c1a2f4 (HEAD -> main) feat: building AI-powered network digital twin
* 6b7e3d1 feat: multi-agent infrastructure for diagnostics
* 4f8d0a9 perf: cut p99 latency on core service by 38%
* 2e9c8b3 feat: distributed cache experiments (Redis Cluster)
* 1a7f6c2 feat: message queue implementations (Kafka, RabbitMQ)
* 0d4b9e7 feat: network automation platform
* 8c3a1f5 feat: high-throughput microservices in Go
* 5f2e0d8 refactor: migrated core services from Java to Go
* 3b1c9a4 feat: airline booking systems at scale
* a0e8d2f init: started shipping backend systems
```

<br>

## `$ cat /proc/learning`

```yaml
learning:
  - Database Internals
  - Consensus Algorithms (Raft, Paxos)
  - Storage Engines (LSM trees, B-trees)
  - Distributed Transactions
  - Kafka Internals

building:
  - AI Infrastructure
  - Agentic Systems
  - Backend Services
  - Open Source Tooling
```

<br>

## `$ cat /var/log/books`

```text
[reading]   Designing Data-Intensive Applications — Martin Kleppmann
[reading]   Database Internals — Alex Petrov
[queued]    TCP/IP Illustrated, Vol. 1 — W. Richard Stevens
```

<br>

## `$ cat /etc/favorites`

```text
editor        : neovim
shell         : zsh
language      : Go
database      : PostgreSQL
queue         : Kafka
os            : Linux
debug_tool    : tcpdump + a lot of patience
```

<br>

## `$ fetch --stats`

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=archit&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00FF88&icon_color=00FF88&text_color=c9d1d9" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=archit&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=00FF88&ring=00FF88&fire=00FF88&currStreakLabel=00FF88" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=archit&theme=github-compact&hide_border=true&bg_color=0d1117&color=00FF88&line=00FF88&point=c9d1d9" width="90%" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=archit&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00FF88&text_color=c9d1d9" />
</p>

<br>

## `$ cat /var/log/contributions.snake`

<p align="center">
  <img src="https://raw.githubusercontent.com/archit/archit/output/github-contribution-grid-snake-dark.svg" alt="snake" />
</p>

> Generated nightly via [`Platane/snk`](https://github.com/Platane/snk) — see the Actions tab to wire up the workflow.

<br>

---

<p align="center">

```bash
archit@github:~$ echo $MISSION
```

```
Build systems that keep working
even when everything else doesn't.
```

```bash
archit@github:~$ logout
```

```
Connection to github closed.
```

</p>
