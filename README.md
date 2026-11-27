# Saeed Zeydabadi

**Python Backend Developer**

I’m a Computer Engineering student building Python APIs and event-driven commerce systems. I focus on clear service boundaries, reliable background work, and reproducible delivery.

[LinkedIn](https://www.linkedin.com/in/saeed-zeydabadi/) · [Email](mailto:saeedzed2002@gmail.com)

![Illustration of an API gateway, services, an event stream, and a database](assets/backend-blueprint.png)

## Featured project

### [FastAPI Microservices Platform](https://github.com/saeedzed2002/fastapi-microservices-platform)

A portfolio commerce backend with event-driven workflows for checkout, fulfillment, and post-delivery returns across independently deployable services.

- Services own their PostgreSQL data. An outbox relay publishes events to Kafka, and idempotent consumers handle duplicate delivery.
- GitHub Actions installs the Helm charts in a disposable Kind cluster and runs end-to-end checks for checkout, shipping, and returns.

[Reviewer guide](https://github.com/saeedzed2002/fastapi-microservices-platform/blob/main/docs/portfolio/reviewer-guide.md) · [CI runs](https://github.com/saeedzed2002/fastapi-microservices-platform/actions/workflows/platform-ci.yml)

## Selected work

- **[VOLUMA](https://github.com/saeedzed2002/voluma-architecture)** · Bilingual publishing platform with protected editorial tools, asynchronous media processing, and a repeatable Compose smoke test.
- **[Nosh](https://github.com/saeedzed2002/nosh-ordering-platform)** · Local restaurant-ordering demo with server-enforced checkout rules, customer order tracking, and a role-protected operations workspace.
- **[Nivaro Gaming](https://github.com/saeedzed2002/Nivaro)** · Bilingual hardware storefront backed by six FastAPI services, with simulated checkout and a local backup and restore workflow.
- **[Auremont](https://github.com/saeedzed2002/auremont)** · Django and PostgreSQL demo for a watch storefront.

## Tech stack

<!-- Icon artwork: Skill Icons by tandpfun. See assets/skills/LICENSE. -->
<p>
  <img src="assets/skills/python.svg" alt="Python" title="Python" width="54" height="54" />
  <img src="assets/skills/fastapi.svg" alt="FastAPI" title="FastAPI" width="54" height="54" />
  <img src="assets/skills/django.svg" alt="Django" title="Django" width="54" height="54" />
  <img src="assets/skills/postgresql.svg" alt="PostgreSQL" title="PostgreSQL" width="54" height="54" />
  <img src="assets/skills/redis.svg" alt="Redis" title="Redis" width="54" height="54" />
  <img src="assets/skills/kafka.svg" alt="Apache Kafka" title="Apache Kafka" width="54" height="54" />
  <img src="assets/skills/rabbitmq.svg" alt="RabbitMQ" title="RabbitMQ" width="54" height="54" />
  <img src="assets/skills/docker.svg" alt="Docker" title="Docker" width="54" height="54" />
  <img src="assets/skills/kubernetes.svg" alt="Kubernetes" title="Kubernetes" width="54" height="54" />
  <img src="assets/skills/github-actions.svg" alt="GitHub Actions" title="GitHub Actions" width="54" height="54" />
</p>

`Django REST Framework` · `SQLAlchemy` · `Alembic` · `Pydantic` · `Celery` · `MinIO` · `Docker Compose` · `Helm` · `NGINX` · `pytest` · `Ruff`

## Current focus

Practising idempotency and recovery in event-driven workflows, and making Kubernetes delivery and integration tests repeatable.
