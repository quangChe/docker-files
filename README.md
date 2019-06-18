# Lib of Docker Scripts

## Image Scripts

Useful Dockerfiles for building reusable images through Docker.

### To Start:
```
cd images
docker build -t SAMPLE_USER/TARGET_IMAGE:latest /TARGET_IMAGE
docker run SAMPLE_USER/TARGET_IMAGE
```

### To Stop: 
```
docker stop CONTAINER_ID
```

## Compose Scripts

Useful YAML scripts that can be reused to build and run multiple simultaneous containers through Docker Compose.

### To Start:
```
cd compose/TARGET_COMPOSE_PROJECT
docker-compose up -d --build
```

### To Stop:
```
docker-compose down 
```