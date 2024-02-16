# little-daveved-web-app

## Usage

All commands should be from the projects root directory.

### Local Startup

```bash
uvicorn daveved.main:app --port 8001 --host 0.0.0.0 --reload
```

### Docker
```bash
docker build -t little-daveved-web-app .
docker run -p 8001:8001 little-daveved-web-app
```

### Docker Compose
```bash
docker-compose up -d
```

### Docker Hub
```bash
docker pull daveved/little-daveved-web-app
docker run -d -p 8001:8001 daveved/little-daveved-web-app
```