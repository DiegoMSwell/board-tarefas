# Board de Tarefas - API REST

Este projeto é uma API REST para gerenciamento de tarefas, desenvolvida em **Java 17** com **Spring Boot 3**. Ele permite criar, listar, atualizar e excluir tarefas, facilitando a organização e produtividade dos usuários.

##  Tecnologias Utilizadas

- **Java 17** - Versão LTS mais recente, trazendo melhorias de desempenho e novos recursos.
- **Spring Boot 3** - Framework que simplifica o desenvolvimento de aplicações Java.
- **Spring Data JPA** - Abstração para acesso ao banco de dados SQL.
- **OpenAPI (Swagger)** - Documentação interativa da API.
- **Railway** - Plataforma utilizada para deploy na nuvem.

##  Deploy no Railway
O projeto pode ser facilmente implantado no **Railway**. Caso queira fazer o deploy manualmente, siga os passos:
1. Crie uma conta no [Railway](https://railway.app/).
2. Suba o código para um repositório no GitHub.
3. No Railway, conecte seu repositório e configure as variáveis de ambiente para o banco de dados.
4. Deploy automático será iniciado.
   
## Endpoints Principais

| Método | Endpoint       | Descrição                     |
|--------|--------------|-----------------------------|
| GET    | /tarefas      | Lista todas as tarefas      |
| POST   | /tarefas      | Cria uma nova tarefa        |
| PUT    | /tarefas/{id} | Atualiza uma tarefa         |
| DELETE | /tarefas/{id} | Remove uma tarefa          |
