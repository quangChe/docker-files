# Lib of Docker Scripts

## Image Scripts

Useful Dockerfiles for building reusable images through Docker.
```
cd images
docker build -t SAMPLE_USER/TARGET_IMAGE:latest /TARGET_IMAGE
docker run SAMPLE_USER/TARGET_IMAGE
```

## Compose Scripts

Useful YAML scripts that can be reused to build and run multiple simultaneous containers through Docker Compose.
```
cd compose/TARGET_COMPOSE_PROJECT
docker-compose up --build
```