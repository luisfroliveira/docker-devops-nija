## docker-devops-ninja
## Repositório contendo exercício de docker praticado no curso DevOps Ninja <br />

Nesta atividade foi proposto montar uma aplicação com um contador de acessos, a aplicação é composta por 4 conteineres(nginx, node, redis e mysql) que se comunicam entre si dentro de uma EC2 na AWS.<br />

A atividade foi executada da seguinte forma:
- Criação de uma EC2 na AWS <br />
![alt text](imagens/ec2.png)<br />

- Executado o arquivo docker-compose na vm: <br />
```sh
$ docker-compose -f docker-compose.yml up -d
$ docker ps
```
![alt text](imagens/docker.png)<br />

- Aplicação Node rodando no NGINX <br />
![alt text](imagens/node.png)<br />

- Aplicação REDIS comunicando com a API Node <br />
![alt text](imagens/redis.png)<br />
