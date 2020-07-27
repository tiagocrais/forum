# Linguagem Java
- Aplicação Java com o Spring Boot;
- Projeto Maven;
- Arquitetura REST.
## Infraestrutura básica do projeto:
- Instalação do Java JDK/JVM;
- Java versão 8 (JavaSE-1.8) ou superior.
- Importar na IDE como projeto Maven (existing maven projects);
## Projeto - forum
### Funcionalidade:
- Um forum sobre cursos.
### Execução:
- No projeto, executar Run as em 'ForumApplication' (Run Forum Application);
### Execução Banco de dados H2:
- http://localhost:8080/h2-console
### api:
- #### Consumo do endpoint (Browser ou Postman):
- GET localhost:8080/topicos;
- GET localhost:8080/topicos/3;
- POST localhost:8080/topicos:
  - Headers:
    - Content-Type
    - application/json
  - Body:
  - {
      "titulo":
      "mensagem":
      "nomeCurso":
    }
- PUT localhost:8080/topicos/3:
  - Headers:
    - Content-Type
    - application/json
  - Body:
    - {
        "titulo":
        "mensagem":
      }
 - DEL localhost:8080/topicos/2
