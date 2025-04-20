# Curso .NET 9 + React

Este repositório acompanha um curso prático de **.NET 9**, onde desenvolvemos uma **Web API** explorando os novos recursos do .NET 9 e a integramos com um front-end em **React**.

## O que você vai aprender

- Utilizar os **novos recursos** introduzidos no .NET 9  
- Estruturar o backend seguindo **Clean Architecture**  
- Implementar o padrão **CQRS** com **MediatR**  
- Criar endpoints RESTful seguros e documentados  
- Consumir a API com um aplicativo **React** moderno  

## Tecnologias utilizadas

- **.NET 9** (ASP.NET Core Web API)  
- **Clean Architecture** (Domain, Application, Infrastructure, API)  
- **CQRS** e **MediatR** para separação de comandos e consultas  
- **React** para o front-end  
- **Swagger/OpenAPI** para documentação automática  

## Estrutura do repositório

```plaintext
Tuito/
├── API/            # Projeto Web API (ponto de entrada)
├── Domain/         # Entidades e regras de negócio
├── Application/    # Casos de uso e handlers CQRS
└── Infrastructure/ # Persistência, EF Core, configurações
frontend/           # Código React para consumir a API
