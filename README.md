# Fundamentos de APIs em ASP.NET Core

Este � um projeto desenvolvido como parte do curso "Fundamentos de APIs em ASP.NET Core" na plataforma desenvolvedor.io . Durante este curso, adquiri conhecimento sobre o funcionamento das APIs, todas as funcionalidades essenciais, bem como t�picos avan�ados, incluindo configura��o do Entity Framework, mapeamento de banco de dados com Migrations, valida��o de entidades e seguran�a da API, incluindo autentica��o e autoriza��o com ASP.NET Identity e uso de JWT (JSON Web Tokens) para autenticar e autorizar a API. O projeto foi constru�do seguindo as melhores pr�ticas de desenvolvimento.

## Descri��o do Projeto

Este projeto � uma aplica��o API desenvolvida em ASP.NET Core. Ele demonstra os seguintes t�picos:

- Estrutura de uma API: A aplica��o segue as pr�ticas recomendadas para criar uma API RESTful, incluindo a defini��o de rotas, controladores e endpoints.
- Entity Framework e Migrations: Utilizamos o Entity Framework Core para mapear e interagir com o banco de dados, com suporte a migra��es para manter o esquema do banco de dados atualizado.
- Valida��o de Entidades: Implementamos valida��es para garantir a integridade dos dados recebidos pela API.
- Seguran�a da API: Adicionamos autentica��o e autoriza��o � API usando ASP.NET Identity e JWT, garantindo que apenas usu�rios autenticados e autorizados possam acessar recursos protegidos.
- Boas Pr�ticas: O c�digo-fonte do projeto segue as melhores pr�ticas de desenvolvimento para manter o c�digo limpo, organizado e escal�vel.

## Pr�-requisitos

Antes de executar este projeto, certifique-se de ter as seguintes ferramentas e recursos dispon�veis:

- Visual Studio (ou Visual Studio Code) com suporte ao desenvolvimento ASP.NET Core.
- .NET SDK
- SQL Server (ou outro banco de dados compat�vel)
- Navegador da Web

## Configura��o e Uso

1. Clone este reposit�rio em sua m�quina local.
2. Abra o projeto no Visual Studio (ou Visual Studio Code).
3. Configure a conex�o com o banco de dados no arquivo de configura��o apropriado.
4. Execute as migra��es para criar ou atualizar o banco de dados:

```bash
dotnet ef database update
```

5. Execute a aplica��o:

```bash
dotnet run
```

6. Acesse a API por meio de um cliente REST (como o Postman) ou um navegador da web para testar os endpoints.

## Contato

Se voc� tiver alguma d�vida ou sugest�o, sinta-se � vontade para entrar em contato:

Matheus Fernandes - [matheusfernandesofc@gmail.com](mailto:matheusfernandesofc@gmail.com)

Projeto: [Link para o Projeto no GitHub](https://github.com/cafepng/ApiFuncional)
