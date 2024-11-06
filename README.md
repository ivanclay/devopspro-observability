# Observability with Prometheus and Grafana

![Badge de Status do Projeto](https://img.shields.io/badge/status-training-blue.svg?style=flat-square)
![Badge de Licença](https://img.shields.io/badge/Swagger-X.X.X-blue.svg?style=flat-square&logo=swagger)
![Badge de Licença](https://img.shields.io/badge/Prometheus-X.X.X-blue.svg?style=flat-square&logo=prometheus)
![Badge de Licença](https://img.shields.io/badge/Grafana-X.X.X-blue.svg?style=flat-square&logo=grafana)
![Badge de Licença](https://img.shields.io/badge/Docker-X.X.X-blue.svg?style=flat-square&logo=docker)
![Badge de Versão](https://img.shields.io/badge/app-v_1.0.0-green.svg?style=flat-square&logo=app)

![](imgs/Screenshot_2.png)

### Start the environment
- [x] Docker-compose up -d

### Check if environment is running
- [x] docker container ls

### Remove container
- [x] docker container rm -f id-do-container

### Remove all containers
- [x] docker rm $(docker ps -a -q)

### Mongodb Exporter
- [x] http://localhost:9216/metrics

### API metrics
- [x] http://localhost:8080/metrics


### DOCKER
#### REMOVE ALL IMAGES
- docker rmi -f $(docker images -q)

#### REMOVE ALL VOLUMES
- docker volume rm $(docker volume ls -q)
- docker volume prune -f

