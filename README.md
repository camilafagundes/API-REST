# API-REST

Vamos criar as seguintes classes e pacotes:

Model: Define as entidades.

Repository: Define os repositórios JPA para acesso ao banco de dados.

Service: Define a lógica de negócios.

Controller: Define os endpoints da API.

# Executando a Aplicação:

Para executar a aplicação, você pode usar o comando mvn spring-boot:run se estiver usando Maven. 

A API estará disponível em http://localhost:8080.

# Testando a API

Você pode testar os endpoints usando ferramentas como Postman ou cURL.

Aqui estão alguns exemplos de requisições:

GET /alunos: Listar todos os alunos.

GET /alunos/{id}: Obter um aluno específico.

POST /alunos: Criar um novo aluno.

PUT /alunos/{id}: Atualizar um aluno existente.

DELETE /alunos/{id}: Deletar um aluno.

**Repita essas operações para professores e turmas conforme necessário.
