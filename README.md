## My Finance


**Sobre** 📃 <br>
My finance uma plataforma desenvolvida para a eficiente gestão financeira de receitas e despesas.
Com funcionalidades de controle de entradas e saídas, você poderá facilmente adicionar, 
editar ou remover contas, além de gerenciar transações e categorias associadas às mesmas. 
Simplificando assim, o controle e organização das suas finanças de forma prática e intuitiva.

**Arquitetura** ⚙️ <br>
MVC (Model View Controller) com camadas Application Services 

**Tecnologias** <br>
ASP.NET (.NET 7)
MySQL Server


## Para instalar o projeto 👨‍💻

passo-a-passo:

1 Clonar o repositório 

2 Instalar os programas: 
- [MySQL Server](https://www.mysql.com/downloads/)
- [Vs code](https://code.visualstudio.com/download)
- [.Net 7](https://dotnet.microsoft.com/pt-br/download)

3 Executar o script de criação do banco de dados (SQL creation file);

4 Inclusão da biblioteca do mySQL no .Net 
    ```dotnet add package Pomelo.EntityFrameworkCore.MySql```

5 Inclusão da biblioteca do Entity no .Net
     ```dotnet add package microsoft.entityframeworkcore.mysql```

6 Acessar a pasta do projeto 
    ```cd myfinance-web-dotnet```
    
7 Executar os comandos 

```dotnet build```

```donet run```
