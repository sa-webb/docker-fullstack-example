# Fullstack Docker

From [LinkedIn Learning](https://www.linkedin.com/learning/docker-for-developers-2/)

## Stack

app: Express Server <br/>
client: React client <br/>
mongo: MongoDB <br/>

## Instructions

### Build

`docker-compose up` should build all services without problem.

If problem - start sequentially:

1. `docker-compose up -d mongo`
2. `docker-compose up -d app`
3. `docker-compose up -d client`

### Running

`docker-compose up`

Client - http://localhost:3000

Server - http://localhost:4000