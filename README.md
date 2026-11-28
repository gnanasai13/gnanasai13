# Hi, I'm Gnana Sai Talla

<p>
  <strong>Backend Software Engineer</strong> · Python · FastAPI · Django · SQL
</p>

I enjoy building backend systems that solve practical problems: designing APIs, modelling data, making asynchronous workflows reliable, and handling concurrency and search at scale. My work has included Python services, relational databases, Redis, Elasticsearch, and integrating AI capabilities into applications.

I'm interested in backend engineering, system design, distributed systems, and building products that are useful beyond a demo.

## Featured projects

### [TrustCircle — Community-Powered Scam Intelligence](https://github.com/gnanasai13/trustcircle)

**Python · FastAPI · PostgreSQL · Redis · Celery · Elasticsearch · Next.js · OpenAI**

A platform for investigating suspicious messages and discovering connections between separate reports.

- Built a privacy-aware report pipeline with PII redaction, normalized indicators, and keyed HMAC digests for sensitive identifiers.
- Implemented asynchronous investigation using a transactional outbox, Celery workers, idempotency checks, retries, and failed-event requeue.
- Developed provisional campaign correlation using shared indicators, message fingerprints, token similarity, and OpenAI-generated semantic embeddings.
- Integrated OpenAI-powered structured message classification to identify scam categories and tactics, with evidence-quote validation.
- Added Elasticsearch search, community corroboration, moderation workflows, and audit-backed review.

### [Ticket Booking Service](https://github.com/gnanasai13/ticket-booking-service)

**Python · FastAPI · PostgreSQL · Redis · SQLAlchemy · Docker**

A reservation backend focused on correctness when multiple users try to book the same seat.

- Implemented temporary seat holds, confirmation, cancellation, expiry, and idempotent reservation workflows.
- Used PostgreSQL row-level locking and a partial unique index to prevent double booking.
- Added expiry processing with FOR UPDATE SKIP LOCKED, Redis-backed rate limiting, event caching, and a transactional notification outbox.
- Includes PostgreSQL integration tests and GitHub Actions CI. Payment and notification delivery are explicitly simulated.

### [URL Shortener](https://github.com/gnanasai13/url-shortener)

**Python · FastAPI · MySQL · Redis · Celery · SQLAlchemy**

A modular URL-shortening API with link management and click analytics.

- Implemented JWT authentication, custom aliases, expiry, password-protected links, and owner-scoped URL management.
- Used Redis for redirect caching and rate limiting.
- Moved click recording and expired-link cleanup into Celery background tasks.
- Includes automated tests, database migrations, and GitHub Actions CI.

## Technical skills

| Area | Technologies |
|---|---|
| Languages | Python, Java, C++, JavaScript, SQL |
| Backend | FastAPI, Django, Flask, REST APIs, asynchronous Python |
| Databases & search | PostgreSQL, MySQL, Oracle SQL, Elasticsearch |
| Caching & background jobs | Redis, Celery |
| AI integration | OpenAI API, structured classification, text embeddings |
| Frontend | React, Next.js |
| Tools & delivery | Git, Docker, AWS, Jenkins, Postman, CI/CD |
| Engineering | API design, data modelling, database transactions, concurrency, testing, caching, system design |

## Currently interested in

- Backend architecture and low-level / high-level system design
- Distributed processing, queues, retries, idempotency, and eventual consistency
- Database transactions, concurrency control, and query optimization
- Search, caching, and reliable data pipelines
- Practical AI integration in backend products

## Education

**B.Tech — Indian Institute of Technology Gandhinagar (IIT Gandhinagar)**

## Connect

- [LinkedIn](https://www.linkedin.com/in/gnana-sai-talla)
- [GitHub](https://github.com/gnanasai13)
