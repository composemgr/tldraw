## 👋 Welcome to tldraw 🚀

Collaborative whiteboard and drawing application

## 📋 Description

Collaborative whiteboard and drawing application

## 🚀 Services

- **tldraw**: tldraw/tldraw:latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/tldraw/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/tldraw" ~/.local/srv/docker/tldraw
cd ~/.local/srv/docker/tldraw
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install tldraw
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
SERVICE_USER=1000
SERVICE_GROUP=1000
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:3004

## 📂 Volumes

- `./volumes/config/tldraw` - Data storage
- `./volumes/data/tldraw` - Data storage

## 🔍 Logging

```shell
docker compose logs -f tldraw
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
