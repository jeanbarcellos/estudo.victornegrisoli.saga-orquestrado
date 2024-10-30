_Repositório apenas para estudo_

# Curso: Arquitetura de Microsserviços: Padrão Saga Orquestrado

_Com Java 17, Spring Boot 3, Apache Kafka, PostgreSQL, MongoDB, Docker e docker-compose!_

Códigos gerado a partir do curso

<br>

**Descrição:**

Neste curso, serão abordados os conceitos de padrões de desenvolvimento de arquitetura de microsserviços em um de seus quesitos mais importantes: lidar com **transações distribuídas** e tratamento de falhas.

Iremos abordar os conceitos teóricos por trás de transações distribuídas, two-phase commit protocol (2PC), padrão Saga Orquestrado e Coreografado, e padrão Outbox.

Neste curso, implementaremos o padrão **Saga Orquestrado** em uma arquitetura de microsserviços com Java 17 e Spring Boot 3.

Para isso, utilizaremos Docker e docker-compose para subir toda a nossa arquitetura com facilidade.

Utilizaremos 2 bancos de dados, **PostgreSQL** e **MongoDB**.

Utilizaremos o Apache Kafka para a comunicação dos eventos e orquestração da nossa **saga**.

Criaremos 5 APIs, em que uma será apenas o orquestrador da saga, 3 microsserviços participantes e um microsserviços de realização de pedido.

Ao final deste curso, você compreenderá as diferenças entre os padrões de microsserviços, os conceitos de transações distribuídas, e como realizar tratativa de erros em diversos serviços, assim como sua implementação.

Você também estará apto a desenvolver aplicações distribuídas com orientação a eventos (Apache Kafka) e trabalhar com Java 17 e o framework Spring Boot na versão 3, porém, o conteúdo do curso é sobre um padrão de arquitetura, e não sobre uma tecnologia específica, ou seja, com o conhecimento adquirido, você conseguirá aplicar a mesma abordagem em qualquer outra tecnologia que permita o desenvolvimento de microsserviços.

**SEÇÃO BÔNUS**

Foi adicionada a Seção 11 como um bônus, realizando a conversão de toda a arquitetura desenvolvida para o Padrão Saga Coreografado, desta forma, os alunos terão o conhecimento de como implementar as duas abordagens do Padrão Saga, e também compreenderão quando implementar cada abordagem dependendo da necessidade.

<br>

**Para quem é este curso:**

- Desenvolvedores Back-End (nível iniciante ou intermediário)
- Desenvolvedores Java (nível iniciante ou intermediário)
- Desenvolvedores Nodejs (nível iniciante ou intermediário)

<br>

**Requisitos**

- Conhecimento básico em Java 1.8+ e no framework Spring Boot
- Conhecimento básico em Docker e docker-compose
- Conhecimento básico em API REST e Microsserviços
- Conhecimento básico sobre mensagerias e Message Brokers

<br>

**Instrutor:**

- [Victor Hugo Negrisoli](https://www.udemy.com/user/victor-hugo-negrisoli/)

**Referências:**

- https://www.udemy.com/course/comunicacao-entre-microsservicos
- https://github.com/vhnegrisoli/curso-udemy-comunicacao-microsservicos

## Conteúdo do curso

- Seção 1: Introdução Teórica - Microsserviços, Transações Distribuídas e Padrão SAGA
- Seção 2: Eventos e Apache Kafka: tudo que precisaremos saber
- Seção 3: Preparando o ambiente de desenvolvimento
- Seção 4: Definindo estruturas em comum entre os microsserviços
- Seção 5: Order-Service: microsserviço de geração de pedidos, o que inicia toda a saga
- Seção 6: Product-Validation-Service: microsserviço para validar os produtos
- Seção 7: Payment-Service: microsserviço para realizar pagamentos
- Seção 8: Inventory-Service: microsserviço de inventário/estoque
- Seção 9: Orchestrator-Service: microsserviço Orquestrador da saga
- Seção 10: Finalização: analisando a arquitetura desenvolvida e o que continuar estudando
- Seção 11: SEÇÃO BÔNUS: convertendo a arquitetura para Saga Coreografado

<br>
