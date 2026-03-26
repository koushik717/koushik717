<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a2a,100:238636&height=200&section=header&text=Venkata%20Koushik%20Nakka&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Distributed%20Systems%20%E2%80%A2%20Backend%20%E2%80%A2%20M.S.%20CS%20%40%20Indiana%20University&descAlignY=60&descSize=15&descColor=8b949e" width="100%"/>
</div>

<div align="center">
  <a href="https://linkedin.com/in/venkata-koushik-nakka-532b80217"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  &nbsp;
  <a href="mailto:venkatakoushik777@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
  &nbsp;
  <a href="https://koushik717.github.io/portfolio"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=github&logoColor=white"/></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=koushik717&style=flat-square&color=238636" alt="profile views"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2500&pause=1000&color=3FB950&center=true&vCenter=true&multiline=false&width=600&lines=Built+Raft+consensus+from+scratch+in+Java+21;Kafka-inspired+MQ+%E2%80%94+ISR+replication+%2B+zero-copy+I%2FO;12%2C000%2B+req%2Fsec+on+AWS+%2B+Kubernetes;Open+source+contributor+%40+canonical%2Fcloud-init;Graduating+May+2026+%E2%80%94+open+to+new+grad+roles" alt="typing"/>
</div>

<br/>

## About

M.S. Computer Science at Indiana University Bloomington — **GPA 3.8/4.0**, graduating May 2026.

I build distributed systems from scratch rather than just consuming them. That means a full Raft consensus implementation with WAL crash recovery, a Kafka-inspired MQ with ISR-based replication and FileChannel zero-copy I/O, and a URL shortener sustaining 12,000+ req/sec with Redis consistent hashing — all running live on real infrastructure.

- Interned at MyEdMaster (HealthTech): sole engineer on a clinical AI platform, cut p99 latency from 4s to 200ms
- Contributed to canonical/cloud-init: [PR #6796](https://github.com/canonical/cloud-init/pull/6796) — added `--timeout` to `cloud-init status --wait`
- Running 3 Docker/Kubernetes stacks on a self-managed DigitalOcean droplet, continuously

---

## Projects

| | Project | What it is | Stack | Links |
|---|---|---|---|---|
| ⚡ | [distributed-kv-store](https://github.com/koushik717/distributed-kv-store) | Raft consensus from scratch — leader election, log replication, WAL crash recovery, linearizable reads/writes at sub-10ms p99 across a 3-node gRPC cluster | Java 21 • gRPC • Protobuf • Kubernetes | [Dashboard](https://kv-store-frontend.vercel.app) |
| 📨 | [distributed-mq](https://github.com/koushik717/distributed-mq) | Kafka-inspired MQ from scratch — partitioned append-only logs, ISR replication, consumer groups with committed-offset tracking, FileChannel zero-copy I/O | Java 17 • Spring Boot • Prometheus • Docker | [Dashboard](https://mq-dashboard-pi.vercel.app) |
| 🔗 | [snaplink](https://github.com/koushik717/snaplink) | High-throughput URL shortener — 12K+ req/sec, 95% Redis cache hit rate, token-bucket rate limiting, HyperLogLog analytics, HPA auto-scaling 1→5 replicas | Java 17 • Spring Boot • Redis • AWS • Terraform • K8s | [Live](http://157.230.83.134:8090) |
| 🤖 | [cf-ai-distsys-tutor](https://github.com/koushik717/cf_ai_distsys_tutor) | Long-horizon AI agent on Cloudflare edge — persistent session memory with async summarization, RAG over distributed systems material, SSE token streaming | TypeScript • Workers AI • Durable Objects | [Live](https://cf-ai-distsys-tutor.venkatakoushik777.workers.dev) |

---

## Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

**Backend & Systems**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

---

## GitHub Stats

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=koushik717&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github&bg_color=0d1117&title_color=3fb950&icon_color=3fb950&text_color=8b949e"/>
  &nbsp;
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=koushik717&layout=compact&theme=github_dark&hide_border=true&langs_count=6&bg_color=0d1117&title_color=3fb950&text_color=8b949e"/>
</div>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=koushik717&theme=github-dark-blue&hide_border=true&background=0d1117&ring=3fb950&fire=3fb950&currStreakLabel=3fb950"/>
</div>

---

## Open Source

**[canonical/cloud-init — PR #6796](https://github.com/canonical/cloud-init/pull/6796)**

Added `--timeout <seconds>` to `cloud-init status --wait`. The existing flag blocks indefinitely with no bound. Using the Unix `timeout` utility as a workaround exits with code 124, conflicting with cloud-init's own exit codes and causing silent failures in CI pipelines. This PR adds a native timeout option. Currently open, under review.

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:238636,50:1a3a2a,100:0d1117&height=100&section=footer" width="100%"/>
</div>
