<h1 align="center">Hi, I'm Saeed Zeydabadi 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=28&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=840&lines=Backend+Developer;Reliable+APIs+%C2%B7+Commerce+Systems+%C2%B7+Event-Driven+Services;Python+%C2%B7+FastAPI+%C2%B7+Django" alt="Backend Developer" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/saeed-zeydabadi/">LinkedIn</a> · <a href="mailto:saeedzed2002@gmail.com">Email</a>
</p>

I’m a Computer Engineering student building Python APIs and event-driven commerce systems. I focus on clear service boundaries, reliable background work, and reproducible delivery.

![Illustration of an API gateway, services, an event stream, and a database](assets/backend-blueprint.jpg)

## Featured project

### [FastAPI Microservices Platform](https://github.com/saeedzed2002/fastapi-microservices-platform)

A portfolio commerce backend with event-driven workflows for checkout, fulfillment, and post-delivery returns across independently deployable services.

- Services own their PostgreSQL data. An outbox relay publishes events to Kafka, and idempotent consumers handle duplicate delivery.
- GitHub Actions installs the Helm charts in a disposable Kind cluster and runs end-to-end checks for checkout, shipping, and returns.

[Reviewer guide](https://github.com/saeedzed2002/fastapi-microservices-platform/blob/main/docs/portfolio/reviewer-guide.md) · [CI runs](https://github.com/saeedzed2002/fastapi-microservices-platform/actions/workflows/platform-ci.yml)

## Selected work

- **[Nivaro Gaming](https://github.com/saeedzed2002/Nivaro)** · Bilingual hardware storefront backed by six FastAPI services, with simulated checkout and a local backup and restore workflow.
- **[Nosh](https://github.com/saeedzed2002/nosh-ordering-platform)** · Local restaurant-ordering demo with server-enforced checkout rules, customer order tracking, and a role-protected operations workspace.
- **[VOLUMA](https://github.com/saeedzed2002/voluma-architecture)** · Bilingual publishing platform with protected editorial tools, asynchronous media processing, and a repeatable Compose smoke test.
- **[Auremont](https://github.com/saeedzed2002/auremont)** · Django and PostgreSQL demo for a watch storefront.

## Tech stack

<!-- Icon credits: assets/skills/SOURCES.md -->

### Core stack

<p>
  <img src="assets/skills/python.svg" alt="Python" title="Python" width="54" height="54" />
  <img src="assets/skills/django.svg" alt="Django" title="Django" width="54" height="54" />
  <img src="assets/skills/fastapi.svg" alt="FastAPI" title="FastAPI" width="54" height="54" />
  <img src="assets/skills/docker.svg" alt="Docker" title="Docker" width="54" height="54" />
</p>

`Python` · `Django` · `FastAPI` · `Docker`

### APIs & persistence

<p>
  <img src="assets/skills/djangorest.svg" alt="Django REST Framework" title="Django REST Framework" width="54" height="54" />
  <img src="assets/skills/pydantic.svg" alt="Pydantic" title="Pydantic" width="54" height="54" />
  <img src="assets/skills/sqlalchemy.svg" alt="SQLAlchemy" title="SQLAlchemy" width="54" height="54" />
  <img src="assets/skills/jwt.svg" alt="JSON Web Tokens" title="JSON Web Tokens" width="54" height="54" />
</p>

`Django REST Framework` · `Pydantic` · `SQLAlchemy` · `JSON Web Tokens` · `Alembic`

### Databases, caching & storage

<p>
  <img src="assets/skills/postgresql.svg" alt="PostgreSQL" title="PostgreSQL" width="54" height="54" />
  <img src="assets/skills/redis.svg" alt="Redis" title="Redis" width="54" height="54" />
  <img src="assets/skills/minio.svg" alt="MinIO" title="MinIO" width="54" height="54" />
</p>

`PostgreSQL` · `Redis` · `MinIO`

### Messaging & background jobs

<p>
  <img src="assets/skills/kafka.svg" alt="Apache Kafka" title="Apache Kafka" width="54" height="54" />
  <img src="assets/skills/rabbitmq.svg" alt="RabbitMQ" title="RabbitMQ" width="54" height="54" />
  <img src="assets/skills/celery.svg" alt="Celery" title="Celery" width="54" height="54" />
</p>

`Apache Kafka` · `RabbitMQ` · `Celery`

### Containers & infrastructure

<p>
  <img src="assets/skills/docker-compose.svg" alt="Docker Compose" title="Docker Compose" width="54" height="54" />
  <img src="assets/skills/kubernetes.svg" alt="Kubernetes" title="Kubernetes" width="54" height="54" />
  <img src="assets/skills/helm.svg" alt="Helm" title="Helm" width="54" height="54" />
  <img src="assets/skills/nginx.svg" alt="NGINX" title="NGINX" width="54" height="54" />
</p>

`Docker Compose` · `Kubernetes` · `Helm` · `NGINX`

### CI & code quality

<p>
  <img src="assets/skills/github-actions.svg" alt="GitHub Actions" title="GitHub Actions" width="54" height="54" />
  <img src="assets/skills/pytest.svg" alt="pytest" title="pytest" width="54" height="54" />
  <img src="assets/skills/ruff.svg" alt="Ruff" title="Ruff" width="54" height="54" />
</p>

`GitHub Actions` · `pytest` · `Ruff`

## Current focus

Practising idempotency and recovery in event-driven workflows, and making Kubernetes delivery and integration tests repeatable.
