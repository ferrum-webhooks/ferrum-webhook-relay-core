# ferrum-webhook-relay-phase1 (archived)

The first iteration of **Ferrum**: a synchronous FastAPI + PostgreSQL + Redis-cache monolith. Kept for history; not built, deployed or maintained.

It was split and substantially reworked into:

| This repository | Became |
|---|---|
| API, auth, CRUD, cache | [`ferrum-webhook-gateway`](https://github.com/pratishtha-abrol/ferrum-webhook-gateway) |
| (no delivery yet) | [`ferrum-webhook-worker`](https://github.com/pratishtha-abrol/ferrum-webhook-worker): outbox relay, Redis Streams consumer, scheduled retries |
| Docker and compose files | [`infra`](https://github.com/pratishtha-abrol/infra) |

What changed and why (durability, idempotency, security, observability, measured performance) is told in the engineering notes of the umbrella repository's `docs/engineering/`.

MIT licensed.
