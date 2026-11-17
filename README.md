# Fagnner Sousa

**Backend engineer — payments infrastructure.**
Rails · PostgreSQL · PIX/TED · idempotency · reconciliation

I build and stabilize systems that move money. Six years in production, mostly Ruby on Rails and PostgreSQL, in domains where a wrong assumption costs real money: payment flows, billing, reconciliation and account limits.

Currently a backend engineer at Jaya Tech, allocated to Syngenta Digital, migrating legacy Python services to Rails 7 and building large-scale geospatial processing with PostGIS and RabbitMQ. Before that: the payments squad at Grafeno (PIX, TED, settlement, collections, account limits) and Governance & Billing at Pipefy (materialized views, real-time revenue capture, usage limits).

I also evaluate AI-generated code and model output at micro1 — rubrics, RLHF, and review of JavaScript, TypeScript and Python. That turns out to be a useful pairing with payments: I can review what agents write before it reaches a ledger.

---

### What I'm good at

| Area | What that means in practice |
|---|---|
| **Payment flows** | Idempotency, webhooks, ledger, reconciliation, retries, audit trails |
| **Rails & PostgreSQL performance** | N+1, composite indexes, materialized views, queues, lock contention |
| **Geospatial data** | PostGIS, large-volume binary processing, optimization algorithms |
| **AI in production** | Evals, guardrails, and reviewing AI-generated code for correctness and security |

### Selected work

- **[production-n8n-postgres-ha](https://github.com/fassousa/production-n8n-postgres-ha)** — fault-tolerant n8n + PostgreSQL stack: queue mode with dedicated workers, PgBouncer in front of Postgres, Redis persistence, Caddy reverse proxy. Built around three specific failure modes (OOM on webhook spikes, connection exhaustion, silent timeouts), not around a tutorial.
- **[currency-converter-ruby](https://github.com/fassousa/currency-converter-ruby)** — Rails 7 API with JWT auth, 190 tests, caching, CI/CD and a real deploy. Written as a technical assessment; kept as a reference for how I structure a Rails service.
- **[fassousa.github.io](https://github.com/fassousa/fassousa.github.io)** — my personal site.

### Stack

`Ruby` `Rails 7` `RSpec` `Sidekiq` `PostgreSQL` `PostGIS` `Redis` `RabbitMQ` `AWS` `Google Cloud` `Docker` `CI/CD` `TypeScript` `Node.js` `Python`

---

<details>
<summary><strong>Português</strong></summary>

<br>

**Engenheiro backend — infraestrutura de pagamentos.**
Rails · PostgreSQL · PIX/TED · idempotência · conciliação

Construo e estabilizo sistemas que movimentam dinheiro. Seis anos em produção, principalmente com Ruby on Rails e PostgreSQL, em domínios onde uma premissa errada custa dinheiro real: fluxos de pagamento, cobrança, conciliação e limites de conta.

Hoje sou engenheiro backend na Jaya Tech, alocado na Syngenta Digital, migrando serviços legados de Python para Rails 7 e construindo processamento de geodados em larga escala com PostGIS e RabbitMQ. Antes: squad de meios de pagamento na Grafeno (PIX, TED, liquidação, cobrança, limites de conta) e Governança & Billing no Pipefy (materialized views, captura de receita em tempo real, limites de uso).

Também avalio código gerado por IA na micro1 — rubricas, RLHF e revisão de JavaScript, TypeScript e Python. É uma combinação útil com pagamentos: sei revisar o que agentes escrevem antes de chegar a um ledger.

**Aberto a** posições sênior de backend (remoto, UTC-3) e contratos em fintechs, SaaS e empresas com fluxo de pagamento crítico.

</details>

---

**Contact** · [LinkedIn](https://www.linkedin.com/in/fagnnersousa/) · sousafagnner@gmail.com · Rio de Janeiro, Brazil (UTC-3)
