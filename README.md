# devopspro-observability

![](imgs/Screenshot_2.png)

### Subir o ambiente
- [x] Docker-compose up -d

### Verificar se ambiente rodando
- [x] docker container ls

### Remover container
- [x] docker container rm -f id-do-container

### Remover todos os containers
- [x] docker rm $(docker ps -a -q)

### Mongodb Exporter
- [x] http://localhost:9216/metrics

### API metrics
- [x] http://localhost:8080/metrics


### DOCKER
#### REMOVER TODAS AS IMAGENS
- docker rmi -f $(docker images -q)

#### REMOVER TODOS OS VOLUMES
- docker volume rm $(docker volume ls -q)
- docker volume prune -f

