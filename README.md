# Caching in Django – Property Listings

This project demonstrates how to implement **caching in Django** using **Redis** for improved performance and scalability.  
The example application is a **Property Listings API**, where caching helps reduce database hits and speed up repeated queries.

---

## Features
- Django 5.x project structure
- PostgreSQL as the database
- Redis as the caching backend
- Dockerized setup for PostgreSQL + Redis
- Example `Property` model and listing views
- Cached property queries with `django-redis`
- Configurable cache timeout and invalidation

---

## Tech Stack
- **Backend:** Django, Django REST Framework
- **Database:** PostgreSQL
- **Cache:** Redis (via `django-redis`)
- **Task Queue (optional):** Celery + RabbitMQ
- **Containerization:** Docker & Docker Compose



