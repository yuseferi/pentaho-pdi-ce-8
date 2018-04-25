# pentaho-pdi-ce-8
Pentaho Data Integration 8 Docker image with Ubuntu 14

## How to use
**Note: The instructions below assumes you have [docker](https://docs.docker.com/engine/installation/) and [docker-compose](https://docs.docker.com/compose/install/) installed.**
- Download scripts
```
# git clone https://github.com/zhilevan/pentaho-pdi-ce-8.git
# cd pentaho-pdi-ce-8
```
- Edit .env and/or docker-compose.yml based on your needs
- Start PDI server
```
# docker-compose up -d
```
You should now be able to use admin/password to access the PDI server via [http://localhost:8080/kettle/status](http://localhost:8080/kettle/status).

## How to build
```
# git clone https://github.com/zhilevan/pentaho-pdi-ce-8.git
# cd pentaho-pdi-ce-8
# docker-compose build
```

