# Gnana Sai Talla

**Backend Software Engineer | Python | FastAPI | Django | SQL**

I build backend applications and APIs with a focus on reliable data flows, clear service boundaries, and practical problem-solving. My experience includes Python backend development, relational databases, caching, asynchronous processing, search, and API integrations.

I'm especially interested in backend engineering, database design, concurrency, distributed systems, and building services that are maintainable under real-world workloads.

## Featured projects

### [Ticket Booking Service](https://github.com/gnanasai13/ticket-booking-service)
**FastAPI · PostgreSQL · Redis · SQLAlchemy · Docker**

A ticket reservation backend focused on correctness under concurrent requests.

- Implemented temporary seat holds, confirmation, cancellation, expiry, and idempotent reservation workflows.
- Used PostgreSQL row-level locking and a partial unique index to prevent double booking.
- Added expiry processing with `FOR UPDATE SKIP LOCKED`, Redis-backed rate limiting, and an outbox workflow for notification events.
- Payment and notification delivery are explicitly simulated in this portfolio implementation.

### [URL Shortener](https://github.com/gnanasai13/url-shortener)
**FastAPI · MySQL · Redis · Celery · SQLAlchemy**

A modular URL-shortening API with link management and click analytics.

- Implemented JWT authentication, custom aliases, expiry, password-protected links, and owner-scoped URL management.
- Used Redis for redirect caching and rate limiting.
- Moved click recording and expired-link cleanup into Celery background tasks.
- Includes automated tests and CI; see the repository README for the current test and coverage details.

## Technical skills

- **Languages:** Python, Java, C++, JavaScript, SQL
- **Backend:** FastAPI, Django, Flask, REST APIs, asynchronous Python
- **Data & storage:** PostgreSQL, MySQL, Oracle SQL, Redis, Elasticsearch
- **Frontend:** React, Next.js
- **Tools:** Git, Docker, AWS, Jenkins, Postman
- **Practices:** API design, database modelling, automated testing, CI/CD, caching, background jobs

## Engineering interests

- Backend architecture and system design
- Database transactions, concurrency control, and query optimization
- Caching, background processing, and distributed systems
- API reliability, testing, and performance
- Applying AI capabilities in backend products

## Connect

- [LinkedIn](https://www.linkedin.com/in/gnana-sai-talla)
- [GitHub](https://github.com/gnanasai13)
