# 🐳 Next.js Dockerized App

A minimal example showing a **successfully Dockerized Next.js application** — image built, container running, and app accessible.

---

## ✅ Status

- **Docker Image:** `nextjs-docker:latest`
- **Container:** `nextjs-docker-cont`
- **Status:** Running
- **Port:** `3000:3000`
- **Framework:** Next.js 16.1.1

Docker Desktop confirms:
- Image built successfully
- Container running without errors

---

## 🚀 App Access

`http://localhost:3000`

---

## 🐳 Docker Commands

```bash
# Build the Docker image
docker build -t nextjs-docker .

# Run the container
docker run -p 3000:3000 --name nextjs-docker-cont nextjs-docker

# List running containers
docker ps

# View container logs
docker logs nextjs-docker-cont

# Stop the container
docker stop nextjs-docker-cont

```

## Continer Screenshot

![Docker Image](/screenshots/container.png)

## Image Screenshot

![Docker Image](/screenshots/docker-image.png)