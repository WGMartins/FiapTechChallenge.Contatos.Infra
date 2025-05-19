# FIAP Tech Challenge 

## Tema

O Tech Challenge desta fase será desenvolver um aplicativo utilizando a plataforma .NET 8 para cadastro de contatos regionais, considerando a persistência de dados e a qualidade do software.

## Tecnologias Utilizadas
- BD Postgres
  - PostgreSQL é um sistema de gerenciamento de banco de dados relacional de código aberto, amplamente utilizado por sua robustez e suporte a tipos de dados avançados.
    - Suporte a transações e integridade referencial.
    - Capacidade de escalar horizontalmente.
    - Flexibilidade para lidar com consultas complexas.

- RabbitMQ
  - RabbitMQ é um broker de mensagens que permite a comunicação assíncrona entre serviços.
    - Integração nativa com .NET via bibliotecas como RabbitMQ.Client e MassTransit.
    - Suporte a roteamento avançado com exchanges (direct, topic, fanout).
    - Alta confiabilidade com filas persistentes e entrega garantida de mensagens.
   
- Azure AKS
  - AKS é o serviço gerenciado de Kubernetes da Azure, ideal para orquestrar contêineres.
    - Gerenciamento automatizado de clusters, com escalabilidade e atualizações simplificadas.
    - Integração nativa com outros serviços Azure, como Monitor, Key Vault e Load Balancer.
    - Alta disponibilidade e resiliência com balanceamento de carga e auto-recovery.
   
- Kong Gateway
  - Kong é uma API Gateway leve e extensível para gerenciamento de APIs.
    - Permite controle de tráfego, autenticação, rate limiting e logging centralizado.
    - Suporte a plugins personalizáveis e integração com serviços como OAuth2 e JWT.
    - Compatível com ambientes Kubernetes, facilitando o roteamento em microsserviços.
