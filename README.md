# Directions

## Rails
### Building
```bash
docker build -t app .
docker volume create app-storage
docker run --rm -it --name rails_app -d --network rails -p 3000:3000 app
```
## Wiki
### Building
```
docker compose up -d
```