# 🚗 Catálogo de Carros - API em C#

Este é um projeto simples de **API RESTful** desenvolvido em **C# com ASP.NET Core**, que permite gerenciar um catálogo de carros. O objetivo é praticar a criação de APIs, estruturação em camadas e integração com banco de dados.

## 🔧 Tecnologias Utilizadas

- ASP.NET Core
- Entity Framework Core (EF Core)
- SQLite ou SQL Server
- Swagger (para documentação)
- AutoMapper (opcional)
- LINQ

## 📌 Funcionalidades

- ✅ Cadastrar um novo carro  
- 📄 Listar todos os carros  
- 🔍 Buscar um carro por ID  
- ✏️ Atualizar os dados de um carro  
- ❌ Remover um carro do catálogo  

## 🗂️ Estrutura da API

| Método | Endpoint            | Ação                     |
|--------|---------------------|--------------------------|
| GET    | /api/carros         | Listar todos os carros   |
| GET    | /api/carros/{id}    | Buscar carro por ID      |
| POST   | /api/carros         | Adicionar um novo carro  |
| PUT    | /api/carros/{id}    | Atualizar dados do carro |
| DELETE | /api/carros/{id}    | Remover um carro         |

## ▶️ Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/catalago_carro.git


## 💡 Aprendizados

Este projeto foi desenvolvido com o objetivo de:

- Praticar a criação de APIs REST com C# e ASP.NET Core  
- Aplicar o padrão de camadas (Controller, Service, Repository)  
- Trabalhar com Entity Framework Core e banco de dados  
- Desenvolver uma aplicação realista e funcional
