O projeto consiste em uma API de produtos, oferecendo funcionalidades básicas de gerenciamento de produtos, como criação, busca, ordenação, atualização e deleção.

Foi desenvolvido como uma aplicação ASP.NET Core, utilizando o .NET 8.0 e o Entity Framework para interações com o banco de dados, optou-se pela abordagem "Code-First" para modelagem do banco de dados. O banco de dados escolhido foi o SQLite.

Para os testes unitários foi utilizado projeto XUnit e para o Integrado foi utilizado NUnit.

O projeto segue uma estrutura de desenvolvimento utilizando Domain-Driven Design (DDD).

Execução dos comandos
Para gerar novas migrations: Add-Migration "init" -o Persistence\Migrations
Para executar as migrations: Update-Database
