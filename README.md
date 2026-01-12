# 🐳 Docker Assignment: Next.js & FastAPI

A comprehensive example showing **successfully Dockerized Next.js and FastAPI applications** — images built, containers running, and apps accessible.

---

## ✅ Status

### Next.js App
- **Docker Image:** `nextjs-docker:latest`
- **Container:** `nextjs-docker-cont`
- **Status:** Running
- **Port:** `3000:3000`
- **Framework:** Next.js 16.1.1

### FastAPI App
- **Docker Image:** `fastapi-docker:latest`
- **Container:** `fastapi-docker-cont`
- **Status:** Running
- **Port:** `8000:8000`
- **Framework:** FastAPI

Docker Desktop confirms:
- Images built successfully
- Containers running without errors

---

## 🚀 App Access

- **Next.js:** `http://localhost:3000`
- **FastAPI:** `http://localhost:8000`

---

## 🐳 Docker Commands

### Next.js

```bash
cd nextjs-docker

# Build the Docker image
docker build -t nextjs-docker .

# Run the container
docker run -p 3000:3000 --name nextjs-docker-cont nextjs-docker
```

### FastAPI

```bash
cd fastapi-docker

# Build the Docker image
docker build -t fastapi-docker .

# Run the container
docker run -p 8000:8000 --name fastapi-docker-cont fastapi-docker
```

---

## 📸 Screenshots

### Next.js
![Next.js Container](/nextjs-docker/screenshots/container.png)
![Next.js Image](/nextjs-docker/screenshots/docker-image.png)

### FastAPI
![FastAPI Container](/fastapi-docker/screenshots/container.png)
![FastAPI Image](/fastapi-docker/screenshots/docker-image.png)