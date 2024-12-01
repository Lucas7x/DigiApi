# API de Exemplo para Estudos

Uma API simples criada com o objetivo de aprender os conceitos básicos de desenvolvimento de APIs, incluindo rotas, autenticação e operações CRUD.

## Funcionalidades

- Gerenciamento de usuários (CRUD):
  - Criar um usuário
  - Buscar detalhes de um usuário
  - Atualizar informações de um usuário
  - Excluir um usuário
- Autenticação de usuários:
  - Login com geração de token JWT
  - Proteção de rotas com autenticação

## Tecnologias Utilizadas

- **Linguagem**: C# 
- **Framework**: ASP.NET Core
- **Banco de Dados**: SQLite
- **Autenticação**: JSON Web Token (JWT)
- **Ferramenta para testes**: Postman (ou cURL)

## Pré-requisitos

Certifique-se de ter os seguintes itens instalados no seu ambiente:

- [.NET SDK](https://dotnet.microsoft.com/download)
- Um editor de código (recomendo o Visual Studio)
- [Postman](https://www.postman.com/) para testar os endpoints

## Como rodar o projeto

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Lucas7x/DigiApi.git
   cd DigiApi

2. Restaure as dependências:
   dotnet restore

3. Configure o banco de dados (SQLite já configurado por padrão no arquivo appsettings.json):
   - O banco será criado automaticamente na primeira execução do projeto.
     
4. Execute o projeto:
   dotnet run

