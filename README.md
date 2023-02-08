# Apache Kafka

Curso de Apache Kafka da Full Cycle

## Módulo 01 - Introdução

## Módulo 02 - Conceitos Básicos na Prática

### Criando Primeiro Tópico

Itens do Docker Compose:

- Zookeeper
- Kafka
- Control Center

Rodando o Docker-Compose: 

`docker-compose up -d`. 

Visualizar a Lista de Imagens: 

`docker ps` 

Rodar uma Imagem Específica da Lista: 

`docker exec -it nome da imagem bash`

Criar o Seu Primeiro Tópico:

`kafka-topics --create --topic=teste --bootstrap-server=localhost:9092 --partitions=3`

Listar Seus Tópicos:

`kafka-topics --list --bootstrap-server=localhost:9092`

Retornar um Resumo dos Seus Tópicos Especificados:

`kafka-topics --bootstrap-server=localhost:9092 --topic=teste --describe`

Consumir um Tópico:

`kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste`

Enviar uma Mensagem:

`kafka-console-producer --bootstrap-server=localhost:9092 --topic=teste`

Consumir um Tópico Desde o Início dos Envios:

`kafka-console-consumer --bootstrap-server=localhost:9092 --topic=teste --from-beginning`

## Módulo 03 - Desenvolvendo Produtor e Consumidor

## Módulo 04 - Kafka Connect

## Módulo 05 - Serviços Gerenciados