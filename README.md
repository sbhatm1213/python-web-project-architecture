
## Components

### Nginx

-- Reverse proxy and load handling

-- Serves static files

-- Forwards requests to Gunicorn

### Gunicorn

-- WSGI application server

-- Runs multiple Django worker processes

### Django

-- REST APIs / Web logic

-- Handles business workflows

-- Stores data in PostgreSQL

-- Offloads long-running tasks to Celery

### PostgreSQL

-- Primary relational database

### RabbitMQ

-- Message broker for asynchronous task queue

### Celery Workers

-- Background processing

-- Handles heavy or long-running jobs (reports, integrations, data processing, etc.)
