# Java-Design-Patterns-Project
# Desafio de Implementação de Padrões de Projeto em Java  Este repositório contém um projeto Java que explora a implementação prática de padrões de projeto comuns. O objetivo é demonstrar como os padrões de projeto podem ser aplicados para melhorar a estrutura e a manutenibilidade do código em projetos Java.



# Arquitetura
Este projeto adota uma arquitetura de software baseada no padrão MVC (Model-View-Controller). O MVC é um padrão de arquitetura de software amplamente utilizado para separar a aplicação em três componentes distintos:



# Padrões
RESTful API
Este projeto segue os princípios de uma API RESTful (Representational State Transfer). Alguns dos princípios fundamentais seguidos incluem:

Uso adequado dos verbos HTTP (GET, POST, PUT, DELETE) para operações CRUD.
Nomes de recursos significativos na URL, como /users para recursos de usuários.
Respostas HTTP apropriadas com códigos de status e representações de recursos em JSON.

## Injeção de Dependência
O projeto utiliza o padrão de Injeção de Dependência, com a ajuda do Spring Framework. Isso permite que as dependências, como o UserService e o UserFactory, sejam injetadas nos controladores, promovendo o desacoplamento e facilitando a manutenção e testabilidade do código.


# Padrão DTO (Data Transfer Object)
Para a comunicação entre a API e o cliente (nesse caso, o Postman), é usado um DTO (Data Transfer Object). O UserDTO é um objeto que transporta os dados entre a API e o cliente, permitindo a validação e manipulação adequada dos dados de entrada.

# Banco de Dados Relacional
O projeto utiliza um banco de dados relacional para armazenar os dados dos usuários. A escolha do banco de dados (por exemplo, MySQL, PostgreSQL, H2) pode ser configurada no arquivo application.properties.

Estes são os principais padrões e princípios arquitetônicos adotados neste projeto Spring Boot. Eles fornecem uma base sólida para o desenvolvimento de APIs escaláveis e de fácil manutenção.
