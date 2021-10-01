# sitkmutt-static-web

## How to run with Docker

```bash
# Build Docker Image for static web
docker build -t web .

# Run static web on port 8080
docker run -d --name web -p 8080:80 web
```

## How to run with Docker Compose

```bash
docker-compose up
```
