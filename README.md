# desafio-docker-golang
Desafio utizando golang com docker

# Start the docker
```bash 
sudo service docker start
```
# Build the image
```bash 
docker build -t <dockerID>/codeeducation .
```

# Run container
```bash
docker run <dockerID>/codeeducation:latest
```

# Send image to Docker Hub
```bash
docker login
docker push <dockerID>/codeeducation:latest
```