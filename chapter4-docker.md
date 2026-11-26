
docker build -t edu-api:latest .
docker run -d -p 8000:8000 --name edu-service edu-api:latest
docker ps
docker logs edu-service
