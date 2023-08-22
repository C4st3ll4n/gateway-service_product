# API Gateway

Esse serviço é um pedaço do ecosistema de micro serviços de Gerenciamento de Inventário/Produtos.
Sendo esse o serviço de porta de entrada, o API Gateway para acessar os micro serviços de ordem e produto.

### Dependências
* Spring (boot)
* Keycloak
* OAuth2
* Micrometer
* Zipkin
* Spring Security
* Eureka Client

É necessário que tenha um cliente de Keycloak rodando
### Como rodar
`docker compose up`