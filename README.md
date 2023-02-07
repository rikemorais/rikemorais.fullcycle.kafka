# Apache Kafka

Curso de Apache Kafka da Full Cycle

## Módulo 01 - Introdução

## Módulo 02 - Conceitos Básicos na Prática

### Criando Primeiro Tópico

Itens do Docker Compose:

- Zookeeper
- Kafka
- Control Center

Para rodar o Docker-Compose, basta rodar o comando: 

`docker-compose up -d`. 

Para visualizar a lista de Imagens, rode o comando: 

`docker ps` 

Para rodar a imagem específica da lista, use o comando: 

`docker exec -it nome da imagem bash`

Para criar o seu primeiro tópico, use o seguinte comando:

`kafka-topics --create --topic=teste --bootstrap-server=localhost:9092 --partitions=3`

Para listar seus tópicos, use o seguinte comando:

`kafka-topics --list --bootstrap-server=localhost:9092`

Para retornar um resumo dos seus tópico especificado, use o seguinte comando:

`kafka-topics --bootstrap-server=localhost:9092 --topic=teste --describe`

## Módulo 03 - Desenvolvendo Produtor e Consumidor

## Módulo 04 - Kafka Connect

## Módulo 05 - Serviços Gerenciados