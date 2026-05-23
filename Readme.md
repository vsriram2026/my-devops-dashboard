# My Dashboard

A simple containerized dashboard project built using Docker and NGINX.

## Features
- Static webpage deployment
- Docker containerization
- Port mapping
- NGINX web server

## Run locally

```bash
docker build -t my-dashboard .
docker run -p 8080:80 my-dashboard
```

Then open:
http://localhost:8080